# non-visual-hepatic-feedback-game-using-Wii-remote
non-visual hepatic feedback game using wiimote

I came up with an idea to take away the screen and focuses on the surprise element of a game. At first I was going to make my own remote but thought against it and saw https://github.com/the-raspberry-pi-guy/Wiimote youtube video and that set everything into motion. Since a Wii remote has a rumble feedback which is the main objective of this game I went to see what is out there. @The-raspberry-pi-guy showed a great example pairing and showing the feed back the Wii remote sends to the raspberry pi but I wanted to do the opposite. My idea was to make the remote rumble randomly. And so the journey for the 2018 Valley Hackathon Event in Modesto,CA started. With the help of the other collaborator we tried pairing the Wii remote using the cwiid library as @the-raspberry-pi-guy code suggest but it would not work. I did get it to pair but it would say wiimote not found. Seeing it had motion plus inside did not seem like a big deal but I was wrong. Believe me, make sure you have an original Wii remote only!! Once we used the correct Wii remote it was smooth sailing. Make sure you install cwiid library. Then we needed to figure how to send a rumble to the Wii remote have the player respond within a certain time and it would continue on a random loop until the player missed the response time and woulwould be game over.

We plan on continuing to expand on this game and add more remotes to the game ideally so a group can all have their own remote and the random loop of not knowing who is getting the rumble next. We also plan to have levels ideally which would get harder the longer you play.

