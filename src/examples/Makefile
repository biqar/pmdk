# SPDX-License-Identifier: BSD-3-Clause
# Copyright 2014-2023, Intel Corporation

#
# examples/Makefile -- build the Persistent Memory Development Kit examples
#

include ../common.inc

DIRS = libpmem libpmemblk libpmemlog libpmemobj libpmempool \
	pmreorder libpmem2

include Makefile.inc

rmtmp:
	$(RM) $(TMP_HEADERS)

clobber clean: rmtmp
