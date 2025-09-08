Project Settings:

IDE and Compiler:

	Developed using: Visual Studio 2022
	Target Platform: 10.0.22621.0

Build Configuration:

	Debug:
	     Optimization: Disabled
	     Enable Intrinsic Function:	No
	     Whole Program Optimization: No

	Release:
	     Optimization: Maximum Optimization (Favor Speed) (/O2)
	     Enable Intrinsic Function:	Yes (/Oi)
	     Whole Program Optimization: Yes

Architecture:
	Target Architecture: x64

Libraries Dependencies:

Fmod	  Task: To create channels and sounds and use the creation to play/stop/resume/pause the audios.
GLFW	  Task: OpenGL setup, Graphic Rendering, Keyboard/Mouse input
ImGUI	  Task: Uses ImGui library for showing List of Game Objects, the Game Object details after selecting the game object, background RGB change, showing FPS, assets library 		etcs.
Lua54	  Task: Serialization/De-Serialization of data from the .lua files.
sol2	  Task: Wrapper for Lua54, comes together.
glad	  Task: Extension of OpenGL for access to their functions
freetype  Task:	For font rendering with multiple font format support where it reads and loads each character's data from TTF font files and renders character textures based on 		the provided text.
KHR	  Task:	OpenGL debugging assistance
DLG 	  Task:	Creating ImGui tools/debugging interfaces graphically
stb	  Task: To load JPG/PNG images as textures, which are then used for rendering as textures for game objects.

How to build:

	Open the solution file: Grabity.sln
	Choose your desired configuration: Debug / Release
	Build the project by selecting Build > Build Solution, or by Ctrl+Shift+B
	Executable will be available in "Executable/Debug/" or "Executable/Release/"

Supported Platforms:

	The project is currently tested and supported on Windows 10 and later.
	The project must be built using NVidia Graphic PhysX processor

Configuration File:

	Configurations of the window/game setting is found at the same directory as the executable: config.lua
	The config currently contains screen resolution, Fullscreen mode

System Average Time:

	A system average time log will be produced at the same directory as the executable when the program has ran
