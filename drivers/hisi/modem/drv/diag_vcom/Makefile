-include $(srctree)/drivers/hisi/modem/config/product/$(OBB_PRODUCT_NAME)/config/balong_product_config.mk

ifeq ($(strip $(llt_gcov)),y)
GCOV_PROFILE := y
endif

obj-y       +=  diag_vcom_main.o  diag_vcom_handler.o

subdir-ccflags-y := -Wno-error
