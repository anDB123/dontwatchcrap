This webapp aims to replace youtube "doomscrolling" with a much more intentional watching experience. 
Do you ever find yourself on youtube, switching through video after video but not really watching anything in particular?
Me too! That's why I created dontwatchcrap (i know there should be an apostrophe but don'twatchcrap doesn't look good. Also, it's not searchable.)

The UI is designed around keeping you focused.

<img width="1728" alt="Screenshot 2025-04-30 at 16 20 17" src="https://github.com/user-attachments/assets/c6eda3af-ed81-4325-95d8-650eb697ae8a" />

3 Buttons; Stop, delete and next. The player has no ability to pause, go forward and backward or restart the video. Like TV used to be, it's on and you're watching or you miss it. I may remove the pause feature but I felt it better to do this than make the user close the webstie when not watching.


<img width="1728" alt="Screenshot 2025-04-30 at 16 21 05" src="https://github.com/user-attachments/assets/9189b01c-fd16-493c-bcdb-b20c0ea416b1" />
Instead of browsing through recommended content, you need to search for videos. I prefer this as i'ts more intentional than a browse but I don't like that it encourages you to find videos through youtube (THE WEBSITE WE WERE TRYING TO AVOID). Hence, it's a bit of a dumb decision in retropect. I would need to design a brand new browse that will increase your chances of finding good content. Maybe some categories and then videos within those or something.

I've also added a table view. As you get more and more videos, you might want to look for a specific one. If so, the next button becomes less and less useful. 

<img width="1728" alt="Screenshot 2025-04-30 at 16 23 10" src="https://github.com/user-attachments/assets/5d610159-cd44-4a27-9659-b584b97658cd" />

The main issue if I tried to host this is that my youtube search API only allows 100 searches per day. With this limitation, it becomes a bad use of time to continue development presently. The only way around this would be applying to increase my search limit which requires google to check my code. BOOOOOO! 

This was really fun to develop but I might set my sights on something less reliant on an API next. It's a bit annoying to run into walls.
