## Linux file systems
### Linux File System Structure
Linux organizes files in a hierarchical structure starting from the root directory (`/`).

#### Common Directories

| Directory | Description                      |
|-----------|----------------------------------|
| `/`       | Root directory                   |
| `/home`   | User home directories            |
| `/bin`    | Basic system commands            |
| `/etc`    | Configuration files              |
| `/tmp`    | Temporary files                  |
| `/usr`    | Installed software and libraries |
| `/var`    | Log and variable files           |
| `/dev`    | Device files                     |

#### Example Structure

```text
/
├── home
├── bin
├── etc
├── tmp
├── usr
├── var
└── dev
```
### Current Working Directory
Check your current location:
```bash
pwd
```
### Listing Files and Directories
Basic listing
```bash
ls
```
Long format
```bash
ls -l
```
### Navigating Directories
Change directory
```bash
cd directory_name
```
Go to home directory
```bash
cd
```
Move up one level
```bash
cd ..
```
### Understanding Paths
#### Absolute Path
Starts from root (`/`)
```bash
/home/student/data
```
#### Relative Path
Starts from the current directory
```bash
data/project1
```
### Creating Directories
```bash
mkdir test_folder
```





----
## Basic Linux command line
