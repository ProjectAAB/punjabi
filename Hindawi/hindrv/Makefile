#Copyright (C) 2006 Abhishek Choudhary
#This file is part of the Hindawi Indic Programming System.
#
#The Hindawi Indic Programming System is free software; 
#you can redistribute it and/or modify it under the terms of the 
#GNU General Public License as published by the 
#Free Software Foundation; either version 2 of the License, or 
#(at your option) any later version.
#
#The Hindawi Indic Programming System is distributed in the hope 
#that it will be useful, but WITHOUT ANY WARRANTY; without 
#even the implied warranty of MERCHANTABILITY or FITNESS FOR 
#A PARTICULAR PURPOSE. See the GNU General Public License for 
#more details.
#
#You should have received a copy of the GNU General Public
#License along with this file; see the file COPYING. If
#not, write to the Free Software Foundation,
#51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA
#
#Modifications: (Please maintain in reverse chronological order)
#
#  dd-mmm-yyyy, Nature of change,
#                 Changed by <alias>,
#                 email@server.tld
#
#  31-Jul-2006, Created makefile, Ver. 0.2.0,
#                 Abhishek Choudhary <hi_pedler>,
#                 choudhary@indicybers.net

#Makefile for Hindawi Indic Programming System Ver. 0.2.0 - hindrv

EXECDIR=/usr/bin

all:

clean_all: clean

clean:

install:
	install hincc $(INSTROOT)$(EXECDIR)/hincc
	install hincc.awk $(INSTROOT)$(EXECDIR)/hincc.awk
	install hin2std $(INSTROOT)$(EXECDIR)/hin2std
	install hin2std.awk $(INSTROOT)$(EXECDIR)/hin2std.awk
	install std2hin $(INSTROOT)$(EXECDIR)/std2hin
	install std2hin.awk $(INSTROOT)$(EXECDIR)/std2hin.awk

uninstall:
	rm $(INSTROOT)$(EXECDIR)/hincc
	rm $(INSTROOT)$(EXECDIR)/hincc.awk
	rm $(INSTROOT)$(EXECDIR)/hin2std
	rm $(INSTROOT)$(EXECDIR)/hin2std.awk
	rm $(INSTROOT)$(EXECDIR)/std2hin
	rm $(INSTROOT)$(EXECDIR)/std2hin.awk
	
