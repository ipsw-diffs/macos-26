## ShareMail

> `/System/Library/PrivateFrameworks/ShareKit.framework/Versions/A/PlugIns/ShareMail.appex/Contents/MacOS/ShareMail`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-2094.70.81.1.1
-  __TEXT.__text: 0x2d98
-  __TEXT.__auth_stubs: 0x230
+2094.70.81.1.4
+  __TEXT.__text: 0x2ddc
+  __TEXT.__auth_stubs: 0x240
   __TEXT.__objc_stubs: 0x8e0
   __TEXT.__objc_methlist: 0x74
   __TEXT.__const: 0x20

   __TEXT.__objc_classname: 0x3e
   __TEXT.__objc_methname: 0x811
   __TEXT.__objc_methtype: 0x48
-  __TEXT.__unwind_info: 0x110
-  __DATA_CONST.__auth_got: 0x128
+  __TEXT.__unwind_info: 0x118
+  __DATA_CONST.__auth_got: 0x130
   __DATA_CONST.__got: 0xe8
   __DATA_CONST.__const: 0x2d0
   __DATA_CONST.__cfstring: 0x340

   - /System/Library/PrivateFrameworks/ShareKit.framework/Versions/A/ShareKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 50
-  Symbols:   210
+  Functions: 51
+  Symbols:   212
   CStrings:  126
 
Symbols:
+ GCC_except_table10
+ GCC_except_table6
+ _MailPlugInEncodedQueryValue
+ _objc_autoreleaseReturnValue
- GCC_except_table5
- GCC_except_table9
Functions:
~ -[MailPlugInComposeService composeMailUsingFallbackWithRecipients:subject:body:] : 604 -> 540
+ _MailPlugInEncodedQueryValue
```
