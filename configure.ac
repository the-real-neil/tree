# tree/configure.ac

AC_PREREQ([2.68])
AC_INIT([tree],
        [1.7.0],
        [ice+tree@mama.indstate.edu],
        [tree],
        [http://mama.indstate.edu/users/ice/tree/])
AC_LANG_PUSH([C])
AC_CONFIG_SRCDIR([tree.h])
AC_CONFIG_HEADERS([config.h])

AC_CONFIG_MACRO_DIR([m4])

AM_INIT_AUTOMAKE([subdir-objects])



# Checks for programs.
AC_PROG_CC_C99

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([langinfo.h limits.h locale.h stdlib.h string.h strings.h sys/time.h unistd.h wchar.h wctype.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_TYPE_UID_T
AC_C_INLINE
AC_TYPE_MODE_T
AC_TYPE_OFF_T
AC_TYPE_SIZE_T

# Checks for library functions.
AC_FUNC_LSTAT_FOLLOWS_SLASHED_SYMLINK
AC_FUNC_MALLOC
AC_FUNC_REALLOC
AC_FUNC_STRCOLL
AC_CHECK_FUNCS([getcwd iswprint memset nl_langinfo setlocale strcasecmp strchr strtoul strverscmp])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
