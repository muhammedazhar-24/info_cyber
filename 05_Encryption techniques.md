# Encryption Techniques
## Learning Objectives 
- Understand crytography basics
- differentiate batween symmetrics and asymmetric encryption
- learn hashing and digital singnature concepts

  ## crytography
  cryptography is a techique of securing information and communication using codes to ensure confidentiality, integrity and aunthentication.

  ## Symmetrics encryption
  - Uses two keys: Public key (for encrytion) & Private key (for decryption).
  - Used for secure key exchange and digitals communication.

  ## Hashing
  - converts data into a fixed- length string.
  - One-way process cannot be reversed.
  - Used for password storage and integrity checking.
  - Common Algorithms: SHA-256, HDS (deprecated)

  ## Digital Signatures and Certificates

  - Ensure authenticity and non-repudiation.
  - A digital signature uses private key to sign data and public kay to verify.
  - Certificates (X.509) are issued by Certificate Authorities (CAs) for trust verification (used in HTTPS).

  ## Example:
When visiting https://bank.com
- browser verifies certificate signed by CA to ensure authenticity.
