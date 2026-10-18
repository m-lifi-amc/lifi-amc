#CNN-based Modulation Prediction in Li-Fi Systems

#Overview
This project implements three 1D CNN architectures for automatic modulation classification (AMC) in Li-Fi systems.

# Contents
- `report.pdf` - Full FYP report
- `1req.txt` - Pytorch libraries
- `configg.py` - Configuration parameters
- `signall.py` - Signal generation + channel model
- `dattaset.py` - PyTorch dataset and data loaders
- `modeels.py` - CNN architectures (Lightweight, 1D, Robust)
- `trainn.py` - Training pipeline
- `resultss.py` - Visualization and evaluation
- `mainn.py` - Main script

#Key Results: test accuracy at [0:18dB]

Lightweight 1D CNN | 83.8% | 45 KB | 9.5 ms per batch |
Standard 1D CNN | 85.0% | 559 KB | 29.8 ms per batch |
Robust 1D CNN | 84.2% | 1,179 KB | 52.3 ms per batch |

# Contact

For questions, please contact: majd75connect@proton.me
