# Sound Localization Project

This project implements a sound localization algorithm using the **Delay-and-Sum (DAS)** method, applied for ultrasound image reconstruction.

## Features

- **Delay-and-Sum Algorithm**: Implements a beamforming technique to localize sound sources.
- **Image Reconstruction**: Generates spatial representations of sound sources.
- **Parameter Analysis**: Allows exploration of factors affecting localization accuracy, such as sampling rate and array parameters.
- **Visualization**: Produces plots that loaclise the obstacle.

## How It Works

1. **Data Collection**: Captures input signals from a microphone array.
2. **Preprocessing**: Filters and prepares signals for analysis.
3. **Localization**: Applies the DAS algorithm to compute the spatial position of sound sources.
4. **Reconstruction**: Maps sound intensity to each point in the constructed spatial grid.
5. **Analysis**: Evaluates accuracy and performance based on various parameters.

### Example Output
The output includes:
- **Spatial Map**: A heatmap of sound intensity in the analyzed area.

