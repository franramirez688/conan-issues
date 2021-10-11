AC_INIT([libhelloworld], 1, peter@peter-b.co.uk)

# This is used to help configure check whether the source code is actually present, and
# that it isn't being run from some random directory.
AC_CONFIG_SRCDIR([a/helloworld.c])

# Put M4 macros in the m4/ subdirectory.
AC_CONFIG_MACRO_DIR([m4])

# We're using automake, but we want to turn off complaints about missing README files
# etc., so we need the "foreign" option.
AM_INIT_AUTOMAKE([foreign])

# We need a C compiler
AC_PROG_CC

LT_INIT

# configure needs to generate three Makefiles.
AC_CONFIG_FILES([a/Makefile
                 b/Makefile
                 Makefile])
AC_OUTPUT