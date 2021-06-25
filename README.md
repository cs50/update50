# Update50

A `bash` script that replaces `.devcontainer` in the current working directory with the from a repository hosted on GitHub.com.

## Usage

From a CS50 Codespace:

```
$ update50 --help
update50 ASSIGNMENT

Example:
  update50 classroom50/hello

$ update50 classroom50/hello
Updating ...
Success!
Click "Rebuild now" on bottom-right or press Ctrl (or Cmd) + Shift + P, search for "Rebuild Container" and click "Rebuild" to get the latest updates.
```

From the default Codespace:

```
$ curl https://raw.githubusercontent.com/cs50/update50/main/update50 | bash -s ASSIGNMENT
Updating ...
Success!
Click "Rebuild now" on bottom-right or press Ctrl (or Cmd) + Shift + P, search for "Rebuild Container" and click "Rebuild" to get the latest updates.
```
