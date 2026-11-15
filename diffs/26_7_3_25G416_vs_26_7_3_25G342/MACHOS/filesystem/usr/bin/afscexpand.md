## afscexpand

> `/usr/bin/afscexpand`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-174.160.2.701.1
-  __TEXT.__text: 0x138ac
+174.160.2.0.0
+  __TEXT.__text: 0x13888
   __TEXT.__auth_stubs: 0x320
   __TEXT.__const: 0x235c0
   __TEXT.__cstring: 0xbca
Functions:
~ sub_10000e5e0 : 2736 -> 2704
~ sub_100011b68 -> sub_100011b48 : 1520 -> 1516
```
