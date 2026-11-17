## sysdiagnosed

> `/usr/libexec/sysdiagnosed`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1527.120.2.0.0
-  __TEXT.__text: 0x63dac
+1527.120.2.700.1
+  __TEXT.__text: 0x63f10
   __TEXT.__auth_stubs: 0x1470
-  __TEXT.__objc_stubs: 0x8300
+  __TEXT.__objc_stubs: 0x8320
   __TEXT.__objc_methlist: 0x37ec
   __TEXT.__const: 0x1e4
-  __TEXT.__cstring: 0xe846
+  __TEXT.__cstring: 0xe868
   __TEXT.__oslogstring: 0x7d2a
   __TEXT.__objc_classname: 0x327
   __TEXT.__objc_methtype: 0xe27
   __TEXT.__gcc_except_tab: 0x107c
-  __TEXT.__objc_methname: 0x8cec
-  __TEXT.__unwind_info: 0x1158
+  __TEXT.__objc_methname: 0x8d09
+  __TEXT.__unwind_info: 0x1160
   __DATA_CONST.__auth_got: 0xa48
   __DATA_CONST.__got: 0x328
   __DATA_CONST.__auth_ptr: 0x70
   __DATA_CONST.__const: 0x1180
-  __DATA_CONST.__cfstring: 0x10040
+  __DATA_CONST.__cfstring: 0x100a0
   __DATA_CONST.__objc_classlist: 0x120
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arrayobj: 0x1818
   __DATA_CONST.__objc_intobj: 0x228
   __DATA.__objc_const: 0x4990
-  __DATA.__objc_selrefs: 0x23c8
+  __DATA.__objc_selrefs: 0x23d0
   __DATA.__objc_ivar: 0x408
   __DATA.__objc_data: 0xb40
   __DATA.__data: 0x1a8

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsysdiagnose.dylib
   - /usr/lib/libtailspin.dylib
-  Functions: 1630
+  Functions: 1631
   Symbols:   442
-  CStrings:  4363
+  CStrings:  4367
 
CStrings:
+ "/.nofollow"
+ "/.nofollow/"
+ "/.resolve/"
+ "rangeOfString:options:range:"
```
