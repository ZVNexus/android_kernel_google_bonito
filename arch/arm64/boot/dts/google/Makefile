ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

dtb-$(CONFIG_BOARD_BONITO) += \
	sdm670-b4-dev.dtb \
	sdm670-s4-dev.dtb

endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
