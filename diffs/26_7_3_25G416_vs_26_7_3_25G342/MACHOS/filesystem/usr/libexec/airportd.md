## airportd

> `/usr/libexec/airportd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-19155.5.0.0.0
-  __TEXT.__text: 0xde2a8
-  __TEXT.__auth_stubs: 0x2000
-  __TEXT.__objc_stubs: 0xff60
+19155.4.0.0.0
+  __TEXT.__text: 0xddc5c
+  __TEXT.__auth_stubs: 0x1fb0
+  __TEXT.__objc_stubs: 0xff80
   __TEXT.__objc_methlist: 0x5590
   __TEXT.__const: 0xf18
-  __TEXT.__objc_methname: 0x14640
+  __TEXT.__objc_methname: 0x1465d
   __TEXT.__objc_classname: 0x3c9
   __TEXT.__objc_methtype: 0x339b
   __TEXT.__gcc_except_tab: 0x20e4
-  __TEXT.__cstring: 0x2d5e8
-  __TEXT.__oslogstring: 0x163c
+  __TEXT.__cstring: 0x2d5ee
+  __TEXT.__oslogstring: 0x147c
   __TEXT.__unwind_info: 0x2790
-  __DATA_CONST.__auth_got: 0x1018
+  __DATA_CONST.__auth_got: 0xff0
   __DATA_CONST.__got: 0x900
   __DATA_CONST.__auth_ptr: 0x28
   __DATA_CONST.__const: 0x3230

   __DATA_CONST.__objc_dictobj: 0x168
   __DATA_CONST.__objc_arrayobj: 0x78
   __DATA.__objc_const: 0x6808
-  __DATA.__objc_selrefs: 0x4860
+  __DATA.__objc_selrefs: 0x4868
   __DATA.__objc_ivar: 0x708
   __DATA.__objc_data: 0xb90
   __DATA.__data: 0x418

   - /usr/lib/libpcap.A.dylib
   - /usr/lib/libz.1.dylib
   Functions: 2794
-  Symbols:   833
-  CStrings:  7474
+  Symbols:   828
+  CStrings:  7467
 
Symbols:
+ _fopen
- _fchmod
- _fcntl
- _fdopen
- _fstat
- _rename
- _unlink
Functions:
~ sub_100062330 : 4104 -> 2492
CStrings:
+ "/private/var/tmp/%@"
+ "<%{public}s:%u> Unable to open read file '%{public}s'"
+ "moveItemAtPath:toPath:error:"
- "%@/.%@.XXXXXX"
- "<%{public}s:%u> Not a regular file '%{public}s'"
- "<%{public}s:%u> Path too long '%{public}s'"
- "<%{public}s:%u> Unable to close '%{public}s'"
- "<%{public}s:%u> Unable to create temporary file '%{public}s', errno[%d]"
- "<%{public}s:%u> Unable to flush '%{public}s'"
- "<%{public}s:%u> Unable to move '%{public}s' to '%{public}s', errno[%d]"
- "<%{public}s:%u> Unable to open read file '%{public}s', errno[%d]"
- "<%{public}s:%u> Unable to open read stream '%{public}s'"
- "<%{public}s:%u> Unable to open write stream '%{public}s'"
```
