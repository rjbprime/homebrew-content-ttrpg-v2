---
pageSize: A4
---

<style>

:root {
  --main-color:           #9B0719;
  --main-color-dark:      #0F6475;
  --main-color-light:     #5BB1C2;
  --main-color-lighter:   #D0E8ED;
  --main-color-lightest:  #F6FDFE;

  --main-color-stripe1:   #fbfbfb;
  --main-color-stripe2:   #f5f5f5;
}

.smallerRE {
    font-size: 5.5pt;
}

.smallerIT {
    font-size: 5.5pt;
    font-style: italic;
}

.phb .classTable h5,
.phb blockquote h5,

.phb .classTable {
    border: 3px solid var(--main-color);
    margin: 0em 0.2em 1.5em 0.2em;
    padding: 0 .5em;
    border-image: -webkit-linear-gradient(135deg, var(--main-color) 0%, var(--main-color-lightest) 50%, var(--main-color) 100%) 1;
    background: #fff;
    position: relative;
}

.phb .classTable:before, .phb .classTable:after {
    content: "";
    border: 3px solid var(--main-color);
    position: absolute;
    z-index: -1;
    display: inline-block;
    padding: 12px;
}

.phb .classTable:before { top: -9px; left: -9px; }
.phb .classTable:after {bottom: -9px; right: -9px; }

.phb{
	width : 210mm;
	height : 297mm;
	padding: 8mm;
	column-gap: 4mm;
}

/** Import Fonts **/
@import url('https://fonts.googleapis.com/css?family=IM+Fell+English');
@import url('https://fonts.googleapis.com/css?family=Uncial+Antiqua');
/** Defining fonts **/
@font-face {
	font-family: 'First Order';
	src: url('https://groumy.github.io/homebrewery-sotdl/fonts/firstv2.ttf')
}
@font-face {
	font-family: 'GothamBold';
	src: url('https://groumy.github.io/homebrewery-sotdl/fonts/GothamBold%20Regular.otf')
}
@font-face {
	font-family: 'GothamBook';
	src: url('https://groumy.github.io/homebrewery-sotdl/fonts/GothamBook%20Regular.otf')
}
@font-face {
	font-family: 'JSL Ancient';
	src: url('https://groumy.github.io/homebrewery-sotdl/fonts/jancieni.ttf')
}
@font-face {
	font-family: 'Poison Hope';
	src: url('https://groumy.github.io/homebrewery-sotdl/fonts/PoisonHope-Regular.otf')
}

/**	**/

.phb#p1:after {
	background: none;
	background-image: none;
	content:"";
}


.phb:nth-last-child(1):after {
	background: none;
	background-image: none;
	content:"";
}

.phb:after {
	background: none;
	background-image: url('https://groumy.github.io/homebrewery-sotdl/images/page-number-pentagram.png');
	background-size: 90px 90px;
	background-repeat: no-repeat;
	background-position: 0px calc(100% - 0px);
	height: 90px;
}

.phb {
	font-family: Athelas;
	background: url('D:/Users/Danno/Documents/dmbinder/aigr/source/imgs/sotdl-background-small.jpg');
	background-size: 100% 100%;
	background-repeat: no-repeat;
}

.phb h1{
	font-family: "First Order";
	font-size: 220%;
	text-align: center;
	text-shadow: 0px 0px 5px black;
	color:white;
	text-transform: uppercase;
	background-image: url('https://groumy.github.io/homebrewery-sotdl/images/h1.banner-large.png');
	background-size: 100% 102.5%;
	padding-top: 0.45em;
	padding-bottom : 25px;
	margin-left : 1mm;
	margin-right : 0mm;
	margin-top : -1mm;
	-webkit-font-smoothing: antialiased;
}

.phb h1+p::first-letter {
	float: inherit;
	font-family: inherit;
	font-size: inherit;
	color: inherit;
	line-height: inherit;
}

.phb h2,.phb h3,.phb h4,.phb h5,.phb h6,.phb h7 {
	font-family: "Portmanteau",'IM Fell English';
	text-transform : uppercase;
	text-align: left;
	color: rgb(155,7,25);
	font-weight: 400;
	line-height: 1.05;
}

.phb h2{
	font-size: 140%;
}

.phb h3{
	font-size: 120%;
	border-bottom-style: none;
        margin-top:auto;
        margin-bottom:auto;
        line-height: 1;
}

.phb h4{
	font-size: 115%;
}

.phb h5{
	font-size: 110%;
	border-bottom-style: solid;
	border-bottom-color: black;
	border-bottom-width: 1px;
}

.phb h6{
	font-size: 105%;
	border-bottom-style: solid;
	border-bottom-color: black;
	border-bottom-width: 1px;
	color: black;
}

