## AppleMediaServicesUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Versions/A/AppleMediaServicesUI`

```diff

-7.6.5.0.0
-  __TEXT.__text: 0x1dac80
+7.6.5.1.0
+  __TEXT.__text: 0x1dbbf8
   __TEXT.__auth_stubs: 0x45c0
-  __TEXT.__objc_methlist: 0x106d4
+  __TEXT.__objc_methlist: 0x1070c
   __TEXT.__const: 0xcb44
-  __TEXT.__cstring: 0xcd80
-  __TEXT.__oslogstring: 0x968b
+  __TEXT.__cstring: 0xce70
+  __TEXT.__oslogstring: 0x989a
   __TEXT.__ustring: 0x13a
-  __TEXT.__gcc_except_tab: 0x1644
+  __TEXT.__gcc_except_tab: 0x16a4
   __TEXT.__dlopen_cstrs: 0x9b8
   __TEXT.__swift5_typeref: 0xe18c
   __TEXT.__constg_swiftt: 0x501c

   __TEXT.__swift_as_entry: 0x19c
   __TEXT.__swift_as_ret: 0x1dc
   __TEXT.__swift5_mpenum: 0x48
-  __TEXT.__unwind_info: 0x8970
+  __TEXT.__unwind_info: 0x8988
   __TEXT.__eh_frame: 0x5f90
   __TEXT.__objc_classname: 0x37b4
-  __TEXT.__objc_methname: 0x268cf
+  __TEXT.__objc_methname: 0x26a8f
   __TEXT.__objc_methtype: 0x80e1
-  __TEXT.__objc_stubs: 0x1ab40
-  __DATA_CONST.__got: 0x1968
-  __DATA_CONST.__const: 0x3a48
+  __TEXT.__objc_stubs: 0x1ad00
+  __DATA_CONST.__got: 0x1970
+  __DATA_CONST.__const: 0x3a98
   __DATA_CONST.__objc_classlist: 0xa38
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x388
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8930
+  __DATA_CONST.__objc_selrefs: 0x8998
   __DATA_CONST.__objc_protorefs: 0x130
   __DATA_CONST.__objc_superrefs: 0x658
-  __DATA_CONST.__objc_arraydata: 0x340
+  __DATA_CONST.__objc_arraydata: 0x3d0
   __AUTH_CONST.__auth_got: 0x22f0
   __AUTH_CONST.__const: 0x80d8
-  __AUTH_CONST.__cfstring: 0xa820
-  __AUTH_CONST.__objc_const: 0x1ffd8
+  __AUTH_CONST.__cfstring: 0xa940
+  __AUTH_CONST.__objc_const: 0x20038
   __AUTH_CONST.__objc_intobj: 0x330
-  __AUTH_CONST.__objc_dictobj: 0x258
+  __AUTH_CONST.__objc_dictobj: 0x370
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH.__objc_data: 0x79f8
   __AUTH.__data: 0x4cd8
-  __DATA.__objc_ivar: 0x1110
+  __DATA.__objc_ivar: 0x1118
   __DATA.__data: 0x5dd0
   __DATA.__objc_stublist: 0x8
   __DATA.__bss: 0xa0b0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13366
-  Symbols:   15515
-  CStrings:  9431
+  Functions: 13373
+  Symbols:   15542
+  CStrings:  9464
 
Symbols:
+ +[AMSUIWebView _resourceTrustRulesForDomains:]
+ +[AMSUIWebView _topDocumentTrustRulesForDomains:]
+ -[AMSUIWebClientContext disableResourceTrustRules]
+ -[AMSUIWebClientContext disableScriptMessageFrameCheck]
+ -[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]
+ GCC_except_table50
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableResourceTrustRules
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableScriptMessageFrameCheck
+ ___57-[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]_block_invoke
+ ___75-[AMSUIWebView userContentController:didReceiveScriptMessage:replyHandler:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48s56s_e32_v28?0"NSArray"8B16"NSError"20ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e20_v20?0B8"NSError"12lw64l8s56l8s32l8s40l8s48l8
+ ___block_descriptor_81_e8_32s40s48s56s64bs72w_e5_v8?0lw72l8s64l8s32l8s40l8s48l8s56l8
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
- ___block_descriptor_56_e8_32s40s48s_e32_v28?0"NSArray"8B16"NSError"20ls32l8s40l8s48l8
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
+ "TB,R,N,V_disableResourceTrustRules"
+ "TB,R,N,V_disableScriptMessageFrameCheck"
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
