# File Globbing

## Matching with *
- using * with `cd /ch*` as `*` matches any file name which is prseent  
- then executing `/challenge/run`
- ![image](https://github.com/user-attachments/assets/daa3f582-3b12-4719-ae26-1231dbb152f4)

## Matching with ?
- had to use `?` for single character
- therefore, `cd /?ha??enge`
- ![image](https://github.com/user-attachments/assets/cc6bc6d8-622b-4512-8e83-2b2e8b4849a1)

## Matching with [ ] 
- we use square brackets for a set of single characters
- ![image](https://github.com/user-attachments/assets/c70de843-a579-43c9-809e-d33f0397cc3e)

## Matching paths with [ ]  
- globbing happens on a path basis so that you can expand entire paths with your globbed arguments
- used `challenge/run /challenge/files/file_[bash]`  
- ![image](https://github.com/user-attachments/assets/c95fbda9-b5de-4094-a8c6-d36bed739ab2)

## Mixing globs
- used `cd /challenge/files` to change the directory
- used `/challenge/run [cep]*` to match "challenging", "educational", and "pwning"
- ![image](https://github.com/user-attachments/assets/edbf0dae-ef9f-461e-b213-d05e67fb4772)

## Exclusionary globbing 
- used `cd /challenge/files` to change the directory
- used `/challenge/files$ /challenge/run [!pwn]*` as `!` represents not
- ![image](https://github.com/user-attachments/assets/139aa60a-880b-4a2e-81b0-3c6312eb398e)  





