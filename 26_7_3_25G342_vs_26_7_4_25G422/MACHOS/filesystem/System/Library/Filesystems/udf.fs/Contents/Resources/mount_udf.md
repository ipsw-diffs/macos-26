## mount_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/mount_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-324.160.3.701.4
-  __TEXT.__text: 0x9e24
+324.160.3.702.8
+  __TEXT.__text: 0x9f84
   __TEXT.__auth_stubs: 0x3d0
-  __TEXT.__cstring: 0x1092
-  __TEXT.__gcc_except_tab: 0x304
+  __TEXT.__cstring: 0x11f3
+  __TEXT.__gcc_except_tab: 0x2fc
   __TEXT.__const: 0x564
   __TEXT.__unwind_info: 0x3d0
   __DATA_CONST.__auth_got: 0x1f0

   - /usr/lib/libutil.dylib
   Functions: 247
   Symbols:   78
-  CStrings:  149
+  CStrings:  156
 
Functions:
~ sub_10000124c : 288 -> 304
~ sub_100001798 -> sub_1000017a8 : 676 -> 732
~ sub_100003ea8 -> sub_100003ef0 : 172 -> 240
~ sub_100005554 -> sub_1000055e0 : 744 -> 756
~ sub_100008938 -> sub_1000089d0 : 384 -> 424
~ sub_100008be4 -> sub_100008ca4 : 820 -> 884
~ sub_100008f30 -> sub_100009030 : 348 -> 352
~ sub_100009314 -> sub_100009418 : 836 -> 928
CStrings:
+ "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
+ "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
+ "Sparing table size %u cannot hold %u entries"
+ "The VAT has too many entries"
+ "The VAT information length exceeds the VAT stream length"
+ "The VAT is too small to hold its tail"
+ "The lengthOfHeader in VAT ICB exceeds the VAT length"
+ "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
- "non-memory resident sparing table is not implemented yet"
```
