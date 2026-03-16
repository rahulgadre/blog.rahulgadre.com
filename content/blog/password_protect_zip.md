---
title: How to Password Protect a Zip File on Mac
date: 2026-02-05T14:30:00.000Z
tags: ["Mac", "Terminal", "Tips"]
description: A quick guide on how to password protect a zip file on Mac using Terminal
---

# How to Password Protect a Zip File on Mac

Today, I had a "Today I Learned" moment — I learned how to password protect a zip file on Mac using Terminal.

Password protecting an Excel sheet or a zip file on Windows is straightforward, but on Mac? Not so much. Fortunately, Mac's built-in Terminal makes it simple with just a single command.

## Steps

### Step 1: Open Terminal

Open **Terminal** and navigate to the directory where the file you want to zip is located.

```bash
cd /path/to/your/file
```

### Step 2: Run the Zip Command

Run the following command to create a password-protected zip file:

```bash
zip -e [name-of-new-zip-file].zip [original-file-name]
```

**Example:**

```bash
zip -e zipfilename.zip yourfilename.xlsx
```

### Step 3: Set the Password

Press **Enter**. Terminal will prompt you to set and verify a password for the zip file.

```bash
Enter password:
Verify password:
```
**Note:** Once the password is set and verified, the password-protected zip file will be created in the same directory as the original file.

