#
# Process this file with autogen to produce a configure script.
#

AC_PREREQ(2.52)

AC_INIT([Apertium English], [0.1.0], [francis.tyers@gmail.com], [apertium-eng], [http://wiki.apertium.org/wiki/Apertium-eng])
AM_INIT_AUTOMAKE

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.6.0)
PKG_CHECK_MODULES(LTTOOLBOX, lttoolbox >= 3.5.0)
PKG_CHECK_MODULES(CG3, cg3 >= 1.3.0)

AP_MKINCLUDE

AC_OUTPUT([Makefile apertium-eng.pc])
