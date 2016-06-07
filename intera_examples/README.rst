intera_examples
===============

Examples for utilizing the Intera SDK Interface to communicate with robots from Rethink Robotics

Code & Tickets
--------------

+-----------------+----------------------------------------------------------------+
| Documentation   | http://sdk.rethinkrobotics.com/wiki                            |
+-----------------+----------------------------------------------------------------+
| Issues          | https://github.com/RethinkRobotics/intera_sdk/issues           |
+-----------------+----------------------------------------------------------------+
| Contributions   | http://sdk.rethinkrobotics.com/wiki/Contributions              |
+-----------------+----------------------------------------------------------------+

intera_examples Repository Overview
-----------------------------------

::

     .
     |
     +-- scripts/                                  example program executables
     |   +-- analog_io_rampup.py
     |   +-- digital_io_blink.py
     |   +-- gripper_action_client.py
     |   +-- gripper_cuff_control.py
     |   +-- gripper_joystick.py
     |   +-- gripper_keyboard.py
     |   +-- head_action_client.py
     |   +-- head_wobbler.py
     |   +-- ik_service_client.py
     |   +-- joint_position_file_playback.py
     |   +-- joint_position_joystick.py
     |   +-- joint_position_keyboard.py
     |   +-- joint_position_waypoints.py
     |   +-- joint_recorder.py
     |   +-- joint_torque_springs.py
     |   +-- joint_trajectory_client.py
     |   +-- joint_trajectory_file_playback.py
     |   +-- joint_velocity_puppet.py
     |   +-- joint_velocity_wobbler.py
     |   +-- navigator_io.py
     |   +-- send_urdf_fragment.py
     |   +-- xdisplay_image.py
     |
     +-- launch/                                   example program launch scripts
     |   +-- gripper_action_client.launch
     |   +-- gripper_joystick.launch
     |   +-- joint_position_joystick.launch
     |   +-- joint_trajectory_client.launch
     |   +-- joint_trajectory_file_playback.launch
     |
     +-- src/                                      intera_examples api
     |   +-- intera_examples/                      example classes
     |   +-- intera_external_devices/              external device classes
     |
     +-- share/                                    shared example program resources
     |
     +-- cfg/                                      dynamic reconfigure example configs


Other Baxter Repositories
-------------------------

+------------------+-----------------------------------------------------+
| intera_common    | https://github.com/RethinkRobotics/intera_common    |
+------------------+-----------------------------------------------------+

Latest Release Information
--------------------------

http://sdk.rethinkrobotics.com/wiki/Release-Changes