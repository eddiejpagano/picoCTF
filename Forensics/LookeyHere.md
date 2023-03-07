## Description

Attackers have hidden information in a very large mass of data in the past, maybe they are still doing it.
Download the data [here](https://artifacts.picoctf.net/c/296/anthem.flag.txt).

Hint: Download the file and search for the flag based on the known prefix.

## Solution 

Login to your picoCTF webshel and remove any files from previous practices. <br>
Download the file with <code> wget https://artifacts.picoctf.net/c/296/anthem.flag.txt </code> <br>
We will now use grep to search for the text "pico" in the file since the file is so large. <br>
Enter <code> grep pico anthem.flag.txt </code> and you should get your flag. <br>


<details>
  <summary>Flag</summary>
  
  
    picoCTF{gr3p_15_@w3s0m3_2116b979}

</details>


