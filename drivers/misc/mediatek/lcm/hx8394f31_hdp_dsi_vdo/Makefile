# Makefile for misc devices that really don't fit anywhere else.
#


obj-y += hx8394f31_hdp_dsi_vdo.o
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
ccflags-$(CONFIG_MTK_LCM) += -I$(srctree)/drivers/misc/mediatek/lcm/inc
ccflags-$(CONFIG_PRIZE_LCD_BIAS_TPS65132) += -I$(srctree)/drivers/misc/mediatek/prize/lcdbias/tps65132

