# Copyright (c) 2015 OpenWrt.org
#
include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=mediatek
BOARDNAME:=MediaTek Ralink ARM
SUBTARGETS:=32
FEATURES:=squashfs nand ubifs fpu
MAINTAINER:=John Crispin <john@phrozen.org>

KERNEL_PATCHVER:=4.9

KERNELNAME:=Image dtbs zImage

include $(INCLUDE_DIR)/target.mk
DEFAULT_PACKAGES += \
	kmod-mt76 kmod-leds-gpio kmod-gpio-button-hotplug \
	wpad-mini

$(eval $(call BuildTarget))
