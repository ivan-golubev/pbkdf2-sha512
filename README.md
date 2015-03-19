# Password-based key derivation function 2 with SHA512

PBKDF2 with HmacSHA512 psuedo random function(PRF) as defined in  PKCS#5 v2.0.

This is a patched version of this class taken from the OpenJDK:
- PBKDF2HmacSHA1Factory.

Class PBKDF2KeyImpl was not modified at all.

The only difference with the standard implementation is the usage of SHA512 instead of SHA1.