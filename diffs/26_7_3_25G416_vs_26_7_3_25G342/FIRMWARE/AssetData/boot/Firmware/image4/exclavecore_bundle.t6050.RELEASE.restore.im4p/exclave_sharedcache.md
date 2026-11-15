## exclave_sharedcache

> `AssetData/boot/Firmware/image4/exclavecore_bundle.t6050.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA.__auth_ptr`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__data`
- `__PDATA.__const`
- `__PDATA.__shared_cache`
- `__PDATA.__auth_ptr`

```diff

 1148.120.6.0.0
-  __TEXT.__text: 0x54c884
+  __TEXT.__text: 0x54a6d8
   __TEXT.__lcxx_override: 0x34c
-  __TEXT.__cstring: 0x445f1
+  __TEXT.__cstring: 0x443c1
   __TEXT.__const: 0x10a474
   __TEXT.__swift5_typeref: 0xf4da
   __TEXT.__swift5_reflstr: 0xb488

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0xa8
-  __TEXT.__eh_frame: 0x2df34
+  __TEXT.__eh_frame: 0x2ddcc
   __DATA.__TIGHTBEAM_VT: 0x540
   __DATA.__TIGHTBEAM: 0x168
   __DATA.__data: 0xff08

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x38
-  __DATA.__bss: 0xd270
-  __DATA.__common: 0x5ba
+  __DATA.__bss: 0xd250
+  __DATA.__common: 0x5ca
   __PDATA.__data: 0x24e0
   __PDATA.__const: 0x5e38
   __PDATA.__ENDPOINTS: 0x838

   __PDATA.__common: 0x2520
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 21445
+  Functions: 21433
   Symbols:   1
-  CStrings:  6302
+  CStrings:  6285
 
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
