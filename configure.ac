#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.68])
AC_INIT([niagara], [0.1], [angelo.marletta@gmail.com])
AC_CONFIG_FILES([Makefile src/Makefile])
AM_INIT_AUTOMAKE

AC_CONFIG_SRCDIR([src/niagara.c])

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([fcntl.h netdb.h stdlib.h string.h sys/socket.h sys/time.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_FUNC_ERROR_AT_LINE
AC_CHECK_FUNCS([memset socket strchr strstr strtol])

AC_OUTPUT
#(Makefile src/Makefile)
