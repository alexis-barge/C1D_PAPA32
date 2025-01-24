# C1D_PAPA32

Modified version of standard [C1D_PAPA](https://doi.org/10.5194/gmd-8-69-2015) [NEMO](https://www.nemo-ocean.eu/) test case. 

**Modifications include:**
  - vertical grid discretized over 32 depth levels
  - vertical domain defined up to 200m depth
  - new time step: 1800s

**Repository content:**
- Repository follows standard structure of a NEMO config.
- ``FORCING`` contains input files (domain and surface forcing)
- ``PLOTS`` contains Python scripts to plot temperature and salinity profiles. It also contains temperature and salinity observations from Ocean Station PAPA for comparison.

**Requirements:**
- [NEMO_v4.2.1](https://forge.nemo-ocean.eu/nemo/nemo/-/releases/4.2.1)
- XIOS library
- Arch file template is provided, adapt in accordance with your computing environment
