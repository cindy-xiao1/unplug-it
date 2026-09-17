# Unplug-It
Unplug-It is an integrated system that combines a mobile app, energy-saving AI, and robot arm to safely reduce phantom power in homes.

<img width="1246" height="700" alt="Screenshot 2026-09-16 at 11 46 11 PM" src="https://github.com/user-attachments/assets/28d79179-3c59-402e-bd59-2f49f876f217" />
<img width="1247" height="701" alt="Screenshot 2026-09-16 at 11 46 20 PM" src="https://github.com/user-attachments/assets/8f9f2207-c3f9-42a4-a046-e574a7882fd1" />

## Community Problem and Who Benefits
The United States wastes a significant amount of electricity through devices that remain plugged in even when switched off. According to the Natural Resources Defense Council (NRDC), American households spend approximately $19 billion annually, or $165 per household, on electricity consumed by inactive but plugged-in devices. This is known as “phantom load,” or “vampire power,” and accounts for 44 million tons of CO₂ emissions each year, which can contribute up to 20% of a household’s monthly electricity bill.
This problem disproportionately affects families with limited resources, elderly individuals who may find unplugging devices physically difficult, and communities already burdened by rising energy costs. My project Unplug-It directly addresses this issue by helping households identify, monitor, and automatically unplug idle appliances. It also encourages users to reinvest their saved energy into community sharing and sustainability efforts.

## What the System Does
The mobile app allows users to scan living space using a phone camera and AI image recognition to build an appliance list and identify likely phantom-load devices. By integrating Home Energy Management System (HEMS) APIs, the system measures real-time wattage, distinguishes idle versus active use, and estimates energy and cost savings (kWh × local $/kWh).
The robot arm uses visual marker recognition with AprilTags placed near outlets or plugs. These markers allow accurate outlet identification and pose estimation, guiding a robot arm to safely unplug devices or flip switches using vision and force sensing. The robot confirms success, logs actions back to the app, and improves over time through reinforcement learning trained in simulation before deployment, creating a safe, automated, and scalable sustainability solution.
