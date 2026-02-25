**Wand**

I found the this wand. I don’t know whose wand is so i need to find it and also the flag is inside this image. Go on, you may find the hint.

Analysis:

there was only one photo. I tried binwalk, Strings and exiftool Since there was an image and the flag is in the image. After using exiftool i got "password: Full name of the weilder without spaces in small letters"
So I assumed there is a hidden zip or some file with an password for extracting.

After some researching I got to know "Steghide" I used it and the password to extract the txt file.The password was "albuspercivalwulfricbriandumbledore". The  command was "steghide extract -sf wand.jpeg"/

The Flag:potter{1_570l3_7h47_3ld3r_w4nd}
