#
# Makefile for SiW touch driver
#
EXTRA_CFLAGS += -DSOMC_TOUCH_BRINGUP

siwtch-y := siw_touch.o
siwtch-y += siw_touch_hal.o siw_touch_hal_sysfs.o
siwtch-y += siw_touch_hal_abt.o
siwtch-y += siw_touch_hal_prd.o
siwtch-y += siw_touch_hal_watch.o
siwtch-y += siw_touch_bus.o
siwtch-y += siw_touch_bus_i2c.o
siwtch-y += siw_touch_of.o
siwtch-y += siw_touch_irq.o siw_touch_gpio.o
siwtch-y += siw_touch_event.o siw_touch_notify.o
siwtch-y += siw_touch_sys.o siw_touch_sysfs.o
siwtch-y += siw_touch_misc.o

siwtch-$(CONFIG_TOUCHSCREEN_SIW_SW49501) += touch_sw49501.o

obj-$(CONFIG_TOUCHSCREEN_SIW) += siwtch.o

obj-$(CONFIG_TOUCHSCREEN_SIWMON) += mon/

