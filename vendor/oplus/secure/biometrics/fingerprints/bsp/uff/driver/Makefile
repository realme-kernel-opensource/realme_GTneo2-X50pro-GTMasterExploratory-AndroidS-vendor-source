CONFIG_OPLUS_FINGERPRINT_QCOM=y
ifeq ($(CONFIG_OPLUS_FINGERPRINT_QCOM),y)
ccflags-y += -DQCOM_PLATFORM
obj-y  += oplus_fp_driver.o
oplus_fp_driver-y := fp_driver.o fp_platform.o oplus_fp_common.o fingerprint_event.o
endif
obj-$(CONFIG_OPLUS_FINGERPRINT_REE_SPI) += ree_spi/
