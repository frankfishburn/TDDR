# Temporal Derivative Distribution Repair (TDDR)
## About
The code within this repository is the reference implementation for the TDDR algorithm as described in:

Fishburn F.A., Ludlum R.S., Vaidya C.J., & Medvedev A.V. (In Press). Temporal Derivative Distribution Repair (TDDR): A motion correction method for fNIRS. _NeuroImage_.

---
### Usage
```Matlab
signals_corrected = TDDR( signals , sample_rate );
```

---
### Inputs
**signals**: A [sample x channel] matrix of uncorrected optical density data

**sample_rate**: A scalar reflecting the rate of acquisition in Hz

---
### Outputs
   **signals_corrected**: A [sample x channel] matrix of corrected optical density data
