# RSA Factoring Challenge :snake:

We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.

## Description of what each file shows:
* factors - the program to factorize (Usage: time ./factors tests/test00)
* rsa - (Usage: ./rsa tests/rsa-1 ...)
* tests/test00 - the file with the numbers

Compile C function: gcc -fPIC -shared factors_functions.c -o lib_factors_functions.so 


### Environment
* Language: python
* OS: Ubuntu 20.04 LTS


