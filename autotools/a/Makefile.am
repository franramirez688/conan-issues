# We're going to compile one libtool library, installed to ${libdir},
# and named libhelloworld.
lib_LTLIBRARIES = libhelloworld.la

# List the source files used by libhelloworld.
libhelloworld_la_SOURCES = helloworld.c
libhelloworld_la_LDFLAGS = -avoid-version

# We install a single header file to ${includedir}
include_HEADERS = helloworld.h
