# The Quite OK Image Format
[QOI](https://qoiformat.org/qoi-logo-black-framed.svg)

## Introduction
The Quite OK Image Format ([QOI](https://qoiformat.org/)) is a lossless image format
that is designed to be quite ok. While It is not designed to be the best format for
any particular use case, it achieves much faster speeds in both encoding and decoding
compared to png.

I tried implementing it in C++ as a png-to-qoi and visa-versa converter following the
format specifications file ([pdf](https://qoiformat.org/qoi-specification.pdf)). 