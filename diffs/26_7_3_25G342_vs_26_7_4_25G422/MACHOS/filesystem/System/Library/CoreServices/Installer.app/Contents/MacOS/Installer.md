## Installer

> `/System/Library/CoreServices/Installer.app/Contents/MacOS/Installer`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1359.120.1.700.1
-  __TEXT.__text: 0x19304
+1359.120.1.701.1
+  __TEXT.__text: 0x194d4
   __TEXT.__auth_stubs: 0x5e0
-  __TEXT.__objc_stubs: 0x6dc0
-  __TEXT.__objc_methlist: 0x1ae0
+  __TEXT.__objc_stubs: 0x6de0
+  __TEXT.__objc_methlist: 0x1af0
   __TEXT.__const: 0x120
-  __TEXT.__cstring: 0x2efa
-  __TEXT.__objc_methname: 0x6815
+  __TEXT.__cstring: 0x2fa5
+  __TEXT.__objc_methname: 0x685d
   __TEXT.__objc_classname: 0x450
   __TEXT.__objc_methtype: 0xd06
   __TEXT.__gcc_except_tab: 0xdc
-  __TEXT.__unwind_info: 0x6f0
+  __TEXT.__unwind_info: 0x6f8
   __DATA_CONST.__auth_got: 0x300
   __DATA_CONST.__got: 0x4d0
   __DATA_CONST.__const: 0x4b8
-  __DATA_CONST.__cfstring: 0x28c0
+  __DATA_CONST.__cfstring: 0x28e0
   __DATA_CONST.__objc_classlist: 0x118
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x30

   __DATA_CONST.__objc_superrefs: 0xd0
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA.__objc_const: 0x3700
-  __DATA.__objc_selrefs: 0x2110
-  __DATA.__objc_ivar: 0x2d0
+  __DATA.__objc_const: 0x3740
+  __DATA.__objc_selrefs: 0x2118
+  __DATA.__objc_ivar: 0x2d8
   __DATA.__objc_data: 0xaf0
   __DATA.__data: 0x270
   __DATA.__common: 0x8

   - /usr/lib/libDiskUnlock.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 550
+  Functions: 551
   Symbols:   274
-  CStrings:  1905
+  CStrings:  1911
 
CStrings:
+ ".."
+ "Installer Plugins: Ignoring section path that escapes the package's plugins directory: %s"
+ "Installer Plugins: Pinned %lu section path(s) from the package's section list"
+ "_didPinSectionPaths"
+ "_pinnedSectionPaths"
+ "pinnedInstallerSectionPaths"
+ "pluginArchitecturesForSectionPaths:"
- "pluginArchitecturesForDocument:"
```
