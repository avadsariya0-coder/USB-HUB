# USB HUB — Journal Export

- Exported at: 2026-06-16T08:08:33Z
- Project ID: 3172
- Entries: 13

## Entry 1
- ID: 6233
- Author: avadsariya0
- Created At: 2026-05-09T09:24:51Z

### Content

Today I started my new project known as Thermometer-X. Basically it is a digital thermometer witn an OLED display. Today I watched the youtube video and started making schematic. I have done half of the schematic work. The issue for me was finding the components in kicad. For finding the best alternative I had to rely on google.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTMyMDcsInB1ciI6ImJsb2JfaWQifX0=--d16296153d9eff3967d93426c592184a08789c6c/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/7c5e5dea-7123-400e-85b9-dafc54a27781/video.mp4

## Entry 2
- ID: 9307
- Author: avadsariya0
- Created At: 2026-05-26T07:53:28Z

### Content

Firstly I started this project as a thermometer but due to lack of experience and less tutorials I am changing my project to USB hub. I started with seeing a repo containing usb hub schematic to take idea and then started myself to make schematic with the help of datasheet. I am almost done with the schematic the only thing to dpo is assigning footprints and add decoupling tool. Finding symbols nwas a problem as ssome symbols arent available so i have to install library. My laptop was crashing kicad so restarted kicad several time
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA2NTUsInB1ciI6ImJsb2JfaWQifX0=--7b99ce36f1ec766d77ef7c40d35c48745afdd6af/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA2NTYsInB1ciI6ImJsb2JfaWQifX0=--01b8199e0f7ef6803e4ff99d4a05e1fb3be9c132/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/26bb99db-86f5-44d8-8fd3-856a46047e6b/video.mp4

## Entry 3
- ID: 9389
- Author: avadsariya0
- Created At: 2026-05-26T15:44:20Z

### Content

I changed thge diode symbol firstly because the symbol i used first was thicker . I used ultra librarian for the symbol. It took some time as the site wasnt remembering password and username. After that I added decoupling part,wired the SL2.1A and added led chamber. Then I assigned footprint for all the components and fixed few errors showed by ERC. I updated pcb using schematic and thats all.I also uploaded the footprint for the SL2.1A which took time i was unable to upload it
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA4NTgsInB1ciI6ImJsb2JfaWQifX0=--a300ae73945894e677ec13c7000fa33bd56e14a4/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA4NTksInB1ciI6ImJsb2JfaWQifX0=--338d09bdfacb57df766308d7c23b1bb73cd797b4/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/1265e055-2e67-4f8f-8949-8e6acbc85a19/video.mp4

## Entry 4
- ID: 9391
- Author: avadsariya0
- Created At: 2026-05-26T15:48:54Z

### Content

I started with arranging components in the pattern i need. Then started routing the tracks . Routing the tracks were little complex because of number of routing was more. At some place I wasnt able to route some points . After few time as I started checking DRC the laptop crashed and stopped working and I tried to save the pcb by using ctrl+s but it didnt happen the Kicad automatically got closed and I have to do it again which was challenging.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA4NjMsInB1ciI6ImJsb2JfaWQifX0=--c8f35eb61cc48613d14ac288d502db97f611823b/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA4NjQsInB1ciI6ImJsb2JfaWQifX0=--a9dc3a2e3e628894e86f6834311aa0839a9e9bf5/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/c220f1b6-c613-49bb-87af-3e2495eeb3df/video.mp4

## Entry 5
- ID: 9412
- Author: avadsariya0
- Created At: 2026-05-26T16:56:04Z

### Content

I startred with routing again as the Kicad crashed and routing wasnt saved . The routing work was kinda difficult because of the the number of routes. It took me time as the no matter what i do the F.cu ,layer touches another F.cu layer same with the B.cu layer. some times I wasnt able to connect it. After connecting it there were some errors that i fixed. I firstly thought of making it in circle shape but i thought it wont look good so I stick to the traditional rectangle one. I am only able to see resistor,capacitor,LED and diode but unable to see for usb-c and SL2.1A. Next thing I have to do is adding step file for them
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA4OTEsInB1ciI6ImJsb2JfaWQifX0=--2a213c8eb354a3505f89484d7b7dab18c8d5fd6f/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA4OTIsInB1ciI6ImJsb2JfaWQifX0=--71c0faad64be35bf8d62e844bfe8fe7f957ad2b7/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA4OTQsInB1ciI6ImJsb2JfaWQifX0=--3aa739bd0a4bd82f52b89acc244e014f2e9d338f/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/4e978ee7-5d2d-4c3e-aa8b-6ec61389e765/video.mp4

