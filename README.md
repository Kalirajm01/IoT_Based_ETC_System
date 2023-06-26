# IoT_Based_ETC_System

=> Electronic Toll Collection is a generally mature technology that allows for electronic payment of highway tolls. It takes advantages of vehicle-to-roadside communication technologies to perform an electronic monetary transaction between a vehicle passing through a toll station and the toll agency. This system is implemented using the innovative technology of Radio Frequency Identification (RFID).

=> Radio-frequency identification (RFID) is a technology that uses communication via electromagnetic waves to exchange data between a terminal and an electronic tag attached to an object, for the purpose of identification and tracking.

=> Each vehicle will be provided with an RFID tag. This tag stores the unique ID of the vehicle and related information. When interrogated by a reader, it responds with that data over a radio frequency link. The readers are fixed in the toll gates. So, when the vehicle comes near the reader, the data from the tags can be easily read by the readers. This data is passed to the computer and thus the cash can be deducted from the user's account.

<img width="533" alt="image" src="https://github.com/Kalirajm01/IoT_Based_ETC_System/assets/92640470/26df098f-3ff2-48d1-a23c-7416ff3b3d6c">

<img width="590" alt="image" src="https://github.com/Kalirajm01/IoT_Based_ETC_System/assets/92640470/dda6acbd-e66b-42d9-a6d9-b9eff73fc146">

**PROCEDURE:
PART A: CREATING NETWORK TOPOLOGY**

STEP 1: Open packet tracer from start menu.

STEP 2: Drag and place the router, switch, server, RFID tag, RFID reader, and Door.

STEP 3: Configuring IP address and subnet mask for server, router.

STEP 4: Create a network topology.

![image](https://github.com/Kalirajm01/IoT_Based_ETC_System/assets/92640470/fd764dc6-b007-4c5b-a58c-55b56b057e7e)


**PART B: CONFIGURING 
Configuring DCN department**

STEP 1: Open RFID reader, go to “advanced option” click on “config” tab now select IoT server as remote server and enter the IP address, username and password of the server and press connect.

STEP 2: Open door, go to “advanced option” click on “config” tab now select IoT server as remote server and enter the IP address, username and password of the server and press connect.

STEP 3: Open server and go to “IoT monitor” option and log on to your account by entering username and password.

STEP 4: Now click on “Add” button and add the conditions for the IoT devices and save.

**Configuring IT department**

STEP 1: Open RFID reader, go to “advanced option” click on “config” tab now select IoT server as remote server and enter the IP address, username and password of the server and press connect.

STEP 2: Open door, go to “advanced option” click on “config” tab now select IoT server as remote server and enter the IP address, username and password of the server and press connect.

STEP 3: Open server and go to “IoT monitor” option and log on to your account by entering username and password.

STEP 4: Now click on “Add” button and add the conditions for the IoT devices and save.

**PART C: TESTING**

STEP 1: Take “RFID card dcn student” tag and scan it on the “DCN” department, green light will be blinked on the DCN door and door opens.

STEP 2: Take “RFID card dcn student” tag and scan it on the “IT” department, doesn’t respond.

STEP 3: Take “RFID card it student” tag and scan it on the “IT” department, green light will be blinked on the “it” door and door opens.

STEP 4: Take “RFID card it student” tag and scan it on the “DCN” department, doesn’t respond.


