# Hybrid Active Directory + Automation Project Journal

## Introduction
This project simulates a real-world IT environment, demonstrating skills in Active Directory, automation, and security management.  
The lab uses Windows Server 2022 as the domain controller, Windows 10 clients, and PowerShell scripts to automate tasks.  
All steps are documented with screenshots to provide a clear and reproducible workflow.

---

## Phase 1: Lab Setup

### Step 1: Install Virtualization Software
**Objective:** Set up a virtual environment to safely run server and client machines.  
**Action Taken:** Installed VirtualBox on my host machine. Configured a Host-Only network so all virtual machines can communicate within the lab.  
**Screenshot placeholder:** `docs/01_virtualization_home.png`

---

### Step 2: Download Operating Systems
**Objective:** Obtain the necessary ISOs for the lab VMs.  
**Action Taken:** Downloaded Windows Server 2022 for the server VM and Windows 10 Enterprise for client VMs. Verified the ISO checksums to ensure file integrity.  
**Screenshot placeholder:** `docs/02_iso_download.png`

---

### Step 3: Create Virtual Machines
**Objective:** Configure server and client virtual machines for the lab environment.  
**Action Taken:**  
- Server VM: 2 CPUs, 8 GB RAM, 60 GB disk  
- Client VM: 2 CPUs, 4 GB RAM, 40 GB disk  
- Network: Host-only adapter to enable communication  
- Snapshots created for each VM to easily revert changes if needed.  
**Screenshot placeholder:** `docs/03_vm_settings.png`

---

### Step 4: Install Windows Server 2022
**Objective:** Prepare the server to act as the domain controller.  
**Action Taken:** Installed Windows Server 2022, completed initial setup, configured the server name, and applied Windows updates.  
**Screenshot placeholder:** `docs/04_server_install.png`

---

### Step 5: Install Windows 10 Client Machines
**Objective:** Prepare client machines for domain integration.  
**Action Taken:** Installed Windows 10 Enterprise, applied updates, configured network settings, and verified connectivity to the server.  
**Screenshot placeholder:** `docs/05_client_install.png`

---

### Step 6: Document Lab Environment
**Objective:** Maintain a clear reference of all virtual machines and their configurations.  
**Action Taken:** Created a table listing each VM, operating system, CPU, RAM, disk size, and network type.  
**Optional Screenshot/Diagram:** `diagrams/lab-topology.png`

---

## Notes
- Screenshots should be clear and legible.  
- Use consistent naming for images: `01_virtualization_home.png`, `02_iso_download.png`, etc.  
- This phase establishes the foundation for Active Directory installation, configuration, and automation in the next phases.

