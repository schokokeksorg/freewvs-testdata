This directory contains some tests that challenge proper handling
of unexpected situations.

* permission: file with permission 000 (causes read error).
* filename_dir: directory named like a .php file.
* garbage: random binary data in .php file.
* deep_recursion: lots of nested subdirectories to test os.walk limits.

All data here is trivial, but just in case anyone considers it
copyrightable it is licensed as CC0.
