# Linux Basic Commands Lab I

## Objective
Learn and demonstrate essential Linux commands used daily in IT support roles.

## Commands Covered
- pwd
- ls
- cd
- mkdir
- touch
- cat
- less
- cp
- rm

## Lab Steps

## Command 1: pwd

### Purpose
Displays the full path of the current working directory.

### Command Used
```bash
pwd
```

### Explanation
This command confirms the directory I am currently working in.
In IT support, this helps prevent accidental changes to system directories
and ensures commands are run in the correct location.

## Command 2: ls

### Purpose
Lists files and directories in the current location.
Include permission structure with the '-l' flag and hidden files and directories with the '-a' flag.

### Commands Used
```bash
ls
ls -l
ls -la
```

### Explanation
- ls displays visible files and folders
- ls -l shows detailed information such as permissions, ownership, and size
- ls -la includes hidden files and directories

### IT Support Relevance
The ls command is commonly used to:
- Verify the presence of files or folders
- Check permissions during access issues
- Identify hidden configuration files

## Command 3: cd

### Purpose
Changes the current working directory.

### Commands Used
```bash
cd Documents
cd ..
cd ~
```

### Explanation
- cd 'directory' moves into a specified directory
- cd .. moves up one directory level
- cd ~ returns to the user’s home directory

### IT Support Relevance
The cd command is essential for:
- Navigating system directories
- Accessing configuration and log locations
- Avoiding mistakes by confirming the correct working path

## Command 4: mkdir

### Purpose
Creates directories in the filesystem.

### Commands Used
```bash
mkdir linux_basics_lab
mkdir logs
mkdir -p tickets/closed
```

### Explanation
- mkdir creates a single directory
- mkdir -p creates parent and child directories in one command

### IT Support Relevance
The mkdir command is used to:
- Organise user files
- Create log or ticket directories
- Prepare folder structures for applications and scripts

## Command 5: touch

### Purpose
Creates empty files or updates file timestamps.

### Commands Used
```bash
touch system_check.txt
touch notes.txt report.txt
```

### Explanation
- touch creates empty files if they do not exist
- If the file exists, it updates the modification time

### IT Support Relevance
The touch command is used to:
- Create log or note files
- Test file permissions
- Prepare configuration files before editing

## Command 6: cat

### Purpose
Displays the contents of a file.

### Commands Used
```bash
cat system_check.txt
echo "System check completed successfully" > system_check.txt
echo "No errors detected" >> system_check.txt
```
### Explanation
- cat outputs file contents to the terminal
- ">" writes content and overwrites the file
- ">>" appends content to the file

### IT Support Relevance
The cat command is commonly used to:
- View log and configuration files
- Confirm file contents during troubleshooting
- Quickly verify system output

## Command 7: less

### Purpose
Safely views the contents of a file one screen at a time.

### Commands Used
```bash
less system_check.txt
less /etc/os-release
```

### Explanation
The less command opens a file in an interactive viewer, allowing scrolling without loading the entire file at once.
This is safer and more efficient than using cat, especially for large files.

### IT Support Relevance
- Used to view large log and configuration files safely
- Prevents terminal overload during troubleshooting
- Commonly used on remote systems via SSH

  ## Command 8: cp

### Purpose
Copies files and directories from one location to another.

### Commands Used
```bash
cp system_check.txt logs/
cp system_check.txt system_check_backup.txt
cp -r tickets tickets_backup
```

### Explanation
The cp command creates a duplicate of a file or directory.
By default, it copies files, while the -r option is required to copy directories recursively.
This command is commonly used to create backups or preserve original files before making changes.

### IT Support Relevance
- Used to back up configuration files before editing
- Helps preserve logs and user data during troubleshooting
- Essential when testing changes without risking original files

## Command 10: rm

### Purpose
Removes files and directories from the filesystem.

### Commands Used
```bash
rm support_notes.txt
rm system_check_backup.txt
rm -r tickets_backup
rm -i report.txt
```

### Explanation
The rm command permanently deletes files and directories.
By default, deleted items are not recoverable.
The -r option is required to remove directories and their contents recursively.
The -i option prompts for confirmation before deletion, helping prevent accidental data loss.

### IT Support Relevance
- Used to remove temporary, duplicate, or obsolete files
- Helps clean up log files after troubleshooting
- The -i option is commonly used to avoid accidental deletion of important data


