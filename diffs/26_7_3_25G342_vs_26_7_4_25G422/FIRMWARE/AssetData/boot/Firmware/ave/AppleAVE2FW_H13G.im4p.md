## AppleAVE2FW_H13G.im4p

> `AssetData/boot/Firmware/ave/AppleAVE2FW_H13G.im4p`

### Sections with Same Size but Changed Content

- `__DATA._rtk_patchbay`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA.__const`

```diff

-  __TEXT.__text: 0xdd354
+  __TEXT.__text: 0xdd6a4
   __TEXT.__const: 0x1d300
-  __TEXT.__cstring: 0x12b30
+  __TEXT.__cstring: 0x12cdb
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA._rtk_patchbay: 0x211

   __DATA.__zerofill: 0xc67c0
   Functions: 1033
   Symbols:   1424
-  CStrings:  2188
+  CStrings:  2196
 
Functions:
~ __ZN19CFlowControllerBase23ProcessCmd_Process_LRMEEv : 1520 -> 1648
~ __ZN19CFlowControllerBase23ProcessCmd_Process_MCTFEv : 1720 -> 1800
~ __ZN19CFlowControllerBase22ProcessCmd_Process_AVCEv : 1660 -> 1740
~ __ZN19CFlowControllerBase23ProcessCmd_Process_HEVCEv : 1864 -> 1944
~ __ZN19CFlowControllerBase18SendCommandToQueueEP20CAVECommonControllerjPvjjyyj : 1072 -> 1156
~ __Z15AVE_GetCurrTimev : 76 -> 80
~ sub_4d0c0 -> sub_4d288 : 336 -> 348
~ sub_4d210 -> sub_4d3e4 : 188 -> 192
~ sub_4d2cc -> sub_4d4a4 : 368 -> 380
~ __ZN14CAVCController16ProcessPipeStartEPv : 6092 -> 6192
~ __ZN14CAVCController14ConfigureMCPUsEP18AVE_PICMGMT_PARAMS : 9056 -> 9120
~ __ZN14CAVCController19GetSliceHeaderForFWEPhPjj : 848 -> 876
~ __ZN14CAVCController7setPipeEP18AVE_PICMGMT_PARAMS : 26592 -> 26692
~ __Z15AVE_PSInfo_MakePKh13_E_AVE_PSTypeiiP16_S_AVE_PSContext : 752 -> 824
CStrings:
+ "%s:%d %s | too many parameter sets %p %d %d %d %p %d"
+ "%s::%s ConfigureMCPUs failed (%d)"
+ "%s::%s GetSliceHeaderForFW rejected slice header (%d)"
+ "%s::%s slice header count (%d) out of range [0, %d]"
+ "%s::%s:%d  Failed to Queue AVE_Cmd_Process for client_id: %lld %lld"
+ "%s::%s:%d %s | setPipe failed (%d)"
+ "%s::%s:%d Failed to Queue AVE_Cmd_Process for client_id: %lld %lld"
+ "%s::%s:%d invalid layer id %d (max %d)"
+ "0 <= iNum && iNum < (1 + ((2) < ((63 + 1)) ? (2) : ((63 + 1))) * (1 + 9 ))"
+ "9003.79.0"
- "%s::%s getPPSHeaderForFW count (%d) > length (%d)"
- "9003.78.0"
```
