𝗙𝗼𝘂𝗿 𝗕𝗮𝗿 𝗟𝗶𝗻𝗸𝗮𝗴𝗲 𝗖𝗼𝗻𝘁𝗿𝗼𝗹𝗹𝗲𝗿 𝗣𝗿𝗼𝗷𝗲𝗰𝘁

I recently completed a project which allowed me to combined my skills in mechanical design and electrical integration. The goal was to create a 3D-printed four-bar linkage system alongside an Arduino MEGA and stepper motor to showcase a CNC-style homing sequence.

𝗧𝗵𝗲 𝗣𝗿𝗼𝗰𝗲𝘀𝘀:

 • 𝗠𝗲𝗰𝗵𝗮𝗻𝗶𝗰𝗮𝗹 𝗗𝗲𝘀𝗶𝗴𝗻: I used Autodesk Fusion 360 to analytically design the linkage and achieve my desired path. For smooth and easy assembly, I designed custom snap-fit pivot joints to keep the linkages close together and resist torsional forces on the linkages. I then created a test-print of just the joint to ensure my tolerances were correct before fully printing the model. 

 • 𝗣𝗿𝗼𝗯𝗹𝗲𝗺 𝗦𝗼𝗹𝘃𝗶𝗻𝗴: The CAD environment can only show you so much about how a part is going to act in the real world. After printing, I ran into issues during assembly as excess friction between the linkages was causing the stepper motor to stall. After sanding down the rubbing surfaces and adding lubricant, the linkages turned freely. 

 • 𝗧𝗵𝗲 𝗖𝗼𝗻𝘁𝗿𝗼𝗹𝗹𝗲𝗿: I integrated an Arduino MEGA with a motor controller and limit switch in order to create a closed-loop feedback system.

 • 𝗙𝗶𝗿𝗺𝘄𝗮𝗿𝗲: I developed a calibration sequence that allows the linkage to slowly creep up on a switch to find the zero position, mimicking a CNC machine measuring tool length or finding position. 

I'm looking forward to applying these lessons and continuing to grow my mechanical and electrical design skills as I dive deeper into my statics, circuits, and CAD/PDM classes this semester! 
