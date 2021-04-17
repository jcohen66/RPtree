## RP Tree
Generate a visual tree depiction of a directory structure from the command line.

# Usage
````
python3 tree.py <path to directory> [-d] [-o]

python3 tree.py ../hello
python3 tree.py ../hello -d
python3 tree.py ../hello -o

python3 tree.py -v
python3 tree.py -h
````

# Options
- -v, --version   Show the current version information and exit the application.
- -h, --help      Show help and usage messages.
- -d, --dir-only  Generate a directory-only tree and print it to the screen.
- -o, --output-to-markdown Generate a tree and save it to a file in markdown format.
