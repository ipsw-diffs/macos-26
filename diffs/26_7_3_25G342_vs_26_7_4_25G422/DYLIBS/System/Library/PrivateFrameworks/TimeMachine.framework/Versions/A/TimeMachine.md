## TimeMachine

> `/System/Library/PrivateFrameworks/TimeMachine.framework/Versions/A/TimeMachine`

```diff

-2538.3.1.0.0
-  __TEXT.__text: 0xbd9a8
-  __TEXT.__auth_stubs: 0x2730
-  __TEXT.__objc_methlist: 0x5900
+2538.3.2.0.0
+  __TEXT.__text: 0xbe92c
+  __TEXT.__auth_stubs: 0x2760
+  __TEXT.__objc_methlist: 0x5918
   __TEXT.__const: 0x38a0
   __TEXT.__gcc_except_tab: 0x1fd8
-  __TEXT.__cstring: 0xc5fd
+  __TEXT.__cstring: 0xc96d
   __TEXT.__ustring: 0xa4
   __TEXT.__oslogstring: 0xb
   __TEXT.__dlopen_cstrs: 0xb0

   __TEXT.__swift_as_entry: 0x140
   __TEXT.__swift_as_ret: 0x148
   __TEXT.__swift5_protos: 0x10
-  __TEXT.__unwind_info: 0x2fc0
+  __TEXT.__unwind_info: 0x2fd0
   __TEXT.__eh_frame: 0x345c
   __TEXT.__objc_classname: 0x9c2
-  __TEXT.__objc_methname: 0xd055
+  __TEXT.__objc_methname: 0xd105
   __TEXT.__objc_methtype: 0x2401
-  __TEXT.__objc_stubs: 0x9940
-  __DATA_CONST.__got: 0xb08
+  __TEXT.__objc_stubs: 0x99c0
+  __DATA_CONST.__got: 0xb10
   __DATA_CONST.__const: 0xa68
   __DATA_CONST.__objc_classlist: 0x298
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3308
+  __DATA_CONST.__objc_selrefs: 0x3330
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x228
   __DATA_CONST.__objc_arraydata: 0xf8
-  __AUTH_CONST.__auth_got: 0x13b0
-  __AUTH_CONST.__const: 0x5930
-  __AUTH_CONST.__cfstring: 0x8340
+  __AUTH_CONST.__auth_got: 0x13c8
+  __AUTH_CONST.__const: 0x5980
+  __AUTH_CONST.__cfstring: 0x8560
   __AUTH_CONST.__objc_const: 0x8af8
   __AUTH_CONST.__objc_intobj: 0x258
   __AUTH_CONST.__objc_arrayobj: 0x78

   __AUTH.__data: 0x1f8
   __DATA.__objc_ivar: 0x484
   __DATA.__data: 0x9278
-  __DATA.__bss: 0x37b0
+  __DATA.__bss: 0x37c0
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0xab0
   __DATA_DIRTY.__data: 0x230

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3670
-  Symbols:   5867
-  CStrings:  3944
+  Functions: 3677
+  Symbols:   5883
+  CStrings:  3968
 
Symbols:
+ +[NSData(TMExtensions) _tm_dataByReadingRegularFileAtURL:error:]
+ -[NSURL(TMAdditions) tm_FULLFSYNCItemsNamed:error:]
+ GCC_except_table71
+ _NSCocoaErrorDomain
+ _TMOpenContainingDirectory
+ _TMReadErrorForErrno
+ ___42-[TMDiskImage writeTimeMachineInfo:error:]_block_invoke
+ ___42-[TMDiskImage writeTimeMachineInfo:error:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e15_v32?0816^B24l
+ _fstatat
+ _objc_msgSend$_tm_dataByReadingRegularFileAtURL:error:
+ _objc_msgSend$dictionaryWithCapacity:
+ _objc_msgSend$enumerateKeysAndObjectsUsingBlock:
+ _objc_msgSend$initWithFileDescriptor:closeOnDealloc:
+ _objc_msgSend$readDataToEndOfFileAndReturnError:
+ _objc_msgSend$tm_FULLFSYNCItemsNamed:error:
+ _openat
+ _renameat
+ _unlinkat
+ _writeTimeMachineInfo:error:.knownKeys
+ _writeTimeMachineInfo:error:.onceToken
- GCC_except_table44
- GCC_except_table69
- _objc_msgSend$dataWithContentsOfURL:options:error:
- _objc_msgSend$tm_fsync:
- _rename
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Extensions/NSData+TMExtensions.m"
+ "Dropping unrecognized key '%@' from the Time Machine info for '%@'"
+ "FULLFSYNC failed for '%@', error: %d"
+ "FULLFSYNC failed to open '%@', error: %d"
+ "FULLFSYNC failed under '%@', error: %@"
+ "FULLFSYNC not performed for '%@' - file does not exist"
+ "Failed to remove '%@', error: %d - the write will fail"
+ "Ignoring '%@' - not a real file or directory"
+ "Refusing to read '%@' - it is a symbolic link"
+ "Refusing to read '%@' - it is not a regular file"
+ "Refusing to use '%@' - it is a symbolic link"
+ "SafeFileIO"
+ "Unexpected non-regular file at '%@' - removing it before writing"
+ "VerificationDate"
+ "VerificationExtendedSkip"
+ "VerificationID"
+ "VerificationSkeletonCaptureDate"
+ "VerificationState"
+ "_tm_dataByReadingRegularFileAtURL:error:"
+ "dictionaryWithCapacity:"
+ "enumerateKeysAndObjectsUsingBlock:"
+ "initWithFileDescriptor:closeOnDealloc:"
+ "readDataToEndOfFileAndReturnError:"
+ "tm_FULLFSYNCItemsNamed:error:"
+ "v32@?0@8@16^B24"
- "dataWithContentsOfURL:options:error:"
```
