# 2026SP CMSC-2011 Team Robotics
## Team Members
- Prasmit Pokhrel (Builder, Debugger, Programmer)
- Alexander Stockton (Builder, Documentation, Programmer)

## Project
Design a robot using VEX V5 robotics parts and programs that, when placed in battle against other robots of the same variety, can either dismantle, disable, or immobilize them without dismantling, disabling, or immobilizing itself.

## Objectives Met
- [x] Design a robot with VEX V5 robotics parts/programs
- [ ] Dismantles, disables, or immobilizes other robots
- [ ] Without dismantling, disabling, or immobilizing itself

## Opponents List
- Snappy the Snapping Turtle (L)
- Thor (DNF)
- Ant (DNF)

## Controls
### Movement
(Up Arrow) -> Move front-left wheel forward \
(Down Arrow) -> Move front-left wheel back \
(X) -> Move front-right wheel forward \
(B) -> Move front-right wheel back \
(L1) -> Spin rear wheel to the left / Turn right \
(R1) -> Spin rear wheel to the right / Turn left

### Connections/Ports
(Front-Left Wheel) -> Port 11 \
(Front-Right Wheel) -> Port 12 \
(Rear Wheel) -> Port 13 \
(Antenna) -> Port 20 \

## Design
*Three-wheeled automobile with a somewhat-loose plow in front to shove opponents against walls; called "Sentinel" because it is designed to, at best, force a tie and, at worst, annoy opponents*

### Chassis
Sentinel has a rectangular 13.5in x 6.5in frame of interconnected plates with walls on both sides extending for the length of the chassis. The front half of the walls extend 2 inches from the floor of the chassis, protecting two front motors and the brain from being attacked on either side. Several stacked mounting plates on the top prevent the motor from being attacked from above. The rear half of the walls extend up 6.5in above the chassis' floor. There, its battery sits, protected by another plate above it. The very rear of the chassis has two supporting rear plates to prevent it from being flipped backward. It also has a vertical back plate to prevent being attacked from behind. The plates protecting critical points was designed for fighting Thor, which had a vertical hammer, but Sentinel's wheels fell off and was put out of commission before fighting Thor.

### Mobility
Sentinel uses two red motors and one green motor, two forward-aligned and one sideways aligned. In the front, two omnidirectional wheels controlled by red motors form Sentinel's Front-Wheel Drive. In the rear, one omnidirectional wheel controlled by a green motor forms Sentinel's in-place turning. Sentinal can turn either in-place by moving two or more wheels *or* around a focal point by only controlling one wheel at a time. Sentinel's size lets it go through narrow spaces, but not short ones. It also is somewhat slow due to the red motors, but it slides less when being pushed due to the weight and extra torque from the red motors.

### Power
Sentinel uses a standard battery VEX battery.

### Defense
Due to Sentinel's relatively small form factor, it can slip through narrow openings left by opponents when being pushed into tight spots. It can also turn in place to accomplish this. Sentinel's weight makes it slightly more difficult to push without excessive speed or torque, but its slow speed makes it easy to catch.

### Offense
Sentinel has a somewhat loose plow in the front with screws spiking outward from the plow to hook into opponents' mounting places and wheels. At best, this deadlocks Sentinel and its opponent. At worst, it causes a minor inconvenience, successfully accomplishing Sentinel's design of being very annoying.

## Potential Improvements
- Sentinel's front wheels quickly fell off. More secure mechanisms should hold the front wheels in place
- The excess of holes in the variety of mounting plates leaves Sentinel vulnerable to getting speared and dragged.
  - Trade offs with closing holes with alternating plates include significantly increased weight, reduced speed, increased power usage, and less mounting spots
- Sentinel's chassis could be either widened or elongated to fit the battery into the base chassis as well, allowing it to slip inside shorter spaces.
- Sentinel's slow speed and omnidirectional wheels make it difficult to push back when being cornered. Consider changing the types of wheels to increase grip.


Robotics repo, report, and archive for 2026SP-CMSC-2011
