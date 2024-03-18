# OneTimePass
A tool for generating one time pads off of a password and encrypting information within a easy to use accessible html format.
## https://jakekyee.github.io/OneTimePass/examplefile.html

### What is this?

This is a tool for easily generating encrypted messages within an easy to decrypt html document. The one time pad used is derived from the password used to decrypt the message, and no external javascript libraries are used. This means that the file can be unlocked without internet as long as there is access to a browser. 


### How to use


To create an encrypted message, use the generator.html file. Simply fill out the inputs with the password to be encrypted and decrypted with, the message, and the file name and click download.

### How Does It Work?

The One Time Pad used is generated based off of the password. The length of the pad is dependent on both the password, which is also encrypted for verification purposes, and the message itself. 



[//]: #![AliceToMessage](https://user-images.githubusercontent.com/99901262/210124519-288ffd4a-498d-4fa3-97a5-077a2802a5bf.png)  





https://jakekyee.github.io/OneTimePass/generator2.html

### Final thoughts


This probably NOT secure.

I am not an expert, and the extent of the research done for this project consisted of skimming wikipedia articles. There are probably many exploits and flaws, although I believe that the level of security is sufficient for most non-targeted use cases.

There are many similar projects that others have made previously, and the methods that they use are likely better and more cryptographically secure than my own.
