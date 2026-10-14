# egpos

Excellent INS/GNSS/Multi-Sensor Fusion Positioning

## Overview

`egpos` is a high-precision navigation and positioning library for INS/GNSS integration and multi-sensor fusion. It is designed for vehicle localization, smartphone-based positioning, drone navigation, and autonomous driving applications.

By fusing inertial measurements with GNSS observations and other complementary sensors, `egpos` aims to deliver robust and accurate positioning under challenging conditions, including weak signal environments, dynamic motion, and system anomalies.

## Key Features

### GNSS Positioning

`egpos` provides a comprehensive GNSS processing framework, including:

1. Full-frequency support for Beidou, GPS, GLONASS, Galileo, and QZSS
2. SPP, PPP, RTD, and RTK robust least-squares estimation
3. Robust Kalman filtering for SPP, PPP, RTD, and RTK
   - sequential outlier detection
   - clock bias and clock drift jump detection and repair
   - filter model validation and repair
   - filter system fault detection and recovery
4. Adaptive stochastic error modeling for satellite observations
5. Adaptive system noise estimation in Kalman filtering
6. Motion-state discrimination, including static filtering and driving-state adjustment
7. Reliable and efficient ambiguity search and fixing strategies
8. Satellite observation quality statistics and monitoring
9. Autonomous integrity monitoring for positioning quality assessment and control
10. Parallel multi-stage fusion feedback positioning framework
11. RTS forward/backward smoothing for fusion-based positioning solutions

### INS/GNSS Positioning

The library also supports advanced INS/GNSS integrated navigation methods:

1. INS/GNSS loose-coupling algorithms
2. INS/GNSS tight-coupling algorithms for SPP, PPP, RTD, and RTK
3. Robust Kalman filtering for INS/GNSS fusion
   - outlier detection
   - model validation and repair
   - system fault detection and recovery
4. Motion constraints such as NHC, ZUPT, and ZARU
5. Vehicle odometer assistance
6. Dual-antenna GNSS heading assistance
7. Forward/backward INS mechanization
8. Dynamic alignment initialization
9. Motion-state discrimination, including static filtering
10. RTS forward/backward smoothing
11. Autonomous integrity monitoring for positioning quality evaluation and control
12. Adaptive switching between GNSS and INS/GNSS modes
13. SE2(3) Lie group-based INS mechanization and integration methods
14. SE2(3) invariant Kalman filtering for INS/GNSS tight coupling
15. Euler-angle and rotation-vector parameterized INS/GNSS integration algorithms
16. Real-time attitude/position/velocity smoothing
17. INS/GNSS iterative Kalman filtering
18. Static INS/GNSS filtering
19. Combined attitude/velocity/position smoothing for moving platforms

## Applications

`egpos` is intended for:

- vehicle positioning
- smartphone-based navigation
- drone navigation
- autonomous driving systems
- high-precision multi-sensor localization tasks

## Repository Contents

- `README.md` — project overview and feature summary
- `egpos.pdf` — technical document / paper associated with the project

## References

[1] RTKLIB: http://www.rtklib.com

[2] RTCM: http://www.rtcm.org

[3] RTCM NTRIP software: http://software.rtcm-ntrip.org

## Contact

QQ: 1971129844, Su Jinglan

Email: 1971129844@qq.com

## Note

If you need the `egpos` source code, please contact the author.
