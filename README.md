# uav-disturbance-toolkit

Datasets and processing tools supporting the paper on disturbance spectrum analysis from fixed-wing UAV IMU telemetry.

The repository provides reproducible workflows for FFT, PSD (Welch), STFT, filtering, and extraction of band metrics (e.g., RMS, dominant peaks) used to characterize and attribute disturbances (maneuvers, gusts/turbulence, structural resonances, aerodynamic vortices, propulsion-induced vibrations).

## Contents
- `data/` — flight logs and metadata (raw and/or preprocessed IMU;)
- `src/` — processing scripts and utilities
- `notebooks/` — reproducible analysis examples
- `results/` — generated figures/tables

## Status
Active development. **Expect updates**: new flight logs, refined labels/metadata, automated batch pipelines, and improved disturbance attribution methods.

## Citation
If you use this repository, please cite the associated paper (details will be added after publication).

## License
- Code: Apache-2.0

