
AM_CFLAGS = -O2 -Wall @CFLAGS@ -I$(top_builddir) -I$(top_srcdir) 
METASOURCES = AUTO
bin_PROGRAMS = g15macro
EXTRA_DIST = g15macro.wbmp

docdir = $(prefix)/share/doc/$(PACKAGE)-$(VERSION)
doc_DATA = README ChangeLog AUTHORS NEWS COPYING

imagedir = $(prefix)/share/g15macro/splash
image_DATA = ${top_builddir}/g15macro.wbmp

LIBS = -lg15daemon_client -lg15render -lX11 -lXtst -lpthread -lm
IMCLUDES = -I
g15macro_SOURCES =  g15macro.c fileHandling.c


noinst_HEADERS = g15macro.h
