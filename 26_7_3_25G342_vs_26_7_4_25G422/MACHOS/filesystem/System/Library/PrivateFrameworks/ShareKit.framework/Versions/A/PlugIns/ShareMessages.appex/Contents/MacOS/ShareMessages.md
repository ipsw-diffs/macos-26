## ShareMessages

> `/System/Library/PrivateFrameworks/ShareKit.framework/Versions/A/PlugIns/ShareMessages.appex/Contents/MacOS/ShareMessages`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

-2094.70.81.1.1
-  __TEXT.__text: 0x273c
+2094.70.81.1.4
+  __TEXT.__text: 0x27a0
   __TEXT.__auth_stubs: 0x1b0
   __TEXT.__objc_stubs: 0x640
   __TEXT.__objc_methlist: 0x5c

   __TEXT.__objc_classname: 0x1d
   __TEXT.__objc_methname: 0x61a
   __TEXT.__objc_methtype: 0x30
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x110
   __DATA_CONST.__auth_got: 0xe8
   __DATA_CONST.__got: 0xf8
   __DATA_CONST.__const: 0x210

   - /System/Library/PrivateFrameworks/Sharing.framework/Versions/A/Sharing
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 44
-  Symbols:   167
+  Functions: 45
+  Symbols:   168
   CStrings:  106
 
Symbols:
+ GCC_except_table21
+ GCC_except_table9
+ _MessagesPlugInEncodedBody
- GCC_except_table18
- GCC_except_table8
Functions:
~ -[MessagesPlugInComposeService _composeMessageUsingFallbackWithRecipients:subject:body:] : 596 -> 564
+ _MessagesPlugInEncodedBody
```
