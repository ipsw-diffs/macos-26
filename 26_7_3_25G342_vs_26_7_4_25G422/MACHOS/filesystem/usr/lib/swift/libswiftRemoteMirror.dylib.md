## libswiftRemoteMirror.dylib

> `/usr/lib/swift/libswiftRemoteMirror.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`

```diff

-6.3.2.1.11
-  __TEXT.__text: 0xd4e64
+6.3.2.1.12
+  __TEXT.__text: 0xd502c
   __TEXT.__auth_stubs: 0x490
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x705a
+  __TEXT.__cstring: 0x70b7
   __TEXT.__const: 0x7b8
-  __TEXT.__unwind_info: 0x1428
+  __TEXT.__unwind_info: 0x1430
   __DATA_CONST.__got: 0x48
   __DATA_CONST.__const: 0xe58
   __AUTH_CONST.__auth_got: 0x248

   __DATA.__common: 0x10
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 2021
-  Symbols:   2439
-  CStrings:  1639
+  Functions: 2022
+  Symbols:   2440
+  CStrings:  1641
 
Symbols:
+ __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE22isValueGenericArgumentEPNS1_4NodeE
Functions:
~ __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE17decodeMangledTypeEPNS1_4NodeEjb : 20992 -> 21360
+ __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE22isValueGenericArgumentEPNS1_4NodeE
CStrings:
+ "type where a Builtin.FixedArray count is required"
+ "unresolved Builtin.FixedArray element type"
```
