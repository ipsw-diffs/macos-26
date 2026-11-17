## AppleAVE2FW_H13S.im4p

> `AssetData/boot/Firmware/ave/AppleAVE2FW_H13S.im4p`

### Sections with Same Size but Changed Content

- `__DATA._rtk_patchbay`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA.__const`

```diff

-  __TEXT.__text: 0xe1444
+  __TEXT.__text: 0xe1784
   __TEXT.__const: 0x208d0
-  __TEXT.__cstring: 0x12b7e
+  __TEXT.__cstring: 0x12d29
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA._rtk_patchbay: 0x211

   __DATA.__zerofill: 0xc67c0
   Functions: 1059
   Symbols:   1462
-  CStrings:  2209
+  CStrings:  2217
 
Functions:
~ __ZN19CFlowControllerBase23ProcessCmd_Process_LRMEEv : 1520 -> 1648
~ __ZN19CFlowControllerBase23ProcessCmd_Process_MCTFEv : 1720 -> 1800
~ __ZN19CFlowControllerBase22ProcessCmd_Process_AVCEv : 1660 -> 1740
~ __ZN19CFlowControllerBase23ProcessCmd_Process_HEVCEv : 1864 -> 1944
~ __ZN19CFlowControllerBase18SendCommandToQueueEP20CAVECommonControllerjPvjjyyj : 1072 -> 1156
~ __Z15AVE_GetCurrTimev : 76 -> 80
~ sub_4f4e0 -> sub_4f6a8 : 336 -> 348
~ sub_4f630 -> sub_4f804 : 188 -> 192
~ sub_4f6ec -> sub_4f8c4 : 368 -> 380
~ __ZN14CAVCController16ProcessPipeStartEPv : 6092 -> 6192
~ __ZN14CAVCController14ConfigureMCPUsEP18AVE_PICMGMT_PARAMS : 9048 -> 9108
~ __ZN14CAVCController19GetSliceHeaderForFWEPhPjj : 848 -> 876
~ __ZN14CAVCController7setPipeEP18AVE_PICMGMT_PARAMS : 26684 -> 26776
~ __Z15AVE_PSInfo_MakePKh13_E_AVE_PSTypeiiP16_S_AVE_PSContext : 752 -> 824
~ __ZN7AVE_FPS3AddEPK11_S_AVE_Time : 792 -> 788
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
