## newfs_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/newfs_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-324.160.3.702.6
-  __TEXT.__text: 0x1229c
+324.160.3.701.4
+  __TEXT.__text: 0x12198
   __TEXT.__auth_stubs: 0x5c0
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x658
   __TEXT.__gcc_except_tab: 0x380
-  __TEXT.__cstring: 0x39a6
+  __TEXT.__cstring: 0x38f6
   __TEXT.__unwind_info: 0x540
   __DATA_CONST.__auth_got: 0x2e8
   __DATA_CONST.__got: 0x78

   - /usr/lib/libutil.dylib
   Functions: 344
   Symbols:   115
-  CStrings:  332
+  CStrings:  329
 
Functions:
~ sub_100000c30 : 304 -> 288
~ sub_100001190 -> sub_100001180 : 732 -> 676
~ sub_1000021ec -> sub_1000021a4 : 424 -> 384
~ sub_1000024c0 -> sub_100002450 : 884 -> 820
~ sub_10000284c -> sub_10000279c : 352 -> 348
~ sub_10000c3f4 -> sub_10000c340 : 240 -> 172
~ sub_10000eb64 -> sub_10000ea6c : 756 -> 744
CStrings:
+ "non-memory resident sparing table is not implemented yet"
- "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
- "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
- "Sparing table size %u cannot hold %u entries"
- "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
```
