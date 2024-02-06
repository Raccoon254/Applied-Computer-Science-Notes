# Computer Networks

## Attack
 A deliberate attempt to compromise integrity, or availability of a computer system or network by exploiting weaknesses in design, implementation, or configuration.

Attacks can be classified as passive or active.

### Passive Attack
They attempt to learn or make use of information from the system but does not affect system resources. It includes:

- Eavesdropping message content or sniffing
- Traffic analysis

Such attacks are difficult to detect therefore the strategy is to prevent the attack.

### Active Attack
They attempt to alter system resources, or affect their operation. They include:

- Spoofing, ie. masquerading or impersonation
- Replay
- Modification, ie. altering the message, man in the middle
- DOS ,etc.

They are easier to detect but more difficult to prevent.

## Terms
**Vulnerability** is a weakness in a security system.

**Threat** is a set of circumstances that has potential to cause loss or harm.

**Controls** are ways to block a threat that tries to exploit one or more vulnerabilities.

## Security Objectives

1. **Confidentiality** - aims to protect data against unauthorized disclosure.
2. **Integrity** - aims to detect unauthorized data modification and replay.
3. **Availability** - ensures that systems work promptly and service is not denied to authorized users.

## Impacts of Security Attacks

An attack on a business can lead to:

- Economic/Financial losses
- Reputation damage
- Legal consequences

## Security Controls

**Technical Controls** 
 - Cryptography
 - Authentication and Access Control
 - Firewalls

# Cryptography 

This is the process of concealing the contents of a message from all except those who know the key.
The Key is a data string which when combined with the plain text message using an algorithm, produces output result called cipher text that is unreadable until decrypted.

A message in its original form is called ***plaintext***/ ***ClearText*** and the encrypted message is called **ciphertext**, this is a message produced in disguise form.

The process of converting plaintext to ciphertext is called **encryption** and the reverse process is called **decryption**.

<img src="images/image.png" alt="Alt text" width="" height="200">

There are three types of algorithms used in cryptography:

- **Symmetric Key Algorithms** - Also called 
***Secret Key, Single key encryption*** Uses a single key for both encryption and decryption. The encryption algorithm and decryption algorithm run in reverse order. 
They use a single key for both encryption and decryption.

Although this algorithm is fast, it suffers from the problem of key distribution.

Examples include 
DES(Data Encryption Standard) - 56-bit key, 
 3DES(Triple DES) - 168-bit key,
 Extended DES - 128-bit key,
 AES(Advanced Encryption Standard) uses variable key lengths of 128, 192, or 256 bits.
 CAST-128, Rivest Cipher, RC4, Blowfish, Twofish, KASUMI, Skipjack, Misty1, etc.

## Assignment Operation of DES

TODO: Add the assignment operation of DES

- **Asymmetric Key Algorithms** - ***Public Key*** Uses two keys, a public key and a private key. The public key is used for encryption and the private key is used for decryption. Examples include RSA, DSA, etc.

- **Hash Functions** - These are used to ensure data integrity. They take an input and produce a fixed-size string of bytes. Examples include MD5, SHA-1, etc.

