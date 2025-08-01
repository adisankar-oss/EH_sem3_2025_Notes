



### 📁 1. Folder Structure

Make sure your folder named `mini-port-scanner` contains the following:

```
mini-port-scanner/
├── mini_port_scanner.sh           # Bash script
├── scan_2025-07-31.log            # Sample output
├── Mini_Port_Scanner_Report.docx  # Word report
└── README.md                      # Project summary (provided below)
```

---

### 📝 2. Create the `README.md`

Inside the `mini-port-scanner` folder, create a file named `README.md` and paste this:

````markdown
# 🛡️ Mini Port Scanner – Cybersecurity Project

This is a simple Bash-based port scanner developed as part of a Cybersecurity Honors Project. It scans the top 1000 TCP ports on a target host and saves the results to a dated log file using `nmap`.

---

## 📜 Project Files

| File | Description |
|------|-------------|
| `mini_port_scanner.sh` | Bash script to perform the scan |
| `scan_2025-07-31.log` | Sample output of a scan |
| `Mini_Port_Scanner_Report.docx` | Full project report in Word format |
| `README.md` | Summary and documentation |

---

## 🔧 How to Use

```bash
chmod +x mini_port_scanner.sh
./mini_port_scanner.sh
````

Then, enter the IP address or domain name when prompted.
Scan results will be saved to a file like `scan_2025-07-31.log`.

---

## 📄 Report

The full report (objectives, code, explanation, and analysis) is available in:

```
Mini_Port_Scanner_Report.docx
```

---

## ⚠️ Disclaimer

> This tool is intended for **educational purposes only**.
> Please do **not scan** any system or network without proper authorization.

---

## 📁 Repository Structure

```
mini-port-scanner/
├── mini_port_scanner.sh
├── scan_2025-07-31.log
├── Mini_Port_Scanner_Report.docx
└── README.md
```

````

---

### 🌐 3. Push to GitHub

1. In your Kali terminal:
   ```bash
   cd path/to/mini-port-scanner
````

2. Initialize git:

   ```bash
   git init
   git add .
   git commit -m "Mini Port Scanner: Bash script, report, and output"
   ```

3. Create the GitHub repo at [github.com/adisankar-oss](https://github.com/adisankar-oss)

   * Click **New**
   * Name it: `mini-port-scanner`
   * Leave it **public**
   * DO NOT initialize with a README (you already have one)

4. Connect to GitHub and push:

   ```bash
   git branch -M main
   git remote add origin https://github.com/adisankar-oss/mini-port-scanner.git
   git push -u origin main
   ```

---

### ✅ Done!

Your GitHub repo will now contain:

* ✔️ Your script
* ✔️ Sample output
* ✔️ Word report
* ✔️ README for public viewing


