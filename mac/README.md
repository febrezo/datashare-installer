# Mac Installer

This Mac installer use the following dependencies:

* openssl
* apple-codesign (Rust crate)

You must also set those environment variables:

* `DATASHARE_PEM_B64`: Generated by Apple when certificate was created encoded in base64 ;
* `ICIJ_CERT_B64`: Certificate encoded in base64 ;
* `APPSTORE_KEY_ID`: Key ID (an alphanumeric string like DEADBEEF42)
* `APPSTORE_ISSUER_ID`: Issuer ID (likely a UUID)
* `APPSTORE_PRIVATE_KEY_B64`: PEM encoded ECDSA Privare Key private key (downloaded when you create an API Key) encoded in base64 ;
