# Affine-Cipher-Cryptography
# Q-What is the Affine cipher? (Definition)
Affine encryption is the name given to a substitution cipher whose correspondence is given by an affine function endowed with 2 coefficients A and B.

# Q-How to encrypt using Affine cipher

Encryption uses a classic alphabet, and two integers, called coefficients or keys A and B, these are the parameters of the affine function Ax+B.

Example: Encrypt DCODE with the keys A=5, B=3 and the English/latin alphabet ABCDEFGHIJKLMNOPQRSTUVWXYZ.

For each letter of the alphabet is associated to the value of its position in the alphabet (starting at 0).

Example: By default, A=0, B=1, …, Z=25, but it is possible (but not recommended) to use A=1, …, Y=25, Z=0 using the alphabet ZABCDEFGHIJKLMNOPQRSTUVWXY.

For each letter of value x
of the plain text, is associated a value y, resulting of the affine function y=A×x+Bmod26 (with 26 the alphabet size). For each value y, corresponds a letter with the same position in the alphabet, it is the ciphered letter. The Affine ciphertext is the replacement of all the letters by the new ones.
