Upon receiving your partner’s public key via email, you can send encrypted messages to him/her over a public channel (the Internet).

Start a text file and write your full name and a message for your partner in this file. Save it as yournamePlain.txt. (For example, my file would be yesemPlain.txt)

Repeat the steps in Part 1 until the “Generate Key” step. At the “Generate Key” step, choose to load a file for the key and load your partner’s public key file. (Here it is assumed that your partner followed the steps above and used the same algorithms and parameters as in Part1 to generate his/her key.)

Continue as follows:

- Mode> ECB
- Input/Output > For input file, load the message file you created for your partner. Choose New for Output File and name the output file as yournameCipher.enc.
- Then hit GO!

Take a screenshot of the Kryptos window indicating that encryption was done:

![](.guides/img/kryptos1.png)
Check your working folder to see that there is a new file called yournameCipher.enc in the folder. Send this encrypted message to your partner via email. 
