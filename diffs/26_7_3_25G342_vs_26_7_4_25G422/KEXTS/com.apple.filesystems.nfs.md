## com.apple.filesystems.nfs

> `com.apple.filesystems.nfs`

```diff

-343.160.4.702.5
-  __TEXT.__cstring: 0x9c42
+343.160.4.704.4
+  __TEXT.__cstring: 0x9cb5
   __TEXT.__const: 0x39c
-  __TEXT_EXEC.__text: 0x9d2f0
+  __TEXT_EXEC.__text: 0x9d350
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xf00
   __DATA.__common: 0xee4

   __DATA_CONST.__kalloc_var: 0x320
   Functions: 1002
   Symbols:   1617
-  CStrings:  1156
+  CStrings:  1158
 
Symbols:
+ _nfs3_vnop_mkdir.kalloc_type_view_5645
+ _nfs3_vnop_mkdir.kalloc_type_view_5759
+ _nfs3_vnop_rmdir.kalloc_type_view_5816
+ _nfs3_vnop_rmdir.kalloc_type_view_5892
+ _nfs3_vnop_symlink.kalloc_type_view_5456
+ _nfs3_vnop_symlink.kalloc_type_view_5576
+ _nfs_sillyrename.kalloc_type_view_7083
+ _nfs_sillyrename.kalloc_type_view_7142
+ _nfs_vnop_remove.kalloc_type_view_4918
- _nfs3_vnop_mkdir.kalloc_type_view_5630
- _nfs3_vnop_mkdir.kalloc_type_view_5744
- _nfs3_vnop_rmdir.kalloc_type_view_5801
- _nfs3_vnop_rmdir.kalloc_type_view_5877
- _nfs3_vnop_symlink.kalloc_type_view_5441
- _nfs3_vnop_symlink.kalloc_type_view_5561
- _nfs_sillyrename.kalloc_type_view_7068
- _nfs_sillyrename.kalloc_type_view_7127
- _nfs_vnop_remove.kalloc_type_view_4903
Functions:
~ _nfs_request_finish : 2944 -> 2948
~ _nfs_buf_read_finish : 356 -> 472
~ _nfs_vnop_pageout : 5076 -> 4916
~ _nfs_loadattrcache : 2048 -> 2184
CStrings:
+ "%s: %d: clamping nb_validend %lld to EOF: boff %lld, nb_endio %lld, nb_bufsize %u, n_size %llu"
+ "nfs_buf_read_finish"
```
