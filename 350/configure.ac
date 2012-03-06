AC_INIT
AC_CONFIG_HEADERS(config.h:config.hin)
AC_STATE_SAVE(before)
AC_ERLANG_PATH_ERL([no])
AC_ERLANG_PATH_ERLC([no])
if test "$ERL" = "no" || test "$ERLC" = "no"; then AS_EXIT([77]); fi
AC_ERLANG_SUBST_ERTS_VER

AC_OUTPUT
AC_STATE_SAVE(after)
