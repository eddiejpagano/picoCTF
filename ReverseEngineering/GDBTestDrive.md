## Description

Can you get the flag?
Download this [binary](https://artifacts.picoctf.net/c/117/gdbme).
Here's the test drive instructions:
$ chmod +x gdbme
$ gdb gdbme
(gdb) layout asm
(gdb) break *(main+99)
(gdb) run
(gdb) jump *(main+104)

Hint: None

## Solution

Oopen up the pico ctf webshell in a new tab and login. <br>
Then just copy the instuctions given to you in the description. <br>

<details>
  <summary>Flag</summary>
  
  
    picoCTF{d3bugg3r_dr1v3_7776d758}
</details>
