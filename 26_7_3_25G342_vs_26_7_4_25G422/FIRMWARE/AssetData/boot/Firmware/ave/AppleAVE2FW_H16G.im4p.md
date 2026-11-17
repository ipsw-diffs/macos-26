## AppleAVE2FW_H16G.im4p

> `AssetData/boot/Firmware/ave/AppleAVE2FW_H16G.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA._rtk_patchbay`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA._rtk_power`
- `__DATA.__const`

```diff

-  __TEXT.__text: 0x10ebbc
+  __TEXT.__text: 0x10efac
   __TEXT.__const: 0x2394c
-  __TEXT.__cstring: 0x15a4e
+  __TEXT.__cstring: 0x15bf9
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA._rtk_patchbay: 0x211

   __DATA.__zerofill: 0xc99c0
   Functions: 1172
   Symbols:   1650
-  CStrings:  2527
+  CStrings:  2535
 
Functions:
~ __ZN19CFlowControllerBase23ProcessCmd_Process_LRMEEv : 1528 -> 1652
~ __ZN19CFlowControllerBase23ProcessCmd_Process_MCTFEv : 1744 -> 1824
~ __ZN19CFlowControllerBase22ProcessCmd_Process_AVCEv : 1680 -> 1760
~ __ZN19CFlowControllerBase23ProcessCmd_Process_HEVCEv : 1888 -> 1968
~ __ZN19CFlowControllerBase18SendCommandToQueueEP20CAVECommonControllerjPvjjyyj : 1712 -> 1896
~ __Z15AVE_GetCurrTimev : 76 -> 80
~ sub_5a6bc -> sub_5a8e4 : 336 -> 348
~ sub_5a80c -> sub_5aa40 : 188 -> 192
~ sub_5a8c8 -> sub_5ab00 : 368 -> 380
~ __ZN14CAVCController16ProcessPipeStartEPv : 6100 -> 6200
~ __ZN14CAVCController14ConfigureMCPUsEP18AVE_PICMGMT_PARAMS : 9236 -> 9288
~ __ZN14CAVCController19GetSliceHeaderForFWEPhPjj : 848 -> 876
~ __ZN14CAVCController7setPipeEP18AVE_PICMGMT_PARAMS : 29024 -> 29196
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
