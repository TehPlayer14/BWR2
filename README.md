# BWR2
TF2 MvM Be With Robots 2

Informations:
Official group http://steamcommunity.com/groups/TF2BWR2
Remember to update tf2items.randomizer.txt after an TF2 update!
___The Story___
[CODE]Begin log - 03.11.2012
  Location: Tank Carrier
  
  It was a windy night on the desert after so many fails trying to destroy Mann co, that we gave up until one day...
  Knocking*
  Robot Scout: Did you hear that?
  Robot Soldier: Yes its seems somebody or something is knocking our tank carrier trapdoor
  Robot Scout: Sniper go open it and see who's at the trapdoor
  Robot Sniper goes to trap door* robot footsteps*
  Robot Sniper: Who are you?
  ???: Me?
  Robot Sniper: Yes you, are you one of red team?
  ???: No I m from blue team my name's Leonardo I m here to offer you help destroying Mann co
  Robot Sniper: Wait a minute Goes back to robots and talks about his offer*
  Robot Sniper: Yes we can accept you if you will help us
  Leonardo: Ok i m going to help you...
  End log
  
  Begin log 19.03.2014
  After destroying a lot of Mann co's factories we realized that Leonardo help was very good indeed
  Location: Decoy (Middle of the desert)
  
  We have sent our fastest unit Super Scout
  He was at the hatch and he was deploying the bomb until he jumped and killed himself and the bomb didn't exploded!
  Robot Scout: WHATS GOING ON WITH THE BOMB?
  Robot Sniper: I don't know maybe it's broken?
  *One of the red team throws a hologram projector
  Message from Leonardo: Class: Spy *Spy's laugh phahahahaooooohahahahahahahahaha you stupid robots I have tricked you, I have broke the bomb so you can't deploy it, and also i have messed up your buff banners that they will not work, last more thing I m out of TF2 and I have last surprise for you robots YOU ARE TERMINATED! pushes the button that disables all robots
  Robot Scout: NOOOOOOOOOO system shutting down...
  End log
  
  And after that Mann co won the war with robots harmony and peace was restored until the day someone...
  
  Begin log 19.10.2014
  Location Bigrock
  
  Michal: *Walks to the tank carrier
  Michal: What happened? why all robots are down?
  Michal: I might know wasn't that Leonardo that spy?
  Michal: I need to help them repair the bomb, buff banners and reactivate robots
  Michal: Hmmm what that switch do? Pushes it*
  Michal: That did reboot robots
  Robot Scout: What happened where I m? what date is it,  how long I was shut down for?
  Michal: You was shut down for about 7 months after Leonardo disabled you all
  Robot Scout: Thanks for your help you're welcome to our Robot team
  Michal: No problem...
  
  
And then the war begun again this time robots maybe will win the war and take control of Mann co
 
End log
[/CODE] This plugin allows players to play as robot on MvM mode


Contributors:
Benoist3012
Who's Credit to team:
Leonardo for the orginal plugin;
Oshizu for the help;
Benoist3012 for porting TF2ItemsInfo to TF2Items for early verison of BWR 2;

Plugin future:
Bot control will replace BWR 2 soon
How to find a server with [TF2]BWR 2?
Type into description BWR2 and click refresh BWR Must be uppercase!
Official group:
Here

//
Here //offline
Dependencies:
TF2Items snapshot extension;
TF2Items Randomizer's gamedata;
TF2 Attributes plugin.
Optional:
mvm_visiblemaxplayers;
10vM;
Cleaner; if you are using mvmvisiblemaxplayer (put this in cleaner.cfg)
[CODE]
Setting sv_visiblemaxplayers to 6 for MvM
Setting sv_visiblemaxplayers to 7 for MvM
Setting sv_visiblemaxplayers to 8 for MvM
Setting sv_visiblemaxplayers to 9 for MvM
Setting sv_visiblemaxplayers to 10 for MvM
Bad pstudiohdr in GetSequenceLinearMotion()!
[/CODE] How to install?
Have Sourcemod 1.7

Step 00: Only for upgrading from TF2BWR Reborn: Remove old tf2bwr.smx in plugins folder before installing new bwr2.smx!
Step 01: Install Snapshot TF2Items
Step 02: Get tf2items.randomizer.txt from attached files
Step 03: Put tf2items.randomizer.txt in /addons/sourcemod/gamedata/
Step 04: Install TF2 Attributes plugin.
Step 05: Download zip from attached files
Step 06: Extract to addons/sourcemod folder
Known issues:
1/ Animation glitches, so alot of taunts disabled;

ToDo list:
(Important issues color)
Proper disguise for red spies
Make menu if randomize cvar is off
Balance variants
Fix health for giants
Fix bugs
Boss System:
Here
You can become the boss on creatain waves or by using admin menu
CVars & CMDs:
[CODE]// List of console variables
sm_tf2bwr_version // version
sm_tf2bwr_logs 1 // enable/disable logs
Removed  sm_tf2bwr_autoupdate 0 // enable/disable autoupdate
sm_tf2bwr_flag 0 // allow human robots to pick up flag/bomb
sm_tf2bwr_freeze 1 // freeze human robots between rounds
sm_tf2bwr_respawn_red 20 // respawn timer fix (RED team)
sm_tf2bwr_respawn_blue 7 // respawn timer fix (BLU team)
sm_tf2bwr_randomizer 1 // pick random class variant after death
sm_tf2bwr_buster 1 // enable/disable human busters
sm_tf2bwr_autojoin 1 // handle autojoin command with change to be thrown to the BLU team
sm_tf2bwr_autoupdate 0 // use Updater
sm_tf2bwr_restrict_ready 1 // block Ready status command (BLU team)
sm_tf2bwr_max_defenders 7 // Limit of defenders ( 10 - max_defenders = max_human_robots )
sm_tf2bwr_min_defenders 4 // Defenders count required to join BLU team
sm_tf2bwr_min_defenders4giants 6 // Defenders count required to allow BLU team select giant robots
sm_tf2bwr_notifications 1 // Show/hide chat notifications
sm_tf2bwr_engineers 1 // Allow/disallow robot engineers  
  // List of commands
sm_robotmenu // show class/class_variants menu
sm_robomenu // same as above
sm_robotclass // same as above
sm_roboclass // same as above
sm_robothelp // print help info
sm_robohelp // same as above
sm_bewithrobots // same as 'jointeam blue'
sm_joinblue // same as above
sm_joinblu // same as above
sm_joinred // same as 'jointeam red'
sm_bwr_players // display player list
sm_bwr_kick // Admin: move players to Spetators  
  // Access command overrides
tf2bwr_joinred // default: everyone
tf2bwr_joinblue // default: everyone
[/CODE] Change log:
