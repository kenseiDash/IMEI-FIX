# IMEI-FIX-A12M
<h1 align="center">
    <img src="https://i.ibb.co/ynwTPfw/k.png">
</h1>



## Start

adb devices

adb shell

su

cd /mnt/vendor/nvdata/md/NVRAM

rm -R NVD_IMEI


## Reboot

adb devices

adb shell

su

cd /mnt/vendor/nvdata/md/NVRAM

chmod 550 NVD_IMEI

## Backup

cp -R NVD_IMEI /storage/self/primary
