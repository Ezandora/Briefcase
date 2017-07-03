Briefcase
=====
Script for the Kremlin's Greatest Briefcase in Kingdom of Loathing. Also includes a relay override with a \~ghost briefcase\~ oOOooOOoooo.



Installation
----------------
Run this command in the graphical CLI:
<pre>
svn checkout https://github.com/Ezandora/Briefcase/branches/Release/
</pre>
Will require [a recent build of KoLMafia](http://builds.kolmafia.us/job/Kolmafia/lastSuccessfulBuild/).



Usage
----------------
Type "briefcase help" into the graphical CLI, or select Scripts>Briefcase.ash from the menu, and type in "help".

Some commands:  
__enchantment__ or __e__ - changes briefcase enchantment (type "briefcase enchantment" for more information.)  
__unlock__ - unlocks most everything we know how to unlock.  
__buff__ or __b__ - obtain tab buffs.  
__status__ - shows current briefcase status  
__help__  
__solve__ - unlocks everything we know how to unlock, also solves puzzles. You may want the "unlock" command instead.  

__drawers__ or __left__ or __right__ - unlocks all/left/right drawers  
__hose__ - unlocks martini hose  
__drink__ or __collect__ - acquires three splendid martinis and other dailies  

Unimportant commands:  
__charge__ - charges flywheel (most commands do this automatically)  
__second__ or __third__ - lights respective light  
__identify__ - identifies the tab function of all six buttons  
__reset__ - resets the briefcase  
__stop__ - stops moving tabs  


Enchantments  
----------------  
The briefcase has three configurable slots, which each can be one of the following.  
Slot 1:  
__weapon:__ +25% weapon damage  
__spell:__ +50% spell damage  
__prismatic:__ +5 prismatic damage  
__critical:__ +10% critical hit  

Slot 2:  
__init:__ +25% initiative  
__absorption:__ +100 Damage Absorption  
__hot__ or __cold__ or __spooky__ or __stench__ or __sleaze:__ +5 (type) resistance  

Slot 3:  
__regen:__ 5-10 HP/MP regen  
__adventures:__ +5 adventures/day  
__fights:__ +5 PvP fights/day  
__-combat:__ -5% combat  
__+combat:__ +5% combat  
__ml:__ +25 ML  
__skills:__ -3 MP to use skills  


The command "briefcase enchantment prismatic init adventures" would give your briefcase +5 prismatic damage, +25% init, and +5 adventures/day.  
"briefcase e -combat" would give it -combat.  


Buffs  
----------------  
The briefcase can give fifty turns of various buffs, via complicated tabs.  

__meat:__ +100% meat (not yet known)  
__item:__ +50% item (not yet known)  
__init:__ +50% init (not yet known)  
__experience,__ or __xp:__ +5 stats/fight (not yet known)  

__hp,__ or __mp:__ +100% HP/MP (not yet known)  
__muscle:__ +100% muscle (not yet known)  
__myst:__ +100% myst (not yet known)  
__moxie:__ +100% moxie (not yet known)  

__muscle_absolute:__ +30 muscle (not yet known)  
__myst_absolute:__ +30 myst (not yet known)  
__moxie_absolute:__ +30 moxie (not yet known)  


The command "briefcase buff item" would spend clicks until we obtained the +50% item buff. "briefcase buff meat" would do the same for +meat.