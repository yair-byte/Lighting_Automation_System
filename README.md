# Lighting_Automation_System
Lighting automation system with 6 sectors

For each sector there are 4 operating modes:
- Control the lights by means of light sensors.
- Control the lights by means of motion sensors.
- Control the lights by means of a schedule.
- Off (Normal Mode)
To configure the system the user interacts with a screen and a keyboard.

When starting the system, the main screen will show the current system time, as well as the lights on in the different sectors:

<img width="173" alt="Captura de pantalla 2023-01-07 172305" src="https://user-images.githubusercontent.com/56457143/211169133-c323c613-b776-4944-a2de-633cebd0cce4.png">

We see that it is 12:31 pm and the lights in bedroom 2, the bathroom and the exterior lights are on.
To enter the configuration mode, press the ENTER key. Once there, we can observe the configuration for the different sectors.
To access the system time configuration we must go down to the last item:

<img width="173" alt="Captura de pantalla 2023-01-07 172327" src="https://user-images.githubusercontent.com/56457143/211169172-5624234b-3fed-4809-babb-19a349f341fb.png">

If we enter the configuration of a sector we can see which of the four available modes is activated:

<img width="174" alt="Captura de pantalla 2023-01-07 172358" src="https://user-images.githubusercontent.com/56457143/211169195-0e4d4b7e-6c48-4407-837e-fd06a5750791.png">

In this case we see that the Light sensor mode is activated.
To activate one of the modes, we must indicate which one with the cursor and press the ENTER key. If the mode requires additional configuration then it will prompt the user. When you finish configuring a mode successfully, it will show on the screen that the configuration was saved successfully.
It should be noted that if at any time during the course of configuration the EXIT key is pressed, all the changes generated will not be saved, and the main screen will be displayed again.
Another important issue is that only one of the four modes can be active at any given time.
If we want to configure a sector to work with the schedule mode (Chrono Mode) we must first indicate the time at which the lights should be turned on and then the time at which they should be turned off. An important fact is that the configuration
of the minutes it can only be done 30 in 30 minutes; that is to say XX: 00 hs or XX: 30 hs.
Whenever a time is to be set, the user will first be prompted to change the hour, then press ENTER to set the minutes.
For the configuration of the light sensor mode, we will have to configure three sensitivity options (LOW, MID, HIGH).
Motion sensor setup and normal mode do not require additional setup.
The deactivated mode or Normal mode, what it will do is deactivate the other three modes so that the user can turn the lights on or off outside of this system.
This mode is the one found by default in all sectors. In this instance the lights are off.
