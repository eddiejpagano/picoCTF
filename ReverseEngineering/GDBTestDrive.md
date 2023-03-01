## Description

Can you get the flag?
Download this [binary](https://artifacts.picoctf.net/c/117/gdbme).
Here's the test drive instructions:

<code>$ chmod +x gdbme</code> <br>
<code>$ gdb gdbme</code> <br>
<code>(gdb) layout asm</code> <br>
<code>(gdb) break *(main+99)</code> <br>
<code>(gdb) run</code> <br>
<code>(gdb) jump *(main+104)</code> <br>

Hint: None

## Solution

Oopen up the pico ctf webshell in a new tab and login. <br>
Then just copy the instuctions given to you in the description. <br>

<details>
  <summary>Flag</summary>
  
  
    picoCTF{d3bugg3r_dr1v3_7776d758}
</details>
