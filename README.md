# Caesar-Cipher-in-Cryptography-in-Python

This is a simple version of Caesars Cipher in Python language

The Caesar Cipher technique is one of the earliest and simplest methods of encryption technique.
It’s simply a type of substitution cipher, i.e., each letter of a given text is replaced by a letter with a fixed number of positions down the alphabet.
For example with a shift of 1, A would be replaced by B, B would become C, and so on. 

Thus to cipher a given text we need an integer value, known as a shift which indicates the number of positions each letter of the text has been moved down. 
The encryption can be represented using modular arithmetic by first transforming the letters into numbers, according to the scheme, A = 0, B = 1,…, Z = 25. 

The alphabet and number that are used in programs includes the lower and uppercase of an alphabet and the decimal numbers from 0-9.

There is a separate function for the shifting of the position, so that it can easily decrypt or encrypt a certain text.
