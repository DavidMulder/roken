AC_PREREQ(2.62)
AC_INIT([roken], 1.0)
AC_CONFIG_MACRO_DIR([cf])
AC_CONFIG_HEADERS(include/config.h)

AM_INIT_AUTOMAKE([foreign 1.11])

LT_PREREQ([2.2])
LT_INIT

AC_PROG_CC

m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

rk_ROKEN(src)
rk_VERSIONSCRIPT

AC_CONFIG_FILES(Makefile include/Makefile src/Makefile)
AC_OUTPUT
