# 10 Linux Command Lines

- ls: List directory contents. Use it to view the files and directories in the current directory. Example: ls
- cd: Change directory. Use it to navigate between directories. Example: cd Documents 
- pwd: Print working directory. Displays the current directory you're in. Example: pwd
- mkdir: Make directory. Use it to create a new directory. Example: mkdir new_folder
- rm: Remove. Deletes files or directories. Example: rm file.txt . Use rm -rf to forcefully delete. r stands for recursive and f stands for force. to forcefully and recursively delete all files and directories within the specified location without asking for confirmation.
- ssh: Secure shell. Connects to a remote server securely. Example: ssh username@hostname
- df: Disk free. Displays information about disk space usage. Example: df -h. df: Stands for "disk free." -h: This option tells df to display sizes in a human-readable format, such as "K" for kilobytes, "M" for megabytes, "G" for gigabytes, etc. 
- du: Disk usage. Shows the sizes of directories and files. Example: du -sh directory. du: Stands for "disk usage." -s: This option tells du to display only a summary total for each specified directory. 
- top: Displays real-time system resource usage. Example: top 
- history: Displays the list of previously executed commands. Example: history

Shortcuts
Type few characters and press tab to have the complete word
ctrl+alt+T - to open terminal
ctrl+z - to close the running program




# Text Operations Using Commands
1. touch: Create empty files.
 ```
touch file1.txt
   ```
2. cp: Copy files and directories.
```
cp file1.txt file2.txt
```
3. mv: Move or rename files and directories.
```
mv file1.txt directory/
```
```
mv file1.txt new_name.txt
```
4. cat: Concatenate and display files.
```
cat file1.txt
```
5. more: Display files one screen at a time.
```
more file1.txt
   ```
6. less: Display files interactively, with backward navigation.
```
less file1.txt
```
7. head: Output the first part of files.
```
head -n 10 file1.txt
```
8. tail: Output the last part of files.
```
tail -n 5 file1.txt
```
9. find: Search for files and directories.
```
find /path/to/search -name *.txt
```
10. zip: Package and compress files.
```
zip archive.zip file1.txt file2.txt directory/
```    
   
   
   

