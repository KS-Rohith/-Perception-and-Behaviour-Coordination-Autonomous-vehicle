# -Perception-and-Behaviour-Coordination (Webots)
In developing an autonomous car controller in a simulated environment, I enhanced its capabilities to detect and respond to traffic lights.  while maintaining its existing behavior of moving forward, staying on the road, and taking random turns at junctions. This integration ensures safety and driving behavior.
In the development of an autonomous car controller within a simulated environment, I aimed to enhance the vehicle's capabilities by incorporating traffic light recognition and response. The existing controller enabled the car to move forward, stay on the road, and take random turns at junctions. However, to achieve more realistic and safe autonomous driving behavior, it was crucial to implement a mechanism for the car to detect and respond appropriately to traffic lights.

The desired behavior was to ensure that the car stops when encountering a red traffic light and continues moving once the traffic light turns green, without compromising the existing functionalities. This integration required a robust perception system to detect traffic lights and a reliable control mechanism to manage the car's stopping and starting actions based on the traffic light signals.

In this project, I developed and implemented the perception and control systems necessary for the car to respond to traffic lights effectively. The perception system was designed to accurately identify the state of the traffic lights (red or green) using sensor data and computer vision techniques. The control system was then responsible for stopping the car upon detecting a red light and resuming its motion when the light turned green, seamlessly integrating these new behaviors with the car's existing movement and navigation capabilities. This approach ensures the car maintains its path and continues to take random turns at junctions, while also adhering to traffic light signals, thereby enhancing both safety and realism in the simulation.
