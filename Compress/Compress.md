## **Compress**

The Apache Commons Compress library defines an API for working with ar, cpio, Unix dump, tar, zip, gzip, XZ, Pack200, bzip2, 7z, arj, LZMA, snappy, DEFLATE, lz4, Brotli, Zstandard, DEFLATE64 and Z files.

The code in this component has many origins:

- The bzip2, tar and zip support came from Avalon's Excalibur, but originally from Ant, as far as life in Apache goes. The tar package is originally Tim Endres' public domain package. The bzip2 package is based on the work done by Keiron Liddle as well as Julian Seward's [libbzip2](http://www.bzip.org/index.html). It has migrated via:
  Ant -> Avalon-Excalibur -> Commons-IO -> Commons-Compress.
- The cpio package has been contributed by Michael Kuss and the [jRPM](http://jrpm.sourceforge.net/) project.
- The pack200 code has originally been part of the now retired [Apache Harmony™](https://harmony.apache.org/) project.