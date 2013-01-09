::2012.10.18 (yyy.mm.dd)::

This directory contains the Multiplo's software and some third party software tools. It has the following subdirs:

CodeBlocks-RG:	This is the complete IDE + Toolchain + libraries, ready to compile Minibloq and other wxWidgets projects with GCC.
				To use it, please uncompress the zip file in your destination directory, and run codeblocks.exe. If you want to
				compile Minibloq, you need to go to Minibloq's subdir, uncompress the sources (over a valid Minibloq installation),
				open the workspace and Rebuild it. It should be completely rebuilt in about 2 minutes, with 0 warnings.
				
DuinoPack:		This is the Arduino IDE 0022 with the necessary extra files to work with the DuinoBot.v1.2, including sensors
				and motors libraries and the DuinoBot core. It works as the standard Arduino IDE (more documentation here: 
				http://arduino.cc/en/Guide/HomePage). You should select the DuinoBot in the boards menu. This package includes
				examples to work with Multiplo's controller: please go to menu File->Examples->9.Multiplo.
				
Minibloq:		This directory contains the last version of Minibloq. Minibloq's comes in 2 distributions:
				
				- Windows installer version (Minibloq.v0.81.Beta.UP2.msw.exe).
				- Installation-free, multiple-OS version (Minibloq.v0.81.Beta.UP2.zip)
				We also included the Croatian translation package, because it was contributed by a user after we published the 
				last version of Minibloq (Minibloq.hr.20120907.zip).
				
				Finally, the sources are here too: Minibloq.v0.81.Beta.UP2.Sources.zip. To use them, you should unzip this file
				over a previous installation of Minibloq.
				
				For further documention on how to install, please take a look to this page: http://blog.minibloq.org/p/download.html
