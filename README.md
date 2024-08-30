# egpos
excellent ins/gnss/multi-sensors fusion positioning

# 简介
egpos是高精度INS/GNSS融合定位算法库，适用于车载定位、智能手机定位、无人机导航以及自动驾驶等应用场景，融合惯性传感器、卫星观测数据、里程计等多源信息进行高精度定位解算，其主要特点包括有：

GNSS positioning:
1. 支持北斗/GPS/GLONASS/GALILEO/QZSS卫星导航定位系统全频点；
2. SPP、PPP、RTD、RTK抗差最小二乘估计；
3. SPP、PPP、RTD、RTK稳健卡尔曼滤波器：序贯粗差探测、钟差与钟漂跳变探测及修复、滤波模型验证与修复、滤波系统故障检测与修复；
4. 自适应卫星观测随机误差模型；
5. 自适应卡尔曼滤波器系统噪声估计；
6. 运动状态判别：静止滤波器、直行/转弯状态调整；
7. 可靠且快速模糊度搜索及固定策略；
8. 卫星观测数据质量统计和监测；
9. 定位自主完好性监测算法，包括定位质量监测和控制；
10. 并联多级融合反馈式定位框架；
11. RTS/前后向滤波融合平滑定位解算；

INS/GNSS positionging:
1. INS/GNSS松耦合算法;
2. INS/GNSS紧耦合算法：SPP、PPP、RTD、RTK紧耦合算法；
3. INS/GNSS稳健卡尔曼滤波器：粗差探测、滤波模型验证与修复、滤波系统故障检测与修复；
4. NHC、ZUPT、ZARU等运动约束；
5. 车载里程计辅助；
6. GNSS双天线航向辅助；
7. INS前向/后向机械编排；
8. 动对准初始化；
9. 运动状态判别：静止滤波器；
10. RTS/前后向滤波融合平滑定位解算；
11. 定位自主完好性监测算法，包括定位质量监测和控制；
12. 自适应GNSS、INS/GNSS解算模式切换；
13. 基于SE_2(3)李群李代数INS机械编排、INS/GNSS松组合算法；
14. 基于SE_2(3)李群李代数INS/GNSS紧耦合算法：SPP、PPP、RTD、RTK紧耦合算法；
15. 基于SE_2(3)李群李代数INS/GNSS不变卡尔曼滤波算法；
16. 欧拉角、旋转向量参数化INS/GNSS松紧组合算法；
17. 实时姿态/位置/速度平滑器；
18. INS/GNSS迭代卡尔曼滤波器；
19. INS/GNSS静止滤波器；
20. INS/GNSS组合姿态/速度/位置移动平滑滤波；

# 参考
[1] http://www.rtklib.com

[2] http://www.rtcm.org

[3] http://software.rtcm-ntrip.org

# 联系

QQ  ：1971129844，苏景岚

Email：1971129844@qq.com

# 备注
若对egpos源码有需求可咨询作者
