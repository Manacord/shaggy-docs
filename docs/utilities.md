## Giveaways
?> This feature is currently in open beta so expect frequent changes and updates.

<!-- tabs:start -->

<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**giveaway create** \<duration> \<winners> \<prize> [channel=current]<br><span class="user-permissions">Manage Server</span> | `/giveaway create 10m 1 Nitro` | Creates a giveaway for the specified duration, number of winners, prize and optional channel which defaults to the channel that the command is used in.
**giveaway reroll** \<giveaway_id> [members...]<br><span class="user-permissions">Manage Server</span> | `/giveaway reroll 23 @Manacord` | Rerolls the giveaway with the specified giveaway id. Optionally, you can mention the members that should be excluded from the reroll.
**giveaway end** \<giveaway_id><br><span class="user-permissions">Manage Server</span> | `/giveaway end 42` | Ends an ongoing giveaway prematurely. You will be asked if you want to announce winners or not.
**giveaway list** [choice=active]<br><span class="user-permissions">Manage Server</span> | `/giveaway list inactive` | Shows the list of active/inactive giveaways.
**giveaway participants** \<giveaway_id><br><span class="user-permissions">Manage Server</span> | `/giveaway participants 4` | Check the users that have participated in a particular giveaway.

<!-- tabs:end -->