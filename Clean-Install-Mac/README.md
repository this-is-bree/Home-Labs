# macOS Clean Install: 2017 MacBook Air

This documentation outlines the process of performing a clean factory reset and OS reinstallation on a 13-inch MacBook Air (2017). This procedure was executed to optimize system performance and prepare the hardware for a dedicated virtualization environment.

## 🛠 Hardware Profile
* **Model:** MacBook Air (13-inch, 2017)
* **Processor:** Intel Core i5/i7 (Dual-Core)
* **Memory:** 8GB RAM
* **Storage:** 500GB SSD

## 📋 Methodology
A clean install involves the complete erasure of the internal SSD and a fresh installation of the operating system via macOS Recovery. This removes accumulated system bloat, clears fragmented files, and ensures a stable foundation for technical projects.

---

## 🚀 Step-by-Step Implementation

### 1. Data Sanitization & Backup
Before initialization, all critical data was migrated to external storage. Local hardware encryption (FileVault) was verified to ensure data security during the transition.

### 2. Booting into Recovery Mode
The system was powered down and restarted while holding **Command (⌘) + R**. This triggered the macOS Recovery partition, bypassing the local OS to access system utilities.

> *[Insert photo: MacBook Air booting into macOS Utilities menu]*

### 3. Disk Partitioning and Formatting
Using **Disk Utility**, the primary drive was wiped to ensure no residual data remained.
* **Drive Selected:** Macintosh HD
* **Format:** APFS (Apple File System)
* **Scheme:** GUID Partition Map

> *[Insert photo: Disk Utility configuration with APFS selected]*

### 4. macOS Reinstallation
The "Reinstall macOS" utility was executed. This process downloads a clean image from Apple’s servers and installs a verified version of the operating system.

> *[Insert photo: The 'Install macOS' progress screen]*

### 5. Final Provisioning
Once the installation was complete, the system was configured with a minimal footprint:
* Standard user account creation.
* Disabled unnecessary telemetry and background indexing.
* Updated to the latest security patches.

---

## 📉 Results
* **Storage Recovery:** Restored full capacity of the 500GB SSD.
* **Performance:** Reduced idle RAM usage, providing a larger buffer for resource-intensive applications.
* **System Stability:** Established a "clean slate" for future homelab and virtualization deployments.

---