## Entry 6
- ID: 9605
- Author: avadsariya0
- Created At: 2026-05-27T08:38:32Z

### Content

Firstly I started with downloading step files and add 3d models for USB-C and SL2.1A. As I checked the 3d viewer I came to know that the USB-C opening were facing in opposite direction. So I rotated the USB-
C in the PCB but routing got disconnected and had to do route few tracks. I tried to route the missing tracks but due to extra routing I wasnt able to route all the tracks. So I though of removing all the routes and start it again . Finally I did it and PCB is done with 3d models... Now I am going to start 3d designing.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjEyNjksInB1ciI6ImJsb2JfaWQifX0=--aef2e05c41ea96e76eb204c547495fbe79ec835a/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjEyNzAsInB1ciI6ImJsb2JfaWQifX0=--4bbb0781df2eb530389bc312df78432a8877a007/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjEyNzIsInB1ciI6ImJsb2JfaWQifX0=--51a7c69271bf649e1b38615247fcc63875b9c795/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/5c79241a-cec8-4707-84f7-c405eab2c132/video.mp4
- https://lookout.hackclub.com/api/media/caba4d4d-832d-40ab-9cc6-27cbfcf26698/video.mp4

## Entry 7
- ID: 9866
- Author: avadsariya0
- Created At: 2026-05-28T09:11:47Z

### Content

Today I began with making outline for the pcb with curves.Firstly I removed my old outline and draw lines and curves and made it in such a way that USB opening must be near the edge of the pcb. As all USB opening were nere edge of pcb there were some errors as the some routes were outside the outline.So I change the posution of that particular routes and added the hackclub logo on the pcb . I also tried to add logo with my name to it but I wasnt able to it. After that I startrd with 3d design work in fusion 360. I have created bottom plasne,walls and the top face.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjE4OTcsInB1ciI6ImJsb2JfaWQifX0=--b5a1f46e945e3fe64b356a18d0a738267c8f0c8e/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjE4OTgsInB1ciI6ImJsb2JfaWQifX0=--a264dcc5ae53e3e0f6498a10881651a2a4f9975b/image.png)


### Recording Links

- https://public.lapse-hackclub.link/timelapses/m78NQK6x7Bj4/timelapse-m78NQK6x7Bj4.mp4
- https://public.lapse-hackclub.link/timelapses/_aN3S_Qcqn8A/timelapse-_aN3S_Qcqn8A.mp4
- https://public.lapse-hackclub.link/timelapses/-z3wCEWTDTBq/timelapse--z3wCEWTDTBq.mp4

## Entry 8
- ID: 9964
- Author: avadsariya0
- Created At: 2026-05-28T18:02:20Z

### Content

I started with adding the bottom cover for the enclosure and made the cutouts for the USB-C ports. My laptop was super laggy and was sticking in between. But I managed to add cutouts for the ports and added screw holes . After adding holes in beginning I wasnt able to see the circles it took me time to do for first corner. Then I started adding screws to the holes using joint function in fusion 360. I had to select screw everytime as copy/paste wasnt working. Few times I fitted screw upside down🤦‍♂️. I am ready with the enclosure and everything . The thing left is github repository and arranging files.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjIzOTAsInB1ciI6ImJsb2JfaWQifX0=--fec4f1896c6cef11b5c2eee6b08789266946b031/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjIzOTIsInB1ciI6ImJsb2JfaWQifX0=--3a213f4148bca9460ef7077ce87fe82e493a50ec/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjIzOTUsInB1ciI6ImJsb2JfaWQifX0=--9326bbabb13442750cf85ca7f3af779271f04efb/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/bd71c210-1b86-4069-b36a-432d8023aea0/video.mp4

## Entry 9
- ID: 10428
- Author: avadsariya0
- Created At: 2026-05-30T15:53:50Z

### Content

I started with making the bill of material for the USb HUB and mentioned Price per unit in both INR and USD , Quantity required etc. Finding some of the components online was time consuming and some were really expensive. Then I made the Github repository and added the pcb files .I added the MIT license to the repository. Making folder and organising it is a big task. For the CAD folder I wasnt able to export the enclosure as step. My laptop was getting crashed and Fusion 360 was getting stut down. It occured many times . After successfully making CAD folder I wasnt able to upload whole folder to the github repo. I tried 2 to 3 times but I wasnt able to upload . So I thought of uploading 2 to 3 file together but still unable to upload. At the end I had to upload all files in CAD folder individually which took lot of time. For organising files I reffered to the github repo made by me for previous project USB HUB. Now I have to make zine poster and write a good readme.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjM3NTUsInB1ciI6ImJsb2JfaWQifX0=--2e1347accd2862db7f08310649e1fda79a5409b7/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjM3NTYsInB1ciI6ImJsb2JfaWQifX0=--54c29db3b7029d344adf6c5bb1c8015022aae352/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjM3NTcsInB1ciI6ImJsb2JfaWQifX0=--0867543a1c36f8bdbeb1153f31ebc78d25ea8433/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/239750e8-cb4d-4032-94ee-94ba35de2b08/video.mp4
- https://lookout.hackclub.com/api/media/71b8ccdb-5f28-46fe-a21a-d4d502b976a6/video.mp4

