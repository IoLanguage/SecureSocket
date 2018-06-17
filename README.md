# SecureSocket 
Interface to secure network communication. 
Sockets will auto-yield to other coroutines while waiting on a request. 
All blocking operations use the timeout settings of the socket. 
Reads are appended to the socket's read buffer which can be accessed using the readBuffer method.
A SecureSocket is a wrapper on an OpenSSL SSL object and supports both TLSv1 and DTLSv1.

# Installation
`openssl` should be installed and foundable in your system. Then:
```
eerie install https://github.com/IoLanguage/SecureSocket.git
```
