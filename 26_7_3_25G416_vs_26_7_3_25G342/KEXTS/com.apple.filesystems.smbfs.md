## com.apple.filesystems.smbfs

> `com.apple.filesystems.smbfs`

```diff

-538.161.2.702.2
+538.161.2.701.5
   __TEXT.__const: 0xc25
-  __TEXT.__cstring: 0x490e
-  __TEXT.__os_log: 0x16521
-  __TEXT_EXEC.__text: 0x7d3cc
+  __TEXT.__cstring: 0x48f3
+  __TEXT.__os_log: 0x164c1
+  __TEXT_EXEC.__text: 0x7d0e4
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xdf8
   __DATA.__bss: 0x106c

   __DATA_CONST.__const: 0x78
   __DATA_CONST.__kalloc_type: 0x4dc0
   __DATA_CONST.__kalloc_var: 0x460
-  Functions: 768
-  Symbols:   2094
-  CStrings:  2534
+  Functions: 767
+  Symbols:   2093
+  CStrings:  2529
 
Symbols:
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6280
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6318
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6329
+ _smb1fs_smb_findclose.kalloc_type_view_5682
+ _smb2_smb_read_uio.kalloc_type_view_9021
+ _smb2_smb_read_uio.kalloc_type_view_9038
+ _smb2_smb_read_write_async.kalloc_type_view_9190
+ _smb2_smb_read_write_async.kalloc_type_view_9256
+ _smb2_smb_read_write_async.kalloc_type_view_9584
+ _smb2_smb_read_write_async.kalloc_type_view_9653
+ _smb2_smb_write_uio.kalloc_type_view_10813
+ _smb2_smb_write_uio.kalloc_type_view_10866
+ _smb2fs_reconnect.kalloc_type_view_3830
+ _smb2fs_reconnect.kalloc_type_view_4374
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3592
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3748
+ _smbfs_CloseChildren.kalloc_type_view_3383
+ _smbfs_build_path.kalloc_type_view_113
+ _smbfs_build_path.kalloc_type_view_115
+ _smbfs_build_path.kalloc_type_view_183
+ _smbfs_build_path.kalloc_type_view_186
+ _smbfs_clear_lockEntries.kalloc_type_view_6691
+ _smbfs_clear_lockEntries.kalloc_type_view_6721
+ _smbfs_free_locks_on_close.kalloc_type_view_6879
+ _smbfs_get_lockEntry.kalloc_type_view_7086
+ _smbfs_get_lockEntry.kalloc_type_view_7175
+ _smbfs_lease_hash_add.kalloc_type_view_6132
+ _smbfs_lease_hash_remove.kalloc_type_view_6232
+ _smbfs_nget.kalloc_type_view_1046
+ _smbfs_nget.kalloc_type_view_1066
+ _smbfs_nget.kalloc_type_view_1073
+ _smbfs_nget.kalloc_type_view_1378
+ _smbfs_nget.kalloc_type_view_962
+ _smbfs_nget.kalloc_type_view_991
+ _smbfs_smb_findopen.kalloc_type_view_5945
+ _smbfs_smb_reopen_file.kalloc_type_view_5032
+ _smbfs_smb_reopen_file.kalloc_type_view_5108
+ _smbfs_trigger_get_mount_args.kalloc_type_view_205
+ _smbfs_trigger_get_mount_args.kalloc_type_view_236
+ _smbfs_trigger_get_mount_args.kalloc_type_view_260
+ _smbfs_trigger_rel_mount_args.kalloc_type_view_282
+ _smbfs_vgetstrm.kalloc_type_view_1465
+ _smbfs_vgetstrm.kalloc_type_view_1472
+ _smbfs_vgetstrm.kalloc_type_view_1683
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6314
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6352
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6363
- _smb1fs_smb_findclose.kalloc_type_view_5708
- _smb2_smb_read_uio.kalloc_type_view_9027
- _smb2_smb_read_uio.kalloc_type_view_9044
- _smb2_smb_read_write_async.kalloc_type_view_9196
- _smb2_smb_read_write_async.kalloc_type_view_9262
- _smb2_smb_read_write_async.kalloc_type_view_9590
- _smb2_smb_read_write_async.kalloc_type_view_9659
- _smb2_smb_write_uio.kalloc_type_view_10819
- _smb2_smb_write_uio.kalloc_type_view_10872
- _smb2fs_reconnect.kalloc_type_view_3864
- _smb2fs_reconnect.kalloc_type_view_4408
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3626
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3782
- _smb_symlink_target_is_unsafe
- _smbfs_CloseChildren.kalloc_type_view_3417
- _smbfs_build_path.kalloc_type_view_114
- _smbfs_build_path.kalloc_type_view_116
- _smbfs_build_path.kalloc_type_view_184
- _smbfs_build_path.kalloc_type_view_187
- _smbfs_clear_lockEntries.kalloc_type_view_6725
- _smbfs_clear_lockEntries.kalloc_type_view_6755
- _smbfs_free_locks_on_close.kalloc_type_view_6913
- _smbfs_get_lockEntry.kalloc_type_view_7120
- _smbfs_get_lockEntry.kalloc_type_view_7209
- _smbfs_lease_hash_add.kalloc_type_view_6166
- _smbfs_lease_hash_remove.kalloc_type_view_6266
- _smbfs_nget.kalloc_type_view_1025
- _smbfs_nget.kalloc_type_view_1080
- _smbfs_nget.kalloc_type_view_1100
- _smbfs_nget.kalloc_type_view_1107
- _smbfs_nget.kalloc_type_view_1412
- _smbfs_nget.kalloc_type_view_996
- _smbfs_smb_findopen.kalloc_type_view_5971
- _smbfs_smb_reopen_file.kalloc_type_view_5058
- _smbfs_smb_reopen_file.kalloc_type_view_5134
- _smbfs_trigger_get_mount_args.kalloc_type_view_207
- _smbfs_trigger_get_mount_args.kalloc_type_view_238
- _smbfs_trigger_get_mount_args.kalloc_type_view_262
- _smbfs_trigger_rel_mount_args.kalloc_type_view_308
- _smbfs_vgetstrm.kalloc_type_view_1499
- _smbfs_vgetstrm.kalloc_type_view_1506
- _smbfs_vgetstrm.kalloc_type_view_1717
Functions:
~ _smb_check_for_windows_symlink : 888 -> 868
~ _smbfs_trigger_get_mount_args : 1024 -> 816
~ _smbfs_trigger_rel_mount_args : 108 -> 92
~ _smbfs_smb_get_reparse_tag : 596 -> 572
~ _smbfs_smb_windows_read_symlink : 824 -> 720
~ _smbfs_smb_unix_read_symlink : 884 -> 780
~ _nb_put_name : 280 -> 284
- _smb_symlink_target_is_unsafe
~ _smb2_smb_parse_get_reparse_point : 572 -> 548
CStrings:
- "%s: %s has an unsafe symlink target, rejecting\n"
- ","
- "noexec"
- "quarantine"
- "rdonly"
```
