# Elantra N / Veloster N / Kona N Open Source Tuning Definitions

Welcome to the community-driven repository for tuning definitions used in Hyundai N vehicles equipped with the SIM2K ECU.

## Purpose

This project was created to open source tuning definitions for the Elantra N, enabling enthusiasts and developers to access, edit, and build custom calibrations. These definitions are compatible with tools that can edit `.BIN` files and calculate checksums properly.

## Tools Required

- **Editor:** [TunerPro RT](http://www.tunerpro.net/) (for editing XDF/XML definitions and BIN files)
- **Flashing Software:** BitBox or any compatible device/software that supports `.BIN` format and checksum correction for SIM2K ECUs
- **Data Logging Software:** VehiCAL is the best option as it allows RAM virable logging


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

## How to Use

1. **Download the Matching Files**  
   Grab the correct `XDF` and original `BIN` file that matches the software version on your ECU.

2. **Open in TunerPro RT**  
   Launch TunerPro RT and load the `XDF` definition. Then open the corresponding `BIN` file.  
   *(Refer to [TunerPro RT documentation](http://www.tunerpro.net/help/) if you're new to the software.)*

3. **Edit Your Tune**  
   Make your desired changes to maps.

4. **Save the BIN File**  
   Save your modified calibration as a new `.BIN` file.

5. **Flash to ECU**  
   Use BitBox or any flashing tool that supports `.BIN` format and checksum correction for SIM2K ECUs to flash the file to your vehicle.

> **Note:** Always log your changes and test incrementally. A small mistake in torque modeling can cause major issues.

## Contributing

Pull requests are welcome. If you have improved map definitions, added axis scaling, or discovered new maps, we encourage you to share them with the community.

## Disclaimer

This repository is for educational and research purposes only.  
You assume full responsibility for any damage or legal consequences resulting from the use of these files. Use at your own risk.  
Tuning may void your vehicle’s warranty.

---

**Stay safe, log everything, and tune responsibly.**
