<h1>Day1</h1>
<h2>Linux Commands</h2>
<img src="https://github.com/itsOmSarraf/Daily-Learning/blob/main/resources/png-clipart-penguin-linux-tux-computer-software-svg-gallery-computer-vertebrate-removebg-preview.png" width="128"/>

From Kunal's [video](https://youtu.be/iwolPf6kN-k).

check " man command_name " to get more filtrs of the commands 

|    Command   |    Function   |
|    :----:   |    :----:   |
| pwd | present working directory |
| ls | list |
| open.. | open last directory |
| ls -a | hidden files |
| . | current directory |
| .. | previous directory |
| ls -l | details of the files ; ' l ' stands for long details |
| ls -a -l | details of hiddens files as well |
| cd | change directory |
| open . | opens current directory |
| mkdir directory_name | makes a directory |
| ls -R | lists all files in sub-directory |
| cat | concatenate (list all contenets of the file) |
| cat file1 file2 > file3 | all data is merged into file3, > represents redirection |
| echo | echoes the text |
| echo "text goes here" file_name | content is written into the file |
| man command_name | details about the command |
| cat file1 \| tr a-z A-Z > file2 | performs tasks(here translate lower-case to upper-case) on the files contents, pipe(output for the 1st command, acts as input for 2nd command) |
| use \ | for chaining commands |
| touch filename | create files |
| cp file1 file2 | cop file1 as file2 |
| mv director2 or file1 directory_2 or file2 | moves the file to new directory or renames the file |
| mv file1 ../file2 | renames the file 1 as file2 and changes the final location as well |
| rm file1 | removes file1 permanently and not in the bin |
| cp -R directory1 directory2 | directory1 is copied into directory2 |
| rm -R directory1 | deletes the directory |
| rm -f file | deleted the file forecully even if it open, etc |
| sudo command | Super User DO, for admin permissions |
| df | free disk space |
| du | disk usage stats |
| head -n file1 | display the first part of the file ( enter number of lines after n ) |
| tail -n file1 | display the last part of the file ( enter number of lines after n ) |
| diff file1 file2 | compares the content of both the files line by line and outputs the lines that don't match |
| locate "x.txt" | finds all txt files or whatver criteria in the " " |
| find -type | search for files in a directory of a particular type |
| chmod =rwx,g=rx,o=r file1 | change file permissions: 3 types : Read(r)=4 , Write(w)=2 , Execute(x)=1 ; 
3 types of people who use computer : User(u) , Group(g) , Others(o) |
| whoami | prints user id |
| sudo chown root file1 | change root permissions of file |
| grep "what to search" file1 | to search something in files |
| 