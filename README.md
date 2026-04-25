````markdown
# BurpSuite Installer

Cross-platform installer for downloading and launching BurpSuite tools.

---

## Requirements

Before installing, make sure the following are installed:

- **Git**
- **Java** (`java` available in terminal)

### Check Installed Versions

```bash
java -version
git --version
````

---

## Installation Commands

### Windows (PowerShell)

```powershell
git clone https://github.com/sahmsec/burpsuite.git
cd burpsuite
java -jar burpsuite-installer.jar
```

### Linux

```bash
git clone https://github.com/sahmsec/burpsuite.git
cd burpsuite
java -jar burpsuite-installer.jar
```

### macOS

```bash
git clone https://github.com/sahmsec/burpsuite.git
cd burpsuite
java -jar burpsuite-installer.jar
```

---

## What Happens Automatically

After running the installation commands:

* Repository is cloned
* Installer launches
* `BurpTools/` folder is created
* Latest Burp Suite JAR is downloaded
* Additional repository assets are downloaded

---

## Output Example

```bash
BurpTools/
├── burpsuite_pro_vXXXX.jar
└── tool.jar
```

---

## Manual Run (If Already Cloned)

```bash
cd burpsuite
java -jar burpsuite-installer.jar
```

---

## Update Existing Repo

```bash
cd burpsuite
git pull
java -jar burpsuite-installer.jar
```

---

## Troubleshooting

### Java not found

Install Java and retry.

### Git not found

Install Git and retry.

### Permission denied (Linux/macOS)

```bash
sudo java -jar burpsuite-installer.jar
```

> Use `sudo` only if required.

```
```
