## fsck_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/fsck_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-324.160.3.702.6
-  __TEXT.__text: 0x11040
+324.160.3.701.4
+  __TEXT.__text: 0x10f18
   __TEXT.__auth_stubs: 0x420
   __TEXT.__init_offsets: 0x8
-  __TEXT.__cstring: 0x36d6
+  __TEXT.__cstring: 0x35c9
   __TEXT.__const: 0x4f5d
-  __TEXT.__gcc_except_tab: 0x5c4
+  __TEXT.__gcc_except_tab: 0x5c0
   __TEXT.__unwind_info: 0x518
   __DATA_CONST.__auth_got: 0x218
   __DATA_CONST.__got: 0x50

   - /usr/lib/libc++.1.dylib
   Functions: 365
   Symbols:   84
-  CStrings:  395
+  CStrings:  390
 
Functions:
~ sub_100001610 : 304 -> 288
~ sub_100001b6c -> sub_100001b5c : 732 -> 676
~ sub_100004544 -> sub_1000044fc : 280 -> 192
~ sub_100005fd0 -> sub_100005f30 : 756 -> 744
~ sub_100009660 -> sub_1000095b4 : 472 -> 416
~ sub_100009964 -> sub_100009880 : 884 -> 820
~ sub_100009cf0 -> sub_100009bcc : 380 -> 376
CStrings:
+ "non-memory resident sparing table is not implemented yet"
- "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
- "Illegal packet length %u in Sparable Partition"
- "L_EA + L_AD exceeds sector size\t ICB addr: %u"
- "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
- "Sparing table size %u cannot hold %u entries"
- "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
```