.phb p, .phb li, .phb ol{
	font-family: 'GothamBook';
	font-size: 7.5pt;
    text-align: left;
    padding-right: 1mm;
    padding-left: 1.1mm;
}

.phb table thead th {
	background-color: #000000;
	color: #ffffff;
	font-family: "GothamBook";
	font-size:.85em;
	padding-top: 3px;
	padding-bottom: 3px;
}
.phb table tbody tr{
	font-family: "GothamBook";
	font-size:.85em;
}

.phb table tbody tr:nth-child(odd){
	background-color: initial;
	font-family: "GothamBook";
	font-size:.85em;
}

.phb table tbody tr:nth-child(even) {
	background-color: #fff;
	font-family: "GothamBook";
	font-size:.85em;
}

.phb strong em, .phb em strong{
	color: rgb(155,7,25);
	font-style : normal;
	font-weight: bold;
}

.phb blockquote{
	border-image: url('https://groumy.github.io/homebrewery-sotdl/images/parchment.png') 50 round;
	background-color: transparent;
	background-image: url('https://groumy.github.io/homebrewery-sotdl/images/parchment-back.png');
	box-shadow: none;
	padding-left: 20px;
	padding-right:20px;
	padding-top:10px;
}

.phb blockquote h5{
	border: none;
	text-align: center;
	padding-bottom: 10px;
}

.phb blockquote p{
	font-size:0.83em;
}

.phb .descriptive{
	border: none;
	background-color: transparent;
	box-shadow: none;
	font-style: italic;
	padding-left:30px;
}

.phb .descriptive h5{
	font-style:normal;
	color:black;
	text-align:center;
}

.phb .footnote{
	color:black;
	font-family: "First Order";
	font-size: 2.5em;
	width:100%;
	bottom:0px;
}

.phb .pageNumber {
	margin-bottom:6px;
	vertical-align: middle;
	font-size: 12pt;
	color: rgb(155,7,25);
	margin-right:0mm;
	margin-left:0mm;
	margin-top:2mm;
}

.phb .pageNumber.auto{
	bottom:20px;
}

.phb .pageNumber.auto::after{
	height:20px;
}

.phb .pageNumber.auto p{
	font-family: "First Order";
	font-size: 12pt;
	color: black;
	text-align: center;
}

.phb .pageNumber p{
	font-family: "First Order";
	font-size: 12pt;
	color: black;
	text-align: center;
}

.html-code code{
	visibility: visible;
	box-shadow: 1px 1px 1px black;
	background-color: #000;
	font-family: 'Lucida Console'
}

.phb hr{
	visibility: invisible;
	border-style : solid;
	border-color: black;
	border-width: 1px 0px 0px 0px;
	position: relative;
}

.phb p+hr{
	top: -5px;
}


.phb .spell h4{
	font-size: 0.5em;
}

.phb:nth-child(odd):after {
	transform: scaleX(-1);
}

.phb:nth-child(even):after {
	transform: scaleX(1);
}


/** Monster Stat Block **/

.phb hr+blockquote{
	padding : 0px;
}

.phb hr+blockquote h1{
	font-family : Athelas;
	background-color: black;
	background-image : none;
	color : white;
	font-weight: bold;
	font-size: 1em;
	padding: 5px;
	float:left;
	margin: 0px;
	width:60%;
	text-align: left;
}

.phb hr+blockquote h2{
	font-family : Athelas;
	background-color: black;
	color : white;
	font-weight: bold;
	font-size: 1.2em;
	padding: 5px;
	float:left;
	width: 100%;
	margin : 0px;
	text-align:left;
}

.phb hr+blockquote h3{
	background-color: #BBB;
	color: black;
	padding: 3px;
	padding-left: 5px;
	font-size: 0.8em;
	font-family: 'GothamBook';
	font-weight: bold;
	border-style : none;
}

.phb hr+blockquote h2+p{
	clear : both;
	background-color : darkred;
	color: white;
	padding : 3px;
	padding-left: 5px;
}

.phb hr+blockquote h2+p+hr,
.phb hr+blockquote h3+hr{
	display:none;
}

.phb hr+blockquote hr+ul li {
	margin-left: 5px;
	font-family: Athelas;
}

.phb hr+blockquote hr {
	background-image : none;
	visibility: visible;
	border-style: solid;
	border-color: black;
	border-width: 1px 0px 0px 0px;
	position: relative;
}

  .toc a {
    color: inherit !important;	/*toc specifically wants black text. This resets the headers*/
    font-size:8.5pt;
  }

  .toc li span:nth-child(2){	/*Allow dot leaders to fill remaining space but not overlap*/
    width: auto;
    overflow: hidden;
    white-space: nowrap;
    display: block;
  }

  .toc li span:nth-child(2):after{
    font-family		: "Portmanteau",'IM Fell English';	/*Remove any header styles from dot leaders*/
    font-size   	: 5pt;
    font-weight		: normal;
    color			: black;
    content:
      " ........................................."
      ".........................................."
      ".........................................."
      ".........................................."
      "..........................................";
  }

  .toc li span:first-child{
    float: right;
    font-family		: "Portmanteau",'IM Fell English';	/*Remove any header styles from page numbers*/
    font-size   	: 8.5pt;
    font-weight		: normal;
    color			: black;
	margin-left		: 1px;	/*Leaves a small space between page numbers and dot leaders*/
	margin-right:-0mm;
  }

