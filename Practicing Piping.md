# Practicing Piping

## Redirecting Output  
- used `echo PWN > COLLEGE` to write PWN in COLLEGE
- ![image](https://github.com/user-attachments/assets/7befef4f-671e-437f-91b9-6f4593b7bd0d)

## Redirecting more Output  
- copied `myflag` to `/challenge/run`   
- `cat myflag` for output   
- ![image](https://github.com/user-attachments/assets/28ae4287-0ed4-4ccf-8d7a-fb1400aaece7)

## Appending Output  
- used `/challenge/run >> /home/hacker/the-flag` to append
- then, `cat /home/hacker/the-flag` to show the output
- ![image](https://github.com/user-attachments/assets/d8c35f2c-4ad0-4cd4-9ae8-e662e0f440b0)

## Redirecting errors  
- used `/challenge/run > myflag 2> instructions` which redirected the output to `myflag`
- used `cat myflag` to display output
- ![image](https://github.com/user-attachments/assets/249b1bf8-8937-46c6-a797-042ed753f23d)

## Redirecting input 
- learnt to redirect using `<`
- used `echo COLLEGE > PWN` to redirect output
- used `/challenge/run < PWN` to redirect input and thus, obtain the flag
- ![image](https://github.com/user-attachments/assets/9b05e03b-0b8a-498e-8187-f5d900bc6d84)

## Grepping stored results  
- to redirect the output of /challenge/run to /tmp/data.txt, we used `/challenge/run > /tmp/data.txt`
- then for grepping used `grep pwn /tmp/data.txt` and obtained the respective flag
- ![image](https://github.com/user-attachments/assets/b0a92cec-3ffb-4276-858f-5039c64c26b8)

## Grepping live output  
- learnt to avoid the need to store result by usin `|` operator
- used ` /challenge/run | grep pwn.college` to find the flag
- ![image](https://github.com/user-attachments/assets/0240aa09-4df4-44ef-bfe0-be173e4f857c)

## Grepping errors  
- can redirect a file descriptor to another file descriptor using `>&`
- therefore, used `/challenge/run 2>& 1|grep pwn.college ` to obatin the flag
- ![image](https://github.com/user-attachments/assets/0cd020ad-2199-4ed4-8174-19d973f3758b)

## Duplicating piped data with tee 
- understood that `tee` command is used to duplicate the data
- intercepted the data via `tee output`
- used ` /challenge/pwn --secret ECjBQqc2 | /challenge/college` for the flag
- ![image](https://github.com/user-attachments/assets/7cc663a7-fe3e-46fe-beaf-7d24a3ba25a0)

## Writing to multiple programs  
- used ` /challenge/hack | tee >(/challenge/the) >(/challenge/planet)`
- ![image](https://github.com/user-attachments/assets/fb3e7a3e-d0d3-46cc-8a6f-291a85b905a4)

## Split-piping stderr and stdout 
-  used `/challenge/hack | tee 2> >(/challenge/the) 1> >(/challenge/planet)` which was wrong, then
-  used `/challenge/hack 2> >(/challenge/the) 1> >(/challenge/planet)` which gave me the flag
-  ![image](https://github.com/user-attachments/assets/92d817cb-9cfe-46a0-90ca-125122ce0550) 








