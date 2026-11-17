## mddiagnose

> `/usr/bin/mddiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2418.6.3.9.403
-  __TEXT.__text: 0x11250
-  __TEXT.__auth_stubs: 0xf30
+2418.6.3.9.404
+  __TEXT.__text: 0x11284
+  __TEXT.__auth_stubs: 0xf40
   __TEXT.__objc_stubs: 0x13e0
   __TEXT.__objc_methlist: 0x32c
   __TEXT.__const: 0x198
-  __TEXT.__cstring: 0x4c69
+  __TEXT.__cstring: 0x4c8c
   __TEXT.__oslogstring: 0x81
   __TEXT.__objc_methname: 0xf2d
   __TEXT.__gcc_except_tab: 0xcc
   __TEXT.__objc_classname: 0x4b
   __TEXT.__objc_methtype: 0x171
   __TEXT.__unwind_info: 0x428
-  __DATA_CONST.__auth_got: 0x7a8
+  __DATA_CONST.__auth_got: 0x7b0
   __DATA_CONST.__got: 0x1d0
   __DATA_CONST.__auth_ptr: 0x30
   __DATA_CONST.__const: 0x638
-  __DATA_CONST.__cfstring: 0x4ea0
+  __DATA_CONST.__cfstring: 0x4f00
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 349
-  Symbols:   313
-  CStrings:  1048
+  Symbols:   314
+  CStrings:  1051
 
Symbols:
+ _MDPathByStrippingLookupPrefix
Functions:
~ sub_100000fd8 : 2032 -> 2024
~ sub_1000054f8 -> sub_1000054f0 : 272 -> 332
CStrings:
+ "/.nofollow/"
+ "/.resolve/"
+ "/.resolve/1"
```