/*Special cases for headings*/
  .toc li h3 span:nth-child(2):after{
  	content: " ";						/*Remove dot leaders on h3*/
  }

  .toc li h3 {
    margin-bottom: 4px !important;		/*Special spacing for h3*/
    margin-top: 10px !important;
    line-height: initial !important;	/*For some reason Multi-line h3 line spacing changed*/
	font-size:8.5pt;
	margin-right:0mm;
  }

.toc li h4 {
	margin-bottom: 4px !important;		/*Special spacing for h3*/
    margin-top: 10px !important;
    line-height: initial !important;	/*For some reason Multi-line h3 line spacing changed*/
	font-size:8.5pt;
	margin-right:0mm;
  }

  .toc li h3 span:first-child{
  	line-height: 1.8em !important;  	/*Line page numbers up with Multi-line h3 better*/
	font-size:8.5pt;
	margin-right:-0mm;
  }

  .toc ul ul {
  	margin-left: 10px !important;		/*Original lists intented too much*/
    margin-right: -4px !important;
  }

  .toc>ul>li {
	margin-bottom: initial !important;	/*margin for list items needs to be removed or 0*/
	margin-right:0mm;
  }

.phb table {
  font-size: 9pt;
  margin-bottom:auto;
}

img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width:12mm;
    height:auto;
}

</style>

<div class='classTable wide'>

## The Brigand: Monk Rebranded

| Level | Proficiency Bonus | Scrapping Die | Spite Points | Abscond | Features |
|:---:|:---:|:---:|:---:|:---:|:---:|---:|
| 1st | +2 | 1d4 | - | - | Battle Tempo, Scrapping |
| 2nd | +2 | 1d4 | 2 | +10 ft. | Spite, Abscond |
| 3rd | +2 | 1d4 | 3 | +10 ft. | Dirty Trade, Quick Reflexes |
| 4th | +2 | 1d4 | 4 | +10 ft. | Ability Score Improvement, Tumble |
| 5th | +3 | 1d6 | 5 | +10 ft. | Extra Attack, Low Blow |
| 6th | +3 | 1d6 | 6 | +15 ft. | Undercut, Dirty Trade feature |
| 7th | +3 | 1d6 | 7 | +15 ft. | Evasion, Low-Blow, Snap Out of It |
| 8th | +3 | 1d6 | 8 | +15 ft. | Ability Score Improvement |
| 9th | +4 | 1d6 | 9 | +15 ft. | Abscond improvment |
| 10th | +4 | 1d6 | 10 | +20 ft. | Piss and Vinegar |
| 11th | +4 | 1d8 | 11 | +20 ft. | Dirty Trade feature |
| 12th | +4 | 1d8 | 12 | +20 ft. | Ability Score Improvement |
| 13th | +5 | 1d8 | 13 | +20 ft. | Loud and Clear |
| 14th | +5 | 1d8 | 14 | +25 ft. | Tough it Out |
| 15th | +5 | 1d8 | 15 | +25 ft. | Spite Death Itself |
| 16th | +5 | 1d8 | 16 | +25 ft. | Ability Score Improvement |
| 17th | +6 | 1d10 | 17 | +25 ft. | Dirty Trade feature |
| 18th | +6 | 1d10 | 18 | +30 ft. | Infiltrate |
| 19th | +6 | 1d10 | 19 | +30 ft. | Ability Score Improvement |
| 20th | +6 | 1d10 | 20 | +30 ft. | No Rest for the Wicked |

</div>

A man clad in a threadbare tunic and holding a simple axe stands tall against the line of guards. A bolt flies and clatters off the side of the axe head flashing through the air to meet it. Silence returns as the lone combatant wordlessly challenges one of them to lead the charge.

Through busy mud streets, a merchant leads his cart through the town, unaware that he's passed the same beggar thrice now on his journey.

A chorus of laughs arise from a crowd surrounding two brawlers. Drunk and giddy, the men of the rival gangs deliver cheers and catcalls at the duo as they jeer and slam into eachother. As one lunges, the other sneers. Pulling a dagger, he goes for the kill, and the crowd devolves into chaos and flashing iron. Amidst the bloodshed, the latter brawler helps up his supposedly shanked opponent and they share a grin before the two undercover guardsmen fall into the battle, their axes uncaring which gang they bite first.

