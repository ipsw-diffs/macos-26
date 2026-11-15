## newfs_apfs

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/newfs_apfs`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2811.160.7.702.4
-  __TEXT.__text: 0x548a4
+2811.160.7.704.3
+  __TEXT.__text: 0x54914
   __TEXT.__auth_stubs: 0x900
-  __TEXT.__cstring: 0x10848
+  __TEXT.__cstring: 0x1089a
   __TEXT.__const: 0x84c1
   __TEXT.__oslogstring: 0x125
   __TEXT.__unwind_info: 0x8d8

   - /usr/lib/libutil.dylib
   Functions: 807
   Symbols:   161
-  CStrings:  1407
+  CStrings:  1408
 
Functions:
~ sub_1000455ac : 5876 -> 5980
~ sub_100051204 -> sub_10005126c : 92 -> 100
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
+ "2811.160.7.704.3"
- "2811.160.7.702.4"
```
