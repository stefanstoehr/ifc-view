# :telescope: ifc gucken

![Screenshot of the ifc-viewer opened with MS Edge.](https://github.com/stefanstoehr/ifc-view/blob/main/screenshot.png)

## sources, thanks and creation 

:construction: A minimal working viewer from "That Open" (https://github.com/ThatOpen).

:hammer_and_wrench: The viewer is created in April 2024 from a .zip-file available as an attachement of the session "That Open Engine" (https://people.thatopen.com/c/first-steps-to-freedom-course/sections/113160/lessons/378730) as part of the course "First Step to Freedom Course".

:mechanic: I downloaded the original .zip-file from https://people.thatopen.com/c/first-steps-to-freedom-course/sections/113160/lessons/378730. I unzipped the .zip-file. I dragged and dropped the folder in VS-Code. I updated all dependencies to the latest versions I could found. I run "npm install" in the Terminal of VS-Code (from the dragged and dropped folder by the way of course) and received errors. So I downgraded the dependencies step by step till no error appeard. Thanks to the community of "That Open People" (https://people.thatopen.com/home) and @HoyosJuan (https://github.com/HoyosJuan) for the amazing support (https://people.thatopen.com/c/ask-the-community/ifc-geometry-vs) I was able to modify the main.ts with "ScreenCuller"(-method?) and my IFC-model appears molto bene. I run "npm run dev" to check the result on localhost. At least I run "npm run build" to get the files, which are in this reposotory right now (that is why you can not find the main.ts). I activated the GitHub-Pages functionality and now I can run the app in the web and upload models to have a quick easy impression.        

IFC-Notes #1: Different kind of models:
![Screenshot of the ifc-viewer opened with MS Edge.](https://github.com/stefanstoehr/ifc-view/blob/main/Modelle.PNG)

IFC-Notes #2: models not equal models:
![Screenshot of the ifc-viewer opened with MS Edge.](https://github.com/stefanstoehr/ifc-view/blob/main/Teilmodelle.PNG)

Stefan
### B.STR :heart: NG
