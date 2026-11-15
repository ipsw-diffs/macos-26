## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Fri Oct 30 17:18:08 PDT 2026; root:libignition-58~38704/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Fri Oct 30 17:18:08 PDT 2026; root:libignition-58~38704/libignition_core/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Sun Oct 11 23:43:09 PDT 2026; root:libignition-58~38688/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Sun Oct 11 23:43:09 PDT 2026; root:libignition-58~38688/libignition_core/RELEASE_ARM64E"
```
