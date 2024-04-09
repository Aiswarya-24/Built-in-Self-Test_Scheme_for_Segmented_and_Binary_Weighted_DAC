### Built-in-Self-Test (BIST) Scheme for Segmented and Binary Weighted DAC

#### Overview
This project presents a 10-bit segmented current-steering Digital-to-Analog Converter (DAC) designed with an integrated Built-in-Self-Test (BIST) circuit. The BIST circuit includes on-chip current references, an offset-compensated comparator, and digital control logic to enable self-testing functionalities.

#### Key Features
- **10-bit Segmented DAC**: The DAC architecture employs both segmented and binary weighted techniques for enhanced performance.
- **BIST Circuit**: Integrated BIST circuitry enables on-chip testing without the need for external equipment.
- **Current References**: On-chip current references ensure accurate and stable operation of the DAC.
- **Offset-Compensated Comparator**: The comparator is designed to compensate for offset errors, improving the accuracy of test results.
- **Digital Control Logic**: Enables control and configuration of the self-test operation.

#### Application
The BIST scheme is designed for several key applications:
- **Linearity Error Testing**: The BIST allows for the verification of linearity across the DAC's output range.
- **Integral Non-linearity (INL) Estimation**: INL testing helps to quantify deviations from an ideal transfer function.
- **Differential Non-linearity (DNL) Analysis**: DNL testing helps to assess the step size accuracy of the DAC.

#### Tools Used
- **Cadence Virtuoso**: The design and simulation of the DAC and BIST circuitry were performed using Cadence Virtuoso, a leading EDA tool for integrated circuit design.



