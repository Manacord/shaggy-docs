?> All commands here require `suggestion` to have been used and set in order to work.

<!--![Suggestions](_images/suggestions.png ':size=75%')-->

## Settings

<!-- tabs:start -->

<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | -----------------------------------------------------------------------------                      
**suggestion** [channel=suggestions]<br><span class="user-permissions">Manage Server</span> | `/settings set suggestion` | Sets a channel as the suggestions channel.
**suggestion-limit** \<limit><br><span class="user-permissions">Manage Server</span> | `/settings set suggestion-limit 5` | The amount of votes difference required to change the embed color to red/green. **This option is optimal and turned off by default.**

<!-- tabs:end -->


## Making Suggestions

<!-- tabs:start -->                                                    

<!-- tab:Slash Commands -->
Anyone can use the `suggest` command to make suggestions.

Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**suggest** \<content> | `/suggest make vc`| Creates a suggestion.                                   

<!-- tabs:end -->


## Suggestion Decisions

<!-- tabs:start -->           

<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**suggestion approve** \<suggestionid> [reason]<br><span class="user-permissions">Manage Server</span> | `/suggestion approve 3` | Approves a suggestion.                    
**suggestion deny** \<suggestionid> [reason]<br><span class="user-permissions">Manage Server</span> | `/suggestion deny 4 spam` | Denies a suggestion.                       
**suggestion consider** \<suggestionid> [reason]<br><span class="user-permissions">Manage Server</span> | `/suggestion consider 5` | Marks a suggestion as being considered. 
**suggestion implemented** \<suggestionid> [reason]<br><span class="user-permissions">Manage Server</span> | `/suggestion implemented 1 Added` | Marks a suggestion as implemented.

<!-- tabs:end -->