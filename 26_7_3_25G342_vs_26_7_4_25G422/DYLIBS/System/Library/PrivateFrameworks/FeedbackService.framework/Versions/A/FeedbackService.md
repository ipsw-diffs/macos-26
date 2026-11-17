## FeedbackService

> `/System/Library/PrivateFrameworks/FeedbackService.framework/Versions/A/FeedbackService`

```diff

-208.3.0.0.0
-  __TEXT.__text: 0x92f6c
+208.3.1.0.0
+  __TEXT.__text: 0x92fd8
   __TEXT.__auth_stubs: 0x14b0
   __TEXT.__objc_methlist: 0x1374
   __TEXT.__const: 0xc0b0
   __TEXT.__cstring: 0x2848
   __TEXT.__ustring: 0xd8
-  __TEXT.__oslogstring: 0x104f
+  __TEXT.__oslogstring: 0x107f
   __TEXT.__gcc_except_tab: 0x104
   __TEXT.__constg_swiftt: 0x23d4
   __TEXT.__swift5_typeref: 0x2942

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3748
+  Functions: 3750
   Symbols:   2228
-  CStrings:  1112
+  CStrings:  1113
 
Functions:
~ +[FBKSSharedConstants appleSeedURLFromDefaults:withEnvironment:] : 368 -> 340
~ +[FBKSSharedConstants environment] : 132 -> 152
~ +[FBKSSharedConstants overrideEnvironment:host:] : 288 -> 340
+ _OUTLINED_FUNCTION_1
+ +[FBKSSharedConstants overrideEnvironment:host:].cold.1
~ +[FBKSSharedConstants _deriveSystemVersion].cold.1 : 68 -> 56
CStrings:
+ "Ignoring environment override on non-internal build"
```
