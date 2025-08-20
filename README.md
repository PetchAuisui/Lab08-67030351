# Lab-08-teamwork-dev-for-esp32 
## Result
<img width="1916" height="1077" alt="image" src="https://github.com/user-attachments/assets/e453ab72-34fb-473d-b8b7-b110740d2622" />

```c
Executing action: monitor
Running idf_monitor in directory /project
Executing "/opt/esp/python_env/idf6.0_py3.12_env/bin/python /opt/esp/idf/tools/idf_monitor.py -p socket://localhost:5555 -b 115200 --toolchain-prefix xtensa-esp32-elf- --target esp32 --revision 0 /project/build/lab8.elf /project/build/bootloader/bootloader.elf -m '/opt/esp/python_env/idf6.0_py3.12_env/bin/python' '/opt/esp/idf/tools/idf.py'"...
--- esp-idf-monitor 1.6.2 on socket://localhost:5555 115200
--- Quit: Ctrl+] | Menu: Ctrl+T | Help: Ctrl+T followed by Ctrl+H
I (17134) LAB8: 📋 Reading #2
I (17134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (17134) SENSOR: 🌡️  Temperature: 35.2°C
I (17134) SENSOR: 💧 Humidity: 79.6%
I (17134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (17134) SENSOR: 📈 All sensors operating normally
I (17134) LED: ❌ LED OFF from file: ./managed_components/led/LED/src/led.c, line: 27
I (17134) LED: 🔴 LED is now OFF
I (17134) LAB8: 💡 LED OFF (fake_value <= 50)
I (17134) LAB8: ==========================================
I (21134) LAB8: 📋 Reading #3
I (21134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (21134) SENSOR: 🌡️  Temperature: 27.2°C
I (21134) SENSOR: 💧 Humidity: 88.2%
I (21134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (21134) SENSOR: 📈 All sensors operating normally
I (21134) LED: ✅ LED ON from file: ./managed_components/led/LED/src/led.c, line: 20
I (21134) LED: 🟢 LED is now ON
I (21134) LAB8: 💡 LED ON (fake_value > 50)
I (21134) LAB8: ==========================================
I (25134) LAB8: 📋 Reading #4
I (25134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (25134) SENSOR: 🌡️  Temperature: 26.2°C
I (25134) SENSOR: 💧 Humidity: 82.0%
I (25134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (25134) SENSOR: 📈 All sensors operating normally
I (25134) LED: ❌ LED OFF from file: ./managed_components/led/LED/src/led.c, line: 27
I (25134) LED: 🔴 LED is now OFF
I (25134) LAB8: 💡 LED OFF (fake_value <= 50)
I (25134) LAB8: ==========================================
I (29134) LAB8: 📋 Reading #5
I (29134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (29134) SENSOR: 🌡️  Temperature: 35.0°C
I (29134) SENSOR: 💧 Humidity: 86.2%
I (29134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (29134) SENSOR: 📈 All sensors operating normally
I (29134) LED: ❌ LED OFF from file: ./managed_components/led/LED/src/led.c, line: 27
I (29134) LED: 🔴 LED is now OFF
I (29134) LAB8: 💡 LED OFF (fake_value <= 50)
I (29134) LAB8: ==========================================
I (33134) LAB8: 📋 Reading #6
I (33134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (33134) SENSOR: 🌡️  Temperature: 29.0°C
I (33134) SENSOR: 💧 Humidity: 68.0%
I (33134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (33134) SENSOR: 📈 All sensors operating normally
I (33134) LED: ❌ LED OFF from file: ./managed_components/led/LED/src/led.c, line: 27
I (33134) LED: 🔴 LED is now OFF
I (33134) LAB8: 💡 LED OFF (fake_value <= 50)
I (33134) LAB8: ==========================================
I (37134) LAB8: 📋 Reading #7
I (37134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (37134) SENSOR: 🌡️  Temperature: 28.3°C
I (37134) SENSOR: 💧 Humidity: 79.0%
I (37134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (37134) SENSOR: 📈 All sensors operating normally
I (37134) LED: ✅ LED ON from file: ./managed_components/led/LED/src/led.c, line: 20
I (37134) LED: 🟢 LED is now ON
I (37134) LAB8: 💡 LED ON (fake_value > 50)
I (37134) LAB8: ==========================================
I (41134) LAB8: 📋 Reading #8
I (41134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (41134) SENSOR: 🌡️  Temperature: 33.0°C
I (41134) SENSOR: 💧 Humidity: 83.4%
I (41134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (41134) SENSOR: 📈 All sensors operating normally
I (41134) LED: ✅ LED ON from file: ./managed_components/led/LED/src/led.c, line: 20
I (41134) LED: 🟢 LED is now ON
I (41134) LAB8: 💡 LED ON (fake_value > 50)
I (41134) LAB8: ==========================================
I (45134) LAB8: 📋 Reading #9
I (45134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (45134) SENSOR: 🌡️  Temperature: 34.3°C
I (45134) SENSOR: 💧 Humidity: 77.3%
I (45134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (45134) SENSOR: 📈 All sensors operating normally
I (45134) LED: ✅ LED ON from file: ./managed_components/led/LED/src/led.c, line: 20
I (45134) LED: 🟢 LED is now ON
I (45134) LAB8: 💡 LED ON (fake_value > 50)
I (45134) LAB8: ==========================================
I (49134) LAB8: 📋 Reading #10
I (49134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (49134) SENSOR: 🌡️  Temperature: 32.8°C
I (49134) SENSOR: 💧 Humidity: 89.1%
I (49134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (49134) SENSOR: 📈 All sensors operating normally
I (49134) LED: ❌ LED OFF from file: ./managed_components/led/LED/src/led.c, line: 27
I (49134) LED: 🔴 LED is now OFF
I (49134) LAB8: 💡 LED OFF (fake_value <= 50)
I (49134) LAB8: ==========================================
I (53134) LAB8: 📋 Reading #11
I (53134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (53134) SENSOR: 🌡️  Temperature: 34.1°C
I (53134) SENSOR: 💧 Humidity: 72.9%
I (53134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (53134) SENSOR: 📈 All sensors operating normally
I (53134) LED: ❌ LED OFF from file: ./managed_components/led/LED/src/led.c, line: 27
I (53134) LED: 🔴 LED is now OFF
I (53134) LAB8: 💡 LED OFF (fake_value <= 50)
I (53134) LAB8: ==========================================
I (57134) LAB8: 📋 Reading #12
I (57134) SENSOR: 📊 Reading sensor data from file: ./managed_components/sensor/Sensor/sensor.c, line: 18
I (57134) SENSOR: 🌡️  Temperature: 25.5°C
I (57134) SENSOR: 💧 Humidity: 97.3%
I (57134) SENSOR: ✅ Sensor status check from file: ./managed_components/sensor/Sensor/sensor.c, line: 30
I (57134) SENSOR: 📈 All sensors operating normally
I (57134) LED: ✅ LED ON from file: ./managed_components/led/LED/src/led.c, line: 20
I (57134) LED: 🟢 LED is now ON
I (57134) LAB8: 💡 LED ON (fake_value > 50)
I (57134) LAB8: ==========================================
```
