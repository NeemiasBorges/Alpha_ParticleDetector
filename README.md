## Mobile Low-Cost Spectrometer API [IN DEVELOPMENT]

The Mobile Low-Cost Spectrometer API is an accessible solution for measuring radioactivity and the energy of ionizing radiation, such as alpha particles and electrons. This system is based on two existing projects: the RadStar Alpha equipment and the DIY project supported by CERN (https://github.com/ozel/DIY_particle_detector/).

### Overview

This compact spectrometer is designed to provide real-time data, enabling its use in fieldwork, educational applications, and scientific studies. With a portable and affordable design, it democratizes access to radiation measurement, making it an essential tool for a wide range of users.

***
### Features

- **Radioactivity Measurement**: Capable of detecting and measuring the energy of alpha particles and electrons.
- **Accessible API**: Facilitates integration with other applications and platforms.
- **Compact Design**: Ideal for field use and easy transport.
- **Real-Time Data**: Enables instant monitoring and analysis.
- **Diverse Applications**: Suitable for educational, scientific, and environmental safety contexts.

### Technologies Used

- **Based on RadStar Alpha**: Reference equipment for alpha radiation measurements.
- **DIY CERN Project**: Incorporates concepts and technologies from the DIY low-cost spectrometer project supported by CERN.

## Components Used

The table below lists the original components from the CERN project and their respective substitutions used in my project. This substitution aims to use more accessible components available in the local market while maintaining the original project's functionality.

| **Original Component**           | **Substitution**                                  | **Purchase Location**                      |
|----------------------------------|---------------------------------------------------|--------------------------------------------|
| BT1 (9V Clip)                    | Generic 9V clip                                   | []                    |
| C1, C2 (10pF radial 2.54mm 50V)  | Multicomp MC0805N100J101A2.54MM (or similar)      | []                    |
| C3, C5, C7, C10 (100nF radial 2.54mm 50V) | Multicomp MC0805Y104M500A2.54MM (or similar) | []                    |
| C4 (470nF radial 2.54mm 50V)     | KEMET C320C474M5U5TA (or 470nF similar)           | []                    |
| C6 (3.3nF radial 2.54mm 50V)     | KEMET C315C332K1R5TA (or 3.9nF/4.7nF similar)     | []                    |
| C8 (47uF 63V THT)                | Panasonic ECA-1JHG470 (or similar)                | []                    |
| C9 (6.8nF radial 2.54mm 50V)     | KEMET C315C682K5R5TA (or similar)                 | []                    |
| D4 (silicon PIN photodiode)      | Osram Opto BPX 61                                 | []                    |
| J3 (male BNC connector)          | Generic BNC connector                            | []                    |
| R1, R4 (4.7k 1% axial)           | Multicomp MCMF006FF4701A50 (or similar)           | []                    |
| R2 (15k 1% axial)                | Multicomp MCMF006FF1502A50 (or similar)           | []                    |
| R3 (40Mega 10% 0805 SMD)         | TE Connectivity RH73H2A40MKTN (or similar)        | []                    |
| R5 (1Mega 1% axial)              | Multicomp MCMF006FF1004A50 (or similar)           | []                    |
| R6, R7, R8 (10k 1% axial)        | Multicomp MCMF006FF1002A50 (or similar)           | []                    |
| R9 (2.2k 1% axial)               | Multicomp MCMF006FF2201A50 (or similar)           | []                    |
| SW1 (SPDT switch on-none-on)     | Generic SPDT switch (3 or 4 pins)                 | []                    |
| U1 (TLE2072CP/ACP)               | Texas Instruments TLE2072CP/ACP (or equivalent)   | []                    |

### Goals

This project aims to provide a radiation measurement tool that is:

- **Affordable**: Low cost to increase accessibility.
- **Portable**: Easy to transport and use in various locations.
- **Accurate**: Provides reliable and detailed measurements.
- **Integrable**: Easy to integrate with other applications through its API.

***
### Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.
