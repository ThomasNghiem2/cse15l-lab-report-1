## cd
* No arguments <br>
![Image](cd-no-argument.png) <br>
The working directory is `/home/lecture1`. Using this command while in this directory functioned to exit out, bringing the working directory to become `/home`. So, it seems that if we are in a working directory outside of `/home`, `cd` without an argument changes to `/home`. This is not an error. <d>
* Directory path <br>
![Image](cd-directory-path.png) <br>
The working directory is `/home`. This command changed our working directory to become `/home/lecture1`, as seen with how it now states `[user@sahara ~ /lecture1`]. So the directory argument changes the working directory to that of the argument. This is not an error. <br>
* File path <br>
![Image](cd-file-path.png) <br>
The working directory is `/home/lecture1`. This command with a file returned an error. This is because the command in meant to use to change directories, meaning that we can not use it to change our directory to be a file. As such, the terminal prints out that the error that `README` is not a directory. <br>
## ls
* No arguments <br>
![Image](ls-no-argument.png) <br>
The working directory is `/home`. This command gave a list of two folders within our working directory, which included `'Lab 1'` and `lecture1`. These are the two folders that we can access from the `/home` working directory. This is not an error. <d>
* Directory path <br>
![Image](ls-directory-path.png) <br>
The working directory is `/home`. This command displayed the files and folders within the `lecture1` directory. So, it acts as a list to see the names of all files and folders within the directory. This is not an error. <br>
* File path <br>
![Image](ls-file-path.png) <br>
The working directory is `/home/lecture1`. This command with a file returned an error. This is because the command in meant to use to change directories, meaning that we can not use it to change our directory to be a file. As such, the terminal prints out that the error that `README` is not a directory. <br>

