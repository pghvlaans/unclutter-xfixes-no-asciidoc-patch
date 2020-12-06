# unclutter-xfixes-no-asciidoc-patch
This patch removes asciidoc (which has many dependencies in some distributions) as a dependency for unclutter-xfixes (https://github.com/Airblader/unclutter-xfixes). Installing unclutter after applying this patch will disable the creation of the man page. All other functionality is unaffected.

DEPENDENCIES and Makefile will be altered.

To use the patch, move it into the root directory for unclutter-xfixes. Then, run `patch -p0 <patch.txt` while inside that directory. From here, it will be possible to install unclutter without installing asciidoc.

The patch is currrent to unclutter-xfixes v.1.5 (as of December 5th, 2020)
