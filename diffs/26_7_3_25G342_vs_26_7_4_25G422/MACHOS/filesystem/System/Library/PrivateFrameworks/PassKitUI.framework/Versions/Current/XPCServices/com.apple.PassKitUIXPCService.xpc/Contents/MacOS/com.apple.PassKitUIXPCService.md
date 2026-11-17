## com.apple.PassKitUIXPCService

> `/System/Library/PrivateFrameworks/PassKitUI.framework/Versions/Current/XPCServices/com.apple.PassKitUIXPCService.xpc/Contents/MacOS/com.apple.PassKitUIXPCService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-384.0.0.0.0
-  __TEXT.__text: 0x2680
-  __TEXT.__auth_stubs: 0x260
+384.1.0.0.0
+  __TEXT.__text: 0x2a68
+  __TEXT.__auth_stubs: 0x2f0
   __TEXT.__objc_stubs: 0x8c0
   __TEXT.__objc_methlist: 0x374
-  __TEXT.__const: 0x58
-  __TEXT.__cstring: 0x3bd
-  __TEXT.__oslogstring: 0x1cc
-  __TEXT.__objc_classname: 0x3e
+  __TEXT.__const: 0x70
+  __TEXT.__cstring: 0x403
+  __TEXT.__oslogstring: 0x25c
+  __TEXT.__objc_classname: 0x3f
   __TEXT.__objc_methtype: 0x263
   __TEXT.__objc_methname: 0xcce
-  __TEXT.__unwind_info: 0xd8
-  __DATA_CONST.__auth_got: 0x138
+  __TEXT.__unwind_info: 0xe8
+  __DATA_CONST.__auth_got: 0x180
   __DATA_CONST.__got: 0xc8
-  __DATA_CONST.__const: 0x180
-  __DATA_CONST.__cfstring: 0x260
+  __DATA_CONST.__const: 0x1b0
+  __DATA_CONST.__cfstring: 0x2a0
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8

   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
+  - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/PrivateFrameworks/AppleAccount.framework/Versions/A/AppleAccount
   - /System/Library/PrivateFrameworks/Bom.framework/Versions/A/Bom
   - /System/Library/PrivateFrameworks/PassKitCore.framework/Versions/A/PassKitCore
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 46
-  Symbols:   81
-  CStrings:  208
+  Functions: 51
+  Symbols:   95
+  CStrings:  213
 
Symbols:
+ _CFBooleanGetTypeID
+ _CFBooleanGetValue
+ _CFGetTypeID
+ _CFRelease
+ _PKPassKitUIXPCServiceAddEntitlement
+ _PKPassKitUIXPCServiceAddSilentlyEntitlement
+ _PKPassKitUIXPCServiceIsEntitled
+ _PKPassKitUIXPCServicePeerIsEntitled
+ _PKPassKitUIXPCServiceTaskIsEntitled
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateWithAuditToken
+ _xpc_connection_cancel
+ _xpc_connection_get_audit_token
+ _xpc_connection_get_pid
CStrings:
+ "@16@?0@\"NSString\"8"
+ "[PassKitUIXPCService] failed to read entitlement %{public}@: %{public}@"
+ "[PassKitUIXPCService] refusing connection from unentitled peer, pid %d."
+ "com.apple.passes.add"
+ "com.apple.passes.add-silently"
```
