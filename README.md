# Where does a learned inverse-design model fail, and can we see it coming?

Short self-directed study on **[EngiBench](https://engibench.ethz.ch) Beams2D** (2D topology optimization, IDEAL Lab, ETH Zurich).

1. **Where does it fail?** Every generated design is simulated and compared with the optimized design for the same condition, per condition, not only on average.
2. **Can we see it coming?** Ensemble disagreement and distance to the nearest training condition are tested as warning signals for the worst designs (AUROC), before any simulation.

## Results
_To be filled in after the full run._

## Run it
```bash
conda create -n beams python=3.12 -y
conda activate beams
pip install -r requirements.txt
```
Open `notebooks/beams2d_reliability_study.ipynb`, select the `beams` kernel, set `QUICK=True` for a smoke test, then Run All.

## Built on
F. Felten et al., "EngiBench: A Framework for Data-Driven Engineering Design Research," NeurIPS 2025 Datasets and Benchmarks. https://github.com/IDEALLab/EngiBench

## Author
Jahid Hasan Jony
