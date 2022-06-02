# Creed Bratton Bot

This reddit bot uses [PRAW](https://praw.readthedocs.io/en/stable/#), Reddit's API wrapper for functioning. <br><br>
The bot goes through the top ten posts in the 'hot' section of the [subreddit](https://www.reddit.com/r/DunderMifflin/) dedicated to the show, [The Office](https://en.wikipedia.org/wiki/The_Office_(American_TV_series)) (US version). <br><br>
It goes through the comments of the posts and looks for the name of a character, ['Creed Bratton'](https://theoffice.fandom.com/wiki/Creed_Bratton), being mentioned. <br><br>
If the name is found, it posts a reply under the comment with a quote from the character chosen at random from an array of quotes. <br>
The bot then sleeps for 700 seconds as to not be seen as spam and shut down. <br>
The bot is written in Python, and the code is commented for ease of understanding and use.
