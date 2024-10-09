# Comprehending Commands    
## cat: not the pet, but the command!
- Learnt the `cat` command which is used for reading out files and it can concatenate multiple files if multiple arguments are provided.
- Started the challenge and entered `cat flag` in the terminal prompt to read out the contents of the flag file, thus obtaining the flag
  ![image](https://github.com/user-attachments/assets/1db03e24-8215-4890-bb18-96159dfbb49d)  
  
## catting absolute paths
- Understood that we can specify cat's arguements as absolute paths.
- Started the challenge and entered `cat /flag` in the terminal prompt where /flag is the absolute path and thus obtained the flag
  <img width="404" alt="image" src="https://github.com/user-attachments/assets/75124c35-1366-41ea-b5b2-3929fef92760">  
  
## more catting practice
- On starting the challenge the absolute path of the flag containing file was shown.
- I used `cat /usr/lib/php/flag` to read out the contents of the flag file thus obtaining the flag
  <img width="543" alt="image" src="https://github.com/user-attachments/assets/454a36ce-fa7d-4190-b987-27a1897ad779">  

## grepping for a needle in a haystack
- I learned the `grep` command and that it can be used to search a file for lines of text containing a specific sequence of characters(string).
- Started the challenge and entered `grep pwn.college /challenge/data.txt` where "pwn.college" is the argument since flags start with "pwn.college" and this obtained the flag  
  <img width="639" alt="image" src="https://github.com/user-attachments/assets/4c85cfea-def5-4e69-a186-96d19dc97c49">  
  
## listing files  
- understood the function of ls which is to read files    
- first read the files in challenge and then opened challenged and execute it  
- ![image](https://github.com/user-attachments/assets/86950c13-0723-4c56-ac5d-a271346c349f)

## touching files
- understood the function of touch     
- touched pwn, college    
- then executed `/challenge/run`     
- ![image](https://github.com/user-attachments/assets/8549335c-bfa0-4275-aa5d-bd93d0dc5443)     

## removing files
- understood the function of rm which is to remove   
- removed delete_me by `rm delete_me`   
- then executed `/challenge/check`     
- ![image](https://github.com/user-attachments/assets/4907f2f3-781d-4259-a3c9-2ea9f691396b)

## hidden files
- understood the concept of hidden files   
- it starts with `.` and thus to display we write `ls -a`   
- ![image](https://github.com/user-attachments/assets/a0fb91c3-d858-4c16-9187-8630cefe221b)

## An Epic Filesystem Quest   
- used `cd` to open   
- `cat` to read   
- `ls` to see files and `ls -a` for hidden files   
- and where `cd` was not allowed I directly used `ls` and then `cat /file/location`

## making directories
- understood the command `mkdir` which is used to create a directory   
- created `pwn` in `tmp` and then created a file using `touch college`    
- ![image](https://github.com/user-attachments/assets/bf7fe639-baba-428f-8abb-1b414504eb1f)

## finding files
- understood the function of `find`    
- used `find -name flag`      
- then tried for each file where permission is given    
- ![image](https://github.com/user-attachments/assets/82102c78-476c-472c-8e35-7ca2b281a8fd)

## linking files
- used `-ln s` and then the file path
- then used `/challenge/catflag` to read out the catflag





  
