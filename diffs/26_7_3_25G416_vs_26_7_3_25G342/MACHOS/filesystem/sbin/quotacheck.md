## quotacheck

> `/sbin/quotacheck`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA.__data`

```diff

-757.0.0.701.1
-  __TEXT.__text: 0x1a18
-  __TEXT.__auth_stubs: 0x2e0
-  __TEXT.__cstring: 0x337
+757.0.0.0.0
+  __TEXT.__text: 0x18b8
+  __TEXT.__auth_stubs: 0x2b0
+  __TEXT.__cstring: 0x2e5
   __TEXT.__const: 0x20
   __TEXT.__unwind_info: 0xa8
-  __DATA_CONST.__auth_got: 0x170
+  __DATA_CONST.__auth_got: 0x158
   __DATA_CONST.__got: 0x20
   __DATA.__data: 0x30
   __DATA.__bss: 0x511
   __DATA.__common: 0x4019
   - /usr/lib/libSystem.B.dylib
   Functions: 17
-  Symbols:   52
-  CStrings:  45
+  Symbols:   49
+  CStrings:  44
 
Symbols:
+ _fopen
- _close
- _fdopen
- _fstat
- _open
Functions:
~ sub_100000d00 : 2220 -> 1868
CStrings:
+ "w+"
- "quotacheck: %s: not a regular file\n"
- "quotacheck: %s: quota file changed unexpectedly\n"
```
