Added docker for simulating a robotic dog from the Volt brothers. 
Change path in 77 line in Dockerfile.

Have tested in ubuntu 24:
``` roslaunch mors bringup_sim.launch ```

![image](https://github.com/user-attachments/assets/178f15e5-892c-4d68-92f5-f0831d643206)

``` rosservice call /robot_action "cmd: 6.0" ```

![image](https://github.com/user-attachments/assets/e130d4cf-44c2-448d-b326-e3dc1561e177)

original pkg:

https://github.com/voltdog/mors_base

https://github.com/voltdog/mors_pc

https://github.com/loco-3d/whole_body_state_msgs.git
