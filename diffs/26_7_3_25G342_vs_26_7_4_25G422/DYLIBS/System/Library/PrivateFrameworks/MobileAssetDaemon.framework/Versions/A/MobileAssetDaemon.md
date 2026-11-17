## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/Versions/A/MobileAssetDaemon`

```diff

-1837.160.15.698.1
-  __TEXT.__text: 0x2baff4
+1837.160.15.700.3
+  __TEXT.__text: 0x2bb4f4
   __TEXT.__auth_stubs: 0x2150
-  __TEXT.__objc_methlist: 0x12844
+  __TEXT.__objc_methlist: 0x1286c
   __TEXT.__const: 0x183a
-  __TEXT.__cstring: 0x3ec89
-  __TEXT.__oslogstring: 0x5d264
+  __TEXT.__cstring: 0x3ed29
+  __TEXT.__oslogstring: 0x5d474
   __TEXT.__gcc_except_tab: 0xea3c
   __TEXT.__constg_swiftt: 0xf0
   __TEXT.__swift5_typeref: 0x146

   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_proto: 0x24
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x5630
+  __TEXT.__unwind_info: 0x5638
   __TEXT.__eh_frame: 0x90
   __TEXT.__objc_classname: 0x10ee
-  __TEXT.__objc_methname: 0x46eb6
+  __TEXT.__objc_methname: 0x46f52
   __TEXT.__objc_methtype: 0x46c4
-  __TEXT.__objc_stubs: 0x26e20
+  __TEXT.__objc_stubs: 0x26e80
   __DATA_CONST.__got: 0xfe0
-  __DATA_CONST.__const: 0x1110
+  __DATA_CONST.__const: 0x1188
   __DATA_CONST.__objc_classlist: 0x470
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xac48
+  __DATA_CONST.__objc_selrefs: 0xac60
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x350
-  __DATA_CONST.__objc_arraydata: 0xd60
+  __DATA_CONST.__objc_arraydata: 0xd70
   __AUTH_CONST.__auth_got: 0x10b8
   __AUTH_CONST.__const: 0x3330
-  __AUTH_CONST.__cfstring: 0x32720
+  __AUTH_CONST.__cfstring: 0x32780
   __AUTH_CONST.__objc_const: 0x184c8
   __AUTH_CONST.__objc_arrayobj: 0x2e8
   __AUTH_CONST.__objc_intobj: 0x13b0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7293
-  Symbols:   16258
-  CStrings:  19049
+  Functions: 7296
+  Symbols:   16264
+  CStrings:  19058
 
Symbols:
+ +[MADAutoAssetAuthorizationPolicy _accessibleAssetTypesContainSoftwareUpdateAssetType:]
+ +[MADAutoAssetAuthorizationPolicy _assetTypes:authorizedForAccessibleAssetTypes:]
+ +[MADAutoAssetAuthorizationPolicy authorizationAssetTypesFromMessage:alreadyOnStateQueue:]
+ _objc_msgSend$_accessibleAssetTypesContainSoftwareUpdateAssetType:
+ _objc_msgSend$_assetTypes:authorizedForAccessibleAssetTypes:
+ _objc_msgSend$authorizationAssetTypesFromMessage:alreadyOnStateQueue:
CStrings:
+ "; the stage-target-all sentinel needs a software-update asset type"
+ "CheerSecurityFizzC"
+ "Loaded built-in MobileAssetDaemon_Framework Nov  8 2026 22:19:16"
+ "MAAutoAssetStage-target-all-asset-types"
+ "_accessibleAssetTypesContainSoftwareUpdateAssetType:"
+ "_assetTypes:authorizedForAccessibleAssetTypes:"
+ "authorizationAssetTypesFromMessage:alreadyOnStateQueue:"
+ "com.apple.MobileAsset.PSUSConfig.AutoAssetSetTargets"
+ "{_assetTypes:authorizedForAccessibleAssetTypes:} accessible-asset-types entitlement is %{public}@, expected an array | assetType:%{public}@"
+ "{_assetTypes:authorizedForAccessibleAssetTypes:} asset type not covered by accessible-asset-types entitlement (exact entry or com.apple.MobileAsset.<prefix>.* wildcard)%{public}@ | assetType:%{public}@, accessibleAssetTypes:%{public}@"
+ "{authorizationAssetTypesFromMessage} Found asset types: %{public}@, for message: %{public}@"
+ "{authorizationAssetTypesFromMessage} Found multiple asset types (not formally supported): %{public}@, for message: %{public}@, authorizing all of them"
+ "{isConnection:authorizedForMessage:}(%{public}@) Client does not have all requested asset types: %{public}@ (found: %{public}@)"
+ "{isConnection:authorizedForMessage:}(%{public}@) Ignoring bypass entitlement of unexpected type: %{public}@ (expected a BOOL or a string)"
+ "{isConnection:authorizedForMessage:}(%{public}@) Request had no asset type listed for message: %{public}@"
- "CheerSecurityFizzB"
- "Loaded built-in MobileAssetDaemon_Framework Nov  5 2026 20:47:18"
- "{MADAutoAssetAuthorizationPolicy}(%{public}@) Client does not have requested asset type: %@ (found: %@)"
- "{MADAutoAssetAuthorizationPolicy}(%{public}@) Request had no asset type listed for message: %{public}@"
- "{MADAutoAssetAuthorizationPolicy}(authorizationAssetTypeFromMessage) Found asset type: %{public}@, for message: %{public}@"
- "{MADAutoAssetAuthorizationPolicy}(authorizationAssetTypeFromMessage) Found multiple asset types: %{public}@, for message: %{public}@"
```
