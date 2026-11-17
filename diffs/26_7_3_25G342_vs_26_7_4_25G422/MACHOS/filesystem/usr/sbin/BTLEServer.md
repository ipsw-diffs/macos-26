## BTLEServer

> `/usr/sbin/BTLEServer`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-356.1.0.0.0
-  __TEXT.__text: 0x46d28
-  __TEXT.__auth_stubs: 0xbf0
-  __TEXT.__objc_stubs: 0x6be0
-  __TEXT.__objc_methlist: 0x4014
+356.1.0.1.0
+  __TEXT.__text: 0x47290
+  __TEXT.__auth_stubs: 0xc50
+  __TEXT.__objc_stubs: 0x6c20
+  __TEXT.__objc_methlist: 0x4024
   __TEXT.__objc_classname: 0x4e9
   __TEXT.__objc_methtype: 0x1a2d
-  __TEXT.__cstring: 0x1dd1
+  __TEXT.__cstring: 0x1e43
   __TEXT.__const: 0x328
-  __TEXT.__objc_methname: 0xa384
-  __TEXT.__oslogstring: 0x64f0
+  __TEXT.__objc_methname: 0xa3bc
+  __TEXT.__oslogstring: 0x6660
   __TEXT.__gcc_except_tab: 0x9cc
   __TEXT.__ustring: 0xbe
-  __TEXT.__unwind_info: 0x10d0
-  __DATA_CONST.__auth_got: 0x608
+  __TEXT.__unwind_info: 0x10d8
+  __DATA_CONST.__auth_got: 0x638
   __DATA_CONST.__got: 0x4c8
   __DATA_CONST.__auth_ptr: 0x38
   __DATA_CONST.__const: 0xd48

   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA_CONST.__objc_intobj: 0xf0
   __DATA.__objc_const: 0x8de8
-  __DATA.__objc_selrefs: 0x2458
+  __DATA.__objc_selrefs: 0x2468
   __DATA.__objc_ivar: 0x434
   __DATA.__objc_data: 0xdc0
   __DATA.__data: 0x660

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1566
-  Symbols:   357
-  CStrings:  2864
+  Functions: 1570
+  Symbols:   363
+  CStrings:  2876
 
Symbols:
+ ___error
+ _chmod
+ _geteuid
+ _lstat
+ _mkdir
+ _mkdtemp
CStrings:
+ "/var/tmp/BTLEServer"
+ "/var/tmp/BTLEServer.XXXXXX"
+ "LoggingManager - Failed to create directory %@. Error: %{darwin.errno}d"
+ "LoggingManager - Failed to lstat directory %@. Error: %{darwin.errno}d"
+ "LoggingManager - Not using untrusted directory %@ (mode 0%o, uid %u)"
+ "LoggingManager - logRetrievalComplete - Failed to create fallback directory. Error: %{darwin.errno}d"
+ "LoggingManager - logRetrievalComplete - Using fallback directory %@"
+ "NULL"
+ "No entitlements. Good bye."
+ "Not a valid application ID. Good bye. %s"
+ "_createTrustedDirectoryAtPath:"
+ "com.apple.DiagnosticExtensions.BluetoothHeadset"
+ "com.apple.bluetooth.airpodslogging"
+ "fileSystemRepresentation"
- "/var/tmp/BTLEServer/"
- "LoggingManager - logRetrievalComplete - Failed to create directory %@. Error: %@"
```
