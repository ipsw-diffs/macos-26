## gssd

> `/usr/sbin/gssd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-85.0.0.0.0
-  __TEXT.__text: 0x9cb0
-  __TEXT.__auth_stubs: 0xaa0
+85.0.0.700.1
+  __TEXT.__text: 0x9ca8
+  __TEXT.__auth_stubs: 0xab0
   __TEXT.__const: 0x70
   __TEXT.__cstring: 0x2ca1
   __TEXT.__oslogstring: 0x19
   __TEXT.__unwind_info: 0x190
-  __DATA_CONST.__auth_got: 0x550
+  __DATA_CONST.__auth_got: 0x558
   __DATA_CONST.__got: 0xc0
   __DATA_CONST.__auth_ptr: 0x18
   __DATA_CONST.__const: 0x278

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   Functions: 98
-  Symbols:   205
+  Symbols:   206
   CStrings:  368
 
Symbols:
+ _strcmp
Functions:
~ sub_1000057f8 : 1056 -> 1048
```
