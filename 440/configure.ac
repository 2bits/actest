AC_INIT
AC_CONFIG_HEADERS(config.h:config.hin)
AC_STATE_SAVE(before)
AC_DIAGNOSE([obsolete],[Remove this warning and
`AC_CHECK_HEADER(memory.h, AC_DEFINE(...))' when you adjust your code to
use HAVE_STRING_H and HAVE_MEMORY_H, not NEED_MEMORY_H.])dnl
AC_CHECK_HEADER([memory.h],[AC_DEFINE([NEED_MEMORY_H], 1,
			   [Same as `HAVE_MEMORY_H', don't depend on me.])])
AC_CHECK_HEADERS([string.h memory.h])
AC_OUTPUT
AC_STATE_SAVE(after)
