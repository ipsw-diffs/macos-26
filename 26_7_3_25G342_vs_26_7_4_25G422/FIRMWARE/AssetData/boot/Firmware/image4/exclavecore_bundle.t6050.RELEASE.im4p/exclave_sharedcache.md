## exclave_sharedcache

> `AssetData/boot/Firmware/image4/exclavecore_bundle.t6050.RELEASE.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__data`
- `__PDATA.__const`
- `__PDATA.__shared_cache`
- `__PDATA.__auth_ptr`

```diff

 1148.120.6.0.0
-  __TEXT.__text: 0xae205c
+  __TEXT.__text: 0xae52ac
   __TEXT.__lcxx_override: 0x34c
-  __TEXT.__cstring: 0x809a1
-  __TEXT.__const: 0x162cf4
-  __TEXT.__swift5_typeref: 0x20400
-  __TEXT.__swift5_reflstr: 0x2bf28
+  __TEXT.__cstring: 0x80c91
+  __TEXT.__const: 0x162d54
+  __TEXT.__swift5_typeref: 0x20420
+  __TEXT.__swift5_reflstr: 0x2bf38
   __TEXT.__swift5_assocty: 0xbd30
-  __TEXT.__swift5_fieldmd: 0x460ac
-  __TEXT.__constg_swiftt: 0x46818
+  __TEXT.__swift5_fieldmd: 0x460e4
+  __TEXT.__constg_swiftt: 0x4688c
   __TEXT.__swift5_protos: 0xd2c
   __TEXT.__swift5_proto: 0x7840
-  __TEXT.__swift5_types: 0x475c
+  __TEXT.__swift5_types: 0x4764
   __TEXT.__swift5_types2: 0x68
   __TEXT.__swift5_builtin: 0x1fa4
   __TEXT.__objc_methtype: 0x21f

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x100
-  __TEXT.__eh_frame: 0x5dc1c
+  __TEXT.__eh_frame: 0x5dd24
   __DATA.__TIGHTBEAM_VT: 0xb70
   __DATA.__TIGHTBEAM: 0x318
-  __DATA.__data: 0x33b08
-  __DATA.__const: 0xbb928
+  __DATA.__data: 0x33b68
+  __DATA.__const: 0xbb948
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x147b9
-  __DATA.__auth_ptr: 0x5910
+  __DATA.__auth_ptr: 0x5920
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x2a0
   __DATA.__MMIOREGS: 0x795

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x38
-  __DATA.__bss: 0x21df0
-  __DATA.__common: 0x1ff1
+  __DATA.__bss: 0x21e10
+  __DATA.__common: 0x1fe1
   __PDATA.__data: 0x24e0
   __PDATA.__const: 0x5e38
   __PDATA.__ENDPOINTS: 0x838

   __PDATA.__common: 0x2520
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 41955
+  Functions: 41967
   Symbols:   1
-  CStrings:  12002
+  CStrings:  12024
 
CStrings:
+ "!ctx->used"
+ "(addr - base) % slot_size == 0"
+ "(map[idx / FREE_MAP_WORD_BITS] & bit) == 0"
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Sun Nov  8 22:08:21 PST 2026; root:/ExclaveImage4/RELEASE_ARM64E"
+ "Build Date: Sun Nov  8 21:53:09 PST 2026"
+ "Builtin.FixedArray of %zd elements with stride %zu is too large to be representable\n"
+ "Cannot mint a moved capability"
+ "ExclaveOS Image4 Framework Version 7.0.0: Sun Nov  8 22:08:21 PST 2026; root:/ExclaveImage4/RELEASE_ARM64E"
+ "Failed to delete root endpoint capability "
+ "Failed to mint endpoint capability from "
+ "No init endpoint for asid "
+ "Sun Nov  8 22:44:09 PST 2026"
+ "Tried to build a Builtin.FixedArray without metadata for the element type"
+ "addr - base < populated_bytes"
+ "addr >= base"
+ "free_map_acquire"
+ "free_map_release"
+ "getOrAllocateComponentResourceCapFromEdge(edge:permissions:)"
+ "idx < populated_slots"
+ "init(indirectTag:cap:compBadge:clientNotificationType:)"
+ "initialize_thread_context"
+ "ipc_buffer_free_map != NULL"
+ "mintEndpoint(to:permissions:copy:)"
+ "release_thread_context"
+ "slot_index"
+ "thread_context_free_map != NULL"
+ "type where a Builtin.FixedArray count is required"
+ "unresolved Builtin.FixedArray element type"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Mon Oct 12 02:09:01 PDT 2026; root:/ExclaveImage4/RELEASE_ARM64E"
- "Build Date: Sun Oct 11 23:57:31 PDT 2026"
- "ExclaveOS Image4 Framework Version 7.0.0: Mon Oct 12 02:09:01 PDT 2026; root:/ExclaveImage4/RELEASE_ARM64E"
- "Mon Oct 12 02:40:00 PDT 2026"
- "getOrAllocateComponentResourceCapFromEdge(edge:)"
- "init(indirectTag:cap:identifier:compBadge:clientNotificationType:)"
```
