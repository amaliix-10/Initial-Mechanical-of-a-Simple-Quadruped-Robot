# Initial-Mechanical-of-a-Simple-Quadruped-Robot
Conceptual mechanical design and torque analysis for a basic quadruped robot focused on stable locomotion
This project is a foundational step into the world of robotics. The goal here isn't to build a highly advanced or expensive robot dog. 
Instead, it is a hands-on experiment to understand the core mechanical principles that allow a four-legged robot to stand, balance, and walk.

----------------------------------------------------

# What makes this project ?
Most advanced robots you see online use complex computer programming and expensive motors for every single joint to move their legs. 

This project uses a much smarter and simpler approach:
We use a clever system of connected bars called a Linkage Mechanism. When just one central motor spins, 
it automatically pushes these bars in a perfect sequence, forcing the legs to lift, step forward, and push the ground. 
so The walking movement is built directly into the physical design of the robot, not into complex software code.

----------------------------------------------------

# The Core Components

Here is a quick breakdown of what I have designed and documented in the project file:

* **1. Body & Frame:** A solid central chassis that safely holds the motor in the middle and spreads the weight evenly to both sides.
* **2. Simple Movement (1 DoF):** The robot only needs **1 Degree of Freedom** per side. This means the legs follow a fixed path, allowing the robot to walk using cheap, everyday DC motors instead of 12 expensive servos.
* **3. Calculating the Motor Force (Torque):** I included the engineering formula ($T_{total} = m \cdot g \cdot L_{max}$) to calculate exactly how strong our motor needs to be to lift the robot's weight against gravity.
* **4. Balance:** The robot relies on **Static Stability**, meaning it is designed to always keep enough feet on the ground so it never tips over while moving.

----------------------------------------------------

# Challenges I am Solving
Building a mechanical robot comes with natural engineering puzzles that I am working on:
1. Wobbly Legs (Backlash): Because there are many connecting pins, any tiny looseness makes the legs shake. I solve this by using high-precision 3D printing or laser cutting.
2. Friction: Many moving parts cause rubbing, which slows down the motor. I plan to use tiny bearings to keep it smooth.
3. Steering: Running everything on one motor means it only walks in a straight line. To let it turn, I will eventually upgrade it to use two independent motors (one for the left legs, one for the right).

----------------------------------------------------

# Project Status
- Create conceptual design and walking mechanism.
- Calculate initial motor torque requirements.
- 3D print/Laser cut the physical parts.
- Assemble and test the first walking steps!
