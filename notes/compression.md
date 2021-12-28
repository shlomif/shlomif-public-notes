# Resources about Compression

* [gzip](https://en.wikipedia.org/wiki/Gzip) - commonly used
* [bzip2](https://en.wikipedia.org/wiki/Bzip2) - better ratio than gzip on average, but slower.
* [xz](https://en.wikipedia.org/wiki/Xz) - better ratio than bzip2 on average, but slower.
    * [lzip](https://en.wikipedia.org/wiki/Lzip) - `.lz` under the GPL
    * [LZMA](https://en.wikipedia.org/wiki/Lempel%E2%80%93Ziv%E2%80%93Markov_chain_algorithm) - the algorithm they are based on (as used by 7z).
* [zstd](https://en.wikipedia.org/wiki/Zstandard) - reportedly very fast
* [Brotli](https://en.wikipedia.org/wiki/Brotli) - improves on gzip compression
* [lz4](https://en.wikipedia.org/wiki/LZ4_%28compression_algorithm%29) - fast but "slightly worse" compression ratio
* [lrzip](https://github.com/ckolivas/lrzip) - supports ZPAQ for efficient but slow compression
* [zopfli](https://github.com/google/zopfli) - gzip-compatible more efficient, but very slow compression. Does not compress as well as xz and is much slower.

## Documents

* [Compression FAQ](http://www.faqs.org/faqs/compression-faq/)
* [Huffman coding](https://en.wikipedia.org/wiki/Huffman_coding)
* [Arithmetic coding](https://en.wikipedia.org/wiki/Arithmetic_coding)

## Tools

* [optipng](http://optipng.sourceforge.net/)
* [lepton](https://github.com/dropbox/lepton) - losslessly compress JPEGs.
* [packMP3](https://github.com/packjpg/packMP3) - lossless compression of mp3s (saw on the lepton README)
    * [Build / compilation fix](https://github.com/packjpg/packMP3/pull/7)
* [XMLPPM: XML-Conscious Compression](http://xmlppm.sourceforge.net/)

## License

This document is hereby placed under a triple
[MIT/Expat licence](http://en.wikipedia.org/wiki/MIT_License) /
[CC0](https://creativecommons.org/choose/zero/) /
[CC-by 4.0](https://creativecommons.org/licenses/by/4.0/) (or at your option
any later version of the licence), as copyrighted or waived copyright
by [Shlomi Fish](http://www.shlomifish.org/), 2018.

# Publicity
