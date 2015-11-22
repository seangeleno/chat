
# Shat - Schat with Sockets

This is the README markdown for Schat with Sockets.

The primary service of Schat is to provide a real-time visual chatting with other people that are nearby. This markdown will provide full descriptive details about Schat, including which APIs will be utilized, technologies used (langauages, frameworks, packages, etc.), where the application is hosted online, etc.

### Contents

- Team seangeleno
- Description of Schat
- Technologies/APIs used
- Hosting site

### Team Triple S

| Name               | Slack               | Email                    | GitHub      |
|--------------------|:-------------------:|:------------------------:|:-----------:|
| Sean Esteva        | @seangeleno         | seangeleno@gmail.com     | /seangeleno |

### Description of Schat

Schat will provide ONLY logged in users the ability to chat with other users via javascript sockets.

Pretty cool, I know, right?!

 If a user does not have a profile, they must CREATE one prior to using Schat's services. Upon login they will see who they can chat with. <!-- Additional description of features, upon completion of application -->. It will be built and implemented using socket.IO and the MEAN technology stack.

There will be full CRUD functionality for users for their profiles. Users will be able to CREATE a user profile, and upon signing in, have the ability to READ their user info, UPDATE/edit their information, and DESTROY their user profile. If the user attempts to provide credentials and fails at authentication three times in a row, they will be forwarded to the CREATE user (sign-up) page.

The logged in user activities will be logged to a Mongo database. The object will include eight different activities to choose from <!--name 8 activities here -->

## Technologies/APIs Used

- Languages/Technologies Used: MongoDB, Express, NodeJS, HTML, CSS
- Possible additional languages/technologies used: J5, Bootstrap, Sass

## Hosting Site

The current plan is to initiation Schat as a Git Repository and push the application to Heroku for public consumption.

## User Stories

Story 1 - The Talker - You outside, you need to communicate this to your buddy who you're about to pick up. Just send him a message with the Schat app.

Story 2 - Star-Striken-Lover - You just wanna Netflix-and-Chill and you need a way to communicate. Presto.
