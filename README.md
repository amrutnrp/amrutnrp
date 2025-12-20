 # 👋 Hi, I’m Amrut
- I love to **create, build and tinker** - whether it's Microcontrollers, PCBs, code, script, automations, tools, ideas & whatnot. <br>
- My projects span **embedded hardware**, **open source software**, **handmade PCBs**, **FPGA/RTL**, **Python automation**, and **AI-assisted tools**
- if you find anything below interesting, feel free to reach out - I'd be happy to talk more and/or collaborate
- 📫 linkedIn -> [amrut-pngr](https://www.linkedin.com/in/amrut-pngr/)
---

## Workplace Tools & Engineering Initiatives
> Self-driven tools built to improve engineering workflow, efficiency,
> and turnaround time for deliverables.  
> The initiatives below had meaningful impact in day-to-day work.
> Demos available upon request.


<details>
<summary><strong>Circuit reView</strong> — Schematic visualization & cross-reference tool</summary>

**What it does**
- Reconstructs circuit connectivity using graph traversal to enable end-to-end visibility
- Allows interactive inspection of connected nets, resistors, and capacitors
- Computes total capacitance on any supply rail
- Quickly gets MCNs, descriptions, and discrete values directly from the BOM

**Impact**
- Made verification independent of fragile external tools and network dependencies
- Drastically reduced cross-reference time and manual errors
- Improved design quality across multiple deliverables

</details>

<details>
<summary><strong>Power DC Automation</strong> — Automated DCR simulation workflow</summary>

**What it does**
- Implements a validated, Excel-driven workflow verified in Python before simulation
- Extracts netlists from layout (SPD) files
- Verifies user-entered components and connectivity against layout data
- Ensures connectivity correctness via graph traversal
- Auto-generates TCL scripts and invokes Cadence PowerDC

**Impact**
- Reduced dependency on license availability blocking parallel work
- Cut a ~2-week, 2-engineer task down to ~2 days, single engineer
- Inspired multiple follow-on automation efforts within the team

</details>

<details>
<summary><strong>S-Parameter Reduction for SoC Socket</strong> — Socket modelling for SoC power rails </summary>

**What it does**
- Processes ~2GB 3D matrix data to extract R and L values per SoC power port
- Applies S-parameter theory and numerical matrix manipulation
- Implements a custom data-reduction pipeline in Python

**Impact**
- Reduced an error-prone 6-day manual workflow to ~15 minutes
- Delivered cleaner, more repeatable results

</details>

<details>
<summary><strong>RCM Crawler Automation</strong> — Guided resistive current measurement workflow</summary>

**What it does**
- Addresses long turnaround and usability issues in resistive current measurement flows
- Replaces fragile legacy tooling with a web-hosted, guided interface
- Provides step-by-step execution and review for circuit compilation and verification

**Impact**
- Reduced analysis turnaround time from >2 weeks to ~3 days
- Improved usability, clarity, and repeatability of the workflow

</details>

<details>
<summary><strong>PDN Auto</strong> — Interactive PDN exploration and learning tool</summary>

**What it does**
- Computes PDN behavior via matrix manipulation of S-parameters and capacitor connectivity
- Allows interactive modification of capacitor placement
- Visualizes PDN changes to support rapid what-if analysis

**Impact**
- Enabled faster learning and intuition around capacitor placement strategies
- Improved understanding of how component size and value affect PDN behavior

</details>


---
## Personal Projects
Here's a List of my projects not related to work (only the presentable ones :P & not in chronological order) <br>
| Project | HW | SW | AI-Assisted | Components |
|---------|----|----|-------------|------------|
|  [Python BKM](https://gist.github.com/amrutnrp/e8e8ab7761e47d4afb35dab2a29ff388)| | ✅| |python |
| [Promira-prime: Custom SPI dongle solution](https://github.com/swtrix-by-Amrut/Promira-prime)  |✅ |✅ | | python, Arduino|
| [Rust host app with lua backend for scripting](https://github.com/swtrix-by-Amrut/Rustlue) | | ✅| ✅| Rust, Lua, GUI|
| [UART based LCD driver using 8051](https://github.com/Hardware-Lab-by-Amrut/UART-based-LCD)| ✅  | |  | PCB, 8051, Assembly
|  [Dashboard for Linux server](https://github.com/swtrix-by-Amrut/Dashboard-for-Linux-server)| | ✅|✅ | Linux Server |
| [Odia language typing](https://github.com/swtrix-by-Amrut/Odia-Fasttype-windows)  | |✅ | |C++, Lua |
| [Link Launcher using Rust](https://github.com/swtrix-by-Amrut/Rusty-Launcher) | | ✅|✅ | GUI, Rust |
| [Python Obfuscation](https://github.com/swtrix-by-Amrut/Secure-Runner) | |✅ |✅ |Python, Rust |
| [Compare CSV](https://github.com/swtrix-by-Amrut/CSV-comparator) | | ✅| ✅| python, web, streamlit  |
| [Highlight components in schematic diagram](https://github.com/swtrix-by-Amrut/Highlight-BOM-in-Schematic)  | | ✅| ✅| python, web, streamlit  |
|[8051 flashing tool using Teensy](https://github.com/Hardware-Lab-by-Amrut/8051-flasher-using-teensy)|✅| | | Arduino, Teensy|
|  | | | | |



<!---
amrutnrp/amrutnrp is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
