# MSSC2025 - Modelling Solid State Chemistry

<div align="center">
  <img src="https://mssc.crystalsolutions.eu/wp-content/uploads/2025/02/logo_Full-1024x735.png" width="35%">
</div>

Welcome to the official GitHub repository of the **MSSC2025** 
(*Modelling Solid State Chemistry*) summer school! This repository contains all 
the necessary files, scripts, and resources that will be used during the 
tutorial sessions. MSSC2025 will be held in **Torino, Italy** in **September**, and it 
is designed to provide participants with hands-on experience in the field of 
solid-state chemistry modeling.

## 🧪 About MSSC2025

The MSSC summer school is an annual event that focuses on the application of 
quantum-mechanical methods to the study of materials science. Topics include:

- Basics of solid-state physics
- Density-functional theory
- Electronic structure of materials
- Use of local basis sets
- Spin-orbit coupling and magnetism
- Elasticity
- Lattice dynamics, vibrational spectroscopy (IR and Raman), thermodynamics
- Transport properties
- Electron density analysis
- Parallel computing and response properties

🔗 For more information, visit the [official MSSC2025 webpage](https://mssc.crystalsolutions.eu)

## 💻 Virtual Machine Setup Instructions

This guide provides step-by-step instructions to set up the **CRYSTAL Virtual Machine** on different operating systems.

### 🐧🪟🍎 Linux, Windows, and macOS (Intel-based)

1. 🔽 **[Download and Install VirtualBox](https://www.virtualbox.org/)**  
   > ⚠️ May require **Microsoft Visual C++** — choose the correct architecture: `x86`, `x64`, or `ARM`.

2. 🧪 **Open VirtualBox** to verify installation.

3. 📦 **Import `CRYSTAL_VM_MSSC2025.ova`**:
   - Go to **File → Import Appliance**
   - Select the file `CRYSTAL_VM_MSSC2025.ova`
   - (Optional) Choose your preferred **Machine Base Folder**
   - For **MAC Address Policy**:  
     `Generate new MAC addresses for all network adapters`
   - For **Additional Options**:  
     `Import Hard Drives as VDI`
   - Click **Import** and wait for the process to complete.

4. ▶️ In VirtualBox, **select and start** the imported VM.

### 🍏 macOS (Apple Silicon - ARM)

1. 🔽 **[Download and Install UTM](https://mac.getutm.app/)**

2. 📂 **Unzip**: `CRYSTAL_VM_MSSC2025.utm.zip`

3. 🖱️ **Drag and drop** `CRYSTAL_VM_MSSC2025.utm` into UTM

4. ▶️ Click the **Start** button in UTM

### 🧰 Final Setup Steps

Once the Virtual Machine (based on **Debian GNU/Linux 12**) starts:

- 🔐 **Password**: `crystalcode`
- ⌨️ **Set keyboard layout**:
  - Use the top-right layout menu  
  **OR**  
  - Navigate to: `Activities → Settings → Keyboard`

## 📬 Contact

If you have any questions or need assistance, feel free to contact the tutors maintaining this repository:

- [davide.mitoli@unito.it](mailto:davide.mitoli@unito.it)
- [giacomo.ambrogio@unito.it](mailto:giacomo.ambrogio@unito.it)
- [filippo.bodo@unito.it](mailto:filippo.bodo@unito.it)

