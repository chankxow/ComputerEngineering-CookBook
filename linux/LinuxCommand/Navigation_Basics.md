# Navigation Basics And Common Command to using terminal

## Basics Command

-   pwd (print working directory): 
  use for check current directory
  
```bash
pwd
```

Result
```bash
/home/user/path <--- your current path
```
this means that are you now at home/user/path 



-   ls (list) : use for check file and folder in your directory
```bash
ls
```

Result may be:
```bash
folder1 folder2 filet.txt python.py
```

-   ls -a : show hiiden folder 
```bash
ls -a
```

Result
```bash
. .. .hiddenfile1 file1.txt
```

-   .   for current directory
-   . .     before directory

-   cd (change Directory):use for change directory or open your folder
```bash
cd path/to/directory
```

Other 
```bash
cd.. <-- back to before
cd ~ <-- back to home directory
```

###  file and directory management 

-  cp : copy file or folder
```bash
cp source destination
```

e.g
```bash
cp file.txt /home/user/Documents/
```

- mv : move or rename file or folder

```bash
mv oldfile.txt newfile.txt
```

- rm : remove file

```bash
rm file.txt
```
  rm -r <directory >: remove folder and file in folder (recursive)

- mkdir

```bash
mkdir newfolder
```

- touch :create empty file 

### System and Management
- sudo : run comman with administration
```bash
sudo command
```
- whoami : show current username
```bash
whoami
```

- chmod : change file acces
```bash
chmod 755 file.txt
```

- chown : change file or folder owner
```bash
sudo chown user:user file.txt
```


