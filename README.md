# ZThread-BOT 
-----------------------------🧵
<p align="center">
<img src="https://user-images.githubusercontent.com/51421090/234418436-484e4361-b976-4c39-8f4b-70257059e56b.png"</img>
</p><br> 
 
is a simple way to reorganize your discord channels in threads, it takes place in 2 steps :

**1 - Put the reaction 🪡 on a message to start a thread** 

**2 - Put the reaction 🧵 on the message you want to add to the thread** 

Optional : - Use the reaction ✂️ to output text from the thread and send it to the parent channel
<br><br><br>

## How to install

**You can directly add it to your discord server by going to => [this link]([https://top.gg/fr/bot/1100136352978317363](https://discord.com/oauth2/authorize?client_id=1291467962166804500&permissions=8&redirect_uri=https%3A%2F%2Fdiscord.com%2Foauth2%2Fauthorize%3Fclient_id%3D1291467962166804500&integration_type=0&scope=bot))**  
<br>

**Or you can install it locally :** 

Add your tokens and id in your `.env`, or set the `config.json` 

Install packages with `pnpm install` 

Run the command `node index.js` for start the bot 

Run the command `node deploy-commands.js` to deploy slash commands
<br><br>


**Or you can use Docker and build your image => `docker build -t zthread-bot .`** 

<br>

## Slash Commands

__For Admins :__  

**/setadmin** => *To restrict bot actions to administrators* (default)

**/seteveryone** => *To make bot actions open to everyone*
<br><br><br>
__For Everyone :__  

**/status** => *To visualize the bot status*

<br>


## Dependencies 

[discord.js](https://discord.js.org/#/) : A library for interacting with the Discord API. 

[supabase.js](https://supabase.com/) : A library for interacting with the Supabase API
<br><br><br>

----------------------------------------------------------------------------------------------------------🧵

