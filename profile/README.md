## AOSP development for the Moto MT6879 devices

### Common repositories for moto mt6879
* [**Common Tree**](https://github.com/moto-mt6879/android_device_motorola_mt6879-common) (`android_device_motorola_mt6879-common`)
* [**Kernel Source**](https://github.com/moto-mt6879/android_kernel_motorola_mt6879) (`android_kernel_motorola_mt6879`)
* [**Common vendor Tree**](https://github.com/moto-mt6879/proprietary_vendor_motorola_mt6879-common) (`proprietary_vendor_motorola_mt6879-common`)

### Device-specific repositories for manaus
* [**Device Tree**](https://github.com/moto-mt6879/android_device_motorola_manaus) (`android_device_motorola_manaus`)
* [**Vendor Tree**](https://github.com/moto-mt6879/proprietary_vendor_motorola_manaus) (`proprietary_vendor_motorola_manaus`)

### Device-specific repositories for tesla
* [**Device Tree**](https://github.com/moto-mt6879/android_device_motorola_tesla) (`android_device_motorola_tesla`)
* [**Vendor Tree**](https://github.com/moto-mt6879/proprietary_vendor_motorola_tesla) (`proprietary_vendor_motorola_tesla`)

### Required Hardware/SEPolicy repositories
* [**MediaTek SEPolicy**](https://github.com/moto-manaus/device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek Hardware**](https://github.com/moto-manaus/hardware_mediatek) (`android_hardware_mediatek`)
* [**Motorola Hardware**](https://github.com/moto-manaus/hardware_motorola) (`android_hardware_motorola`)

### patches (fenrir patched LK support)
* [**Allow flashing images from fastbootd with fenrir patched LKs**](https://github.com/yaap/system_core/commit/ca84e2ec0689f62ad6449dbb7f45dece5898a307) (`android_system_core`)
* [**Return true for IsDeviceUnlocked() if fenrir=true**](https://github.com/yaap/bootable_recovery/commit/b0630ff093f377c7c3158a11eae15bf4505cdc52) (`bootable_recovery`)
