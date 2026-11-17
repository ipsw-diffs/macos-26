## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Versions/A/Sharing`

```diff

-2094.70.81.1.1
-  __TEXT.__text: 0x31661c
+2094.70.81.1.4
+  __TEXT.__text: 0x31735c
   __TEXT.__auth_stubs: 0x4a30
-  __TEXT.__objc_methlist: 0x12ae4
-  __TEXT.__cstring: 0x2bd05
-  __TEXT.__const: 0x1f39c
-  __TEXT.__gcc_except_tab: 0x34e0
-  __TEXT.__oslogstring: 0xb11e
+  __TEXT.__objc_methlist: 0x12adc
+  __TEXT.__cstring: 0x2bcd5
+  __TEXT.__const: 0x1f3ac
+  __TEXT.__gcc_except_tab: 0x34f4
+  __TEXT.__oslogstring: 0xb4de
   __TEXT.__dlopen_cstrs: 0x5ab
   __TEXT.__ustring: 0x18
   __TEXT.__swift5_typeref: 0x80c5

   __TEXT.__swift_as_entry: 0x380
   __TEXT.__swift_as_ret: 0x374
   __TEXT.__swift5_mpenum: 0xa8
-  __TEXT.__unwind_info: 0xce30
+  __TEXT.__unwind_info: 0xce68
   __TEXT.__eh_frame: 0xcb54
   __TEXT.__objc_classname: 0x299d
-  __TEXT.__objc_methname: 0x28e61
-  __TEXT.__objc_methtype: 0x5fe3
-  __TEXT.__objc_stubs: 0x15ec0
-  __DATA_CONST.__got: 0x10d8
-  __DATA_CONST.__const: 0x2d90
+  __TEXT.__objc_methname: 0x28e91
+  __TEXT.__objc_methtype: 0x6023
+  __TEXT.__objc_stubs: 0x15f00
+  __DATA_CONST.__got: 0x10e0
+  __DATA_CONST.__const: 0x2d88
   __DATA_CONST.__objc_classlist: 0x810
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x330
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x85b0
+  __DATA_CONST.__objc_selrefs: 0x85c8
   __DATA_CONST.__objc_protorefs: 0x1c0
   __DATA_CONST.__objc_classrefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x518
   __DATA_CONST.__objc_arraydata: 0x2f0
   __AUTH_CONST.__auth_got: 0x2530
-  __AUTH_CONST.__const: 0x17438
-  __AUTH_CONST.__cfstring: 0x11e40
-  __AUTH_CONST.__objc_const: 0x33810
+  __AUTH_CONST.__const: 0x17488
+  __AUTH_CONST.__cfstring: 0x11dc0
+  __AUTH_CONST.__objc_const: 0x337e8
   __AUTH_CONST.__objc_intobj: 0x498
   __AUTH_CONST.__objc_dictobj: 0x398
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH.__objc_data: 0x2a78
   __AUTH.__data: 0x1f20
-  __DATA.__objc_ivar: 0x2000
+  __DATA.__objc_ivar: 0x1ffc
   __DATA.__data: 0xa958
-  __DATA.__bss: 0x338f0
+  __DATA.__bss: 0x33900
   __DATA.__common: 0x80
   __DATA_DIRTY.__objc_data: 0x41a0
   __DATA_DIRTY.__data: 0x21a0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 19995
-  Symbols:   20085
-  CStrings:  14760
+  Functions: 20012
+  Symbols:   20093
+  CStrings:  14779
 
Symbols:
+ +[SFCollaborationUtilities addParticipantsAllowedForURL:share:auditToken:completionHandler:]
+ -[SFCollaborationCloudSharingRequest auditToken]
+ -[SFCollaborationCloudSharingRequest setAuditToken:]
+ -[SFCompanionManager currentRendezvousName]
+ GCC_except_table156
+ GCC_except_table158
+ GCC_except_table291
+ _OBJC_CLASS_$_NSCache
+ _OBJC_IVAR_$_SFCollaborationCloudSharingRequest._auditToken
+ _SFBundleIDFromAuditToken
+ _SFInvalidateCanShareURLCache
+ _SFProcessCanShareURL
+ _SFRealPathForFileURL
+ ___43-[SFCompanionManager currentRendezvousName]_block_invoke
+ ___92+[SFCollaborationUtilities addParticipantsAllowedForURL:share:auditToken:completionHandler:]_block_invoke
+ ___SFRealPathForFileURL_block_invoke
+ ____getCanShareURLCache_block_invoke
+ ___block_descriptor_40_e8_32bs_e83_v40?0"<SFCompanionServiceManagerProtocol>"8"NSString"16"NSString"24"NSError"32l
+ ___block_descriptor_40_e8_32s_e83_v40?0"<SFCompanionServiceManagerProtocol>"8"NSString"16"NSString"24"NSError"32l
+ ___block_descriptor_48_e8_32s40r_e18_v16?0"NSString"8l
+ __canShareURLCache
+ __canShareURLCacheToken
+ _objc_msgSend$currentRendezvousName
+ _objc_msgSend$realToken
+ _objc_msgSend$rendezvousNameWithReply:
- +[SFCollaborationUtilities addParticipantsAllowedForURL:share:completionHandler:]
- +[SFCompanionService serviceFromDictionary:]
- -[SFCompanionManager deviceName]
- -[SFCompanionManager setDeviceName:]
- -[SFCompanionService deviceName]
- -[SFCompanionService setDeviceName:]
- GCC_except_table146
- GCC_except_table152
- GCC_except_table154
- _OBJC_IVAR_$_SFCompanionManager._deviceName
- _OBJC_IVAR_$_SFCompanionService._deviceName
- ___81+[SFCollaborationUtilities addParticipantsAllowedForURL:share:completionHandler:]_block_invoke
- ___SFRealpathForFileURL_block_invoke
- ___block_descriptor_40_e8_32bs_e96_v48?0"<SFCompanionServiceManagerProtocol>"8"NSString"16"NSString"24"NSString"32"NSError"40l
- ___block_descriptor_40_e8_32s_e96_v48?0"<SFCompanionServiceManagerProtocol>"8"NSString"16"NSString"24"NSString"32"NSError"40l
- _kSFCompanionServiceDeviceNameKey
- _objc_msgSend$setDeviceName:
CStrings:
+ "%@|%@"
+ "@\"BSAuditToken\""
+ "Cannot create sharing URL because calling process %@ has no access to file %@"
+ "Cannot request sharing URL because calling process %@ has no access to file %@"
+ "Cannot request whether add participants is allowed because calling process %@ has no access to file %@"
+ "Cannot share URL %@ (resolved to %@) for a process without read permissions"
+ "Cannot share URL %@ (resolved to %@) for security reasons"
+ "ERROR_MESSAGE_FILE_NO_ACCESS"
+ "Error retrieving proxy object. Returned values (proxy = %@, deviceID = %@, deviceIP = %@, error = %@)"
+ "No manager proxy when asking for rendezvous name"
+ "SFCompanionService (serviceType = %@, deviceID = %@, managerID = %@, identifier = %@)"
+ "T@\"BSAuditToken\",&,N,V_auditToken"
+ "Timed out asking for rendezvous name"
+ "URL %{private}@ does not exist, skipping sandbox access check on the assumption that it is a placeholder"
+ "_auditToken"
+ "addParticipantsAllowedForURL:share:auditToken:completionHandler:"
+ "currentRendezvousName"
+ "file-read-data"
+ "realToken"
+ "realpath failed for URL %{private}@ with code %ld, falling back to path"
+ "rendezvousNameWithReply:"
+ "sandbox check failure %{private}@ (resolved to %{private}@): erno:%d - error:%s"
+ "sandbox_check_by_audit_token returned %d for resolved URL %@ (unresolved path: %@)"
+ "setAuditToken:"
+ "setting cached value for SFProcessCanShareURL canShare: %d with key: %{private}@"
+ "using cache for SFProcessCanShareURL with cached key: %{private}@ cached value: %s"
+ "v24@0:8@?<v@?@\"NSString\">16"
+ "v40@0:8@\"NSString\"16@\"<SFCompanionServiceManagerClient>\"24@?<v@?@\"<SFCompanionServiceManagerProtocol>\"@\"NSString\"@\"NSString\"@\"NSError\">32"
+ "v40@?0@\"<SFCompanionServiceManagerProtocol>\"8@\"NSString\"16@\"NSString\"24@\"NSError\"32"
+ "v72@0:8@16@24{?=[8I]}32@?64"
- "DeviceID"
- "Error retrieving proxy object. Returned values (proxy = %@, deviceName = %@, deviceID = %@, deviceIP = %@, error = %@)"
- "IPAddress"
- "ManagerID"
- "SFCompanionService (serviceType = %@, deviceName = %@, deviceID = %@, managerID = %@, identifier = %@)"
- "ServiceIdentifier"
- "addParticipantsAllowedForURL:share:completionHandler:"
- "device_name"
- "serviceFromDictionary:"
- "v40@0:8@\"NSString\"16@\"<SFCompanionServiceManagerClient>\"24@?<v@?@\"<SFCompanionServiceManagerProtocol>\"@\"NSString\"@\"NSString\"@\"NSString\"@\"NSError\">32"
- "v48@?0@\"<SFCompanionServiceManagerProtocol>\"8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSError\"40"
```
