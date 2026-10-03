# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_FUXI) += yt6801.o
yt6801-objs := fuxi-gmac-common.o fuxi-gmac-desc.o fuxi-gmac-ethtool.o fuxi-gmac-hw.o \
	       fuxi-gmac-net.o fuxi-gmac-pci.o fuxi-gmac-phy.o fuxi-efuse.o fuxi-dbg.o \
	       fuxi-gmac-debugfs.o
ccflags-y += -DFXGMAC_DEBUG
ccflags-y += -Wno-self-assign
