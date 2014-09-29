# myBridge

Node.js Asterisk confBridge moderator landing page.  Moderator login is validated from mySQL database.  Events are logged using AMI.

##Features:
- Last 5 active talkers
- Mute / Unmute individual participants
- Mute / Unmute entire conference
- Remove individual participants
- Remove all participants from conference
- Lock / Unlock Conference
- Dynamic participant talking indicator (Flashing in Chrome/FF, steady in IE)
- Name in participant list
- Dail in Number in participant list
- Same session reconnect to websocket
- New session redirect to login

##Project Details

###Built upon:
- Node.js
- Html5
- socket.io (1.10)
- asterisk-ami
- passport
- express 4.x
- Jade templates

###Design assumptions:
- Asterisk version 11.x
- mySQL table:
  - Conference
  - Moderator PIN
  - Participant PIN
  - Bridge Profile
  - User Profile
  - First Name
  - Last Name
  - Phone Number
  - Email Address
- Websocket for server/client communiations
- jQuery for dynamic content update

##License
GNU
