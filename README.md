# Temporal Derivative Distribution Repair (TDDR)
![TDDR demonstration](https://raw.githubusercontent.com/frankfishburn/TDDR/master/demo.png)
## About
The code within this repository is the reference implementation for the TDDR algorithm as described in:

Fishburn F.A., Ludlum R.S., Vaidya C.J., & Medvedev A.V. (2019). Temporal Derivative Distribution Repair (TDDR): A motion correction method for fNIRS. _NeuroImage_, 184, 171-179. doi: [10.1016/j.neuroimage.2018.09.025](https://doi.org/10.1016/j.neuroimage.2018.09.025)

---
### Usage
```matlab
signals_corrected = TDDR( signals , sample_rate );
```

---
### Inputs
**signals**: A [sample x channel] matrix of uncorrected optical density data

**sample_rate**: A scalar reflecting the rate of acquisition in Hz

---
### Outputs
   **signals_corrected**: A [sample x channel] matrix of corrected optical density data
