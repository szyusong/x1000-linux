
obj-y += misc.o regulator.o #sound.o
obj-$(CONFIG_LCD_BYD_8991FTGF) += lcd-8991.o
obj-$(CONFIG_LCD_KFM701A21_1A) += lcd-kfm701a21_1a.o
obj-$(CONFIG_FB_JZ4775_ANDROID_EPD)	+= mensa-epd.o
obj-$(CONFIG_MMC_JZ4775)		+= mmc.o
obj-$(CONFIG_BCM4330_RFKILL)		+= bt.o
ifdef CONFIG_SLCD_SUSPEND_ALARM_WAKEUP_REFRESH
obj-y += pm_slcd.o
else
obj-y += pm.o
endif
obj-$(CONFIG_VIDEO_JZ4780_CIM_HOST)     += mensa-cim.o
obj-$(CONFIG_MTD_NAND_MIRCON_ACA)	+= nand_aca.o
