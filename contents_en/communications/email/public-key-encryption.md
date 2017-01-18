[Title]: # (Public Key Encryption)
[Difficulty]: # (Advanced)
[Order]: # (1)

PGP is built upon the concept of Public Key Encryption. This is a cryptographic system that uses two keys - a public key known to everyone and a private key known only to the recipient of the message. When John wants to send a secure message to Jane, he uses Jane's public key to encrypt the message. Jane then uses her private key to decrypt it.

*   So public key encryption lets you encrypt and send messages safely to anyone whose public key you know.
*   If others know your public key, they can send you messages, which only you can decode.
*   And if people know your public key, you can sign messages so that those people will know they could only have come from you.
*   And if you know someone else's public key, you can decode a message signed by them, and know that it only came from them.

You should keep your private key stored somewhere safe, and protected with a long password. (If someone else gets a copy of your private key, they can pretend to be you, and sign messages claiming that they were written by you.) You can give your public key to anyone you want to communicate with you, or who wants to learn whether a message truly came from you.