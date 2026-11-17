## gamed

> `/usr/libexec/gamed`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
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

-820.6.10.1.2
-  __TEXT.__text: 0x395790
+820.6.10.1.3
+  __TEXT.__text: 0x395bd8
   __TEXT.__auth_stubs: 0x4850
-  __TEXT.__objc_stubs: 0x1baa0
-  __TEXT.__objc_methlist: 0xe1fc
+  __TEXT.__objc_stubs: 0x1bb20
+  __TEXT.__objc_methlist: 0xe22c
   __TEXT.__const: 0x6fd30
   __TEXT.__objc_classname: 0x2b67
-  __TEXT.__oslogstring: 0x18699
+  __TEXT.__oslogstring: 0x186d9
   __TEXT.__cstring: 0x19f01
-  __TEXT.__objc_methname: 0x23d97
-  __TEXT.__objc_methtype: 0x731d
+  __TEXT.__objc_methname: 0x23e57
+  __TEXT.__objc_methtype: 0x736d
   __TEXT.__gcc_except_tab: 0x32a8
   __TEXT.__swift5_typeref: 0x3630
   __TEXT.__constg_swiftt: 0x2464

   __TEXT.__swift_as_ret: 0x640
   __TEXT.__swift5_protos: 0x34
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__unwind_info: 0x9c50
+  __TEXT.__unwind_info: 0x9c60
   __TEXT.__eh_frame: 0xc930
   __DATA_CONST.__auth_got: 0x2440
-  __DATA_CONST.__got: 0x1f78
+  __DATA_CONST.__got: 0x1f80
   __DATA_CONST.__auth_ptr: 0xff8
   __DATA_CONST.__const: 0x1c858
   __DATA_CONST.__cfstring: 0xbfe0

   __DATA_CONST.__objc_dictobj: 0x280
   __DATA_CONST.__objc_arrayobj: 0x138
   __DATA.__objc_const: 0x214f0
-  __DATA.__objc_selrefs: 0x8250
+  __DATA.__objc_selrefs: 0x8278
   __DATA.__objc_ivar: 0x708
   __DATA.__objc_data: 0x77e0
   __DATA.__data: 0x5708

   - /System/Library/PrivateFrameworks/AtomicsInternal.framework/Versions/A/AtomicsInternal
   - /System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit
   - /System/Library/PrivateFrameworks/BackgroundSystemTasks.framework/Versions/A/BackgroundSystemTasks
+  - /System/Library/PrivateFrameworks/BaseBoard.framework/Versions/A/BaseBoard
   - /System/Library/PrivateFrameworks/BiomeLibrary.framework/Versions/A/BiomeLibrary
   - /System/Library/PrivateFrameworks/BiomeStreams.framework/Versions/A/BiomeStreams
   - /System/Library/PrivateFrameworks/BoardServices.framework/Versions/A/BoardServices

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13323
-  Symbols:   2579
-  CStrings:  10585
+  Functions: 13331
+  Symbols:   2580
+  CStrings:  10594
 
Symbols:
+ _OBJC_CLASS_$_BSAuditToken
CStrings:
+ "B48@0:8{?=[8I]}16"
+ "B56@0:8@16{?=[8I]}24"
+ "B56@0:8{?=[8I]}16^?48"
+ "appIsFromUntrustedSignerCategory:"
+ "appIsFromUntrustedSignerCategory: csops_audittoken failed with err=%d"
+ "appIsFromUntrustedSignerCategory:csopsFnValidCat:"
+ "clientClassForBundleID:"
+ "shouldRejectUntrustedClaimToBundleID:auditToken:"
+ "tokenFromAuditToken:"
```
