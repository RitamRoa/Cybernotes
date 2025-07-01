# CheatSheets/linux-basics.md

# Basic Linux Commands

## File and Directory Management

- **ls**
  - **Description**: Lists files and directories in the current directory.
  - **Usage**: 
    - `ls` 
    - `ls -l` (detailed list)
  - **Tip**: Use `ls -a` to show hidden files.

- **cd**
  - **Description**: Changes the current directory.
  - **Usage**: 
    - `cd /path/to/directory`
    - `cd ..` (go up one directory)
  - **Tip**: Use `cd ~` to go to the home directory.

- **mkdir**
  - **Description**: Creates a new directory.
  - **Usage**: 
    - `mkdir new_directory`
  - **Tip**: Use `mkdir -p /path/to/new_directory` to create parent directories as needed.

## File Manipulation

- **cp**
  - **Description**: Copies files or directories.
  - **Usage**: 
    - `cp source_file destination_file`
    - `cp -r source_directory destination_directory` (for directories)
  - **Tip**: Use `-i` to prompt before overwriting.

- **mv**
  - **Description**: Moves or renames files or directories.
  - **Usage**: 
    - `mv old_name new_name`
    - `mv file /new/path/`
  - **Tip**: Use `-i` to prompt before overwriting.

- **rm**
  - **Description**: Removes files or directories.
  - **Usage**: 
    - `rm file`
    - `rm -r directory` (for directories)
  - **Tip**: Use `-i` to confirm before deletion.

## System Information

- **top**
  - **Description**: Displays real-time system processes.
  - **Usage**: 
    - `top`
  - **Tip**: Press `q` to exit.

- **df**
  - **Description**: Shows disk space usage.
  - **Usage**: 
    - `df -h` (human-readable format)
  - **Tip**: Use `-T` to show filesystem type.

- **free**
  - **Description**: Displays memory usage.
  - **Usage**: 
    - `free -h` (human-readable format)
  - **Tip**: Use `-m` for output in megabytes.

## Networking Commands

- **ping**
  - **Description**: Tests connectivity to a host.
  - **Usage**: 
    - `ping example.com`
  - **Tip**: Use `-c` to limit the number of packets sent (e.g., `ping -c 4 example.com`).

- **ifconfig**
  - **Description**: Displays network interface configuration.
  - **Usage**: 
    - `ifconfig`
  - **Tip**: Use `ip a` for a more modern alternative.

- **netstat**
  - **Description**: Displays network connections and listening ports.
  - **Usage**: 
    - `netstat -tuln`
  - **Tip**: Use `-p` to show the process using the port.

## Conclusion

This cheat sheet provides a quick reference for essential Linux commands that are useful for cybersecurity tasks. Familiarizing yourself with these commands will enhance your efficiency in navigating and managing Linux systems.