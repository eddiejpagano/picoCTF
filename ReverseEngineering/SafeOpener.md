## Description

Can you open this safe?
I forgot the key to my safe but this [program](https://artifacts.picoctf.net/c/463/SafeOpener.java) is supposed to help me with retrieving the lost key. Can you help me unlock my safe?
Put the password you recover into the picoCTF flag format like:
picoCTF{password}

Hints: None


## Solution

Open up the picoCTF webshel in a new tab and login. <br>
Remove any other files from other Practice challenges. <br>
To get the file type <code> wget https://artifacts.picoctf.net/c/463/SafeOpener.java </code> <br>
Run the program with <code> java SafeOpener.java </code> <br>
As you can see it needs a password that we dont have, so exit the program. <br>
View the program's code by typing <code> nano SafeOpener.java </code> <br>
In it's code you can see a string that looks like an encoded base64 string. <br>
![Screenshot 2023-03-04 181252](https://user-images.githubusercontent.com/66439855/222932840-ba7ed94d-be5e-4d36-9afc-a2290fa0de53.png) <br>
Open up a new tab in your host computer and find a base64 decoder. *i reccomend https://www.base64decode.org/* and type the string from the file. <br>
Press decode and you should get most of the flag. <br>
Add picoCTF{THE OUTPUT YOU GOT HERE} <br>
And that is the flag. <br>

<details>
  <summary>Flag</summary>
  
  
    picoCTF{pl3as3_l3t_m3_1nt0_th3_saf3}

</details>
