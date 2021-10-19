# osu180_pll_vsd
Phase Locked Loop IP designed using OSU 180nm PDK as a part of VSDOpen 2021 Tutorial 1
## Steps to design:
1. Finalize design at architecture level based on specifications.
2. Construct SPICE netlist of circuit and simulate using ngspice.
3. Verify that pre-layout simulations match specifications. If not, modify circuit or architecture.
4. Construct layout from circuit in accordance with Euler's path rules using Magic.
5. Extract post-layout SPICE netlist from Magic(includes parasitics).
6. Modify generated netlist to include library file and voltage sources to simulate in ngspice.
7. Confirm that final waveform with parasitics included satisfies specifications.
