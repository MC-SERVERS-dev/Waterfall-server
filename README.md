## >>SERVER INSTRUCTIONS START<<

First, go to the top of the repo and click on code > codespaces > create codespace
now you have your own free server instance to host eaglercraft. Next you need to run the setup commands:

create 2 terminal tabs and paste in the following snipits:

first terminal: `cd server && sudo java -jar server.jar`

second terminal: `cd bungee && sudo java -jar bungee.jar`

IMPORTANT NOTE! [THIS IS FOR THE FIRST TERMINAL.] You need to agree to the eula in order for it to work. In your codespaces, go to the left sidebar and see the symbol that looks like two circles on top and one branch on the bottom, click on it, pres the `+` on the `eula.txt` and write a commit message and click "commit". Rerun the server using `sudo java -jar server.jar`.

Now go to the ports area and forward (and make public) ports 25565 and 8081

And then, ⚠ MOST IMPORTANT! ⚠
Copy the 8081 port address and it should be like, for example, `https://eagtek-files-392jejdw-8081.app.github.dev` . Copy this and paste it in your ⚠⚠⚠ browser BUT DONT,  ⚠⚠⚠⚠ DO NOT PRESS `ENTER` YET!⚠⚠⚠⚠ 
Instead, replace the `https` (in the beginning of the port address) and replace it with a `wss` . Here is some examples:
❌ WRONG: `https://eagtek-files-392jejdw-8081.app.github.dev`
✅ CORRECT: `wss://eagtek-files-392jejdw-8081.app.github.dev`

Thats it, your done! Enjoy!!!
