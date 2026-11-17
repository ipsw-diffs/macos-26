## Bom

> `/System/Library/PrivateFrameworks/Bom.framework/Versions/A/Bom`

```diff

-277.3.0.0.0
-  __TEXT.__text: 0x611f8
+277.5.0.0.0
+  __TEXT.__text: 0x61258
   __TEXT.__auth_stubs: 0x1a20
-  __TEXT.__cstring: 0x13de9
+  __TEXT.__cstring: 0x13e71
   __TEXT.__const: 0x1738
   __TEXT.__oslogstring: 0x10b9
   __TEXT.__unwind_info: 0xb70

   - /usr/lib/libz.1.dylib
   Functions: 1118
   Symbols:   1598
-  CStrings:  2501
+  CStrings:  2503
 
Functions:
~ _BOMStorageCopyFromBlock : 236 -> 284
~ _BOMStorageCopyFromBlockRange : 660 -> 708
CStrings:
+ "BOMStorageCopyFromBlock: bid >= storage->blockTableCount"
+ "BOMStorageCopyRangeFromBlockRange: bad block (bid >= storage->blockTableCount)"
+ "Nov  8 2026"
- "Oct 20 2026"
```
