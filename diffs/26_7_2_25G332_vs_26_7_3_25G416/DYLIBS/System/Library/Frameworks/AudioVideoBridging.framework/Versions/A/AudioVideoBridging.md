## AudioVideoBridging

> `/System/Library/Frameworks/AudioVideoBridging.framework/Versions/A/AudioVideoBridging`

```diff

-1440.7.0.0.0
-  __TEXT.__text: 0x1b1370
+1450.2.0.0.0
+  __TEXT.__text: 0x1b1e7c
   __TEXT.__auth_stubs: 0x980
-  __TEXT.__objc_methlist: 0x191c4
-  __TEXT.__const: 0x568
+  __TEXT.__objc_methlist: 0x191ec
+  __TEXT.__const: 0x578
   __TEXT.__gcc_except_tab: 0x1ae0
-  __TEXT.__cstring: 0x1ad4a
-  __TEXT.__oslogstring: 0x673f
+  __TEXT.__cstring: 0x1ada7
+  __TEXT.__oslogstring: 0x689e
   __TEXT.__ustring: 0x60
-  __TEXT.__unwind_info: 0x5910
+  __TEXT.__unwind_info: 0x5920
   __TEXT.__objc_classname: 0x445c
-  __TEXT.__objc_methname: 0x256e2
-  __TEXT.__objc_methtype: 0x327a
-  __TEXT.__objc_stubs: 0x14180
-  __DATA_CONST.__got: 0xf98
+  __TEXT.__objc_methname: 0x257c5
+  __TEXT.__objc_methtype: 0x3289
+  __TEXT.__objc_stubs: 0x14240
+  __DATA_CONST.__got: 0xfa0
   __DATA_CONST.__const: 0x13d8
   __DATA_CONST.__objc_classlist: 0x1000
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8348
+  __DATA_CONST.__objc_selrefs: 0x8380
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xdb8
   __DATA_CONST.__objc_arraydata: 0x50
   __AUTH_CONST.__auth_got: 0x4d8
   __AUTH_CONST.__const: 0x1600
-  __AUTH_CONST.__cfstring: 0x14ac0
+  __AUTH_CONST.__cfstring: 0x14ae0
   __AUTH_CONST.__objc_const: 0x269b0
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH.__objc_data: 0xa000
   __DATA.__objc_ivar: 0x1384
   __DATA.__data: 0x668
-  __DATA.__bss: 0x148
+  __DATA.__bss: 0x150
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9164
-  Symbols:   16309
-  CStrings:  10356
+  Functions: 9171
+  Symbols:   16321
+  CStrings:  10369
 
Symbols:
+ +[AVB17221AEMMemoryObjectURL setURLBackedMemoryObjectsAllowed:]
+ +[AVB17221AEMMemoryObjectURL urlBackedMemoryObjectsAllowed]
+ +[AVBVirtualAudioConfiguration entityModelByResolvingMemoryObjectDataURLs:error:]
+ _NSURLIsRegularFileKey
+ __OBJC_$_CLASS_METHODS_AVB17221AEMMemoryObjectURL
+ _objc_msgSend$arrayWithCapacity:
+ _objc_msgSend$dictionaryWithDictionary:
+ _objc_msgSend$entityModelByResolvingMemoryObjectDataURLs:error:
+ _objc_msgSend$getResourceValue:forKey:error:
+ _objc_msgSend$initWithContentsOfURL:options:error:
+ _objc_msgSend$urlBackedMemoryObjectsAllowed
+ _sAVB17221AEMURLBackedMemoryObjectsAllowed
CStrings:
+ "@32@0:8@16^@24"
+ "Could not read the data_url of a memory object, %{private}@: %{public}@"
+ "Not resolving the data_url of a memory object: %{private}@ is not a plain file"
+ "Not resolving the data_url of a memory object: only local file URLs are supported, not %{private}@"
+ "Not resolving the data_url of a memory object: this process does not allow URL backed memory objects"
+ "The contents of %@ could not be read for a memory object of the custom virtual entity model."
+ "arrayWithCapacity:"
+ "dictionaryWithDictionary:"
+ "entityModelByResolvingMemoryObjectDataURLs:error:"
+ "getResourceValue:forKey:error:"
+ "initWithContentsOfURL:options:error:"
+ "setURLBackedMemoryObjectsAllowed:"
+ "urlBackedMemoryObjectsAllowed"
```
