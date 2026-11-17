## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/Contents/MacOS/iMessage`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1450.700.71.1.8
-  __TEXT.__text: 0xd4984
+1450.700.71.1.10
+  __TEXT.__text: 0xd49cc
   __TEXT.__auth_stubs: 0x1af0
-  __TEXT.__objc_stubs: 0xcfe0
-  __TEXT.__objc_methlist: 0x29ac
+  __TEXT.__objc_stubs: 0xd000
+  __TEXT.__objc_methlist: 0x29bc
   __TEXT.__const: 0xfe0
-  __TEXT.__gcc_except_tab: 0xa034
+  __TEXT.__gcc_except_tab: 0xa040
   __TEXT.__cstring: 0x32dd
-  __TEXT.__oslogstring: 0x1757b
+  __TEXT.__oslogstring: 0x174eb
   __TEXT.__objc_classname: 0x68f
-  __TEXT.__objc_methname: 0x126a3
+  __TEXT.__objc_methname: 0x12743
   __TEXT.__objc_methtype: 0x2ca9
   __TEXT.__ustring: 0x4
   __TEXT.__swift5_typeref: 0x74e

   __TEXT.__swift5_builtin: 0x78
   __TEXT.__swift5_mpenum: 0x38
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x24d0
+  __TEXT.__unwind_info: 0x24e0
   __TEXT.__eh_frame: 0xae8
   __DATA_CONST.__auth_got: 0xd88
   __DATA_CONST.__got: 0x1080

   __DATA_CONST.__objc_arrayobj: 0x78
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA.__objc_const: 0x2ee0
-  __DATA.__objc_selrefs: 0x3a20
+  __DATA.__objc_selrefs: 0x3a28
   __DATA.__objc_ivar: 0x1c8
   __DATA.__objc_data: 0x9c8
   __DATA.__data: 0xb68

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1898
+  Functions: 1899
   Symbols:   854
   CStrings:  4602
 
CStrings:
+ "_setReplyToGUIDForMessage:messageDictionary:"
+ "bestCandidateGroupChatWithFromIdentifier:toIdentifier:displayName:participants:updatingToLatestiMessageGroupID:sortedIdentifiers:serviceName:"
+ "setReplyToMessageGUID: %@ for message: %@"
- "Dropping group message payload of type %@ because its sender %@ is not in its from participants: %@"
- "Dropping message because its sender %@ is not in its participant list. participants: %@"
- "isSender:listedInParticipants:"
```
