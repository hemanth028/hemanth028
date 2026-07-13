<h1 align="center">
  Hi, I'm Hemanth S 👋⚡
</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00D2FF&center=true&vCenter=true&width=650&lines=ASIC%2FFPGA+Design+Verification+Engineer;SystemVerilog+%2B+UVM+%7C+Coverage-Driven+Verification;RTL+Design+%7C+AMBA+%7C+CDC+%7C+RISC-V;always(%40posedge+clk)+chase_coverage_closure();" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hemanth-s-775618290/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hemanth.s28925@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=hemanth028&style=for-the-badge&color=00D2FF" alt="Profile views" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D2FF,100:005A9C&height=120&section=header" width="100%" />
</p>

---

### 🧠 `whoami`

```verilog
module hemanth_s #(
    parameter GRAD_YEAR   = 2027,
    parameter SPEEDUP_16X = 0        // real number below, no rounding up
) (
    input  logic        clk_curiosity,
    input  logic        debug_persistence,
    output logic [4:0]  ai_rank,          // 5 = All India Rank, eYantra Robotics
    output logic [3:0]  speedup_factor,   // 13x on the Kalman Filter accelerator
    output logic         hready,           // AHB handshake, always respected
    output logic         chip_that_works
);

    // ECE undergrad @ SSN College of Engineering, Chennai (2023 - 2027)
    // ASIC/FPGA Design Verification Engineer-in-training
    // e-YSIP'26 @ e-Yantra, IIT Bombay:
    //   -> co-designed an FPGA SoC: ARM host + RV32I soft controller
    //      + custom fixed-point Kalman Filter accelerator over AXI DMA/Stream
    //   -> offloaded matrix math from software to RTL -> 13x speedup,
    //      verified numerical accuracy preserved (not just "looks close enough")
    // Believes 90% of "hardware bugs" are actually testbench bugs

    assign ai_rank        = 5'd5;
    assign speedup_factor = 4'd13;

    always_ff @(posedge clk_curiosity) begin
        if (debug_persistence)
            chip_that_works <= 1'b1;   // eventually. always eventually.
        else
            chip_that_works <= 1'bx;   // unknown state, just like my sleep schedule
    end

endmodule
```

---

## 🏆 Hall of Fame & Major Milestones

<table align="center" border="1" cellpadding="12">
  <tr>
    <td align="center" width="50%">
      <h3>🔬 e-YSIP 2026, IIT Bombay</h3>
      <p><b>RISC-V SoC & Kalman Filter Accelerator</b></p>
      <p>Co-designed an FPGA SoC fusing an ARM host, an RV32I soft controller, and a custom fixed-point Kalman Filter datapath — offloading matrix ops from software to RTL for a <b>13× execution speedup</b> with verified numerical accuracy.</p>
    </td>
    <td align="center" width="50%">
      <h3>🤖 All India Rank 5</h3>
      <p><b>eYantra Robotics Competition</b></p>
      <p>Designed an RTL maze-solving controller on a DE0-Nano FPGA, fusing multi-sensor feedback with mechanical-arm control — optimized real-time sensor-motor coordination to place <b>5th nationally</b>.</p>
    </td>
  </tr>
</table>



## 🛠 Tech Stack & Hardware Arsenal

### 💻 Languages & Methodologies
<p align="left">
  <img src="https://img.shields.io/badge/SystemVerilog-005A9C?style=for-the-badge&logo=intel&logoColor=white" alt="SystemVerilog" />
  <img src="https://img.shields.io/badge/Verilog-F15A24?style=for-the-badge&logo=cpu&logoColor=white" alt="Verilog" />
  <img src="https://img.shields.io/badge/UVM-6E40C9?style=for-the-badge&logo=checkmarx&logoColor=white" alt="UVM" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
</p>

### 🧩 Core Methodologies & Architectures
<p align="left">
  <img src="https://img.shields.io/badge/Coverage--Driven%20Verification-2E8B57?style=for-the-badge" alt="CDV" />
  <img src="https://img.shields.io/badge/Clock%20Domain%20Crossing-8A2BE2?style=for-the-badge" alt="CDC" />
  <img src="https://img.shields.io/badge/DFT-FF8C00?style=for-the-badge" alt="DFT" />
  <img src="https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white" alt="RISC-V" />
  <img src="https://img.shields.io/badge/AMBA%20(AXI%2FAHB%2FAPB)-CC0000?style=for-the-badge" alt="AMBA" />
  <img src="https://img.shields.io/badge/UART-444444?style=for-the-badge" alt="UART" />
</p>

### 🔧 EDA & Simulation Tools
<p align="left">
  <img src="https://img.shields.io/badge/Xilinx%20Vivado-FF6B6B?style=for-the-badge&logo=amd&logoColor=white" alt="Vivado" />
  <img src="https://img.shields.io/badge/Vitis-00A3E0?style=for-the-badge&logo=amd&logoColor=white" alt="Vitis" />
  <img src="https://img.shields.io/badge/QuestaSim-002E5D?style=for-the-badge&logo=siemens&logoColor=white" alt="QuestaSim" />
  <img src="https://img.shields.io/badge/ModelSim-002E5D?style=for-the-badge&logo=siemens&logoColor=white" alt="ModelSim" />
  <img src="https://img.shields.io/badge/Intel%20Quartus-0071C5?style=for-the-badge&logo=intel&logoColor=white" alt="Quartus" />
  <img src="https://img.shields.io/badge/LTspice-9B5DE5?style=for-the-badge&logo=spice&logoColor=white" alt="LTspice" />
</p>

### ⚙ Developer Environment
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Vim%2FGVim-019733?style=for-the-badge&logo=vim&logoColor=white" alt="Vim" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

---

## 📈 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hemanth028&show_icons=true&theme=radical&hide_border=true" alt="Hemanth's GitHub stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hemanth028&layout=compact&theme=radical&hide_border=true" alt="Top Languages" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hemanth028&theme=radical&hide_border=true" alt="GitHub Streak" width="60%" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=hemanth028&theme=react-dark&hide_border=true" alt="Activity Graph" width="90%" />
</p>

---

## 🎮 A Little Chaos, Professionally Contained

> **Fun fact:** I debug hardware the way I debug everything else — one `$display` statement at a time, questioning every assumption, and blaming the testbench first.

```
 ______________________________________
< HREADY was low the whole time.        >
< I checked everything except the       >
< one signal that mattered.             >
 --------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

---

## 📫 Let's Connect!

* **Email:** [hemanth.s28925@gmail.com](mailto:hemanth.s28925@gmail.com)
* **LinkedIn:** [Hemanth S](https://www.linkedin.com/in/hemanth-s-775618290/)
* **HDLBits:** Add your profile link here
* **Institution:** SSN College of Engineering (ECE, Class of 2027)

<p align="center">
  <i>"Writing deterministic hardware in a non-deterministic world."</i> ⚡
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:005A9C,100:00D2FF&height=100&section=footer" width="100%" />
</p>
