## Description

Another program, but this time, it seems to want some input. What happens if you try to run it on the command line with input "Hello!"?
Download the program [here](https://artifacts.picoctf.net/c/353/run).

Hint: Try running it and add the phrase "Hello!" with a space in front (i.e. "./run Hello!")

## Solution

Open up the pico ctf webshell in a new tab and login. <br>
type <code>rm run</code> to remove the old run file. <br>
type <code>wget https://artifacts.picoctf.net/c/353/run</code> to get the new run file. <br>
Like last time type <code>chmod +x run</code> to make the file executable. <br>
Now type <code>./run Hello!</code> and you should get your flag. <br>

<details>
  <summary>Flag</summary>
  
  
    picoCTF{F1r57_4rgum3n7_f65ed63e}

</details>
