# In case the platform does NOT support this type of sensors
ccflags-y += -I$(srctree)/drivers/misc/mediatek/sensors-1.0/hwmon/include
ccflags-y += -I$(srctree)/drivers/misc/mediatek/sensors-1.0/include
obj-y   +=  gyroscope.o gyro_factory.o


obj-$(CONFIG_MTK_GYROHUB)      +=  gyrohub/
obj-$(CONFIG_MTK_LSM6DS3HGY)   +=  lsm6ds3hgy/
obj-$(CONFIG_MTK_BMI160GY_I2C) +=  bmi160gy-i2c/
obj-$(CONFIG_MTK_MPU6050GY)   +=  mpu6050gy/
#prize add by zhaopengge--------20210206-----start
obj-$(CONFIG_MTK_ICM426XX_G)   +=  icm426xx_g/
#prize add by zhaopengge--------20210206-----end

