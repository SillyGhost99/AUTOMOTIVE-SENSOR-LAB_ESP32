MotoDAQ
Motorsport Data Acquisition System 🧭

MotoDAQ is a real-time riding data logger built on the ESP32. It mounts on a bike and captures acceleration, G-forces, lean angle, vibration, and temperature while you ride — streaming live telemetry to a Python dashboard and feeding an ML pipeline that classifies driver behaviour from self-collected data.
Inspired by professional systems like the AiM MXS Strada and MoTeC M1 logger. Built for a fraction of the cost using off-the-shelf hardware.

Why
Most people train ML models on downloaded Kaggle datasets.
MotoDAQ trains on data physically collected from a real bike on real roads.
That's a completely different conversation in an engineering interview.
Stack
Hardware — ESP32 WROOM-32, MPU6050, DHT22, 0.96" OLED
Firmware — C++ via VS Code + PlatformIO
Dashboard — Python (matplotlib, pandas)
ML — scikit-learn, Google Colab
Status
[x] Firmware simulated and tested on Wokwi
[ ] Flashed to real hardware
[ ] First test ride
[ ] Python live dashboard
[ ] ML driver behaviour classifier
Built by Immad uddin — 2nd Year Mechanical Engineering
