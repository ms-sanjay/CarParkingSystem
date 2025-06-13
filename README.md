# Smart Car Parking System using 8051

This project is a smart car parking system made using the 8051 microcontroller, IR sensors, servo motors, and an LCD display. It shows the number of free parking slots and controls gate access automatically based on car entry and exit.

## Components Used
- 8051 Microcontroller
- IR Sensors (Entry and Exit)
- Servo Motors (Gates)
- LCD Display
- Keil µVision (for coding and simulation)
- Proteus (for circuit simulation)

## How it Works
- When a car arrives at the entrance, the IR sensor detects it.
- If a parking slot is available, the entrance gate opens using a servo motor.
- The available slots count is reduced and shown on the LCD.
- Similarly, when a car exits, the exit IR sensor detects it and the exit gate opens.
- The slots count increases again.

The system won’t allow entry if all slots are full, and won’t open the exit gate if no car is parked.

## Files Included
- `source_code.asm`: The Assembly code for the 8051 microcontroller
- `project_report.pdf`: Complete documentation
- `circuit_diagram.png`: Screenshot from Proteus
- `hardware_photo.jpg`: Real photo of the working hardware
- `demo_video_link.txt`: Link to the demonstration video

## Contributors
- Sanjay M S (22BML0106)
- Hariharasudhan V (22BEC0955)
- Pugalarusu M (22BEC0962)
- Hariharan N (22BEC0965)

## Demo Video
[Click here to watch](https://drive.google.com/file/d/1Ye1F6rvkmcXyYnLElvZshQH8VeqsdL7P/view)

