## AppleMediaServicesUI

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Versions/A/AppleMediaServicesUI`

```diff

-7.6.5.0.0
-  __TEXT.__text: 0x1bdb20
+7.6.5.1.0
+  __TEXT.__text: 0x1bec1c
   __TEXT.__auth_stubs: 0x3fa0
-  __TEXT.__objc_methlist: 0xe6fc
+  __TEXT.__objc_methlist: 0xe73c
   __TEXT.__const: 0xd294
-  __TEXT.__gcc_except_tab: 0x119c
-  __TEXT.__oslogstring: 0x8873
-  __TEXT.__cstring: 0xc9e0
+  __TEXT.__gcc_except_tab: 0x11fc
+  __TEXT.__oslogstring: 0x8a82
+  __TEXT.__cstring: 0xcad0
   __TEXT.__dlopen_cstrs: 0x93b
   __TEXT.__swift5_typeref: 0xe5f4
   __TEXT.__constg_swiftt: 0x50c0

   __TEXT.__swift_as_ret: 0x1c0
   __TEXT.__swift5_protos: 0x2c
   __TEXT.__swift5_mpenum: 0x48
-  __TEXT.__unwind_info: 0x75d0
+  __TEXT.__unwind_info: 0x75e0
   __TEXT.__eh_frame: 0x5d30
   __TEXT.__objc_classname: 0x3284
-  __TEXT.__objc_methname: 0x1fdb5
+  __TEXT.__objc_methname: 0x1fff5
   __TEXT.__objc_methtype: 0x677c
-  __TEXT.__objc_stubs: 0x162a0
-  __DATA_CONST.__got: 0x1788
+  __TEXT.__objc_stubs: 0x16460
+  __DATA_CONST.__got: 0x1790
   __DATA_CONST.__const: 0x1268
   __DATA_CONST.__objc_classlist: 0x978
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x2d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x73c8
+  __DATA_CONST.__objc_selrefs: 0x7430
   __DATA_CONST.__objc_protorefs: 0x108
   __DATA_CONST.__objc_superrefs: 0x5d8
-  __DATA_CONST.__objc_arraydata: 0x348
+  __DATA_CONST.__objc_arraydata: 0x3d8
   __AUTH_CONST.__auth_got: 0x1fe0
-  __AUTH_CONST.__const: 0xac28
-  __AUTH_CONST.__cfstring: 0x9fe0
-  __AUTH_CONST.__objc_const: 0x1d460
+  __AUTH_CONST.__const: 0xac58
+  __AUTH_CONST.__cfstring: 0xa100
+  __AUTH_CONST.__objc_const: 0x1d4c0
   __AUTH_CONST.__objc_intobj: 0x288
-  __AUTH_CONST.__objc_dictobj: 0x2d0
+  __AUTH_CONST.__objc_dictobj: 0x3e8
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x120
   __AUTH.__objc_data: 0x6d38
   __AUTH.__data: 0x5270
-  __DATA.__objc_ivar: 0xfd8
+  __DATA.__objc_ivar: 0xfe0
   __DATA.__data: 0x5970
   __DATA.__bss: 0xa908
   __DATA.__common: 0x240

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12817
-  Symbols:   13860
-  CStrings:  8393
+  Functions: 12825
+  Symbols:   13887
+  CStrings:  8426
 
Symbols:
+ +[AMSUIWebView _resourceTrustRulesForDomains:]
+ +[AMSUIWebView _topDocumentTrustRulesForDomains:]
+ -[AMSUIWebClientContext disableResourceTrustRules]
+ -[AMSUIWebClientContext disableScriptMessageFrameCheck]
+ -[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]
+ GCC_except_table29
+ GCC_except_table65
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableResourceTrustRules
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableScriptMessageFrameCheck
+ ___57-[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]_block_invoke
+ ___75-[AMSUIWebView userContentController:didReceiveScriptMessage:replyHandler:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48s56s_e32_v28?0"NSArray"8B16"NSError"20l
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e20_v20?0B8"NSError"12l
+ ___copy_helper_block_e8_32s40s48s56b64w
+ _objc_msgSend$_handleScriptMessage:logKey:replyHandler:
+ _objc_msgSend$_resourceTrustRulesForDomains:
+ _objc_msgSend$_topDocumentTrustRulesForDomains:
+ _objc_msgSend$characterSetWithCharactersInString:
+ _objc_msgSend$disableResourceTrustRules
+ _objc_msgSend$disableScriptMessageFrameCheck
+ _objc_msgSend$escapedPatternForString:
+ _objc_msgSend$frameInfo
+ _objc_msgSend$isMainFrame
+ _objc_msgSend$protocol
+ _objc_msgSend$securityOrigin
+ _objc_msgSend$setHost:
+ _objc_msgSend$setScheme:
+ _objc_msgSend$stringByTrimmingCharactersInSet:
- GCC_except_table58
- ___block_descriptor_56_e8_32s40s48s_e32_v28?0"NSArray"8B16"NSError"20l
CStrings:
+ "%{public}@: [%{public}@] Rejecting script message from opaque origin"
+ "%{public}@: [%{public}@] Rejecting script message from subframe: %{public}@"
+ "%{public}@: [%{public}@] Rejecting script message from untrusted origin: %{public}@ %{public}@"
+ "%{public}@: [%{public}@] Rejecting script message, context is unavailable"
+ "%{public}@: [%{public}@] Resource trust rules disabled by bag."
+ "([^/@]+\\.)?"
+ "AMS INTERNAL ERROR: Context Unavailable"
+ "AMS INTERNAL ERROR: Untrusted Frame"
+ "AMS INTERNAL ERROR: Web View Deallocated"
+ "TB,R,V_disableResourceTrustRules"
+ "TB,R,V_disableScriptMessageFrameCheck"
+ "[%{public}@] %{public}@ present, resource trust rules will be disabled."
+ "[%{public}@] %{public}@ present, script message frame check will be disabled."
+ "^blob:"
+ "^https://%@%@(:[0-9]+)?/"
+ "_disableResourceTrustRules"
+ "_disableScriptMessageFrameCheck"
+ "_handleScriptMessage:logKey:replyHandler:"
+ "_resourceTrustRulesForDomains:"
+ "_topDocumentTrustRulesForDomains:"
+ "characterSetWithCharactersInString:"
+ "disableResourceTrustRules"
+ "disableScriptMessageFrameCheck"
+ "disableWebResourceTrustRules"
+ "disableWebScriptMessageFrameCheck"
+ "escapedPatternForString:"
+ "frameInfo"
+ "ignore-previous-rules"
+ "isMainFrame"
+ "protocol"
+ "securityOrigin"
+ "setHost:"
+ "stringByTrimmingCharactersInSet:"
```
