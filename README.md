# COMS514_VirtualPerimeter
Virtual Perimeter Assistant using Kinect

Virtual Perimeter Assistant is a desktop-enabled, online, sensor-based elderly support software. Its key features are

- Quick warning given to elderly people when they approach risky areas through a call to their cell phone
- Economical (cost is < $100, excluding cost of cell phone and a computer)
- Simple to use and configure


### Version
1.0.0

### Tech

Virtual Perimeter Assistant uses the following software:

* [Kinect SDK] - version 1.8 - Software to control the sensor
* [Twilio API] - Service to make calls to cell phone from computer
* [Microsoft .Net framework 4.0] - Microsoft .Net Framework 4.0
* [Visual Studio 2012] - Optional, required for development


### Installation

1. Install Kinect SDK
2. Create a Twilio account
3. Verify the required mobile number in Twilio
4. Create an application in Twilio and enable Voice support for it
5. Obtain the authentication token, applicatino sid and account sid 
6. Update them in MainWindow.xaml.cs file of source code
7. Build the project and execute it
8. Test it as explained in the demo
9. To configure the distances (ie. marking the risky areas) upate the CallTriggerDistance and MessageTriggerDistance variable in the MainWindow.xaml.cs file


###How it works
1. Start server
2. Update the server with perimeter fencing covering both Warning and Risky areas in your home as may be required
3. Place Kinect Motion sensor at angle 70 degrees to the room area. 
4. Ensure the elderly person is with his/her mobile phones switched "on" so they could receive warning calls
5. Caregivers should also ensure their phones are switched "on" always so that they get calls for rescue when elderly is in danger .



### Development

The software uses C# language for development.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

[Kinect SDK]: <https://www.microsoft.com/en-us/download/details.aspx?id=40278>
[Twilio API]: <https://www.twilio.com/docs/csharp/install>
[Microsoft .Net framework 4.0]: <https://www.microsoft.com/en-us/download/details.aspx?id=17851>
[Visual Studio 2012]: <https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=0ahUKEwiq_r7p4sLJAhWRt4MKHRgoAasQFgguMAE&url=https%3A%2F%2Fmsdn.microsoft.com%2Fen-us%2Flibrary%2Fdd831853(v%3Dvs.110).aspx&usg=AFQjCNHGjM8BieX0YSMZ70nYsQNSta3kjw&sig2=MBlJ-lLwai32nwyk-Uusyw>


Team members contacts:
1. Oluwafemi Richard Oyeleke - richievet2003@yahoo.com
2. Minghui Zhao				 - mhzhao@iastate.edu			
3. Arvind Ranganathan		 - arvindanekal@gmail.com
4. Anugrah Saxena			 - anugrah@iastate.edu
5. Le Zhang					 - lezhang@iastate.edu
