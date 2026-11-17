## DiskManagement

> `/System/Library/PrivateFrameworks/DiskManagement.framework/Versions/A/DiskManagement`

```diff

 1037.160.3.701.5
-  __TEXT.__text: 0x969a4
-  __TEXT.__auth_stubs: 0x19b0
+  __TEXT.__text: 0x946ec
+  __TEXT.__auth_stubs: 0x1940
   __TEXT.__objc_methlist: 0x24cc
-  __TEXT.__cstring: 0x35527
+  __TEXT.__cstring: 0x34be9
   __TEXT.__const: 0x14bc
   __TEXT.__gcc_except_tab: 0xf1c
   __TEXT.__oslogstring: 0x33
-  __TEXT.__unwind_info: 0x1778
+  __TEXT.__unwind_info: 0x1730
   __TEXT.__objc_classname: 0x1fb
   __TEXT.__objc_methname: 0x8493
   __TEXT.__objc_methtype: 0x241f
   __TEXT.__objc_stubs: 0x3b40
-  __DATA_CONST.__got: 0x408
+  __DATA_CONST.__got: 0x400
   __DATA_CONST.__const: 0x2388
   __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_protolist: 0x30

   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x78
   __DATA_CONST.__objc_arraydata: 0xeb8
-  __AUTH_CONST.__auth_got: 0xce8
+  __AUTH_CONST.__auth_got: 0xcb0
   __AUTH_CONST.__const: 0x4c0
-  __AUTH_CONST.__cfstring: 0x20c40
+  __AUTH_CONST.__cfstring: 0x208e0
   __AUTH_CONST.__objc_const: 0x1fe0
   __AUTH_CONST.__objc_arrayobj: 0x1f80
   __AUTH_CONST.__objc_intobj: 0x30

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcsfde.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1906
-  Symbols:   3700
-  CStrings:  6973
+  Functions: 1882
+  Symbols:   3667
+  CStrings:  6936
 
Symbols:
- _AppleLVMCreateVolume
- _AppleLVMDestroyVolume
- _AppleLVMGetVolumeDescription
- _AppleLVMGetVolumeExtents
- _AppleLVMGetVolumeProperties
- _AppleLVMGetVolumesForGroup
- _AppleLVMMergeGroups
- _AppleLVMMigrateVolume
- _AppleLVMModifyVolume
- _AppleLVMRemoveMember
- _AppleLVMResizeVolume
- _AppleLVMSnapShotVolume
- _AppleLVMUpdateVolume
- _CFDataCreateMutableCopy
- _CFDataCreateWithBytesNoCopy
- _CFDataGetBytes
- _CFDataReplaceBytes
- _CFDataSetLength
- ___assert_rtn
- _allocateExtent
- _buildLVMetaDataBlock
- _calculateBitMapSize
- _freeSetInfo
- _gLogicalVolumeIter
- _getSetInfo
- _getVolumeExtents
- _growLastExtent
- _initLogicalVolumeProps
- _kCFAllocatorMalloc
- _logicalVolumeChanged
- _logicalVolumeDetected
- _reallocf
- _truncateExtents
CStrings:
+ " <array> \n<dict> \n<key>AppleRAID-LevelName</key><string>Stripe</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>None</string> \n<key>AppleRAID-CanBeConvertedTo</key><false/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Mirror</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n<string>AppleRAID-Spares</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><true/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><true/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>Any</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Concat</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><true/> \n<key>AppleRAID-RemovalAllowed</key><string>Last</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n </array> \n"
+ " <dict> \n<key>AppleRAID-HeaderVersion</key><integer size=\"32\">0x00020000</integer> \n<key>AppleRAID-LevelName</key><string>internal error</string> \n<key>AppleRAID-SetName</key><string>internal error</string> \n<key>AppleRAID-SetUUID</key><string>internal error</string> \n<key>AppleRAID-SequenceNumber</key><integer size=\"32\">1</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x00008000</integer> \n<key>AppleRAID-ChunkCount</key><integer size=\"64\">0</integer> \n<key>AppleRAID-Members</key><array/> \n<key>AppleRAID-Spares</key><array/> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>internal error</string> \n<key>AppleRAID-ContentHint</key><string/> \n </dict> \n"
+ "21:39:28"
+ "Nov  8 2026"
- " <array> \n<dict> \n<key>AppleLVM-Type</key><string>concat</string> \n</dict> \n<dict> \n<key>AppleLVM-Type</key><string>snap ro</string> \n</dict> \n<dict> \n<key>AppleLVM-Type</key><string>snap rw</string> \n</dict> \n </array> \n"
- " <array> \n<dict> \n<key>AppleRAID-LevelName</key><string>Stripe</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-QuickRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>None</string> \n<key>AppleRAID-CanBeConvertedTo</key><false/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Mirror</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n<string>AppleRAID-Spares</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><true/> \n<key>AppleRAID-QuickRebuild</key><true/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><true/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>Any</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Concat</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-QuickRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><true/> \n<key>AppleRAID-RemovalAllowed</key><string>Last</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>LVG</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><true/> \n<key>AppleRAID-RemovalAllowed</key><string>None</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n </array> \n"
- " <dict> \n<key>AppleLVM-Version</key><integer size=\"32\">0x00030000</integer> \n<key>AppleLVM-GroupUUID</key><string>internal error</string> \n<key>AppleLVM-VolumeUUID</key><string>internal error</string> \n<key>AppleLVM-Sequence</key><integer size=\"32\">0</integer> \n<key>AppleLVM-VolumeSize</key><integer size=\"64\">0x00000000</integer> \n<key>AppleLVM-ExtentCount</key><integer size=\"64\">0x00000001</integer> \n<key>AppleLVM-Type</key><string>internal error</string> \n<key>AppleLVM-Location</key><string/> \n<key>AppleLVM-ContentHint</key><string/> \n<key>AppleLVM-Name</key><string/> \n </dict> \n"
- " <dict> \n<key>AppleRAID-HeaderVersion</key><integer size=\"32\">0x00020000</integer> \n<key>AppleRAID-LevelName</key><string>internal error</string> \n<key>AppleRAID-SetName</key><string>internal error</string> \n<key>AppleRAID-SetUUID</key><string>internal error</string> \n<key>AppleRAID-SequenceNumber</key><integer size=\"32\">1</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x00008000</integer> \n<key>AppleRAID-ChunkCount</key><integer size=\"64\">0</integer> \n<key>AppleRAID-Members</key><array/> \n<key>AppleRAID-Spares</key><array/> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-QuickRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>internal error</string> \n<key>AppleRAID-ContentHint</key><string/> \n </dict> \n"
- "04:10:37"
- "AppleLVM-"
- "AppleLVM-ExtentCount"
- "AppleLVM-GroupUUID"
- "AppleLVM-Location"
- "AppleLVM-ParentUUID"
- "AppleLVM-Sequence"
- "AppleLVM-Status"
- "AppleLVM-Type"
- "AppleLVM-VolumeSize"
- "AppleLVM-VolumeUUID"
- "AppleLVMNotificationVolumeChanged"
- "AppleLVMNotificationVolumeDiscovered"
- "AppleLVMNotificationVolumeTerminated"
- "AppleLVMVolume"
- "AppleRAID-ContentHint"
- "AppleRAID-LVGExtents"
- "AppleRAID-LVGFreeSpace"
- "AppleRAID-LVGVolumeCount"
- "AppleRAID-MemberStart"
- "AppleRAID-MetaData1Used"
- "AppleRAID-MetaData2Size"
- "AppleRAID-QuickRebuild"
- "AppleRAID: Failed to find the size of the mirror quick rebuild bitmap."
- "AppleRAID: Insufficent free space to create requested logical volume."
- "AppleRAID: Insufficent free space to resize the logical volume."
- "AppleRAIDPrimary"
- "AppleRAIDUserLib.c"
- "Oct 12 2026"
- "RAIDNoMedia"
- "_extent data_"
- "bitmap"
- "fast"
- "header->lvExtentsCount == 1"
- "master"
- "meta"
- "writeSecondaryMetaData"
```
