ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

ifeq ($(CONFIG_BOARD_BONITO),y)

dtb-$(CONFIG_BOARD_BONITO) += \
	sdm670-b4-dev.dtb \
	sdm670-s4-dev.dtb \
	sdm670-b4-proto.dtb \
	sdm670-s4-proto.dtb

endif #CONFIG_BOARD_BONITO

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
