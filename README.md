![Shield Bot List Logo](https://shieldbotlist.tk/assets/img/logo.png)
# Shield Bot List API for Java.
This is the Java library for Shield Bot List's API (server count updation), developed by Shindou Mihou, under the programming language Java.
The API is completely open-source and is free to use, modify to your liking as I cannot maintain the other versions by my own.

#### Installation
There are three different versions for this API, one for Javacord, one for JDA and one for Discord4j which are the three largest Java APIs for Discord as of writing, if you wish to have yours supported, feel free to change around the code provided on any one of them as they are all fairly the same.

The links for each one are as follows:
[Javacord](https://github.com/ShindouMihou/shieldbotlist-javacord)
[JDA](https://github.com/ShindouMihou/shieldbotlist-jda)
[Discord4j](https://github.com/ShindouMihou/shieldbotlist-discord4j)

#### Usage
Their usage are also almost the same, only requiring your client (for example in Javacord: DiscordApi) to collect the server count of each one.
All three API versions should be functional as per tests, but if there are any errors, feel free to edit them (the only class that really matters is the ShieldBotApiImpl.class).

### Documentations
As of right now, the only Javadocs we have is for Javacord which pretty much works for the others unless you have modified it.
The link to the javadocs can be found on my website (since I have no place to host it). [Documentations](https://docs.paradoxium.tk).

### Please note
There may be some confusion as to what the token is, here is a brief explanation:
The token is used as an authorization code for the API to send a request to the website, or rather a key used to place requests onto the website.
There are many different tokens which can cause confusion, but the specific token the API is looking for is the one found on the official website [ShieldBotList](https://shieldbotlist.tk)

To find this token is easy, all you have to do is register your bot on the website, press the Edit Bot button then head to the very bottom where it says "Authorization Token", pressing that will reveal your token, be sure to keep it on a safe place and hidden.
