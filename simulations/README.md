- simulations results will be here.

# How to Run Simulations in Cadence Virtuoso

1. **Launch Cadence Virtuoso**

    -  Open a terminal and navigate to the project directory.

    - Run:
          
      virtuoso &
          
This will start the Virtuoso environment.

2. **Open the Design**

    - In the **Library Manager**, navigate to your ALU design library.

    - Open the **schematic** and **layout** of the ALU.

3. **Run Schematic Simulations (Spectre/Analog Design Environment - ADE)**

    - Open **ADE L/ADE XL** for simulation.

    - Load the **testbench** for the ALU.

    - Set up the **analysis** type (Transient, DC, or AC).

    - Choose **Spectre as the simulator** and configure the necessary settings.

    - Run the simulation and observe **power, delay, and PDP metrics**.

4. **Run Layout Simulations (Post-Layout Simulation - Parasitic Extraction)**

    - Extract the **parasitics (RC extraction)** using **Calibre PEX** or Assura.

    - Run post-layout simulations to validate **power and delay improvements**.

5. **Analyze Waveforms**

    - Use the **Virtuoso Waveform Viewer (Viva)** to analyze output waveforms.

    - Verify the ALU’s functionality and compare results with theoretical expectations.

6. **Export Results**

    - Save simulation results and plots for further analysis.

    - Document key performance parameters (Power, Delay, PDP).
