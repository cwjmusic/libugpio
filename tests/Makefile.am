#
# Copyright © 2012-2015 Michael Heimpold <mhei@heimpold.de>
#
# SPDX-License-Identifier: GPL-3.0+
#

INCLUDES                = -I$(top_srcdir)/src -I$(top_builddir)/src

AM_CFLAGS = -Wall -pedantic

bin_PROGRAMS            = gpioctl

gpioctl_SOURCES         = gpioctl.c
gpioctl_LDADD           = $(top_builddir)/src/libugpio.la
