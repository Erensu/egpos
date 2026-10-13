# egpos
Excellent INS/GNSS/multi-sensor fusion positioning

# Introduction
egpos is a high-precision INS/GNSS fusion positioning algorithm library for vehicle positioning, smartphone positioning, drone navigation, and autonomous driving applications. It fuses inertial sensors, satellite observations, odometry, and other multi-source information to achieve high-precision positioning solutions. Its main features include:

GNSS positioning:
1. Full-frequency support for Beidou/GPS/GLONASS/GALILEO/QZSS navigation satellite systems;
2. SPP, PPP, RTD, and RTK robust least-squares estimation;
3. SPP, PPP, RTD, and RTK robust Kalman filters: sequential outlier detection, clock bias and clock drift jump detection and repair, filter model validation and repair, and filter system fault detection and repair;
4. Adaptive stochastic error model for satellite observations;
5. Adaptive Kalman filter system noise estimation;
6. Motion state discrimination: static filter, straight-driving/turning state adjustment;
7. Reliable and fast ambiguity search and fixing strategies;
8. Satellite observation quality statistics and monitoring;
9. Autonomous integrity monitoring algorithms for positioning, including positioning quality monitoring and control;
10. Parallel multi-stage fusion feedback positioning framework;
11. RTS forward/backward filtering fusion smoothing positioning solution;

INS/GNSS positioning:
1. INS/GNSS loose-coupling algorithm;
2. INS/GNSS tight-coupling algorithm: SPP, PPP, RTD, and RTK tight-coupling algorithms;
3. INS/GNSS robust Kalman filter: outlier detection, filter model validation and repair, and filter system fault detection and repair;
4. Motion constraints such as NHC, ZUPT, and ZARU;
5. Vehicle odometer assistance;
6. Dual-antenna GNSS heading assistance;
7. Forward/backward INS mechanization;
8. Dynamic alignment initialization;
9. Motion state discrimination: static filter;
10. RTS forward/backward filtering fusion smoothing positioning solution;
11. Autonomous integrity monitoring algorithms for positioning, including positioning quality monitoring and control;
12. Adaptive GNSS and INS/GNSS mode switching;
13. SE_2(3) Lie group and Lie algebra based INS mechanization and INS/GNSS loose-coupled algorithm;
14. SE_2(3) Lie group and Lie algebra based INS/GNSS tight-coupling algorithm: SPP, PPP, RTD, and RTK tight-coupling algorithms;
15. SE_2(3) Lie group and Lie algebra based INS/GNSS invariant Kalman filter algorithm;
16. Euler angle and rotation vector parameterized INS/GNSS loose/tight integration algorithms;
17. Real-time attitude/position/velocity smoother;
18. INS/GNSS iterative Kalman filter;
19. INS/GNSS static filter;
20. INS/GNSS combined attitude/velocity/position moving smoothing filter;

# References
[1] http://www.rtklib.com

[2] http://www.rtcm.org

[3] http://software.rtcm-ntrip.org

# Contact

QQ: 1971129844, Su Jinglan

Email: 1971129844@qq.com

# Note
If you need the egpos source code, please contact the author.
