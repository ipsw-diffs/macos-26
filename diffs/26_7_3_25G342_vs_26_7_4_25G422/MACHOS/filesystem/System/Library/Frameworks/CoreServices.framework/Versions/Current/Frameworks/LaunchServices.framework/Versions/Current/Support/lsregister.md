## lsregister

> `/System/Library/Frameworks/CoreServices.framework/Versions/Current/Frameworks/LaunchServices.framework/Versions/Current/Support/lsregister`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA.__objc_classrefs`
- `__DATA.__data`

```diff

-1444.5.4.2.0
-  __TEXT.__text: 0x49c0
-  __TEXT.__auth_stubs: 0x650
-  __TEXT.__objc_stubs: 0x4c0
+1444.5.4.3.0
+  __TEXT.__text: 0x4618
+  __TEXT.__auth_stubs: 0x630
+  __TEXT.__objc_stubs: 0x400
   __TEXT.__const: 0x158
-  __TEXT.__gcc_except_tab: 0x488
-  __TEXT.__cstring: 0xd6b
+  __TEXT.__gcc_except_tab: 0x3f0
+  __TEXT.__cstring: 0xcb4
   __TEXT.__objc_classname: 0x1
-  __TEXT.__oslogstring: 0x1c1
-  __TEXT.__objc_methname: 0x359
-  __TEXT.__unwind_info: 0x168
-  __DATA_CONST.__auth_got: 0x338
+  __TEXT.__oslogstring: 0x19e
+  __TEXT.__objc_methname: 0x2fe
+  __TEXT.__unwind_info: 0x160
+  __DATA_CONST.__auth_got: 0x328
   __DATA_CONST.__got: 0xa8
   __DATA_CONST.__const: 0x1b0
-  __DATA_CONST.__cfstring: 0x2c0
+  __DATA_CONST.__cfstring: 0x2a0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA.__objc_selrefs: 0x130
+  __DATA.__objc_selrefs: 0x100
   __DATA.__objc_classrefs: 0x40
   __DATA.__data: 0x8
   __DATA.__bss: 0x68

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 68
-  Symbols:   136
-  CStrings:  132
+  Functions: 67
+  Symbols:   134
+  CStrings:  121
 
Symbols:
- __LSExtensionsLog
- __LSRegisterPlatformFrameworkExtensionPointInfo
Functions:
~ sub_100000c30 : 80 -> 7568
- sub_100000c80
CStrings:
- "%s Registering extension point: %@"
- "SDKDictionary"
- "URL: `%@`"
- "extensionPointDefinitionEnumerator"
- "identifier"
- "int LSRegisterMain(int, const char **)"
- "lsregister: error %d registering Extension Point: `%s` platform: %d %s\n"
- "lsregister: registered Extension Point: `%s` platform: %d %s\n"
- "platform"
- "stringWithFormat:"
- "url"
```
