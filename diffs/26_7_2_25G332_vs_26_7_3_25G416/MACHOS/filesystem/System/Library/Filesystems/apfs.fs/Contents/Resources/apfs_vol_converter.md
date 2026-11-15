## apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_vol_converter`

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
   __TEXT.__auth_stubs: 0xa50
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0xc20
-  __TEXT.__cstring: 0x123e7
+  __TEXT.__cstring: 0x12439
   __TEXT.__gcc_except_tab: 0x698
   __TEXT.__unwind_info: 0xc40
   __DATA_CONST.__auth_got: 0x530

   - /usr/lib/libutil.dylib
   Functions: 882
   Symbols:   190
-  CStrings:  1628
+  CStrings:  1629
 
Functions:
~ sub_10004cda8 : 5876 -> 5980
~ sub_10005a200 -> sub_10005a268 : 92 -> 100
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
+ "2811.160.7.704.3"
- "2811.160.7.702.4"
```
