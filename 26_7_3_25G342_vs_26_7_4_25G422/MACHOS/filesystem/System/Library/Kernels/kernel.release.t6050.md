## kernel.release.t6050

> `/System/Library/Kernels/kernel.release.t6050`

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
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__DATA.__data`
- `__HIBDATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`
- `__BOOTDATA.__static_ifinit`

```diff

-12377.161.15.701.48
+12377.161.15.702.20
   __TEXT.__const: 0x37d60
   __TEXT.__copyio_vectors: 0x340
-  __TEXT.__cstring: 0xae541
-  __TEXT.__os_log: 0x3e511
+  __TEXT.__cstring: 0xae63b
+  __TEXT.__os_log: 0x3e5f0
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310
   __DATA_CONST.__sdt_cstring: 0x6f43

   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x54000
   __TEXT_EXEC.__hib_text: 0x17c8
-  __TEXT_EXEC.__text: 0x9ad9c4
+  __TEXT_EXEC.__text: 0x9ae6e8
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x5250
   __KLD.__text: 0xad68

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4fb78
-  __CTF.__ctf: 0xfc05c
-  Functions: 23231
+  __CTF.__ctf: 0xfc058
+  Functions: 23233
   Symbols:   6896
-  CStrings:  26306
+  CStrings:  26317
 
CStrings:
+ "%s n %p bad copy len %d @%s:%d"
+ "%s: IPv6 payload length %u < extension headers %d"
+ "%s: rejecting AF_LINK gateway on index %u with unusable link address (nlen %u, alen %u, sdl_len %u)\n"
+ "%s: route %s on %s%d link address does not fit (sdl_alen %u, error %d)\n"
+ "32-bit 4k commpage not supported for SPTM configurations @%s:%d"
+ "bytes_lost (%u) smaller than clamped length (%u)"
+ "clamp partial-below RACK segment [%u, %u) flags 0x%x to snd_una %u"
+ "mptcp_usr_sosend"
+ "rt_setgate"
+ "size <= sdl->sdl_alen"
+ "sosend"
+ "stale RACK segment [%u, %u) flags 0x%x at or below snd_una %u"
+ "tcp_rack_output"
- "32-bit 4k commpage not currently supported for SPTM configurations @%s:%d"
- "sdl->sdl_alen == size"
```
