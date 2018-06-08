ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

dtb-$(CONFIG_BOARD_BONITO) += \
	sdm670-bonito-dev.dtb

endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