### The Will of the Spiteful
The one thing that sets a brigand apart from your average thug is the spite with which they act. A brigand knows the rules of a violent world and subverts them. Their sheer will and determination to make life their own fuels them to perform acts beyond mortal limits.

### Creating a Brigand
Brigands are not studied scholars, disciplined fighters, or honorable knights. A brigand takes what anyone would have to use, down to the clothing on their back and their bare fists if needed, and they take it in stride. A brigand will thrive off their street-smarts, learning underhanded tricks and unorthodox techniques to hold their own against an armed and armored foe. 

Due to subversive nature of a brigand, many tend to be chaotic and/or evil in alignment. But that is not true for all brigands. A guard interested in upholding the spirit of the law where the word obstructs it is just as qualified to be a brigand as a lawless mercenary eager for blood money.

#### Quick Build
You can make a brigand quickly by following these suggestions. First, make Dexterity your highest  score, followed by Wisdom. Second, choose the criminal or urchin background.

## Class Features
As a brigand, you gain the following class features
#### Hit Points
___
- **Hit Dice:** 1d8 per brigand level
- **Hit Points at 1st Level:** 8 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d8 (or 5) + your Constitution modifier per brigand level after 1st

```
```

#### Proficiencies
___
- **Armor:** None
- **Weapons:** Simple weapons, shortswords
- **Tools:** Choose one type of artisan's tools or one musical instrument

___
- **Saving Throws:** Strength, Dexerity
- **Skills:** Choose two from Acrobatics, Athletics, History, Insight, Religion, and Stealth 

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
- *(a)* a shortsword or *(b)* any simple weapon
- *(a)* a dungeoneer's pack or *(b)* an explorer's pack
- 10 darts


### Unarmored Defense
Your life is precious, but armor isn't cheap. You've learned to make the best of your natural defenses.

Beginning at 1st Level, while you are wearing no armor and not wielding a shield, your AC equals 10 + your Dexterity modifier + your Wisdom modifier.


### Scrapping
At 1st level, your experience in gritty breakout brawls gives you mastery over basic versatile combat styles that use unarmed strikes and brigand weapons, which are shortswords and any simple melee weapons that don't have the two-handed or heavy property.

You gain the following benefits while you are unarmed or wielding only brigand weapons and you aren't wearing armor or wielding a shield.

• You can use Dexterity instead of Strength for the attack and damage rolls of your unarmed strikes and brigand Weapons.
• You can roll a d4 in place of the normal damage of your unarmed strike or brigand weapon.
• When you use the Attack action with an unarmed strike or a brigand weapon on your turn, you can make one unarmed strike as a bonus action. For example, if you take the Attack action and attack with a quarterstaff, you can also make an unarmed strike as a bonus action, assuming you haven't already taken a bonus action this turn.

### Spite
Starting at 2nd Level, your understanding of the world's brutal ways has taught you how to bend the rules in spite of it. Your access to this ability is represented by a number of spite points. Your brigand level determines the number of points you have, as shown in the Spite Points column of the Brigand table.

You can spend these points to fuel various spite features. You start knowing three such features: Cheap Shot, Measured Taunt, and Hightail. You learn more spite features as you gain levels in this class.

<div class='pageNumber auto'></div>

\page

When you spend a spite point, it is unavailable until you finish a short or long rest, at the end of which you recover your expended spite. You must spend at least 30 minutes of the rest relaxing to regain your spite points.

Some of your spite features require your target to make a saving throw to resist the feature's effects. The saving throw DC is calculated as follows:
___
**Spite save DC** = 8 + your Proficiency Bonus + your Wisdom modifier

#### Cheap Shot
Immediately after you take the Attack action on your turn, you can spend 1 spite point to make two unarmed strikes as a bonus action.

#### Measured Taunt
You can spend 1 spite point to take the Dodge action as a bonus action on your turn.

#### Hightail
You can spend 1 spite point to take the Disengage or Dash action as a bonus action on your turn, and your jump distance is doubled for the turn.

### Abscond
Starting at 2nd level, you are skilled at getting in and out before time is up. Your speed increases by 10 feet while you are not wearing armor or wielding a shield. This bonus increases when you reach certain brigand levels, as shown in the Brigand table.

At 9th level, your getaway talents can make every stride flow through and every finger a fish hook. You gain the ability to move along vertical surfaces and across liquids on your turn without falling during the move.

### Dirty Trade
When you reach 3rd level, you establish an irreputable talent that you've taken a shining to: Bruiser, Shadower, Primordial Ravager, Graverobber, Boozehound, Cutthroat, Heretic, Watchdog, Manifest, or Dispenser. Your trade grants you features at 3rd level and again at 6th, 11th, and 17th level.

