# Task 2: Execute Basic Linux Commands

## Description
Execute basic Linux commands to manipulate files and directories, with an emphasis on understanding their usage. This task includes listing files, creating and deleting directories, changing directories, and more.

## Instructions and Commands

1. **List Files and Directories**
    - **ls**: List the files and directories in the current directory.
    ```sh
    ls
    ```
    ![Screenshot (14)](https://github.com/manish-g0u74m/celebaltech-inturn/assets/148465299/1dd8fe4c-63c1-40a7-97aa-915d6501e63d)

    - **ls -l**: List files and directories with detailed information.
    ```sh
    ls -l
    ```
    ![Screenshot (15)](https://github.com/manish-g0u74m/celebaltech-inturn/assets/148465299/50de1334-a263-45bc-bb1e-59c04cac49c0)
   
    - **ls -a**: List all files, including hidden files (those starting with a dot).
    ```sh
    ls -a
    ```
    ![Screenshot (17)](https://github.com/manish-g0u74m/celebaltech-inturn/assets/148465299/bf1c4e5c-6855-414c-a63b-b59a42186547)
   
    - **ls -la**: Combine detailed and hidden file listing.
    ```sh
    ls -la
    ```
    ![Screenshot (29)](https://github.com/manish-g0u74m/celebaltech-inturn/assets/148465299/2daa74c2-1de6-4a53-81c9-8afdbbaff2c5)
   

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

2. **Make Directory**
    - **mkdir new_directory**: Create a new directory.
    ```sh
    mkdir new_directory
    ```
    - **mkdir -p parent_directory/new_directory**: Create nested directories with a single command.
    ```sh
    mkdir -p parent_directory/new_directory
    ```

3. **Remove Directory**
    - **rmdir directory_name**: Remove an empty directory.
    ```sh
    rmdir directory_name
    ```
    - **rm -r directory_name**: Remove a directory and its contents recursively.
    ```sh
    rm -r directory_name
    ```

4. **Create a File**
    - **touch newfile.txt**: Create a new, empty file.
    ```sh
    touch newfile.txt
    ```

5. **Remove a File**
    - **rm filename**: Remove a file.
    ```sh
    rm filename
    ```

6. **Move/Rename a File or Directory**
    - **mv old_name new_name**: Rename a file or directory.
    ```sh
    mv old_name new_name
    ```
    - **mv filename /path/to/destination**: Move a file to a different directory.
    ```sh
    mv filename /path/to/destination
    ```

7. **Copy a File or Directory**
    - **cp filename /path/to/destination**: Copy a file to a different directory.
    ```sh
    cp filename /path/to/destination
    ```
    - **cp -r source_directory /path/to/destination**: Copy a directory and its contents recursively.
    ```sh
    cp -r source_directory /path/to/destination
    ```

8. **Display File Contents**
    - **cat > filename**: Add Content in a file.
    ```sh
    cat > filename
    ```
     - **cat filename**: Display the contents of a file.
    ```sh
    cat filename
    ```

9. **Print Working Directory**
    - **pwd**: Display the current directory.
    ```sh
    pwd
    ```

## Resources
- [Red Hat: Create and Delete Files and Directories in Linux](https://www.redhat.com/sysadmin/create-delete-files-directories-linux)

    




