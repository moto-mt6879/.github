## AOSP development for the Motorola Edge 40 Neo codenamed `manaus`

### Device-specific repositories
* [**Device Tree**](https://github.com/moto-manaus/device_motorola_manaus) (`device_motorola_manaus`)
* [**Device Kernel (Compiled outputs from kernel source)**](https://github.com/moto-manaus/device_motorola_manaus-kernel) (`device_motorola_manaus-kernel`)
* [**Vendor Tree**](https://codeberg.org/rexix01/vendor_motorola_manaus) (`vendor_motorola_manaus`)

### Required Hardware/SEPolicy repositories
* [**MediaTek SEPolicy**](https://github.com/moto-manaus/device_mediatek_sepolicy_vndr) (`android_device_mediatek_sepolicy_vndr`)
* [**MediaTek Hardware**](https://github.com/moto-manaus/hardware_mediatek) (`hardware_mediatek`)
* [**Motorola Hardware**](https://github.com/moto-manaus/hardware_motorola) (`hardware_motorola`)

### patches (fenrir patched LK support)
* [**Allow flashing images from fastbootd with fenrir patched LKs**](https://github.com/yaap/system_core/commit/ca84e2ec0689f62ad6449dbb7f45dece5898a307) (`android_system_core`)
* [**Return true for IsDeviceUnlocked() if fenrir=true**](https://github.com/yaap/bootable_recovery/commit/b0630ff093f377c7c3158a11eae15bf4505cdc52) (`bootable_recovery`)

### Device kernel repositories
* [**Kernel source**](https://github.com/moto-manaus/kernel_motorola_manaus) (`kernel_motorola_manaus`)
