ifeq ($(PLATFORM_TYPE),m0104)
        dtb-$(CONFIG_ARCH_KONA) += m0104-kona-v2.1-iot-rb5.dtb
endif

ifeq ($(PLATFORM_TYPE),m0054)
        dtb-$(CONFIG_ARCH_KONA) += m0054-kona-v2.1-iot-rb5.dtb
endif

ifeq ($(PLATFORM_TYPE),m0052)
        dtb-$(CONFIG_ARCH_KONA) += m0052-kona-v2.1-iot-rb5.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
