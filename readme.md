# Project Two: Lets Chat

## Rethinking the Way We Learn, Together.

Our goal for Project Two is to create a Slack-like chat app, that is specifically for education. It will allow users to post questions or comments in different interest chatrooms. This post will be tagged so that anyone searching for a specific topic can easily access any previous post with the tagged topic.

### Technologies Utilized:

* Node.js
* Express
* Mongoose
* MongoDB Atlas
* Socket.io
* Javascript
* CSS
* HTML5

### Features

MVP - The user will begin on the landing page which will have a signup button, a login button, or the ability to login through Facebook. If the user is a first time user, after signing up they will be brought to an INTERESTS page. 

INTERESTS will present the user with a list of interests from which they can select a maximum of four. After they cubmit their interests they will be brought to the MAIN page.

MAIN page is a general chatroom that will list the users interests as clickable text on the CHANNELS sidebar, it will allow the user to search from a dropdown search bar. the user will also be able to post in general and they can also reply to other users posts and thei own posts. If the user clicks on one of their INTERESTS in the CHANNELS sidebar they will be taken to that CHANNEL page.

CHANNEL pagewill have the name of the channel in the header.  The user will be able to create a post with and select a tag from a dropdown. They can also reply to other users and their own posts. Users can also delete and edit their own posts.The user can enter another channel or return to the main chatroom from the channels sidebar.  

Models Organization:

![ERD](/db/Models.png)


Workflow chart:

![ERD](/db/flowchat-mvp-v1.png)
