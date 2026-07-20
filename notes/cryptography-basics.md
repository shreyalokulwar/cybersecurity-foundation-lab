# Cryptography Basics

## Introduction

Cryptography protects information through encryption and secure communication techniques.

## Symmetric Encryption

Uses a single key for encryption and decryption.

Examples:
- AES
- DES

Advantages:
- Fast
- Efficient

Disadvantages:
- Key distribution problem

## Asymmetric Encryption

Uses two keys:
- Public Key
- Private Key

Examples:
- RSA
- ECC

Advantages:
- Secure key exchange

Disadvantages:
- Slower than symmetric encryption

## Hashing

Converts data into fixed-length values.

Examples:
- MD5
- SHA-256

Example:

```bash
echo "Cybersecurity" | sha256sum
```

## SSL/TLS

SSL/TLS secures communication between clients and servers.

## OpenSSL Example

```bash
echo "Hello World" | openssl dgst -sha256
```

## Conclusion

Cryptography provides confidentiality, integrity, and authentication.
