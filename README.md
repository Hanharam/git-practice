### **Three Staes in Git**
1. **Modified**: Working Directory
2. **Staged**: Staging Area
3. **Committed**: Git Directory (Repository)

---

### git rm
Removing files from repository.

---
### git log
Check all dommit history. (SHA-1 checksum)

---

### git reset HEAD <file>
Unstaging a staged file.

---
#### git restore --staged<file>
Unstaging a staged file.

warning: this command discards changes you made.

---

#### git restore<file>
Unmodfying a modified file (discarding changes)

warning: this command discards changes you made.
 
---

#### git rm –cached [file_name]

Unstaging a file.

---

#### nano .gitignore
Ignoring a file.

```sh
Ignore all .a files: *.a
But do track lib.a, even though you're ignoring .a files above:  !lib.a
Only ignore the TODO file in the current directory, not subdir/TODO:  /TODO
Ignore all files in any directory named build:  build/
Ignore doc/notes.txt, but not doc/server/arch.txt:  doc/*.txt
Ignore all .pdf files in the doc/directory and any of its subdirextories:  doc/**/*.pdf
```

---

#### git commit -m "commit message"
Commit.

---

#### git branch -m used_name new_name
Change branch name.
