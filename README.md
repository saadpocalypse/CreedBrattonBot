# Creed Bratton Bot

This reddit bot uses PRAW, Reddit's API wrapper for functioning. <br>
The bot goes through the top ten posts in the 'hot' section of the [subreddit](https://www.reddit.com/r/DunderMifflin/) dedicated to the show, [The Office](https://en.wikipedia.org/wiki/The_Office_(American_TV_series)) (US version). <br>
It goes through the comments of the posts and looks for the name of a character, 'Creed Bratton', being mentioned. <br>
If the name is found, it posts a reply under the comment with a quote from the character chosen at random from an array of quotes. <br>
The bot then sleeps for certain amount of seconds as to not be seen as spam and shut down. <br>
