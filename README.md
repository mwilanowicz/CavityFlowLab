# CavityFlowLab
Real-time, interactive simulation of driven cavity flow using the Lattice Boltzmann Method (LBM).

# Technologies Invovlded
- Qt for user interface
- OpenCL for parallel computation on GPU
- OpenGL for rendering simulation

# Weekly Schedule
- **19.03:**
	- Project structure (source and header files).
	- Installation of required libraries (Qt, OpenCL, OpenGL).
	- GUI setup (Qt configuration).
- **26.03:**
	- Implementation of basic GUI in Qt.
	- Handling user input for parameters (Re, velocity, obstacles).
	- Connecting GUI to the main logic of the application.
- **02.04:**
	- Integrating existing LBM solver into the project.
	- Running small-scale tests to validate correctness.
- **09.04:**
	- Modifying LBM solver for GPU execution (OpenCL parallelization).
	- Writing OpenCL kernels for LBM streaming and collision steps.
- **16.04:**
	- Debugging and testing LBM GPU implementation.
	- Performance comparison: CPU vs. GPU.
- **23.04:**
	- Implementing OpenGL rendering for simulation visualization.
	- Connecting OpenGL with OpenCL (displaying real-time simulation).
- **30.04:**
	- Optimizing OpenCL implementation (memory access, kernel execution).
	- Stability and correctness testing of LBM on GPU.
- **07.05:**
	- Testing GPU-accelerated LBM solver on different hardware.
	- Refining GUI and user interaction.
- **14.05:**
	- Preparing documentation for code and user instructions.
	- Performance testing for different Reynolds numbers.
- **21.05:**
	- Final code refinements.
	- Preparing for final testing.
- **28.05:**
    - Final testing and polishing
- **04.06 & 11.06:**
	- Project presentation.

