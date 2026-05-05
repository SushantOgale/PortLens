#  PortLens

**PortLens** is a multi-threaded TCP port scanner with a modern GUI that helps visualize open ports and identify potential network exposure.

It combines fast scanning with a clean dashboard interface and a simple risk analysis system to highlight critical services.

---

## 📌 Features

*  Scan **Top Ports** or full range **(0–65535)**
*  Multi-threaded TCP scanning for faster performance
*  Modern **GUI dashboard (Tkinter-based)**
*  Real-time **progress bar and percentage tracking**
*  Structured results table (Port | Service | Risk)
*  Lightweight **risk analysis system**
*  **Stop Scan button** with confirmation prompt
*  Final **Risk Score summary**

---

##  Interface Overview

* Dark-themed, clean dashboard UI
* Real-time scan progress updates
* Table-based output for clarity
* Risk-based classification of open ports

---

## 🛠️ Tech Stack

* **Python 3**
* `socket` – TCP communication
* `threading` – background execution
* `concurrent.futures` – multi-threading
* `tkinter` – GUI development

---

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/SushantOgale/PortLens.git
cd PortLens
```

### 2. Run the application

```bash
python portlens.py
```

---

##  Usage

1. Enter a **target IP address or domain**
2. Click:

   * **Top Ports** → quick scan of commonly used ports
   * **Full Scan** → scans entire range (0–65535)
3. View results in the table
4. Monitor progress and status in real time
5. Check final **risk score summary**
6. Use **Stop button** to safely interrupt scanning

---

## ⚠️ Disclaimer

This tool is intended for:

* Educational use
* Personal labs
* Authorized testing environments

Do **not** scan systems without proper permission.

---

##  Limitations

* Uses TCP Connect scanning (not stealth)
* Results may vary due to:

  * firewalls
  * network latency
  * filtered ports
* Full scan may take several minutes depending on the network

---

##  Future Improvements

*  Data visualization (charts / graphs)
*  Export reports (PDF / JSON)
*  Service detection (banner grabbing)
*  IP intelligence (geo-location, ISP info)
*  Pause / Resume scanning

---

## 👨‍💻 Author

**Sushant Ogale**
Cyber Security Enthusiast

---

##  Support

If you found this project useful, consider giving it a ⭐ on GitHub!





