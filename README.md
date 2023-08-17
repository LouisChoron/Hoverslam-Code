# Hoverslam-Code
An attempt to predict when to start a simulated SpaceX Falcon rocket landing burn in 1D, accounting for weight and drag, to allow for a safe touchdown.

This was a project I completed over the Summer of 2021 out of my own interest. The code is messy and imperfect, however I could successfully automate different rocket landing scenarios in 1D (different start heights, weights and velocities) and iterate the burn height until they all landed with approx. 0 m/s at approx 0 m. Ultimately, I created a graph of when to start burning for a successful landing, for a range of different scenarios. This is unfinished, however would give a good starting point/estimate for when to start the burn.

To run the code:
1. Make sure the Data set is installed in the same directory as the code file.
2. Run the imports cell at the beginning of the code file.
3. Skip the "Creating Data" cell, and instead navigate to the "TEST USING CREATED DATA SETS" cell.
4. Run this cell, to simulate a landing. You can change the test() function parameters, which are velocity, height and percent of initial fuel.

5. I have completed this project multiple times, firstly on paper, then Excel and here Python. I plan to complete it again someday using reinforcement learning!

Thank you! :)
