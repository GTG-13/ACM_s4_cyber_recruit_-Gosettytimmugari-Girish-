Letter from Hogwarts

I got the letter from hogwarts but it was password encrypted help me to find, lets try until we get the password the password for the pdf. In that pdf u can get the flag.

Analysis:

The pdf file was locked with a password. So I wanted to try using brute force. I used john and got the hashed password. The command is "pdf2john "file name" > Hash.txt"

Then I used John again with a worlist and found the password. The command was "john --worlist=../rockyou.txt hash.txt". The flag was in the pdf.

Flag :potter{w3lc0m3_70_h0gw4r75}
