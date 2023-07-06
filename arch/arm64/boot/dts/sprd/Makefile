# SPDX-License-Identifier: GPL-2.0

dtb-$(CONFIG_ARCH_SPRD) += \
	ums512.dtb

dtbo-$(CONFIG_ARCH_SPRD) += \
	RMX3265-overlay.dtbo \
	S19610AA1-overlay.dtbo

RMX3265-overlay.dtbo-base := ums512.dtb
S19610AA1-overlay.dtbo-base := ums512.dtb

always		:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
