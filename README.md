![Blue](Gallery/BlueJaylogo.png)
# FTC Team #14473 Future - Image processing Framework [Currently in Intense Development]

<img src="Gallery/sample.png" alt="Kitten"
	title="A cute kitten" width="550" height="300" />
	
This library was made to simplify the agony in doing FTC computer vision in Java.   
It follows very simple rules:

- It can be used for all seasons. This code will always be useful unless FTC changes their software setup.

- If you don't need it, you should never see it. All the boilerpalce nitty gritty is handled by magick.

## Features

- **OpenCV Foundation Detection**
- **Opencv Stone Detection** (Pretty good 90%)
- **Opencv SkyStone Detection** (Bestest one)
- simplified interface for Vuforia and tensorflow
- All the above running simultaneously

## Maximizing Accuracy
- Angle the phone so that the field covers as much of the camera image as possible (best performance with elements on field)
- Don't let stones overlap vertically. The stone detector is optimized for horozontal rows of stones.
- Don't let elements get too far away. Small shapes will be calssified as noise
- Don't tilt the camera (like when you steer the car in asphalt 8). The shape classifier will get confused.

## Setup
1. Clone and make a new project at new>project>from version control>git in Android Studio. Code is in the `Teamcode` folder and `bluejay` module. We might do bintray hosting but haven't had time yet :p
2. Sync Gradle. Search for this command with ctrl+shift+a.
3. Examples are in the `teamcode` folder.

## Using the Library
I've been lax on documentation, so ask if there is ambiguity
First off, working code for everyone:

	*Stuff here is outdated, bleh. Check teamcode for example.	
	

## Contact
If you got questions, email me at <xchenbox@gmail.com> or alternatively, find us on Facebook <https://www.facebook.com/future14473>
We don't have a discord (yet). If there's any problems or ambiguity, shoot me an email

## Gallery

![hi!](Gallery/15-ann.JPEG)
![hi!](Gallery/16-ann.JPEG)
![hi!](Gallery/17-ann.JPEG)
![hi!](Gallery/18-ann.JPEG)
![hi!](Gallery/1-ann.JPEG)
![hi!](Gallery/2-ann.JPEG)
![hi!](Gallery/3-ann.JPEG)
![hi!](Gallery/4-ann.JPEG)
![hi!](Gallery/5-ann.JPEG)
![hi!](Gallery/7-ann.JPEG)
![hi!](Gallery/8-ann.JPEG)
![hi!](Gallery/9-ann.JPEG)
![hi!](Gallery/10-ann.JPEG)
![hi!](Gallery/11-ann.JPEG)
![hi!](Gallery/12-ann.JPEG)
![hi!](Gallery/13-ann.JPEG)
![hi!](Gallery/14-ann.JPEG)
