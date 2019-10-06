# CLI - Command-Line Interface
Creating, reading, updating, deleting and navigation on the command-line interface

# Creating a folder
1. `mkdir my_folder`
1. `ls` to list all the content of the current working directory

# Change into that folder
1. `cd my_folder` to change the current working directory into the new directory created
1. `cd ../` to change to the previous directory

# Move folder
`mv my_folder /home/<user-name>/Desktop` to move `my_folder` to the `Desktop`

# Rename a folder
`mv my_folder new_folder`

# Copy a folder
`cp -r new_folder my_folder` copies the content of `new_folder` into `my_folder`

# Delete folder
`rmdir new_folder`
`rm -r new_folder` when `new_folder` is not empty

# Creating file
1. `touch my_file`
1. `cat > my_file` then `Ctrl + C` or `Ctrl + D` to create an empty file

# Writing into a file
1. `cat > my_file` + `Enter or Return` - you then type the content of the file, followed by `Ctrl + C` when you are done
`cat >> my_file` to append new content to the old content, without the second `>`, `my_file` will be over written
1. `echo "string data" >> my_file` to write text into `my_file` directly
1. `cat my_file >> some_new_file` to read the content of `my_file` into `some_new_file` and if `some_new_file` does not exist, it will be created

# Copy a file
`cp my_file my_new_file`

# Move file
`mv my_file /home/<user-name>/Desktop/` to move `my_file` to the Desktop

# Rename file
`mv my_file new_file` - Know that if `new_file` is a directory then `my_file` would be moved into `new_file` instead of renaming it

# Delete file
`rm new_file`

# THE END
1. visit [CLI-presentation](https://github.com/Otumian-empire/CLI-presentation) for this slides
1. and I am [Otumian-empire](https://github.com/Otumian-empire), just do `cd ../`
