# EV-CAN-Bus-Logger
A compact OBD-II CAN bus reader built using an ESP32 and MCP2515 module. The device requests PIDs from a vehicle, reads the raw hex CAN frames, and streams the data over Bluetooth to my phone. I can decode the values in Python, and I’m currently developing a GUI dashboard and a direct data pipeline from the ESP32 into Python.
