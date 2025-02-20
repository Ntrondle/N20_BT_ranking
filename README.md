# N20 Motor Testing for Box Turtle Applications

This repository documents the testing and ranking of N20 motors for use in box turtle-related projects. The motors are evaluated based on the following criteria:

1. **How close to 500 RPM?**
   - Testing for accuracy in achieving the desired rotational speed of 500 RPM.
2. **Noise**
   - Measuring the decibel levels during operation to ensure quiet performance.
3. **Stall Current**
   - Determining the current drawn under stall conditions to gauge electrical efficiency and safety.
4. **Heat Under Normal Operation**
   - Monitoring temperature levels during continuous use under typical loads.
5. **Heat Under Stall Condition**
   - Recording temperature increase when the motor is stalled to assess thermal safety margins.

## Testing Procedure

### Materials Required:
- N20 motors (various models)
- Power supply with adjustable voltage and current limits
- Tachometer for measuring RPM
- Decibel meter for noise measurement
- Multimeter for measuring current
- Thermal camera or thermometer for heat analysis
- Test rig for consistent load application

### Steps:
1. **RPM Testing**
   - Set the motor to operate at its rated voltage.
   - Measure the RPM using a tachometer.
   - Compare the measured RPM with the target of 500 RPM.

2. **Noise Testing**
   - Run the motor under no load at rated voltage.
   - Use a decibel meter to measure noise levels at a fixed distance (e.g., 10 cm).

3. **Stall Current Testing**
   - Gradually increase load until the motor stalls.
   - Record the current using a multimeter.

4. **Heat Under Normal Operation**
   - Operate the motor under a typical load for 30 minutes.
   - Use a thermal camera or thermometer to measure the motor's surface temperature.

5. **Heat Under Stall Condition**
   - Stall the motor under controlled conditions for 10 seconds.
   - Measure the surface temperature immediately after the test.

## Ranking System
- **RPM Accuracy**: Score based on how close the motor's RPM is to 500 (e.g., 10 points for 500 RPM, minus 1 point for every 5 RPM deviation).
- **Noise**: Lower decibel levels receive higher scores.
- **Stall Current**: Lower stall current receives higher scores.
- **Heat Under Normal Operation**: Lower temperature rise receives higher scores.
- **Heat Under Stall Condition**: Lower temperature rise receives higher scores.

### Test Results and Rankings
| Motor Model                                        | RPM Accuracy | Noise (dB) | Stall Current (mA) | Heat Normal (°C) | Heat Stall (°C) | Total Score |
|---------------------------------------------------|--------------|------------|---------------------|---------------------|-------------------|-------------|
| [Motor 1](https://fr.aliexpress.com/item/1005007573764916.html) | 5            | 6          | TBD                 | TBD                 | TBD               | TBD         |
| [Motor 2](https://fr.aliexpress.com/item/1005005480039032.html) | 10           | 7          | TBD                 | TBD                 | TBD               | TBD         |
| [Motor 3](https://fr.aliexpress.com/item/32922112793.html)       | 10           | 8          | TBD                 | TBD                 | TBD               | TBD         |
| [Motor 4](https://fr.aliexpress.com/item/1005006785073459.html)  | 10           | 6          | TBD                 | TBD                 | TBD               | TBD         |

### Notes
- **Motor 1**: Speed is 250 RPM and noise is measured at >30 dB.
- **Motor 2**: Speed is 500 RPM and noise is measured at >25 dB.
- **Motor 3**: Speed is 500 RPM and noise is measured at >20 dB.
- **Motor 4**: Speed is 500 RPM and noise is measured at >30 dB.

## Contributions

Feel free to contribute by:
- Suggesting new motor models for testing
- Improving the testing rig or procedures
- Adding test results

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
