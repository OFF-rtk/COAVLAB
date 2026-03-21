# COAVLAB: Computer Organization and Architecture Virtual Lab

Welcome to **COAVLAB**, a dedicated repository for virtual logic simulations and architectural designs. This project serves as a practical implementation of the concepts and logic components referenced in **M. Morris Mano’s "Computer System Architecture"**. 

The goal of this repository is to bridge the gap between theoretical Boolean algebra and physical hardware implementation through high-fidelity digital simulation.

## 🚀 Featured Simulations
The repository contains a `.circ` file that contains various architectural components, including:
* 4-Bit Ripple Carry Adder (RCA)
* 4-Bit Carry Lookahead Adder (CLA) with parallel carry logic
* Wallace Tree Adder to add 3 4-Bit Numbers
* S-R Latch with NAND gates
* J-K Flip-Flop with a custom built Edge Detector
* Master Slave J-K Flip-Flop
* D Flip-Flop
* T Flip-Flop

## 🛠️ The Simulator
All circuits in this repository are built and verified using **Logisim-Evolution**. 

Logisim-Evolution is a modern, powerful tool for logic circuit design and simulation. It is a significantly upgraded fork of the original Logisim, featuring FPGA support and VHDL/Verilog export capabilities.

* **Official Repository:** [Logisim-Evolution GitHub](https://github.com/logisim-evolution/logisim-evolution)
* **Requirements:** Java JRE/JDK 16 or higher.

### How to Open Circuit Files
1.  **Download/Clone** this repository to your local machine.
2.  Install and launch **Logisim-Evolution**.
3.  Go to `File > Open` in the top menu.
4.  Navigate to the directory and select the `VLAB.circ` file.
5.  Use the **Poke Tool** (the hand icon) to toggle input pins and observe the data propagate.

## 📁 Repository Structure
* **`/` (Root):** Contains the primary Logisim `.circ` project file.
* **`images/`:** Contains high-resolution exports of the built components and logic diagrams for quick reference.
* **`LabFile.tex`:** The formal Laboratory Manual.

## 📄 Generating the Lab Manual (LaTeX)
I have included the formal documentation draft in `.tex` format. To view or edit the professional lab manual:
1.  Upload the `LabFile.tex` and any associated images from the `images/` folder to a new project in **[Overleaf](https://www.overleaf.com)**.
2.  **Crucial Step:** Click on **Menu** (top left) and change the **Compiler** from `pdfLaTeX` to **`XeLaTeX`**.
3.  Click **Recompile**, and the formatted Lab Manual will appear.

## 👤 Author
* **Ritik Joshi** (OFF-rtk)
* B.Tech CSE, 2nd Year, 4th Semester

---
*If you find these simulations helpful for your COA studies, feel free to star the repository!*
