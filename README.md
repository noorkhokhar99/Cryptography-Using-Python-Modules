# Cryptography-Using-Python-Modules

Ever wondered how your passwords are hidden? Have you thought about what the word end-to-end encryption in WhatsApp means? Did your curiosity flick, thinking about the process of online money transfer? 


This feat of internet privacy and security is achieved using cryptography, which is a concept for your online protection.

What is Cryptography?
Cryptography is a lock-and-key technique that enables secure communication of information through codes that can only be accessed by the appropriate receiver. The data is encrypted and decrypted to achieve the required confidentiality of the information.

Encryption is basically a conversion of plain text into cipher text. Decryption is the process of retrieving the plain text from the cipher text using a secret key.

Types of Cryptography
There are three widely used types of cryptography:





Python Modules for Cryptography
Modules are files that contain Python statements and definitions for functions, classes, and variables that can be used in your program. It essentially makes the code understandable and logically organized.




n this article, we will shed light on some modules that can be used for the encryption and decryption of data.

1. Fernet Module
The Fernet module comes under the cryptography package. Here, a unique key is generated without which the data cannot be read/modified. Hence it implements Symmetric Key Cryptography.

It uses three major methods to generate keys, encrypt and decrypt the data.



To use the Fernet module, you need to install the cryptography package first by running the following command:

pip install cryptography



2. Crytocode Module
Cryptocode is a library, which is basically a collection of modules. It is the simplest way of encryption and decryption as it is more suitable for people wanting a mere abstraction.

The encryption has two parameters – the string to be encoded and the key to decrypt the encoded string. This library is not a built-in module, so it needs to be installed in your terminal using the command:

pip install cryptocode




3. RSA Algorithms
RSA algorithm implements Asymmetric Key Cryptography. It uses two keys for encryption and decryption of text – a public and a private key.




Anyone with a public key can encrypt and send the data. But only the user with the private key can decrypt and access the data.

To install the RSA library, enter the following code in your terminal:

pip install rsa


4. Hashlib Modules
Hashlib module is a collection of hashing algorithms used to encrypt data as a hash. Regardless of the size of the data, a hash is a string of fixed length.


This encoding technique is used widely by tech giants as the data encrypted is almost impossible to decrypt. This is a built-in module in Python, so you don’t need to install it. Out of the numerous algorithms present under hashlib, we will take a glance at the SHA256 algorithm.



SHA256

SHA256 – Secure Hash Algorithm converts the data into a fixed string of 256 bytes in length. It improves security, as longer hashes lead to higher security levels. It is the successor of SHA1 algorithms.


5. AES Algorithms
AES Algorithm uses a single common secret key to encrypt and decrypt the data and is used by governments due to its high level of data integrity. The encryption and decryption occur in blocks where the data is modified and stored in blocks of size 128 bits, whereas the size of the encryption key can be 128, 192, or 256 bits.

Different modes are applied to facilitate a proper stream of data in the blocks. The five modes are:

ECB mode: Electronic Code Book mode
CBC mode: Cipher Block Chaining mode
CFB mode: Cipher Feedback mode
OFB mode: Output FeedBack mode
CTR mode: Counter mode
Run the following code in your terminal to install the pyaes module:

pip install pyaes


6. Simple-crypt Module
Simple-crypt justifies its name by portraying it as one of the fastest and simplest ways to encrypt and decrypt text with just a single line of code. It also uses the pycrypto module, which provides the necessary algorithm implementations and a check to warn when cipher text is modified. 

Enter the following command in your terminal to install the modules:

pip install simple-crypt --no-dependencies
pip install pycrypto


Cryptography is a vast ocean that needs more exploration. I have brushed the working of some famous Python modules used in cryptography. Each module has a unique characteristic that has to be implemented in apt situations where they can be efficiently used.

I hope you learned something new about the cryptography modules used in Python. All the best for your future endeavors!



