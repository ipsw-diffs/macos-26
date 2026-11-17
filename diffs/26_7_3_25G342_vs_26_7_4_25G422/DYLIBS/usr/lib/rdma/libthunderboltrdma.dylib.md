## libthunderboltrdma.dylib

> `/usr/lib/rdma/libthunderboltrdma.dylib`

```diff

-40.120.7.0.0
-  __TEXT.__text: 0x3764
+40.120.7.701.1
+  __TEXT.__text: 0x3aa0
   __TEXT.__auth_stubs: 0x210
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x20
-  __TEXT.__oslogstring: 0xa3f
+  __TEXT.__oslogstring: 0xaf9
   __TEXT.__cstring: 0x3f
   __TEXT.__unwind_info: 0xc8
   __DATA_CONST.__got: 0x8

   __AUTH_CONST.__const: 0x2a8
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/rdma/libibverbs.dylib
-  Functions: 91
+  Functions: 94
   Symbols:   87
-  CStrings:  70
+  CStrings:  73
 
Symbols:
+ _tbt_qp_handle_kernel_initiated_error
- _OUTLINED_FUNCTION_14
CStrings:
+ "Destroy QP failed with return %d"
+ "Failed to handle kernel intervention during QP destroy with code %d"
+ "Failed to transition to error for QP[%u]"
+ "QP[%u] kernel-initiated error detected, transitioning to ERROR"
- "Destroy QP failed\n"
```
