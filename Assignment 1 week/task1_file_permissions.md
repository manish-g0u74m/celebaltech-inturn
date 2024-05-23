# Task 1: File Permissions

## Description
Create a file, assign permissions (read, write, execute) to different user categories (owner, group, others), and practice changing permissions using `chmod`.

## Instructions
1. **Create a File**
    ```sh
    touch myfile.txt
    ```

2. **Assign Permissions**
    - **Owner**: Read, write, execute
    - **Group**: Read, execute
    - **Others**: Read only

    ```sh
    chmod 754 myfile.txt
    ```

3. **Verify Permissions**
    ```sh
    ls -l myfile.txt
    ```

## Resources
- [YouTube: Understanding File Permissions](https://www.youtube.com/watch?v=iwolPf6kN-k)
- [Pluralsight: Linux File Permissions](https://www.pluralsight.com/blog/it-ops/linux-file-permissions)
