## sysinfocachegen

> `/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Support/sysinfocachegen`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-744.4.105.3.0
-  __TEXT.__text: 0xfd98
-  __TEXT.__auth_stubs: 0xe30
+744.4.105.4.0
+  __TEXT.__text: 0x108d8
+  __TEXT.__auth_stubs: 0xe50
   __TEXT.__objc_stubs: 0x7a0
   __TEXT.__objc_methlist: 0x224
-  __TEXT.__const: 0x128
-  __TEXT.__cstring: 0x489f
-  __TEXT.__oslogstring: 0x6f9
+  __TEXT.__const: 0x140
+  __TEXT.__cstring: 0x4a03
+  __TEXT.__oslogstring: 0x80d
   __TEXT.__objc_methname: 0x7cf
   __TEXT.__objc_classname: 0x11
   __TEXT.__objc_methtype: 0xea
-  __TEXT.__unwind_info: 0x1f8
-  __DATA_CONST.__auth_got: 0x720
+  __TEXT.__unwind_info: 0x210
+  __DATA_CONST.__auth_got: 0x730
   __DATA_CONST.__got: 0x158
+  __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x250
   __DATA_CONST.__cfstring: 0x1180
   __DATA_CONST.__objc_classlist: 0x10

   - /System/Library/PrivateFrameworks/DiagnosticLogCollection.framework/Versions/A/DiagnosticLogCollection
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 159
-  Symbols:   278
-  CStrings:  1010
+  Functions: 175
+  Symbols:   281
+  CStrings:  1019
 
Symbols:
+ _CFDataAppendBytes
+ _CFDataCreateMutable
+ _CFPropertyListCreateWithData
+ ___chkstk_darwin
+ ___memcpy_chk
+ __exit
+ _fchmod
+ _ftruncate
+ _geteuid
+ _lseek
+ _read
+ _strlcpy
+ _strrchr
- _CFPropertyListCreateFromStream
- _CFPropertyListWriteToStream
- _CFReadStreamClose
- _CFReadStreamCreateWithFile
- _CFReadStreamOpen
- _CFStringGetSystemEncoding
- _CFWriteStreamClose
- _CFWriteStreamCreateWithFile
- _CFWriteStreamOpen
- _fclose
CStrings:
+ "%s %s exited with status %d"
+ "%s %s was killed by signal %d"
+ "/var/db/RemoteManagement/caches"
+ "/var/db/RemoteManagement/caches/asp.stage.XXXXXX"
+ "CreateStagingFile"
+ "GatherCacheInfo"
+ "No system_profiler data was collected"
+ "Refusing to stage in %s: not a private directory"
+ "Unable to pipe to %s  error %s"
+ "Unable to protect %s  error %s"
+ "Unable to unlink %s  error %s"
+ "Unable to write the %s cache  error %s"
- "/tmp/asp.cache"
- "/tmp/tigerasp.xml"
- "w"
```
