## MailCore

> `/System/Library/PrivateFrameworks/MailCore.framework/Versions/A/MailCore`

```diff

-3864.700.51.1.4
-  __TEXT.__text: 0x8b764
+3864.700.51.1.5
+  __TEXT.__text: 0x8b750
   __TEXT.__auth_stubs: 0x1230
   __TEXT.__objc_methlist: 0x812c
   __TEXT.__const: 0x4b0
-  __TEXT.__cstring: 0x7f41
+  __TEXT.__cstring: 0x7e60
   __TEXT.__gcc_except_tab: 0x1650
   __TEXT.__oslogstring: 0x1de7
   __TEXT.__unwind_info: 0x2350
Functions:
~ -[NSData(HFSDataConversion) wrapperForAppleFileDataWithFileEncodingHint:] : 2912 -> 2888
~ -[MCMimePart _decodeMultipartAppledouble] : 1164 -> 1168
CStrings:
+ "!appleFileEntryIsInBounds(&thisEntry, length)"
+ "thisEntry.entryLength < sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt16)"
+ "thisEntry.entryLength < sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32)"
+ "thisEntry.entryLength > MAXPATHLEN"
- "thisEntry.entryLength > length || thisEntry.entryOffset > length || thisEntry.entryOffset > length - thisEntry.entryLength"
- "thisEntry.entryLength > length || thisEntry.entryOffset > length || thisEntry.entryOffset > length - thisEntry.entryLength || thisEntry.entryLength > MAXPATHLEN"
- "thisEntry.entryOffset > length - (sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt16))"
- "thisEntry.entryOffset > length - (sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32))"
```
