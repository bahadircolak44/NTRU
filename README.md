# NTRU
"Please look at Key Exchange Paper" for more explanation

NTRU Key Exchange Protocol
Key exchange is a trusted and functional method in cryptography. This cryptographic method centered exchanging keys between two parties, allowing use of a cryptographic algorithm.
To be able to exchanging ecrypted messages, both sides of process must be equipped to encrypt messages to be sent and decrypt messages received. The nature of the equipping they require depends on the encryption technique they might use. If they use a code, both will require a copy of the same codebook. If they use a cipher, they will need appropriate keys. If the cipher is a symmetric key cipher, both will need a copy of the same key. If an asymmetric key cipher with the public/private key property, both will need the other's public key.

We will give you a result of implementations of NTRU and NTRU-KE. For our experiment we built a python package and run it on a computer with 8Gb RAM, Intel Core i7-6500U up to 3.16GHz. We use python for this implementation, because python is really efficient for mathematical calculations. To obtain the best results of encryption and decryption, we randomly chose polynomials ourselves, instead of using python libraries. A brief description of both packages is provided below.
