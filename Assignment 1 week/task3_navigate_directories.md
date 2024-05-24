# Task 3: Navigating Directories

## Description
Using the terminal, practice navigating through directories, listing file contents, and moving files to different locations. This task helps to build proficiency in managing file systems through the command line.

## Instructions and Commands

1. **Change Directory**
    - **cd directory_name**: Change to the specified directory.
    ```sh
    cd directory_name
    ```
    ![Screenshot (30)](https://github.com/manish-g0u74m/celebaltech-inturn/assets/148465299/85ba9d26-f83f-4a6d-9018-1aeeb088998c)
   
    - **cd ..**: Move up one directory level.
    ```sh
    cd ..
    ```
    ![Screenshot (32)](https://github.com/manish-g0u74m/celebaltech-inturn/assets/148465299/37821e99-b705-4e45-84a4-78e24aa34f51)


    - **cd ~**: Change to the home directory.
    ```sh
    cd ~
    ```
    ![Screenshot (33)](https://github.com/manish-g0u74m/celebaltech-inturn/assets/148465299/8e3c7d68-42ff-4647-98e6-585981055b73)
    - **cd /path/to/directory**: Change to an absolute path.
    ```sh
    cd /path/to/directory
    ```

3. **List Directory Contents**
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

4. **Move Files**
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

5. **Copy Files**
    - **cp filename /path/to/destination**: Copy a file to a different directory.
    ```sh
    cp filename /path/to/destination
    ```
    - **cp -r source_directory /path/to/destination**: Copy a directory and its contents recursively.
    ```sh
    cp -r source_directory /path/to/destination
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
    
7. **Remove Files and Directories**
    - **rm filename**: Remove a file.
    ```sh
    rm filename
    ```
    - **rm -r directory_name**: Remove a directory and its contents recursively.
    ```sh
    rm -r directory_name
    ```

8. **Display File Contents**
    - **cat filename**: Display the contents of a file.
    ```sh
    cat filename
    ```
   
    - **head filename**: Display the first 10 lines of a file.
    ```sh
    head filename
    ```
    - **tail filename**: Display the last 10 lines of a file.
    ```sh
    tail filename
    ```

9. **Print Working Directory**
    - **pwd**: Display the current directory.
    ```sh
    pwd
    ```
    ![Screenshot (47)](https://github.com/manish-g0u74m/celebaltech-inturn/assets/148465299/080b2479-418f-4ea9-9122-604a24a61a58)


10. **Find Files**
    - **find /path/to/search -name filename**: Search for a file by name within a directory.
    ```sh
    find /path/to/search -name filename
    ```

11. **Check Disk Usage**
    - **du -h /path/to/directory**: Display the disk usage of a directory and its contents in a human-readable format.
    ```sh
    du -h /path/to/directory
    ```

## Resources
- [Red Hat: Navigating the Filesystem in Linux Terminal](https://www.redhat.com/sysadmin/navigating-filesystem-linux-terminal)
