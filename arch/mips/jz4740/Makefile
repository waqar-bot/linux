# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the Ingenic JZ4740.
#

# Object file lists.

obj-y += prom.o time.o reset.o setup.o timer.o

CFLAGS_setup.o = -I$(src)/../../../scripts/dtc/libfdt

# PM support

obj-$(CONFIG_PM) += pm.o
