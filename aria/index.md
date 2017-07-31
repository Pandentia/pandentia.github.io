# Aria
Aria is the first moderation-oriented bot I made with my own framework, and I think I did a pretty good job.

### [Invite Link](https://discordapp.com/oauth2/authorize?client_id=244901248153681931&scope=bot&permissions=8)
* Requires administrator <sup>[why?](#adminreason)</sup>

## Features
* Global bans (to prevent the worst of the worst from joining your server)
* Mod logs
* Welcome messages
* Temporary voice channels
* Temporary bans
* Regex message filtering
* Hackbans
* Voice kicks
* Message logging
* Client crash prevention

Some of these features are enabled by default, like message logging and client crash prevention. These can however be
disabled at any time.

You can find the commands to enable all of this via `??help`.


### Making feature requests
Please submit feature requests via the `??feedback` command.

## FAQ
* **Q:** Why did Aria leave my server?<br>
  **A:** This can happen for 3 reasons:
    * If your server is too small (<5 people), she will leave, as there's not really a need for her there.
    * If your server's bot-to-human ratio is too high, she will leave, due to the fact that I still have to
    pay my server's power bill and sitting around, idling, in a bot testing server is wasteful.
    * <a name="adminreason"></a>If you don't grant Aria administrator privileges within 2 minutes of adding her, she 
    will leave. This is due to the fact that Aria is a moderation bot, which makes her quite useless without admin 
    permissions.
        * I realize that trusting a bot with admin permissions can be difficult, but Aria will only perform 
        administrative actions if they have been enabled beforehand (with the exception of crash prevention, which 
        protects server members from malicious users attempting to crash their clients, however even this feature can
        be disabled). I use Aria on my own servers too, thus the integrity of any server Aria is on is of utmost 
        importance to me. If you believe Aria has performed an administrative action without it being requested, 
        please inform me with the `??feedback` command.

## Name origin
Some of you might wonder why I picked this name, and won't
even understand who or what the avatar is. Basically, the long
and short of it is that [Aria](http://masseffect.wikia.com/wiki/Aria_T'Loak)
is an [asari](http://masseffect.wikia.com/wiki/Asari) who controls
a mining asteroid known as Omega. To quote the wiki,
> Aria is very authoritative of her reign on Omega, ruling the
station with an iron fist. *[...]* Almost nothing that happens on Omega escapes her notice, causing mercenary groups
to think twice before crossing her.

Due to my love of the Mass Effect series and its story, I felt that this was the perfect name for my moderation bot.
