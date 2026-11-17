## sm_stats

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/sm_stats`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2811.160.7.702.4
-  __TEXT.__text: 0x43354
+2811.160.7.704.3
+  __TEXT.__text: 0x433b4
   __TEXT.__auth_stubs: 0x720
-  __TEXT.__cstring: 0xcd9c
+  __TEXT.__cstring: 0xcdee
   __TEXT.__const: 0x1e8
   __TEXT.__unwind_info: 0x6f8
   __DATA_CONST.__auth_got: 0x390

   - /usr/lib/libutil.dylib
   Functions: 578
   Symbols:   129
-  CStrings:  1050
+  CStrings:  1051
 
Functions:
~ sub_10000b448 : 5876 -> 5980
~ sub_100026a14 -> sub_100026a7c : 508 -> 500
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
```
