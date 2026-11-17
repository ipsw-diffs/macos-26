## bluetoothd

> `/usr/sbin/bluetoothd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-196.5.0.5.0
-  __TEXT.__text: 0x832680
+196.5.0.6.0
+  __TEXT.__text: 0x832914
   __TEXT.__auth_stubs: 0x4320
   __TEXT.__objc_stubs: 0x139e0
   __TEXT.__init_offsets: 0x5c
   __TEXT.__objc_methlist: 0x7a74
-  __TEXT.__gcc_except_tab: 0x67260
+  __TEXT.__gcc_except_tab: 0x67264
   __TEXT.__const: 0x846c
-  __TEXT.__cstring: 0xb0b82
+  __TEXT.__cstring: 0xb0d79
   __TEXT.__oslogstring: 0xaf832
   __TEXT.__objc_methname: 0x18649
   __TEXT.__objc_classname: 0x769

   - /usr/lib/libsqlite3.dylib
   Functions: 33440
   Symbols:   1368
-  CStrings:  37941
+  CStrings:  37946
 
Functions:
~ sub_1000f6428 : 908 -> 1192
~ sub_10014bdc0 -> sub_10014bedc : 280 -> 284
~ sub_10014c5f4 -> sub_10014c714 : 1020 -> 1380
~ sub_100546964 -> sub_100546bec : 852 -> 864
CStrings:
+ "20:23:12"
+ "Nov 12 2026"
+ "Rejected malformed AAP SDP Protocol Descriptor List -- l2capSeq element type validation failed, ElemSeq[1].ElemType:%d\n"
+ "Rejected malformed AAP SDP Protocol Descriptor List -- l2capSeq type validation failed, ElemType:%d\n Size:%d \n"
+ "Rejected malformed AAP SDP Protocol Descriptor List -- seq type/size validation failed, ElemType:%d Size:%d \n"
+ "Rejecting HID GET_REPORT %s response, expectingContinuation=%d (transParam 0x%x len %d)"
+ "Rejecting HID GET_REPORT response - exceeded %d fragments for one request"
- "00:16:08"
- "Nov  3 2026"
```
