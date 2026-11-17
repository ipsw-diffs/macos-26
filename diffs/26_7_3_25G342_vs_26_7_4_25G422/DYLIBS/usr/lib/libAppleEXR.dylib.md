## libAppleEXR.dylib

> `/usr/lib/libAppleEXR.dylib`

```diff

-3.4.1.0.0
-  __TEXT.__text: 0x9c410
+3.4.1.2.0
+  __TEXT.__text: 0x9c7c8
   __TEXT.__auth_stubs: 0x410
   __TEXT.__objc_methlist: 0x254
   __TEXT.__const: 0x2118c
-  __TEXT.__gcc_except_tab: 0x4e0
-  __TEXT.__cstring: 0x41b3
+  __TEXT.__gcc_except_tab: 0x4e4
+  __TEXT.__cstring: 0x4596
   __TEXT.__oslogstring: 0x3
   __TEXT.__unwind_info: 0x820
   __TEXT.__eh_frame: 0x130

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 730
-  Symbols:   942
-  CStrings:  503
+  Functions: 732
+  Symbols:   944
+  CStrings:  509
 
Symbols:
+ __ZN14AXRChunkHeader11GetMipLevelE11ChunkLayout
+ __ZN4Part11InitOffsetsEPKvmRmm11axr_flags_t
+ __ZNK4Part20CheckChunkPartNumberEPKvmmm11axr_flags_t
+ __ZZN4Part11InitOffsetsEPKvmRmm11axr_flags_tE13kRowSizeProcs
- __ZN4Part11InitOffsetsEPKvmRm11axr_flags_t
- __ZZN4Part11InitOffsetsEPKvmRm11axr_flags_tE13kRowSizeProcs
CStrings:
+ "%s error: expected rowBytes for channel size (%lu) x RGBA channel count (%lu) x width (%u) = %lu bytes\n\tThe provided destination row bytes is only %lu and the data will not fit.\n\tSkipping operation."
+ "EXR File corrupted: chunk appears in the offset table for part %lu, but reports it belongs to part %d"
+ "Interleave_Uncompressed: header runLength=%lu exceeds destination row capacity (%lu pixels for %lu rowBytes, %u channels x %zu bytes); clamping to prevent OOB write.\n"
+ "TileDecoder_PIZ::Interleave: header runLength=%u exceeds destination row capacity (%lu pixels for %lu rowBytes, %u channels x %zu bytes); clamping to prevent OOB write.\n"
+ "TileDecoder_PXR24::Interleave: header runLength=%u exceeds destination row capacity (%lu pixels for %lu rowBytes, %u channels x %zu bytes); clamping to prevent OOB write.\n"
+ "TileDecoder_ScanlineCompressed::Interleave: header runLength=%u exceeds destination row capacity (%lu pixels for %lu rowBytes, %u channels x %zu bytes); clamping to prevent OOB write.\n"
```
