# mcserver

requirements: wget, java 

For more information on how to install the required software visit https://www.jcchouinard.com/wget/ and https://www.java.com/en/download/windows_offline.jsp

open cmd if hosting locally or putty if hosting on a vps 

make a file in root for your mc server or if you're hosting locally your file will be located at c:/users/your_user

* mkdir minecraft

* cd minecraft

* wget https://launcher.mojang.com/v1/objects/1b557e7b033b583cd9f66746b7a9ab1ec1673ced/server.jar

you will need to run the java file and then wait until all the files are installed then configure in server.properties

* run java -Xmx1024M -Xms1024M -jar minecraft_server.1.16.5.jar nogui
 
you only really need to configure server.properties to give the server like a subdomain, enable whitelist, make cracked versions able to play, etc.

* sudo nano server.properties

after you are down configuring run this command again run java -Xmx1024M -Xms1024M -jar minecraft_server.1.16.5.jar nogui to start the server :)
