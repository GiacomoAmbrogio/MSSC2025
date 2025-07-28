# 💻 How to Set Up the CRYSTAL Virtual Machine for MSSC 2025

This guide provides step-by-step instructions to set up the **CRYSTAL Virtual Machine** on different operating systems.

---

## 🐧🪟🍎 Linux, Windows, and macOS (Intel-based)

1. 🔽 **[Download and Install VirtualBox](https://www.virtualbox.org/)**  
   > ⚠️ VirtualBox may require **Microsoft Visual C++**. Be sure to install the version matching your architecture: `x86`, `x64`, or `ARM`.

2. 🧪 **Verify installation** by launching VirtualBox.

3. 📦 **Import the Virtual Machine `CRYSTAL_VM_MSSC2025.ova`**:
   - Go to **File → Import Appliance**
   - For the **File**, select the path to `CRYSTAL_VM_MSSC2025.ova`
   - (Optional) Choose your preferred **Machine Base Folder**
   - Under **MAC Address Policy**, choose:  
     `Generate new MAC addresses for all network adapters`
   - Under **Additional Options**, check:  
     `Import Hard Drives as VDI`
   - Click **Import** and wait for the import process to complete.

4. ▶️ In VirtualBox, **select the imported VM and click Start**.

---

## 🍏 MacOS (Apple Silicon - ARM)

1. 🔽 **[Download and Install UTM](https://mac.getutm.app/)**

2. 📂 **Unzip** the file: `CRYSTAL_VM_MSSC2025.utm.zip`

4. 🖱️ **Drag and drop** the Virtual Machine `CRYSTAL_VM_MSSC2025.utm` into UTM

5. ▶️ Click the **Start** button in UTM

---

## 🧰 Final Setup Steps

Once the Virtual Machine (based on **Debian GNU/Linux 12**) starts:

- 🔐 **Password**: `crystalcode`
- ⌨️ **Customize your keyboard layout**:
  - Use the layout selector in the **top-right corner** of the upper bar  
  **OR**  
  - Go to `Activities` (top-left corner) → `Settings → Keyboard`

---

🎉 You're all set! Welcome to the MSSC 2025 Virtual Environment.
