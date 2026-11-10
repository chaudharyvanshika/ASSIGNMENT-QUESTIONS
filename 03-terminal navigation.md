# Assignment 3 – Terminal Navigation Practice Sheet

## Objective
To practise basic terminal commands for navigating folders, creating files, copying, renaming, deleting, and viewing files.

## Commands Practised

| # | Task | Command |
| 1 | Show current folder | `pwd` |
| 2 | List files | `ls` |
| 3 | List hidden files with details | `ls -Force` |
| 4 | Create a folder | `mkdir practice` |
| 5 | Enter the folder | `cd practice` |
| 6 | Create an empty file | `ni index.html` |
| 7 | Create nested folders | `mkdir css/images` |
| 8 | Go up one level | `cd ..` |
| 9 | Go to home directory | `cd ~` |
| 10 | Copy a file | `cp index.html backup.html` |
| 11 | Rename a file | `mv backup.html old.html` |
| 12 | Delete a file | `rm old.html` |
| 13 | Delete a folder | `rm -r css` |
| 14 | Print file contents | `cat index.html` |
| 15 | Clear the screen | `cls` |
| 16 | Open folder in VS Code | `code .` |

## Practice Exercise

Starting from the home directory, I created the following structure:

text
website/
├── index.html
├── css/
│   └── style.css
└── images/


### Commands Used

powershell
cd ~
mkdir website
mkdir website/css
mkdir website/images
ni website/index.html
ni website/css/style.css
cd website
cd css
cd ..
ls -R
mv index.html home.html
mv home.html index.html


### Result

I successfully practised terminal navigation, folder creation, file creation, listing, and renaming commands. I also opened the website folder in Visual Studio Code.