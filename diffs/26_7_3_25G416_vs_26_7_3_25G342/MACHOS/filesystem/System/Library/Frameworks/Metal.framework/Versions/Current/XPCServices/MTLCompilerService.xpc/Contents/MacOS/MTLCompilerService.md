## MTLCompilerService

> `/System/Library/Frameworks/Metal.framework/Versions/Current/XPCServices/MTLCompilerService.xpc/Contents/MacOS/MTLCompilerService`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-373.7.2.0.0
-  __TEXT.__text: 0x5c50
-  __TEXT.__auth_stubs: 0x6e0
+373.7.1.0.0
+  __TEXT.__text: 0x47d8
+  __TEXT.__auth_stubs: 0x6d0
   __TEXT.__gcc_except_tab: 0x2c4
   __TEXT.__const: 0xa0
-  __TEXT.__cstring: 0x9e4
-  __TEXT.__oslogstring: 0x501
+  __TEXT.__cstring: 0x56a
+  __TEXT.__oslogstring: 0x503
   __TEXT.__objc_classname: 0x1
   __TEXT.__unwind_info: 0x2a8
-  __DATA_CONST.__auth_got: 0x378
+  __DATA_CONST.__auth_got: 0x370
   __DATA_CONST.__got: 0xb8
   __DATA_CONST.__const: 0x1b8
   __DATA_CONST.__cfstring: 0x20

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 170
-  Symbols:   323
-  CStrings:  136
+  Functions: 138
+  Symbols:   317
+  CStrings:  83
 
Symbols:
+ GCC_except_table38
+ GCC_except_table46
+ GCC_except_table51
+ GCC_except_table52
+ GCC_except_table59
+ GCC_except_table60
- GCC_except_table40
- GCC_except_table50
- GCC_except_table53
- GCC_except_table56
- GCC_except_table61
- GCC_except_table62
- _OUTLINED_FUNCTION_10
- _OUTLINED_FUNCTION_11
- _OUTLINED_FUNCTION_9
- __ZL13MTLBlobRejectPKc
- __ZNK18MTLRequestBlobView12checkCStringEyy
- _memchr
CStrings:
+ "Invalid request data size"
+ "Request data size insufficient for operation"
- "Invalid request data"
- "Request blob validation failed: %{public}s"
- "airScript"
- "archiveID"
- "archiveID header does not fit requestSize"
- "archiveID.archiverBasePath"
- "archiverBasePath"
- "binaryArchiveID"
- "binaryRequest.bitCode"
- "binaryRequest.functionName"
- "binaryRequest.pluginData"
- "buildBinaries header does not fit requestSize"
- "buildLibraryFromSource header does not fit requestSize"
- "cispi header does not fit requestSize"
- "cispi.funcInfo"
- "cispi.funcInfo.arguments"
- "cispi.funcInfo.moduleIndex"
- "cispi.funcNames"
- "cispi.module.bitCode"
- "cispi.moduleInfo"
- "dylibInstallName"
- "entries array exceeds requestSize"
- "entry.airScript"
- "entry.binary"
- "entry.bitCode"
- "entry.bitcodeHashList"
- "entry.hashes"
- "entry.reflectionBlock"
- "entry.tools"
- "gpuCompilerSPIOptions"
- "hashes"
- "header does not fit requestSize"
- "libFromSource.align overflow"
- "libFromSource.linkedAir"
- "libFromSource.linkedAir blobSize"
- "libFromSource.linkedAir size prefix"
- "libFromSource.options"
- "libFromSource.options cstring"
- "libFromSource.source"
- "libFromSource.source cstring"
- "libFromSource.unaligned blob"
- "linkData"
- "mtlScript"
- "overrideTriple"
- "pipelineArchUnitId"
- "pipelineData"
- "pipelineList"
- "privateVisibleFunctionRequests"
- "requestData"
- "sandboxExt"
- "specializedName"
- "tools"
- "uniqueBitcodeList"
- "visibleFunctionGroup"
- "visibleFunctionRequests"
```
