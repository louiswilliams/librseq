# SPDX-License-Identifier: MIT
#
# Copyright (C) 2019 Michael Jeanson <mjeanson@efficios.com>
#

AM_CFLAGS += -I$(top_srcdir)/include -I$(top_builddir)/include

noinst_PROGRAMS = basic_percpu_ops_test basic_test

basic_percpu_ops_test_SOURCES = basic_percpu_ops_test.c
basic_percpu_ops_test_LDADD = $(top_builddir)/src/librseq.la

basic_test_SOURCES = basic_test.c
basic_test_LDADD = $(top_builddir)/src/librseq.la

TESTS = basic_percpu_ops_test basic_test