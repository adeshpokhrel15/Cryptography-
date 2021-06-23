# Cryptography
Cryptography deals with encrypting or encoding a piece of information (in a plain text) into a form that looks gibberish and makes little sense in ordinary language.
This encoded message(also called ciphertext) can then be decoded back into a plain text by the intended recipient using a decoding technique (often along with a private key) communicated to the end-user. <br>
Caesar Cipher is a type of substitution cipher, in which each letter in the plain text is replaced by another letter at some fixed positions from the current letter in the alphabet.

### Algorithm For Cipher Ceaser
<img src ="https://res.cloudinary.com/adeshpokhrel/image/upload/v1622684720/alg_vebbpx.png">

### Caesar Cipher encryption rule
<img src = "https://res.cloudinary.com/adeshpokhrel/image/upload/v1622684712/encr_y7j9na.png">

### Caesar Cipher Decrypt rule
<img src= "https://res.cloudinary.com/adeshpokhrel/image/upload/v1622684712/des_nodrfh.png">

# Vigenere Cipher
Vigenere Cipher is a method of encrypting alphabetic text. It uses a simple form of polyalphabetic substitution. A polyalphabetic cipher is any cipher based on substitution, using multiple substitution alphabets .The encryption of the original text is done using the Vigenère square or Vigenère table.

### Encryption 
The plaintext(P) and key(K) are added modulo 26. <br>
  Ei = (Pi + Ki) mod 26

### Decryption
  Di = (Ei - Ki + 26) mod 26

# One Time Pad Cipher
It is a system that generates a randomly organized and unique ‘private key’; this one-time use private key is used to encrypt a later decrypted message by the receiver using a matching one-time-pad and key. Information encrypted with keys is almost impossible to break. Each encryption is unique and shows no relation with other encryption. In one-time-pad, the key used is known as a secret key as they hold a very crucial piece of pieces of information.

### Encryption
To encrypt a letter, a user needs to write a key underneath the plaintext. The plaintext letter is placed on the top and the key letter on the left. The cross section achieved between two letters is the plain text.

### decryption 
To decrypt a letter, user takes the key letter on the left and finds cipher text letter in that row. The plain text letter is placed at the top of the column where the user can find the cipher text letter.



