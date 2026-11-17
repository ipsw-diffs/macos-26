## AppleAVE2FW_H13D.im4p

> `AssetData/boot/Firmware/ave/AppleAVE2FW_H13D.im4p`

### Sections with Same Size but Changed Content

- `__DATA._rtk_patchbay`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA.__const`

```diff

-  __TEXT.__text: 0xfd710
+  __TEXT.__text: 0xfdae0
   __TEXT.__const: 0x21130
-  __TEXT.__cstring: 0x14587
+  __TEXT.__cstring: 0x14732
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA._rtk_patchbay: 0x211

   __DATA.__zerofill: 0xd2680
   Functions: 1110
   Symbols:   1558
-  CStrings:  2385
+  CStrings:  2393
 
Functions:
~ __ZN19CFlowControllerBase23ProcessCmd_Process_LRMEEv : 1528 -> 1652
~ __ZN19CFlowControllerBase23ProcessCmd_Process_MCTFEv : 1744 -> 1824
~ __ZN19CFlowControllerBase22ProcessCmd_Process_AVCEv : 1680 -> 1760
~ __ZN19CFlowControllerBase23ProcessCmd_Process_HEVCEv : 1888 -> 1968
~ __ZN19CFlowControllerBase18SendCommandToQueueEP20CAVECommonControllerjPvjjyyj : 1488 -> 1672
~ __Z15AVE_GetCurrTimev : 76 -> 80
~ sub_55734 -> sub_5595c : 336 -> 348
~ sub_55884 -> sub_55ab8 : 188 -> 192
~ sub_55940 -> sub_55b78 : 368 -> 380
~ __ZN14CAVCController16ProcessPipeStartEPv : 6100 -> 6200
~ __ZN14CAVCController14ConfigureMCPUsEP18AVE_PICMGMT_PARAMS : 9220 -> 9272
~ __ZN14CAVCController19GetSliceHeaderForFWEPhPjj : 848 -> 876
~ __ZN14CAVCController7setPipeEP18AVE_PICMGMT_PARAMS : 27968 -> 28112
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
