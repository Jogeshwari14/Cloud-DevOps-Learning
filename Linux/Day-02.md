# Linux Day 02 File and Directory Management

## How to Create a File    

                                                 How to Create File
                                      ___________________|____________________
                                      |           |              |            |
                                     cat         touch          vi/vm        nano

### 1. `cat`

**Purpose:** Create a file and display file contents.

**Syntax:**

```bash
cat > filename
```

**Example:**

```bash
cat > test.txt
```

---

### 2. `touch`

**Purpose:** Create an empty file.

**Syntax:**

```bash
touch filename
```

**Example:**

```bash
touch test.txt
```

---

### 3. `vi / vim`

**Purpose:** Create and edit a file using the Vi/Vim text editor.

**Example:**

```bash
vi test.txt
```

---

### 4. `nano`

**Purpose:** Create and edit a file using the Nano text editor.

**Example:**

```bash
nano test.txt
```

---

## Directory Management

### 5. `mkdir`

**Purpose:** Create a directory.

```bash
mkdir directory_name
```

**Example:**

```bash
mkdir devops
```

### 6. `mkdir -p`

**Purpose:** Create parent directories along with the required directory.

```bash
mkdir -p parent/child
```

### 7. `mkdir -v`

**Purpose:** Display a message for each directory created.

```bash
mkdir -v devops
```

### 8. `mkdir -rp`

**Purpose:** Create directories recursively and remove them recursively when used with `rm`.

> Note: `mkdir -rp` is valid, but `-r` has no meaningful effect for `mkdir`. Usually use `mkdir -p`.

---

## Copy

### 9. `cp`

**Purpose:** Copy files or directories.

```bash
cp source destination
```

**Example:**

```bash
cp file1.txt file2.txt
```

---

## Cut and Paste

Linux does not have a single `cut` command that works exactly like Windows cut-and-paste.

To move a file from one location to another, use:

```bash
mv source destination
```

---

## Move / Rename

### 10. `mv`

**Purpose:** Move or rename files and directories.

**Rename:**

```bash
mv oldname.txt newname.txt
```

**Move:**

```bash
mv file.txt /home/user/Documents/
```

---

## Remove

### 11. `rm -rf`

**Purpose:** Remove directories and their contents recursively and forcefully.

```bash
rm -rf directory_name
```

⚠️ Use this command carefully because it can permanently delete files and directories.

---

### 12. `rm -r`

**Purpose:** Remove a directory and its contents recursively.

```bash
rm -r directory_name
```

---

## Listing Files and Directories

### 13. `ls`

**Purpose:** List files and directories.

```bash
ls
```

### 14. `ls -l`

**Purpose:** Display files and directories in long/list format with details such as permissions, ownership, size, and modification time.

```bash
ls -l
```

### 15. `ls -a`

**Purpose:** Display all files and directories, including hidden files.

```bash
ls -a
```

### 16. `ll`

**Purpose:** Common shell alias for a long listing, often equivalent to:

```bash
ls -l
```

> `ll` is an alias in many Linux distributions, but it is not a standard Linux command everywhere.

---

## Change Directory

### 17. `cd`

**Purpose:** Change the current working directory.

```bash
cd directory_name
```

**Example:**

```bash
cd devops
```

### 18. `cd ..`

**Purpose:** Move to the parent directory.

```bash
cd ..
```

### 19. `cd .`

**Purpose:** Refer to the current directory.

```bash
cd .
```

---

## Key Takeaway

Today I learned how to:

* Create and edit files
* Create and manage directories
* Copy, move, and rename files
* Remove files and directories
* List files and directories
* Navigate between directories

         
