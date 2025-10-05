# 🤖 Wall-Following Pioneer P3DX Robot

## 🧭 Overview
This project showcases a **Pioneer P3DX robot** simulation in **CoppeliaSim**, programmed in **Lua**, to perform **autonomous wall-following** behaviour.  
The robot starts in a random roaming state and switches automatically to wall-following when nearby obstacles are detected using its 16 ultrasonic sensors.

During the simulation:
- A **blue trajectory trace** visualises the robot’s movement path.  
- A **graph** displays real-time **error values** between the actual and ideal wall-following distance.  
- Sensor readings are printed in the CoppeliaSim console for live observation.

The system demonstrates stable wall adherence, dynamic transition from free motion to tracking, and effective distance regulation.

---

## 🚀 How to Run the Simulation

1. **Open CoppeliaSim** on your system.  
2. Go to **`File → Open Scene`**.  
3. Select and load the file **`main.ttt`**.  
4. Click the **▶ Start Simulation** button.  
5. Observe:
   - The **robot’s path** and **turning behaviour**.  
   - The **blue trace** representing its travel route.  
   - The **graph window** displaying real-time wall-following error.  
   - **Console logs** showing sensor readings and distance updates.

---

## 📁 File Information
| File | Description |
|------|--------------|
| `main.ttt` | Complete simulation file containing robot model, Lua script, sensors, and graph setup |

---