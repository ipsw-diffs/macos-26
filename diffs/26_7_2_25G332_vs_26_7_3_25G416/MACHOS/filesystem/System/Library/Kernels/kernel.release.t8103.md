## kernel.release.t8103

> `/System/Library/Kernels/kernel.release.t8103`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__PPLDATA_CONST.__const`
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`
- `__BOOTDATA.__static_ifinit`
- `__CTF.__ctf`

```diff

-12377.161.15.701.48
+12377.161.15.702.13
   __TEXT.__const: 0x37110
   __TEXT.__copyio_vectors: 0x150
-  __TEXT.__cstring: 0xa6582
-  __TEXT.__os_log: 0x3e2f7
+  __TEXT.__cstring: 0xa65be
+  __TEXT.__os_log: 0x3e3d6
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x6b0
   __DATA_CONST.__hib_const: 0x6f0

   __DATA_CONST.__mod_init_func: 0x2d8
   __DATA_CONST.__auth_ptr: 0x10
   __TEXT_EXEC.__hib_text: 0x3fb0
-  __TEXT_EXEC.__text: 0x96db84
+  __TEXT_EXEC.__text: 0x96e088
   __TEXT_EXEC.__commpage_text: 0x334
   __KLD.__text: 0xb020
-  __PPLTEXT.__text: 0x2d1e8
+  __PPLTEXT.__text: 0x2d23c
   __PPLDATA_CONST.__const: 0x190
   __LASTDATA_CONST.__mod_init_func: 0x8
   __LAST.__pinst: 0x8

   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4fb78
   __CTF.__ctf: 0xe79d8
-  Functions: 22682
+  Functions: 22683
   Symbols:   6896
-  CStrings:  25813
+  CStrings:  25818
 
CStrings:
+ "%s: IPv6 payload length %u < extension headers %d"
+ "%s: refcnt overflow of ptdp %p for pte %p @%s:%d"
+ "%s: rejecting AF_LINK gateway on index %u with unusable link address (nlen %u, alen %u, sdl_len %u)\n"
+ "%s: route %s on %s%d link address does not fit (sdl_alen %u, error %d)\n"
+ "rt_setgate"
+ "size <= sdl->sdl_alen"
- "sdl->sdl_alen == size"
```
