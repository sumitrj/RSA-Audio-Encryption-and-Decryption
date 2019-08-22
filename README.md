# Audio-Encryption-and-Communication

## Generic Procedure of communicating using Texts:
1. A client (for example browser) sends its public key to the server and requests for some data.
2. The server encrypts the data using client’s public key and sends the encrypted data.
3. Client receives this data and decrypts it.

## Why prefer RSA algorithm?
The idea of RSA is based on the fact that it is difficult to factorize a large integer. 

The public key consists of two numbers where one number is multiplication of two large prime numbers. And private key is also derived from the same two prime numbers. 

So if somebody can factorize the large number, the private key is compromised. 

Therefore encryption strength totally lies on the key size and if we double or triple the key size, the strength of encryption increases exponentially.   
         
RSA keys can be typically 1024 or 2048 bits long, but experts believe that 1024 bit keys could be broken in the near future. But till now it seems to be an infeasible task.
       
