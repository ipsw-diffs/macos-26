## MTLCompiler

> `/System/Library/PrivateFrameworks/MTLCompiler.framework/Versions/32023/MTLCompiler`

```diff

-373.7.1.0.0
-  __TEXT.__text: 0xb3650
+373.7.2.0.0
+  __TEXT.__text: 0xb39d0
   __TEXT.__auth_stubs: 0x2280
-  __TEXT.__gcc_except_tab: 0x9b84
-  __TEXT.__const: 0xf98
-  __TEXT.__cstring: 0x843c
-  __TEXT.__oslogstring: 0x557
+  __TEXT.__gcc_except_tab: 0x9ba4
+  __TEXT.__const: 0xfa8
+  __TEXT.__cstring: 0x851d
+  __TEXT.__oslogstring: 0x5ad
   __TEXT.__unwind_info: 0x2f40
   __TEXT.__objc_classname: 0x1
   __TEXT.__objc_methname: 0x2b0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2231
-  Symbols:   3600
-  CStrings:  1449
+  Functions: 2233
+  Symbols:   3599
+  CStrings:  1456
 
Symbols:
+ GCC_except_table312
+ GCC_except_table318
+ GCC_except_table324
+ GCC_except_table328
+ GCC_except_table333
+ GCC_except_table342
+ GCC_except_table345
+ GCC_except_table347
+ GCC_except_table349
+ GCC_except_table358
+ GCC_except_table364
+ GCC_except_table366
+ GCC_except_table369
+ GCC_except_table381
+ GCC_except_table392
+ GCC_except_table415
+ GCC_except_table419
+ GCC_except_table428
+ GCC_except_table434
+ GCC_except_table446
+ GCC_except_table455
+ GCC_except_table462
+ GCC_except_table476
+ GCC_except_table478
+ GCC_except_table491
+ GCC_except_table493
+ GCC_except_table499
+ GCC_except_table505
+ __ZNSt3__16vectorIPcNS_9allocatorIS1_EEE9push_backB9nqe210106EOS1_
- GCC_except_table311
- GCC_except_table317
- GCC_except_table323
- GCC_except_table327
- GCC_except_table332
- GCC_except_table339
- GCC_except_table343
- GCC_except_table346
- GCC_except_table348
- GCC_except_table355
- GCC_except_table363
- GCC_except_table365
- GCC_except_table368
- GCC_except_table379
- GCC_except_table390
- GCC_except_table414
- GCC_except_table418
- GCC_except_table424
- GCC_except_table432
- GCC_except_table445
- GCC_except_table452
- GCC_except_table461
- GCC_except_table474
- GCC_except_table477
- GCC_except_table489
- GCC_except_table492
- GCC_except_table497
- GCC_except_table501
- GCC_except_table512
- GCC_except_table518
Functions:
~ __ZL22parseFunctionConstantsRN4llvm11LLVMContextEPKcmPj : 328 -> 360
~ __ZN17MTLCompilerObject20storeToBinaryArchiveEP29MTLBuildBinariesRequestHeadermRK20ReadModuleParametersRK24BackendCompilationOutput15MTLFunctionTypeR21FrameworkPassesOutputRKP20MTLOpaqueGPUArchiverPPc : 1808 -> 1964
~ __ZN17MTLCompilerObject13generateMachOEPKvmU13block_pointerFvjS1_mPKcE : 4788 -> 5376
+ __ZL22parseFunctionConstantsRN4llvm11LLVMContextEPKcmPj.cold.1
+ __ZN17MTLCompilerObject13generateMachOEPKvmU13block_pointerFvjS1_mPKcE.cold.1
CStrings:
+ "Failed to allocate MachO binary request entries"
+ "Failed to allocate function constants"
+ "Invalid pipeline archiver unit id"
+ "Invalid visible function request count"
+ "MachO entry %llu reflection block out of bounds"
+ "Unknown linked bitcode hash in MachO binary request"
+ "Visible function hashes do not match the tools list"
```
