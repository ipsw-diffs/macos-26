## apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_checkseal`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2811.160.7.704.3
-  __TEXT.__text: 0x4f2f8
+2811.160.7.702.4
+  __TEXT.__text: 0x4f288
   __TEXT.__auth_stubs: 0x790
   __TEXT.__const: 0x4f0
-  __TEXT.__cstring: 0x10322
+  __TEXT.__cstring: 0x102d0
   __TEXT.__unwind_info: 0x8e8
   __DATA_CONST.__auth_got: 0x3c8
   __DATA_CONST.__got: 0x50

   - /usr/lib/libutil.dylib
   Functions: 733
   Symbols:   136
-  CStrings:  1304
+  CStrings:  1303
 
Functions:
~ sub_100042190 : 5980 -> 5876
~ sub_10004f4c4 -> sub_10004f45c : 100 -> 92
CStrings:
- "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
```
