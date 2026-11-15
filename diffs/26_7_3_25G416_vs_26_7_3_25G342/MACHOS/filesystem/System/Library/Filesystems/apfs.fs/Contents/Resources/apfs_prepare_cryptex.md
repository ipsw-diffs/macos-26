## apfs_prepare_cryptex

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_prepare_cryptex`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2811.160.7.704.3
-  __TEXT.__text: 0x6e718
+2811.160.7.702.4
+  __TEXT.__text: 0x6e6a8
   __TEXT.__auth_stubs: 0x840
   __TEXT.__const: 0xc51a
-  __TEXT.__cstring: 0x1825c
+  __TEXT.__cstring: 0x1820a
   __TEXT.__unwind_info: 0xc50
   __DATA_CONST.__auth_got: 0x420
   __DATA_CONST.__got: 0x58

   - /usr/lib/libutil.dylib
   Functions: 1001
   Symbols:   148
-  CStrings:  2082
+  CStrings:  2081
 
Functions:
~ sub_100061498 : 5980 -> 5876
~ sub_10006eacc -> sub_10006ea64 : 100 -> 92
CStrings:
+ "2811.160.7.702.4"
- "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
- "2811.160.7.704.3"
```
