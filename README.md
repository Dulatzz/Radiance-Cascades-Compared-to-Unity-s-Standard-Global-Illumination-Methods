# Radiance Cascades Compared to Unity’s Standard Global Illumination Methods

DIGRA conference experiment setup



This repository contains the experimental materials for the paper:



"Comparative Evaluation of Real-Time Global Illumination Methods in Unity URP"



\## Contents



\- Raw FPS and frame time datasets

\- Generated figures used in the paper

\- Render Video recorded for visual comparison can be seen on Youtube Playlist: https://www.youtube.com/watch?v=daDjPJyB86o&list=PLaHv1eGKS6CyZF2IG05RV7KAHvvU5-xIQ



## Data Structure

Measurements are stored in `Measured Data/`, one folder per test scene:

- `Isometric/`
- `Realistic FPS/`
- `Stylized Fps/`

Each scene folder contains:

- `gi_run_<METHOD>_<date>.csv` — raw log for one GI method (columns: `time_sec`, `ms_per_frame`, `fps`, `gi_mode`)
- `Performance_comparison_<Scene>.xlsx` — summary table for the scene

GI methods (`<METHOD>` in file names):

- `NoGI` — no global illumination (baseline)
- `RC` — Radiance Cascades
- `SSGI` — Screen Space Global Illumination
- `RTLM`



\## Engine Version



Unity 6000.2.12f1



\## Hardware



NVIDIA RTX 4060 Laptop GPU  

Intel Core i7-13620H



\## License



MIT

