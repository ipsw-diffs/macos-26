## slurpAPFSMeta

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/slurpAPFSMeta`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2811.160.7.704.3
-  __TEXT.__text: 0x36880
+2811.160.7.702.4
+  __TEXT.__text: 0x36820
   __TEXT.__auth_stubs: 0x830
-  __TEXT.__cstring: 0x8be5
+  __TEXT.__cstring: 0x8b93
   __TEXT.__const: 0x1e0
   __TEXT.__unwind_info: 0x688
   __DATA_CONST.__auth_got: 0x418

   - /usr/lib/libSystem.B.dylib
   Functions: 521
   Symbols:   144
-  CStrings:  758
+  CStrings:  757
 
Functions:
~ sub_10001dc4c : 5980 -> 5876
~ sub_100025944 -> sub_1000258dc : 172 -> 180
CStrings:
- "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
```
