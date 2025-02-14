# Over the Wire Bandit

## Introduction

This repository has the walkthrough guide to complete the [Bandit](https://overthewire.org/wargames/bandit/) games from OverTheWire.
I will write in the solution of all levels, along with the task.

## Walkthrough Guide

### **1. Level 0 -> Level 1**

```bash
    ls
    cat readme
```
**Password:** ```ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If```

### **2. Level 1 -> Level 2**

```bash
    ls
    cat ./-
```
**Password:** ```263JGJPfgU6LtdEvgfWU1XP5yac29mFx```

### **3. Level 2 -> Level 3**

```bash
    ls
    cat spaces\ in\ this\ filename
```
**Password:** ```MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx```

### **4. Level 3 -> Level 4**

```bash
    ls
    cd inhere/
    ls -a
    cat ...Hiding-From-You
```
**Password:** ```2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ```

### **5. Level 4 -> Level 5**

```bash
    ls
    cd inhere/
    file ./-file0*
    cat ./-file07
```
**Password:** ```4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw```

### **6. Level 5 -> Level 6**

```bash
    ls
    cd inhere/
    find -size 1033c -type f -readable ! -executable

```
**Password:** ```HWasnPhtq9AVKe0dmk45nxy20cvUa6EG```

### **7. Level 6 -> Level 7**

```bash
    cd ../../
    find -user bandit7 -group bandit6 -size 33c 2>/dev/null
    cat ./var/lib/dpkg/info/bandit7.password
```
**Password:** ```morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj```

### **8. Level 7 -> Level 8**

```bash
    ls
    grep millionth data.txt
```
**Password:** ```dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc```

### **9. Level 8 -> Level 9**

```bash
    ls
    cat data.txt | sort | uniq -u
```
**Password:** ```4CKMh1JI91bUIZZPXDqGanal4xvAg0JM```

### **10. Level 9 -> Level 10**

```bash
    ls
    strings data.txt | grep =
```
**Password:** ```FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey```

### **11. Level 10 -> Level 11**

```bash
    ls
    base64 -d data.txt
```
**Password:** ```dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr```

### **12. Level 11 -> Level 12**

```bash
    ls
    cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```
**Password:** ```7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4```
