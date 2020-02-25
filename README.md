# Mypaint-Styrene - a slightly extended Styrene
_(Perhaps it's wrapped in some cellophane)_

[Original Styrene repository](https://github.com/achadwick/styrene/)

Refer to the [original docs](https://styrene.readthedocs.io/en/latest/)
for more information.

### Additional features

These are the additions to MyPaint-Styrene that are not part of the original.

* The `--build-7z` option bundles the build output in a 7z archive.
* The `IcoFileLocation` launcher field enables use of premade .ico files.
* The substitution `{cfg_dir}` can be used in a specification file, to define a path that is relative to the location of the specification file itself.
* Defaulting to lzma compression for installers.
* Priority of `delete`/`nodelete` patterns can be adjusted by adding `@-rank-n` to the end of a pattern, where `n` is a positive integer.
