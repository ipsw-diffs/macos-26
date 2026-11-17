## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO`

```diff

-2784.102.3.0.0
-  __TEXT.__text: 0x28c4b4
+2784.102.5.0.0
+  __TEXT.__text: 0x28cdec
   __TEXT.__auth_stubs: 0x4ab0
   __TEXT.__objc_methlist: 0xd58
   __TEXT.__const: 0x11b28
-  __TEXT.__gcc_except_tab: 0x1bbcc
-  __TEXT.__cstring: 0x6dddf
+  __TEXT.__gcc_except_tab: 0x1bbfc
+  __TEXT.__cstring: 0x6e216
   __TEXT.__oslogstring: 0x17
   __TEXT.__ustring: 0x30
-  __TEXT.__unwind_info: 0xae38
+  __TEXT.__unwind_info: 0xae40
   __TEXT.__eh_frame: 0x130
   __TEXT.__objc_classname: 0xf1
   __TEXT.__objc_methname: 0x2cd6

   - /usr/lib/libexpat.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 10214
-  Symbols:   19898
-  CStrings:  14810
+  Functions: 10225
+  Symbols:   19903
+  CStrings:  14830
 
Symbols:
+ __ZN12OFDContainer20adoptNestedContainerEPS_
+ __ZN12OFDContainerC1EPK8__CFData
+ __ZN12OFDContainerC2EPK8__CFData
+ __ZN13EXRReadPluginD2Ev
+ __ZNSt3__119__allocate_at_leastB9fqe210106INS_9allocatorIP12OFDContainerEEEENS_19__allocation_resultINS_16allocator_traitsIT_E7pointerEEERS7_m
+ __ZNSt3__16vectorIP12OFDContainerNS_9allocatorIS2_EEE20__throw_length_errorB9fqe210106Ev
+ _unzClose
- __ZN12OFDContainerC1EPhj
- __ZN12OFDContainerC2EPhj
CStrings:
+ "*** BMP - writePrefix failed, not writing pixel data\n"
+ "*** ERROR: PHOTOMETRIC_PALETTE with samplesPerPixel %d at %d bpc is not supported\n"
+ "*** ERROR: PHOTOMETRIC_SEPARATED requires 8 or 16 bpc -- got %d\n"
+ "*** ERROR: PixarLog codec not available for compression %d\n"
+ "*** ERROR: failed to allocte temp (%zu bytes)\n"
+ "*** ERROR: failed to read %u bytes of pixel data for 420f\n"
+ "*** ERROR: invalid JP2: PaletteBox %d color components\n"
+ "*** ERROR: invalid JP2: PaletteBox %d entries\n"
+ "*** ERROR: invalid JP2: PaletteBox component %u unsupported bit depth %u\n"
+ "*** can't write KTX - failed to read %zu bytes of pixel data\n"
+ "*** can't write KTX - unsupported image size (%u x %u, rowBytes %zu)\n"
+ "*** can't write KTX2 - bad image size (%zu x %zu)\n"
+ "*** can't write KTX2 - failed to read %zu bytes of pixel data\n"
+ "*** decode buffer is too small for the SDR conversion\n"
+ "*** failed to read %zu bytes of pixel data\n"
+ "ico image %zu: %zu bytes is too small for a BITMAPINFOHEADER\n"
+ "ico image %zu: header %u + pixels %zu + mask %zu exceeds %zu bytes\n"
+ "iio_xpc_plugin_data_exr_channel"
+ "iio_xpc_plugin_data_exr_image"
+ "iio_xpc_plugin_data_exr_view"
+ "write420fData"
- "*** ERROR: failed to allocte temp (%d bytes)\n"
```
