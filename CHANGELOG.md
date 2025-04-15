# Change Log


## [Unreleased]
[Unreleased]: https://github.com/Goooler/MMKV/compare/v2.1.0.1...HEAD


## [2.1.0.1] - 2025-04-15
[2.1.0.1]: https://github.com/Goooler/MMKV/releases/tag/v2.1.0.1

**Fixed**

- Remove 64-bit check in `MMKV.initialize`.


## [2.1.0] - 2025-04-14
[2.1.0]: https://github.com/Goooler/MMKV/releases/tag/v2.1.0

**Added**

- Supports 32-bit, based on [the upstream version 2.1.0](https://github.com/Tencent/MMKV/releases/tag/v2.1.0).

```
OLD: mmkv-2.1.0-tencent.aar
NEW: mmkv-2.1.0-goooler.aar

 AAR      │ old      │ new      │ diff
──────────┼──────────┼──────────┼──────────
      jar │ 27.2 KiB │ 27.2 KiB │    -71 B
 manifest │    198 B │    198 B │      0 B
   native │  1.4 MiB │  2.5 MiB │ +1.1 MiB
    other │  1.4 MiB │  2.5 MiB │ +1.1 MiB
──────────┼──────────┼──────────┼──────────
    total │  2.8 MiB │    5 MiB │ +2.2 MiB

 JAR     │ old │ new │ diff
─────────┼─────┼─────┼───────────
 classes │  15 │  15 │ 0 (+0 -0)
 methods │ 385 │ 385 │ 0 (+0 -0)
  fields │  59 │  59 │ 0 (+0 -0)

=================
====   AAR   ====
=================

 size      │ diff       │ path
───────────┼────────────┼───────────────────────────────────────────────────────────
 676.8 KiB │ +676.8 KiB │ + prefab/modules/mmkv/libs/android.x86/libmmkv.so
 676.8 KiB │ +676.8 KiB │ + jni/x86/libmmkv.so
 443.1 KiB │ +443.1 KiB │ + prefab/modules/mmkv/libs/android.armeabi-v7a/libmmkv.so
 443.1 KiB │ +443.1 KiB │ + jni/armeabi-v7a/libmmkv.so
      94 B │      +94 B │ + prefab/modules/mmkv/libs/android.armeabi-v7a/abi.json
      86 B │      +86 B │ + prefab/modules/mmkv/libs/android.x86/abi.json
       0 B │        0 B │ + prefab/modules/mmkv/libs/android.armeabi-v7a/
       0 B │        0 B │ + prefab/modules/mmkv/libs/android.x86/
       0 B │        0 B │ + jni/armeabi-v7a/
       0 B │        0 B │ + jni/x86/
  27.2 KiB │      -71 B │ ∆ classes.jar
      65 B │      -22 B │ ∆ prefab/prefab.json
───────────┼────────────┼───────────────────────────────────────────────────────────
   2.2 MiB │   +2.2 MiB │ (total)
```
