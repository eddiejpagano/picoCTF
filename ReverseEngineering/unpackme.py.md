## Description

Can you get the flag?
Reverse engineer this [Python program](https://artifacts.picoctf.net/c/466/unpackme.flag.py).

Hints: None

## Solution

Open up the picoCTF webshel in a new tab and login. <br>
Remove any files in your current directory. <br>
To download the python program type <code> wget https://artifacts.picoctf.net/c/466/unpackme.flag.py </code> <br>
Run the program and you'll see it requires a password that we dont have, so exit the program.<br>
View the program's code by typing <code> nano unpackme.flag.py </code> <br>
Add a new line under the variable plain and put a print statement <code> print(plain) </code><br>
Exit the nano editor by pressing ctrl + X and press y and enter to save changes. <br>
Run the program again and it should give you the flag in the begining output.
![capture](https://user-images.githubusercontent.com/66439855/222988948-c061788c-a42b-43f9-a29d-4cb0473af8ba.png) <br>

<details>
  <summary>Flag</summary>
  
  
    picoCTF{175_chr157m45_85f5d0ac}

</details>
