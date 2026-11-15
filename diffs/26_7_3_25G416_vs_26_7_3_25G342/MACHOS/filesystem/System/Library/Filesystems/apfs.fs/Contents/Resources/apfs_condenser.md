## apfs_condenser

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_condenser`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2811.160.7.704.3
-  __TEXT.__text: 0x4cc18
+2811.160.7.702.4
+  __TEXT.__text: 0x4cba8
   __TEXT.__auth_stubs: 0x820
-  __TEXT.__cstring: 0xfad1
+  __TEXT.__cstring: 0xfa7f
   __TEXT.__const: 0x240
   __TEXT.__unwind_info: 0x820
   __DATA_CONST.__auth_got: 0x410

   - /usr/lib/libutil.dylib
   Functions: 671
   Symbols:   144
-  CStrings:  1289
+  CStrings:  1288
 
Functions:
~ sub_10004146c : 5980 -> 5876
~ sub_10004cc94 -> sub_10004cc2c : 100 -> 92
CStrings:
+ "2811.160.7.702.4"
- "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
- "2811.160.7.704.3"
```
