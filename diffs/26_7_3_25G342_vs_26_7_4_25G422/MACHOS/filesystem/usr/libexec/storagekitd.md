## storagekitd

> `/usr/libexec/storagekitd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 1037.160.3.701.5
-  __TEXT.__text: 0x196ccc
-  __TEXT.__auth_stubs: 0x2eb0
+  __TEXT.__text: 0x194a0c
+  __TEXT.__auth_stubs: 0x2e80
   __TEXT.__objc_stubs: 0xef00
   __TEXT.__objc_methlist: 0x80f4
-  __TEXT.__const: 0xc98
+  __TEXT.__const: 0xc88
   __TEXT.__objc_methname: 0x158e2
   __TEXT.__oslogstring: 0x64a4
   __TEXT.__objc_classname: 0xd84
   __TEXT.__objc_methtype: 0x631b
   __TEXT.__gcc_except_tab: 0x2718
-  __TEXT.__cstring: 0x68301
-  __TEXT.__unwind_info: 0x2af8
+  __TEXT.__cstring: 0x679e5
+  __TEXT.__unwind_info: 0x2ab0
   __TEXT.__eh_frame: 0x168
-  __DATA_CONST.__auth_got: 0x1768
+  __DATA_CONST.__auth_got: 0x1750
   __DATA_CONST.__got: 0xb48
   __DATA_CONST.__auth_ptr: 0xb0
   __DATA_CONST.__const: 0x2b80
-  __DATA_CONST.__cfstring: 0x3f8a0
+  __DATA_CONST.__cfstring: 0x3f580
   __DATA_CONST.__objc_classlist: 0x428
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0xa8

   __DATA.__objc_ivar: 0xa2c
   __DATA.__objc_data: 0x2990
   __DATA.__data: 0x918
-  __DATA.__bss: 0x578
+  __DATA.__bss: 0x570
   __DATA.__common: 0xcc8
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/libcsfde.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 3623
-  Symbols:   1119
-  CStrings:  14583
+  Functions: 3598
+  Symbols:   1116
+  CStrings:  14548
 
Symbols:
- _CFDataCreateMutableCopy
- _CFDataReplaceBytes
- _CFDataSetLength
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
- "_extent data_"
- "bitmap"
- "fast"
- "header->lvExtentsCount == 1"
- "master"
- "meta"
- "writeSecondaryMetaData"
```
