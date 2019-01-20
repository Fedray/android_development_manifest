# local_manifest.xml

## How can I add this to my repo sync?
> Just ctrl+c and ctrl+v this:

```
curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/Fedray/android_development_manifest/local_manifests/local_manifest.xml
```

Or

git clone https://github.com/Fedray/android_device_motorola_cedric device/motorola/cedric -b liquid && git clone https://github.com/PixelExperience/packages_resources_MotoActions packages/resources/MotoActions -b pie && git clone https://github.com/Sohamlad7/android_vendor_motorola_cedric vendor/motorola/cedric -b lineage-16.0 && git clone https://github.com/Sohamlad7/android_kernel_motorola_msm8937 kernel/motorola/msm8937 -b lineage-16.0