## DumpPanicRecoveryOS

> `/usr/libexec/DumpPanicRecoveryOS`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-6.160.2.701.1
-  __TEXT.__text: 0x2a32c
-  __TEXT.__auth_stubs: 0xbc0
-  __TEXT.__objc_stubs: 0x1dc0
-  __TEXT.__objc_methlist: 0x5d8
-  __TEXT.__const: 0x280
-  __TEXT.__objc_methname: 0x1a23
-  __TEXT.__cstring: 0x2cdb
-  __TEXT.__oslogstring: 0x4d4f
+6.160.2.702.1
+  __TEXT.__text: 0x2b778
+  __TEXT.__auth_stubs: 0xc40
+  __TEXT.__objc_stubs: 0x1e40
+  __TEXT.__objc_methlist: 0x5f8
+  __TEXT.__const: 0x290
+  __TEXT.__objc_methname: 0x1a9f
+  __TEXT.__cstring: 0x2c6e
+  __TEXT.__oslogstring: 0x5239
   __TEXT.__objc_classname: 0xe4
   __TEXT.__objc_methtype: 0x44a
   __TEXT.__gcc_except_tab: 0x55c
-  __TEXT.__unwind_info: 0x750
-  __DATA_CONST.__auth_got: 0x5f0
+  __TEXT.__unwind_info: 0x780
+  __DATA_CONST.__auth_got: 0x630
   __DATA_CONST.__got: 0x1d0
   __DATA_CONST.__auth_ptr: 0x30
   __DATA_CONST.__const: 0x708

   __DATA_CONST.__objc_arrayobj: 0xa8
   __DATA_CONST.__objc_dictobj: 0x190
   __DATA_CONST.__objc_intobj: 0xf0
-  __DATA.__objc_const: 0xdb0
-  __DATA.__objc_selrefs: 0x7e8
-  __DATA.__objc_ivar: 0xd0
+  __DATA.__objc_const: 0xe10
+  __DATA.__objc_selrefs: 0x808
+  __DATA.__objc_ivar: 0xdc
   __DATA.__objc_data: 0x370
   __DATA.__data: 0x168
   __DATA.__common: 0x30

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 846
-  Symbols:   270
-  CStrings:  1278
+  Functions: 873
+  Symbols:   279
+  CStrings:  1307
 
Symbols:
+ __os_log_fault_impl
+ _arc4random
+ _dirname_r
+ _fdopen
+ _fgetxattr
+ _fsetxattr
+ _geteuid
+ _gzdopen
+ _mkstemp
+ _openat
+ _renameat
+ _unlinkat
- _getxattr
- _mktemp
- _rename
CStrings:
+ "%s no longer refers to the core we processed, not removing it"
+ "/private/var/tmp/panicregion.XXXXXXXX"
+ "2"
+ "Cannot remove untrusted staged '%{public}@' : %{public}@"
+ "DumpPanicDone cookie already exists at path %s"
+ "DumpPanicDone cookie at %s is not the file we wrote (mode 0%o uid %u)"
+ "Failed to open %s core compressed output file"
+ "Failed to rename compressed %s from %s to %s with error : %s"
+ "_input_core_dev"
+ "_input_core_fd"
+ "_input_core_ino"
+ "closeInputCore"
+ "directory %s was not owned by root:wheel (uid %u gid %u), taking ownership"
+ "failed to create DumpPanicDone cookie at path %s with error %s"
+ "failed to create a temporary file for the panic region. Error: %s"
+ "failed to create staged file %s with error: %s"
+ "failed to derive the directory holding %s with error: %s"
+ "failed to open directory %s with error: %s"
+ "failed to open the directory holding %s with error: %s"
+ "failed to remove %s with error: %s"
+ "fdopen of %s failed with error: %s"
+ "fgetxattr %s returned error : %s"
+ "fileSystemRepresentation"
+ "fstat of %s failed with error: %s"
+ "fstat of directory %s failed with error: %s"
+ "gzdopen of %s/%s failed"
+ "gzdopen(%s, wb) error: %s"
+ "lstat of %s failed with error: %s"
+ "lstat of staged '%{public}@' failed with error %s"
+ "open(%s) error: %s"
+ "refusing core at %s : not a regular file (mode 0%o)"
+ "refusing core at %s : owned by uid %u and not from a directory only uid %u can write"
+ "refusing core at %s : unexpected link count %u"
+ "refusing core at %s : writable by others (mode 0%o)"
+ "refusing to pull in staged '%{public}@' : not a file we wrote (mode 0%o uid %u nlink %u)"
+ "refusing untrusted directory %s (uid %u mode 0%o)"
+ "removeOriginalCore"
+ "stagedFileIsOurs:"
+ "staging compressed %s core at %s/%s"
+ "tempUserSpaceCore.%08x%08x"
- "-[CoreFileHandler getPanicRegion]"
- "/private/var/tmp/kernel_panics/staged/tempUserSpaceCore.XXX"
- "/private/var/tmp/panicregion.XXX"
- "Failed to open %s core compressed output file with error %s"
- "Failed to rename compressed %s from %s to %s"
- "failed to creat() DumpPanicDone cookie at path %s with error %s"
- "getxattr %s returned error : %s"
- "gzopen %s"
- "gzopen(%s, wb) error: %s"
- "handlekernelcore.m"
- "panicRegionTempFile != NULL"
```
