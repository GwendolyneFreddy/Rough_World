
![Latest Release](https://img.shields.io/github/v/release/SpellholdStudios/Rough_World?include_prereleases&color=darkred)<a name="top" id="top"> </a>
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20Mac%20%7C%20linux&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French&color=limegreen)


<div align="center"><h1>Rough World</h1>

<h3>A Spellhold Studios mod for BG:EE (with or without SoD),<br>
BG2:EE, IWD:EE and PsT:EE<h3>


</div><br />


**Author:** elminster  
**Mod Website:** <a href="http://www.shsforums.net/topic/58723-mod-rough-world-beta/">Spellhold Studios</a>  
**Alternative:** <a href="https://forums.beamdog.com/discussion/59889/elminsters-difficulty-adjustments">Beamdog</a>  

## 

:warning: **This mod is not compatible with EET**

## 

[Download the mod at Spellhold Studios](http://www.shsforums.net/files/file/1149-rough-world-beta/)<br>

## 

<div align="center">
<a href="#intro">Overview</a> &#x2B25; <a href="#compat">Compatibility</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Components</a> &#x2B25; <a href="#credits">Credits</a> &#x2B25; <a href="#version">Version History</a></br>
</div>


<hr>


## <a name="intro" id="intro"></a>Overview

In essence, this mod intends to change the tone of the games reputation system, adds a bit of difficulty, and makes the world feel not quite as forgiving.
 
The concept behind this mod is to make the world a rougher place. Low reputation characters are considered to be absolutely horrid human beings - so there is a very low expectation that they will assist anyone. When they do it is regarded as being an exceptional act. As a result, low reputation characters now have a lower bar to donating to increase their reputation than higher reputation characters. Merchants are also actually now inclined to give them a discount - if only to ensure they themselves are not hurt. 

Likewise, because the world is such a dark and unforgiving place, characters that have higher reputation amounts are seen in a much more positive light. People are more willing to forgive them should they make a mistake (such as killing a civilian).
 
It also includes some of the components I've been working on for my upcoming *Eve of War* mod. This includes a component that significantly changes how chapter 7 is handled in the game. You can find more details on this below.

The mod also has other components that increase the games difficulty.
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components

## 

Installation order: It should probably be installed after any quest or romance mods but before any other tweak mods. However, I could be wrong here so please feel free to report any issues you have with this working with other mods so we can determine the best time to install this.

Scaled Spawning should be installed before you install Fixed Insane Difficulty.

Mod-EN=Mod scaling spawning and alternating Legacy of Bhaal 


<hr>


## <a name="components" id="components"></a>Components

The installer includes the following 9 components. The number of each is the component *`DESIGNATED`* number which gives it a fixed install position, lets other components detect it and allows automated installers to specify component choices.

## 

**[0] Scaled Spawning** (BGEE Original Campaign Only)

This component adds new creatures (including creatures that you would otherwise not encounter in BG1) along the main (critical) path of the game. This is in part based on your difficulty level. This also does not change the AI for these creatures (so if you want a challenge there you might want to look into something like SCS). These are all just one-time encounters (they won't respawn). 

## 

**[1] Sparse Resting** (BGEE Original Campaign Only)

This component changes the probability of successfully resting in some areas based on your difficulty setting. In some cases it may now be extremely difficult to successfully rest. It will also open up the option to rest in other areas (that previously blocked resting). 

## 

**[2] Chapter 7 Hardcore** (BGEE Original Campaign Only)

This component does three things.

1. It makes it so that when you hit chapter 7 you lose access to all areas within the City of Baldur's Gate (as well as the farm area). The only way to access the city (and to leave as well) is to pay a smuggler to bring you into and out of the city. The smuggler can be found near the bridge in the bridge area.
2. It makes it so that your movement within the city is very limited. You are only able to move one area at a time - even if you have previously explored a section of the city.
3. It adds Flaming Fist patrols to the streets.

These restrictions will end at the end of Sarevok's coronation ceremony.

## 

**[3] Improved Beggars** (BGEE Original Campaign Only)

Beggars now have flies flying over top of their heads. Extremely low reputation parties can give them a donation and (provided they acted respectfully when doing so) can get a small reputation increase.

## 

**[4] New Reputation Names**

This component renames the description you get for your given level of reputation to one of the following:

- Savior
- Hero
- Adventurer
- Meddler
- Ruffian
- Thug
- Sadist

## 

**[5] Reputation Rebalanced** (BGEE Original Campaign Only)

This component changes reputation in a couple of ways:

- Higher and lower reputation characters get better prices in stores. A character with around 10 reputation for instance would pay more for a good than one with 1 or 20.
- Starting reputation only varies between 9 and 11 now.
- A low reputation character killing someone in law enforcement is now unlikely to cause further reputation losses. Killing civilians however will.
- The reaction modifier for players with higher reputation is improved. Players with 20 reputation now will get +7 to reaction instead of +4. This essentially makes the progression more even than in the vanilla game (at least compared to how low reputation's are handled).
- Very low reputation characters will pay less to see a reputation improvement from donating to a church.

## 

**[6] Innocence Reconcieved** (BGEE Original Campaign Only)

This component changes who the game considers to be "innocent", meaning that killing people found in obscure locations (defined as being either a diagonal location or more than one (e,w,s,n) area away from an urban area) will not result in a reputation loss.

Also makes it so that if you are a paladin that kills an innocent person you lose your paladin status. Rangers however do not face this restriction.

## 

**[7] Fixed Insane Difficulty**

Legacy of Bhaal is forced Insane difficulty : this component turns Legacy of Bhaal into effectively a game where you are permanently playing on the insane difficulty setting.
 
*Note: I do not recommend you install the Fixed Insane Difficulty and Only Autosaves components after you have already started a game. The results could be very mixed if you do so.*

## 

**[8] Only Autosaves**

This component makes it so that you cannot save the game. You must rely on autosaves (and your own wit) to make your way through it.

*Note: This component may cause issues with the game. Let me know (preferably through the thread on the Beamdog forums for this mod) if you experience any problems with it.*

<div align="right"><a href="#top">Back to top</a></div>


<hr>




<hr>


## <a name="versions" id="versions"></a>Version History

##### Version 1.41 &nbsp;(June 21, 2019)

- Fixes an issue that prevented the new reputation system from being used in SoD.
- Due to a bug with blackguards falling I've removed the innocence re-conceived component of the mod. I will reintroduce it sometime in the future when this is fixed.

## 

##### Version 1.4 &nbsp;(April 2, 2017)

- Hopefully fixed an issue that was causing the Only Autosaves component to cause maps to reset.

## 

##### Version 1.3 &nbsp;(December 16, 2016)

- Removed one shambling mound from Cloakwood Forest for players on harder difficulties.

## 

##### Version 1.2 Beta &nbsp;(October 19, 2016)

- Updated to WeiDU v240.

## 

##### Version 1.1 Beta &nbsp;(September 10, 2016)

- Updated Polish translation.

## 

##### Version 1.0 Beta &nbsp;(September 10, 2016)

- Added a bunch of new options to the mod.

## 

##### BGEE Difficulty Adjustments v1.2 &nbsp;(August 29, 2016)

- Added Polish translation provided by Etamin.

## 

##### elminster's Difficulty Adjustments v1.1 &nbsp;(August 9, 2016)

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>

