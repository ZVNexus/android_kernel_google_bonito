ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

ifeq ($(CONFIG_BOARD_BONITO),y)
ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

dtbo-$(CONFIG_BOARD_BONITO) += \
	sdm670-b4-dev.dtbo \
	sdm670-s4-dev.dtbo \
	sdm670-b4-proto.dtbo \
	sdm670-s4-proto.dtbo \
	sdm670-b4-evt.dtbo \
	sdm670-s4-evt.dtbo

sdm670-b4-dev.dtbo-base		:= ../qcom/sdm670.dtb
sdm670-s4-dev.dtbo-base		:= ../qcom/sdm670.dtb
sdm670-b4-proto.dtbo-base		:= ../qcom/sdm670.dtb
sdm670-s4-proto.dtbo-base		:= ../qcom/sdm670.dtb
sdm670-b4-evt.dtbo-base		:= ../qcom/sdm670.dtb
sdm670-s4-evt.dtbo-base		:= ../qcom/sdm670.dtb

endif
endif #CONFIG_BOARD_BONITO

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
