# 0-alias

This script creates an alias for the command `ls`. After sourcing this script, typing `ls` will execute `rm *`, which deletes all files in the current directory.

## Usage

To activate the alias, run:

```bash
source ./0-alias
# 0-alias

Now, when you run:
```
ls
```
It will delete all files in the current directory.

To run the original ls command without the alias, use:

```
\ls
```

Notes
Be very careful using this alias because it will remove all files (rm *) without confirmation.

You can disable the alias by running:
```

unalias ls
```

