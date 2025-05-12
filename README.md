# wipelit   

Wipe files and drives securely with the contents of public domain books.

Because filling hard drives with zeros is really no fun.

```
usage: wipelit.py [-h] [-r] [-n num] [-w] Files [Files ...]

Wipe files/devices with books

positional arguments:
  Files                 Files, Directories, and Devices to wipe

optional arguments:
  -h, --help            show this help message and exit
  -r, --recursive       Recursively parse folders for files to wipe
  -n num, --numrounds num
                        The number of rounds to write the files
  -w, --wipefree        Wipe the free space by creating a large file
```

## TODO

- Refactor original logic
- Remove references to original function of parent project
- Implement safety prompts
- Import libraries to pull books from sources:
    - Project Gutenberg
    - Archive.org
