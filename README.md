# Devzat

Where are the devs at? Devzat!

Devzat is chat over SSH. Because there's SSH apps literally on all platforms, even your phone, you can connect to Devzat on any device!

![image](https://user-images.githubusercontent.com/38882631/115499526-a4d70280-a280-11eb-8723-817f54eccf3e.png)


## Usage

Try it out:

```sh
ssh devzat.hackclub.com
```

If you're under a firewall, you can still join on port 443:
```sh
ssh devzat.hackclub.com -p 443
```

If you add this to `~/.ssh/config`:
```ssh
Host chat
    HostName devzat.hackclub.com
```

You'll be able to join with just:
```sh
ssh chat
```

We also have a Slack bridge! If you're on the [Hack Club](https://hackclub.com) Slack, check out the `#ssh-chat-bridge` channel!

Help:

```text
Welcome to Devzat! Devzat is chat over SSH: github.com/quackduck/devzat
Because there's SSH apps on all platforms, even on mobile, you can join from anywhere.

Interesting features:
• Many, many commands. Check em out by using /commands.
• Built in Tic Tac Toe and Hangman! Run /tic or /hang <word>
• Markdown support! Tables, headers, italics and everything. Just use "\n" in place of newlines.
  You can even send ascii art with code fences. Run /ascii-art to see an example.
• Emoji replacements 🔥 ! :rocket: => 🚀  (like on Slack and Discord)
• Code syntax highlighting. Use Markdown fences to send code. Run /example-code to see an example.

For replacing newlines, I often use bulkseotools.com/add-remove-line-breaks.php.

Made by Ishan Goel with feature ideas from friends.
Thanks to Caleb Denio for lending his server!
```

```text
Available commands
   /dm    <user> <msg>   Privately message people
   /users                List users
   /nick  <name>         Change your name
   /tz    <zone>         Change timezone as per IANA (eg: /tz Asia/Dubai)
   /color <color>        Change your name color
   /tic   <move>         Play Tic Tac Toe!
   /hang  <letter/word>  Play Hangman!
   /all                  Get a list of all unique users ever
   /emojis               See a list of emojis
   /people               See info about nice people who joined
   /exit                 Leave the chat
   /hide                 Hide messages from HC Slack
   /bell                 Toggle the ansi bell
   /id    <user>         Get a unique identifier for a user
   /ban   <user>         Ban a user, requires an admin pass
   /kick  <user>         Kick a user, requires an admin pass
   /help                 Show help
   /commands             Show this message
```

## People

People who you might know who have joined:

**Zach Latta - Founder of Hack Club: _"omg amazing! this is so awesome"_  
Bereket [@heybereket](https://twitter.com/heybereket): _"this is pretty cool"_  
Ayush [@ayshptk](https://twitter.com/ayshptk): _"Can I double star the repo somehow :pleading_face:"_  
Sanketh [@SankethYS](https://twitter.com/SankethYS): _"Heck! How does this work. So cool."_  
Srushti [@srushtiuniverse](https://twitter.com/srushtiuniverse): _"Yess it's awesome. I tried it."_  
Surjith [@surjithctly](https://twitter.com/surjithctly): _"Whoa, who made this?"_  
Arav [@HeyArav](https://twitter.com/HeyArav): [_"Okay, this is actually super awesome."_](https://twitter.com/tregsthedev/status/1384180393893498880)  
Harsh [@harshb__](https://twitter.com/harshb__): _"im gonna come here everyday to chill when i get bored of studying lol, this is so cool"_
Krish [@krishnerkar_](https://twitter.com/krishnerkar_):  [_"SHIT! THIS IS SO DOPE"_](https://twitter.com/krishnerkar_/status/1384173042616573960)  
Amrit [@astro_shenava](https://twitter.com/astro_shenava): _"Super cool man"_
Mudrank [@mudrankgupta](https://twitter.com/mudrankgupta): "🔥🚀🚀"**

From Hack Club:  
**Caleb Denio, Safin Singh, Eleeza A    
Jubril, Sarthak Mohanty, Anghe    
Tommy Pujol, Sam Poder, Rishi Kothari    
Amogh Chaubey, Ella Xu, Hugo Hu  
Matthew Stanciu**





### *Made by [Ishan Goel](https://twitter.com/IshanTheIshan) with feature ideas from friends. Thanks to [Caleb Denio](https://twitter.com/CalebDenio) for lending his server!*
