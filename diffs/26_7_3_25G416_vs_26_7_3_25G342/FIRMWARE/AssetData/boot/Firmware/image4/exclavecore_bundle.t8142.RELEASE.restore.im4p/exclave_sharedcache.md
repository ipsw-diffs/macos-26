## exclave_sharedcache

> `AssetData/boot/Firmware/image4/exclavecore_bundle.t8142.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA.__auth_ptr`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__data`
- `__PDATA.__const`
- `__PDATA.__auth_ptr`

```diff

 1148.120.6.0.0
-  __TEXT.__text: 0x5d39ec
+  __TEXT.__text: 0x5d1840
   __TEXT.__lcxx_override: 0x34c
-  __TEXT.__cstring: 0x49b01
+  __TEXT.__cstring: 0x498e1
   __TEXT.__const: 0x112864
   __TEXT.__swift5_typeref: 0x11c20
   __TEXT.__swift5_reflstr: 0xf458

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0xa8
-  __TEXT.__eh_frame: 0x32698
+  __TEXT.__eh_frame: 0x32530
   __DATA.__TIGHTBEAM_VT: 0x600
   __DATA.__TIGHTBEAM: 0x190
   __DATA.__data: 0x13ac8

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x38
-  __DATA.__bss: 0xdc40
-  __DATA.__common: 0x67a
+  __DATA.__bss: 0xdc20
+  __DATA.__common: 0x68a
   __PDATA.__data: 0x24e0
   __PDATA.__const: 0x5e38
   __PDATA.__ENDPOINTS: 0x838

   __PDATA.__common: 0x2520
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 23409
+  Functions: 23397
   Symbols:   1
-  CStrings:  6785
+  CStrings:  6768
 
CStrings:
- "!ctx->used"
- "(addr - base) % slot_size == 0"
- "(map[idx / FREE_MAP_WORD_BITS] & bit) == 0"
- "Builtin.FixedArray of %zd elements with stride %zu is too large to be representable\n"
- "Tried to build a Builtin.FixedArray without metadata for the element type"
- "addr - base < populated_bytes"
- "addr >= base"
- "free_map_acquire"
- "free_map_release"
- "idx < populated_slots"
- "initialize_thread_context"
- "ipc_buffer_free_map != NULL"
- "release_thread_context"
- "slot_index"
- "thread_context_free_map != NULL"
- "type where a Builtin.FixedArray count is required"
- "unresolved Builtin.FixedArray element type"
```
