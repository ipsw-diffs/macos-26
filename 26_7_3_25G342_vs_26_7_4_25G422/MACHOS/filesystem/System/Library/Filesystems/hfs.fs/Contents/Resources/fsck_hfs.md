## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/Contents/Resources/fsck_hfs`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-715.160.9.702.5
-  __TEXT.__text: 0x2fea4
+715.160.9.704.7
+  __TEXT.__text: 0x30054
   __TEXT.__auth_stubs: 0x7c0
   __TEXT.__const: 0x111c
-  __TEXT.__cstring: 0x6e7e
+  __TEXT.__cstring: 0x6f96
   __TEXT.__unwind_info: 0x518
   __DATA_CONST.__auth_got: 0x3e0
   __DATA_CONST.__got: 0x50

   - /usr/lib/libSystem.B.dylib
   Functions: 481
   Symbols:   139
-  CStrings:  787
+  CStrings:  793
 
Functions:
~ sub_10000548c : 1084 -> 1168
~ sub_10000f758 -> sub_10000f7ac : 6280 -> 6536
~ sub_1000134e4 -> sub_100013638 : 592 -> 684
CStrings:
+ "has extra space"
+ "hfs_swap_BTNode: header node has %d records, should be 3\n"
+ "hfs_swap_BTNode: map node has %d records, should be 1\n"
+ "hfs_swap_HFSPlusBTInternalNode: catalog file record #%d has extra space\n"
+ "hfs_swap_HFSPlusBTInternalNode: catalog folder record #%d %s\n"
+ "hfs_swap_HFSPlusBTInternalNode: catalog thread record #%d has extra space\n"
+ "too big"
- "hfs_swap_HFSPlusBTInternalNode: catalog folder record #%d too big\n"
```
