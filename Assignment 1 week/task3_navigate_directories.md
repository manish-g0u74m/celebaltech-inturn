# Task 3: Navigating Directories

## Description
Using the terminal, practice navigating through directories, listing file contents, and moving files to different locations. This task helps to build proficiency in managing file systems through the command line.

## Instructions and Commands

1. **Change Directory**
    - **cd directory_name**: Change to the specified directory.
    ```sh
    cd directory_name
    ```
    - **cd ..**: Move up one directory level.
    ```sh
    cd ..
    ```
    - **cd ~**: Change to the home directory.
    ```sh
    cd ~
    ```
    - **cd /path/to/directory**: Change to an absolute path.
    ```sh
    cd /path/to/directory
    ```

2. **List Directory Contents**
    - **ls**: List the files and directories in the current directory.
    ```sh
    ls
    ```
    - **ls -l**: List files and directories with detailed information including permissions, number of links, owner, group, size, and modification date.
    ```sh
    ls -l
    ```
    - **ls -a**: List all files, including hidden files (those starting with a dot).
    ```sh
    ls -a
    ```
    - **ls -la**: Combine detailed and hidden file listing.
    ```sh
    ls -la
    ```
    - **ls -lh**: List files with human-readable file sizes.
    ```sh
    ls -lh
    ```

3. **Move Files**
    - **mv old_name new_name**: Rename a file or directory.
    ```sh
    mv old_name new_name
    ```
    - **mv filename /path/to/destination**: Move a file to a different directory.
    ```sh
    mv filename /path/to/destination
    ```
    - **mv source_directory /path/to/destination**: Move a directory to a different location.
    ```sh
    mv source_directory /path/to/destination
    ```

4. **Copy Files**
    - **cp filename /path/to/destination**: Copy a file to a different directory.
    ```sh
    cp filename /path/to/destination
    ```
    - **cp -r source_directory /path/to/destination**: Copy a directory and its contents recursively.
    ```sh
    cp -r source_directory /path/to/destination
    ```

5. **Remove Files and Directories**
    - **rm filename**: Remove a file.
    ```sh
    rm filename
    ```
    - **rm -r directory_name**: Remove a directory and its contents recursively.
    ```sh
    rm -r directory_name
    ```

6. **Create Files and Directories**
    - **touch newfile.txt**: Create a new, empty file.
    ```sh
    touch newfile.txt
    ```
    - **mkdir new_directory**: Create a new directory.
    ```sh
    mkdir new_directory
    ```

7. **Display File Contents**
    - **cat filename**: Display the contents of a file.
    ```sh
    cat filename
    ```
    - **less filename**: View the contents of a file one screen at a time.
    ```sh
    less filename
    ```
    - **head filename**: Display the first 10 lines of a file.
    ```sh
    head filename
    ```
    - **tail filename**: Display the last 10 lines of a file.
    ```sh
    tail filename
    ```

8. **Print Working Directory**
    - **pwd**: Display the current directory.
    ```sh
    pwd
    ```

9. **Find Files**
    - **find /path/to/search -name filename**: Search for a file by name within a directory.
    ```sh
    find /path/to/search -name filename
    ```

10. **Check Disk Usage**
    - **du -h /path/to/directory**: Display the disk usage of a directory and its contents in a human-readable format.
    ```sh
    du -h /path/to/directory
    ```

## Resources
- [Red Hat: Navigating the Filesystem in Linux Terminal](https://www.redhat.com/sysadmin/navigating-filesystem-linux-terminal)
