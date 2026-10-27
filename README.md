# Active Toe Kinematics Simulator
A 2D interactive simulator demonstrating a real-time dynamic multi-link wheel geometry control system. This tool visualizes how advanced electronic suspension systems actively adjust wheel toe angles based on driving conditions to improve vehicle stability and agility. Most modern cars use multi-link suspension, allowing the tires to be adjusted to different angles. Most cars' toeangle can only be adjusted in the factory. However, adjusting the toe according to the road condition is effective for cars to drive more stably and more safely. For htis reason, I made this app.

## Features
Real-Time X-Ray Visualization: A top-down translucent chassis view highlighting the active multi-link suspension actuators.

Independent Wheel Telemetry: Live HUD displays showing precise toe and steering angles for all four wheels independently.

Dynamic Ackermann Geometry: Front wheels dynamically adjust turning angles based on steering input.

Active Rear Steering: Simulates counter-phase steering at low speeds for tight turning, and in-phase steering at high speeds for lane-change stability.

Braking Compensation: Simulates increased rear toe-in under heavy braking to stabilize the chassis.

Multiple Drive Modes: Switch between Comfort, Sport, and Autobahn modes to alter the system's kinematic reaction logic.

## How to Use
This project is entirely browser-based and requires no installation, server, or dependencies.

Clone this repository or download the file.

Double-click the HTML file to open it in any modern web browser (Chrome, Edge, Safari, Firefox).

Use the sliders in the control panel to adjust vehicle speed, steering angle, and braking force.

Observe the real-time wheel geometry changes and check the live telemetry log for system status.
