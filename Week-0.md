# Week 0: VLSI System Design (VSD) Program Foundation & Tool Setup

## 📦 **Tools Installed in Week 0 - Task 0**

#### **Core RTL Design & Synthesis Tools**

| Tool | Purpose | Verification |
|------|---------|--------------|
| 🧠 **Yosys** | RTL Synthesis & Logic Optimization | ✅ Verified |
| 📟 **Iverilog** | Verilog Simulation & Compilation | ✅ Verified |
| 📊 **GTKWave** | Waveform Viewer & Analysis | ✅ Verified |
| ⚡ **Ngspice** | Analog & Mixed-Signal Simulation | ✅ Verified |
| 🎨 **Magic VLSI** | Layout Design & DRC Verification | ✅ Verified |

## 1. Yosys – RTL Synthesis Tool Installation 

~~~

 git clone https://github.com/YosysHQ/yosys.git
 cd yosys 
 sudo apt install make # (If make is not installed please install it) 
 sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
 make 
 sudo make install
 
~~~


## 2. Iverilog Installation 

~~~
sudo apt-get update
sudo apt-get install iverilog
~~~

<img width="1913" height="716" alt="image" src="https://github.com/user-attachments/assets/b81536b4-c8d4-459a-aba7-12065c01536b" />


## 3. GTKwave - Waveform Viewer Installation 

~~~
sudo apt install gtkwave 

~~~

<img width="1913" height="953" alt="image" src="https://github.com/user-attachments/assets/ee79185d-742e-46e2-b179-d5a82b601733" />


## 4. Ngspice – Circuit Simulator


~~~
sudo apt install ngspice
~~~


<img width="1913" height="692" alt="image" src="https://github.com/user-attachments/assets/7954872a-5267-4c80-b2c7-74da590dae5a" />

## 5. Magic VLSI – Layout Tool

~~~
 sudo apt-get install m4
 sudo apt-get install tcsh
 sudo apt-get install csh
 sudo apt-get install libx11-dev
 sudo apt-get install tcl-dev tk-dev
 sudo apt-get install libcairo2-dev
 sudo apt-get install mesa-common-dev libglu1-mesa-dev
 sudo apt-get install libncurses-dev

git clone https://github.com/RTimothyEdwards/magic
cd magic
./configure
make
make install 

~~~

<img width="1913" height="1044" alt="image" src="https://github.com/user-attachments/assets/dadc2339-a378-43b0-bff2-c1ecae683b44" />







