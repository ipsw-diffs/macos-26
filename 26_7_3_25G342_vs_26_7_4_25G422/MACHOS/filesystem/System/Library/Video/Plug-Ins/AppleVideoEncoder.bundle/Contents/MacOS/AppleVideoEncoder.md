## AppleVideoEncoder

> `/System/Library/Video/Plug-Ins/AppleVideoEncoder.bundle/Contents/MacOS/AppleVideoEncoder`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-905.43.1.0.0
-  __TEXT.__text: 0x181378
+905.44.1.0.0
+  __TEXT.__text: 0x1814a4
   __TEXT.__auth_stubs: 0x1050
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0xc
   __TEXT.__const: 0x23ba8
-  __TEXT.__cstring: 0x52cf6
+  __TEXT.__cstring: 0x52db7
   __TEXT.__gcc_except_tab: 0x71c
   __TEXT.__objc_methname: 0xb
   __TEXT.__unwind_info: 0x8c8

   - /usr/lib/libobjc.A.dylib
   Functions: 1593
   Symbols:   511
-  CStrings:  6622
+  CStrings:  6625
 
Functions:
~ sub_1103b4 : 2964 -> 2984
~ sub_150060 -> sub_150074 : 724 -> 764
~ sub_156eb4 -> sub_156ef0 : 1380 -> 1404
~ sub_17d318 -> sub_17d36c : 476 -> 692
CStrings:
+ "%lld %d AVE %s: %s:%d %s | too many DRL entries %d (max %d)"
+ "%lld %d AVE %s: %s:%d %s | too many DRL entries %d (max %d)\n"
+ "22:02:26"
+ "22:02:29"
+ "22:02:31"
+ "22:02:32"
+ "905.44.1"
+ "Nov 11 2026"
+ "num <= 2"
+ "pInfo->num_negative_pics <= 16 && pInfo->num_positive_pics <= 16 && (pInfo->num_negative_pics + pInfo->num_positive_pics) <= 16"
- "02:24:25"
- "02:24:28"
- "02:24:29"
- "02:24:30"
- "905.43.1"
- "Oct 12 2026"
- "pInfo->num_negative_pics <= 16 && pInfo->num_positive_pics <= 16"
```
