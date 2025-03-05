# FileSys - Simple Java File System

## Overview
FileSys is a simple file system implemented in Java. It allows users to create, manage, and manipulate files and directories in a structured way, similar to a terminal-based file system.

## Features
- Create and remove files
- Read file content
- Navigate directories
- Simple command-line interface

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/FileSys.git
   ```
2. Navigate to the project directory:
   ```sh
   cd FileSys
   ```
3. Compile the Java file:
   ```sh
   javac FileSys.java
   ```

## Usage
Run the program using:
```sh
java FileSys
```

### Available Commands
- `create <filename>` - Creates a new file
- `cat <filename>` - Reads the content of a file
- `rm <filename>` - Removes a file
- `mkdir <dirname>` - Creates a new directory
- `cd <dirname>` - Changes to a specified directory
- `ls` - Lists files and directories
- `pwd` - Displays the current directory

## Example
```sh
Enter prompt> mkdir projects
Enter prompt> cd projects
Enter prompt> create file1.txt
Enter prompt> cat file1.txt
(file contents appear)
Enter prompt> ls
file1.txt
```

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License
This project is open-source and available under the MIT License.