## Entry 10
- ID: 10685
- Author: avadsariya0
- Created At: 2026-05-31T15:55:32Z

### Content

I started with making zine poster finding the suitable tempelate was challenge. Firstly I downloaded the png for my render from the fusion 360. But it didnt get downloaded 1 to 2 times and my laptop wasnt supporting me 😭😭. I changed the environment for the render.I choosed the tempelate  and added my render and chan ged the background and made the poster and added the qr code for the github repository to it.
![USB HUB ZINE.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQzNTgsInB1ciI6ImJsb2JfaWQifX0=--a2e477ac9a7c2bac55bf16d435971f7e6f961158/USB HUB ZINE.png)


### Recording Links

- https://lookout.hackclub.com/api/media/8cf34bfd-23fa-43d6-806b-3063eb20fd5c/video.mp4

## Entry 11
- ID: 10688
- Author: avadsariya0
- Created At: 2026-05-31T16:02:38Z

### Content

I started with downloading all the render image , get screenshot of PCB and Schematic and added the images folder to the repository . Then I wrote readme for the project. After writing half of the readme I came to know that i forgot to add BOM and zine poster to the repository. I added them to the repository. For the reference to the pattern of readme i reffered to the my repository for TITAN BLINKER. For license,contribution part I copied the text from Titan Blinker repository to the USB HUB repository.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQzNjYsInB1ciI6ImJsb2JfaWQifX0=--848d3a7c47703d11d86436bbaf6c572ceb21a6df/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQzNjcsInB1ciI6ImJsb2JfaWQifX0=--9d6c283c181012434aa326db2b4e4bc5315887f4/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjQzNjgsInB1ciI6ImJsb2JfaWQifX0=--8b0e21e488bc97692319bd51942b15d05248ea70/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/0c7579c6-8ad0-4ce7-88c6-2ddc389dfab9/video.mp4

## Entry 12
- ID: 11851
- Author: avadsariya0
- Created At: 2026-06-05T15:15:04Z

### Content

I started with removing whole PCB and updated PCb from schematic and arranged them in a manner that there is no much space between them. Then I started routing . It wasnt that difficult but routing last 3 to 4 connection was difficult. Then I added the mounting holes to the PCB.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6Mjc2NzUsInB1ciI6ImJsb2JfaWQifX0=--036dbc148d7d71936f5dad81a889c9f066e5e209/image.png)
<!-- Uploading image.png (106 KB)... Processing... -->


### Recording Links

- https://lookout.hackclub.com/api/media/78ef91aa-dd14-46ce-b6c0-6f9f10688153/video.mp4
- https://lookout.hackclub.com/api/media/2596fc81-d826-4626-bf39-ddd12e07c260/video.mp4

## Entry 13
- ID: 12454
- Author: avadsariya0
- Created At: 2026-06-08T09:49:44Z

### Content

I started with making the enclosure for the USB HUB. The enclosure contains 4 standoff pillar for holding the pcb. and top lid which can be fitted without screw because it uses a friction fit lid. in 3d designing selecting some part was challenge as sometime whole body got selected. AT last I madse some changes in the body and the enclosure was done. Then I made zine firstly I wasnt sure about tempelate to use 🤦‍♂️🤦‍♂️. Then I selected a tempewlate and did it. THen I stated making changes in repository updated all folders,readme added pcba nd enclosure cost to BOM and updated it
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkyNzksInB1ciI6ImJsb2JfaWQifX0=--08a3546c8ee727e51c7093000bd45c77dd27faab/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkyODAsInB1ciI6ImJsb2JfaWQifX0=--eff1c73f153ede198c71284393f662dfe33395ac/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkyODEsInB1ciI6ImJsb2JfaWQifX0=--f17204df9a3abf100080e0cea94959c01482e3e1/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjkyODIsInB1ciI6ImJsb2JfaWQifX0=--555f634fc7de3cc652200d88b87ddf50cb492ebf/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/5602b3fe-c4ed-476c-827e-a41d74f18319/video.mp4
- https://lookout.hackclub.com/api/media/6720e756-3d35-425b-b117-60e1fd8a2ae9/video.mp4
