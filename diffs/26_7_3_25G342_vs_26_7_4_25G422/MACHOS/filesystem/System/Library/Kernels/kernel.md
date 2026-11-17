## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__got`
- `__KLDDATA.__init`
- `__KLDDATA.__init_entry_set`
- `__KLDDATA.__const`
- `__KLDDATA.__static_ifinit`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__LASTDATA_CONST.__mod_init_func`

```diff

-12377.161.15.701.48
-  __TEXT.__text: 0x8d1190
+12377.161.15.702.20
+  __TEXT.__text: 0x8d1f10
   __TEXT.__const: 0x44db0
-  __TEXT.__os_log: 0x47f7b
-  __TEXT.__cstring: 0x9f14b
+  __TEXT.__os_log: 0x4807b
+  __TEXT.__cstring: 0x9f24b
   __TEXT.__eh_frame: 0x118
   __DATA.__lock_grp: 0x15f10
   __DATA.__data: 0x83520
   __DATA.__percpu: 0x3de8
-  __DATA.__common: 0x1bcda0
+  __DATA.__common: 0x1bcd90
   __DATA.__bss: 0x7e8e0
   __DATA_CONST.__const: 0xa1078
   __DATA_CONST.__kalloc_type: 0x17180

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4d6d4
-  __CTF.__ctf: 0xddda8
-  Functions: 26472
-  Symbols:   23795
-  CStrings:  25571
+  __CTF.__ctf: 0xddda6
+  Functions: 26476
+  Symbols:   23796
+  CStrings:  25582
 
Symbols:
+ _rt_gateway_lladdr_copyout
CStrings:
+ "%s n %p bad copy len %d @%s:%d"
+ "%s: IPv6 payload length %u < extension headers %d"
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
