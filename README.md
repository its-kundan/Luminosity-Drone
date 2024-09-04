# Luminosity Drone

This project, **Luminosity Drone**, was developed as part of the Robotics Eyantra competition. The aim of the project is to design and implement a drone simulation capable of detecting and responding to varying luminosity levels in its environment. The project was built using Gazebo, Ubuntu, VSCode, OpenCV, and Python.

## Project Overview

The **Luminosity Drone** is a simulation-based drone designed to perform real-time luminosity detection using computer vision techniques. The project leverages the Gazebo simulation environment to simulate drone behavior and navigation in a virtual world. With the help of OpenCV, the drone captures and processes images to analyze luminosity levels and take appropriate actions based on light intensity.

### Key Features:
- **Simulation Environment**: Gazebo is used to simulate the physical environment and drone dynamics.
- **Image Processing**: OpenCV is employed to process images from the drone's camera and measure light intensity.
- **Autonomous Control**: The drone's behavior changes autonomously based on detected luminosity levels.
- **Platform**: The project was developed on an Ubuntu system using VSCode for development and Python for scripting.

### Tools & Technologies:
- **Gazebo**: Simulation environment for testing and visualizing drone performance.
- **Ubuntu**: Development platform.
- **VSCode**: Integrated development environment for code writing and debugging.
- **OpenCV**: Library for real-time computer vision tasks.
- **Python**: Main programming language used for scripting and logic implementation.

### How It Works:
1. The drone, simulated in Gazebo, moves through a virtual environment.
2. OpenCV captures frames from the drone’s camera feed.
3. Using image processing techniques, the luminosity level of the environment is determined.
4. The drone reacts based on predefined thresholds of luminosity, changing its movement or performing specific tasks.

### Installation and Setup:
1. Install **Gazebo**: [Gazebo installation guide](http://gazebosim.org/tutorials?tut=install_ubuntu).
2. Set up **OpenCV**: Follow the [OpenCV installation guide](https://docs.opencv.org/master/df/d65/tutorial_table_of_content_introduction.html).
3. Clone the repository:
   ```bash
   git clone https://github.com/your-username/luminosity-drone.git
   ```
4. Run the Python scripts to start the simulation and control the drone.

### Future Enhancements:
- Integration with real-world drones.
- Improved image processing algorithms for better luminosity detection.
- Enhanced control mechanisms based on advanced AI techniques.

---

Feel free to modify or extend this description to fit your needs!
