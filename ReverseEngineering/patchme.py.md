## Description

Can you get the flag?
Run this [Python program](https://artifacts.picoctf.net/c/388/patchme.flag.py) in the same directory as this [encrypted flag](https://artifacts.picoctf.net/c/388/flag.txt.enc).

Hints: None

## Solution

Open up the PicoCTF webshel in a new tab and login. <br>
Clear any other files that may be in the directory you are in. <br>
To get both of the file type <code> wget FILE ADDRESS HERE </code> and do it for both. <br>
Test out the python file by typing <code> python patchme.flag.py </code> and it will ask you for a password witch we dont know. So press enter to exit the program. <br>
To view the code in the python file type <code> nano patchme.flag.py </code> <br>
The key should be spead out in multiple lines, as circled here. <br>
![Screenshot 2023-03-04 175532](https://user-images.githubusercontent.com/66439855/222932338-aa8f7409-41c3-4f25-91bb-800868823afa.png) <br>
Open up notepad in your host computer and get each green text circled into one string. <br>
What you should have in your notepad is <code> ak98-=90adfjhgj321sleuth9000 </code> <br>
Start the python program again and paste what you have in your notepad. <br>
The following output is the flag. <br>

<details>
  <summary>Flag</summary>
  
  
    picoCTF{p47ch1ng_l1f3_h4ck_21d62e33}

</details>
