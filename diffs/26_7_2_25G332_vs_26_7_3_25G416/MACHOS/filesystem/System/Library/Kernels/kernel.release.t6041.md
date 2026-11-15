## kernel.release.t6041

> `/System/Library/Kernels/kernel.release.t6041`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__const`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`

```diff

-12377.161.15.701.48
+12377.161.15.702.13
   __TEXT.__const: 0x36ea0
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0xa22ee
-  __TEXT.__os_log: 0x3e351
+  __TEXT.__cstring: 0xa22ef
+  __TEXT.__os_log: 0x3e430
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310
   __DATA_CONST.__sdt_cstring: 0x6f17

   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x54000
   __TEXT_EXEC.__hib_text: 0x17e8
-  __TEXT_EXEC.__text: 0x969d44
+  __TEXT_EXEC.__text: 0x96a24c
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x5330
   __KLD.__text: 0xaf48

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4fb78
-  __CTF.__ctf: 0xe8533
-  Functions: 22529
+  __CTF.__ctf: 0xe8513
+  Functions: 22530
   Symbols:   6896
-  CStrings:  25590
+  CStrings:  25594
 
CStrings:
+ "%s: IPv6 payload length %u < extension headers %d"
+ "%s: rejecting AF_LINK gateway on index %u with unusable link address (nlen %u, alen %u, sdl_len %u)\n"
+ "%s: route %s on %s%d link address does not fit (sdl_alen %u, error %d)\n"
+ "32-bit 4k commpage not supported for SPTM configurations @%s:%d"
+ "rt_setgate"
+ "size <= sdl->sdl_alen"
- "32-bit 4k commpage not currently supported for SPTM configurations @%s:%d"
- "sdl->sdl_alen == size"
```
