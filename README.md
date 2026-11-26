# IC Design & Layout Portfolio

Academic IC design projects done during the M.Sc. in Micro- and Nanoelectronics at Peter the Great St. Petersburg Polytechnic University (SPbPU), 2024-2025. The work covers the full CMOS block flow: transistor-level schematic, simulation, layout, DRC/LVS, parasitic extraction and post-layout verification, plus simulation automation and statistical analysis.

**Tools and technology:** Cadence Virtuoso (Schematic, Layout XL, ADE L / ADE XL, Visualization & Analysis XL), Assura (DRC, LVS), QRC (parasitic extraction), Spectre, OCEAN scripts, 0.18 um CMOS technology (1.8 V standard transistors).

> The repository contains screenshots and result tables taken from the course reports. Design databases and technology files are not included.

## Projects

| # | Project | What it shows |
|---|---------|---------------|
| 1 | [4-bit CMOS binary counter](01-cmos-binary-counter) | Logic synthesis with Karnaugh maps, transistor-level schematic, full custom layout (about 1200 um2), extraction, post-layout speed limit |
| 2 | [CMOS digital cell library](02-cmos-digital-cell-library) | NAND/NOR (2-5 inputs), XOR/XNOR, MUX, RS, D/T/JK flip-flops; transistor sizing for equal rise and fall delays |
| 3 | [Inverter and differential amplifier layout](03-inverter-and-diff-amp-layout) | Layout with DRC and LVS, parasitic extraction, schematic vs post-layout comparison |
| 4 | [SRAM cell layout](04-sram-cell-layout) | Compact memory cell layout (about 6.9 x 1.6 um), array tiling with mirrored cells, effective area estimate |
| 5 | [Simulation automation and statistics](05-simulation-automation-and-statistics) | OCEAN scripts for corner/temperature sweeps, Monte Carlo (ADE XL), supply and process variation |

## Skills demonstrated

- Transistor-level CMOS design: static gates, pass-transistor latches, flip-flops, differential pair with current mirror
- Physical layout in Cadence Virtuoso: standard-cell style blocks, compact SRAM cell, analog layout with matched devices, DRC, LVS
- Parasitic extraction and comparison of schematic and post-layout behavior
- Corner (tt, ff, ss, snfp, fnsp), temperature, supply and Monte Carlo analysis
- Automation with OCEAN scripts and result export to files

## Contact

Dmitrii Sergeev - HCMC, Vietnam - dmitrii.sergeev.alekseevich@gmail.com
