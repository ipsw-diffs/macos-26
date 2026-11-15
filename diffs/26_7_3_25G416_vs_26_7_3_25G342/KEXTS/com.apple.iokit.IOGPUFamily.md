## com.apple.iokit.IOGPUFamily

> `com.apple.iokit.IOGPUFamily`

```diff

-130.16.7.0.0
+130.16.5.0.0
   __TEXT.__cstring: 0x64ea
-  __TEXT.__os_log: 0x5031
+  __TEXT.__os_log: 0x4fa2
   __TEXT.__const: 0xcc
-  __TEXT_EXEC.__text: 0x46cc8
+  __TEXT_EXEC.__text: 0x46bb0
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x460
   __DATA.__common: 0x8e8

   __DATA_CONST.__kalloc_var: 0x1090
   __DATA_CONST.__assert: 0x28
   Functions: 2146
-  Symbols:   3580
-  CStrings:  938
+  Symbols:   3578
+  CStrings:  936
 
Symbols:
+ __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2388
+ __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2394
+ __ZZN13IOGPUResource10initializeEP11IOGPUDeviceP20IOGPUNewResourceArgsyE21kalloc_type_view_1253
+ __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_2135
+ __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_2198
+ __ZZN17IOGPUCommandQueue4freeEvE20kalloc_type_view_204
- __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2395
- __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2401
- __ZZN13IOGPUResource10initializeEP11IOGPUDeviceP20IOGPUNewResourceArgsyE21kalloc_type_view_1271
- __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_2160
- __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_2223
- __ZZN13IOGPUResource31newResourceWithParentResourceIDEP5IOGPUP11IOGPUDevice13eIOGPUResTypeyyyyPyjE11_os_log_fmt_8
- __ZZN13IOGPUResource31newResourceWithParentResourceIDEP5IOGPUP11IOGPUDevice13eIOGPUResTypeyyyyPyjE11_os_log_fmt_9
- __ZZN17IOGPUCommandQueue4freeEvE20kalloc_type_view_208
Functions:
~ __ZN13IOGPUResource31newResourceWithParentResourceIDEP5IOGPUP11IOGPUDevice13eIOGPUResTypeyyyyPyj : 1212 -> 1044
~ __ZNK13IOGPUResource17getMappingOptionsEP20IOGPUNewResourceArgsy : 380 -> 356
~ __ZN13IOGPUResource14updateMappingsE11OSSharedPtrIS_EP14IOGPUMappingOpjj : 1320 -> 1300
~ __ZN11IOGPUDevice12new_resourceEP20IOGPUNewResourceArgsP26IOGPUNewResourceReturnDatayPj : 2512 -> 2472
~ __ZN17IOGPUCommandQueue13clientReleaseEv : 132 -> 104
CStrings:
- "%s: child resource (offset=0x%llx, size=0x%llx) exceeds parent memory size 0x%llx.\n"
- "%s: client_buffer (0x%llx) precedes client_base (0x%llx).\n"
```
