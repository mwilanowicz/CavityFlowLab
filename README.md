# CavityFlowLab
A program for experimenting with fluid dynamics in the driven cavity problem.
Users can adjust simulation parameters, draw obstacles inside the cavity to modify its flow geometry, and observe the evolution of their simulation in real time.

The simulation utilizes the Lattice Boltzmann Method (LBM) with parallel execution on CPU.

# Technologies Involved
- Qt - for the user interface
- std::threads – for parallel computation on CPU (local execution)
- OpenFrameworks – for rendering the simulation

# Weekly Schedule

**26.03:**

- Project structure (source and header files).
- Installation of required frameworks (Qt, openFrameworks).
- GUI and main application setup.

**02.04:**
- Implementation of basic GUI functionalities (Run, Restart, Exit).
- Connecting GUI to the main application.
- Handling user input for parameters (Reynolds number, cavity's velocity, fluids viscosity).
-  Basic obstacle selection (square, circle, triangle).

**09.04:**
- Integrating LBM solver into the project.
- Defining basic obstacles with boundary conditions inside the solver and linking them to the GUI.
- Implementing "run-once" simulation for obstacle handling:
  - Users define obstacles & parameters, then start the simulation.
  - Obstacles and parameters remain fixed until a reset is triggered.

**16.04:**
  - Modifying LBM solver for parallel execution on CPU (std::threads parallelization).
  - Paralellisation testing (performance comparison with single thread). 

**23.04:**
- Implementing free-form obstacle drawing using the mouse.
- Validation of user-drawn obstacles with LBM boundary conditions.

**30.04:**
- Implementing openFrameworks visualization (velocity streamlines with heatmap).
- Connecting visualization to solver data.

**07.05:**
- Performance testing for different numbers of threads (scalability tests).

**14.05 & 21.05 & 28.05:**
- Final code refinements.
- Final testing and polishing

**04.06 & 11.06:**
- Project presentation.

