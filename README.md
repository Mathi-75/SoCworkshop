# SoC Design Learning Journey

This repository documents my progress and learnings throughout the **SoC Design Labs** course offered by **vlsisystemdesign.com**. It serves as a personal log of all the labs, projects, and assignments completed during the program, showcasing the hands-on experience gained in System on Chip design and verification.

---

## Course Progress

| Week   | Topic                                | Status      |
| :----- | :----------------------------------- | :---------- |
| Week 0 | Environment Setup & Introduction     | ✅ Complete |

---

## Week 0: Introduction and Environment Setup

<details>
  <summary>▶ Day 0 - Tools Installation</summary>
  
  <br>
  The first day focused on getting acquainted with the course structure and setting up the necessary open-source tools for VLSI design and simulation on a Linux environment. This foundational setup is crucial for all the upcoming labs and projects.

  The primary tools installed were:
  * **Icarus Verilog (`iverilog`):** A Verilog compiler used for simulating digital circuits.
  * **GTKWave:** A powerful waveform viewer for visualizing and analyzing the output of simulations.
  * **Yosys:** An open-source framework for Verilog RTL synthesis, which translates the hardware description into a gate-level netlist.

  After the installation process, I verified that each tool was correctly set up and accessible from the terminal.

  #### Tool Installation Verification

  The following screenshots confirm the successful installation and basic invocation of the essential tools.

  **1. Icarus Verilog (`iverilog`)**

  Running the `iverilog` command in the terminal displays its usage options, confirming that the compiler is ready to use.

  ![Icarus Verilog Installation](images/iverilog.jpg)

  **2. GTKWave**

  Launching `gtkwave` from the terminal successfully opens the GUI, which is now ready to load and display `.vcd` waveform files for analysis.

  ![GTKWave Installation](images/gtkwave.jpg)

  **3. Yosys Open Synthesis Suite**

  Executing the `yosys` command starts the synthesis suite, confirming that the tool is installed and operational for future synthesis tasks.

  ![Yosys Installation](images/yosys.jpg)

  With the environment now set up, I am ready to proceed with the upcoming labs.

</details>

*(You can add more `<details>` blocks here for Day 1, Day 2, etc. as you complete them)*

---

## Acknowledgements

I would like to express my sincere gratitude to **Kunal Ghosh**, the director of VSD, for his invaluable guidance and for providing the platform to learn about SoC Design.

- **LinkedIn**: [Kunal Ghosh](https://www.linkedin.com/in/kunal-ghosh-vlsisystemdesign-com-28084836/)