## BTLEServerAgent

> `/usr/sbin/BTLEServerAgent`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-356.1.0.0.0
-  __TEXT.__text: 0x46e28
-  __TEXT.__auth_stubs: 0xc10
-  __TEXT.__objc_stubs: 0x6be0
-  __TEXT.__objc_methlist: 0x4014
+356.1.0.1.0
+  __TEXT.__text: 0x47390
+  __TEXT.__auth_stubs: 0xc70
+  __TEXT.__objc_stubs: 0x6c20
+  __TEXT.__objc_methlist: 0x4024
   __TEXT.__objc_classname: 0x4e9
   __TEXT.__objc_methtype: 0x1a2d
   __TEXT.__const: 0x328
   __TEXT.__gcc_except_tab: 0x9cc
-  __TEXT.__cstring: 0x1d92
-  __TEXT.__oslogstring: 0x6509
-  __TEXT.__objc_methname: 0xa384
+  __TEXT.__cstring: 0x1e04
+  __TEXT.__oslogstring: 0x6679
+  __TEXT.__objc_methname: 0xa3bc
   __TEXT.__ustring: 0xbe
-  __TEXT.__unwind_info: 0x10b8
-  __DATA_CONST.__auth_got: 0x618
+  __TEXT.__unwind_info: 0x10c0
+  __DATA_CONST.__auth_got: 0x648
   __DATA_CONST.__got: 0x4c8
   __DATA_CONST.__auth_ptr: 0x38
   __DATA_CONST.__const: 0xd48

   __DATA_CONST.__objc_arrayobj: 0x48
   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA.__objc_const: 0x8de8
-  __DATA.__objc_selrefs: 0x2458
+  __DATA.__objc_selrefs: 0x2468
   __DATA.__objc_ivar: 0x434
   __DATA.__objc_data: 0xdc0
   __DATA.__data: 0x660

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1568
-  Symbols:   359
-  CStrings:  2868
+  Functions: 1572
+  Symbols:   365
+  CStrings:  2880
 
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
