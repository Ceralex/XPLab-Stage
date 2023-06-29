# Xplab-Stage

This is a collection of projects developed during the three-week internship at [Xplab S.a.s.](http://xplab.net/) from 12/06/2023 to 30/06/2023.<br>
The objective was to create a small program for each new library learned, in order to become familiar with it.<br>
All programs are written in the company's proprietary language, [Power-KI](http://power-ki.com/), and my knowledge of the language when I joined the company was zero.
---
### Ciao-01 and Ciao-02
The first two programs were developed on the first day of the internship. Ciao-01 is a command-line interface (CLI) program, while Ciao-02 utilizes the GUI features of Power-KI. These two exercises are part of the magazine [Fast.Track-01](https://issuu.com/xplab/docs/pwk-ft-01-en) and serve as a starting point to learn the Power-KI environment.

![ciao-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/88d5ed54-5ca7-4371-b16d-6b8fd9bb0a0e)
![ciao-02](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/e61c133f-1a92-45d8-b13b-cb0d72357f90)
---
### Agenda-01
This program was not developed by us, but we assisted one of the XpLab developers who programmed and explained, illustrating some language features, particularly introducing us to the "Table" data structure.

![agenda-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/5e6128fd-a8e1-4050-9f0a-3d217690bba8)
---
### Scherzo-01
This program is a modified version of "Ciao-02" that makes it impossible for the user to click the SUBMIT button by moving it and changing its size.

![scherzo-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/8ac762cd-018f-4c56-b6bb-02969a1968aa)
---
### Rete-01
This program utilizes the UDP protocol to exchange messages between two or more hosts using the SOK library for socket operations. In the top input box, simply enter the IP address of the recipient, and if it is listening, it will receive the message and display it in the central pane.

![rete-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/e781d573-125b-4179-840b-4f7999c3de1c)
---
### Realsense-01
This program utilizes two [dll](https://en.wikipedia.org/wiki/Dynamic-link_library) specifically created for the [Intel Realsense D435](https://www.intelrealsense.com/depth-camera-d435/). It simultaneously displays the device's four different viewing modes.

![realsense-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/6beb69e5-8a28-4e52-a733-a166c7180909)
---
### Point-drawer-01
This program makes use of the image DRAW functionality integrated into a GUI. The interface consists of three sections:
- The right section is the panel on which points are drawn.
- The left section is a grid that displays all the points that have been created.
- The bottom-left section represents the input: a box for the color in [HEX](https://en.wikipedia.org/wiki/Web_colors#Hex_triplet) format, one for the X coordinate of the point, and one for the Y coordinate.

![point-drawer-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/b70cf02a-e737-49a1-994c-96ba405d1096)
---
### Grid-02
This program consists of two different GUIs. One is a modification of the previous Point-drawer GUI, and the other is dedicated solely to color selection and creation.

![grid-02(1)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/7f8714fb-b1c1-4a47-a2ac-bf8c98fcc1b5)
![grid-02(2)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/9af39d35-8219-4f85-84c4-187f2ced3501)
---
### File-transfer
Three different versions of this program were developed: file-transfer-02, file-transfer-03, and file-transfer-04. Between the first and second versions, there was a redesign of the interface, while in file-transfer-04, file transfer in segments was introduced. This simple GUI program allows sending files to a host by knowing its IP address, and at the bottom, a grid displays the transfer history.

![file-transfer-02](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/fa5726bb-e809-4552-8255-ddbb8dca71b3)
![file-transfer-04](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/d8a8f021-7e19-4cae-8395-ace3cac48a50)
---
### Agenda-02
The interface of this program is identical to that of agenda-01, but instead of using a table, it utilizes a SQLite database.

![agenda-02](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/5e6128fd-a8e1-4050-9f0a-3d217690bba8)
---
### Web-01
This program is a small browser that uses the Webfast component of Power-KI to embed a web interface within a GUI.

![web-01](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/c64fb9c5-0c57-48f5-a6d9-8a7013838595)
---
### Native-cloud-01
This is a test program we developed with the goal of learning how to use remote GUIs, which are GUIs hosted on a different machine than the one being used but accessible remotely by knowing the IP address of the executing machine of the .pwk package.

![native-cloud-01(1)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/d2a24c07-440e-429b-aa42-4941200c39cf)
![native-cloud-01(2)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/7a77be01-41c7-4e59-be2a-3cd0f874f03d)
---
### Server-remote-01
This was the first little project that was a bit more complex.<br>
It is a file explorer with the following features:
- Folder creation
- File/folder renaming
- File/folder deletion
- File upload
- File download

The entire program is executed on a remote GUI. This allows for convenient and easy file exchange between two or more machines, ideally a server and multiple clients connected to the server for data uploading.

![server-remote-01(1)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/48220ff8-60c2-4d4c-900f-840f3741f2f1)
![server-remote-01(2)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/4dbb1d68-2069-4b22-a289-cd94366ab480)
![server-remote-01(3)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/7539013c-11e5-4107-8c82-79b25b544285)
---
### Diario
This program is a school agenda aimed at students that offers several features:
- Adding and viewing grades with grade, subject and date sorted by day
- Viewing and editing the weekly schedule
- Subject management panel
- Event management panel with title, type(tests, questions or homework), subject, date and notes
- There is a panel in the home showing an overview of the current week's events

![diario(1)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/b9e50c67-b2a5-4cbc-b3ec-59ad1bcf90b1)
![diario(2)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/b172872f-3d86-4426-9d05-9f6ebe7768cf)
![diario(3)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/9691753c-e1cf-42a9-b119-45cc68a71a57)
![diario(4)](https://github.com/Ale-Ceresa/XPLab-Stage/assets/92877764/f7a95305-9357-4ee8-ba30-ec5fafd0cf4d)
