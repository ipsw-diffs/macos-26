## com.apple.driver.AppleUSBLightningAdapter

> `com.apple.driver.AppleUSBLightningAdapter`

```diff

-85.0.0.701.1
+85.0.0.702.1
   __TEXT.__const: 0x8
   __TEXT.__cstring: 0x135b
-  __TEXT.__os_log: 0xdbe
-  __TEXT_EXEC.__text: 0x60d0
+  __TEXT.__os_log: 0xdf3
+  __TEXT_EXEC.__text: 0x60dc
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xc4
   __DATA.__common: 0x60

   __DATA_CONST.__kalloc_type: 0x80
   Functions: 107
   Symbols:   493
-  CStrings:  180
+  CStrings:  181
 
Functions:
~ __ZN27AppleUSBLightningAdapterBOS18_getCapabilityDataEPKN11StandardUSB13BOSDescriptorE : 504 -> 500
~ sub_A074 -> sub_fffffe0009b26b14 : 40 -> 56
CStrings:
+ "Invalid platform descriptor length for MikeyBus info! (bLength: %u, expectedDescriptorLength: %u)"
+ "Invalid platform descriptor length! (bLength: %u, expectedDescriptorBaseLength: %u)"
- "Invalid platform descriptor length!"
```
