## Chapter 3: Basic Commands in Linux

In this chapter, we will explore some fundamental commands in Linux. These commands are essential for navigating the file system, managing files, and interacting with the system environment.

### 1. \`ls\`

The \`ls\` command lists directory contents. It shows files and directories in the current working directory.

Example:
\`\`\`bash
ls
\`\`\`

### 2. \`cd\`

The \`cd\` command changes the current directory. You can navigate to a specific directory by providing its path.

Example:
\`\`\`bash
cd /home/user/documents
\`\`\`

### 3. \`pwd\`

The \`pwd\` command prints the current working directory. It displays the path of the directory you are currently in.

Example:
\`\`\`bash
pwd
\`\`\`

### 4. \`mkdir\`

The \`mkdir\` command creates a new directory. You specify the name of the directory you want to create.

Example:
\`\`\`bash
mkdir new_directory
\`\`\`

### 5. \`rmdir\`

The \`rmdir\` command removes an empty directory. It deletes the specified directory if it is empty.

Example:
\`\`\`bash
rmdir empty_directory
\`\`\`

### 6. \`rm\`

The \`rm\` command removes files and directories. Use with caution, as it deletes files permanently.

Example (remove a file):
\`\`\`bash
rm file.txt
\`\`\`

Example (remove a directory and its contents):
\`\`\`bash
rm -r directory_to_delete
\`\`\`

### 7. \`cp\`

The \`cp\` command copies files and directories from one location to another.

Example (copy a file):
\`\`\`bash
cp file.txt /path/to/destination
\`\`\`

Example (copy a directory and its contents):
\`\`\`bash
cp -r directory_to_copy /path/to/destination
\`\`\`

### 8. \`mv\`

The \`mv\` command moves files and directories from one location to another. It can also be used to rename files and directories.

Example (move a file):
\`\`\`bash
mv file.txt /path/to/destination
\`\`\`

Example (rename a file):
\`\`\`bash
mv old_file.txt new_file.txt
\`\`\`

### 9. \`touch\`

The \`touch\` command creates an empty file. It updates the timestamp of an existing file if it already exists.

Example:
\`\`\`bash
touch new_file.txt
\`\`\`

### 10. \`chmod\`

The \`chmod\` command changes the permissions of files and directories.

Example (change permissions for a file):
\`\`\`bash
chmod 644 file.txt
\`\`\`

Example (change permissions for a directory and its contents):
\`\`\`bash
chmod -R 755 directory
\`\`\`

### 11. \`sudo\`

The \`sudo\` command allows users to run programs with the security privileges of another user (commonly the superuser, or root).

Example (update package list using sudo):
\`\`\`bash
sudo apt update
\`\`\`

### Additional Commands

Here are a few more essential commands:

### 12. \`grep\`

The \`grep\` command searches for patterns in files. It's commonly used with pipes to filter output.

Example (search for a pattern in a file):
\`\`\`bash
grep "pattern" file.txt
\`\`\`

### 13. \`find\`

The \`find\` command searches for files in a directory hierarchy based on various criteria.

Example (find all text files in the current directory):
\`\`\`bash
find . -name "*.txt"
\`\`\`

### 14. \`tar\`

The \`tar\` command is used to compress and decompress files in Linux. It can create, view, and extract files from tar archives.

Example (create a tar archive):
\`\`\`bash
tar -cvf archive.tar file1 file2
\`\`\`

Example (extract files from a tar archive):
\`\`\`bash
tar -xvf archive.tar
\`\`\`

### 15. \`wget\`

The \`wget\` command downloads files from the internet using HTTP, HTTPS, or FTP protocols.

Example (download a file):
\`\`\`bash
wget https://example.com/file.txt
\`\`\`

These commands cover a range of tasks from file manipulation to system administration. They are essential for managing and interacting with a Linux system effectively.

## Contributions

We welcome contributions from the community! If you have a useful script, tutorial, or command explanation, please fork the repository, make your changes, and submit a pull request. Together, we can build a valuable resource for Linux users everywhere.
