## avbdeviced

> `/usr/sbin/avbdeviced`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1450.2.0.0.0
-  __TEXT.__text: 0x45234
+1440.7.0.0.0
+  __TEXT.__text: 0x44de0
   __TEXT.__auth_stubs: 0x490
-  __TEXT.__objc_stubs: 0x5a40
+  __TEXT.__objc_stubs: 0x59a0
   __TEXT.__objc_methlist: 0x1ba4
-  __TEXT.__cstring: 0x2263
-  __TEXT.__const: 0xe0
+  __TEXT.__cstring: 0x2210
+  __TEXT.__const: 0xd0
   __TEXT.__gcc_except_tab: 0x574
-  __TEXT.__oslogstring: 0x4142
-  __TEXT.__objc_methname: 0x69ec
+  __TEXT.__oslogstring: 0x3fe0
+  __TEXT.__objc_methname: 0x6985
   __TEXT.__objc_classname: 0x3ec
   __TEXT.__objc_methtype: 0x1064
   __TEXT.__unwind_info: 0x878
   __DATA_CONST.__auth_got: 0x258
-  __DATA_CONST.__got: 0x2d0
+  __DATA_CONST.__got: 0x2c0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0x1578
-  __DATA_CONST.__cfstring: 0x1b20
+  __DATA_CONST.__cfstring: 0x1ac0
   __DATA_CONST.__objc_classlist: 0xb8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x78

   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA.__objc_const: 0x3c40
-  __DATA.__objc_selrefs: 0x1b40
+  __DATA.__objc_selrefs: 0x1b18
   __DATA.__objc_ivar: 0x27c
   __DATA.__objc_data: 0x730
   __DATA.__data: 0x5b0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 872
-  Symbols:   185
-  CStrings:  1745
+  Symbols:   183
+  CStrings:  1735
 
Symbols:
- _OBJC_CLASS_$_AVB17221AEMMemoryObjectData
- _OBJC_CLASS_$_AVBCustomVirtualAudioEntityAEMValidator
Functions:
~ sub_10003b570 : 1628 -> 1288
~ sub_10003daa8 -> sub_10003d954 : 1372 -> 604
CStrings:
- "Custom virtual entity \"%{public}@\" has a memory object (configuration %hu, descriptor %hu) whose content this daemon will not resolve; it will not be served to controllers"
- "Custom virtual entity \"%{public}@\" has a memory object (configuration %hu, descriptor %hu) whose descriptor claims %llu bytes but which holds %lu; reads are bounded by what it holds"
- "Custom virtual entity model failed validation."
- "ValidationErrors"
- "ValidationWarnings"
- "data"
- "succeeded"
- "validateCustomVirtualAudioEntityWithModelFromPlist:"
- "validationErrors"
- "validationWarnings"
```
