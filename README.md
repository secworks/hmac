# hmac
HMAC-SHA-256 in Verilog 2001


## Introduction
This core implements the keyed-hash message authentication code
function HMAC as specified in [NIST FIPS
198-1](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.198-1.pdf)
(PDF).

The specific version of HMAC implemented use SHA-256 as the hash
function, accepts a 256-bit key, and generates a 128-bit tag.

The implementation is (will be) compatible with the [HMAC-SHA-256-128 auth/integ function defined in RFC 4868](https://tools.ietf.org/html/rfc4868).


## Status
Not completed. Does **NOT** yet work. Do not use


## Implementation notes
The core uses [the sha256 core](https://github.com/secworks/sha256).