### Quick Reflexes
Starting at 3rd level, you've learned how to react when there's no time to think. You can use your reaction to deflect or catch the missile when you are hit by a ranged weapon attack. When you do so, the damage you take from the attack is reduced by 1d10 + your Dexterity modifier + your brigand level.

If you reduce the damage to 0, you can catch the missile if it is small enough for you to hold in one hand and you have at least one hand free. If you catch a missile in this way, you can spend 1 spite point to make a ranged attack with the weapon or piece of ammunition you just caught, as part of the same reaction. You make this attack with proficiency, regardless of your weapon proficiencies, and the missile counts as a brigand weapon for the attack, which has a normal range of 20 feet and a long range of 60 feet.

### Ability Score Improvement
When you reach 4th level, and again at 8th, 12th, 16th, and 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can’t increase an ability score above 20 using this feature.

Using the optional feats rule, you can forgo taking this feature to take a feat of your choice instead.

### Tumble
Beginning at 4th level, you can use your reaction when you fall to reduce any falling damage you take by an amount equal to five times your brigand level.

### Extra Attack
Beginning at 5th level, you can attack twice, instead of once, whenever you take the Attack action on your turn.

### Low Blow
Starting at 5th level, you know the difference between honor and victory. When you hit another creature with a melee weapon attack, you can spend 1 spite point to attempt a low blow. The target must succeed on a Constitution saving throw or be stunned until the end of your next turn.

### Undercut
Starting at 6th level, your unarmed strikes count as magical for the purpose of overcoming resistance and immunity to nonmagical attacks and damage.

```
```

### Evasion
At 7th level, your instinctive agility lets you dodge out of the way of certain area effects, such as a blue dragon’s lightning breath or a fireball spell. When you are subjected to an effect that allows you to make a Dexterity saving throw to take only half damage, you instead take no damage if you succeed on the saving throw, and only half damage if you fail.

### Snap Out of It
Starting at 7th level, you can use your action to end one effect on yourself that is causing you to be charmed or frightened.

### Piss and Vinegar
At 10th level, your sheer stubborn will makes you immune to disease and poison.

### Loud and Clear
Starting at 13th level, your insight into body language and your ability to brute force a point across lets you understand all spoken languages. Moreover, any creature that can understand a language can understand what you say.

### Tough it Out
Beginning at 14th level, grit and hardiness grants you proficiency in all saving throws.

Additionally, whenever you make a saving throw and fail, you can spend 1 spite point to reroll it and take the second result.

### Spite Death Itself
At 15th level, your spite sustains you so that you suffer none of the frailty of old age, and you can’t be aged magically; ensuring you'll be the mean old bastard you were destined to be. You can still die of old age, however. In addition, you no longer need food or water.

### Infiltrate
Beginning at 18th level, you get where you want to go. You can use your action to spend 4 spite points to become invisible for 1 minute. During that time, you also have resistance to all damage but force damage.

Additionally, you can spend 8 spite points to cast the astral projection spell, without needing material components. When you do so, you can’t take any other creatures with you.

### No Rest for the Wicked
At 20th level, you can sleep when you're dead. When you roll for initiative and have no spite points remaining, you regain 4 spite points.

