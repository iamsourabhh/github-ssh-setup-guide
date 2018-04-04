# Github SSH Setup Guide

- Go to your root
    ```
    cd ~
    ```
- Check if /.ssh folder exists or not.


- /.ssh contains private and public keys, .pub is for the public key and the other one is your private key


- If does not have these file
- Run
    ```
    ssh-keygen
    Generating public/private rsa key pair.
    Enter file in which to save the key (/home/test/.ssh/id_rsa): y
    Enter passphrase (empty for no passphrase): 
    Enter same passphrase again: 
    Your identification has been saved in y.
    Your public key has been saved in y.pub.
    The key fingerprint is:
    SHA256:LQ2qzGcTeE9PBP4Uiv37wVvQbNQmwVwMlbkPmCZAsaQ test@superprofs-Lenovo-B50-70
    The key's randomart image is:
    +---[RSA 2048]----+
    |       .=..  oo==|
    |       *.+ .  o=.|
    |      E *.o. 0o +|
    |     . . O. ++.+ |
    |    . + S *o. +..|
    |   o o + + o o  .|
    |    + + . o o .  |
    |     o .   . +   |
    |            o    |
    +----[SHA256]-----+

    ```

    