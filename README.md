<h1 align="center"> EncryChat </h1>


## Objective

The aim of this project is so that people can give their opinions, in a fully encrypted chat, over the tor network.

## EncryChat Security

EncryChat uses RSA encryption, using an asymmetric key which ensures greater security.

### Initializing the connection

1. Client connects to the server.
2. The server returns a public key.
3. Client sends your data to the server encrypted with the public server key in json format.
4. Connection initialized.

### When a user sends a message

1. Client sends to the server your message encrypted with the public server key.
2. The server decrypts the message, and to send to each customer, encrypts with each one's key and send to the respective customers.
3. Submission completed


These steps guarantee the security of the chat, making it almost impossible for someone outside the network to decrypt.

## > All over the Tor network!
