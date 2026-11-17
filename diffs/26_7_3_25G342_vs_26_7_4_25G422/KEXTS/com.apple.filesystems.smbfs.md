## com.apple.filesystems.smbfs

> `com.apple.filesystems.smbfs`

```diff

-538.161.2.701.5
+538.161.2.702.5
   __TEXT.__const: 0xc25
-  __TEXT.__cstring: 0x48f3
+  __TEXT.__cstring: 0x490e
   __TEXT.__os_log: 0x164c1
-  __TEXT_EXEC.__text: 0x7d0e4
+  __TEXT_EXEC.__text: 0x7d1c0
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xdf8
   __DATA.__bss: 0x106c

   __DATA_CONST.__kalloc_var: 0x460
   Functions: 767
   Symbols:   2093
-  CStrings:  2529
+  CStrings:  2533
 
Symbols:
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6305
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6343
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6354
+ _smb2_smb_read_uio.kalloc_type_view_9032
+ _smb2_smb_read_uio.kalloc_type_view_9049
+ _smb2_smb_read_write_async.kalloc_type_view_9201
+ _smb2_smb_read_write_async.kalloc_type_view_9267
+ _smb2_smb_read_write_async.kalloc_type_view_9595
+ _smb2_smb_read_write_async.kalloc_type_view_9664
+ _smb2_smb_write_uio.kalloc_type_view_10824
+ _smb2_smb_write_uio.kalloc_type_view_10877
+ _smb2fs_reconnect.kalloc_type_view_3855
+ _smb2fs_reconnect.kalloc_type_view_4399
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3617
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3773
+ _smbfs_CloseChildren.kalloc_type_view_3408
+ _smbfs_clear_lockEntries.kalloc_type_view_6716
+ _smbfs_clear_lockEntries.kalloc_type_view_6746
+ _smbfs_free_locks_on_close.kalloc_type_view_6904
+ _smbfs_get_lockEntry.kalloc_type_view_7111
+ _smbfs_get_lockEntry.kalloc_type_view_7200
+ _smbfs_lease_hash_add.kalloc_type_view_6157
+ _smbfs_lease_hash_remove.kalloc_type_view_6257
+ _smbfs_nget.kalloc_type_view_1016
+ _smbfs_nget.kalloc_type_view_1071
+ _smbfs_nget.kalloc_type_view_1091
+ _smbfs_nget.kalloc_type_view_1098
+ _smbfs_nget.kalloc_type_view_1403
+ _smbfs_nget.kalloc_type_view_987
+ _smbfs_trigger_get_mount_args.kalloc_type_view_206
+ _smbfs_trigger_get_mount_args.kalloc_type_view_237
+ _smbfs_trigger_get_mount_args.kalloc_type_view_261
+ _smbfs_trigger_rel_mount_args.kalloc_type_view_307
+ _smbfs_vgetstrm.kalloc_type_view_1490
+ _smbfs_vgetstrm.kalloc_type_view_1497
+ _smbfs_vgetstrm.kalloc_type_view_1708
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6280
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6318
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6329
- _smb2_smb_read_uio.kalloc_type_view_9021
- _smb2_smb_read_uio.kalloc_type_view_9038
- _smb2_smb_read_write_async.kalloc_type_view_9190
- _smb2_smb_read_write_async.kalloc_type_view_9256
- _smb2_smb_read_write_async.kalloc_type_view_9584
- _smb2_smb_read_write_async.kalloc_type_view_9653
- _smb2_smb_write_uio.kalloc_type_view_10813
- _smb2_smb_write_uio.kalloc_type_view_10866
- _smb2fs_reconnect.kalloc_type_view_3830
- _smb2fs_reconnect.kalloc_type_view_4374
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3592
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3748
- _smbfs_CloseChildren.kalloc_type_view_3383
- _smbfs_clear_lockEntries.kalloc_type_view_6691
- _smbfs_clear_lockEntries.kalloc_type_view_6721
- _smbfs_free_locks_on_close.kalloc_type_view_6879
- _smbfs_get_lockEntry.kalloc_type_view_7086
- _smbfs_get_lockEntry.kalloc_type_view_7175
- _smbfs_lease_hash_add.kalloc_type_view_6132
- _smbfs_lease_hash_remove.kalloc_type_view_6232
- _smbfs_nget.kalloc_type_view_1046
- _smbfs_nget.kalloc_type_view_1066
- _smbfs_nget.kalloc_type_view_1073
- _smbfs_nget.kalloc_type_view_1378
- _smbfs_nget.kalloc_type_view_962
- _smbfs_nget.kalloc_type_view_991
- _smbfs_trigger_get_mount_args.kalloc_type_view_205
- _smbfs_trigger_get_mount_args.kalloc_type_view_236
- _smbfs_trigger_get_mount_args.kalloc_type_view_260
- _smbfs_trigger_rel_mount_args.kalloc_type_view_282
- _smbfs_vgetstrm.kalloc_type_view_1465
- _smbfs_vgetstrm.kalloc_type_view_1472
- _smbfs_vgetstrm.kalloc_type_view_1683
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
