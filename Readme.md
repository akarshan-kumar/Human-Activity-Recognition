# Detection of Human Movement Using Sensor Data with LSTMs

This project involves the detection of human movement by analyzing sensor data using various Long Short-Term Memory (LSTM) network architectures.

## Model Performance

The table below summarizes the performance of different LSTM architectures tested in this project:

| S.NO. | Architecture     | Test Accuracy |
|-------|------------------|---------------|
| 1     | LSTM(8+16)       | 70.00%        |
| 2     | LSTM(16+32)      | 90.91%        |
| 3     | LSTM(32+64)      | 92.23%        |
| 4     | LSTM(8+16+32)    | 94.82%        |
| 5     | LSTM(16+32+64)   | 93.28%        |

## Overview

LSTM networks are a type of recurrent neural network (RNN) that are well-suited for time series and sequential data analysis. In this project, we explored several LSTM architectures to determine their effectiveness in accurately detecting human movement from sensor data.

## Architectures

1. **LSTM(8+16)**:
   - Two layers: the first with 8 units and the second with 16 units.
   - Achieved a test accuracy of 70.00%.

2. **LSTM(16+32)**:
   - Two layers: the first with 16 units and the second with 32 units.
   - Achieved a test accuracy of 90.91%.

3. **LSTM(32+64)**:
   - Two layers: the first with 32 units and the second with 64 units.
   - Achieved a test accuracy of 92.23%.

4. **LSTM(8+16+32)**:
   - Three layers: the first with 8 units, the second with 16 units, and the third with 32 units.
   - Achieved a test accuracy of 94.82%.

5. **LSTM(16+32+64)**:
   - Three layers: the first with 16 units, the second with 32 units, and the third with 64 units.
   - Achieved a test accuracy of 93.28%.

## Conclusion

The results indicate that increasing the complexity of the LSTM architecture generally improves the model's accuracy in detecting human movement. The LSTM(8+16+32) architecture achie
