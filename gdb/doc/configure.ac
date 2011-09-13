AC_PREREQ(2.64)
AC_INIT(refcard.tex)
sinclude(../../config/acx.m4)
AC_PROG_INSTALL
AC_PROG_LN_S

READLINE_TEXI_INCFLAG='-I $(READLINE_DIR)'
AC_SUBST(READLINE_TEXI_INCFLAG)

ACX_PKGVERSION([GDB])
ACX_BUGURL([http://www.gnu.org/software/gdb/bugs/])
AC_OUTPUT(Makefile)
