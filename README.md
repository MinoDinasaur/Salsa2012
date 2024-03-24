# Salsa20/12
# Salsa20/12 Algorithm
The Salsa20/12 cryptographic method is a symmetric stream cipher meticulously crafted to offer a blend of robust security and efficient performance. It functions effectively with input data of varying lengths, yielding ciphertext that matches the length of the original plaintext.

# Example usage
key = b"Today_I_code_Salsa2012_algorithm"

nonce = b"mynonce1"

plaintext = b"Congatulation, you remake Salsa2012"

# Encrypt the plaintext
encrypted = encrypt(plaintext, key, nonce)

# Decrypt the ciphertext
decrypted = decrypt(encrypted, key, nonce)

# Result
Encrypted: eb5eadb64f763f988da746d1c834cc5627ff07353fe376b9de41da81b36cd029a6b8e5

Decrypted: Congatulation, you remake Salsa2012

# Compare Salsa20/12 to RC4

Salsa20 Generation Time: 4.940304756164551 seconds
RC4 Generation Time:  0.4647209644317627 seconds

# Source Code
[Code]([https://colab.research.google.com/drive/148CgeQQzID6h9XUVg9Igz2wtqXeK6Hin#scrollTo=wnQ-cZVr-4pb](https://colab.research.google.com/drive/1d2ZGj3D-t13YvR0KV-RIe_paM9dMwRY3#scrollTo=QOvB7f1msJBE))

# Github
(https://github.com/MinoDinasaur/Salsa2012)https://github.com/MinoDinasaur/Salsa2012
