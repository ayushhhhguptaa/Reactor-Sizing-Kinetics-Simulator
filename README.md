# Reactor-Sizing-Kinetics-Simulator
Isothermal vs. Adiabatic Reaction Modeling
📖 Overview
This project is a computational tool designed to solve a core challenge in chemical plant design: How big should a reactor be? Using Python, I developed two simulation models to calculate and compare the volumes of Continuous Stirred-Tank Reactors (CSTR) and Plug Flow Reactors (PFR). The project demonstrates how different thermal environments—constant temperature (Isothermal) versus self-heating (Adiabatic)—drastically change the efficiency and size requirements of industrial equipment.

🚀 Key Features
Dual-Environment Simulation: Toggle between Isothermal (steady temperature) and Adiabatic (temperature increases as the reaction releases heat) conditions.
Simpson’s 1/3 Rule Integration: Implemented a high-precision 5-point quadratic formula to calculate PFR volumes, offering better accuracy than standard linear methods.
Levenspiel Plot Visualization: Generates industry-standard plots to visually compare reactor footprints and efficiency.
Kinetics Engine: Models 1st-order reaction kinetics with temperature-dependent rate shifts.

🧪 The Science Simplified
1. The Reactors
CSTR (The "Blender"): Imagine a giant stirred tank. It’s simple but often requires more space because the concentration of "fuel" drops instantly upon entering.
PFR (The "Pipe"): Think of a long tube. Chemicals react as they flow through, making it generally more space-efficient.

2. The Thermal Shift
Isothermal: We assume the tank is cooled perfectly. The reaction speed stays steady.
Adiabatic: We let the reaction heat itself up. In an exothermic reaction, this heat acts like a "turbo boost," speeding up the reaction and allowing us to use a smaller reactor to get the same result.

🛠️ Tech Stack
Language: Python 3.x
Libraries: NumPy (Mathematical Engine), Matplotlib (Data Visualization)
Methodology: Numerical Analysis via Simpson’s 1/3 Rule


💡 Why This Matters
As a Chemical Engineering student with an interest in Space Science and UI/UX, I built this tool to make "invisible" chemical math visible.
