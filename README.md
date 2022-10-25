# Password-match-from-a-rainbow-table
There are a lot of IoT systems are vulnerable from poor password authentication. Rather than storing passwords in plaintext on the device, 
one common approach is to hash the password using a cryptographic hash function, and then store the hash values. This way, 
if an attacker is able to recover the hashed password file, it would be difficult for the attacker to recover the password from the hashed values.

First created a hash rainbow password table from a plaintext of table, the plaintext table contains 10,000 passwords.
The idea is to compare a hash value from the hashed password list if it appears in the rainbow table there will be a
match and will give the corresponding plaintext password.
The matching passwords output shows the minimum and maximum time to recover a password.
The output shows the time needed to search the entire rainbow table when no password could be recovered.
