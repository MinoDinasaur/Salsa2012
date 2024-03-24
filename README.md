# Salsa20/12
# Salsa20/12 Algorithm
The Salsa20/12 cryptographic method is a symmetric stream cipher meticulously crafted to offer a blend of robust security and efficient performance. It functions effectively with input data of varying lengths, yielding ciphertext that matches the length of the original plaintext.

# Input test case
key = b"Today_I_code_Salsa2012_algorithm"

nonce = b"mynonce1"

plaintext = b"Congatulation you remake Salsa2012"

# Encrypted plaintext
encrypted = encrypt(plaintext, key, nonce)

# Decrypted ciphertext
decrypted = decrypt(encrypted, key, nonce)

# Output test case
Encrypted: eb5eadb64f763f988da746d1c83895403daa552237ef7cb79b32e88cac7e832ba7bb

Decrypted: Congatulation you remake Salsa2012

# Comparasion between Salsa20/12 and RC4 in generating key time

Salsa20/12 Key-Generation Time: 4.940304756164551 seconds

RC4 Key-Generation Time:  0.4647209644317627 seconds

# Key sensitivity test:

Sensitivity of Salsa20/12 to Key: 510 bytes differ

Sensitivity of RC4 to Key: 509 bytes differ

# Code
[Code](https://colab.research.google.com/drive/1d2ZGj3D-t13YvR0KV-RIe_paM9dMwRY3#scrollTo=QOvB7f1msJBE) https://colab.research.google.com/drive/1d2ZGj3D-t13YvR0KV-RIe_paM9dMwRY3#scrollTo=QOvB7f1msJBE

# Github
[Github](https://github.com/MinoDinasaur/Salsa2012) https://github.com/MinoDinasaur/Salsa2012
