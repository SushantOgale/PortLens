# 🚀 PortLens

**PortLens** is a multi-threaded TCP port scanner with a modern GUI that helps visualize open ports and assess potential network exposure.

It combines fast port scanning with a clean dashboard interface and a simple risk analysis system to highlight critical services.

---

## 📌 Features

* 🔍 Scan **Top Ports** or full range **(0–65535)**
* ⚡ Multi-threaded scanning for faster results
* 🖥️ Modern **GUI dashboard (Tkinter)**
* 📊 Real-time **progress bar & status updates**
* 📋 Structured results table (Port, Service, Risk)
* 🧠 Lightweight **risk analysis system**
* 🟥 **Stop Scan button** with confirmation
* 📈 Final **Risk Score summary**

---

## 🖼️ Interface Overview

* Clean dark-themed UI
* Live scanning progress (%)
* Table-based output instead of raw logs
* Risk-based color highlighting

---

## 🛠️ Tech Stack

* **Python 3**
* `socket` – network communication
* `threading` – background execution
* `concurrent.futures` – multi-threading
* `tkinter` – GUI development

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/portlens.git
cd portlens
```

### 2. Run the application

```bash
python portlens.py
```

---

## 🧪 Usage

1. Enter a **target IP or domain**
2. Click:

   * **Top Ports** → fast scan of common ports
   * **Full Scan** → scan all ports (0–65535)
3. View results in the table
4. Check the **risk score summary**
5. Use **Stop button** to safely interrupt scan

---

## ⚠️ Disclaimer

This tool is intended for:

* Educational purposes
* Personal labs
* Authorized environments only

Do **NOT** scan systems without permission.

---

## 💡 Limitations

* Uses TCP Connect scan (not stealth)
* Results may vary due to:

  * firewalls
  * network latency
  * filtered ports
* Full scan may take several minutes

---

## 🚀 Future Improvements

* 📊 Data visualization (charts / graphs)
* 📁 Export reports (PDF / JSON)
* 🔍 Service detection (banner grabbing)
* 🌐 IP intelligence (geo + ISP info)
* 🔄 Pause / Resume scanning

---

## 👨‍💻 Author

**Sushant Ogale**
Cyber Security Enthusiast

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
