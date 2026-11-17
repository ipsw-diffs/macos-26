## AppleAVE2FW_H14C.im4p

> `AssetData/boot/Firmware/ave/AppleAVE2FW_H14C.im4p`

### Sections with Same Size but Changed Content

- `__DATA._rtk_patchbay`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA.__const`

```diff

-  __TEXT.__text: 0xfd5ac
+  __TEXT.__text: 0xfd99c
   __TEXT.__const: 0x21500
-  __TEXT.__cstring: 0x1451c
+  __TEXT.__cstring: 0x146c7
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA._rtk_patchbay: 0x211

   __DATA.__zerofill: 0xd2680
   Functions: 1117
   Symbols:   1560
-  CStrings:  2384
+  CStrings:  2392
 
Functions:
~ __ZN19CFlowControllerBase23ProcessCmd_Process_LRMEEv : 1528 -> 1652
~ __ZN19CFlowControllerBase23ProcessCmd_Process_MCTFEv : 1744 -> 1824
~ __ZN19CFlowControllerBase22ProcessCmd_Process_AVCEv : 1680 -> 1760
~ __ZN19CFlowControllerBase23ProcessCmd_Process_HEVCEv : 1888 -> 1968
~ __ZN19CFlowControllerBase18SendCommandToQueueEP20CAVECommonControllerjPvjjyyj : 1488 -> 1672
~ __Z15AVE_GetCurrTimev : 76 -> 80
~ sub_54fe0 -> sub_55208 : 336 -> 348
~ sub_55130 -> sub_55364 : 188 -> 192
~ sub_551ec -> sub_55424 : 368 -> 380
~ __ZN14CAVCController16ProcessPipeStartEPv : 6100 -> 6200
~ __ZN14CAVCController14ConfigureMCPUsEP18AVE_PICMGMT_PARAMS : 9236 -> 9288
~ __ZN14CAVCController19GetSliceHeaderForFWEPhPjj : 848 -> 876
~ __ZN14CAVCController7setPipeEP18AVE_PICMGMT_PARAMS : 29000 -> 29172
~ __Z15AVE_PSInfo_MakePKh13_E_AVE_PSTypeiiP16_S_AVE_PSContext : 752 -> 824
~ __ZN7AVE_FPS3AddEPK11_S_AVE_Time : 780 -> 784
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
