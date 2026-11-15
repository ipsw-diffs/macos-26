## hfs_convert

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/hfs_convert`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2811.160.7.704.3
-  __TEXT.__text: 0xb68e4
+2811.160.7.702.4
+  __TEXT.__text: 0xb6874
   __TEXT.__auth_stubs: 0x11b0
   __TEXT.__objc_stubs: 0x80
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x1aac8
+  __TEXT.__cstring: 0x1aa76
   __TEXT.__const: 0xa470
   __TEXT.__objc_methname: 0x48
   __TEXT.__unwind_info: 0xbc0

   - /usr/lib/libz.1.dylib
   Functions: 2054
   Symbols:   308
-  CStrings:  2707
+  CStrings:  2706
 
Functions:
~ sub_100059f44 : 5980 -> 5876
~ sub_100066160 -> sub_1000660f8 : 100 -> 92
CStrings:
+ "2811.160.7.702.4"
- "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
- "2811.160.7.704.3"
```
