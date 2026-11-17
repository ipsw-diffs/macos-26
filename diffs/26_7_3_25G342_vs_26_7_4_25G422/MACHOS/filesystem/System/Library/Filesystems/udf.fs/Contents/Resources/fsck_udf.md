## fsck_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/fsck_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-324.160.3.701.4
-  __TEXT.__text: 0x10f18
+324.160.3.702.8
+  __TEXT.__text: 0x1109c
   __TEXT.__auth_stubs: 0x420
   __TEXT.__init_offsets: 0x8
-  __TEXT.__cstring: 0x35c9
+  __TEXT.__cstring: 0x3787
   __TEXT.__const: 0x4f5d
-  __TEXT.__gcc_except_tab: 0x5c0
+  __TEXT.__gcc_except_tab: 0x5bc
   __TEXT.__unwind_info: 0x518
   __DATA_CONST.__auth_got: 0x218
   __DATA_CONST.__got: 0x50

   - /usr/lib/libc++.1.dylib
   Functions: 365
   Symbols:   84
-  CStrings:  390
+  CStrings:  399
 
Functions:
~ sub_100001610 : 288 -> 304
~ sub_100001b5c -> sub_100001b6c : 676 -> 732
~ sub_1000044fc -> sub_100004544 : 192 -> 280
~ sub_100005f30 -> sub_100005fd0 : 744 -> 756
~ sub_1000095b4 -> sub_100009660 : 416 -> 472
~ sub_100009880 -> sub_100009964 : 820 -> 884
~ sub_100009bcc -> sub_100009cf0 : 376 -> 380
~ sub_10000a030 -> sub_10000a158 : 836 -> 928
CStrings:
+ "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
+ "Illegal packet length %u in Sparable Partition"
+ "L_EA + L_AD exceeds sector size\t ICB addr: %u"
+ "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
+ "Sparing table size %u cannot hold %u entries"
+ "The VAT has too many entries"
+ "The VAT information length exceeds the VAT stream length"
+ "The VAT is too small to hold its tail"
+ "The lengthOfHeader in VAT ICB exceeds the VAT length"
+ "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
- "non-memory resident sparing table is not implemented yet"
```
