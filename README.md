# Ashwath Satish

Junior at Rouse High School in Leander, Texas. I work on digital hardware — RTL, FPGAs, and accelerator design — and I'm applying to study electrical and computer engineering.

### What I'm building right now

**A bit-serial quantized neural network accelerator on a Tang Nano 20K** (Gowin GW2AR-18), built to answer one question: how much energy does a fixed-precision inference actually cost on an FPGA compared to the same model running in software on an ESP32-S3?

The whole flow is open-source — Yosys for synthesis, nextpnr-himbaechel for place and route, gowin_pack for bitstream generation, openFPGALoader to flash. No vendor IDE.

→ [`bitserial-fpga-energy`](https://github.com/ashwath-satish/bitserial-fpga-energy)

### Other things here

- **[`Indicators-`](https://github.com/ashwath-satish/Indicators-)** — a performance-indicator study tool for DECA competitors, live at [indicators-minus.vercel.app](https://indicators-minus.vercel.app). Built it because the official PI lists are PDFs nobody can study from.
- **MNIST implementations** — handwritten digit classification, written to understand the arithmetic rather than to call a library. Relevant background for quantizing a network down to something a small FPGA can hold.
- **`apl-sim`** — autonomous parking lot simulation, C++/raylib.

### Interests

Low-power digital design, quantization and fixed-point arithmetic, open-source FPGA toolchains, and the measurement side of hardware — building the harness that proves a claim, not just the thing being claimed.

Also: Controls subteam on local FRC team, and I build and maintain online practice testing infrastructure for 500+ students at Leap4ward.

### Contact

Open to research assistance, internships, and anything where a high schooler who can write Verilog and run a measurement is useful. Reachable at the email on my CV, or open an issue on any repo here.
