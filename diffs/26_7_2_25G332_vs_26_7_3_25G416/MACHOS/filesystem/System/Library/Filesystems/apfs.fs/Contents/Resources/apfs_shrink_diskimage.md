## apfs_shrink_diskimage

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_shrink_diskimage`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2811.160.7.702.4
-  __TEXT.__text: 0x59c18
+2811.160.7.704.3
+  __TEXT.__text: 0x59c88
   __TEXT.__auth_stubs: 0x7e0
-  __TEXT.__cstring: 0x131a9
+  __TEXT.__cstring: 0x131fb
   __TEXT.__const: 0x250
   __TEXT.__unwind_info: 0x938
   __DATA_CONST.__auth_got: 0x3f0

   - /usr/lib/libutil.dylib
   Functions: 762
   Symbols:   140
-  CStrings:  1517
+  CStrings:  1518
 
Functions:
~ sub_10004bf94 : 5876 -> 5980
~ sub_10005a0fc -> sub_10005a164 : 92 -> 100
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
```
