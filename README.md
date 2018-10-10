# tirc

packet-level irc message translation.

tirc works by acting as a proxy, detecting the language of and translating incoming irc messages before sending them to the client. 

[irc client] <- [tirc] <- [irc server]

bidirectional support may also be added, so you can choose a language to translate your messages to and have them translated before being sent.
