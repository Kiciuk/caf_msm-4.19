ifeq ($(CONFIG_MACH_XIAOMI_MSM8953),y)
dtb-$(CONFIG_MACH_XIAOMI_C6) += msm8953-qrd-sku3-mido.dtb
else
dtb-$(CONFIG_ARCH_MSM8953) += msm8953-cdp.dtb \
	msm8953-mtp.dtb \
	msm8953-ext-codec-mtp.dtb \
	msm8953-qrd-sku3.dtb \
	msm8953-rcm.dtb \
	msm8953-ext-codec-rcm.dtb \
	msm8953-ipc.dtb \
	msm8953-cdp-1200p.dtb \
	msm8953-iot-mtp.dtb \
	msm8953-pmi8940-cdp.dtb \
	msm8953-pmi8940-mtp.dtb \
	msm8953-pmi8937-cdp.dtb \
	msm8953-pmi8937-mtp.dtb \
	msm8953-pmi8940-ext-codec-mtp.dtb \
	msm8953-pmi8937-ext-codec-mtp.dtb \
	msm8953-pmi632-cdp-s2.dtb \
	
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
