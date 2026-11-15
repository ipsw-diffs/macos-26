## com.apple.filesystems.hfs.kext

> `com.apple.filesystems.hfs.kext`

```diff

-715.160.9.704.5
+715.160.9.702.5
   __TEXT.__const: 0x1ac0
-  __TEXT.__cstring: 0xae30
-  __TEXT_EXEC.__text: 0x4eccc
+  __TEXT.__cstring: 0xab3a
+  __TEXT_EXEC.__text: 0x4e8ec
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x4d0
   __DATA.__common: 0x10

   __DATA_CONST.__kalloc_var: 0x5f0
   Functions: 511
   Symbols:   1573
-  CStrings:  881
+  CStrings:  868
 
Symbols:
+ _cat_check_link_ancestry.kalloc_type_view_1883
+ _cat_check_link_ancestry.kalloc_type_view_1910
+ _cat_createlink.kalloc_type_view_2215
+ _cat_createlink.kalloc_type_view_2290
+ _cat_getentriesattr.kalloc_type_view_2636
+ _cat_getentriesattr.kalloc_type_view_2757
+ _cat_lookup_dirlink.kalloc_type_view_4099
+ _cat_lookup_dirlink.kalloc_type_view_4102
+ _cat_lookup_dirlink.kalloc_type_view_4140
+ _cat_lookup_dirlink.kalloc_type_view_4142
+ _cat_lookup_lastlink.kalloc_type_view_2094
+ _cat_lookup_lastlink.kalloc_type_view_2173
+ _cat_lookup_siblinglinks.kalloc_type_view_2039
+ _cat_lookup_siblinglinks.kalloc_type_view_2070
+ _cat_lookuplink.kalloc_type_view_1995
+ _cat_lookuplink.kalloc_type_view_2019
+ _cat_rename.kalloc_type_view_1407
+ _cat_resolvelink.kalloc_type_view_3574
+ _cat_resolvelink.kalloc_type_view_3596
+ _cat_update_siblinglinks.kalloc_type_view_1966
+ _cat_update_siblinglinks.kalloc_type_view_1976
+ _getkey.kalloc_type_view_3639
+ _getkey.kalloc_type_view_3642
+ _getkey.kalloc_type_view_3676
+ _getkey.kalloc_type_view_3677
+ _hfs_mountfs.kalloc_type_view_1272
+ _hfs_mountfs.kalloc_type_view_1883
+ _hfs_unmount.kalloc_type_view_2100
- _cat_check_link_ancestry.kalloc_type_view_1885
- _cat_check_link_ancestry.kalloc_type_view_1912
- _cat_createlink.kalloc_type_view_2217
- _cat_createlink.kalloc_type_view_2292
- _cat_getentriesattr.kalloc_type_view_2638
- _cat_getentriesattr.kalloc_type_view_2759
- _cat_lookup_dirlink.kalloc_type_view_4111
- _cat_lookup_dirlink.kalloc_type_view_4114
- _cat_lookup_dirlink.kalloc_type_view_4152
- _cat_lookup_dirlink.kalloc_type_view_4154
- _cat_lookup_lastlink.kalloc_type_view_2096
- _cat_lookup_lastlink.kalloc_type_view_2175
- _cat_lookup_siblinglinks.kalloc_type_view_2041
- _cat_lookup_siblinglinks.kalloc_type_view_2072
- _cat_lookuplink.kalloc_type_view_1997
- _cat_lookuplink.kalloc_type_view_2021
- _cat_rename.kalloc_type_view_1413
- _cat_resolvelink.kalloc_type_view_3576
- _cat_resolvelink.kalloc_type_view_3598
- _cat_update_siblinglinks.kalloc_type_view_1968
- _cat_update_siblinglinks.kalloc_type_view_1978
- _getkey.kalloc_type_view_3641
- _getkey.kalloc_type_view_3644
- _getkey.kalloc_type_view_3678
- _getkey.kalloc_type_view_3679
- _hfs_mountfs.kalloc_type_view_1283
- _hfs_mountfs.kalloc_type_view_1894
- _hfs_unmount.kalloc_type_view_2111
Functions:
~ _InsertKeyRecord : 552 -> 484
~ _BTSearchRecord : 1020 -> 1016
~ _BTIterateRecord : 2024 -> 1828
~ _BTIterateRecords : 2180 -> 1952
~ _BTReloadData : 308 -> 260
~ _hfs_swap_BTNode : 5712 -> 5328
~ _builddesc : 520 -> 516
~ _cat_rename : 1776 -> 1744
~ _hfs_mount : 3660 -> 3644
~ _VerifyHeader : 228 -> 216
CStrings:
+ "\"hfs_swap_HFSPlusBTInternalNode: catalog file record #%d too big\\n\" @%s:%d"
+ "hfs_swap_HFSPlusBTInternalNode: catalog file record #%d too big\n"
- "\"hfs_swap_BTNode: header node has %d records, should be 3\\n\" @%s:%d"
- "\"hfs_swap_BTNode: map node has %d records, should be 1\\n\" @%s:%d"
- "\"hfs_swap_HFSPlusBTInternalNode: catalog file record #%d %s\\n\" @%s:%d"
- "\"hfs_swap_HFSPlusBTInternalNode: catalog folder record #%d has extra space after it\\n\" @%s:%d"
- "\"hfs_swap_HFSPlusBTInternalNode: catalog thread record #%d has extra space after it\\n\" @%s:%d"
- "BTIterateRecord"
- "BTIterateRecords"
- "has extra space"
- "hfs: %s() found mismatched sibling node on volume %s: found kind=%d, height=%u; expected kind=%d, height=%u\n"
- "hfs_swap_BTNode: header node has %d records, should be 3\n"
- "hfs_swap_BTNode: map node has %d records, should be 1\n"
- "hfs_swap_HFSPlusBTInternalNode: catalog file record #%d %s\n"
- "hfs_swap_HFSPlusBTInternalNode: catalog folder record #%d has extra space after it\n"
- "hfs_swap_HFSPlusBTInternalNode: catalog thread record #%d has extra space after it\n"
- "too big"
```
