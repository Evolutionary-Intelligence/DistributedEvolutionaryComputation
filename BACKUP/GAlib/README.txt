Matthew's GAlib: A C++ Genetic Algorithm Library
Copyright (c) 1994-1996 Massachusetts Institute of Technology
Copyright (c) 1996-2007 Matthew Wall

GAlib is a C++ library of genetic algorithm objects.  With GAlib you 
can add genetic algorithm optimization to your program using any data 
representation and standard or custom selection, replacement, crossover, 
mutation, scaling, and termination methods.  The GAlib distribution 
includes a description of the programming interface, features, and 
examples.  GAlib version 2.4 and later includes examples illustrating 
the use of GAlib with PVM for distributed (parallel) genetic algorithms 
on various networked UNIX and Windows platforms.

Announcements Mailing List: galib-announce
Discussion Mailing List: galib
Documentation: http://lancet.mit.edu/ga/ 
Source: http://lancet.mit.edu/ga/dist

To subscribe to one of the mailing lists, send email to
LISTNAME-request@mit.edu with the word 'subscribe' in the subject line
and nothing in the body of the email.

This directory contains UNIX (.tar.gz), MacOS (.hqx), and DOS (.zip) 
versions of the GA library.  Once you have downloaded the file, 
uncompress and extract it.  It will expand to its own directory.

Also in this directory are extensive documentation, project files for
some platforms and graphic examples for windows:

  gademo.zip                 graphic 2D function demo for windows
  tspdemo.zip                graphic travelling salesperson demo for windows
  galib-projects.sit         project file(s) for metrowerks on macos
  gadoc.pdf                  documentation in PDF format
  gadoc.ps.gz                documentation in PostScript format (compressed)
  project-files              directory with various project files

GAlib requires a cfront 3.0 compatible C++ compiler.  Here are some of
the systems on which GAlib has been used:

	DEC MIPS ultrix 4.2	g++ 2.6.8, 2.7.x
	DEC ALPHA		g++ 2.7.x, 2.8.x
	IBM RSAIX 3.2		g++ 2.6.8, 2.7.x
	SUN SOLARIS 2.3		g++ 2.6.8, 2.7.x
	SUN OS 5.3		g++ 2.6.3; SunSoft c++ 3.0.1
	HP-UX			g++ 2.6.8, 2.7.x
	LINUX			g++ 2.7.x
	SGI IRIX 5.x		g++ 2.6.8, 2.7.x, 2.8.x; DCC 1.0
	SGI IRIX 4.0.x		cfront 3.0
	MacOS			THINK 7.0; MetroWerks 7-11, pro 3
	DOS/Windows		Borland Turbo C++ 3.1, 4.5; MS VC++ 2.2, 5.0
        MacOSX                  g++ 2, 3, 4
        Ubuntu, Debian, RH      g++ 2, 3, 4

GAlib is free under the terms of a BSD-style license.  See the COPYRIGHT
file in the distribution for details.
