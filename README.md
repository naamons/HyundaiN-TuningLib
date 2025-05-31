# Elantra N / Veloster N / Kona N Open Source Tuning Definitions

Welcome to the community-driven repository for tuning definitions used in Hyundai N vehicles equipped with the SIM2K ECU.

## Purpose

This project was created to open source tuning definitions for the Elantra N, enabling enthusiasts and developers to access, edit, and build custom calibrations. These definitions are compatible with tools that can edit `.BIN` files and calculate checksums properly.

## Tools Required

- **Editor:** [TunerPro RT](http://www.tunerpro.net/) (for editing XDF/XML definitions and BIN files)
- **Flashing Software:** BitBox or any compatible device/software that supports `.BIN` format and checksum correction for SIM2K ECUs

## Platform Details

The SIM2K ECU used in Hyundai N vehicles is a complex torque/load-based control unit, structurally similar to the SIMOS18 ECU used in Volkswagen platforms. Tuning this ECU requires proper understanding of:

- Torque modeling
- Load calculation
- Airflow and boost limits
- Fuel and ignition strategies
- Safety limiters and intervention logic

If you are not familiar with tuning modern torque-based ECUs, **do not flash custom calibrations**. Improper tuning can result in engine damage, drivability issues, or safety system malfunctions.

## What’s Included

- `XDF` or `XML` definition files for use with TunerPro RT
- Original `BIN` files

## Contributing

Pull requests are welcome. If you have improved map definitions, added axis scaling, or discovered new maps, we encourage you to share them with the community.

## Disclaimer

This repository is for educational and research purposes only.  
You assume full responsibility for any damage or legal consequences resulting from the use of these files. Use at your own risk.  
Tuning may void your vehicle’s warranty.

---

**Stay safe, log everything, and tune responsibly.**
