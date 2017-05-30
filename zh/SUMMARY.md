# Summary

* [项目介绍](README.md)
* [新手上路](setup/getting_started.md)
  * [初始设置](setup/config_initial.md)
  * [安装工具链](setup/dev_env.md)
    * [Mac OS](setup/dev_env_mac.md)
    * [Linux](setup/dev_env_linux.md)
      * [Advanced Linux](setup/dev_env_linux_boutique.md)
    * [Windows](setup/dev_env_windows.md)
  * [代码编译](setup/building_px4.md)
  * [高级配置](setup/config_advanced.md)
  * [贡献&  开发者电话会议](contribute/README.md)
    * [GIT例程](contribute/git_examples.md)
* [概念解读](concept/README.md)
  * [飞行模式](concept/flight_modes.md)
  * [结构概述](concept/architecture.md)
  * [飞行控制栈](concept/flight_stack.md)
  * [中间件](concept/middleware.md)
  * [混控和执行器](concept/mixing.md)
  * [PWM限制状态机](concept/pwm_limit.md)
* [教程](tutorials/tutorials.md)
  * [地面站](qgc/README.md)
  * [编写应用程序](tutorials/tutorial_hello_sky.md)
  * [QGC的视频流](qgc/video_streaming.md)
  * [远距离视频流](qgc/video_streaming_wifi_broadcast.md)
  * [综合测试](test_and_ci/integration_testing.md)
  * [光流](tutorials/optical_flow.md)
  * [ecl EKF](tutorials/tuning_the_ecl_ekf.md)
  * [飞行前检查](tutorials/pre_flight_checks.md)
  * [数传](tutorials/telemetry.md)
  * [传感器热补偿](tutorials/sensor_thermal_calibration.md)
  * [着陆检测](tutorials/land_detector.md)
* [仿真](simulation/README.md)
  * [基本仿真](simulation/sitl.md)
  * [Gazebo仿真](simulation/gazebo.md)
  * [HITL仿真](simulation/hitl.md)
  * [连接到ROS](simulation/ros_interface.md)
  * [AirSim仿真](simulation/airsim.md)
  * [多机仿真](simulation/multi-vehicle-simulation.md)
* [自驾仪硬件](flight_controller/README.md)
  * [Crazyflie 2.0](flight_controller/crazyflie2.md)
  * [Intel® Aero Ready to Fly Drone](flight_controller/intel_aero.md)
  * [Pixfalcon](flight_controller/pixfalcon.md)
  * [Pixhawk](flight_controller/pixhawk.md)
  * [Pixracer](flight_controller/pixracer.md)
  * [Raspberry Pi](flight_controller/raspberry_pi.md)
  * [Snapdragon Flight](flight_controller/snapdragon_flight.md)
    * [相机和光流](flight_controller/snapdragon_flight_camera.md)
    * [高级Snapdragon](flight_controller/snapdragon_flight_advanced.md)
      * [获取I/O数据](flight_controller/snapdragon_flight_accessing_io_data.md)
* 中间件及架构
  * [uORB消息机制](middleware/uorb.md)
  * [MAVLink消息机制](middleware/mavlink.md)
  * [守护程序](advanced/architecture_daemon.md)
  * [驱动框架](middleware/drivers.md)
  * [模块 & 命令](middleware/modules_main.md)
    * [命令](middleware/modules_command.md)
    * [通信](middleware/modules_communication.md)
    * [驱动](middleware/modules_driver.md)
    * [系统](middleware/modules_system.md)
