## Fixed version

This forked version has some modifications to make things work.

### Changes

- Removed 2 zero-bytes padding for each filenames.
- Applied segmentation merging if files are separated in two or more segments.
- Fixed incorrect paths when extracting to Linux

## Original README

KiriKiri .XP3 archive repacking and extraction tool

Extracts an .XP3 archive to a directory of files, and
packs a directory of files into an .XP3 archive, including any
subdirectory structure.

Uses Numpy (if available) to speed up decryption/encryption.

Original script by Edward Keyes, ed-at-insani-dot-org, 2006-07-08, http://www.insani.org/tools/

and SmilingWolf, https://bitbucket.org/SmilingWolf/xp3tools-updated

Python 3 rewrite, Awakening
