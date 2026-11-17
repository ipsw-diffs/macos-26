## avbdiagnose

> `/usr/bin/avbdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-1440.7.0.0.0
-  __TEXT.__text: 0x6fb0
-  __TEXT.__auth_stubs: 0x1f0
-  __TEXT.__objc_stubs: 0x18a0
+1450.2.0.0.0
+  __TEXT.__text: 0x7434
+  __TEXT.__auth_stubs: 0x3c0
+  __TEXT.__objc_stubs: 0x1900
   __TEXT.__objc_methlist: 0x134
   __TEXT.__const: 0x8
-  __TEXT.__cstring: 0x251d
-  __TEXT.__objc_methname: 0xf79
+  __TEXT.__cstring: 0x2806
+  __TEXT.__objc_methname: 0xfd4
   __TEXT.__objc_classname: 0x2c
-  __TEXT.__objc_methtype: 0xba
-  __TEXT.__unwind_info: 0x100
-  __DATA_CONST.__auth_got: 0x100
-  __DATA_CONST.__got: 0x128
+  __TEXT.__objc_methtype: 0xc8
+  __TEXT.__unwind_info: 0x118
+  __DATA_CONST.__auth_got: 0x1e8
+  __DATA_CONST.__got: 0x120
   __DATA_CONST.__const: 0x398
-  __DATA_CONST.__cfstring: 0x12c0
+  __DATA_CONST.__cfstring: 0x1240
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA.__objc_const: 0x288
-  __DATA.__objc_selrefs: 0x650
+  __DATA.__objc_selrefs: 0x668
   __DATA.__objc_ivar: 0x8
   __DATA.__objc_data: 0x140
-  __DATA.__bss: 0x2c
+  __DATA.__data: 0xc
+  __DATA.__bss: 0x13c
   - /System/Library/Frameworks/AudioVideoBridging.framework/Versions/A/AudioVideoBridging
   - /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/TimeSync.framework/Versions/A/TimeSync
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 47
-  Symbols:   81
-  CStrings:  531
+  Functions: 52
+  Symbols:   109
+  CStrings:  554
 
Symbols:
+ ___error
+ ___strlcat_chk
+ ___strlcpy_chk
+ __exit
+ _bzero
+ _close
+ _confstr
+ _dup
+ _fchown
+ _fcopyfile
+ _fdopen
+ _fstat
+ _fstatat
+ _fwrite
+ _getenv
+ _geteuid
+ _mkdirat
+ _mkdtemp
+ _open
+ _openat
+ _removefile
+ _removefile_state_alloc
+ _removefile_state_free
+ _sigaction
+ _snprintf
+ _strerror
+ _strlen
+ _strtoul
+ _umask
+ _unlinkat
- _OBJC_CLASS_$_NSData
- _fopen
CStrings:
+ "\nOutput saved to: %s\n"
+ "        Failed to create %s (%s)\n"
+ "        Failed to write %s/%s (%s)\n"
+ "        Wrote %s/%s\n"
+ "%@.aemxml"
+ "%savbdiagnose-XXXXXXXX"
+ "-"
+ "--output-dir"
+ "-cjf"
+ "-o"
+ "/"
+ "/private/var/tmp"
+ "1450.2"
+ "@28@0:8i16@20"
+ "Apple"
+ "Missing directory after \"%s\"\n"
+ "SUDO_GID"
+ "SUDO_UID"
+ "TMPDIR"
+ "avbdiagnose: cannot create %s/%s (%s)\n"
+ "avbdiagnose: cannot duplicate the archive descriptor (%s)\n"
+ "avbdiagnose: cannot open output directory %s (%s)\n"
+ "avbdiagnose: failed to capture /var/log/system.log (%s)\n"
+ "avbdiagnose: failed to create %s\n"
+ "avbdiagnose: failed to create the ioreg dump (%s)\n"
+ "avbdiagnose: failed to remove %s (%s)\n"
+ "avbdiagnose: output file name is too long\n"
+ "avbdiagnose: unable to create a private staging directory (%s)\n"
+ "avbdiagnose: unable to create the capture directory (%s)\n"
+ "avbdiagnose: unable to create the info dump (%s)\n"
+ "avbdiagnose: unable to open the capture directory (%s)\n"
+ "bz2"
+ "com.apple.avbdeviced.connections"
+ "com.apple.avbdeviced.devices"
+ "com.apple.avbdeviced.entityIDs"
+ "com.apple.avbdeviced.persistentinfo"
+ "com.apple.avbdeviced.virtual"
+ "currentDirectoryPath"
+ "fileSystemRepresentation"
+ "info.dump"
+ "initWithDirectoryFileDescriptor:name:"
+ "initWithFileDescriptor:closeOnDealloc:"
+ "ioreg"
+ "stringByAppendingPathComponent:"
+ "stringByAppendingPathExtension:"
+ "stringWithFileSystemRepresentation:length:"
+ "substringToIndex:"
+ "system.log"
+ "terminationStatus"
+ "usage:\n%s [--no-enumeration] [--no-coreaudio] [--acmp-state] [--stream-info] [--stream-counters] [--no-info-tree] [--no-timesync] [--no-finder-reveal] [-o|--output-dir <directory>]\n"
+ "writeData:error:"
- "\nOutput saved to: %s.bz2\n"
- "        Wrote %s\n"
- "%@.bz2"
- "%@/%@"
- "%@/%@.aemxml"
- "%@/info.dump"
- "%@/ioreg"
- "%@/system.log"
- "-cvjf"
- "-rf"
- "/bin/cp"
- "/bin/rm"
- "/tmp"
- "/tmp/avbdiagnose-%@"
- "1440.7"
- "Apple/com.apple.avbdeviced.connections"
- "Apple/com.apple.avbdeviced.devices"
- "Apple/com.apple.avbdeviced.entityIDs"
- "Apple/com.apple.avbdeviced.persistentinfo"
- "Apple/com.apple.avbdeviced.virtual"
- "createDirectoryAtURL:withIntermediateDirectories:attributes:error:"
- "createFileAtPath:contents:attributes:"
- "data"
- "fileHandleForWritingAtPath:"
- "fileURLWithPath:"
- "initWithPath:"
- "usage:\n%s [--no-enumeration] [--no-coreaudio] [--acmp-state] [--stream-info] [--stream-counters] [--no-info-tree] [--no-timesync]\n"
- "writeToURL:atomically:"
```
