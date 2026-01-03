# OS Project: Virtualization and Hardware Evaluation
**Department:** ITBED  
**Year:** 3rd Year, 2018 E.C.  
**Student Name:** Bekalu Adugna  
**Student ID:** 1600749  

---

## 📁 Repository Contents
This repository contains the following project files:
1. **bekalu adugna.docx**: Complete documentation of the RHEL 9.x installation process.
2. **oprating assignment in excell 1.xlsx**: Detailed evaluation of Haier Mobile hardware.
3. **oprating assignment of excell 2.xlsx**: Detailed evaluation of Fujitsu PC/Server hardware.

---

## 🛠 Part 1: RHEL Operating System Installation
This task involved installing **Red Hat Enterprise Linux (RHEL) 9.x** within a virtual environment using **Oracle VM VirtualBox**.

### 🚀 Objectives
- Demonstrate understanding of OS installation in a controlled virtual environment.
- Apply theoretical concepts (boot process, partitioning, XFS filesystem).
- Develop troubleshooting skills related to enterprise Linux deployment.

### 💻 System Requirements
- **Host Machine:** Intel Core i5 / AMD Ryzen 5 (Virtualization VT-x enabled).
- **Guest VM:** 4096 MB RAM, 20 GB VDI Storage.
- **Software:** Oracle VirtualBox & RHEL 9.x DVD ISO.

### 📝 Key Installation Details
- **Filesystem:** `XFS`. 
  - *Why?* RHEL defaults to XFS because it is a high-performance 64-bit journaling system that handles large files and enterprise scalability better than ext4.
- **User Account:** 
  - **Full Name:** Bekalu Adugna
  - **Username:** ID 1600749
- **Software Selection:** Installed as "Server with GUI" for desktop accessibility.

### 🔧 Issues & Solutions
- **Problem:** Network interface was disconnected by default.  
  **Solution:** Manually enabled "Connect automatically" in the network settings.
- **Problem:** Small screen resolution (800x600).  
  **Solution:** Installed **VirtualBox Guest Additions** to enable dynamic resizing.
- **Problem:** Restricted package installation.  
  **Solution:** Registered for a free **Red Hat Developer Subscription** to enable the subscription-manager.

---

## 📱 Part 2: Haier Mobile Evaluation
**Focus:** Performance, Durability, and Value.

| Category | Evaluation Summary |
| :--- | :--- |
| **Performance** | Entry/Mid-range. Uses MediaTek Helio or older Snapdragon 400 series. |
| **Display** | 720p (HD+) or 1080p (FHD) LCD/IPS at 60Hz. |
| **Camera** | Functional 13MP Main + 2MP Depth; 1080p Video. |
| **Build** | Durable Polycarbonate/Plastic; High drop resistance. |
| **Price/Value** | High value for students and seniors due to affordability. |

---

## 💻 Part 3: Fujitsu PC/Server Evaluation
**Focus:** Business-class Reliability and Engineering.

| Category | Evaluation Summary |
| :--- | :--- |
| **Hardware** | Business Class Intel Core i5/i7 vPro with fast NVMe SSDs. |
| **Portability** | Ultra-light (Lifebook models often under 1kg) using magnesium-alloy. |
| **Durability** | Military Grade (MIL-STD-810H) certified. |
| **Security** | Industry leader featuring **PalmSecure** (vein pattern scanning). |
| **Connectivity** | Excellent legacy support (VGA, HDMI, RJ45) alongside Thunderbolt 4. |

---

## 🎓 Part 4: Theory - Virtualization
### What is it?
Virtualization is technology that allows you to create multiple simulated environments (Virtual Machines) from a single physical hardware system.

### Why use it?
- **Server Consolidation:** Run multiple servers on one machine to save costs.
- **Disaster Recovery:** VMs are files; they can be backed up and moved easily.
- **Isolation:** Provides a safe environment to test OS like RHEL without risking the host machine.

### How does it work?
It uses a **Hypervisor** (like VirtualBox or KVM) which acts as a software layer on top of the physical hardware to allocate CPU, RAM, and Storage to Guest OSs.

---

**Submission Date:** 27/04/2018 E.C.
