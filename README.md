- 👋 Hi, I’m @Johnsonbenjami436
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Johnsonbenjami436/Johnsonbenjami436 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
deletion.
 2 changes: 1 addition & 1 deletion2  
app.json
Original file line number	Diff line number	Diff line change
@@ -1,117 +1,117 @@
{
  "name": "venocyber-md",
  "description": "Simple WhatsApp Bot",
  "logo": "https://github.com/kingjux/Venocyber-md/blob/main/lib/assets/logo.png?raw=true",
  "keywords": ["VENOCYBER-MD", "VENOCYBER", "VENOCYBER MD BOT","VENOCYBER MD","venocyber","venocybertech"],
  "success_url": "/",
  "stack": "container",
  "env": {
    "OWNER_NAME": {
      "description": "Name for Bot Owner",
      "value": "𝐕𝐄𝐍𝐎𝐂𝐘𝐁𝐄𝐑-𝐓𝐄𝐂𝐇",
      "required": true
    },
    "WELCOME": {
      "description": "put 'false' or 'true' to enable & disable WELCOME ",
      "value": "false",
      "required": false
    },
    "GOODBYE": {
      "description": "put 'false' or 'true' to enable & disable GOODBYE ",
      "value": "false",
      "required": false
    },
    "BOT_NAME": {
      "description": " NAME FOR BOT",
      "required": false,
      "value": "𝐕𝐄𝐍𝐎𝐂𝐘𝐁𝐄𝐑 𝐌𝐃 𝐰𝐚𝐛𝐨𝐭𝐬"
    },
    "TZ": {
      "description": "Put TIME_ZONE according to your location",
      "required": false,
      "value": "Africa/Dar es salaam"
    },
    "READ_COMMAND": {
      "description": " Read bot cmds",
      "required": false,
      "value": "false"
    },
    "WARN_COUNT": {
      "description": " Warn count for users to kick/block when warn limit exceed!",
      "required": false,
      "value": "3"
    },
    "AUTO_SAVE_STATUS": {
      "description": " Auto save whatsapp status",
      "required": false,
      "value": "false"
    },
    "HEROKU_API_KEY": {
      "description": "Put Your Heroku Api Key Here",
      "value": "",
      "required": true
    },
    "HEROKU_APP_NAME": {
      "description": "Put Your Heroku App Name Here",
      "value": "",
      "required": true
    },
    "WAPRESENCE": {
      "description": "Fill the value: 'unavailable'(for nothing) | 'available'(for alwaysonline) | 'composing'(for typing) | 'recording' | 'paused' ",
      "required": false,
      "value": "unavailable"
    },
    "AUTO_READ_STATUS": {
      "description": "Fill the value true if you want bot view your Statuses.",
      "required": false,
      "value": "true"
    },
    "MSGS_IN_LOG": {
      "description": "Fill the value -true- if you want to see Messages in logs.",
      "required": false,
      "value": "false"
    },
    "READ_MESSAGE": {
      "description": "Fill the value true if you want bot to read all messages.",
      "required": false,
      "value": "false"
    },
    "DISABLE_PM": {
      "description": "Make it 'false' if you wanna run bot in your pm (if MODE is Public)",
      "value": "false",
      "required": false
    },
    "PREFIX": {
      "description": "Enter your desired prefix for bot. you can set `all | . | .!*`",
      "value": "."
    },
    "OWNER_NUMBER": {
      "description": "The phone numbers of the users who you want to be admin for the bot (should be in international format without + and multiple numbers must be separated by a comma \",\")",
      "value": "255625774543"
    },
    "SESSION_ID": {
      "description": "put your SESSION_ID here.",
      "value": ""
    },
    "MODE": {
      "description": "Worktype of your bot. Use public or private, if it is private then only bot number can use it. If public then everyone can use it.",
      "value": "private"
    },
    "PACK_NAME": {
      "description": "Put Sticker Pack_Name.",
      "value": "VENOCYBER",
      "required": false
    },
    "PACK_AUTHER": {
      "description": "Put Sticker Author_Name.",
      "value": "TECH",
      "required": false
    }
  },
  "addons": [{ "plan": "heroku-postgresql:basic" }],
  "addons": [{ "plan": "heroku-postgresql" }],
  "buildpacks": [
    { "url": "https://github.com/heroku/heroku-buildpack-nodejs#latest" },
    { "url": "https://github.com/carlosdommor/heroku-buildpack-ffmpeg-latest
