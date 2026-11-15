## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/Versions/A/AirPlayReceiver`

```diff

-960.13.25.2.0
-  __TEXT.__text: 0xe1270
+960.13.25.4.0
+  __TEXT.__text: 0xe1428
   __TEXT.__auth_stubs: 0x35d0
   __TEXT.__objc_methlist: 0x924
   __TEXT.__const: 0xd155
   __TEXT.__dlopen_cstrs: 0xad
   __TEXT.__gcc_except_tab: 0x720
-  __TEXT.__cstring: 0x2a58a
+  __TEXT.__cstring: 0x2a5cb
   __TEXT.__unwind_info: 0x1158
   __TEXT.__objc_classname: 0x12c
   __TEXT.__objc_methname: 0x1f66

   __DATA_CONST.__objc_arraydata: 0x10
   __AUTH_CONST.__auth_got: 0x1af8
   __AUTH_CONST.__const: 0x4b50
-  __AUTH_CONST.__cfstring: 0xa600
+  __AUTH_CONST.__cfstring: 0xa620
   __AUTH_CONST.__objc_const: 0x1358
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0x1e0

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/Versions/A/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1336
-  Symbols:   3319
-  CStrings:  4887
+  Functions: 1337
+  Symbols:   3320
+  CStrings:  4889
 
Symbols:
+ GCC_except_table1049
+ GCC_except_table1057
+ GCC_except_table1059
+ GCC_except_table923
+ GCC_except_table942
+ GCC_except_table993
+ GCC_except_table997
+ _airplayReqProcessor_ensurePairingServices
- GCC_except_table1048
- GCC_except_table1056
- GCC_except_table1058
- GCC_except_table922
- GCC_except_table941
- GCC_except_table992
- GCC_except_table996
CStrings:
+ "960.13.25.4"
+ "CoreUtils"
+ "OSStatus APPairingServicesCoreUtilsCreate(CFAllocatorRef, APPairingServicesRef *)"
+ "OSStatus _StartServers(AirPlayReceiverServerRef)"
+ "OSStatus airplayReqProcessor_ensurePairingServices(APReceiverRequestProcessorRef, Boolean, APSTransportMessageProcessingStatus *)"
+ "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, CFDataRef, CFDataRef *, Boolean *)"
+ "[%{ptr}] APPairingServicesCoreUtils created.\n"
+ "[%{ptr}] Created %s pairing services [%{ptr}]\n"
+ "_StartServers"
+ "airplayReqProcessor_ensurePairingServices"
+ "disablePairSetupThrottling"
+ "legacy"
- "960.13.25.2"
- "OSStatus APPairingServicesCoreUtilsCreate(CFAllocatorRef, Boolean, APPairingServicesRef *)"
- "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, APSecurityMode, CFDataRef, CFDataRef *, Boolean *)"
- "[%{ptr}] APPairingServicesCoreUtils (%s) created.\n"
- "[%{ptr}] Created legacy pairing services [%{ptr}]\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-setup.\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-verify\n"
- "private"
- "public"
- "void _StartServers(AirPlayReceiverServerRef)"
```
