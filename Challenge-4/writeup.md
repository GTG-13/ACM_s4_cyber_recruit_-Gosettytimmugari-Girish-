This is for u know who

Someone from the Hogwarts send this file given below to the voldemort.I don’t know who it is and what is the information in it. What ever the information is but it will definitely harm harry so find the person who send it. The flag lies there.

Analysis and Solving:

I first extracted the contents of the file. There was only one text file with a clue. It was a harrypotter reference. The clue was indicating like only owners or similar people can veiw the real content. So I saw the hidden files. There was indeed one hidden file in it and it was a image.

Since it is an image I used binwalk First. IT showed some files So i extracted them using binwalk. The command was "binwalk -e <image name>". This led to another set of files which also had one text file. So i again used same method and got another image named 'horcurx"

Since strings give more info i first used exiftool and there was a comment in it. It was a Base64 encrypted. After decrypting I got the flag.

Flag: potter{7h15_15_D010r35_Um8r1dg3}
