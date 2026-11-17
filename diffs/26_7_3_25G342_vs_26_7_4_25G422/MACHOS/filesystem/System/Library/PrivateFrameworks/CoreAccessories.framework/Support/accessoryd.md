## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1147.120.2.0.0
-  __TEXT.__text: 0x190864
+1147.120.2.700.1
+  __TEXT.__text: 0x190a18
   __TEXT.__auth_stubs: 0x16e0
   __TEXT.__objc_stubs: 0x8680
   __TEXT.__objc_methlist: 0x6bc8
   __TEXT.__const: 0x1a89
   __TEXT.__cstring: 0xd0d0
-  __TEXT.__oslogstring: 0x36b7b
+  __TEXT.__oslogstring: 0x36bb0
   __TEXT.__gcc_except_tab: 0x1d34
   __TEXT.__objc_methname: 0xf0fe
   __TEXT.__objc_classname: 0x1046

   - /usr/lib/libsysdiagnose.dylib
   Functions: 6666
   Symbols:   9019
-  CStrings:  8224
+  CStrings:  8226
 
Functions:
~ _loggingProtocol_parseIncomingByteStream : 332 -> 768
CStrings:
+ "Invalid message length."
+ "Message exceeds buffer size."
```
