## AppleParavirtGPUMetalIOGPUFamily

> `/System/Library/Extensions/AppleParavirtGPUMetalIOGPUFamily.bundle/Contents/MacOS/AppleParavirtGPUMetalIOGPUFamily`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`
- `__DATA.__thread_vars`

```diff

-64.5.0.0.0
-  __TEXT.__text: 0x28008
-  __TEXT.__auth_stubs: 0x570
+64.6.0.0.0
+  __TEXT.__text: 0x28030
+  __TEXT.__auth_stubs: 0x560
   __TEXT.__objc_stubs: 0x41a0
   __TEXT.__objc_methlist: 0x7c80
-  __TEXT.__objc_methname: 0x10496
+  __TEXT.__objc_methname: 0x104a7
   __TEXT.__objc_classname: 0x947
-  __TEXT.__objc_methtype: 0x9669
+  __TEXT.__objc_methtype: 0x9661
   __TEXT.__const: 0x1d1
   __TEXT.__gcc_except_tab: 0x378
-  __TEXT.__cstring: 0x6192
+  __TEXT.__cstring: 0x6189
   __TEXT.__oslogstring: 0xbdb
   __TEXT.__unwind_info: 0xbe8
-  __DATA_CONST.__auth_got: 0x2c8
+  __DATA_CONST.__auth_got: 0x2c0
   __DATA_CONST.__got: 0x1c8
   __DATA_CONST.__const: 0x258
   __DATA_CONST.__cfstring: 0x3c0

   __DATA_CONST.__objc_protolist: 0x1e0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x110
-  __DATA.__objc_const: 0xc6a8
+  __DATA.__objc_const: 0xc6c8
   __DATA.__objc_selrefs: 0x3a80
-  __DATA.__objc_ivar: 0x338
+  __DATA.__objc_ivar: 0x33c
   __DATA.__objc_data: 0xb90
   __DATA.__data: 0x1680
   __DATA.__thread_vars: 0x30

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1459
-  Symbols:   283
+  Symbols:   282
   CStrings:  3475
 
Symbols:
- _IOConnectTrap3
Functions:
~ sub_1c9ec : 164 -> 192
~ sub_1d074 -> sub_1d090 : 288 -> 300
CStrings:
+ "(write - read) < _dirtyRingLength"
+ "00:22:31"
+ "Oct 29 2026"
+ "_dirtyRingLength"
- "(write - read) < _dirtyRO->dirtyRingLength"
- "04:09:50"
- "Oct 12 2026"
- "^{?=II}"
```
