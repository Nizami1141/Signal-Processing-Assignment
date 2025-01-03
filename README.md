# Signal Processing - Assignment 2

This repository contains the solution for Signal Processing Assignment 2. The objective of this assignment is to perform signal modulation, filtering, and reconstruction using Python. 

## Assignment Tasks

1. **Generate Signals:**
   - Create two random signals, `x1` and `x2`, with low-frequency content (<1 rad/sec) using the `numpy` library.
   - Define the time array ranging from -50 to 50 with 0.01 increments.
   - Plot the generated signals.

2. **Signal Modulation:**
   - Modulate `x1` with `cos(10t)` and `x2` with `cos(20t)` to produce `x1m` and `x2m`.
   - Plot the modulated signals.

3. **Signal Addition:**
   - Add the two modulated signals (`x1m` and `x2m`) to create a combined signal `x`.
   - Plot the combined signal.

4. **Bandpass Filtering:**
   - Extract `x1m` from `x` using a bandpass filter, store it as `x1m_extracted`.
   - Repeat the process for `x2m` to get `x2m_extracted`.
   - Use `np.convolve()` for convolution.

5. **Signal Reconstruction:**
   - Reconstruct the original signals (`x1` and `x2`) by:
     - Multiplying `x1m_extracted` with `cos(10t)` and applying a low-pass filter to get `x1_reconstructed`.
     - Repeating the same steps for `x2m_extracted` to obtain `x2_reconstructed`.

6. **Visualization:**
   - Plot `x1` and `x1_reconstructed` on the same figure.
   - Plot `x2` and `x2_reconstructed` on the same figure.

## Repository Contents

- **`assignment_solution.py`**: The Python script containing the implementation for all the tasks listed above.
- **Plots**: Visualizations generated during the process.
- **README.md**: This file.

## Requirements

The following Python libraries are required to run the script:
- `numpy`
- `matplotlib`

You can install the required libraries using pip:

```bash
pip install numpy matplotlib
