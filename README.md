# rfdata_eda

An analysis of a selection of RF signal data with a particular focus on signal quality and environmental factors.

## The Data

[RF Signal Data](https://www.kaggle.com/datasets/suraj520/rf-signal-data): RF Signal data acquired via SDR H/W interfaced to DragonOS Focal.

### Columns

Categorical Fields:

- Modulation: The modulation type used for the RF signal. Options: AM, FM, QAM, BPSK, QPSK, 8PSK.
- Location: The location where the signal was observed (e.g., city and state/province).
- Device Type: The type of RF device used. Options: HackRF, Halow-U, SteamDeck.
- Antenna Type: The type of antenna used. Options: Omnidirectional, Directional, Dipole, Yagi.
- Weather Condition: The weather condition. Options: Sunny, Rainy, Cloudy.
- Interference Type: The type of interference. Options: None, Co-channel, Adjacent-channel, Intermodulation.
- Power Source: Whether the device is plugged into a power source. Options: Yes, No.
- Device Status: The current status of the device. Options: Streaming I/Q data, Transmitting beacon signal, Running game.

Quantitative Fields:

- Timestamp: The date and time of the signal observation.
- Frequency: The frequency of the RF signal in Hertz (Hz).
- Signal Strength: The strength of the RF signal in decibels relative to one milliwatt (dBm).
- Bandwidth: The bandwidth of the RF signal in Hertz (Hz).
- Temperature: The temperature at the location in degrees Celsius.
- Humidity: The relative humidity at the location as a percentage.
- Wind Speed: The speed of the wind at the location in kilometers per hour (km/hr).
- Precipitation: The amount of precipitation at the location in millimeters (mm).
- Battery Level: The remaining battery level of the device as a percentage.
- CPU Usage: The percentage of the CPU usage of the device.
- Memory Usage: The percentage of the memory usage of the device.
- WiFi Strength: The strength of the WiFi signal in dBm.
- Disk Usage: The percentage of the disk usage of the device.
- System Load: The system load of the device.
- Latitude: The latitude of the location.
- Longitude: The longitude of the location.
- Altitude: The altitude of the location in meters.
- Air Pressure: The air pressure at the location in hectopascals (hPa).
- I/Q Data: The in-phase and quadrature components of the signal as a complex valued array.

## Potential Analysis Avenues

### Signal Classification:

The dataset can be used to classify RF signals based on their modulation type, frequency, bandwidth, and other features. This can help in identifying specific types of signals, such as voice or data transmissions, and can aid in tasks such as signal detection, interception, and decoding.

### Interference Detection:

The dataset contains information about the type and level of interference present in the environment. This can be used to develop models for detecting and mitigating interference, which can improve the overall quality of the RF signal.

### Device Performance Optimization:

The dataset includes information about the type of RF device used to generate the signal, as well as its CPU usage, memory usage, and battery level. This can be used to develop models for optimizing the performance of RF devices, such as reducing power consumption or improving signal quality.

### Weather Condition Analysis:

The dataset provides information about the weather conditions at the time of signal observation, including temperature, humidity, wind speed, precipitation, and weather condition. This can be used to analyze the impact of weather conditions on RF signal propagation and to develop predictive models for signal behavior under different weather conditions.

### Geolocation:

The dataset includes latitude and longitude information for each signal observation. This can be used to develop models for geolocation of RF signals, which can aid in tasks such as tracking and surveillance.
