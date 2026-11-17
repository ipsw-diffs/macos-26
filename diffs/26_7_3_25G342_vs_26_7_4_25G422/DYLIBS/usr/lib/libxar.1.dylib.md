## libxar.1.dylib

> `/usr/lib/libxar.1.dylib`

```diff

-503.160.5.701.1
-  __TEXT.__text: 0xc6b8
+503.160.5.702.1
+  __TEXT.__text: 0xcbbc
   __TEXT.__auth_stubs: 0x8b0
-  __TEXT.__const: 0x168
+  __TEXT.__const: 0x170
   __TEXT.__cstring: 0xbf9
   __TEXT.__unwind_info: 0x2f0
   __DATA_CONST.__got: 0x10

   - /usr/lib/libbz2.1.0.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 222
-  Symbols:   368
+  Functions: 223
+  Symbols:   369
   CStrings:  192
 
Symbols:
+ _xar_io_get_decompress_chunk_size
Functions:
~ _xar_darwinattr_archive : 1868 -> 1872
~ _xar_bzip_fromheap_done : 80 -> 92
~ _xar_bzip_fromheap_in : 480 -> 824
~ _xar_darwinattr_extract : 1472 -> 1592
~ _xar_ea_write : 148 -> 264
~ _xar_data_extract : 424 -> 428
~ _xar_data_verify : 164 -> 180
+ _xar_io_get_decompress_chunk_size
~ _xar_attrcopy_from_heap : 712 -> 848
~ _xar_attrcopy_from_heap_to_stream_init : 260 -> 268
~ _xar_attrcopy_from_heap_to_stream : 616 -> 788
~ _xar_attrcopy_from_heap_to_stream_end : 152 -> 200
~ _xar_gzip_fromheap_done : 80 -> 92
~ _xar_gzip_fromheap_in : 588 -> 844
```
