# QPSK Wireless Link Simulation (MATLAB)

Simulation of a digital wireless link following a typical SDR development flow,
compatible with a future USRP implementation.

## Project goal
Transmit a message using QPSK modulation, recover it at the receiver,
and progressively add synchronization and impairment correction stages.

## Development steps (based on job description)
1. Message to bits
2. QPSK symbol mapping
3. Frame construction with preamble
4. Receiver extraction of message bits
5. End-to-end transmission check
6. Upsampling and pulse shaping (RRC)
7. Matched filtering and downsampling
8. Frequency offset insertion and coarse correction
9. Residual frequency and phase estimation using preamble
10. Residual correction
11. Message extraction

## Repository structure
- src/        Core transmitter and receiver code
- tests/      Validation scripts
- docs/       Explanations and notes
- results/    Figures and outputs

## Status
Project initialized. No hardware required at this stage.
