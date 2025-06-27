# 🚁 QuadPilot-FC – STM32F411-Based Flight Controller

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1qYn6Pgk2dRrZZ9FfdGF-8EtIsHSCfpHK" alt="Drone Icon" width="600"/>
</p>

QuadPilot-FC is a compact, custom-built quadcopter flight controller based on the **STM32F411 Blackpill** board. It uses the **INAV configurator** for real-time tuning and configuration, and integrates sensors like **MPU6050**, **ADXL345**, **BM280**, and **HMC5883** for precise flight stabilization and environmental awareness. The hardware is built using a **zero PCB layout**, making it highly space-efficient and ideal for lightweight UAVs.


## 🛠️ Features

- ✅ STM32F411 Blackpill flight controller  
- ✅ INAV-compatible firmware and configuration  
- ✅ Sensor suite: MPU6050 (gyro/accel), ADXL345 (accel), BM280 (barometer), HMC5883 (magnetometer)  
- ✅ PID-based control loop for smooth and stable flight  
- ✅ Zero PCB design  
- ✅ Minimalistic and lightweight hardware footprint  


## 🧩 Hardware 
<p align="center">
  <img src="images/flight_controller_layout.png" width="600"/>
  <br>
  <i>Zero PCB layout of STM32F411 and sensor suite</i>
</p>

<p>
<table align = "center" >
  <thead>
    <tr>
      <th>Component</th>
      <th>Specification</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>MCU</td><td>STM32F411CEU6 (Blackpill)</td></tr>
    <tr><td>IMU</td><td>MPU6050 (Gyroscope + Accelerometer)</td></tr>
    <tr><td>Accelerometer</td><td>ADXL345 (High-precision 3-axis accel)</td></tr>
    <tr><td>Barometer</td><td>BM280 (Altitude & pressure sensing)</td></tr>
    <tr><td>Magnetometer</td><td>HMC5883 (Compass/heading detection)</td></tr>
    <tr><td>ESCs</td><td>Compatible 30A ESCs</td></tr>
    <tr><td>Motors</td><td>1000kV Brushless Motors</td></tr>
    <tr><td>Battery</td><td>3S/4S LiPo</td></tr>
    <tr><td>Frame</td><td>F450 Quadcopter Frame</td></tr>
    <tr><td>Receiver</td><td>FlySky i6 (PPM)</td></tr>
  </tbody>
</table>

</p>


## 📚 Documentation

- **[INAV Configurator](https://github.com/iNavFlight/inav-configurator)**  
- **[STM32F411 Datasheet](https://www.st.com/resource/en/datasheet/stm32f411ce.pdf)**  
- **[MPU6050 Register Map](https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Register-Map1.pdf)**  
- **[ADXL345 Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/adxl345.pdf)**  
- **[BM280 Datasheet](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bme280-ds002.pdf)**  
- **[HMC5883 Datasheet](https://cdn.sparkfun.com/datasheets/Sensors/Magneto/HMC5883L.pdf)**  


## ⚖️ License

This project is open-source under the MIT License. See `LICENSE` for more details.
