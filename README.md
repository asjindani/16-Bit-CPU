# 16-Bit-CPU

A fully-automated 16-bit CPU designed by Ali Shah for the Introduction to Computing (CSE 101) course in the Fall 2024 semester at IBA Karachi.

The CPU circuit has been designed using a free and open-source software called [Logisim Evolution](https://github.com/logisim-evolution/).

## Directory Structure

The essential files have been stored in the `CPU` directory, which allow the user to write and execute any program script on the CPU.

The `scripts` directory contains scripts for four different programs that were used to test us during the course.

Each program reqires three image files:
- Instruction RAM (contains the instructions)
- RAM A (contains the numerical values for A)
- RAM B (contains the numerical values for B)

The `docs` directory contains the mandatory supporting documents for the CPU, which assess the minimum requirements, functionality, good design choices, poor design choices, and a  summary of the architecture.

## Getting Started

To use the CPU, follow the given steps.

1. Download and install [Logisim Evolution](https://github.com/logisim-evolution/).

2. Clone this repository on your system.

3. Choose one of the scripts in the `scripts` directory or create your own script using the `Flow.xlsx` file in the `CPU` directory.

4. Open the `CPU.circ` file in the `CPU` directory using Logisim.

5. Right click the instruction RAM and click on `Load image`.

6. Navigate to the directory that contains the script files and import the instruction RAM file of your chosen script.

7. Repeat the last two steps for RAM A and RAM B.

8. Run the program using by enabling Auto-Tick in `Simulate`.

9. Notice the changes in the three RAMs as your program is executed.

10. Finally, you should see your desired value output in one of the RAMs as the program ends depending on the instruction set you used.