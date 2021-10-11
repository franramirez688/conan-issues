# Make sure we can find the uninstalled header file.
AM_CPPFLAGS = -I$(top_srcdir)/a

# Compile one program, called foo, and installed to ${bindir}, with a single C
# source file.
bin_PROGRAMS = foo
foo_SOURCES = foo.c

# Link against our uninstalled copy of libhelloworld.
foo_LDADD = $(top_builddir)/a/libhelloworld.la
