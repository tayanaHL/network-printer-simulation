# 🖨️ Network Printer Setup + Troubleshooting (Simulated)

This project simulates setting up and troubleshooting a network printer using a fake IP address and manual configuration inside a Windows 10 virtual machine. It’s designed to mimic common Tier 1 printer support scenarios.

---

## 🔧 What This Project Covers

- Manually configuring a TCP/IP printer port
- Adding a printer with a fake network IP
- Manually assigning a generic driver
- Simulating a print issue (e.g. stuck print job)
- Performing basic troubleshooting: pause, cancel queue, resume

---

## 🛠️ Tools Used

- Windows 10 VM (VirtualBox)
- Control Panel > Devices and Printers
- Command Prompt (for `ping` and IP test)
- Printer driver: Generic Text-Only

---

## 🧪 Steps Taken

1. Opened **Printers & Scanners** settings
2. Selected: **The printer that I want isn’t listed**
3. Chose: **Add a printer using a TCP/IP address**
4. Device type: TCP/IP  
   Hostname/IP: `192.168.1.250` (fake IP for simulation)  
   *Unchecked “Query the printer…” to speed up*
5. Installed with a **Generic Text-Only** driver
6. Named the printer `Test Network Printer`

---

## 🛠️ Troubleshooting Simulated:

- Paused the printer
- Attempted to send a test page (got stuck in queue)
- Canceled all documents
- Resumed the printer to simulate “fix”

---

## 💡 What I Learned

- How to add a printer manually by IP
- What happens when a print job gets stuck
- Where to find printer settings and queues
- How to simulate and resolve basic print issues

---

## 🧠 Why It Matters

Printer issues are one of the **most common user tickets** in help desk and Tier 1 IT roles. This project helped me understand the end-to-end flow of adding, configuring, and troubleshooting a network printer manually — even without physical hardware.
