## Description

Can you get the flag?
Run this [Python program](https://artifacts.picoctf.net/c/430/bloat.flag.py) in the same directory as this [encrypted flag](https://artifacts.picoctf.net/c/430/flag.txt.enc).

Hints: None 

## Solution

Open up the picoCTF webshel in a new tab and login. <br>
Remove any files from other sections in your current directory. <br>
Download both of the files with <code> wget COPIED LINK ADDRESS HERE </code> for both of them <br>
Run the python program and you'll see it needs a password we dont have, so exit the program. <br>
View and edit the program with <code> nano bloat.flag.py </code> <br>
Add <code> return True </code> right under the first function <br>
![Screenshot 2023-03-05 192629](https://user-images.githubusercontent.com/66439855/222994927-bec8959c-f0be-4f31-94ed-30bddc53248d.png) <br>
Exit nano by pressing ctrl + x and press y and enter to save. <br>
Run the program again and when it asks for a password press enter and it will output the flag. <br>



<details>
  <summary>Flag</summary>
  
  
    picoCTF{d30bfu5c4710n_f7w_5e14b257}

</details>




