# myBridge
========

Node.js Asterisk confBridge moderator landing page.  Moderator login is validated from mySQL database.  Events are logged using AMI.

#Features:
- 

#Project Details

##Built upon:
- Node.js
- Html5
- socket.io (1.10)
- asterisk-ami
- passport
- express 4.x
- Jade templates

##Design assumptions:
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

