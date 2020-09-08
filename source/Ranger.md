---
pageSize: A4
---

<style>

:root {
 --main-color:      #9B0719;
 --main-color-dark:   #0F6475;
 --main-color-light:   #5BB1C2;
 --main-color-lighter:  #D0E8ED;
 --main-color-lightest: #F6FDFE;

 --main-color-stripe1:  #fbfbfb;
 --main-color-stripe2:  #f5f5f5;
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

/*
.phb#p1 h1{
	font-family: "First Order";
	font-size: 300%;
	text-align: center;
	text-shadow: 0px 0px 5px black;
	color:white;
	text-transform: uppercase;
	background-image: url('https://groumy.github.io/homebrewery-sotdl/images/h1.banner-large.png');
	background-size: 100% 102.5%;
	padding-top: 0.45em;
	padding-bottom : 25px;
	padding-left : 10mm;
	padding-right : 10mm;
	margin-left : -100mm;
	margin-right : -100mm;
	margin-top : -1mm;
	-webkit-font-smoothing: antialiased;
}

.phb#p1 h2{
	font-family: "First Order";
	font-size: 150%;
	text-align: center;
	text-shadow: 0px 0px 5px black;
	color:white;
	text-transform: uppercase;
	background-image: url('https://groumy.github.io/homebrewery-sotdl/images/h1.banner-large.png');
	background-size: 100% 102.5%;
	padding-top: 0.45em;
	padding-bottom : 25px;
	padding-left : 10mm;
	padding-right : 10mm;
	margin-left : -100mm;
	margin-right : -100mm;
	margin-top : -1mm;
	-webkit-font-smoothing: antialiased;
}

.phb#p28 h1{
	font-family: "First Order";
	font-size: 200%;
	text-align: center;
	text-shadow: 0px 0px 5px black;
	color:white;
	text-transform: uppercase;
	background-image: url('https://groumy.github.io/homebrewery-sotdl/images/h1.banner-large.png');
	background-size: 100% 102.5%;
	padding-top: 0.45em;
	padding-bottom : 25px;
	padding-left : 10mm;
	padding-right : 10mm;
	margin-left : -100mm;
	margin-right : -100mm;
	margin-top : -1mm;
	-webkit-font-smoothing: antialiased;
}
*/

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
  font-size  	: 5pt;
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
  font-size  	: 8.5pt;
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
 	line-height: 1.8em !important; 	/*Line page numbers up with Multi-line h3 better*/
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

</style>

<div class='classTable wide'>

## Ranger
| Level | Proficiency Bonus | Features| Spells Known | 1st | 2nd | 3rd | 4th | 5th |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1st | +2 | Favored Enemy, Natural Explorer | — | — | — | — | — | — |
| 2nd | +2 | Fighting Style, Spellcasting| 2 | 2 | — | — | — | — |
| 3rd | +2 | Primeval Awareness, Ranger Conclave | 3 | 3 | ─ | — | — | — |
| 4th | +2 | Ability Score Improvement | 3 | 3 | ─ | — | — | — |
| 5th | +3 | Extra Attack | 4 | 4 | 2 | — | — | — |
| 6th | +3 | Greater Favored Enemy | 4 | 4 | 2 | — | — | — |
| 7th | +3 | Ranger Conclave feature | 5 | 4 | 3 | — | — | — |
| 8th | +3 | Ability Score Improvement, Fleet of Foot | 5 | 4 | 3 | — | — | — |
| 9th | +4 | ─ | 6 | 4 | 3 | 2 | — | — |
| 10th| +4 | Hide in Plain Sight | 6 | 4 | 3 | 2 | — | — |
| 11th| +4 | Ranger Conclave feature | 7 | 4 | 3 | 3 | — | — |
| 12th| +4 | Ability Score Improvement | 7 | 4 | 3 | 3 | — | — |
| 13th| +5 | ─ | 8 | 4 | 3 | 3 | 1 | — |
| 14th| +5 | Vanish | 8 | 4 | 3 | 3 | 1 | — |
| 15th| +5 | Ranger Conclave feature | 9 | 4 | 3 | 3 | 2 | — |
| 16th| +5 | Ability Score Improvement | 9 | 4 | 3 | 3 | 2 | — |
| 17th| +6 | ─ | 10| 4 | 3 | 3 | 3 | 1 |
| 18th| +6 | Feral Senses |10 | 4 | 3 | 3 | 3 | 1 |
| 19th| +6 | Ability Score Improvement | 11| 4 | 3 | 3 | 3 | 2 |
| 20th| +6 | Foe Slayer |11 | 4 | 3 | 3 | 3 | 2 |

</div>

## Class Features
As a Ranger, you gain the following class features
#### Hit Points
___
- **Hit Dice:** 1d10 per Ranger level
- **Hit Points at 1st Level:** 10 + your Constitiution Modifer
- **Hit Points at Higher Levels:** 1D10 (or 6) + your Constitution modifierr

#### Proficiencies
___
- **Armor:** Light armor, medium armor, shields
- **Weapons:** Simple weapons, martial weapons
- **Tools:** none
___
- **Saving Throws:** Strength, Dexterity
- **Skills:** Choose three from Animal Handling, Athletics, Insight, Investigation, Nature, Perception, Stealth, and Survival

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
*  (a) scale mail or (b) leather armor
*  (a) two shortswords or (b) two simple melee weapons
* (a) a dungeoneer’s pack or (b) an explorer’s pack
* A longbow and a quiver of 20 arrows

### Favored Enemy
Beginning at 1st level, you have significant experience studying, tracking, hunting, and even talking to a certain type of enemy commonly encountered in the wilds.

Choose a type of favored enemy: beasts, fey, monstrosities, or undead. Alternatively, you can choose two races of humanoids (such as gnolls and orcs) as favored enemies. You gain a +2 bonus to damage rolls with weapon attacks against creatures of the chosen type. Additionally, you have advantage on Wisdom (Survival) checks to track your favored enemies, as well as on Intelligence checks to recall information about them.

When you gain this feature, you also learn one language of your choice, typically one spoken by your favored enemy or creatures associated with it. However, you are free to pick any language you wish to learn

\page

### Natural Explorer
You are a master of navigating the natural world,and you react with swift and decisive action when attacked. This grants you the following benefits:

* You ignore nonmagical difficult terrain.
* You have advantage on initiative rolls.
* On your first turn during combat, you have advantage on attack rolls against creatures that have not yet acted.

In addition, you are skilled at navigating the wilderness. Choose one skill: Animal Handling, Athletics, History, Insight, Investigation, Medicine, Nature, Perception, Stealth, or Survival. You gain proficiency in the chosen skill if you don’t already have it, and you can add double your proficiency bonus to ability checks using that skill.

### Fighting Style
At 2nd level, you adopt a particular style of fighting as your specialty. Choose one of the following options. You can’t take a Fighting Style option more than once, even if you later get to choose again.

##### Archery
You gain a +2 bonus to attack rolls you make with ranged weapons.

##### Defense
While you are wearing armor, you gain a +1 bonus to AC.

##### Druidic Warrior
You learn two cantrips of your choice from the druid spell list. They count as ranger spells for you, and Wisdom is your spellcasting ability for them. Whenever you gain a level in this class, you can replace one of these cantrips with another cantrip from the druid spell list.

##### Dueling
When you are wielding a melee weapon in one hand and no other weapons, you gain a +2 bonus
to damage rolls with that weapon.

##### Two-Weapon Fighting
When you engage in two-weapon fighting, you can add your ability modifier to the damage of
the second attack.

### Spellcasting

By the time you reach 2nd level, you have learned to use the magical essence of nature to cast spells, much as a druid does. See chapter 10 for the general rules of spellcasting and chapter 11 for the ranger spell list.

##### Spell Slots

The Ranger table shows how many spell slots you have to cast your spells of 1st level and higher. To cast one of these spells, you must expend a slot of the spell’s level or higher. You regain all expended spell slots when you finish a long rest.

For example, if you know the 1st-level spell animal friendship and have a 1st-level and a 2nd level spell slot available, you can cast animal friendship using either slot.

```
```

##### Spells Known of 1st Level and Higher
You know two 1st-level spells of your choice from the ranger spell list. The Spells Known column of the Ranger table shows when you learn more ranger spells of your choice. Each of these spells must be of a level for which you have spell slots. For instance, when you reach 5th level in this class, you can learn one new spell of 1st or 2nd level.

Additionally, when you gain a level in this class, you can choose one of the ranger spells you know and replace it with another spell from the ranger spell list, which also must be of a level for which you have spell slots.

##### Spellcasting Ability
Wisdom is your spellcasting ability for your ranger spells, since your magic draws on your attunement to nature. You use your Wisdom whenever a spell refers to your spellcasting ability. In addition, you use your Wisdom modifier when setting the saving throw DC for a ranger spell you cast and when making an attack roll with one.

**Spell save DC** = 8 + your proficiency bonus +
your Wisdom modifier

**Spell attack modifier** = your proficiency bonus+ your Wisdom modifier

### Primeval Awareness
Beginning at 3rd level, your mastery of ranger lore allows you to establish a powerful link to beasts and to the land around you. You can attune your senses to determine if any of your favored enemies lurk nearby. By spending 1 uninterrupted minute in concentration (as if you were concentrating on a spell), you can sense whether any of your favored enemies are present within 5 miles of you. This feature reveals which of your favored enemies are present, and the creatures’ general direction, number and distance (in miles) from you. If there are multiple groups of your favored enemies within range, you learn this information for each group. Once you use this feature, you can't use it again until you finish a short or Long Rest.

### Ranger Conclave
At 3rd level, you choose to emulate the ideals and training of a ranger conclave:the Beast Master, the Deepwood Sniper, the Gloom Stalker, the Horizon Walker, the Hunter, the Monster Slayer, and the Swarmkeeper all detailed at the end of the class description. Your choice grants you features at 3rd level and again at 7th, 11th, and 15th level.

### Ability Score Improvement
When you reach 4th level, and again at 8th, 12th, 16th, and 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can’t increase an ability score above 20 using this feature.

\page

### Greater Favored Enemy
At 6th level, you are ready to hunt even deadlier game. Choose a type of greater favored enemy: aberrations, celestials, constructs, dragons, elementals, fiends, or giants. You gain all the benefits against this chosen enemy that you normally gain against your favored enemy, including an additional language. Your bonus to damage rolls against all your favored enemies increases to +4.

Additionally, you have advantage on saving throws against the spells and abilities used by a greater favored enemy.

### Fleet of Foot
Beginning at 8th level, you can use the Dash action as a bonus action on your turn.

### Hide in Plain Sight
Starting at 10th level, you can remain perfectly still for long periods of time to set up ambushes.

When you attempt to hide on your turn, you can opt to not move on that turn. If you avoid moving, creatures that attempt to detect you take a −10 penalty to their Wisdom (Perception) checks until the start of your next turn. You lose this benefit if you move, either voluntarily or because of some external effect. You are still automatically detected if any effect or action causes you to no longer be hidden.

If you are still hidden on your next turn, you can continue to remain motionless and gain this benefit until you are detected.

### Vanish
Starting at 14th level, you can use the Hide action as a bonus action on your turn. Also, you cannot be tracked by nonmagical means, unless you choose to leave a trail.

### Feral Senses
Starting at 18th level, if you are able to hear, you are aware of the location of any hidden or Invisible creature within 30 feet of you.

### Foe Slayer
At 20th level, you become an unparalleled hunter. Once on each of your turns, you can add your Wisdom modifier to the attack roll or the damage roll of an attack you make. You can choose to use this feature before or after the roll, but before any effects of the roll are applied.

\page

### Beast Master
Many rangers are more at home in the wilds than in civilization, to the point where animals
consider them kin. Rangers of the Beast Conclave develop a close bond with a beast, then further strengthen that bond through the use of magic.

#### Animal	Companion
At 3rd level, you learn to use your magic to create a powerful bond with a creature of the
natural world. With 8 hours of work and the expenditure of 50 gp worth of rare herbs and fine food, you call forth an animal from the wilderness to serve as your faithful companion.

Choose a beast that is no larger than medium and that has a challenge rating of 1/4 or lower based on the surrounding terrain and on what types of creatures would logically be present in the area. At the end of the 8 hours, your animal companion appears and gains all the benefits of your Companion’s Bond ability. You can have only one animal companion at a time.

#### Companion’s Bond
Your animal companion gains a variety of benefits while it is linked to you. The animal companion loses its Multiattack action, if it has one. The companion obeys your commands as best it can. It rolls for initiative like any other creature, but you determine its actions, decisions, attitudes, and so on. If you are incapacitated or absent, your companion acts on its own.

Your animal companion has abilities and game statistics determined in part by your level. Your companion uses your proficiency bonus rather than its own. In addition to the areas where it normally uses its proficiency bonus, an animal companion also adds your proficiency bonus to its AC, attack rolls, and damage rolls.

Your animal companion gains proficiency in two skills of your choice. It also becomes proficient with all saving throws.

For each level you gain after 3rd, your animal companion gains an additional hit die and increases its hit points accordingly.

Whenever you gain the Ability Score Improvement class feature, your companion’s abilities also improve. Your companion can increase one ability score of your choice by 2, or it can increase two ability scores of your choice by 1. As normal, your companion can’t increase an ability score above 20 using this feature unless its description specifies otherwise.

Your animal companion gains the benefits of your Favored Enemy feature, and of your Greater Favored Enemy feature when you gain that feature at 6th level. It uses the favored enemies you selected for those features.

#### Coordinated Actions
Beginning at 7th level, you and your animal companion form a more potent fighting team. When you use the Attack action on your turn, if your companion can see you or otherwise sense you, it can use its reaction to make a melee attack or move half its movement speed.

#### Beast’s Defense
At 11th level, while your companion can see you, it has advantage on all saving throws.

#### Storm of Claws and Fangs
At 15th level, your companion can use its action to make a melee attack against each creature of its choice within 5 feet of it, with a seperate attack roll for each target.
