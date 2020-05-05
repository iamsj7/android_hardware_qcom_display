#                                               -*- Autoconf -*-
<<<<<<< HEAD
# configure.ac -- Autoconf script for sdm
=======
# configure.ac -- Autoconf script for display commonsys intf
>>>>>>> 05e4a006396d7e1e136d52a9314f1426a62e1e87
#

# Process this file with autoconf to produce a configure script

# Requires autoconf tool later than 2.61
AC_PREREQ(2.61)
<<<<<<< HEAD
# Initialize the display package version 1.0.0
AC_INIT([display],1.0.0)
=======
# Initialize the display commonsys intf package version 1.0.0
AC_INIT([disp-commonsys-intf],1.0.0)
>>>>>>> 05e4a006396d7e1e136d52a9314f1426a62e1e87
# Does not strictly follow GNU Coding standards
AM_INIT_AUTOMAKE([foreign])
# Disables auto rebuilding of configure, Makefile.ins
AM_MAINTAINER_MODE
# defines some macros variable to be included by source
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIR([m4])
<<<<<<< HEAD
AC_SUBST([COMMON_CFLAGS], [-Wall -Werror -Wno-sign-conversion -Wconversion -DDEBUG_CALC_FPS])
=======
>>>>>>> 05e4a006396d7e1e136d52a9314f1426a62e1e87
AC_SUBST([AM_CPPFLAGS], [--std=c++11])

AC_ARG_WITH([core_includes],
    AC_HELP_STRING([--with-core-includes=@<:@dir@:>@],
       [Specify the location of the core headers]),
    [core_incdir=$withval],
    with_core_includes=no)

if test "x$with_core_includes" != "xno"; then
   CFLAGS="${CFLAGS} -I${core_incdir}"
fi

AC_ARG_WITH(sanitized-headers,
   AS_HELP_STRING([--with-sanitized-headers=DIR],
       [Specify the location of the sanitized Linux headers]),
<<<<<<< HEAD
   [CPPFLAGS="$CPPFLAGS -idirafter $withval"])
=======
   [CPPFLAGS="$CPPFLAGS -I$withval"])
>>>>>>> 05e4a006396d7e1e136d52a9314f1426a62e1e87

# Checks for programs.
AC_PROG_CC
AM_PROG_CC_C_O
AC_PROG_CXX
AC_PROG_LIBTOOL
AC_PROG_AWK
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET

AC_SUBST([CFLAGS])
AC_SUBST([CC])
AC_CONFIG_FILES([ \
        Makefile \
<<<<<<< HEAD
        libqservice/Makefile \
        libqdutils/Makefile \
        sdm/libs/utils/Makefile \
        sdm/libs/core/Makefile
=======
        libqdmetadata/Makefile
>>>>>>> 05e4a006396d7e1e136d52a9314f1426a62e1e87
        ])
AC_OUTPUT
