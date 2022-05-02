# Discord Rich Presence

<h1>Requirements</h1>

>[Nodejs](https://nodejs.org/en/download/) <br>
[Visual Studio Code](https://code.visualstudio.com/) or any other code editor <br>
[Git](https://git-scm.com/downloads) <br>
[Discord](https://discord.com/)

<h1>How To Use</h1>

- Go to [Discord Developers Portal](https://discord.com/developers/applications) and then go to the top left corner of your screen, click "Create Application" and name it. (I recommend naming it as "Discord")

- Then click onto the application under "Rich Presence" category, and then click onto "Art Assets".

- Click "Add Asset" then choose an image from your computer.

- [Download this repository as zip](https://github.com/anmol420/Discord-RPC/archive/refs/heads/main.zip) and extract it.

- Open your terminal and type "npm i discord-rpc".

- Go to "config.json" file:
```
  {
    "ClientID": "YOUR_CLIENT_ID",
    "LargeImage": "YOUR_LARGE_IMAGE_NAME", 
    "LargeImageText": "Discord",
    "Button1": "Invite Now!",
    "Button2": "Vote For Discord",
    "Link1": "https://discord.com/api/oauth2/authorize?client_id=880515863164387348&permissions=2147609600&scope=applications.commands%20bot",
    "Link2": "https://top.gg/bot/880515863164387348/vote",
    "Details": "YOUR_APPLICATION_DESCRIPTION",
    "State": "YOUR_APPLICATION_STATE" //This Is Optional
  }
```
- Change `YOUR_CLIENT_ID` text with your app's id (`APPLICATION ID`) that's shown under `General Information` section on your app's developer page.

- Change `YOUR_LARGE_IMAGE_NAME` text with your uploaded image's name that's under `Rich Presence>Art Assets`.

- You're good to go, open your terminal and type `node index.js` to make rich presence shown in your status!

- Note: Buttons will not work for you, but they always will be working for others!

<h2>Discord Server</h2>

[Join our discord server now to get additional support or hang out!](https://discord.gg/QGf3q7e3J5)

<h3>Developer</h3>

👤 anmol420.
- GitHub: [anmol420](https://www.github.com/anmol420)
- Discord: [Anmol](https://www.discord.com/users/875986400649052191)

<h3>Contributing</h3>

- Contributions, issues and feature requests are always needed and welcome!

<h3>Support</h3>

You can show your support by giving a ⭐ on using the RPC!

<h3>License</h3>

Copyright © 2022 anmol420<br>
This project is [MIT](https://en.wikipedia.org/wiki/MIT_License) Licensed.
