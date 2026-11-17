## BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/Contents/MacOS/BackgroundShortcutRunner`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-4711.1.3.0.0
-  __TEXT.__text: 0x75f14
-  __TEXT.__auth_stubs: 0x2920
-  __TEXT.__objc_stubs: 0x1e40
-  __TEXT.__objc_methlist: 0x60c
+4711.1.4.0.0
+  __TEXT.__text: 0x762cc
+  __TEXT.__auth_stubs: 0x2930
+  __TEXT.__objc_stubs: 0x1e60
+  __TEXT.__objc_methlist: 0x61c
   __TEXT.__const: 0x1640
   __TEXT.__constg_swiftt: 0x420
   __TEXT.__swift5_typeref: 0xbed

   __TEXT.__swift5_proto: 0xbc
   __TEXT.__swift5_types: 0x5c
   __TEXT.__objc_classname: 0x216
-  __TEXT.__objc_methname: 0x242f
-  __TEXT.__objc_methtype: 0x989
-  __TEXT.__oslogstring: 0x928
+  __TEXT.__objc_methname: 0x244f
+  __TEXT.__objc_methtype: 0x98a
+  __TEXT.__oslogstring: 0x918
   __TEXT.__swift5_capture: 0x37c
-  __TEXT.__cstring: 0xeca
+  __TEXT.__cstring: 0xf02
   __TEXT.__swift_as_entry: 0xb0
   __TEXT.__swift_as_ret: 0x110
   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__gcc_except_tab: 0x40
   __TEXT.__unwind_info: 0x10d0
   __TEXT.__eh_frame: 0x3638
-  __DATA_CONST.__auth_got: 0x14a0
+  __DATA_CONST.__auth_got: 0x14a8
   __DATA_CONST.__got: 0xc78
   __DATA_CONST.__auth_ptr: 0x380
   __DATA_CONST.__const: 0x11c8
-  __DATA_CONST.__cfstring: 0x3e0
+  __DATA_CONST.__cfstring: 0x400
   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x88

   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA.__objc_const: 0x8d0
-  __DATA.__objc_selrefs: 0x9c0
+  __DATA.__objc_selrefs: 0x9c8
   __DATA.__objc_ivar: 0xc
   __DATA.__objc_data: 0x3b8
   __DATA.__data: 0x1030

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2316
-  Symbols:   309
-  CStrings:  593
+  Functions: 2318
+  Symbols:   310
+  CStrings:  595
 
Symbols:
+ _NSStringFromSelector
CStrings:
+ "%s client called %{public}@ without stepwise-execution entitlement"
+ "-[WFIsolatedShortcutRunner checkToolKitAccessForMethod:]"
+ "Client is not entitled to perform this operation."
+ "Vv36@0:8@16B24@?28"
+ "checkToolKitAccessForMethod:"
- "%s runToolWithInvocation: called without stepwise-execution entitlement, rejecting"
- "-[WFIsolatedShortcutRunner runToolWithInvocation:]"
- "v36@0:8@16B24@?28"
```
