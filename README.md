# purr
DIY automatic pet feeder with ESP32 microcontroller, a stepper motor, and home assistant 
Objective: feed the pet on schedule or on-demand with alexa integrated.

Especially build for pandora :)

Structure:

purr/

├── README.md

├── esp32/

│   └── feeder_web_server.ino  # ESP32 code for web server and motor control

├── home_assistant/

│   ├── automation.yaml         # Automation for feeding schedules

│   └── configuration.yaml      # REST command setup for Home Assistant

└── requirements.txt            # Dependencies
