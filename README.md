# mysnapfix
Recently I was facing a problem in my kali-xfce with snap store.
The problem is,
Whatever application I install from from snap store, it runs from the terminal but the icons doesn't appear in the application menu.
After a google search, I found that many people are facing the same problem as I am.
But I've also found a trick to solve the problem.
So I wrote this bash script.
If you are facing the same issue,
then follow this:

--> git clone https://github.com/marufmurtuza/mysnapfix.git
--> cd mysnapfix
--> sudo cp mysnapfix /usr/bin/
--> sudo chmod +x /usr/bin/mysnapfix

Okay. You are done.
Now you can run this by simply typing 'mysnapfix' in the terminal.
Then it will ask you for the application name that you just installed from snap but can't find on the application menu.
Just type the name and hit enter and it will fix the problem.
