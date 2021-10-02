# mcserver

requirements: wget, java 

For more information on how to install the required software visit https://www.jcchouinard.com/wget/ and https://www.java.com/en/download/windows_offline.jsp

open cmd if hosting locally or putty if hosting on a vps 

make a file in root for your mc server or if you're hosting locally make a file on your desktop or on your secondary storage drive

(Vps)
* mkdir minecraft

* cd minecraft

* wget https://launcher.mojang.com/v1/objects/1b557e7b033b583cd9f66746b7a9ab1ec1673ced/server.jar


you will need to run the java file and then wait until all the files are installed then configure in server.properties

* run java -Xmx1024M -Xms1024M -jar minecraft_server.1.16.5.jar nogui
 
you only really need to configure server.properties to give the server like a subdomain, enable whitelist, make cracked versions able to play, etc.

* sudo nano server.properties

* agree to eula.txt by doing sudo nano eula.txt

* run java -Xmx1024M -Xms1024M -jar minecraft_server.1.16.5.jar nogui to start the server
(Windows)
* make the file that will contain the server files

* Download the server jar https://launcher.mojang.com/v1/objects/1b557e7b033b583cd9f66746b7a9ab1ec1673ced/server.jar

* Run the jar and wait for all the stuff to install

* Agree to the eula.txt

* Open Server.properties to edit server configuration if needed

* run the jar again and the server will start  
