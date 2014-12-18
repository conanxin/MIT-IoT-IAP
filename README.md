##说明

这是关于MIT上[Internet of Things: Connecting Anything and Everything to the Internet, a Hands-on Workshop](http://www.iotfestival.com/IoTIAP.html)这门课的笔记。

这门课主要关于Internet of Things，一周的课程。

##目录

- [背景阅读](#1)
- [视频教程](#2)
- [Dart学习材料](#3)
- [系统设置](#4)
- [参考硬件](#5)
- [课程安排](#6)
- [脚注](#7)

---
<a name="1"></a>
###背景阅读：

1.IoT - The Wikipedia view (compare and contrast to WoT - The Wikipedia View)   

2.The Internet of Things is Reaching Escape Velocity

3.Top 2014 Acquistions that Advanced the Internet of Things

4.CyberSecurity, The Internet of Things, and the Role of Government

5.How Smart, Connected Products are Transforming Competition

6.The Problem With The Internet of Things

7.Life (yet to be) Scripted - by Bob Frankston

8.GSMA: Connected Living (June 2014)

9.New cheap NFC sensor can transmit information on hazardous chemicals, food spoilage to smartphone

10.If We Build IoT, They Will Come. Right?

11.The Problem With The Internet Of Things

12.Enabling Open Markets for the Web of Things

13.Google's "Call for Research Proposals to participate in the Open Web of Things Expedition" is a blogpost by Vint Cerf over here and more detail on their "Request For Proposal: Open Web of Things An Internet of Things Research and Open Innovation Expedition" available here (and due for submission by January 21, 2015)

14.People, Places, Things: Web Presence for the Real World

15.IETF Journal, The Internet of Things, by Carsten Bormann, JP Vasseur, and Zack Shelby (Nov 2010)

---
<a name="2"></a>
###视频教程：

1.Electronics 101 (Collection of basic electronics videos, runtime about 90 minutes)

2.Making a Simple 4 Bit Computer (Waiting for Friday, Simon Inns, 5:25 minutes)

3.How a CPU works (21 minutes)

---
<a name="3"></a>
###Dart学习材料：

**Dart学习视频**

1.[Intro to Dart 介绍Dart](https://www.youtube.com/watch?v=5KlnlCq2M5Q) (4 minutes)

2.[Structured Web Programming: An Introduction to Dart](https://www.youtube.com/watch?v=vT1KmTQ-1Os) (37:21 minutes)

3.[WebAudio with Dart and WebRTC](https://www.youtube.com/watch?v=PMH1vM-dSc0) - The internet of musical things! (41 minutes)

**Dart阅读材料**

1.[Quick Start Intro to Dart 快速介绍Dart](https://www.dartlang.org/docs/dart-up-and-running/ch01.html)

2.[A Tour of the Dart Language](https://www.dartlang.org/docs/dart-up-and-running/ch02.html)

3.[Command Line Apps in Dart](https://www.dartlang.org/docs/tutorials/cmdline/)

4.[An Introduction to the dart:io library](https://www.dartlang.org/articles/io/)

**Dart练习**

1.[See Dart](https://www.dartlang.org/#code) (5 minutes)

2.[Write Dart](https://www.dartlang.org/codelabs/darrrt/) (1 hour)

3.[Dive Deep into Dart docs, libraries, and tools](https://www.dartlang.org/docs/) (1 day)

4.[Tech Notes on using Dart, BeagleBone Black and Debian for IoT Applications](http://www.iotfestival.com/IoTDartAndBBBNotes.html)

---
<a name="4"></a>
###系统设置

1.Install [Dart](https://www.dartlang.org/) from https://www.dartlang.org/ (requires Java installed on your system)

2.Install FileZilla from https://filezilla-project.org/ (we'll use this for transferring files)

3.Install Energia (we'll use this with the CC3200)

4.During class .... you'll get sample programs for BeagleBone (in Dart) and CC3200 (in Energia)

**Dart启动**

- For the class, we'll run Dart on the BeagleBone as well as on a laptop you bring.
- Dart uses symlinks, and commonly Linux or Mac are recommended platforms.
- Dart should work fine on modern Windows but is not supported on Windows XP.
- If you can download Dart and run this simple program, your machine is ready to go

		void main() { // The app starts executing here.
		  	print("Hello, IoT IAP @ MIT");   // print a simple test
          }

---
<a name="5"></a>
###参考硬件

1.BeagleBone Black

2.LaunchPad CC3200

3.myPartsKit

4.electronic bricks

5.ARM: IoT From Sensor to Server

---
<a name="6"></a>
###课程安排

**第一天：介绍**

- Goals / Objectives / Class Design
- Participant Introductions / Objectives
- IoT - the big picture
	- Various kinds of apps (aka user experiences, markets)
		- consumer, industrial, municipal, medical, environmental, transport ...
	- Technology and Business Model Impact -> Michael Porter 11/20/2014 - "Managing the Internet of Things: How Smart, Connected Products are Changing the Competitive Landscape"
	- International / Global
	- The Physical Web - Each device is discoverable, has it's own URL
- IoT Product Demonstrations
- IoT IAP Themes
	- IoT = Hardware + Software + Networks (wireless/wired) + Apps
	- Security: Ciphers, computablity and practical considerations
	- Build-It Brainstorming
	- Pick a Project / Chart a 5-day Plan from prototype to packaging
- Our first working development: "Hello, IoT"
	- Hardware Example
	- Software Example
	- Network Example
	- Secure Example
- IoT Starter Kit - component review / demonstration
	- Components listed below
- Electronics Parts Kit - component review / demonstration
	- Link to components available for use
- Intro Topics
	- Dart, https://www.dartlang.org/codelabs/darrrt/
	- BeagleBone, http://beagleboard.org/black
	- Example IoT Device we'll use in coursework
- Food: Pizza

**第二天：深入硬件和软件**

- Hardware
	- Platforms we'll demo include BeagleBone Black, LaunchPad CC3200
	- Capes, BoosterPacks and more
	- Making Toys? "Fail Fast" - http://makezine.com/2014/05/17/hacking-toys-with-energia/
- Electronics 101
	- Descriptions / functions snap-together Electronic Bricks
	- Descriptions / functions electronic components
- Interactive Physical Computing
	- "Hello, World" with LEDs
	- Controlling LEDs and Sensors with Dart
- SBCs, GPIO and Sensors
- Software
- Dart
	- Dart IoT Libraries / custom for class
- Linux / Debian
- Energia
- Web ware
	- Browser GUI
	- HTML5
	- Mobile Interfaces
	- Dart / TypeScript / JavaScript
- IoT Libraries - custom for IAP
- Food: Subs / Sandwiches (http://www.potbelly.com/)

**第三天：网络和封装**

- Guest Speaker: Bob Frankston
- Networks
	- WiFi, Ethernet, BLE
	- Websocket and communication models
		- Dartiverse
	- Connecting to the Internet
	- Protocols
- The Cloud
	- Platform As A Service
	- APIs
	- Big Data
- Packaging
	- Industrial Design
	- 3D Printing / Prototyping
- Project Work
	- Lab Time
- Food: Italian

**第四天：制作时间**

- Project Work
	- Lab Time
- Help Labs
	- Hardware
	- Software
	- Networking
	- Packaging / 3D Printing
- Food: Chinese

**第五天：演示**

- Project Work
	- Lab Time
- Project Demonstrations
	- Poster Session
- Product Launches!!
- Class wrap-up / Debrief
- Food: Wild Card / Cake & Ice Cream

**目的：**

1. Master some of the basic technologies of IoT
2. Build an IoT Device
3. Demo a finished "product" you can call your own

**使用到的一些器件有：**

BeagleBone Black / Power  
Breadboard(8.3 x 5.5cm)  
Breadboard Bus Strips(8.3 x 1cm)  
Electronic Brick - Track Sensor  
Electronic Brick - Big Button  
Electronic Brick - Lighting Emitting Diode - Green  
Electronic Brick - Tilt Sensor/Switch Brick  
Electronic Brick - Buzzer  
Electronic Brick - Temperature Sensor Brick  
Electronic Brick - Sound Sensor/Microphone Brick    
Electronic Brick - Rotary Potentiometer Brick  
Electronic Brick - Magnetic Sensor/Switch Brick  
Electronic Brick - Moisture Sensor  
Electronic Brick - Light Sensor Brick  
Electronic Brick - 5V Relay

---
<a name="7"></a>
###脚注：

1. No soldering required!

2. Designed for individual participation, but team organization also possible.

3. "IoT Starter Kits" will be provided to participants who complete the program. This will include (tentative): BeagleBoneBlack, CC3200 SimpleLink Wi-Fi LaunchPad, sensors, Electronics Starter Kit, Text, Handouts/Slides/Notes

4. We'll have guest speakers, product demos, labs, group and interactive discussions along the way

**BeagleBone链接**

1. BeagleBone System Reference Manual
2. Latest Production Files / Schematics, BOM etc.

**对CC3200编程**

1. CC3200 SimpleLink™ Wi-Fi® and IoT Solution with MCU LaunchPad Hardware User's Guide
2. Energia Download for Mac, Windows, Linux
3. Energia First Sketch (explanation of a simple Energia program)
4. Internet of the Backyard: Energia is out there for CC3200
5. Good Pro/Con of CC3200 for IoT
6. tmp006 Document

**CC3200设置/配置**

1. CC3200 Setup - follow this guide
2. CC3200 - How to Setup on Windows
3. CC3200 - Setup Guide
4. How to edit / maintain your com ports on Windows
5. To Check COM port, use the Device Manager on Windows [here's a link how]
6. CC32000 Getting Started Video and Pin Mapping
7. CC3200 Chip Specs
8. CC3200 SimpleLink Wi-Fi and Internet-ofThings Solution, a Single Chip Wireless MCU: Technical Reference Manual
9. Energia Introduction on Windows
10. Energia / CC3200 Guide
11. Energia on Ubuntu (Note: Initial attempts trying this failed)
12. CC3200 Jumper Settings (take particular note of the jumper settings for run vs flash)
13. Energia on GitHub
14. CC3200 SDK
15. CC3200 Getting Started Guide / Element14
16. Uniflash Standalone Flash Tool for TI Microcontrollers (MCUs) and Sitara Processors
17. ARM Coretex-M Series
18. Demo video (7:54 min) of Energia running on an MSP430 (a different, simpler chip than what we will use)

**给IoT嵌入WiFi**

1. CC3200 Out of Box Experience
2. TI Launches CC3200
3. Code Composer Studio / Project 0
4. Meet the new Internet: Embedded Wi-Fi for the IoT
5. Energia Out of Box Experience

**行业标准组**

1. AllJoyn

**小型设备网络协议：CoAP案例研究**

1. Zach Shelby, Embedded Web Services: SenZations, Sensinode (August 2010)
2. IETF Journal, The Internet of Things, by Carsten Bormann, JP Vasseur, and Zack Shelby (Nov 2010)
3. Embedded Web Services, Shelby and Tolle (January 2011)
4. Zach Shelby PDF: "Introduction to Resource-Oriented Applications in Constrained Networks" (March 2011)
6. 6LoWPAN - The Wireless Embedded Internet, Part 1, Zach Shelby and Carsten Bormann (May 2011)
7. 6LoWPAN: The wireless embedded Internet - Part 2: 6LoWPAN history, market perspective & applications (May 2011)
8. Zach Shelby on "CoAP: The Web of Things Protocol" (April 30, 2014; Video: 40:19) (corresponding slides are here)
9. IETF RFC7252 - The Constrained Application Protocol (June 2014)
10. IETF Draft - CoAP Core Interfaces (Nov 2014) (replace earlier version)
11. Constrained Application Protocol (Wikipedia description)
12. Connecting Sensor Networks (Video from Hangout 42:05) (September 2014)
13. Short interview with Zach Shelby on IoT, Standards etc. (June 2014)
14. OMA Lightweight M2M Tutorial (LWM2M) (22:16 video) (October 2014)
15. Nokia Foundation awards Internet of Things pioneer Zach Shelby (December 2014)
16. Life of Jeremy (4:45 video)
17. 6LoWPAN vs ZigBee
18. Internet of Things: 802.15.4, 6LoWPAN, RPL, COAP
19. Internet Protocol Suite
20. Open Systems Interconnection Model
21. Embedded Web Services (behind paywall), by Zach Shelby (2010)
22. Media Types for Sensor Markup Language (IETF Draft Standard, Expired)