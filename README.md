# Introduction & Goals
Cameras are an important part of the sporting industry as they are the intermediary between the action and the fan​. With this, it is important that the camera be centered on what people care about, such as a ball or an important player. To avoid needing a camera operator, our team has developed a prototype that centers the camera on a selected object automatically. The goal of our project is to create a camera tracking prototype that can be used with multiple types of selected objects. The prototype should center the selected object in the center of the frame, putting emphasis on what is important. The actors used in our project were 2 stepper motors, the sensors used in our project were a camera and an ambient light sensor (ALS), and our advanced mechatronics topic was machine vision.
# Project Requirements Table
![ME 6705 Capture 1](https://github.com/mconnelly17/Camera-Tracking-Prototype/assets/126015712/8040d75a-fddc-42b4-bf78-8d7306a888e9)
# Project Requirements Discussion
![ME 6705 Capture 2](https://github.com/mconnelly17/Camera-Tracking-Prototype/assets/126015712/fb6cbf46-00fb-43f4-84ed-295d098d23b5)
### Why did we choose these?
- Threshold #1: Wanted user to see video output to simulate what the true application where this would be used was like. Allowed the user to watch the tracking mechanism in real-time and helped with debugging.
- Objective #2: Wanted to reach a threshold of what we considered "watchable". Did not want any lag.
- Objective #3: Wanted to always know the position and speed of motors to understand the bigger picture of the motion taken from start to finish and helped with debugging.
- Objective #4: Wanted to give the user extra capability to track whatever they wanted. In its true application, it should be able to track anything requested.
- Threshold #5: Removed (see rationale).
- Objective #6: Wanted quick tracking response time, so that the tracking mechanism was not delayed and did not constantly fall behind the play.
- Threshold #7: Wanted to provide the user with a good watching experience. No one would want to watch a sporting event with oscillating or jerking motions.
- Threshold #8: Wanted to full-range of motion tracking, so that the automated tracking did not lose the object.
- Objective #9: Wanted to track moving objects to simulate the true application (running players and moving balls).
### Did we achieve these?
- Threshold #1: Achieved. Uses a connected computer to interface with prototype​.
- Objective #2: Achieved. Using greyscale and lowest resolution possible, the camera was able to be viewed between 30 and 40 FPS pre-tracking and between 18 and 24 FPS during tracking​.
- Objective #3: Achieved. Both motor speeds (presented as step counts in x and y) and motor position (presented as change in angle from start reference) shown on front panel​.
- Objective #4: Achieved. No limit to what can be tracked​.
- Threshold #5: Removed (see rationale)​.
- Objective #6: Achieved. Quick response time (see demonstration).​
- Threshold #7: Achieved. Smooth tracking (see demonstration).​
- Threshold #8: Achieved. Always keeps object on screen (see demonstration).​
- Objective #9: Achieved. Can track moving object (see demonstration).
# Video Demonstration
- [Manual Control Video](https://youtube.com/shorts/X6N_BbKG_28?feature=share)
- [Light Conditions & Constant Object Video](https://youtu.be/gAOmJhzI1h8)
- [Moving Object Video](https://youtu.be/H2pl6y8ZW2Q)
- [Front Panel Video](https://youtu.be/bCesvpSmST0)

