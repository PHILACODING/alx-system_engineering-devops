# 🐚 Shell, Permissions & User Management

Welcome to the **Shell Permissions** repository! 🚀 This project covers fundamental Linux/Unix administration concepts, focusing on user management, group memberships, file ownership, and setting permissions using shell commands.

---

## 📚 Directory Structure & Tasks

| Directory / File | Description | Key Commands Used |
| :--- | :--- | :--- |
| 📁 `0x00-shell_basics` | Introduction to essential Shell navigation, directory operations, and basic commands. | `pwd`, `ls`, `cd`, `mkdir` |
| 📁 `0x01-shell_permissions` | Hands-on scripts for managing users, groups, and file ownership permissions. | `chmod`, `chown`, `chgrp`, `su` |

---

## 📂 `0x01-shell_permissions` Scripts Overview

* 👤 **`0-iam_betty`** – Switches the current user context to user `betty`.
* 🆔 **`1-who_am_i`** – Prints the effective username of the current user (`whoami`).
* 👥 **`2-groups`** – Displays all groups the current user belongs to (`groups`).
* 🔑 **`3-new_owner`** – Changes the owner of the file `hello` to user `betty`.
* 📄 **`4-empty`** – Creates an empty file named `hello`.

---

## ⚙️ Environment & Requirements

* **OS:** Ubuntu 20.04 LTS
* **Shell:** Bash (`/bin/bash`)
* All scripts are executable and written to pass standard Shellcheck linter rules.

---

## 🚀 How to Run Scripts

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/PHILACODING/alx-system_engineering-devops.git](https://github.com/PHILACODING/alx-system_engineering-devops.git)
