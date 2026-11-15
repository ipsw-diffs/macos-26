## libcompression.dylib

> `/usr/lib/libcompression.dylib`

```diff

-193.120.2.700.1
-  __TEXT.__text: 0x5c598
+193.120.2.702.2
+  __TEXT.__text: 0x5c65c
   __TEXT.__auth_stubs: 0x300
   __TEXT.__const: 0x76961
-  __TEXT.__cstring: 0x2ec
+  __TEXT.__cstring: 0x2f9
   __TEXT.__unwind_info: 0x6a8
   __TEXT.__eh_frame: 0x448
   __DATA_CONST.__got: 0x10

   - /usr/lib/liblzma.5.dylib
   Functions: 528
   Symbols:   690
-  CStrings:  49
+  CStrings:  50
 
Functions:
~ _lzfseDecode : 2700 -> 2736
~ _lzvn_decode_scratch_size : 12 -> 40
~ _ProcessCommands : 2468 -> 2548
~ _SafeProcessCommands : 2812 -> 2792
~ _SafeDecodeCommandBlockSwitch : 792 -> 804
~ _DecodeCommandBlockSwitch : 432 -> 444
~ _SafeDecodeLiteralBlockSwitch : 868 -> 880
~ _DecodeLiteralBlockSwitch : 500 -> 512
~ _SafeDecodeDistanceBlockSwitch : 812 -> 824
~ _DecodeDistanceBlockSwitch : 452 -> 464
CStrings:
+ "BLOCK_SWITCH"
```
