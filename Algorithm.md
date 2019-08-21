# ALGORITHM:

<b> Select two prime no's. </b> 

Suppose P = a and Q = b. 
Now First part of the Public key : n = P*Q = ab.

<b> Now take an integer e such that , it is an integer and not a factor of n </b>

Also , 1 < e < Ф
[Ф = (a-1)*(b-1)]

Such that Φ(n) = (a-1)(b-1)

<b> Calculate Private Key, d: </b> 

d = (k*Φ(n) + 1) / e 

## This gives the keys as:
Public Key: <b>n</b> and <b>e</b> 

Private Key: <b>d</b>

