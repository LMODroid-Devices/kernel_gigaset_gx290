# In case the platform does NOT support this type of sensors
ccflags-y += -I$(srctree)/drivers/misc/mediatek/sensors-1.0/hwmon/include
ccflags-y += -I$(srctree)/drivers/misc/mediatek/sensors-1.0/include

obj-y   +=  accel.o accel_factory.o

obj-$(CONFIG_MTK_ACCELHUB) += accelhub/
obj-$(CONFIG_MTK_LSM6DS3HG)+= lsm6ds3hg/
obj-$(CONFIG_MTK_BMI160_I2C)   += bmi160-i2c/
obj-$(CONFIG_MTK_MPU6050G)   += mpu6050g/
obj-$(CONFIG_MTK_MXC400X_PRIZE)   +=  mxc400x_prize/
#prize add by zhaopengge--------20210506-----start
obj-$(CONFIG_MTK_ICM426XX_A)   +=  icm426xx_a/
#prize add by zhaopengge--------20210506-----end
