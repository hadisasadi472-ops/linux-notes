## 📅 Day 6: Linux File Management & Troubleshooting Challenge

Today, I focused on advanced file and directory operations using the Linux CLI, simulating a real-world corporate website infrastructure layout. I practiced creating clean directory trees, managing backups, and moving legacy files to archives.

### 🛠️ What I Did:
1. **Infrastructure Layout:** Created a structured project directory (`Company-Website`) containing isolated environments for `Website`, `Backup`, `Logs`, and `Archive`.
2. **File Operations:** Practiced data redundancy by copying active web assets (`index.html`, `about.html`) to the `Backup` directory.
3. **Log & Archive Management:** Simulated moving outdated assets (`old-page.html`) to the `Archive` folder using absolute/relative paths.

---

### 🔍 Crucial Troubleshooting Lessons Learned Today:

During the practical session, I encountered and successfully resolved two major system behaviors:

#### 1. The Directory vs. File Trap (`mkdir` vs. `touch`)
* **The Issue:** Using `mkdir` with extensions like `.txt` or `.html` creates **directories**, not files. This led to `cp` omitting the operations because it detected folders instead of regular files.
* **The Solution:** Reinforced the core Linux standard: Use `mkdir` strictly for directories and `touch` for initializing empty files. 

#### 2. Relative Path Pitfalls (`cannot stat` error)
* **The Issue:** Attempting to move a file using a path relative to the root while my terminal was already inside the subdirectory (e.g., trying to run `mv Website/file.html` while inside the `Website` folder).
* **The Solution:** Used `cd ..` to navigate back to the project root before executing the relative path command, ensuring accurate target and destination tracking.

### 📊 Current Workspace Structure:
```text
.
├── Archive
│   └── old-page.html
├── Backup
│   ├── about.html
│   ├── contact.html
│   └── index.html
├── Logs
│   └── 2.txt
└── Website
    ├── about.html
    └── index.html
