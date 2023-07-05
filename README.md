# BITCOIN_
Cryptography was primarily used in secret by the military or spies up until the 1970s. The US government's publication of the Data Encryption Standard (DES), a block cypher that was widely adopted, and Whitfield Diffie and Martin Hellman's first publicly accessible work on public-key cryptography, however, changed that and made it more widely known.
## Diffie–Hellman key exchange
One of the first public-key protocols was the Diffie-Hellman-Merkle key exchange, which Ralph Merkle called after Whitfield Diffie and Martin Hellman. One of the earliest real-world applications of public key exchange in cryptography is DHM-key_ex. This is the first known study that put out the concept of a private key and an associated public key.
Although Diffie-Hellman key agreement is a non-authenticated key agreement protocol in and of itself, it serves as the foundation for a number of authenticated protocols and is utilised to provide forward secrecy in TLS' ephemeral modes (referred to as EDH or DHE depending on the cypher suite).
Different Internet services are secured using Diffie-Hellman. However, according to research released in October 2015, many DH Internet apps at the time did not utilise strong enough security measures to guard against compromise by highly well-funded attackers, such as the security agencies of some nations.
## DS(DIGITAL SIGNATURE)

The public-key primitives used in message authentication are digital signatures. On written or typed texts, handwritten signatures are frequently used in the physical world. They serve to bond the message's signatories.
A similar method that ties a person or entity to digital data is a digital signature. The recipient and any other person may independently verify this binding.
Data and a secret key known only to the signer are used to calculate the digital signature, which is a cryptographic value. To achieve secrecy in many digital conversations, it is preferable to send encrypted messages rather than plaintext. A public (encryption) key of the sender is made available in the public domain in a public key encryption method, allowing anybody to spoof the sender's identity and transmit any encrypted message to the recipient.
To ensure message authentication and non-repudiation, users that utilise Public Key Cryptography (PKC) for encryption must also look for digital signatures to accompany encrypted data.

## Symmetric and Asymmetric Key

In symmetric key encryption, the encryption and decryption processes use the same key. This makes it harder to share the key since anyone who intercepts the communication and sees the key may then decode your data.
As a result, symmetric key encryption is commonly employed to encrypt data at rest. The most widely used symmetric key encryption technique is AES-256. 
AWS uses it to encrypt data stored on hard drives (EBS volumes) and S3 buckets. In asymmetric key encryption, one key (the public key) is used exclusively to encrypt data, while another key (the private key) is used to decode it. When there are two or more parties engaged in the data transport, asymmetric key encryption is utilised. This sort of encryption is used to encrypt data in transit, which is data transmitted between two or more systems. RSA is the most well-known example of asymmetric key encryption. 

## RSA

Asymmetric algorithms are used to build public-key cryptography. RSA (Rivest-Shamir-Adleman) is a popular public-key cryptosystem for secure data transfer. The abbreviation "RSA" is derived from the surnames of Ron Rivest, Adi Shamir, and Leonard Adleman, who presented the method publicly in 1977. 
The RSA algorithm is relatively slow. As a result, it is rarely used to directly encrypt user data. RSA is most commonly used to send shared keys for symmetric-key cryptography, which are subsequently utilised for bulk encryption-decryption.

## Elliptic-curve cryptography (ECC)

Based on the algebraic nature of elliptic curves over finite fields, this method provides public-key encryption. When compared to non-EC encryption (based on ordinary Galois fields), ECC allows for fewer keys to guarantee equal security.
Elliptic curves can be used for key agreement, digital signatures, pseudo-random number generators, and other applications. They may be used for encryption indirectly by combining the key agreement with a symmetric encryption algorithm.
By computing discrete logarithms on a hypothetical quantum computer, Shor's technique can be used to break elliptic curve encryption. According to the most recent quantum resource estimates, breaking a curve with a 256-bit modulus (128-bit security level) requires 2330 qubits and 126 billion Toffoli gates. Satoshi Nakamoto was opposed to and despised this type of encryption.

## PRETTY GOOD PRIVACY(PGP)

A cryptographic privacy and authentication programme for data transmission. PGP is used to sign, encrypt, and decrypt text, e-mails, files, directories, and whole disc partitions, as well as to improve e-mail security. PGP was created in 1991 by Phil Zimmermann. They use the OpenPGP (RFC 4880) standard for encrypting and decrypting data. He made the first publicly available programme using public-key cryptography (together with its source code) available for distribution over public FTP in 1991.

## Decentralized(Web of Trust)

Phil Zimmermann proposed it first in 1992. A web of trust is a notion in cryptography that is used in OpenPGP-compatible systems to establish the legitimacy of the binding between a public key and its owner. Its decentralised trust approach is an alternative to a public key infrastructure (PKI)'s centralised trust model, which depends solely on a certificate authority (or a hierarchy of such).

## Certification authority (CA); Centralised
A digital certificate in cryptography confirms that the identified subject of the certificate owns a public key. This enables others (relying parties) to depend on signatures or statements made about the private key that corresponds to the certified public key. A CA works as a trusted third party, trusted by both the subject (owner) of the certificate and the party relying on the certificate. The X.509 or EMV standard defines the format of these certificates.
### SSL
SSL is a standard technique that encrypts data exchanged between a website and a browser (or between two servers) to secure an internet connection.
It is made up of an IP address and a port number.
### SECURE SHELL
SSH, also known as Secure Shell or Secure Socket Shell, is a network protocol that allows users, particularly system administrators, to access a computer over an unprotected network in a safe manner. SSH can also refer to a collection of tools that implement the SSH protocol.

## TIME STAMP PROTOCOL
The Time-Stamp Protocol, sometimes known as TSP, is a cryptographic technique for validating timestamps utilising X.509 certificates and public key infrastructure. A piece of electronic data was created at or before the time indicated by the timestamp, according to the signer. RFC 3161 contains the protocol's definition. One use of the protocol is to demonstrate when a digital signature was issued, for example, before the related certificate was revoked.

## HASHING




