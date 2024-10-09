# FreeRTOS-Projects


Projects built using FreeRTOS, a light-weight OS for embedded systems. The projects are implemented using STM32L151C8T6A board and SEGGER tool for debugging and analysis. 

Project structure


├── Source/                 # Application source code
│   ├── main.c              # Main application file
│   ├── freertos.c          # Code for freertos applications
├── Include/                # Header files
│   ├── FreeRTOSConfig.h    # customize the FreeRTOS kernel settings
│   └── main.h              # Main application header file
├── Middlewares/            # ThirdParty Files
│   ├── main.c              # Main application file
│   ├── freertos.c          # Code for freertos applications
└── README.md               # Project documentation
