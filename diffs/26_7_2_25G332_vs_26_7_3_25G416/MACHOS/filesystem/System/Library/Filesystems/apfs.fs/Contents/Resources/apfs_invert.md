## apfs_invert

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_invert`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2811.160.7.702.4
-  __TEXT.__text: 0x518e0
+2811.160.7.704.3
+  __TEXT.__text: 0x51950
   __TEXT.__auth_stubs: 0x7f0
-  __TEXT.__cstring: 0x10ec5
+  __TEXT.__cstring: 0x10f17
   __TEXT.__const: 0x8440
   __TEXT.__unwind_info: 0x900
   __DATA_CONST.__auth_got: 0x3f8

   - /usr/lib/libutil.dylib
   Functions: 735
   Symbols:   142
-  CStrings:  1397
+  CStrings:  1398
 
Functions:
~ sub_100045498 : 5876 -> 5980
~ sub_100050d08 -> sub_100050d70 : 92 -> 100
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
+ "2811.160.7.704.3"
- "2811.160.7.702.4"
```
