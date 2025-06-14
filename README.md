

# 80BitFloat

**80BitFloat** is a lightweight C++ library providing support for 80-bit extended precision floating point numbers, based on the IEEE 754 standard (often referred to as "Extended Precision" or "Float80"). This implementation is designed for systems that do not natively support the 80-bit format, such as modern ARM architectures.

## Features

- Emulates IEEE 754 80-bit floating point format
- Designed for binary compatibility with AIFF and similar formats
- Currently supports **big-endian** byte order only
- Provides basic conversion and operator overloading
- Intended to integrate cleanly into projects requiring extended precision types

## Status

This project is **not under active development**, except as required by its parent project dependency. Bug reports and contributions may be addressed as needed but are not guaranteed.

## Use Case

Primarily developed to support accurate parsing and generation of audio file formats like AIFF-C, which rely on 80-bit big-endian floats to store sample rates and other metadata.

## License

[MIT License](LICENSE) — feel free to use and modify as needed.