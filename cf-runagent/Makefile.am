sbin_PROGRAMS = cf-runagent

AM_CPPFLAGS = @CPPFLAGS@ -I$(srcdir)/../libpromises \
	$(NOVA_CPPFLAGS)

AM_CFLAGS = @CFLAGS@ \
	$(NOVA_CFLAGS)

LDADD = ../libpromises/libpromises.la

CLEANFILES = *.gcno *.gcda

#
# Some basic clean ups
#
MOSTLYCLEANFILES = *~ *.orig *.rej
