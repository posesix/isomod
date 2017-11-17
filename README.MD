# ISOMOD

Allows injecting files into ISO images without re-building the image completely, with restrictions.

You may freely use, distribute, and modify the source code.

Simply invoke a C++ compiler on `isomod.cpp` to compile.
MinGW needs `-mno-ms-bitfields` option.

```
isomod put <iso_image> <iso_file> <host_file>`
```
Use the full path and name for `iso_file`. File ID is not used or required. (`;N`)

Example:
```
isomod put image.iso DATA/FILE.DAT hostfile.dat
```
