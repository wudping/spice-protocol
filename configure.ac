AC_PREREQ([2.57])

m4_define([SPICE_MAJOR], 0)
m4_define([SPICE_MINOR], 14)
m4_define([SPICE_MICRO], 0)

AC_INIT(spice-protocol, [SPICE_MAJOR.SPICE_MINOR.SPICE_MICRO], [], spice-protocol)

AC_CONFIG_MACRO_DIR([m4])
AM_CONFIG_HEADER([config.h])

AM_INIT_AUTOMAKE([foreign dist-bzip2])
AM_MAINTAINER_MODE

m4_ifdef([AM_SILENT_RULES],[AM_SILENT_RULES([yes])])

AC_OUTPUT([
Makefile
spice-protocol.pc
spice/Makefile
])
