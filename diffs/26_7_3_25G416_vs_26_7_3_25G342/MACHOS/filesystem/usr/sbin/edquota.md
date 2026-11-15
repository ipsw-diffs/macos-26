## edquota

> `/usr/sbin/edquota`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA.__data`

```diff

-757.0.0.701.1
-  __TEXT.__text: 0x1dec
-  __TEXT.__auth_stubs: 0x340
-  __TEXT.__cstring: 0x59b
+757.0.0.0.0
+  __TEXT.__text: 0x1d14
+  __TEXT.__auth_stubs: 0x330
+  __TEXT.__cstring: 0x57a
   __TEXT.__unwind_info: 0xb0
-  __DATA_CONST.__auth_got: 0x1a0
+  __DATA_CONST.__auth_got: 0x198
   __DATA_CONST.__got: 0x20
   __DATA.__data: 0x40
   __DATA.__bss: 0x4de
   - /usr/lib/libSystem.B.dylib
   Functions: 24
-  Symbols:   58
-  CStrings:  65
+  Symbols:   57
+  CStrings:  64
 
Symbols:
- _fstat
Functions:
~ sub_100000a08 : 300 -> 180
~ sub_100001448 -> sub_1000013d0 : 864 -> 756
~ sub_1000021d0 -> sub_1000020ec : 44 -> 56
CStrings:
- "edquota: %s: not a regular file\n"
```