> ##### Referencing Official Content
> This document is meant to be used as an alternative to the monk class in D&D 5th Edition's *Player's Handbook* and monk subclasses in the *Player's Handbook, Sword Coast Adventurer's Guide,* and *Xanathar's Guide to Everything*. Content not found in the [5th Edition SRD](https://media.wizards.com/2016/downloads/DND/SRD-OGL_V5.1.pdf) must be consulted from the aforementioned resources. In the Dirty Trades section of this document, each subclass will provide a reference to the official content that it rebrands. Look for these notes:
>
>*(See: Player's Handbook page 79, Way of the Open Hand)*
>
>*(See: Open Hand Technique)*

## Dirty Trades
A dirty trade isn't an officially recognized role, and there is no professional training. Instead, brigands come into these roles naturally as they dive further and further into less-than-respectful careers. Regardless of specialty, every brigand has a basic understanding of operation to base off of. Thus, a brigand need choose a trade only upon reaching 3rd level.

### Bruiser
*(See: Player's Handbook page 79, Way of the Open Hand)*

Bruisers are naturally tough bare-fisted brawlers capable of bullying, shoving, tripping, and all-around harassing anyone to get on their bad side. And their spite alone can make creatures second-guess an approach.

<div class='pageNumber auto'></div>

\page

#### Bully
*(See: Open Hand Technique)*

Starting when you choose this trade at 3rd level, you can harness your spite to harass an enemy. Whenever you hit a creature with one of the attacks granted by your Cheap Shot, you can impose one of the following effects on that target:

 - It must succeed on a Dexterity saving throw or be knocked prone.
 - It must make a Strength saving throw. If it fails, you can push it up to 15 feet away from you.
 - It can’t take reactions until the end of your next turn.

#### Shrug it Off
*(See: Wholeness of Body)*

At 6th level, you gain the ability to heal yourself. As an action, you can regain hit points equal to three times your brigand level. You must finish a long rest before you can use this feature again.

#### Pacify
*(See: Tranquility)*

Beginning at 11th level, you can exude your spite in an aura of menace that discourages enemies from picking a fight. At the end of a long rest, you gain the effect of a sanctuary spell that lasts until the start of your next long rest (the spell can end early as normal). The saving throw DC for the spell equals 8 + your Wisdom modifier + your proficiency bonus.

#### Snakebite
*(See: Quivering Palm)*

At 17th level, you gain the ability to slip a poisoned pin between your fingers. When you hit a creature with an unarmed strike, you can spend 3 spite points to spike the target with the pin. The poison lasts for a number of days equal to your brigand level. The poison is imperceptible until the final lethal moment, of which only you know when will occur. You can use your action to trigger the poison. To do so, you and the target must be on the same plane of existence. When you use this action, the creature must make a Constitution saving throw. If it fails, it is reduced to 0 hit points. If it succeeds, it takes 10d10 necrotic damage.

You can have only one creature under the effect of this feature at a time. You can choose to say the poison is fake and end the ability without spending an action.

### Shadower
*(See: Player's Handbook page 80, Way of Shadow)*

Shadowers are silent spies, stalkers, burglars, and assassins. Through their experience hiding in the darkness, they've internalized its nature and can manifest its aspects through their spite. A shadower worth their salt is rarely noticed. Even if they are, well, no-one will notice if there's no-one *to* notice.

#### Subterfuge
*(See: Shadow Arts)*

Starting when you choose this trade at 3rd level, you can use your spite to duplicate the effects of certain spells...

#### Split
*(See: Shadow Step)*

At 6th level, you gain the ability to step from one shadow into another...

#### Tuck Away
*(See: Cloak of Shadows)*

By 11th level, you have learned to truly blend in with the shadows...

#### Blindside
*(See: Opportunist)*

At 17th level, you can exploit a creature's momentary distraction when it is hit by an attack...


### Primordial Ravager
*(See: Player's Handbook page 80, Way of the Four Elements)*


Primordial Ravagers have a connection to the elemental planes and are capable of dredging up elemental power and bending it to their will. Be it a hired goon infused with power from a wizard's stolen magnum opus, a descendant of a noble genie, or a child born during a great elemental event, the Primordial Ravager's reckless spite is a force of nature that obeys only one. 

#### Force of Nature
*(See: Disciple of the Elements)*

When you choose this trade at 3rd level, you learn magical forces that harness the power of the four elemental planes. A force requires you to spend spite points each time you use it...

```
```

#### Elemental Forces
*(See: Elemental Disciplines)*

The elemental forces are presented in alphabetical order. If a force requires a level, you must be that level in this class to learn the force.

**Binding Wind*(6th Level Required)*.** *(See: Clench of the North Wind)*

**Cruel Combustion*(11th Level Required)*.** *(See: Flames of the Phoenix)*

**Elemental Instinct.** *(See: Elemental Attunement)*

**Flame Spit.** *(See: Sweeping Cinder Strike)*

**Inferno Barrier*(17th Level Required)*.** *(See: River of Hungry Flame)*

**Into Thin Air*(11th Level Required)*.** *(See: Mist Stance)*

**Rising Tide.** *(See: Shape the Flowing River)*

**Scorch Knuckles.** *(See: Fangs of the Fire Snake)*

**Splitting Cry*(6th Level Required)*.** *(See: Gong of the Summit)*

**Stone Scales*(17th Level Requirement)*.** *(See: Eternal Mountain Defense)*

**Stubborn Block*(17th Level Required)*.** *(See: Wave of Rolling Earth)*

**Thundercrack.** *(See: Fist of Four Thunders)*

**Undertow.** *(See: Water Whip)*

**Whistling Gale.** *(See: Rush of the Gale Spirits)*

**Windburst.** *(See: Fist of Unbroken Air)*

**Wind Walk*(11th Level Required)*.** *(See: Ride the Wind)*

**Winter's Howl*(17th Level Required)*.** *(See: Breath of Winter)*

### Graverobber
*(See: Sword Coast Adventurer's Guide page 130, Way of the Long Death)*

As the name suggests, graverobbers prefer to take their ill-gotten goods from those who are no longer present. Their continuous lonely presence among the departed grants them insight into the nature of life and death, and with their spite they can influence the line between states and take more than just buried possessions.

#### Why Wait?
*(See: Touch of Death)*

Starting when you choose this trade at 3rd level, your familiarity with death allows you to extract vitality from another creature as it nears its demise. ..

#### Sepulchral Aura
*(See: Hour of Reaping)*

At 6th level, you gain the ability to unsettle or terrify those around you as an action, for your soul has been touched by the shadow of death...

#### Borrowed Time
*(See: Mastery of Death)*

Beginning at 11th level, you use your familiarity with death to escape its grasp...

#### The Dead Don't Complain
*(See: Touch of the Long Death)*

Starting at 17th level, your touch can channel the energy of death into a creature...

### Boozehound
*(See: Xanathar's Guide to Everything page 33, Way of the Drunken Master)*

Boozehounds are drunken rabble-rousers swaying in and out of all varieties of altercations. Their penchant for taverns and taprooms makes them deceptively informed, and with their wild inebriated combat style they are dangerously unpredictable in a fight, shifting from one place to another in random and unorthodox ways.

#### Bonus Proficiencies
*(See: Bonus Proficiencies)*

When you choose this trade at 3rd level, your lifestyle of dulled inhibitions grants you extra proficiencies...

#### Barroom Brawler
*(See: Drunken Technique)*

At 3rd level, you learn how to twist and turn quickly as part of your Cheap Shot...

#### Wild Motions
*(See: Tipsy Sway)*

Starting at 6th level, you can move in sudden, swaying ways. You gain the following benefits.

**Rebound.** *(See: Leap to Your Feet)*

**Scapegoat.** *(See: Redirect Attack)*

<div class='pageNumber auto'></div>

\page

#### Compensate
*(See: Drunkard's Luck)*

Starting at 11th level, you know your body - inside and out - and how to work with it through bad conditions...

#### Numb and Swinging
*(See: Intoxicated Frenzy)*

At 17th level, you gain the ability to make an overwhelming number of attacks against a group of enemies...


### Cutthroat
*(See: Xanathar's Guide to Everything page 34, Way of the Kensei)*

When cards drop and blades are drawn, a cutthroat is the first to leap over the table with flashing steel. Powerful upfront fighters, they find a preference for a choice few weapons and become as deadly with them as they are fond for them. These brigands typically name their weapons and act as highway robbers, skilled guards, and inscrutable mercenaries. When a cutthroat fingers for their favorite axe, it's best to be on their good side.

#### Weapon of Choice
*(See: Path of the Kensei)*

When you choose this trade at 3rd level, your particular weapons experience leads you to master the use of certain weapons. This trade also includes knowledge on how to front as a respectable calligrapher or painter. You gain the following benefits.

**Favored Weapons.** *(See: Kensei Weapons)*

**Resourceful Gear.** *(See: Agile Parry)*

**Take Your Time.** *(See: Kensei's Shot)*

**Respectable Front.** *(See: Way of the Brush)*

#### This is My Hatchet This is My Bow
*(See: One with the Blade)*

At 6th level, you drive your spite and experience into strikes with favored weapons, granting you the following benefits.

**Magic Favored Weapons.** *(See: Magic Kensei Weapons)*

**Backbiter.** *(See: Deft Strike)*

#### Coat the Blade
*(See: Sharpen the Blade)*

At 11th level, you gain the ability to augment your weapons further with custom treatments...

#### Feint
*(See: Unerring Accuracy)*

At 17th level, your mastery of weapons grants you extraordinary accuracy...


### Heretic
*(See: Sword Coast Adventurer's Guide page 131 or Xanathar's Guide to Everything page 35, Way of the Sun Soul)*

In a world where the gods are very much real, there is one con to stand above them all: swindling divine power from celestial hands. Heretics have risked not just the ire of churches, but the swift judgement of the lords above for the divine power they now wield for their own gain. Heretics live a lifestyle of peculiar dichotomy: they possess radiant fire with which to strike their enemies and divine health to preserve them, but must take care not to flaunt these traits lest they catch the eye of an oath-sworn dark knight.

#### Irreverent Bolt
*(See: Radiant Sun Bolt)*

Starting when you choose this trade at 3rd level, you can hurl searing bolts of magical radiance...

#### Roiling Radiance
*(See: Searing Arc Strike)*

At 6th level, you gain the ability to channel your spite into searing waves of energy...

#### Supplanted Daylight
*(See: Searing Sunburst)*

At 11th level, you gain the ability to create an orb of light that erupts into a devastating explosion...

#### Apostate Shield 
*(See: Sun Shield)*

At 17th level, you become wreathed in a luminous, magical aura...

```
```

### Watchdog
*(See: Unearthed Arcana: Monk, [Way of Tranquility](https://media.wizards.com/2016/dnd/downloads/M_2016_UAMonk1_12_12WKWT.pdf))*

Watchdogs are the solid line of defense between their charge and those that would disrupt it. Often stoic and imposing bodyguards, prison wardens, or bouncers, a watchdog's best talent is intimidation. They do not withold all their spite for fights or shows of power, instead letting it radiate off of them in a pseudo-diplomatic display of dominance.

#### Try Me
*(See: Path of Tranquility)*

When you choose this trade at 3rd level, you can cow the violent in even the most chaotic of situations...

#### Patch-Up Job
*(See: Healing Hands)*

Whoever said "medicine is a science" never met you. You know enough healing to keep your charges alive: be it magic, medicine, alchemy, or something else. Starting at 3rd level, you have a pool of healing potential that replenishes when you take a long rest...

#### Let Sleeping Dogs Lie
*(See: Emissary of Peace)*

At 6th level, you gain the ability to discourage violent situations with your presence...
> ##### Optional Rule: Intimidation
> With approval from your DM, you can change the rules for this feature in the following way:
> - Instead of making an entreaty in good faith, you must threaten violence in reaction.
> - Replace Intimidation with Persuasion when determining whether or not a check benefits from this feature.

#### Not Your Problem
*(See: Douse the Flames of War)*

At 11th level, you gain the ability to temporarily extinguish a creature’s will to join the fight...

#### Mutually Assured Destruction
*(See: Anger of a Gentle Soul)*

At 17th level, you gain the ability to visit vengeance on someone who fells others...

### Manifest
*(See: Unearthed Arcana: Barbarian and Monk, [Way of the Astral Self](https://media.wizards.com/2019/dnd/downloads/UA-WildAstral.pdf))*

The spite of some brigands flows like a river from one thing to the next; or it flies out in bursts like a geyser. The spite of a manifest rises like a flood, spilling over dams and walls to exist where it shouldn't. The peak of their driven emotions is too much for a mortal form to contain, and so it overflows and takes shape in the world around them, manifesting as an embodiment of their intentions.

#### Spiteful Will
*(See: Arms of the Astral Self)*

When you choose this trade at 3rd level, your overwhelming spite can spill out into the world and form around your arms in a shape that represents and supports your intentions to act... While your will is manifested you gain the following benefits.

#### Spiteful Drive
*(See: Visage of the Astral Self)*

Starting at 6th level, your spite can form over your head in a shape that represents and supports your intentions to distinguish... While your drive is manifested, you gain the following benefits.

 - **No Patience for Secrets.** *(See: Wisdom of the Spirit)*
 - **Scrutiny.** *(See: Astral Sight)*
 

#### Purposeful Spite
*(See: Awakening of the Astral Self)*

Starting at 11th level, you tap into the greater power of your manifestations. While you have both your spiteful will and drive manifested, you gain the following benefits.

 - **Implacable.** *(See: Deflect Energy)*
 - **Empowered Will.** *(See: Empowered Arms)*
 - **Listen Here.** *(See: Word of the Spirit)*

<div class='pageNumber auto'></div>

\page
 
#### Spite Made Whole
*(See: Complete Astral Self)*

Starting at 17th level, your spite has reached its peak, allowing you manifest it entirely... While your spite is fully manifested, you gain the following benefits. 

 - **Armor of Spite.** *(See: Armor of the Spirit)*
 - **Unrelenting.** *(See: Astral Barrage)*
 - **Vindication.** *(See: Ki Consumption)*

### Dispenser
*(See: Unearthed Arcana 2020: Subclasses Part 1, [Way of Mercy](https://media.wizards.com/2020/dnd/downloads/UA2020-Subclasses01.pdf)

Dispensers specialize in getting the body to experience what it can't or shouldn't on its own. Whether they use medicine, illegal substances, enhancements, or any variety of unusual consumables, they can leave you far better or far worse than they found you.

> ##### Disclaimer
> Concepts of substance abuse and its impact on people's real lives are beyond my expertise and I am in no way knowledgeable of the properties of chemical substances. Please do not take this for anything more than a handwave explanation for how the following features are possible for a brigand that matches with the legally-questionable themes of the class.

#### Tools of the Trade
*(See: Implements of Mercy)*

Your profession involves the making of consumable compounds, and you know the tools for the job...

#### Pick Them Up
*(See: Hands of Healing)*

You can administer a healing compound to quickly restore someone to health...

#### Put Them Down
*(See: Hands of Harm)*

You can spray, jab, or otherwise administer a harmful compound to an enemy in combat...

#### Choking Smoke
*(See: Noxious Aura)*

You can burn a compound that releases toxic smoke you've become resistant to, obscuring you at a distance and poisoning enemies up close...

#### Detox
*(See: Healing Technique)*

You know how to bring the sickened back to their feet...

#### False Toxin
*(See: Hand of Mercy)*

You can use a special compound to put someone in a death-like state...

> ##### Credit
> u/Gamesmasher23

<div class='pageNumber auto'></div>
