OpenSSL capi engine patch (deprecated)
======================================

**Note**: This is included in OpenSSL since 1.0.1d (I think).

This patch is for OpenSSL's capi engine. It adds support for private keys
inside a machine keystore (`MACHINE_KEYSET`). It has been tested with 
OpenSSL version 1.0.1 but since it is very simple it should work with most 
future versions of this engine (until they maybe finally implement it by 
themselves.
