## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/Contents/MacOS/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-905.43.1.0.0
-  __TEXT.__text: 0x7757c
+905.44.1.0.0
+  __TEXT.__text: 0x775a4
   __TEXT.__auth_stubs: 0xd50
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x4
Functions:
~ sub_681d0 : 724 -> 764
CStrings:
+ "22:02:48"
+ "905.44.1"
+ "Nov 11 2026"
- "02:24:46"
- "905.43.1"
- "Oct 12 2026"
```
