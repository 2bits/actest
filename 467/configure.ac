AC_INIT
AC_CONFIG_HEADERS(config.h:config.hin)
AC_STATE_SAVE(before)
AC_DIAGNOSE([obsolete],[your code should no longer depend upon `HAVE_ST_BLKSIZE', but
`HAVE_STRUCT_STAT_ST_BLKSIZE'.  Remove this warning and
the `AC_DEFINE' when you adjust the code.])dnl
AC_CHECK_MEMBERS([struct stat.st_blksize],[AC_DEFINE(HAVE_ST_BLKSIZE, 1,
			    [Define to 1 if your `struct stat' has
			     `st_blksize'.  Deprecated, use
			     `HAVE_STRUCT_STAT_ST_BLKSIZE' instead.])])

AC_OUTPUT
AC_STATE_SAVE(after)
