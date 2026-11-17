## diskutil

> `/usr/sbin/diskutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 1037.160.3.701.5
-  __TEXT.__text: 0x852a4
-  __TEXT.__auth_stubs: 0x1dd0
+  __TEXT.__text: 0x82fe4
+  __TEXT.__auth_stubs: 0x1d60
   __TEXT.__objc_stubs: 0x58e0
   __TEXT.__objc_methlist: 0x1198
-  __TEXT.__const: 0x31f8
+  __TEXT.__const: 0x31e1
   __TEXT.__objc_methname: 0x524a
-  __TEXT.__cstring: 0x1e36f
+  __TEXT.__cstring: 0x1da47
   __TEXT.__objc_classname: 0x1df
   __TEXT.__objc_methtype: 0x6ed
   __TEXT.__ustring: 0x16

   __TEXT.__oslogstring: 0x1b2
   __TEXT.__swift5_capture: 0x184
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x16d0
+  __TEXT.__unwind_info: 0x1688
   __TEXT.__eh_frame: 0x11b0
-  __DATA_CONST.__auth_got: 0xef8
-  __DATA_CONST.__got: 0x480
+  __DATA_CONST.__auth_got: 0xec0
+  __DATA_CONST.__got: 0x478
   __DATA_CONST.__auth_ptr: 0x428
   __DATA_CONST.__const: 0x2388
-  __DATA_CONST.__cfstring: 0x8780
+  __DATA_CONST.__cfstring: 0x8440
   __DATA_CONST.__objc_classlist: 0x88
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28

   __DATA.__objc_data: 0x6d0
   __DATA.__data: 0x16b2
   __DATA.__common: 0x1d0
-  __DATA.__bss: 0x536c
+  __DATA.__bss: 0x5368
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/DiskArbitration.framework/Versions/A/DiskArbitration
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_DarwinFoundation2.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 2281
-  Symbols:   740
-  CStrings:  3315
+  Functions: 2256
+  Symbols:   732
+  CStrings:  3279
 
Symbols:
- _CFDataAppendBytes
- _CFDataCreateMutableCopy
- _CFDataCreateWithBytesNoCopy
- _CFDataGetBytes
- _CFDataReplaceBytes
- _CFDataSetLength
- _kCFAllocatorMalloc
- _reallocf
CStrings:
+ " <array> \n<dict> \n<key>AppleRAID-LevelName</key><string>Stripe</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>None</string> \n<key>AppleRAID-CanBeConvertedTo</key><false/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Mirror</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n<string>AppleRAID-Spares</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><true/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><true/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>Any</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Concat</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><true/> \n<key>AppleRAID-RemovalAllowed</key><string>Last</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n </array> \n"
+ " <dict> \n<key>AppleRAID-HeaderVersion</key><integer size=\"32\">0x00020000</integer> \n<key>AppleRAID-LevelName</key><string>internal error</string> \n<key>AppleRAID-SetName</key><string>internal error</string> \n<key>AppleRAID-SetUUID</key><string>internal error</string> \n<key>AppleRAID-SequenceNumber</key><integer size=\"32\">1</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x00008000</integer> \n<key>AppleRAID-ChunkCount</key><integer size=\"64\">0</integer> \n<key>AppleRAID-Members</key><array/> \n<key>AppleRAID-Spares</key><array/> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>internal error</string> \n<key>AppleRAID-ContentHint</key><string/> \n </dict> \n"
- " <array> \n<dict> \n<key>AppleLVM-Type</key><string>concat</string> \n</dict> \n<dict> \n<key>AppleLVM-Type</key><string>snap ro</string> \n</dict> \n<dict> \n<key>AppleLVM-Type</key><string>snap rw</string> \n</dict> \n </array> \n"
- " <array> \n<dict> \n<key>AppleRAID-LevelName</key><string>Stripe</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-QuickRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>None</string> \n<key>AppleRAID-CanBeConvertedTo</key><false/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Mirror</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n<string>AppleRAID-Spares</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><true/> \n<key>AppleRAID-QuickRebuild</key><true/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><true/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>Any</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Concat</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-QuickRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><true/> \n<key>AppleRAID-RemovalAllowed</key><string>Last</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>LVG</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><true/> \n<key>AppleRAID-RemovalAllowed</key><string>None</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n </array> \n"
- " <dict> \n<key>AppleLVM-Version</key><integer size=\"32\">0x00030000</integer> \n<key>AppleLVM-GroupUUID</key><string>internal error</string> \n<key>AppleLVM-VolumeUUID</key><string>internal error</string> \n<key>AppleLVM-Sequence</key><integer size=\"32\">0</integer> \n<key>AppleLVM-VolumeSize</key><integer size=\"64\">0x00000000</integer> \n<key>AppleLVM-ExtentCount</key><integer size=\"64\">0x00000001</integer> \n<key>AppleLVM-Type</key><string>internal error</string> \n<key>AppleLVM-Location</key><string/> \n<key>AppleLVM-ContentHint</key><string/> \n<key>AppleLVM-Name</key><string/> \n </dict> \n"
- " <dict> \n<key>AppleRAID-HeaderVersion</key><integer size=\"32\">0x00020000</integer> \n<key>AppleRAID-LevelName</key><string>internal error</string> \n<key>AppleRAID-SetName</key><string>internal error</string> \n<key>AppleRAID-SetUUID</key><string>internal error</string> \n<key>AppleRAID-SequenceNumber</key><integer size=\"32\">1</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x00008000</integer> \n<key>AppleRAID-ChunkCount</key><integer size=\"64\">0</integer> \n<key>AppleRAID-Members</key><array/> \n<key>AppleRAID-Spares</key><array/> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-QuickRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>internal error</string> \n<key>AppleRAID-ContentHint</key><string/> \n </dict> \n"
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
- "RAIDNoMedia"
- "_extent data_"
- "bitmap"
- "fast"
- "header->lvExtentsCount == 1"
- "master"
- "meta"
- "writeSecondaryMetaData"
```
