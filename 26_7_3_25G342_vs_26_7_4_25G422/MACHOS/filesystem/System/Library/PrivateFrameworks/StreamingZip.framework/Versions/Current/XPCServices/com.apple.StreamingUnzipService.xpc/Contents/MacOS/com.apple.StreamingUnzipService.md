## com.apple.StreamingUnzipService

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/Current/XPCServices/com.apple.StreamingUnzipService.xpc/Contents/MacOS/com.apple.StreamingUnzipService`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA.__objc_const`
- `__DATA.__objc_protorefs`
- `__DATA.__objc_classrefs`
- `__DATA.__objc_superrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-252.0.0.0.0
-  __TEXT.__text: 0x1a7c8
-  __TEXT.__auth_stubs: 0xa70
-  __TEXT.__objc_stubs: 0x2320
-  __TEXT.__objc_methlist: 0xf04
+252.0.0.700.1
+  __TEXT.__text: 0x1b48c
+  __TEXT.__auth_stubs: 0xaf0
+  __TEXT.__objc_stubs: 0x2360
+  __TEXT.__objc_methlist: 0xf1c
   __TEXT.__const: 0x118
-  __TEXT.__cstring: 0x6ebc
+  __TEXT.__cstring: 0x7555
   __TEXT.__gcc_except_tab: 0x64
-  __TEXT.__objc_classname: 0x20e
-  __TEXT.__objc_methname: 0x2f02
-  __TEXT.__objc_methtype: 0xd0c
+  __TEXT.__objc_classname: 0x219
+  __TEXT.__objc_methname: 0x2f43
+  __TEXT.__objc_methtype: 0xd29
   __TEXT.__oslogstring: 0x518
-  __TEXT.__unwind_info: 0x360
+  __TEXT.__unwind_info: 0x370
   __TEXT.__eh_frame: 0xb4
-  __DATA_CONST.__auth_got: 0x548
+  __DATA_CONST.__auth_got: 0x588
   __DATA_CONST.__got: 0x78
   __DATA_CONST.__auth_ptr: 0x18
-  __DATA_CONST.__const: 0x320
-  __DATA_CONST.__cfstring: 0x37e0
+  __DATA_CONST.__const: 0x340
+  __DATA_CONST.__cfstring: 0x3b00
   __DATA_CONST.__objc_classlist: 0x60
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA.__objc_const: 0x1ef0
-  __DATA.__objc_selrefs: 0xa40
+  __DATA.__objc_selrefs: 0xa48
   __DATA.__objc_protorefs: 0x10
   __DATA.__objc_classrefs: 0x100
   __DATA.__objc_superrefs: 0x50
   __DATA.__objc_ivar: 0x194
   __DATA.__objc_data: 0x3c0
   __DATA.__data: 0x378
-  __DATA.__bss: 0xc1
+  __DATA.__bss: 0xe1
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
+  - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /usr/lib/libAppleArchive.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 331
-  Symbols:   214
-  CStrings:  1301
+  Functions: 334
+  Symbols:   222
+  CStrings:  1331
 
Symbols:
+ __qtn_proc_alloc
+ __qtn_proc_apply_to_self
+ __qtn_proc_free
+ __qtn_proc_get_flags
+ __xpc_peer_requirement_match_token
+ _qtn_proc_init_with_pid
+ _xpc_copy_description
+ _xpc_peer_requirement_create_platform_identity
CStrings:
+ "21:44:34"
+ "B72@0:8^B16{?=[8I]}24@56^@64"
+ "Caller %@ has %@ entitlement; forcing untrusted quarantine handling"
+ "Caller %@ has %@ entitlement; trusting any supplied quarantine parameters, or none if unspecified"
+ "Caller %@ has process quarantine flags 0x%x"
+ "Caller %@ is NOT a platform binary; ignoring supplied quarantine parameters, and adopting caller's process quarantine state (XPC: %s)"
+ "Caller %@ is a platform binary; trusting any supplied quarantine parameters, or none if unspecified"
+ "Caller %@ is not quarantined"
+ "Caller %@ quarantine flags 0x%x already adopted; skipping redundant apply"
+ "Failed to apply caller %@ quarantine state to extractor process."
+ "Failed to apply caller %@ quarantine state to extractor process. : %@"
+ "Failed to create qtn_proc object."
+ "Failed to create qtn_proc object. : %@"
+ "Failed to read quarantine state for caller %@."
+ "Failed to read quarantine state for caller %@. : %@"
+ "Failed to read quarantine state for caller %@: QTN_MATCH_UNAVAILABLE"
+ "Failed to read quarantine state for caller %@: QTN_MATCH_UNAVAILABLE : %@"
+ "Failed to read quarantine state for caller %@: unknown quarantine error %d"
+ "Failed to read quarantine state for caller %@: unknown quarantine error %d : %@"
+ "IPCSupport"
+ "Nov  8 2026"
+ "Quarantine is unavailable/not supported; treating caller %@ as not quarantined"
+ "SZExtractorQuarantineErrorDomain"
+ "Unable to determine quarantine state for caller %@."
+ "Unable to determine quarantine state for caller %@. : %@"
+ "Unexpectedly handling IPC without necessary support compiled in!"
+ "Unexpectedly handling IPC without necessary support compiled in! : %@"
+ "Unknown Process Name"
+ "_AdoptCallerQuarantineState"
+ "_GetCallerIsTrustedQuarantineProvider"
+ "_getShouldTrustQuarantineOptions:forAuditToken:connection:error:"
+ "com.apple.private.SZExtractor.force-untrusted-quarantine-provider"
+ "com.apple.private.SZExtractor.trusted-quarantine-provider"
- "00:10:30"
- "Nov  3 2026"
- "Unknown Process Name (pid %d)"
```
