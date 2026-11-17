## ARDAgent

> `/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/MacOS/ARDAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

-744.4.105.3.0
-  __TEXT.__text: 0xa34f4
+744.4.105.4.0
+  __TEXT.__text: 0xa3fc0
   __TEXT.__auth_stubs: 0x2870
   __TEXT.__objc_stubs: 0x2ac0
   __TEXT.__objc_methlist: 0xee8
   __TEXT.__const: 0x1018
-  __TEXT.__oslogstring: 0x7085
-  __TEXT.__cstring: 0x23103
+  __TEXT.__oslogstring: 0x70d2
+  __TEXT.__cstring: 0x236f7
   __TEXT.__objc_methname: 0x2896
   __TEXT.__objc_classname: 0x182
   __TEXT.__objc_methtype: 0x972
-  __TEXT.__unwind_info: 0xf90
+  __TEXT.__unwind_info: 0xf98
   __DATA_CONST.__auth_got: 0x1440
   __DATA_CONST.__got: 0x4e8
   __DATA_CONST.__auth_ptr: 0x38

   __DATA.__objc_selrefs: 0xd40
   __DATA.__objc_ivar: 0xb0
   __DATA.__objc_data: 0x460
-  __DATA.__data: 0x3e0
-  __DATA.__bss: 0x15b0
-  __DATA.__common: 0xd7e9
+  __DATA.__data: 0x428
+  __DATA.__thread_vars: 0x18
+  __DATA.__thread_bss: 0x1
+  __DATA.__bss: 0x15c8
+  __DATA.__common: 0xd7f9
   __CGPreLoginApp.__cgpreloginapp: 0x0
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/libpcre2-8.0.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1552
-  Symbols:   816
-  CStrings:  4533
+  Functions: 1561
+  Symbols:   817
+  CStrings:  4555
 
Symbols:
+ __tlv_bootstrap
CStrings:
+ "EnqueueLocalDatagram"
+ "InitLocalDatagramPipe"
+ "Rejecting kCmdSLSCommandReq (sub-command %u) because the packet length (%d) has no room for an MDItemRef"
+ "Rejecting kCmdSLSCommandReq (sub-command slsStartSearch) because the folder scope path (%u bytes) does not fit in the packet (%d)."
+ "Rejecting kCmdSLSCommandReq (sub-command slsStartSearch) because the packet length (%d) has no room for the folder scope path size"
+ "Rejecting kCmdSLSCommandReq (sub-command slsStartSearch) because the packet length (%d) is smaller than the header (%u)"
+ "Rejecting kCmdSLSCommandReq because %d trailing bytes cannot hold a search item header (%zu)"
+ "Rejecting kCmdSLSCommandReq because an unknown sub-command (%u) was received."
+ "Rejecting kCmdSLSCommandReq because the packet length (%d) is smaller than the header (%zu)"
+ "Unable to allocate %ld bytes in delete selected"
+ "Unable to allocate %ld bytes in delete selected query"
+ "Unable to write to gLocalDatagramPipe"
+ "dropping datagram from loopback source"
+ "hp->addrequal %d hp->localOrigin %d hp->valid %d flags %d"
+ "invalid datagram size %ld"
+ "memory error"
+ "path data out of range - pktIndex %u dataSize %d dataLen %d"
+ "performSLS_Thread: folder scope path component (%d bytes) does not fit in the remaining path data (%d) - ignoring scope."
+ "performSLS_Thread: folder scope path is truncated at offset %d of %u - ignoring scope."
+ "slsCopyToHFSUniStr255"
+ "slsCopyToHFSUniStr255: truncating a %ld character name to %d"
+ "slsNotficationCallback"
+ "slsNotficationCallback: dropping a search result whose entry (%u bytes) does not fit in an empty packet (%d)"
+ "unable to create local datagram pipe. errno %d %s"
- "hp->addrequal %d hp->selfsend %d hp->valid %d flags %d"
- "path data out of range"
```
