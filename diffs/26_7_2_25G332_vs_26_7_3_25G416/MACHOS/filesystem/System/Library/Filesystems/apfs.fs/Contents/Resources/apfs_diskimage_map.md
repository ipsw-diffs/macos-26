## apfs_diskimage_map

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_diskimage_map`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2811.160.7.702.4
-  __TEXT.__text: 0x4b3e4
+2811.160.7.704.3
+  __TEXT.__text: 0x4b454
   __TEXT.__auth_stubs: 0x7c0
-  __TEXT.__cstring: 0xefeb
+  __TEXT.__cstring: 0xf03d
   __TEXT.__const: 0x248
   __TEXT.__unwind_info: 0x858
   __DATA_CONST.__auth_got: 0x3e0

   - /usr/lib/libutil.dylib
   Functions: 679
   Symbols:   138
-  CStrings:  1228
+  CStrings:  1229
 
Functions:
~ sub_10003e798 : 5876 -> 5980
~ sub_10004ba64 -> sub_10004bacc : 92 -> 100
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
```
