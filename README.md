# 🟦 Kailancraft - Java 21 Edition

A custom-built voxel game engine simulation developed in Java. **Kailancraft** features a functional launcher, coordinate tracking system, and a simulated "Flat World" environment with unique world-border logic.

## 🚀 Features

* **Custom Java Renderer:** Features a parallax-based "Flat World" with a dynamic horizon and sky.
* **Coordinate System:** Real-time tracking of $X, Y, and Z$ positions.
* **The 12-Million-Block Border:** Includes "The Cutout" logic—cross the 12,000,000 mark to witness the world-border glitch effect.
* **The Infinity Glitch:** A dedicated debug key (**F**) to simulate coordinate overflow and "Infinity" states.
* **Standalone JAR:** Fully portable executable that runs on any system with JRE 21+.

## 🛠️ Controls

| Key | Action |
| :--- | :--- |
| **W / S** | Move Forward / Backward (Z-axis) |
| **A / D** | Move Left / Right (X-axis) |
| **Space** | Fly Up (Y-axis) |
| **L-Shift** | Fly Down (Y-axis) |
| **F** | Trigger "Infinity" Glitch |
| **R** | Reset Coordinates to 0,0,0 |

## 📦 How to Build

If you want to compile the project manually, ensure you have **JDK 21** installed and run:

1. **Compile the source:**
   ```batch
   javac -d bin src/com/kailan/Main.java
