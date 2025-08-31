# shellgen

**shellgen** is a simple shellcode loader generator written in C.

It does the following:

- Accepts shellcode input in hexadecimal format.
- Generates a `loader.c` file that can execute the provided shellcode.

**Important Safety Notice:**

- This tool is for **educational purposes only** and should only be used in **controlled lab environments** (e.g., virtual machines or sandboxed systems).  
- **Never run untrusted shellcode on your main hardware**, as it can be harmful or destructive.  
- Use this project responsibly and ethically.