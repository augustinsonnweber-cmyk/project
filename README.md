# project

BOM

Item	Description	Quantity	Est. price	Link	Status
Raspberry Pi 5 16GB	Main computer	1	0 Euros	---	Already owned
Power Supply	Official USB-C power supply	1	0 Euros	---	Already owned
Microphone Array/speaker	WM8960 Audio HAT Compatible with Raspberry Pi 5	1	25 Euros	https://www.amazon.de/-/en/WM8960-Audio-HAT-Compatible-Raspberry/dp/B0DY1LTBP5/ref=sr_1_6?crid=13JPV1OQA0PG3&dib=eyJ2IjoiMSJ9.IoXMjfZtGLJBEe3Hb7VRJKprJyjwg0Uq9LLG1Iz0HbE4h6kcwCF_qZg_3S3GVUyzmvlazo4C8ZQ6B7wCgXfMynPrqbUFtCxDo0iWD0MhjNfrq4CmbUkeEO6lCZBMPEWoS9h9HHMZemmuRLjZdaJa_YVYTGbPfVgFH5iMX2CvWGvlZjlTldDqBSoLL_uhbX-f.glI2rS4yA7oWPgLvkZICWP5caYivMPEsi0gPfUChyqA&dib_tag=se&keywords=Raspberry+Pi+microphone+array+HAT+Pi5&qid=1792924483&s=computers&sprefix=raspberry+pi+microphone+array+hat+pi5%2Ccomputers%2C168&sr=1-6


this is my project for hack club. i am making a voice assistant for home assistant using a raspberry pi 5. it uses a waveshare wm8960 audio hat that has two built in microphones and comes with a 5 watt speaker so it can hear commands and talk back.

the main idea is to make something that works locally without sending voice data to amazon or google. it connects to home assistant using wyoming satellite. when you say a wake word, it sends the audio to the home assistant server over wifi. home assistant uses whisper for speech to text, figures out what you want to do, and uses piper to turn the answer back into voice audio. then the speaker plays the response.

for hardware i already have the raspberry pi 5 and the power supply and a microSD card. i just need the audio hat with the speaker to make it work. the audio hat plugs right into the top pins of the raspberry pi 5. the software side will run linux with the wm8960 drivers and wyoming satellite software.

the goal is to control smart home devices like lights and switches by talking to the raspberry pi 5 instead of using a phone app or a cloud speaker.
