### Name: Python Wrangling
### Tag: General Skills
### Description: 
Python scripts are invoked kind of like programs in the Terminal... Can you run this Python *script* and using *this password* to get *the flag*?

We can download the script, password, and flag, and when we open the pw.txt file, we are given the password: 68f88f9368f88f9368f88f9368f88f93.

Hint 1 says: Get the Python script accessible in your shell by entering the following command in the Terminal prompt: $ wget https://mercury.picoctf.net/static/2ac2139344d2e734d5d638ac928f1a8d/ende.py. 

We do this with flag.txt.en, and run the command **python3 ende.py -d flag.txt.en** (-d is used to decrypt), and the python file asks for the password. Then, we enter the password that were given in pw.txt and get the flag: ***picoCTF{4p0110_1n_7h3_h0us3_68f88f93}***
