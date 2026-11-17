## AppKit

> `/System/Library/Frameworks/AppKit.framework/Versions/C/AppKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-2685.70.102.0.0
-  __TEXT.__text: 0x10e9050
+2685.70.102.1.0
+  __TEXT.__text: 0x10e93b4
   __TEXT.__auth_stubs: 0x12cf0
-  __TEXT.__objc_methlist: 0xdacac
-  __TEXT.__const: 0x2b508
+  __TEXT.__objc_methlist: 0xdacdc
+  __TEXT.__const: 0x2b518
   __TEXT.__dlopen_cstrs: 0x12e5
   __TEXT.__cstring: 0xc4561
   __TEXT.__swift5_typeref: 0xee16

   __TEXT.__swift5_capture: 0x3910
   __TEXT.__swift5_protos: 0x134
   __TEXT.__swift5_mpenum: 0x58
-  __TEXT.__oslogstring: 0x1d04c
+  __TEXT.__oslogstring: 0x1d0e9
   __TEXT.__swift_as_entry: 0x124
   __TEXT.__swift_as_ret: 0xe4
-  __TEXT.__gcc_except_tab: 0xb93d4
+  __TEXT.__gcc_except_tab: 0xb9420
   __TEXT.__swift5_types2: 0x4
   __TEXT.__ustring: 0x191a
   __TEXT.__dof_NSTrackin: 0x7e7
   __TEXT.__dof_NSApplica: 0x809
   __TEXT.__dof_NSAccessi: 0x1eb
-  __TEXT.__unwind_info: 0x5c750
+  __TEXT.__unwind_info: 0x5c770
   __TEXT.__eh_frame: 0x687c
   __TEXT.__objc_classname: 0x1b47f
-  __TEXT.__objc_methname: 0x171937
-  __TEXT.__objc_methtype: 0x45a82
-  __TEXT.__objc_stubs: 0x10c2c0
+  __TEXT.__objc_methname: 0x171a57
+  __TEXT.__objc_methtype: 0x45a92
+  __TEXT.__objc_stubs: 0x10c340
   __DATA_CONST.__got: 0x5de0
   __DATA_CONST.__const: 0xaf60
   __DATA_CONST.__objc_classlist: 0x5068

   __DATA_CONST.__objc_catlist: 0x218
   __DATA_CONST.__objc_protolist: 0x1318
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x513f0
+  __DATA_CONST.__objc_selrefs: 0x51418
   __DATA_CONST.__objc_protorefs: 0x740
   __DATA_CONST.__objc_superrefs: 0x3fa8
   __DATA_CONST.__objc_arraydata: 0x4b50
   __AUTH_CONST.__auth_got: 0x9690
   __AUTH_CONST.__const: 0x41e78
   __AUTH_CONST.__cfstring: 0x9cf20
-  __AUTH_CONST.__objc_const: 0x10df98
+  __AUTH_CONST.__objc_const: 0x10dfc8
   __AUTH_CONST.__objc_intobj: 0x2d48
   __AUTH_CONST.__objc_arrayobj: 0x1ad0
   __AUTH_CONST.__objc_doubleobj: 0x410

   __DATA.__data: 0x1aa60
   __DATA.__bss: 0x2f2b0
   __DATA.__common: 0x10c8
-  __DATA_DIRTY.__objc_ivar: 0x4448
+  __DATA_DIRTY.__objc_ivar: 0x444c
   __DATA_DIRTY.__objc_data: 0xb040
   __DATA_DIRTY.__data: 0x3440
   __DATA_DIRTY.__crash_info: 0x148

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 97423
-  Symbols:   157506
-  CStrings:  88701
+  Functions: 97428
+  Symbols:   157514
+  CStrings:  88711
 
Symbols:
+ -[NSRemoteSavePanel _URLsToCommit]
+ -[NSRemoteSavePanel _replyBlockAllowingRetryForURLs:continuing:]
+ -[NSRemoteSavePanel _retryAfterPresentingErrorRequestedByHost]
+ -[NSRemoteSavePanel pendingRetryURLs]
+ -[NSRemoteSavePanel setPendingRetryURLs:]
+ ___64-[NSRemoteSavePanel _replyBlockAllowingRetryForURLs:continuing:]_block_invoke
+ _objc_msgSend$_URLsToCommit
+ _objc_msgSend$_replyBlockAllowingRetryForURLs:continuing:
+ _objc_msgSend$pendingRetryURLs
+ _objc_msgSend$setPendingRetryURLs:
- -[NSRemoteSavePanel _retryAfterPresentingError]
- GCC_except_table492
CStrings:
+ "@?32@0:8@16@?24"
+ "Ignoring retry request from host. The host did not reject any URLs."
+ "Ignoring retry request from host. The panel's URLs changed after the host rejected them."
+ "T@\"NSArray\",C,N,V_pendingRetryURLs"
+ "_URLsToCommit"
+ "_pendingRetryURLs"
+ "_replyBlockAllowingRetryForURLs:continuing:"
+ "_retryAfterPresentingErrorRequestedByHost"
+ "pendingRetryURLs"
+ "setPendingRetryURLs:"
```
