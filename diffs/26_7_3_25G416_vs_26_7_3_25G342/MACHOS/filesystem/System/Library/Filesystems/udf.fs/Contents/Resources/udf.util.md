## udf.util

> `/System/Library/Filesystems/udf.fs/Contents/Resources/udf.util`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-324.160.3.702.6
-  __TEXT.__text: 0xa1ac
+324.160.3.701.4
+  __TEXT.__text: 0xa0a8
   __TEXT.__auth_stubs: 0x380
-  __TEXT.__cstring: 0x1056
+  __TEXT.__cstring: 0xfa6
   __TEXT.__gcc_except_tab: 0x328
   __TEXT.__const: 0x564
   __TEXT.__unwind_info: 0x3f0

   - /usr/lib/libc++.1.dylib
   Functions: 255
   Symbols:   70
-  CStrings:  139
+  CStrings:  136
 
Functions:
~ sub_100001254 : 304 -> 288
~ sub_1000017b0 -> sub_1000017a0 : 732 -> 676
~ sub_100003ef8 -> sub_100003eb0 : 240 -> 172
~ sub_1000055e8 -> sub_10000555c : 756 -> 744
~ sub_1000089d8 -> sub_100008940 : 424 -> 384
~ sub_100008cac -> sub_100008bec : 884 -> 820
~ sub_100009038 -> sub_100008f38 : 352 -> 348
CStrings:
+ "non-memory resident sparing table is not implemented yet"
- "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
- "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
- "Sparing table size %u cannot hold %u entries"
- "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
```
