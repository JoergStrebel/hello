#                                               -*- Autoconf -*-
#
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT(Hello, 1.0, joerg.strebel@gmail.com)
AC_CONFIG_SRCDIR([src/hello.c])
#AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE([1.11])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.
AC_CHECK_LIB(m,sqrt)

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h unistd.h math.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_FUNC_MALLOC
AC_CHECK_FUNCS([sqrt])
AC_CONFIG_FILES([Makefile src/Makefile doc/Makefile man/Makefile script/Makefile])
AC_OUTPUT

