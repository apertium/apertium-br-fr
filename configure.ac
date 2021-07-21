AC_PREREQ(2.52)

AC_INIT([apertium-br-fr], [0.5.1], [apertium-stuff@lists.sourceforge.net])
AM_INIT_AUTOMAKE
AC_PROG_AWK

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.7.1)
PKG_CHECK_MODULES(CG3, cg3 >= 1.3.2)
PKG_CHECK_MODULES(APERTIUM_RECURSIVE, apertium-recursive >= 1.0.0)
PKG_CHECK_MODULES(APERTIUM_SEPARABLE, apertium-separable >= 0.3.3)
PKG_CHECK_MODULES(APERTIUM_LEX_TOOLS, apertium-lex-tools >= 0.2.3)

PKG_CHECK_MODULES(REGTEST, apertium-regtest >= 0.0.1, [],
                  [AC_MSG_WARN([Running tests requires apertium-regtest])])

AP_MKINCLUDE

AC_OUTPUT([Makefile])
