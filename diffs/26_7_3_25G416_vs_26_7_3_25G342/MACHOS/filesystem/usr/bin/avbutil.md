## avbutil

> `/usr/bin/avbutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1450.2.0.0.0
-  __TEXT.__text: 0x15658
+1440.7.0.0.0
+  __TEXT.__text: 0x15648
   __TEXT.__auth_stubs: 0x2d0
-  __TEXT.__objc_stubs: 0x1800
+  __TEXT.__objc_stubs: 0x17e0
   __TEXT.__objc_methlist: 0x78c
-  __TEXT.__objc_methname: 0x15bf
+  __TEXT.__objc_methname: 0x159d
   __TEXT.__cstring: 0x440c
   __TEXT.__objc_classname: 0x121
   __TEXT.__objc_methtype: 0x54f

   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x78
   __DATA.__objc_const: 0x14c8
-  __DATA.__objc_selrefs: 0x798
+  __DATA.__objc_selrefs: 0x790
   __DATA.__objc_ivar: 0x60
   __DATA.__objc_data: 0x4b0
   __DATA.__data: 0x180

   - /usr/lib/libobjc.A.dylib
   Functions: 119
   Symbols:   102
-  CStrings:  740
+  CStrings:  739
 
Functions:
~ sub_100001c74 : 972 -> 956
CStrings:
+ "1440.7"
- "1450.2"
- "setURLBackedMemoryObjectsAllowed:"
```
