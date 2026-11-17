## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

```diff

-905.43.1.0.0
+905.44.1.0.0
   __TEXT.__const: 0x42610
-  __TEXT.__cstring: 0x41dc0
-  __TEXT.__os_log: 0x544af
-  __TEXT_EXEC.__text: 0x1a365c
+  __TEXT.__cstring: 0x42300
+  __TEXT.__os_log: 0x54aae
+  __TEXT_EXEC.__text: 0x1a489c
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x2b8
   __DATA.__common: 0x130

   __DATA_CONST.__kalloc_type: 0x4900
   __DATA_CONST.__kalloc_var: 0x2030
   Functions: 2785
-  Symbols:   10768
-  CStrings:  9119
+  Symbols:   10788
+  CStrings:  9146
 
Symbols:
+ __ZZ16AVE_Client_StartP13_S_AVE_ClientP14_S_AVE_TimeOutjiP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKcE11_os_log_fmt__28_
+ __ZZ18AVE_Client_PrepareP13_S_AVE_ClientP14_S_AVE_TimeOutP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKcE11_os_log_fmt__11_
+ __ZZ23AVE_Client_CheckDMVInfoP13_S_AVE_Client12_E_AVE_DevIDbP35AVE_SessionSettings_UserKernel_DataE11_os_log_fmt__11_
+ __ZZ23AVE_Client_CheckGGMInfoP13_S_AVE_Client12_E_AVE_DevIDbP35AVE_SessionSettings_UserKernel_DataE11_os_log_fmt__12_
+ __ZZ24AVE_Client_CheckLRMEInfoP13_S_AVE_Client12_E_AVE_DevIDbP35AVE_SessionSettings_UserKernel_DataE11_os_log_fmt_9
+ __ZZ24AVE_Client_CheckMCTFInfoP13_S_AVE_Client12_E_AVE_DevIDbP35AVE_SessionSettings_UserKernel_DataE11_os_log_fmt_9
+ __ZZ24AVE_Client_CheckMCTFInfoP13_S_AVE_Client12_E_AVE_DevIDbP35AVE_SessionSettings_UserKernel_DataE11_os_log_fmt__10_
+ __ZZ25AVE_CHM_SetDataInfo_FrameP10_S_AVE_CHMP16_S_AVE_FrameInfoP18AVE_PICMGMT_PARAMSE11_os_log_fmt_2
+ __ZZ26AVE_UCCmd_CheckParam_Start12_E_AVE_DevID17_E_AVE_ClientTypeP21S_AVE_UCInParam_StartE11_os_log_fmt_3
+ __ZZ28AVE_Client_DMV_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_1
+ __ZZ28AVE_Client_Enc_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_5
+ __ZZ28AVE_Client_Enc_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_6
+ __ZZ28AVE_Client_Enc_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_7
+ __ZZ28AVE_Client_GGM_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_9
+ __ZZ28AVE_UCCmd_CheckParam_Prepare12_E_AVE_DevID17_E_AVE_ClientTypeP23S_AVE_UCInParam_PrepareE11_os_log_fmt_1
+ __ZZ29AVE_Client_LRME_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_1
+ __ZZ29AVE_Client_MCTF_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_1
+ __ZZN7AVE_HwC15ProcessIntr_CmdEmijE11_os_log_fmt__19_
+ __ZZN7AVE_HwC15ProcessIntr_CmdEmijE11_os_log_fmt__20_
+ __ZZN9AVE_SVERC11UpdateStatsExixi14IMG_FRAME_TYPEiiiiP25_S_AVE_DistributedRCStatsE11_os_log_fmt_3
Functions:
~ __ZN9AVE_FwLog10PrintEntryExx : 1740 -> 1760
~ __Z22AVE_CalcBufSizeOfRecon14_E_AVE_DevType14_E_AVE_EncTypeiiii12_E_ChromaFmtbPi : 1988 -> 2132
~ __Z27AVE_CalcBufSizeOfMCTFOutput14_E_AVE_DevTypebiii12_E_ChromaFmtbPi : 1016 -> 1108
~ __Z25AVE_CHM_SetDataInfo_FrameP10_S_AVE_CHMP16_S_AVE_FrameInfoP18AVE_PICMGMT_PARAMS : 1436 -> 1648
~ __Z28AVE_Client_Enc_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfo : 1388 -> 2108
~ __Z29AVE_Client_LRME_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfo : 464 -> 680
~ __Z29AVE_Client_MCTF_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfo : 464 -> 680
~ __Z23AVE_Client_CheckDMVInfoP13_S_AVE_Client12_E_AVE_DevIDbP35AVE_SessionSettings_UserKernel_Data : 2756 -> 2956
~ __Z23AVE_Client_CheckGGMInfoP13_S_AVE_Client12_E_AVE_DevIDbP35AVE_SessionSettings_UserKernel_Data : 2996 -> 3196
~ __Z24AVE_Client_CheckMCTFInfoP13_S_AVE_Client12_E_AVE_DevIDbP35AVE_SessionSettings_UserKernel_Data : 2260 -> 2688
~ __Z24AVE_Client_CheckLRMEInfoP13_S_AVE_Client12_E_AVE_DevIDbP35AVE_SessionSettings_UserKernel_Data : 2268 -> 2464
~ __Z18AVE_Client_PrepareP13_S_AVE_ClientP14_S_AVE_TimeOutP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKc : 2604 -> 2848
~ __Z16AVE_Client_StartP13_S_AVE_ClientP14_S_AVE_TimeOutjiP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKc : 7772 -> 8024
~ __Z18AVE_Client_ProcessP13_S_AVE_ClientP14_S_AVE_TimeOuti : 1960 -> 1976
~ __Z16AVE_Client_ResetP13_S_AVE_ClientP14_S_AVE_TimeOuti : 1628 -> 1632
~ __ZN7AVE_HwC15ProcessIntr_CmdEmij : 6764 -> 7168
~ __Z28AVE_Client_GGM_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfo : 2768 -> 2972
~ __Z28AVE_Client_DMV_Check_ProcessP13_S_AVE_ClientP16_S_AVE_FrameInfo : 464 -> 680
~ __ZN12AVE_Pipeline6FindMDEy : 60 -> 52
~ __ZN9AVE_SVERC11UpdateStatsExixi14IMG_FRAME_TYPEiiiiP25_S_AVE_DistributedRCStats : 1364 -> 1620
~ __Z28AVE_UCCmd_CheckParam_Prepare12_E_AVE_DevID17_E_AVE_ClientTypeP23S_AVE_UCInParam_Prepare : 484 -> 704
~ __Z26AVE_UCCmd_CheckParam_Start12_E_AVE_DevID17_E_AVE_ClientTypeP21S_AVE_UCInParam_Start : 920 -> 1132
~ ___chkstk_darwin_probe : 44 -> 52
CStrings:
+ "%lld %d AVE %s: %s DPB size overflow %d %d %d %d %lld %lld %lld %lld %lld"
+ "%lld %d AVE %s: %s DPB size overflow %d %d %d %d %lld %lld %lld %lld %lld\n"
+ "%lld %d AVE %s: %s MCTFOutput size overflow %d %d %d %lld %lld %lld %lld %lld"
+ "%lld %d AVE %s: %s MCTFOutput size overflow %d %d %d %lld %lld %lld %lld %lld\n"
+ "%lld %d AVE %s: %s:%d %s | UCInfo epoch still live, prior stop not drained %p %lld %p %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | UCInfo epoch still live, prior stop not drained %p %lld %p %p %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | client name not NUL-terminated %d %d %p %lld"
+ "%lld %d AVE %s: %s:%d %s | client name not NUL-terminated %d %d %p %lld\n"
+ "%lld %d AVE %s: %s:%d %s | frame number out of range %p %lld %lld (range: [0,%d])"
+ "%lld %d AVE %s: %s:%d %s | frame number out of range %p %lld %lld (range: [0,%d])\n"
+ "%lld %d AVE %s: %s:%d %s | invalid ANFD entry %d %p %lld %d (%d %d %d %d %d)"
+ "%lld %d AVE %s: %s:%d %s | invalid ANFD entry %d %p %lld %d (%d %d %d %d %d)\n"
+ "%lld %d AVE %s: %s:%d %s | layer ID out of range %p %lld %u %u"
+ "%lld %d AVE %s: %s:%d %s | layer ID out of range %p %lld %u %u\n"
+ "%lld %d AVE %s: %s:%d %s | non-contiguous frame number %p %lld %p %u %lld"
+ "%lld %d AVE %s: %s:%d %s | non-contiguous frame number %p %lld %p %u %lld\n"
+ "%lld %d AVE %s: %s:%d %s | prior stop not drained %p %lld %p %p %p %p"
+ "%lld %d AVE %s: %s:%d %s | prior stop not drained %p %lld %p %p %p %p\n"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %p"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %p\n"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %lld %d"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %lld %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %lld %d"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %lld %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | invalid slice index %p %d %d %d %p %d %d"
+ "%lld %d AVE %s: %s::%s:%d %s | invalid slice index %p %d %d %d %p %d %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | wrong process done size %p %d 0x%lx %d %ld"
+ "%lld %d AVE %s: %s::%s:%d %s | wrong process done size %p %d 0x%lx %d %ld\n"
+ "%lld %d AVE %s: %s::%s:%d CBP0 flag size out of range %p %lld | %u %u"
+ "%lld %d AVE %s: %s::%s:%d CBP0 flag size out of range %p %lld | %u %u\n"
+ "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %d %p %lld | %d | %p %d"
+ "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %d %p %lld | %d | %p %d\n"
+ "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %lld | %d | %d-%d %d %lld %d | %p %d %d"
+ "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %lld | %d | %d-%d %d %lld %d | %p %d %d\n"
+ "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %lld %d %d-%d %lld"
+ "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %lld %d %d-%d %lld\n"
+ "0 <= iSliceIdx && iSliceIdx < pClient->VideoParams.sSliceMap.iNum"
+ "21:55:42"
+ "905.44.1"
+ "Nov 11 2026"
+ "pClient->pcUCInfoPool == NULL && pClient->pcExUCInfoPool == NULL && pClient->sClientSurfaceSet.pcUCInfo == NULL && pClient->sClientSurfaceSet.pcExUCInfo == NULL"
+ "pEntry->iBase > 0 && pEntry->sRect.iX >= 0 && pEntry->sRect.iY >= 0 && pEntry->sRect.iWidth >= 0 && pEntry->sRect.iHeight >= 0"
+ "pFrameData->sGOPInfo.iFrameNum >= 0 && pFrameData->sGOPInfo.iFrameNum <= 2147483647"
+ "pIn->frameNumber == (uint32_t)(pClient->iLastFrameNumber + 1)"
+ "pIn->iLayerID < pClient->VideoParams.iLayerNum"
+ "size >= (int32_t)sizeof(sCAveCmdEncodeDone)"
- "%lld %d AVE %s: %s DPB size overflow %d %d %d %d %d %d %d %d %lld"
- "%lld %d AVE %s: %s DPB size overflow %d %d %d %d %d %d %d %d %lld\n"
- "%lld %d AVE %s: %s MCTFOutput size overflow %d %d %d %d %d %d %d %lld"
- "%lld %d AVE %s: %s MCTFOutput size overflow %d %d %d %d %d %d %d %lld\n"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %d %p"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %d %p\n"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %lld %d %d"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %lld %d %d\n"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %lld %d %d"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %lld %d %d\n"
- "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %d %p %lld | %d 0x%x | %p %d"
- "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %d %p %lld | %d 0x%x | %p %d\n"
- "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %lld | %d 0x%x | %d-%d %d %lld %d | %p %d %d"
- "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %lld | %d 0x%x | %d-%d %d %lld %d | %p %d %d\n"
- "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %d %lld %d %d-%d %lld"
- "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %d %lld %d %d-%d %lld\n"
- "02:17:58"
- "905.43.1"
- "Oct 12 2026"
```
