#
#  Makefile for the Squid LDAP authentication helper
#
#  $Id: Makefile.am,v 1.4 2006/05/22 20:42:05 hno Exp $
#
#  Uncomment and customize the following to suit your needs:
#

libexec_PROGRAMS 		= squid_unix_group
man_MANS 			= squid_unix_group.8
EXTRA_DIST			= squid_unix_group.8
squid_unix_group_SOURCES	= check_group.c

LDADD		= -L$(top_builddir)/lib -lmiscutil @XTRA_LIBS@
INCLUDES	= -I. -I$(top_builddir)/include -I$(top_srcdir)/include