* [机型](airframes/README.md)
  * [统一的基础代码](airframes/architecture.md)
  * [参考机型](airframes/airframe_reference.md)
  * [添加一个新的机型](airframes/adding_a_new_frame.md)
  * [多旋翼](airframes_multicopter/README.md)
    * [电机映射](airframes_multicopter/motor_map.md)
    * [QAV 250 Racer](airframes_multicopter/qav250.md)
    * [Matrice 100](airframes_multicopter/matrice100.md)
    * [QAV-R](airframes_multicopter/qav-r.md)
  * [直升机](airframes_plane/README.md)
    * [Wing Wing Z-84](airframes_plane/wing_z_84.md)
  * [VTOL](airframes_vtol/README.md)
    * [VTOL Testing](airframes_vtol/testing.md)
    * [TBS Caipiroshka](airframes_vtol/caipiroshka.md)
  * [船舶，潜水艇，飞艇，车辆](airframes_experimental/README.md)
* [协同电脑](companion_computer/README.md)
  * [Pixhawk系列协同电脑](companion_computer/pixhawk_companion.md)
* [使用DroneKit的机器人](dronekit/README.md)
  * [DroneKit的使用](dronekit/example.md)
* [使用ROS的机器人](ros/README.md)
  * [用Linux进行外部控制](ros/offboard_control.md)
  * [在RPi上安装ROS](ros/raspberrypi_installation.md)
  * [MAVROS (ROS上的MAVLink)](ros/mavros_installation.md)
  * [MAVROS外部控制例程](ros/mavros_offboard.md)
  * [外部位置估计](ros/external_position_estimation.md)
  * [Gazebo Octomap](simulation/gazebo_octomap.md)
* [传感器和执行机构总线](sensor_bus/README.md)
  * [I2C总线](sensor_bus/i2c.md)
    * [SF1XX lidar](sensor/sf1xx_lidar_setup.md)
  * [UAVCAN总线](uavcan/README.md)
    * [UAVCAN Bootloader](uavcan/bootloader_installation.md)
    * [UAVCAN固件升级](uavcan/node_firmware.md)
    * [UAVCAN配置](uavcan/node_enumeration.md)
    * [UAVCAN 的各种笔记](uavcan/notes.md)
  * [PWM / GPIO](sensor_bus/pwm_gpio.md)
  * [UART](sensor_bus/uart.md)
    * [uLanding Radar](sensor/uart_ulanding_radar.md)
* 调试及高级主题
  * [FAQ](debug/faq.md)
  * [系统控制台](debug/system_console.md)
  * [系统启动](advanced/system_startup.md)
  * [参数&配置](advanced/parameters_and_configurations.md)
  * [参考参数](advanced/parameter_reference.md)
  * [自驾仪调试](debug/gdb_debugging.md)
  * [Sensor/Topic Debugging](debug/sensor_uorb_topic_debugging.md)
  * [仿真调试](debug/simulation_debugging.md)
  * [发送调试的值](debug/debug_values.md)
  * [Profiling](debug/profiling.md)
  * [室内 / 虚拟 GPS](advanced/fake_gps.md)
  * [相机触发器](advanced/camera_trigger.md)
  * [日志记录](log/logging.md)
  * [飞行日志分析](log/flight_log_analysis.md)
  * [EKF日志回放](log/ekf2_log_replay.md)
  * [System-wide Replay](debug/system_wide_replay.md)
  * [安装Intel RealSense R200的驱动](advanced/realsense_intel_driver.md)
  * [Parrot Bebop](advanced/parrot_bebop.md)
  * [设置云台控制](advanced/gimbal_control.md)
  * [切换状态估计器](advanced/switching_state_estimators.md)
  * [外部模块](advanced/out_of_tree_modules.md)
  * [ULog文件格式](log/ulog_file_format.md)
  * [Licenses](advanced/licenses.md)
  * [无线数传](advanced/telemetry_radio_modem.md)
  * [Wifi数传](advanced/telemetry_wifi.md)
* [软件更新](software_update/README.md)
  * [STM32 Bootloader](software_update/stm32_bootloader.md)
* [测试和持续集成](test_and_ci/README.md)
  * [Docker容器](test_and_ci/docker.md)
  * [持续集成](test_and_ci/continous_integration.md)
    * [Jenkins持续集成环境](test_and_ci/jenkins_ci.md)
  * [维护](test_and_ci/maintenance.md)