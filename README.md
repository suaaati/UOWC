# UOWC
# Underwater Optical Wireless Communication (UOWC) – BPSK BER Simulation

This project simulates Bit Error Rate (BER) performance in Underwater Optical Wireless Communication (UOWC) systems using Binary Phase Shift Keying (BPSK). The simulation considers underwater factors like absorption, scattering, misalignment loss, and turbulence across different types of water bodies.

---

## Features

- Supports 3 Water Types:  
  - `clear_ocean`  
  - `coastal`  
  - `turbid_harbor`

- Factors Included in Simulation:
  - Beer-Lambert Attenuation
  - Henyey-Greenstein Scattering
  - Misalignment Loss
  - Log-Normal Turbulence Fading

- BER Computation via:
  - Theoretical Q-function
  - Monte Carlo Simulation

- User-defined Parameters:
  - Distance (80-1700 meters)
  - Transmit Power (0.0001–0.001 W)
  - Beam Misalignment Angle
  - Divergence Angle
  - Number of Monte Carlo Samples

- Outputs:
  - SNR vs BER plot (Theoretical vs Monte Carlo)
  - Export simulation data as a `.csv` file
  - Stores all input-output data in a structured array for analysis

--
