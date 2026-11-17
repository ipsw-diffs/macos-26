## libusd_ms.dylib

> `/usr/lib/usd/libusd_ms.dylib`

```diff

-23.5.6.0.0
-  __TEXT.__text: 0x1536434
+23.5.7.0.0
+  __TEXT.__text: 0x153ebbc
   __TEXT.__auth_stubs: 0xc1c0
-  __TEXT.__gcc_except_tab: 0x172424
-  __TEXT.__const: 0x360bf0
-  __TEXT.__cstring: 0x29079c
+  __TEXT.__gcc_except_tab: 0x172dd4
+  __TEXT.__const: 0x361210
+  __TEXT.__cstring: 0x29185c
   __TEXT.__oslogstring: 0x1fc
   __TEXT.__constg_swiftt: 0x5d3c
   __TEXT.__swift5_typeref: 0x38ce

   __TEXT.__swift5_builtin: 0x3160
   __TEXT.__swift5_proto: 0x177c
   __TEXT.__swift5_protos: 0x78
-  __TEXT.__unwind_info: 0x98588
+  __TEXT.__unwind_info: 0x987d8
   __TEXT.__eh_frame: 0x26040
   __TEXT.__objc_classname: 0x1
   __TEXT.__objc_methname: 0x1bca

   __DATA_CONST.__objc_selrefs: 0x8c8
   __DATA_CONST.__objc_arraydata: 0x10
   __AUTH_CONST.__auth_got: 0x60f8
-  __AUTH_CONST.__const: 0xb2528
+  __AUTH_CONST.__const: 0xb27a8
   __AUTH_CONST.__cfstring: 0x620
   __AUTH_CONST.__objc_const: 0x50
   __AUTH_CONST.__objc_intobj: 0x228

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_errno.dylib
-  Functions: 109125
+  Functions: 109197
   Symbols:   40694
-  CStrings:  30248
+  CStrings:  30302
 
CStrings:
+ " declares more entries than the element line contains."
+ " was read."
+ " were read."
+ "21:47:37)"
+ "Accessor %d references out-of-range bufferView %d (%zu bufferViews); treating the accessor as empty"
+ "Accessor %d's bufferView %d references out-of-range buffer %d (%zu buffers); treating the accessor as empty"
+ "Accessor count %zu cannot be satisfied by the backing buffer (%zu bytes remaining, %zu bytes per element)"
+ "Accessor count %zu exceeds what its buffer view can hold (%zu elements); treating the accessor as empty"
+ "Accessor offset out of bounds: bufferView.byteOffset=%zu, accessor.byteOffset=%zu, buffer.size=%zu"
+ "Animation sampler accessor count out of range for channel '%s'"
+ "Animation target node %d was not imported; skipping channel"
+ "Blend shape packed offset table size overflows; rejecting inconsistent blend shape data."
+ "Blend shape point indices imply %zu points, which exceeds the supported maximum (%zu); rejecting blend shape data."
+ "Cannot open image \"%s\" for reading, invalid or too large dimensions %lld x %lld"
+ "Cannot resample OpenEXR image \"%s\" from %d x %d with %d channels to %d x %d with %d channels"
+ "Corrupt OpenEXR image \"%s\": %d x %d output does not fit the pixel data decoded from a %d x %d image"
+ "Corrupt OpenEXR image \"%s\": %lld byte read exceeds the %zu byte decoded image"
+ "Corrupt OpenEXR image \"%s\": %zu bytes of pixel data do not fit the %zu byte buffer sized from the header"
+ "Corrupt OpenEXR image \"%s\": decoded %d x %d with %d channels of type %d does not match the header's %d x %d with %d channels of type %d"
+ "Corrupt OpenEXR image \"%s\": resampled %d x %d output does not fit its own buffer"
+ "Corrupt or unsupported OpenEXR image \"%s\": %d x %d with %d channels cannot be read into %d x %d with %d channels"
+ "Corrupt or unsupported OpenEXR image \"%s\": cannot resize to %d x %d with %d channels"
+ "Destination buffer too small (%zu bytes) for %zu elements of %zu bytes"
+ "Destination component count %zu out of range"
+ "External file access denied : "
+ "Integer overflow in accessor source size calculation (count=%zu, stride=%zu, elementSize=%zu)"
+ "Invalid accessor byte stride (%d); bufferView.byteStride=%zu is not a multiple of the accessor component size or the accessor type is invalid"
+ "Invalid accessor element layout: componentSize=%zu, componentCount=%zu"
+ "Invalid ptex header (data type, channels or face count): "
+ "JOINTS_%d/WEIGHTS_%d accessor count out of range for mesh '%s'"
+ "Joint node %d was not imported (USD node index %d)"
+ "Nov 10 2026"
+ "PLY parser: ASCII element line ended before property "
+ "PLY parser: ASCII element line ended before the list count for property "
+ "PLY parser: ASCII list property "
+ "PLY parser: binary file ended inside list property "
+ "PLY parser: binary file ended while reading the list count for property "
+ "PLY parser: file ended before all entries of element "
+ "PtexReader error: constant data too large, file corrupt"
+ "PtexReader error: face count too large, file corrupt"
+ "PtexReader error: invalid face resolution, file corrupt"
+ "PtexReader error: invalid level 0 face count, file corrupt"
+ "PtexReader error: invalid tile resolution, file corrupt"
+ "PtexReader error: level face count too large, file corrupt"
+ "Writing files is not supported\n"
+ "_ValidateDecodedImage"
+ "auto adobe::usd::importNodes(ImportGltfContext &)::(anonymous class)::operator()(int, int) const"
+ "bool adobe::usd::importChannel(const tinygltf::Model &, const tinygltf::AnimationChannel &, const tinygltf::AnimationSampler &, const std::string &, TimeValues<T> &, float &, float &) [T = pxrInternal__aapl__pxrReserved__::GfQuatf]"
+ "bool adobe::usd::importChannel(const tinygltf::Model &, const tinygltf::AnimationChannel &, const tinygltf::AnimationSampler &, const std::string &, TimeValues<T> &, float &, float &) [T = pxrInternal__aapl__pxrReserved__::GfVec3f]"
+ "bool pxrInternal__aapl__pxrReserved__::(anonymous namespace)::_ComputeRangesFromCounts(const TfSpan<const unsigned int> &, TfSpan<GfVec2i>, unsigned int *)"
+ "bool pxrInternal__aapl__pxrReserved__::(anonymous namespace)::_ValidateDecodedImage(const nanoexr_ImageData_t &, int, int, int, exr_pixel_type_t, const std::string &)"
+ "getAccessorElementCount"
+ "glTF node %d is referenced more than once; ignoring extra reference"
+ "glTF node hierarchy deeper than %d levels; ignoring node %d"
+ "importChannel"
+ "invalid quadrangulation info [%s]"
+ "quadrangulated point count overflows [%s]"
+ "size_t adobe::usd::getAccessorElementCount(const tinygltf::Model &, int)"
+ "virtual bool pxrInternal__aapl__pxrReserved__::Hio_OpenEXRImage::ReadCropped(const int, const int, const int, const int, const StorageSpec &)"
- "02:17:59)"
- "Destination buffer too small"
- "Invalid USD node index %d (max %zu)"
- "Oct 12 2026"
- "unsigned int pxrInternal__aapl__pxrReserved__::(anonymous namespace)::_ComputeRangesFromCounts(const TfSpan<const unsigned int> &, TfSpan<GfVec2i>)"
```
