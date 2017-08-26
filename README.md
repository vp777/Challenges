# Some interesting challenges I found in the last year

## keygenMe
The objective is to create a key generator.

## breakMe
Here we have an encryption oracle, which in each run generates randomly a new key, encrypts a message with that key and allows a single encryption of a user-chosen message. 
The goal here is to decrypt the initially given (IV,ciphertext) pair.

## discretelogMe
This one is created by me, tricky but not as hard as the rest of the challenges<br>
Given h=g^d mod p, calculate d. (Solution in about 30 seconds in [cocalc](https://cocalc.com))

## Hints
Run:

	fgrep <keygen,break,discrete> hints.txt
	
To get some hints for a particular challenge