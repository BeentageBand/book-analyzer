# Release version
m4_define([package_version_major],[1])
m4_define([package_version_minor],[0])
m4_define([package_version_micro],[0])

# API version
m4_define([api_version],[1])

# Initialize
AC_INIT([book-analyzer], [package_version_major.package_version_minor.package_version_micro], [beentageband@gmail.com])

# Dependencies
PKG_PROG_PKG_CONFIG
PKG_INSTALLDIR

AC_SUBST([PACKAGE_VERSION_MAJOR],package_version_major)
AC_SUBST([PACKAGE_VERSION_MINOR],package_version_minor)
AC_SUBST([PACKAGE_VERSION_MICRO],package_version_micro)
AC_SUBST([API_VERSION],api_version)


# Autotools aux files
AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_MACRO_DIR([m4])

# Automake config files
AM_INIT_AUTOMAKE([-Wall -Werror foreign subdir-objects])
AC_CONFIG_FILES([Makefile])

# Safety check
AC_CONFIG_SRCDIR([src/book-analyzer.cc])

# Compiler flags
AC_PROG_CXX
AM_PROG_AR

# Libtool

# Output
AC_OUTPUT
