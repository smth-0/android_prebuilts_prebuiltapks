# Prebuilt APKs

This is a collection of FOSS APKs, coupled with the respective Android.mk for an
easy integration in the Android build system.



To include them in your build just add this to the end of `vendor/lineage/config/common.mk`.
``` 
CUSTOM_PACKAGES += \
    AuroraAdroid \
    AuroraServices \
    AuroraStore \
    FakeStore \
    GmsCore \
    GsfProxy \
    MozillaNlpBackend
```

Apps in the repo:
- AuroraAdroid 
- AuroraServices 
- AuroraStore  
- MicroG
- Mozilla Nlp Backend
