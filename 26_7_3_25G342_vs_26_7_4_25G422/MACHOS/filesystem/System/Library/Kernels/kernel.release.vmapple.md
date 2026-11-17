## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__LASTDATA_CONST.__mod_init_func`
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`
- `__BOOTDATA.__static_ifinit`

```diff

-12377.161.15.701.48
+12377.161.15.702.20
   __TEXT.__const: 0x369c0
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0x99768
-  __TEXT.__os_log: 0x3df3e
+  __TEXT.__cstring: 0x9989d
+  __TEXT.__os_log: 0x3e01d
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x6b0
   __DATA_CONST.__hib_const: 0x120

   __DATA_CONST.__mod_init_func: 0x2d0
   __DATA_CONST.__auth_ptr: 0x10
   __TEXT_EXEC.__hib_text: 0xed8
-  __TEXT_EXEC.__text: 0x947c70
+  __TEXT_EXEC.__text: 0x948920
   __TEXT_EXEC.__commpage_text: 0x334
   __KLD.__text: 0xb020
   __LASTDATA_CONST.__mod_init_func: 0x8

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4f6cb
-  __CTF.__ctf: 0xecf47
-  Functions: 21788
+  __CTF.__ctf: 0xecf3e
+  Functions: 21790
   Symbols:   6874
-  CStrings:  24701
+  CStrings:  24713
 
CStrings:
+ "%s n %p bad copy len %d @%s:%d"
+ "%s: IPv6 payload length %u < extension headers %d"
+ "%s: refcnt overflow of ptdp %p for pte %p @%s:%d"
+ "%s: rejecting AF_LINK gateway on index %u with unusable link address (nlen %u, alen %u, sdl_len %u)\n"
+ "%s: route %s on %s%d link address does not fit (sdl_alen %u, error %d)\n"
+ "bytes_lost (%u) smaller than clamped length (%u)"
+ "clamp partial-below RACK segment [%u, %u) flags 0x%x to snd_una %u"
+ "mptcp_usr_sosend"
+ "rt_setgate"
+ "size <= sdl->sdl_alen"
+ "sosend"
+ "stale RACK segment [%u, %u) flags 0x%x at or below snd_una %u"
+ "tcp_rack_output"
- "sdl->sdl_alen == size"
```
