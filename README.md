# Final-Project
This program is a discord bot created by Nicolas De Jesus in 2022 for his final project in CIS 1051 with Professor Rosen, titled "Discord Sneaker Resell Utility Bot".

This program is a simple, but yet effective discord bot you can add to your sneaker resell discord server. It contains multiple useful functionalities such as a weekly 'hype' sneaker release calendar (with estimated retail and resell prices), details on the most hype sneaker of the month, and fee information for when you are interested in maxamizing profits when selling off some of your shoes. 

How To Use:

- First initialize a bot on the discord developer portal.
- Next, give the bot proper text permissions in the developer portal.
- Next, have the bot join your discord server using the link provided in the bot section
- Next, input your private token in the token variable on line 6 to initialize the variable.
- Lastly, run the bot, watch it join your server, and enjoy.
- !!! note: The commands only work in a specified channel, by default they work in the "commands" channel as specified on line 20.


Available Commands (case insensitive):
!weekly - prints out a well formatted list of the weekly sneaker releases for the first month of may (soon to be updated automatically)
!mosthyped - prints out a hype message followed by the users name along with telling the user the most hyped (highest profit) shoe to release in that specified month.
!fees - prints out a well formatted list of the amount of fees you will be charged selling your shoes on different platforms, maximize your profit with this functionality.

Video of Walkthough - Submitted to canvas.

Sources: 
- https://discordpy.readthedocs.io/en/stable/intro.html
- https://discordpy.readthedocs.io/en/stable/quickstart.html
- https://discordpy.readthedocs.io/en/stable/api.html#
- https://www.remote.tools/remote-work/discord-text-formatting
- https://www.writebots.com/discord-text-formatting/
