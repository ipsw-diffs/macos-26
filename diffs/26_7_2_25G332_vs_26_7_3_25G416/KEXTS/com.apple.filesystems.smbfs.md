## com.apple.filesystems.smbfs

> `com.apple.filesystems.smbfs`

```diff

-538.161.2.701.4
+538.161.2.702.2
   __TEXT.__const: 0xc25
-  __TEXT.__cstring: 0x48f3
+  __TEXT.__cstring: 0x490e
   __TEXT.__os_log: 0x16521
-  __TEXT_EXEC.__text: 0x7d2f0
+  __TEXT_EXEC.__text: 0x7d3cc
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xdf8
   __DATA.__bss: 0x106c

   __DATA_CONST.__kalloc_var: 0x460
   Functions: 768
   Symbols:   2094
-  CStrings:  2530
+  CStrings:  2534
 
Symbols:
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6314
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6352
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6363
+ _smb2fs_reconnect.kalloc_type_view_3864
+ _smb2fs_reconnect.kalloc_type_view_4408
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3626
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3782
+ _smbfs_CloseChildren.kalloc_type_view_3417
+ _smbfs_clear_lockEntries.kalloc_type_view_6725
+ _smbfs_clear_lockEntries.kalloc_type_view_6755
+ _smbfs_free_locks_on_close.kalloc_type_view_6913
+ _smbfs_get_lockEntry.kalloc_type_view_7120
+ _smbfs_get_lockEntry.kalloc_type_view_7209
+ _smbfs_lease_hash_add.kalloc_type_view_6166
+ _smbfs_lease_hash_remove.kalloc_type_view_6266
+ _smbfs_nget.kalloc_type_view_1025
+ _smbfs_nget.kalloc_type_view_1080
+ _smbfs_nget.kalloc_type_view_1100
+ _smbfs_nget.kalloc_type_view_1107
+ _smbfs_nget.kalloc_type_view_1412
+ _smbfs_nget.kalloc_type_view_996
+ _smbfs_trigger_get_mount_args.kalloc_type_view_207
+ _smbfs_trigger_get_mount_args.kalloc_type_view_238
+ _smbfs_trigger_get_mount_args.kalloc_type_view_262
+ _smbfs_trigger_rel_mount_args.kalloc_type_view_308
+ _smbfs_vgetstrm.kalloc_type_view_1499
+ _smbfs_vgetstrm.kalloc_type_view_1506
+ _smbfs_vgetstrm.kalloc_type_view_1717
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6289
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6327
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6338
- _smb2fs_reconnect.kalloc_type_view_3839
- _smb2fs_reconnect.kalloc_type_view_4383
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3601
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3757
- _smbfs_CloseChildren.kalloc_type_view_3392
- _smbfs_clear_lockEntries.kalloc_type_view_6700
- _smbfs_clear_lockEntries.kalloc_type_view_6730
- _smbfs_free_locks_on_close.kalloc_type_view_6888
- _smbfs_get_lockEntry.kalloc_type_view_7095
- _smbfs_get_lockEntry.kalloc_type_view_7184
- _smbfs_lease_hash_add.kalloc_type_view_6141
- _smbfs_lease_hash_remove.kalloc_type_view_6241
- _smbfs_nget.kalloc_type_view_1000
- _smbfs_nget.kalloc_type_view_1055
- _smbfs_nget.kalloc_type_view_1075
- _smbfs_nget.kalloc_type_view_1082
- _smbfs_nget.kalloc_type_view_1387
- _smbfs_nget.kalloc_type_view_971
- _smbfs_trigger_get_mount_args.kalloc_type_view_206
- _smbfs_trigger_get_mount_args.kalloc_type_view_237
- _smbfs_trigger_get_mount_args.kalloc_type_view_261
- _smbfs_trigger_rel_mount_args.kalloc_type_view_283
- _smbfs_vgetstrm.kalloc_type_view_1474
- _smbfs_vgetstrm.kalloc_type_view_1481
- _smbfs_vgetstrm.kalloc_type_view_1692
Functions:
~ _smbfs_trigger_get_mount_args : 816 -> 1024
~ _smbfs_trigger_rel_mount_args : 92 -> 108
~ _nb_put_name : 284 -> 280
CStrings:
+ ","
+ "noexec"
+ "quarantine"
+ "rdonly"
```
