* README_EN.txt
* 2020.02.10
* tacklelib--3dparty--xzutils

1. DESCRIPTION
2. LICENSE
3. REPOSITORIES
4. INSTALLATION
5. AUTHOR

-------------------------------------------------------------------------------
1. DESCRIPTION
-------------------------------------------------------------------------------
libarchive patched sources fork from:
https://git.tukaani.org/xz.git

Web access:
https://git.tukaani.org/?p=xz.git
https://tukaani.org/xz/

From authors:

  XZ Utils is free general-purpose data compression software with a high
  compression ratio. XZ Utils were written for POSIX-like systems, but also
  work on some not-so-POSIX systems. XZ Utils are the successor to LZMA Utils.

  The core of the XZ Utils compression code is based on LZMA SDK, but it has
  been modified quite a lot to be suitable for XZ Utils. The primary
  compression algorithm is currently LZMA2, which is used inside the .xz
  container format. With typical files, XZ Utils create 30 % smaller output
  than gzip and 15 % smaller output than bzip2.

  XZ Utils consist of several components:

  liblzma is a compression library with an API similar to that of zlib.
  xz is a command line tool with syntax similar to that of gzip.
  xzdec is a decompression-only tool smaller than the full-featured xz tool.
  A set of shell scripts (xzgrep, xzdiff, etc.) have been adapted from gzip to
  ease viewing, grepping, and comparing compressed files.
  Emulation of command line tools of LZMA Utils eases transition from LZMA
  Utils to XZ Utils.
  While liblzma has a zlib-like API, liblzma doesn't include any file I/O
  functions. A separate I/O library is planned, which would abstract handling
  of .gz, .bz2, and .xz files with an easy to use API.

The original library patched to add these files:

  * changelog file
  * readme file
  * cmake list file
    Cmake scripts uses the cmake modules from the tacklelib library:
    https://svn.code.sf.net/p/tacklelib/tacklelib/trunk/cmake/tacklelib

-------------------------------------------------------------------------------
2. LICENSE
-------------------------------------------------------------------------------
The most interesting parts of XZ Utils (e.g. liblzma) are in the public domain.
You can do whatever you want with the public domain parts.

Some parts of XZ Utils (e.g. build system and some utilities) are under
different free software licenses such as GNU LGPLv2.1, GNU GPLv2, or GNU GPLv3.

(see included text file "COPYING" or
`Licensing` section on the site https://tukaani.org/xz/ )

-------------------------------------------------------------------------------
3. REPOSITORIES
-------------------------------------------------------------------------------
Primary:
  * https://sf.net/p/tacklelib/3dparty--xzutils/HEAD/tree/trunk
    https://svn.code.sf.net/p/tacklelib/3dparty--xzutils/trunk
First mirror:
  * https://github.com/andry81/tacklelib--3dparty--xzutils/tree/trunk
    https://github.com/andry81/tacklelib--3dparty--xzutils.git
Second mirror:
  * https://bitbucket.org/andry81/tacklelib-3dparty-xzutils/src/trunk
    https://bitbucket.org/andry81/tacklelib-3dparty-xzutils.git

-------------------------------------------------------------------------------
4. INSTALLATION
-------------------------------------------------------------------------------
N/A

-------------------------------------------------------------------------------
5. AUTHOR
-------------------------------------------------------------------------------
Andrey Dibrov (andry at inbox dot ru)
