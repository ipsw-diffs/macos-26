## kcm

> `/System/Library/PrivateFrameworks/Heimdal.framework/Helpers/kcm`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-710.160.4.702.2
-  __TEXT.__text: 0x16b78
+710.160.4.704.1
+  __TEXT.__text: 0x16c14
   __TEXT.__auth_stubs: 0x10a0
   __TEXT.__const: 0x40
   __TEXT.__cstring: 0x1ce3

   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0x770
   __DATA_CONST.__cfstring: 0xa0
-  __DATA.__data: 0x698
+  __DATA.__data: 0x6d8
   __DATA.__bss: 0x140
   __DATA.__common: 0x38
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/Heimdal.framework/Versions/A/Heimdal
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
-  Functions: 287
-  Symbols:   711
+  Functions: 288
+  Symbols:   713
   CStrings:  348
 
Symbols:
+ _check_ntlm_challage_locked
+ _ntlm_challenge_mutex
Functions:
~ _kcm_parse_ntlm_challenge_one : 368 -> 392
~ _kcm_unparse_challenge_all : 324 -> 348
~ _kcm_op_add_ntlm_challenge : 308 -> 336
~ _check_ntlm_challage : 208 -> 80
+ _check_ntlm_challage_locked
```
