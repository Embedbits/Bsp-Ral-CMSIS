# CMSIS Repository

This repository contains imported [ARM CMSIS (Cortex Microcontroller Software Interface Standard)](https://github.com/ARM-software/CMSIS_5) sources.  
It serves as a mirror for selected releases, synchronized from official GitHub repositories.

## Structure

- **Branches**
  - `CMSIS_4` – contains releases from the legacy [CMSIS_4](https://github.com/ARM-software/CMSIS_4) repository  
  - `CMSIS_5` – contains releases from the current [CMSIS_5](https://github.com/ARM-software/CMSIS_5) repository  
  - Each release is imported into its dedicated branch:  
    - `x.y.x` → release branch (e.g. `5.9.x`)  
    - Commit message contains the release name (e.g. *Drivers release 5.9.0*)

- **Tags**
  - Preserved from upstream, using the original version format (`vX.Y.Z` or `X.Y.Z`).

- **Content**
  - `CMSIS/Core` – Core support for Arm Cortex-M processors  
  - `CMSIS/Driver` – Standardized peripheral drivers  
  - `CMSIS/DSP` – DSP library  
  - `CMSIS/RTOS2` – RTOS API definitions  
  - `CMSIS/NN` – Neural network kernels  

## Usage

Clone the repository and checkout the required release branch:

```bash
git clone <this-repo-url>
cd CMSIS
git checkout 5.9.x
```

## Source

Original CMSIS sources are maintained by **Arm** and available here:
- [CMSIS_4 repository](https://github.com/ARM-software/CMSIS_4)  
- [CMSIS_5 repository](https://github.com/ARM-software/CMSIS_5)  

This repository only republishes official releases for internal use.

---

## License

This project is licensed under the **CC BY-NC license**.  
You are free to use, modify, and share for **non-commercial purposes** with attribution.
