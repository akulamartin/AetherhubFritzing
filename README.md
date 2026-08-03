# Opening AetherHub in Fritzing

1. Download `aetherhub_fritzing_project.zip` and extract `aetherhub_circuit.fzz`.
2. Open **Fritzing**.
3. Go to **File > Open** and select `aetherhub_circuit.fzz`.

## Pinout Checklist:
- **Shared I2C Bus:**
  - Arduino `A4` (SDA) -> BME280 `SDA` & APDS-9960 `SDA`
  - Arduino `A5` (SCL) -> BME280 `SCL` & APDS-9960 `SCL`
- **Power:**
  - Arduino `3V3` -> Sensor Power Rails
  - Arduino `GND` -> Sensor Ground Rails
- **Interrupt:**
  - Arduino `D2` -> APDS-9960 `INT`
