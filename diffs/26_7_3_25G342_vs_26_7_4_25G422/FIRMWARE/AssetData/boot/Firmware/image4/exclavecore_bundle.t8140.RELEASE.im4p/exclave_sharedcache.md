## exclave_sharedcache

> `AssetData/boot/Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_sharedcache`

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
-  __TEXT.__text: 0xce7258
+  __TEXT.__text: 0xcea4b8
   __TEXT.__lcxx_override: 0x34c
-  __TEXT.__cstring: 0x928a1
-  __TEXT.__const: 0x189c14
-  __TEXT.__swift5_typeref: 0x25a52
-  __TEXT.__swift5_reflstr: 0x3d8b8
+  __TEXT.__cstring: 0x92b91
+  __TEXT.__const: 0x189c74
+  __TEXT.__swift5_typeref: 0x25a62
+  __TEXT.__swift5_reflstr: 0x3d8c8
   __TEXT.__swift5_assocty: 0xce70
-  __TEXT.__swift5_fieldmd: 0x62d00
-  __TEXT.__constg_swiftt: 0x580f8
+  __TEXT.__swift5_fieldmd: 0x62d38
+  __TEXT.__constg_swiftt: 0x5816c
   __TEXT.__swift5_protos: 0xf68
   __TEXT.__swift5_proto: 0x9384
-  __TEXT.__swift5_types: 0x5b48
+  __TEXT.__swift5_types: 0x5b50
   __TEXT.__swift5_types2: 0x80
   __TEXT.__swift5_builtin: 0x2300
   __TEXT.__objc_methtype: 0x21f

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x130
-  __TEXT.__eh_frame: 0x6bdf8
+  __TEXT.__eh_frame: 0x6bf00
   __DATA.__TIGHTBEAM_VT: 0xfc0
   __DATA.__TIGHTBEAM: 0x3f0
-  __DATA.__data: 0x42230
-  __DATA.__const: 0x109e98
+  __DATA.__data: 0x42290
+  __DATA.__const: 0x109eb8
   __DATA.__mod_init_func: 0x48
   __DATA.__ENDPOINTS: 0x148c0
-  __DATA.__auth_ptr: 0x5528
+  __DATA.__auth_ptr: 0x5538
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x2a0
   __DATA.__MMIOREGS: 0x795

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x38
-  __DATA.__bss: 0x23420
-  __DATA.__common: 0x3c01
+  __DATA.__bss: 0x23440
+  __DATA.__common: 0x3bf1
   __PDATA.__data: 0x24e0
   __PDATA.__const: 0x5e38
   __PDATA.__ENDPOINTS: 0x838

   __PDATA.__common: 0x2520
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 50094
+  Functions: 50106
   Symbols:   1
-  CStrings:  13643
+  CStrings:  13665
 
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
+ "Sun Nov  8 22:43:51 PST 2026"
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
- "Mon Oct 12 02:39:47 PDT 2026"
- "getOrAllocateComponentResourceCapFromEdge(edge:)"
- "init(indirectTag:cap:identifier:compBadge:clientNotificationType:)"
```
