## AppleProResHWDecoder

> `/System/Library/Video/Plug-Ins/AppleProResHWDecoder.bundle/Contents/MacOS/AppleProResHWDecoder`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff

-575.1.0.0.0
-  __TEXT.__text: 0x21308
+577.0.0.0.0
+  __TEXT.__text: 0x21310
   __TEXT.__auth_stubs: 0x9f0
   __TEXT.__const: 0x74378
   __TEXT.__gcc_except_tab: 0x448
   __TEXT.__cstring: 0x1122
-  __TEXT.__oslogstring: 0x4189
+  __TEXT.__oslogstring: 0x4194
   __TEXT.__unwind_info: 0x3e8
   __DATA_CONST.__auth_got: 0x500
   __DATA_CONST.__got: 0x1e0
Functions:
~ sub_17290 : 496 -> 484
~ sub_17b6c -> sub_17b60 : 1172 -> 1192
CStrings:
+ "ERROR AppleProResHW (0x%x): %d: %s(): Inconsistent subrame slices pSubFrameInfo->fr[%d].subFrameSize=%d subFrOffs=%d\n\n"
- "AppleProResHW (0x%x): %s(): Inconsistent subrame slices pSubFrameInfo->fr[%d].subFrameSize=%d subFrOffs=%d\n"
```
