## SceneKit

> `/System/Library/Frameworks/SceneKit.framework/Versions/A/SceneKit`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-608.903.0.0.0
-  __TEXT.__text: 0x4c2150
+608.904.0.0.0
+  __TEXT.__text: 0x4c21d4
   __TEXT.__auth_stubs: 0x3200
   __TEXT.__objc_methlist: 0x194b4
   __TEXT.__const: 0x26698

   - /System/Library/Frameworks/ModelIO.framework/Versions/A/ModelIO
   - /System/Library/Frameworks/OpenGL.framework/Versions/A/OpenGL
   - /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
+  - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
   - /System/Library/PrivateFrameworks/CoreSymbolication.framework/Versions/A/CoreSymbolication
   - /System/Library/PrivateFrameworks/CoreUI.framework/Versions/A/CoreUI

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 29204
+  Functions: 29205
   Symbols:   39684
   CStrings:  17799
 
Functions:
~ __ZL14__AddNewSourceP9domSourcePKcP9__C3DMeshPlbP12__C3DLibrary : 2184 -> 2212
~ __ZN20SCNCJavaScriptAction27cpp_updateWithTargetForTimeEP7SCNNoded : 320 -> 296
~ __loadDDS : 2124 -> 2140
~ ___appendController : 1040 -> 1032
+ __ZN20SCNCJavaScriptAction27cpp_updateWithTargetForTimeEP7SCNNoded.cold.1
CStrings:
+ "Welcome to SceneKit 608.904 (Nov  8 2026 22:08:30)"
- "Welcome to SceneKit 608.903 (Oct 12 2026 03:27:40)"
```
