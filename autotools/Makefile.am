# Compile two subdirectories.  We need to compile A/ first so the shared library is
# available to link against.
SUBDIRS = a b

# libtool requires some M4 scripts to be added to the source tree.  Make sure that
# Autoconf knows where to find them.
ACLOCAL_AMFLAGS = -I m4
