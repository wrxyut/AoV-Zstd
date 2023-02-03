# AOV Zstd

This tool for compress and decompress game files for the mobile game "Arena of Valor" (AOV). It uses the Zstandard (zstd).

## Requirements

* python version 3.x
* pyzstd

## Feature

* Compress and Decompress AOV game files using the Zstandard (zstd).

## How to use

### Windows

* Create a directory named "input" in the same location as the script.
* Add the AOV game files you wish to compress or decompress to the "input" directory. These files should have one of the following extensions: ".xml", ".bytes", ".txt".
* Run the script.

## Note

* If the script is unable to find the "input" directory, it will create it for you and ask you to add the files to the directory.
* The script uses the pyzstd library to perform the compression and decompression, and uses the ZSTD_LEVEL and ZSTD_DICT constants as parameters.

## Warning

* Be careful and make sure to backup your files before running the script.

## Contact

For any issues or support please contact the developer on Github: https://github.com/wrxyut

## Version

1.0 (unstable)
