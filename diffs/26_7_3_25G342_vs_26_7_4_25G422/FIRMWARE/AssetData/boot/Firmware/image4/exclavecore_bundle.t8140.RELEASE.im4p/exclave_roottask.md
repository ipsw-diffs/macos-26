## exclave_roottask

> `AssetData/boot/Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_roottask`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__chain_fixups`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA.__auth_ptr`
- `__DATA.__got`

```diff

-1195.160.9.0.0
-  __TEXT.__text: 0x4bad9c
+1195.160.9.700.2
+  __TEXT.__text: 0x4bd7f0
   __TEXT.__lcxx_override: 0x34c
-  __TEXT.__const: 0xedba0
-  __TEXT.__cstring: 0x3bbb2
+  __TEXT.__const: 0xedbe0
+  __TEXT.__cstring: 0x3bd62
   __TEXT.__swift5_typeref: 0xc152
   __TEXT.__swift5_capture: 0x1608
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__swift5_fieldmd: 0x11008
-  __TEXT.__constg_swiftt: 0x14b7c
+  __TEXT.__swift5_fieldmd: 0x11018
+  __TEXT.__constg_swiftt: 0x14b98
   __TEXT.__swift5_builtin: 0xde8
   __TEXT.__swift5_reflstr: 0xa4ec
   __TEXT.__swift5_assocty: 0x67e0
   __TEXT.__swift5_protos: 0x424
   __TEXT.__swift5_proto: 0x2890
-  __TEXT.__swift5_types: 0x1340
+  __TEXT.__swift5_types: 0x1344
   __TEXT.__objc_methtype: 0x1bf
   __TEXT.__swift5_mpenum: 0x540
   __TEXT.__swift5_types2: 0x34

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x78
-  __TEXT.__eh_frame: 0x1ce14
+  __TEXT.__eh_frame: 0x1cf0c
   __DATA.__data: 0xbe90
   __DATA.__shared_cache: 0x70
   __DATA.__mod_init_func: 0x58
   __DATA.__auth_ptr: 0xfa8
-  __DATA.__const: 0x30c38
+  __DATA.__const: 0x30c58
   __DATA.__ENDPOINTS: 0xa46
   __DATA.__DEVICETREE: 0x30
   __DATA.__got: 0x198

   __DATA_CONST.__mod_term_func: 0x0
   __PDATA.__mod_init_func: 0x0
   __PDATA.__shared_cache: 0x0
-  Functions: 17683
+  Functions: 17679
   Symbols:   27
-  CStrings:  5916
+  CStrings:  5925
 
CStrings:
+ "Builtin.FixedArray of %zd elements with stride %zu is too large to be representable\n"
+ "Cannot mint a moved capability"
+ "Failed to delete root endpoint capability "
+ "Failed to mint endpoint capability from "
+ "No init endpoint for asid "
+ "Tried to build a Builtin.FixedArray without metadata for the element type"
+ "getOrAllocateComponentResourceCapFromEdge(edge:permissions:)"
+ "init(indirectTag:cap:compBadge:clientNotificationType:)"
+ "mintEndpoint(to:permissions:copy:)"
+ "type where a Builtin.FixedArray count is required"
+ "unresolved Builtin.FixedArray element type"
- "getOrAllocateComponentResourceCapFromEdge(edge:)"
- "init(indirectTag:cap:identifier:compBadge:clientNotificationType:)"
```
