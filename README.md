I have an idea for a "chat clips" twitch extension that I think might be able to help 
all twitch streamers who also create on yt and don't want to create public vods when 
they livestream with music in the background.

### Here's what I think it should have so far:

* Saves full vod (with link on discord) for X days for offline download
* Lists all user clips and timestamps with final vod
* Discord bot that uploads mp4 files to [#chat-clips] after chat clips them.
* (Normally I would say post an mp4 link to chat, but dmca troll bots REEE)

## INTERFACE:

### Video-player buttons:

    'quickclip' button
    'clip & title' button

### and/or

### Chat bot with commands: 

    !adduser username
    !clip [Clip title] [Clip length in seconds, up to MAX]

    /////// suggest bot commands
    !mod username
    !unmod username
    !guestclips on/off
    !viponly`


## Implentation

Built on AWS for scalability to all of twitch.

This will cost money to store vods and clips, but nothing compared to all the time it will save.
If Partners paid a nominal fee *I think* it can be free for everyone else to use.  This will depend 
if transcoding is required.  If no transcodes are needed, the price decreases significantly.

## Todo

- [ ] If this idea isn't confirmed as trash, figure out the actual price
- [ ] ???
