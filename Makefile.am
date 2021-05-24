ACLOCAL_AMFLAGS = -I m4
bin_PROGRAMS = objpol

objpol_SOURCES = program.c pole.c objetosc.c pole.h objetosc.h
objpol_CFLAGS = $(AM_CFLAGS)

objpol_DEPENDENCIES = libobj.la
lib_LTLIBRARIES = libobj.la
libobj_la_SOURCES = pole.c objetosc.c pole.h objetosc.h
libobj_la_LDFLAGS = -version-info 1:0:0
objpol_LDADD= libobj.la
objpol_LDFLAGS = -rpath /usr/local/lib
# -module -avoid-version -shared #/usr/local/lib # -rpath
#clean local:
#	@rm objpol

