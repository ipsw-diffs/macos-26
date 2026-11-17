## com.apple.filesystems.udf

> `com.apple.filesystems.udf`

```diff

-324.160.3.701.4
+324.160.3.702.8
   __TEXT.__const: 0x1b08
-  __TEXT.__cstring: 0x308d
-  __TEXT_EXEC.__text: 0x2f6e0
+  __TEXT.__cstring: 0x3315
+  __TEXT_EXEC.__text: 0x2fa24
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x4f8
   __DATA.__common: 0x4d8

   __DATA_CONST.__const: 0x1140
   __DATA_CONST.__kalloc_type: 0x80
   __DATA_CONST.__kalloc_var: 0xa0
-  Functions: 860
+  Functions: 859
   Symbols:   1176
-  CStrings:  349
+  CStrings:  361
 
Symbols:
+ __ZN15UDFDeviceBufferC2EP8UDFMountj
+ __ZN18UDFDeviceBufferLRUC1EP8UDFMountj
+ __ZN18UDFDeviceBufferLRUC2EP8UDFMountj
- __ZN15UDFDeviceBufferC2EP8UDFMountm
- __ZN18UDFDeviceBufferLRUC1EP8UDFMountm
- __ZN18UDFDeviceBufferLRUC2EP8UDFMountm
CStrings:
+ "Device buffer hash too large: %zu entries"
+ "Device buffer too large: %u packets of %zu bytes"
+ "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
+ "File times EA backup time offset %lld out of bounds, ignoring"
+ "File times EA creation time offset %lld out of bounds, ignoring"
+ "File times EA length %lld too short for %u timestamp(s), ignoring"
+ "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
+ "Sparing table size %u cannot hold %u entries"
+ "The VAT has too many entries"
+ "The VAT information length exceeds the VAT stream length"
+ "The VAT is too small to hold its tail"
+ "The lengthOfHeader in VAT ICB exceeds the VAT length"
+ "embedded data end exceeds sector size"
+ "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
- "\"non-memory resident sparing table is not implemented yet\" @%s:%d"
- "UDFPartition.cpp"
```
