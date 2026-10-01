# SPDX-License-Identifier: ISC
#
# Makefile fragment for Broadcom 802.11n Networking Device Driver Utilities
#
# Copyright (c) 2011 Broadcom Corporation
#
# -I must stay one word: kbuild's addtree drops a bare -I when building with a separate objtree.
ccflags-y := -I$(src)/../include

obj-$(CPTCFG_BRCMUTIL)	+= brcmutil.o
brcmutil-objs	= utils.o d11.o
