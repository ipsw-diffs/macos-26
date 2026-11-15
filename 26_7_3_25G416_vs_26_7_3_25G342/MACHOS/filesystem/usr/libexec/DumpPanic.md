## DumpPanic

> `/usr/libexec/DumpPanic`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__eh_frame`
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

-6.160.2.702.1
-  __TEXT.__text: 0x30d14
-  __TEXT.__auth_stubs: 0x10d0
-  __TEXT.__objc_stubs: 0x22c0
-  __TEXT.__objc_methlist: 0x758
-  __TEXT.__cstring: 0x323d
+6.160.2.701.1
+  __TEXT.__text: 0x2f888
+  __TEXT.__auth_stubs: 0x1050
+  __TEXT.__objc_stubs: 0x2240
+  __TEXT.__objc_methlist: 0x738
+  __TEXT.__cstring: 0x32ad
   __TEXT.__objc_classname: 0x10c
   __TEXT.__objc_methtype: 0x45c
-  __TEXT.__objc_methname: 0x1e98
-  __TEXT.__const: 0x310
-  __TEXT.__oslogstring: 0x5708
+  __TEXT.__objc_methname: 0x1df6
+  __TEXT.__const: 0x300
+  __TEXT.__oslogstring: 0x5218
   __TEXT.__gcc_except_tab: 0x630
   __TEXT.__constg_swiftt: 0x90
   __TEXT.__swift5_typeref: 0x8b
   __TEXT.__swift5_reflstr: 0x27
   __TEXT.__swift5_fieldmd: 0x34
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x820
+  __TEXT.__unwind_info: 0x7f8
   __TEXT.__eh_frame: 0x48
-  __DATA_CONST.__auth_got: 0x878
+  __DATA_CONST.__auth_got: 0x838
   __DATA_CONST.__got: 0x268
   __DATA_CONST.__auth_ptr: 0x70
   __DATA_CONST.__const: 0x7e0

   __DATA_CONST.__objc_arrayobj: 0xd8
   __DATA_CONST.__objc_dictobj: 0x1b8
   __DATA_CONST.__objc_intobj: 0xd8
-  __DATA.__objc_const: 0x10d8
-  __DATA.__objc_selrefs: 0x940
-  __DATA.__objc_ivar: 0xf8
+  __DATA.__objc_const: 0x1078
+  __DATA.__objc_selrefs: 0x920
+  __DATA.__objc_ivar: 0xec
   __DATA.__objc_data: 0x4d8
   __DATA.__data: 0x2f8
   __DATA.__common: 0x28

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 934
-  Symbols:   380
-  CStrings:  1427
+  Functions: 908
+  Symbols:   371
+  CStrings:  1398
 
Symbols:
+ _getxattr
+ _mktemp
+ _rename
- __os_log_fault_impl
- _arc4random
- _dirname_r
- _fdopen
- _fgetxattr
- _fsetxattr
- _geteuid
- _gzdopen
- _mkstemp
- _openat
- _renameat
- _unlinkat
CStrings:
+ "-[CoreFileHandler getPanicRegion]"
+ "/private/var/tmp/kernel_panics/staged/tempUserSpaceCore.XXX"
+ "/private/var/tmp/panicregion.XXX"
+ "Failed to open %s core compressed output file with error %s"
+ "Failed to rename compressed %s from %s to %s"
+ "failed to creat() DumpPanicDone cookie at path %s with error %s"
+ "getxattr %s returned error : %s"
+ "gzopen %s"
+ "gzopen(%s, wb) error: %s"
+ "handlekernelcore.m"
+ "panicRegionTempFile != NULL"
- "%s no longer refers to the core we processed, not removing it"
- "/private/var/tmp/panicregion.XXXXXXXX"
- "2"
- "Cannot remove untrusted staged '%{public}@' : %{public}@"
- "DumpPanicDone cookie already exists at path %s"
- "DumpPanicDone cookie at %s is not the file we wrote (mode 0%o uid %u)"
- "Failed to open %s core compressed output file"
- "Failed to rename compressed %s from %s to %s with error : %s"
- "_input_core_dev"
- "_input_core_fd"
- "_input_core_ino"
- "closeInputCore"
- "directory %s was not owned by root:wheel (uid %u gid %u), taking ownership"
- "failed to create DumpPanicDone cookie at path %s with error %s"
- "failed to create a temporary file for the panic region. Error: %s"
- "failed to create staged file %s with error: %s"
- "failed to derive the directory holding %s with error: %s"
- "failed to open directory %s with error: %s"
- "failed to open the directory holding %s with error: %s"
- "failed to remove %s with error: %s"
- "fdopen of %s failed with error: %s"
- "fgetxattr %s returned error : %s"
- "fileSystemRepresentation"
- "fstat of %s failed with error: %s"
- "fstat of directory %s failed with error: %s"
- "gzdopen of %s/%s failed"
- "gzdopen(%s, wb) error: %s"
- "lstat of %s failed with error: %s"
- "lstat of staged '%{public}@' failed with error %s"
- "open(%s) error: %s"
- "refusing core at %s : not a regular file (mode 0%o)"
- "refusing core at %s : owned by uid %u and not from a directory only uid %u can write"
- "refusing core at %s : unexpected link count %u"
- "refusing core at %s : writable by others (mode 0%o)"
- "refusing to pull in staged '%{public}@' : not a file we wrote (mode 0%o uid %u nlink %u)"
- "refusing untrusted directory %s (uid %u mode 0%o)"
- "removeOriginalCore"
- "stagedFileIsOurs:"
- "staging compressed %s core at %s/%s"
- "tempUserSpaceCore.%08x%08x"
```
