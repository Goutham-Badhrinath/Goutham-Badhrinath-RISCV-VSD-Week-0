# 🛠️ Task 2 - Tool Installation and Setup  

## 🎯 Objective  
To install and verify the essential tools required for the **RISC-V SoC Tapeout project**:  
- **Icarus Verilog (iverilog)**  
- **GTKWave**  
- **Yosys**  

---


## 🌐 Oracle Virtual Machine for Linux Ubuntu
Download Link: [VirtualBox Downloads](https://www.virtualbox.org/wiki/Downloads)  

---

## 🖥️ System Check  for Linux Ubuntu

| **Requirement** | **Specification** |
|------------------|--------------------|
| RAM              | 6 GB              |
| HDD              | 50 GB             |
| OS               | Ubuntu 20.04+     |
| CPU              | 4 vCPU            |

---

## 1️⃣ Installing Icarus Verilog (iverilog)  

### 🔹 Installation Steps  
```bash
sudo apt-get update
sudo apt-get install iverilog
```
---
### 🔹 Terminal Output 
![iverilog Screenshot](.Screenshots/iverilog.jpg)

## 2️⃣ Installing GTKWave  

### 🔹 Installation Steps  
```bash
sudo apt-get update
sudo apt install gtkwave 
```
---
### 🔹 Terminal Output
![GTKWave Screenshot](.Screenshots/gtkwave.jpg)

## 3️⃣ Installing Yosys  

### 🔹 Installation Steps  
```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make (If make is not installed please install it)
$ sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install 
```
---
### 🔹 Terminal Output
![Yosys Screenshot](.Screenshots/yosys.jpg)




## ✅ Outcome  
- Installed and verified : **Icarus Verilog**, **GTKWave**, and **Yosys**.  
- Tools are ready for **simulation, waveform analysis, and synthesis**.  
