include $(srctree)/drivers/misc/mediatek/Makefile.custom

# In case the platform does NOT support this type of sensors

obj-y	+= step_counter.o

obj-$(CONFIG_MTK_BMI160_STC)   +=  bmi160_stc/

ifeq ($(CONFIG_CUSTOM_KERNEL_STEP_COUNTER),"OTHER_VENDOR")
obj-y += other_vendor/
endif
