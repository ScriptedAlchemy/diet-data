# Diet Data
Brings Brotli level compression to all browsers.

As of right now this is a work in progress upgrade to my previous compression system. The idea is that i want brotli or better levels of compression. 

The idea is through a method I call *algorythem stacking*. Pretty much take non web compression algorythems, store the binary in a efficent string of some kind, then optimize the string if possible, and finally send the file to the client of some transport layer such as gzip. Compressing a already compressed file to get an even more compressed result. 

The main compression I am using right now is some flavor of LZMA-D. 
