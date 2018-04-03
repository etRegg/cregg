AC_PREREQ(2.61)
AC_INIT(cregg, 0.01, gimenezgiaimo.rodrigo@gmail.com)
AC_CANONICAL_SYSTEM
AC_CONFIG_SRCDIR([src/mul.c])
AM_INIT_AUTOMAKE
AM_MAINTAINER_MODE
AC_CONFIG_HEADER(mul.h)

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_MAKE_SET

AC_CHECK_LIB([pthread], [pthread_create])
AC_CHECK_LIB([m],[cos])
CFLAGS="   -Wall -o  $CFLAGS  "

AC_CONFIG_FILES([Makefile])
AC_OUTPUT

echo "
  $PACKAGE_NAME version $PACKAGE_VERSION
  Prefix.........: $prefix
  Debug Build....: $debug
  C Compiler.....: $CC $CFLAGS $CPPFLAGS
  Linker.........: $LD $LDFLAGS $LIBS
"
