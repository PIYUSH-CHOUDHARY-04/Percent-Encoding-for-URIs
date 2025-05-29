# Percent-Encoding-for-URIs
This repository provides simple and efficient APIs for percent-encoding and decoding, which are essential for URI encoding when making web requests.

It includes two main functions:

    percent_encode() — performs percent-encoding of input strings

    percent_decode() — reverses the encoding to retrieve the original string

The implementation uses a pre-computed static lookup table for encoding, which:

    Eliminates runtime overhead by avoiding on-the-fly computations

    Maximizes speed for high-performance applications

    Is well-suited for systems with tight memory constraints

    Prevents memory fragmentation issues commonly caused by dynamic allocation

This design makes it ideal for embedded systems, low-level networking stacks, and other resource-constrained environments.
