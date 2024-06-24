## Twitch
?> **Limits**<br>Non-Donor Manacord servers are limited to subscribing to 15 Twitch channel notifications.<br>Donor Manacord servers are unlimited to subscribing to how many Twitch channel notifications they want.

<!-- ![Twitch](_images/twitch.png ':size=100%')-->

<!-- tabs:start -->

<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**twitch user add** \<name> [channel] [msg]<br><span class="user-permissions">Manage Server</span> | `/twitch user add shroud #live {name} went live` | Binds the streamer's live alerts to the channel.
**twitch list**<br><span class="user-permissions">Manage Server</span>   | `/twitch list`    | Shows all the binded streamers and their live status.                         
**twitch online**<br><span class="user-permissions">Manage Server</span> | `/twitch online`  | Shows all currently live streamers.                                           
**twitch user remove** \<name><br><span class="user-permissions">Manage Server</span> | `/twitch user remove shroud` | Unbinds a streamer's live alerts.
<!-- tabs:end -->
?> **Information/Changes**<br><channel> and <msg> are optimal and do not have to be used. If they are left empty, the global fallback properties are used.<br>User updates can be made if you use user add and just add/leav empty the options.


### Variables
These variables can be used in the message that is sent when a streamer goes live:
- `{link}` - Stream link
- `{name}` - Streamer's username
- `{game}` - Game being played
- `{everyone}` - Tags @everyone


## YouTube

!> No custom messages possible at the moment, follow the update log!<br>This means that the variables for YouTube can currently be ignored.

<!-- tabs:start -->

<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | -----------------------------------------------------------------------------
**youtube user add** \<name> [id]<br><span class="user-permissions">Manage Server</span> | `/youtube user add https://youtube.come/UCX6OQ3DkcsbYNE6H8uQQuVA` | Binds the youtuber channel's alerts to the channel. Can use channel id only at the time (which is the most accurate way).
**youtube list**<br><span class="user-permissions">Manage Server</span> | `/youtube list` | Shows all the binded youtubers and the connected channels.         
**youtube user remove** \<name><br><span class="user-permissions">Manage Server</span> | `/youtube user remove https://youtube.come/UCX6OQ3DkcsbYNE6H8uQQuVA` | Unbinds a youtuber channel's alerts.

<!-- tabs:end -->

### Variables
These variables can be used in the message that is sent when a youtube alert is received:
- `{link}` - Channel link
- `{author}` - Channel name
- `{everyone}` - Tags @everyone