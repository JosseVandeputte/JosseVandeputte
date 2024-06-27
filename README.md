# Introduction
Hi, I am Josse Vandeputte (JV).

I'm a 18-year old student from Belgium.

I'm currently studying Applied Computer Science at Howest Brugge.

----

<strong>Underneath u can find all my sites and projects I made with some information about it</strong>


# vdpj.be - info
Resume of JV

## class.schedule.vdpj.be
    Howest TI class schedule

## railsync.vdpj.be
    Remake of NMBS / SNCB with QuinM

## worlde.vdpj.be
    Own worlde

## jv-chat.vdpj.be
    Own chat application

# jossevandeputte.be - info
    Site for subdomains and files

## api.jossevandeputte.be
    Site for my API's

### api.jossevandeputte.be/hello-world/public/api
#### /info
    GET:
 	    Status for hello-world
#### /hello
    GET:
        Says "Hello World!"

### api.jossevandeputte.be/jv-chat/public/api/
#### /info
    GET:
        Status for jv-chat

#### /chats
    GET:
        Get all the chats that are available on the server

#### /create-chat
    POST:
        Creates a chat

        JSON BODY:
        {
            "name": "xxx"
        }

#### /chats/{chatId}
    GET:
        Gets all the chats with that ID

    POST:
     	Send the message to the server with that ID

        JSON BODY:
        {
            "username": "xxx",
            "message": "xxx"
        }

<!---
JosseVandeputte/JosseVandeputte is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
