## sharingd

> `/usr/libexec/sharingd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2094.70.81.1.1
-  __TEXT.__text: 0x69d590
+2094.70.81.1.4
+  __TEXT.__text: 0x69d938
   __TEXT.__auth_stubs: 0x9340
-  __TEXT.__objc_stubs: 0x29ee0
-  __TEXT.__objc_methlist: 0x1aa0c
+  __TEXT.__objc_stubs: 0x29f60
+  __TEXT.__objc_methlist: 0x1aa84
   __TEXT.__cstring: 0x32396
-  __TEXT.__objc_methname: 0x3de85
+  __TEXT.__objc_methname: 0x3dfe5
   __TEXT.__objc_classname: 0x52d1
-  __TEXT.__objc_methtype: 0x93c9
+  __TEXT.__objc_methtype: 0x93d9
   __TEXT.__const: 0x1bc99
-  __TEXT.__oslogstring: 0x32cc1
+  __TEXT.__oslogstring: 0x32d21
   __TEXT.__gcc_except_tab: 0x2ed0
   __TEXT.__ustring: 0x50
   __TEXT.__dlopen_cstrs: 0x1c0

   __TEXT.__swift5_capture: 0x45d4
   __TEXT.__swift5_protos: 0x224
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__unwind_info: 0x139b0
-  __TEXT.__eh_frame: 0x249a8
+  __TEXT.__unwind_info: 0x139a8
+  __TEXT.__eh_frame: 0x249b0
   __DATA_CONST.__auth_got: 0x49b0
-  __DATA_CONST.__got: 0x2cf0
+  __DATA_CONST.__got: 0x2cf8
   __DATA_CONST.__auth_ptr: 0x1908
   __DATA_CONST.__const: 0x1c0d0
   __DATA_CONST.__cfstring: 0x14780

   __DATA_CONST.__objc_arrayobj: 0x348
   __DATA_CONST.__objc_dictobj: 0x15b8
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA.__objc_const: 0x34be0
-  __DATA.__objc_selrefs: 0xdb28
-  __DATA.__objc_ivar: 0x24f8
+  __DATA.__objc_const: 0x34c88
+  __DATA.__objc_selrefs: 0xdb70
+  __DATA.__objc_ivar: 0x2504
   __DATA.__objc_data: 0x9df0
   __DATA.__data: 0x183ca
   __DATA.__bss: 0x16740

   - /System/Library/PrivateFrameworks/AppleKeyStore.framework/Versions/A/AppleKeyStore
   - /System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit
   - /System/Library/PrivateFrameworks/AuthKitUI.framework/Versions/A/AuthKitUI
+  - /System/Library/PrivateFrameworks/BaseBoard.framework/Versions/A/BaseBoard
   - /System/Library/PrivateFrameworks/Bom.framework/Versions/A/Bom
   - /System/Library/PrivateFrameworks/CacheDelete.framework/Versions/A/CacheDelete
   - /System/Library/PrivateFrameworks/ClassroomKit.framework/Versions/A/ClassroomKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 24817
-  Symbols:   4079
-  CStrings:  22621
+  Functions: 24826
+  Symbols:   4080
+  CStrings:  22640
 
Symbols:
+ _OBJC_CLASS_$_BSAuditToken
CStrings:
+ "Removing legacy persisted Stream ID"
+ "Rendezvous name issued too recently to rotate"
+ "Rotated rendezvous name"
+ "T@\"NSString\",&,V_rendezvousName"
+ "Td,V_rendezvousNameIssuedAt"
+ "T{os_unfair_lock_s=I},R,N,V_rendezvousLock"
+ "_rendezvousLock"
+ "_rendezvousName"
+ "_rendezvousNameIssuedAt"
+ "addParticipantsAllowedForURL:share:auditToken:completionHandler:"
+ "currentRendezvousName"
+ "rendezvousLock"
+ "rendezvousName"
+ "rendezvousNameIssuedAt"
+ "rendezvousNameWithReply:"
+ "rotateRendezvousNameIfIdle"
+ "setRendezvousName:"
+ "setRendezvousNameIssuedAt:"
+ "tokenFromNSXPCConnection:"
+ "v24@0:8@?<v@?@\"NSString\">16"
+ "v40@0:8@\"NSString\"16@\"<SFCompanionServiceManagerClient>\"24@?<v@?@\"<SFCompanionServiceManagerProtocol>\"@\"NSString\"@\"NSString\"@\"NSError\">32"
- "addParticipantsAllowedForURL:share:completionHandler:"
- "v40@0:8@\"NSString\"16@\"<SFCompanionServiceManagerClient>\"24@?<v@?@\"<SFCompanionServiceManagerProtocol>\"@\"NSString\"@\"NSString\"@\"NSString\"@\"NSError\">32"
```
