# Linux Command Repository

Welcome to the Linux Command Repository! This repository serves as a collection of various Linux commands, along with encountered errors and their solutions. Whether you're a beginner or an experienced user, you'll find helpful information here to troubleshoot Linux-related issues.

## Commands

### Navigation

- `cd [directory]`: Change directory.
- `ls [options]`: List directory contents.
- `pwd`: Print the current working directory.
- `mkdir [directory]`: Create a new directory.
- `rmdir [directory]`: Remove a directory.

### File Operations

- `touch [filename]`: Create an empty file.
- `cp [source] [destination]`: Copy files or directories.
- `mv [source] [destination]`: Move or rename files or directories.
- `rm [file]`: Remove files or directories.

### System Information

- `uname [options]`: Print system information.
- `top`: Display Linux processes.
- `df [options]`: Display disk space usage.

### Package Management

- `apt [options]`: Advanced Package Tool for package management.
- `yum [options]`: Yellowdog Updater Modified for package management.
- `dpkg [options]`: Debian package manager.

### Network Operations

- `ping [host]`: Send ICMP echo requests to check network connectivity.
- `ifconfig [options]`: Display or configure network interface parameters.
- `netstat [options]`: Print network connections, routing tables, and interface statistics.

## Error Messages and Solutions

### Error: "Permission denied"

- **Cause**: Lack of permission to access the file or directory.
- **Solution**: Use `sudo` to gain superuser privileges or adjust file permissions using `chmod`.

### Error: "Command not found"

- **Cause**: The command is not available in the current environment or not installed.
- **Solution**: Install the required package using the package manager (`apt`, `yum`, etc.) or check the PATH variable for command availability.

### Error: "No such file or directory"

- **Cause**: The specified file or directory does not exist.
- **Solution**: Double-check the spelling and path of the file or directory.

## Contributing

Contributions are welcome! If you encounter a new command, error, or have a solution to share, feel free to submit a pull request.

## License

This repository is licensed under the [MIT License](LICENSE).
