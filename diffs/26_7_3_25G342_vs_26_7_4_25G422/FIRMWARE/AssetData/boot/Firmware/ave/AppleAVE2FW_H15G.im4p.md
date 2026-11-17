## AppleAVE2FW_H15G.im4p

> `AssetData/boot/Firmware/ave/AppleAVE2FW_H15G.im4p`

### Sections with Same Size but Changed Content

- `__DATA._rtk_patchbay`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA.__const`

```diff

-  __TEXT.__text: 0xf25b0
+  __TEXT.__text: 0xf2940
   __TEXT.__const: 0x1f840
-  __TEXT.__cstring: 0x14100
+  __TEXT.__cstring: 0x142ab
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA._rtk_patchbay: 0x211

   __DATA.__zerofill: 0xc67c0
   Functions: 1127
   Symbols:   1561
-  CStrings:  2354
+  CStrings:  2362
 
Functions:
~ __ZN19CFlowControllerBase23ProcessCmd_Process_LRMEEv : 1520 -> 1648
~ __ZN19CFlowControllerBase23ProcessCmd_Process_MCTFEv : 1724 -> 1804
~ __ZN19CFlowControllerBase22ProcessCmd_Process_AVCEv : 1664 -> 1744
~ __ZN19CFlowControllerBase23ProcessCmd_Process_HEVCEv : 1868 -> 1948
~ __ZN19CFlowControllerBase18SendCommandToQueueEP20CAVECommonControllerjPvjjyyj : 1236 -> 1388
~ __Z15AVE_GetCurrTimev : 76 -> 80
~ sub_55510 -> sub_5571c : 336 -> 348
~ sub_55660 -> sub_55878 : 188 -> 192
~ sub_5571c -> sub_55938 : 368 -> 380
~ __ZN14CAVCController16ProcessPipeStartEPv : 6092 -> 6192
~ __ZN14CAVCController14ConfigureMCPUsEP18AVE_PICMGMT_PARAMS : 9064 -> 9124
~ __ZN14CAVCController19GetSliceHeaderForFWEPhPjj : 848 -> 876
~ __ZN14CAVCController7setPipeEP18AVE_PICMGMT_PARAMS : 27472 -> 27564
~ __Z15AVE_PSInfo_MakePKh13_E_AVE_PSTypeiiP16_S_AVE_PSContext : 752 -> 824
~ __ZN7AVE_FPS3AddEPK11_S_AVE_Time : 784 -> 792
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
