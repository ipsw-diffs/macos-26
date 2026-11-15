## afscexpand

> `/usr/bin/afscexpand`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-174.160.2.0.0
-  __TEXT.__text: 0x13808
+174.160.2.701.1
+  __TEXT.__text: 0x138ac
   __TEXT.__auth_stubs: 0x320
   __TEXT.__const: 0x235c0
   __TEXT.__cstring: 0xbca
Functions:
~ sub_10000c000 : 2468 -> 2548
~ sub_10000c9a4 -> sub_10000c9f4 : 2812 -> 2792
~ sub_10000d64c -> sub_10000d688 : 792 -> 804
~ sub_10000d964 -> sub_10000d9ac : 432 -> 444
~ sub_10000db14 -> sub_10000db68 : 868 -> 880
~ sub_10000de78 -> sub_10000ded8 : 500 -> 512
~ sub_10000e06c -> sub_10000e0d8 : 812 -> 824
~ sub_10000e398 -> sub_10000e410 : 452 -> 464
~ sub_10000e55c -> sub_10000e5e0 : 2708 -> 2736
~ sub_100011ac8 -> sub_100011b68 : 1516 -> 1520
```
