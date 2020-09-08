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

# Artificer Subclass: Mandalorian

##### Like what you see here? [There's more!](https://homebrewery.naturalcrit.com/share/By7MYLKEO-)

____
Though more famous in a galaxy far, far away, the  Mandalorians have an ancient history in Eberron, serving as bounty hunters when high paying customers needed something more subtle than a warforged army. They are skilled warriors, and equally resourceful Artificers, relying on their intellect to prepare for battle.

#### Resol'nare : This is the Way
To retain good faith with your clan, you must adhere to the following tennets. Failing to do so will exile you, which you'd be lucky to survive.

- Never remove your armor in the presence of another.
- Speak the language, Mando'a.
- Defending oneself and family
- Raise your children as Mandalorians
- Contribute to the clan's welfare
- When called upon by the Mand'alor, rally to their cause.

#### Bountysmith

When you adopt this specialization at 3rd level, you gain proficiency with smith's tools. If you already have this proficiency, you gain proficiency with one other type of artisan's tools of your choice.

You learn the language Mando'a.

####  Mandalorian Spells

Starting at 3rd level, you always have certain spells prepared after you reach particular levels in this class, as shown in the Battle Smith Spells table. These spells count as artificer spells for you, but they don't count against the number of artificer spells you prepare.

|Artificer Level| 	Spells gained |
|--------------|--|
|3rd	|Burning Hands, Magic Missle
|5th	|branding smite, Scorching Ray
|9th	|Blinding Smite, Phandom Steed
|13th	|Locate Creature, Wall of Fire
|17th	|Hold Monster, Conjure Volley


#### Trained from Foundling

When you reach 3rd level, your combat training and your experiments with magic have paid off in two ways:

* You gain proficiency with martial weapons, all crossbows, and heavy armor.

* When you attack with a magic weapon or a weapon you Forged, you may use your Intelligence modifier, instead of Strength or Dexterity modifier, for the attack and damage rolls.

<br>

<br><br>

```
```

#### Mandalorian Steel

At Third level, You have a limited supply of Admantine, allowing you to forge one of the following. Over the course of 8 hours, you may reforge the item into another of the listed items. If that item is lost, you may pay 500 gold pieces to acquire a new one, from the Mandolorian Clan. You gain an additional item at levels 5, 9, and 15.

The Mandolorian Clan will not allow someone to possess more of such items than their level would allow, and will not deal to those who have foraken their Resol'nare Oaths.

##### Forgeable Items
| Item | Description |
|:----:|:-------------|
| Whistling Birds  | Once per long rest, you may cast Magic Missle as a Bonus Action. Additionally,  it is cast silently, without Somatic or Verbal components.  |
| Adamantine Armor | You are immune to Criticals while wearing this armor. It can be any medium or heavy armor.|
| Repeater Crossbow | You create a hand crossbow. It does not have the Loading Property, may be fired as a bonus action, and is considered magical for the purposes of overcoming resistance.  |
| Vambraces | When you cast burning hands, you may target a second, equally sized cone of effect. A creature in both cone effects takes damage only once, but has disadvantage on the save. Additionally, you gain a reusable grappling hook that can help you climb up to 50ft upwards, or that can allow you to grapple up to one creature of size Large or smaller at a range of 30ft. |
| Beskad Blade | You forge a melee weapon of your choice that specializes in sundering. It is considered magical for the purposes of overcoming resistances. Any attack with this weapon made against an inanimate object is an automatic critical hit. |


#### Extra Attack

Starting at 5th level, you can attack twice, rather than once, whenever you take the Attack action on your turn.

#### I Gotta Get Me One of Those

At 9th level, you have learned how to create an Arcane Thruster. For one minute, you gain the effects of the spell Levitate, and may carry up to one medium or smaller creature with you.

You can use this ability a number of times equal to your Intelligence modifier (minimum of once). You regain all expended uses when you finish a long rest.


#### Adamantine Perfection

At 15th level, you've learned how to perfectly forge with Adamantine. When creating an item from your list, it has a nonmagical +1 Bonus. This bonus is added to any magical bonuses that are added to it, after enchanting.

<div class='pageNumber auto'></div>

\page

# Summoner

The Summoner is a card-driven class, which in and of itself is a fairly unique thing for D&D. Cards can be drawn, played to summon monsters, discarded to gain alternate benefits, and even played face-down to activate later as trap cards.


>"I once challenged a summoner to game of cards;
><br>Had an ace-high flush and went all in.
><br>He only had a pair of dragons,
><br>but I decided to let him win." ~ Pip Fizzlebang


### Hit Dice
**Hit Dice:** 1d8 per Summoner level<br>
**Hit Points at 1st Level:** 8 + your Constitution modifier<br>
**Hit Points at Higher Levels:** 1d8 (or 5) + your Constitution modifier per Summoner level after 1st

### Proficiencies
**Armor**: Light Armor<br>
**Weapons**: simple Weapons<br>
**Tools**: none<br>
**Skills**: Choose two skills from Animal Handling, Arcana, Deception, History, Intimidation, Investigation, Nature, and Religion<br>
**Saves**: You are proficient in Charisma Saves, Constitution Saves

### Starting Equipment:
- (a) a Light Crossbow and 20 bolts or (b) any simple weapon
- (a) an Explorer's Pack or (b) a Dungeoneer's Pack
- Leather Armor, any simple weapon, and two daggers

### I'm dealing you in
At level 1, you have the ability create cards from the corpses of the fallen. To do so, you must spend 15 minutes using this ability as a ritual, which both separates the original soul from this body and creates a card from it. At the end of this process, the body disappears, and the card is added to your monster deck at random. Souls separated in this way cannot be resurrected into this body, but could be revived by spells that are powerful enough to create a new body for them.

If multiple corpses are available, you may bind them all to cards without requiring additional time. This ability does not work on undead, corpses that have begun to rot, or dismembered corpses. It does work on humanoids, however they lose all class levels. Though the creature summoned looks exactly like them, they have no memories or personality.

```
```

You are limited in how many creatures you can summon. You gain a total number of Monster Points equal to your Summoner level. Each creature summoned costs a number of points equal to its Challenge rating, rounded. Challenge Rating 0, ⅛, and ¼ creatures are free to summon, and when you spend a point to summon a Challenge Rating ½ creature, it's duration is doubled. Monster Points are replenished on a short or long rest.

All cards in your hand are placed back in the deck, at random, at the end of the encounter. All cards in play go into your graveyard. All cards in your graveyard remain there until you have a long rest. Cards can be removed from the deck during a long rest, but are permanently destroyed if you do so.


### I really played you there
At level 1, you gain the ability to play a card from your monster deck as an action. At the start of your turn, draw cards from your monster deck until you have at least 4 -- these compose your hand. On each turn, you may do the following:

**Play a Card**: As an action, you may play a card in your hand. The creature is summoned within a tile adjacent to you. The card floats in front of you while the creature summoned remains alive. It acts immediately after you in the turn order.


 At the end of your turn, the summoned creature(s) lose an amount of hitpoints equal to their constitution modifier times their total number of hit dice, or equal to their total number of hit dice if their constitution modifier is equal to or less than 0; for example, a Goblin (2d6) would lose 2 hp, while a Hill Giant (10d12+40) would lose 40.

 When it reaches 0hp, it immediately disappears, and its card goes into your graveyard. Playing a card while another is active also sends the previously active card to the graveyard.

  **Discard a card**: As an action, you may discard a card from your hand. It immediately goes into your graveyard. Your currently summoned creature is healed for an amount equal to the max hitpoints of the creature discarded, up to the summoned creature's max hp.

  **Draw another**: As a bonus action, you may draw an additional card, though your hand may not have more than 8 at a time.

  **Refund a card**: As a bonus action, you can send a card that's currently in play to the graveyard, killing the summoned creature. You are refunded half of the amount of Monster Points used to cast it.


<div class='wide' style='margin-top:-40px'>

##### If you like this Class, please check out the entirety of my Homebrew Book: <br>

## <a href="https://homebrewery.naturalcrit.com/share/By7MYLKEO-">Pip Fizzlebang's Ode to Eccentricism!</a>

</div>

<div class='pageNumber auto'></div>

\page

<div class='classTable'>

##### The Summoner
| Level | Proficiency Bonus | Highest CR<br> Summon | Features|
|:---:|:---:|:---:|:---|
| 1st | +2 |1| I'm dealing you in,<br>I really played you there|
| 2nd | +2 |2| Two of a Kind |
| 3rd | +2 |3| You activated my trap card |
| 4th | +2 |4|  Ability Score Improvement |
| 5th | +3 |5| - |
| 6th | +3 |6| Sacrificing in Spades |
| 7th | +3 |7| Three of a Kind |
| 8th | +3 |8| Ability Score Improvement |
| 9th | +4 |9| - |
| 10th | +4 |10|Card Crafting (Deduplication) |
| 11th | +4 |11| Four of a Kind|
| 12th | +4 |12| Ability Score Improvement|
| 13th | +5 |13| Summoner's Guard|
| 14th | +5 |14| Card Crafting (Reconstruction)|
| 15th | +5 |15| Suicide King|
| 16th | +5 |16| Ability Score Improvement|
| 17th | +6 |17| Wild Card|
| 18th | +6 |18|- |
| 19th | +6 |19| Ability Score Improvement|
| 20th | +6 |20| Playing a Straight / Flush |

</div>

### Two of a Kind
At level 2, When you would play a card costing half or less of your total Summoner Points, and you have a duplicate of it in your hand, you may play both in one action. When you would use a feature from this class to effect one of your summons, it applies to both. At level 7, you can play up to three at once, and at level 11, up to four.
<br><br><br><br><br><br><br>
```
```

### You activated my trap card
At level three, as an action, you may play a card face-down, and ready an action as if you were the creature on the card, using one of the below triggers. When triggered, the creature appears adjacent to the target (or within 20ft of it), and the creature may take one action. Using a card in this way costs half its usual points, or 0 if the creature was of a challenge rating of ½ or less. After it is activated, or if the trigger becomes impossible, such as the target dying, the card goes back into your deck.
- When [person] is attacked by [target].
- When [target] casts a spell affecting [person]
- When [target] moves to be adjacent to [person].
- When [target] is (or is no longer) [status effect such as prone, invisible, poisoned, etc]

### Sacrificing in spades
At the 6th level, you have gained the ability to return your cards from the grave. When you would draw a card, you may discard a card to instead draw from the graveyard. This card becomes an "undead" card, costing nothing, and the creature gains the following:
 - It becomes "Undead" type; it appears as a zombie of its former self.
 - It is under the effect of Slow, which cannot be removed but can be counteracted temporarily by a Haste effect.
 - It loses any fly speed it once had, and any special abilities it once had such as fire breath or regeneration.
 - It gains Undead Fortitude: If damage reduces the undead creature to 0 hit points, it must make a Constitution saving throw with a DC of the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

### Card Crafting (Deduplicating)
At the 10th level, you may destroy cards to acquire preferred ones. During a long rest, you may combine any number of duplicate cards of a Challenge Rating less than 1. The resulting card, when summoned, will act as if you had played both . The challenge rating of the card is increased as below:

|Initial CR|Resulting CR|
|:---|:----|
|0 |1/8|
|1/8|1/4|
|1/4|1/2|
|1/2|1|

### Summoner's Guard
At the 13th Level, your cards have the ability to offer their defensive stats to you. As a reaction to being targeted by an attack, but before the result of the attack is known, you may discard a card as a reaction. You gain that creature's Armor Class and damage resistances until the start of your next turn. The attack then resolves, and it if hits, you receive damage; not the creature on the card. The card goes into your graveyard when this effect ends.

<div class='pageNumber auto'></div>

\page

### Card Crafting (Reconstruction)
At the 14th level, when you are crafting during a long rest, you may destroy any number of cards of a CR 1/4 or higher. You gain half the Challenge Rating of each card destroyed as crafting points. You may then create a duplicate of any card you currently possess, for a total number of crafting points equal to the desired card's challenge rating. Crafting Points disappear at the end of your long rest.

<div class='pageNumber auto'></div>

 ### Suicide King
 At the 15th level, when you would discard a card, you may discard an additional card, receiving either the same benefit again or a separate one.
Additionally, as a bonus action, you may discard a card to recover Monster Points equal to the Challenge Rating of the creature you discarded, up to your usual maximum.

### Wild Card
At the 17th level, you gain one special card known as the Wild Card. You may not destroy it for any reasons, and cannot gain a second of it. When played, you may burn any number of Monster Points, and treat that card as any creature you've seen of a Challenge Rating equal to the amount of Monster Points spent.

### Playing a Straight / Flush
When you have 5 cards of the same type (excluding humanoid), or of sequential CRs (such as 1, 2, 3, 4, 5), you may play all five cards on your turn, as an action, using only half the Monster Points that would normally be required to summon each of the cards. These creatures all act immediately after your turn, and are destroyed at the end of their turn, and cannot have their duration extended.

<div class='pageNumber auto'></div>

\page

# Grung

### Background
The Grung, though adorable, are actually little bastards that like to keep slaves. They do so by poisoning their slaves regularly to keep them complacent (Seriously check out Volo's Guide to Monster's). As such, the vast majority of Grung are considered evil monsters.

Despite this, some tadpoles are hatched with a immense wanderlust. These tadpoles love exploring and are more inconvenient than evil, spending their childhood causing trouble for the tribe and pulling pranks. The Grung have a word for such troublemakers, which translates roughly to "Gnome Brained".

If the Grung fully develops into adulthood without falling into line, they are promptly kicked out of their home, and begin to explore the world as adventurers.

### Grung Traits

**Ability Score Increase**: Your Dexterity score increases by 1.<br>
**Age**: Grung quickly reach adulthood at age 1 and can live up to 100 years but rarely do so.<br>
**Alignment**: Gnome-brained Grung are impulsive, and lack the need to dominate that most Grung have. Because of this, they lean towards being chaotic neutral.<br>
**Size**: Grung are between 2 and 3 feet tall and weigh between 25 and 35 pounds. Your size is Small.<br>
**Movement Speed:** 25 ft.<br>
**Amphibious**: Grung can breathe air and water.<br>
**Darkvision**: You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can't discern color in darkness, only shades of gray.<br>
**Standing Leap**. The grung's long jump is up to 25 feet and its high jump is up to 15 feet, with or without a running start.<br>
<div class="descriptive">
  ##### Recommended Builds
**Rainforest grung** would make interesting Monks or Barbarians who want to grapple or focus on Unarmed attacks, applying that poison against multiple enemies in a round. Their Spit On The Blade works well with just about any non-spellcaster class, but particularly well with Crossbows, since crossbow users typically make fewer attacks on a round, and don't have many options for their Bonus Action.

Meanwhile, **Swamp Grung** would make a great rogue, able to hide in most places and reach an enemy up to 10ft away with their tongue, triggering sneak attack damage, or a tank, grabbing enemies and pulling them away from your more squishy allies.

Desert Grung are Wise, Stealthy, and Intelligent survivors. They would make great Druids, Clerics, and Wizards.


</div>
<br>
```
```

## Subraces
<img src="https://i.imgur.com/rffbwJJ.png" width=320px>

<font style='margin-left:110px' size=01 family="fantasy">[Art Accreditation,2 ](http://homebrewery.naturalcrit.com/share/By7MYLKEO-#Art)</font>

### Rainforest Grung

<a name="Rainforest"></a>

You hail from a Rainforest region, and the dangers there have given you natural defense mechanisms. In addition to the base Grung stats, you gain the following.
#### Nimble Treefolk
You gain +1 to your Dexterity Score, and have a climb speed of 25 ft.
#### Poisonous Skin
Any creature that grapples with the grung or otherwise comes into direct contact with the grung's skin must succeed on a Constitution saving throw or become poisoned for 1 minute. The DC for this save is 10 + your proficiency bonus. A poisoned creature no longer in direct contact with the grung can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature that succeeds on this save is immune for 1 hour.

Based on what color of Grung you are, the poison has an additional effect:

**Blue**: The poisoned creature must shout loudly or otherwise make a loud noise at the start and end of its turn.

**Green**: The poisoned creature is easily distracted, and may not target the same creature on two consecutive turns unless it is the only visible hostile creature.

**Red**: The poisoned creature is hallucinating wildly. Though you have no control over what they see, it blocks part of their vision, and all other creatures are considered lightly obscured.

#### Spit on the Blade
As a bonus action, you can spit a particularly corrosive poison onto a weapon. On the next hit made with the weapon, the creature hit must make a constitution save (DC 10+your proficiency bonus). It deals an additional 4d4 poison damage on a failed save, or half on a successful one. This ability cannot be reused until you have a short or long rest.

The damage increases to 6d4 at 6th level, 8d4 at 11th level, and 10d4 at 16th level.

<div class='pageNumber auto'></div>

\page

### Swamp Grung

<a name="Swamp"></a>

You hail from the Swamplands: Hot, humid, and wet. In addition to the base Grung stats, you gain the following.

#### Sturdy Swampfolk
You gain +1 to your Constitution Score, and have a swim speed of 25 ft. You may hold your breath for up to 10 minutes, and have advantage on saves against poison and disease.

#### Natural Camouflage
Your skin is bumpy and rocklike, giving you camouflage. While in forests, swamps, caves, or other natural settings, you may Hide while [lightly obscured](https://roll20.net/compendium/dnd5e/The%20Environment#toc_3). You appear as a stone or log, as appropriate.

If you are at least partially submerged in water, you gain advantage on Stealth Checks.

#### Toad Tongue
You gain a natural weapon-- your Tongue. When making an Unarmed Attack, you may choose to attack once with your Tongue. It has a reach of 10ft, deals 1d4 damage (or more if your Unarmed Attack damage is higher), and has the Finesse Property.

If you target an object that isn't being carried or warn, is no heavier than 10 lbs, and could fit in your mouth, you may retract your tongue and the object with it as part of the attack. You may use this appendage to make grapple attempts, pulling the enemy adjacent to you on success.
<br><br><br><br><br><br><br><br>

```
```

<img src = "https://i.imgur.com/UZmriXD.png" width=280px style="margin-top:41px">
<font style='margin-left:110px' size=01 family="fantasy">[Art Accreditation, 1 ](http://homebrewery.naturalcrit.com/share/By7MYLKEO-#Art)</font>

### Desert Grung

<a name="Desert"></a>

You hail from the Desert: Arid and cruel. In addition to the base Grung stats, you gain the following.

#### Sandy Survivors
Your people know how to survive the harshest of environments. Gain +1 to your Wisdom and Intelligence Score, and gain proficiency in Survival.

#### Natural Camouflage
Your skin has a sandy, dirty, gritty appearance, giving you camouflage. While in forests, desserts, caves, or other natural settings, you may Hide while [lightly obscured](https://roll20.net/compendium/dnd5e/The%20Environment#toc_3). You appear to be a pile of sand or dirt, as appropriate.

If you are at least partially submerged in Sand, or during a Sandstorm, you have advantage on Stealth Checks.

#### Battle Cry
You gain the Thunderclap Cantrip and ThunderWave Spell. When casting these, you inflate yourself and let out a shrieking Battle Cry.

Once per Long Rest, you may cast ThunderWave at Level 1 without using a Spell Slot. These Spells use your Wisdom Score as their Spellcasing Ability.

<div class='pageNumber auto'></div>

\page

# Tanooki <a name="Tanooki"></a>

<img src="http://i.imgur.com/ybxvxPQ.png" width=300 style="margin-left:0px">
<font style='margin-left:110px' size=01 family="fantasy">[Art Accreditation, 3C](http://homebrewery.naturalcrit.com/share/By7MYLKEO-#Art)</font>


### Background
The Tanooki are a dexterous race of thieves and fences. The legitimate businesses run by Tanooki are often stocked with items claimed from looting the dead or garbage collection, hence the common name for them-- Trash Pandas. More chaotic leaning Tanooki are bold in their endeavors. If asked about a stolen item-- they will deny having stole it, but are willing to sell you a replacement that happens to look quite like the original.
<div style='margin-top:-10px'>

#### Tanooki Traits
**Ability Score Increase**: Your Dexterity score increases by 1, and your Charisma score is increased by 2.

**Age**: Tanooki reach adulthood at age 6 and can live up to 100 years but rarely do so.

**Alignment**: Tanooki are fundamentally traders, seeking profit over morality. They'll make deals that benefit everyone as well as deals that only benefit themselves, making them neutral. Their word is good on a sale, deal, or contract… but anything else is fair game, often stealing, misleading, and undercutting before the sale is made, making them more chaotic than lawful.

**Size**: Tanooki are between 2 and 3 feet tall and weigh between 25 and 35 pounds. Your size is Small.

**Speed**: Your base walking speed is 25 feet. You have a climb speed of 25 feet
Darkvision: You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can't discern color in darkness, only shades of gray.

**Languages**: As a merchant-people, you come across many languages. You can speak, read, and write Common, Theive's Cant, and one language of your choice, excepting restricted languages normally gained through classes (Druidic).
<br><br><br>
</div>

```
```

### Thieves' luck
Your species is naturally unthreatening and hard to notice. Once per short rest, when a creature could see you, you may freeze in place, rolling a stealth check against their passive perception.

On a success, you are not hidden, but simply unnoticed for one turn--seen in the peripheral. The creature will turn and look at you at the start of their next turn-- but you may spend your turn hiding or fleeing in the meanwhile.

This ability cannot be used against someone who you have interacted with recently already (attacked, pickpocketed, spoken to, etc), as that would force them to have noticed you already.

### Merchant's Luck
You sometimes say just the right thing during the deal; it could be a lie about the quality of what's being sold, a piece of trivia, something in the merchant's past that could be used to blackmail them, or something else entirely.

When you would buy or sell an item you may make a charisma check against the shopkeeper. The price of the item is altered per the chart below. This ability cannot be used more than once on the same item against the same creature-- but you may try it on a different item or with a different shopkeeper.


|Roll|Result|
|:---:|:---|
|1-4|Price of the item goes 10% against your favor.|
|5-10|The price is unchanged.|
|11-19|The price of the item changes 10% into your favor.|
|20+|The price of the item increases by 20% into your favor.|
<br>
>Adventurous Tanooki often become warlocks-- after all, who's better equipped to strike a deal with the devil than the Tanooki merchantfolk?

<div class='wide' style='margin-top:-50px'>

##### If you like this, please check out the entirety of my Homebrew Book: <br>
## <a href="https://homebrewery.naturalcrit.com/share/By7MYLKEO-">Pip Fizzlebang's Ode to Eccentricism!</a>

</div>

<div class='pageNumber auto'></div>

\page

# Fighter (The Witcher)

##### The Witcher focuses on specialization-- not of a weapon or style, but of having a deadly knack for exposing the vulnerability in his opponent, be it humanoid or monstrous, and taking a lethal advantage. It's also a total ripoff of The Witcher, the game.

### Signs
Beginning when you choose this archetype at 3rd level, you gain access to a set of Witcher's Signs, described in the section below, which may be cast as an action. Your spellcasting ability for these is your intelligence, with your Witcher Save DC being 8 + your proficiency bonus + your intelligence modifier. Signs cannot be cast while using a shield, or without a free hand. If a two handed weapon is being held, you may let go with one hand temporarily. You can cast a number of these signs equal to your intelligence modifier, which is regained on a short or long rest.

### One for Monsters… One for people
At the 3rd level, during a long rest, you may enhance your swords with one of the below upgrades: these upgrades may not be on the same blade, and only one of each upgrade may be active at once.

 - **Silvered**: Your weapon is Silvered, and counts as a magical weapon for the purpose of overcoming magical resistance of non-humanoids. This weapon deals -1 damage to humanoids.
 - **Serrated**: Your blade is given serrations along the edge, too small to puncture the skin of monsters, but lethal on humans. When you critically hit a humanoid with this weapon, you may roll a d10. On a result of 10, you cut off one of its limbs-- either permanently falling prone with the loss of a leg or losing use of one arm, your choice. This weapon deals -1 damage to non-humanoids.

### Inhuman speed
At 7th level, your reaction speed is enhanced. When you would be the target of a melee attack, you may expend your reaction to do one of the following:

If the melee attack is a melee weapon attack done by a humanoid, you may counter his attack. Make a single unarmed attack roll. If it is higher than his attack roll, you punch him in the face, dealing unarmed damage and incapacitating him until the start of his next turn.

If the melee attack is done by a non-humanoid, you may use your reaction to dodge-roll out the way, You gain +2 AC against the attack that triggered this reaction, and may move yourself 5 feet in any direction without provoking attacks of opportunity.

<br>
<br>
```
```

### Alchemy
Starting at 10th level, you gain access to witcher's potions. Non-witchers drinking these potions receive 4d6 poison damage. On a long rest, you may make up to two potions, having no more than 2 available at once. You may not create two of the same potion in a short rest. These small vials may be drank as a bonus action. These effects last for a number of turns equal to your intelligence modifier, unless otherwise stated.

- **Cat Potion**: You gain 120ft of Darkvision, and can see through magical darkness. Duration 1 hour.
- **Petri's Philter**: Your sign power is increased. All targets of your signs have disadvantage on saving throws against your signs, and deal additional damage equal to your intelligence modifier, if they originally dealt damage.
- **Swallow**: At the end of your turn, so long as you have at least 1 hit point, you heal for an amount equal to your intelligence modifier. .
- **Thunderbolt**: Add your intelligence modifier to melee attack damage.
- **Wolf**: You gain may add your intelligence modifier to all melee attacks, and melee attacks crit on a 19.

### Know your enemy
At the 15th level, you may try to gain knowledge about a humanoid or monster you can see and study. As an bonus action, make an investigation check of DC 10 + the challenge rating of the monster or humanoid. You may attempt to learn something in particular (is it wounded? Poisoned? How heavily armored is it? Is it very nimble?) so long as it is something that can be observed or deduced-- for example, you might notice a flicker of flame in the mouth of a dragon, warning you that it not only has a breath attack, but that it is currently useable, but there is no physical trait that would allow you to know that dragon is capable of casting spells.

### I've killed your kind before
At 18th level, you may collect a trophy from the body of a defeated non-humanoid, usually it's head but can be any recognizable part of the monster's body. As an action, you may lift this trophy in the air, and all non-humanoids of that species that can see you must make a Wisdom save or become frightened of you for a number of turns equal to your intelligence modifier, with an additional save each time you receive damage (as the creatures are emboldened by your destruction). If the creature that damaged you is also frightened of you, it gets advantage on that save. A creature that succeeds on the initial save or subsequent ones may not be affected by this ability again for 24 hours.

To obtain a trophy, you must spend 5 minutes dismembering the body of a non-humanoid.

<div class='wide' style='margin-top:-40px'>

##### If you like this Class, please check out the entirety of my Homebrew Book: <br>
## <a href="https://homebrewery.naturalcrit.com/share/By7MYLKEO-">Pip Fizzlebang's Ode to Eccentricism!</a>

</div>

<div class='pageNumber auto'></div>

\page

## Signs


#### Aard
*Witcher Cantrip*
___
- **Range:** 15ft Cone
- **Duration:** Instant

You create a burst of force in front of you; Each creature in the 15ft cone must make a Strength saving throw. On a failed save, the creature creature is knocked prone, and cannot take reactions until the start of their turn.

#### Igni
*Witcher Cantrip*
___
- **Range:** 10ft Cone
- **Duration:** Instant

You create a burst of fire in front of you; Each creature in the 10ft cone must make a Dexterity saving throw. On a failed save, the creature takes 1d6 fire damage. Additionally, you can ignite a flammable object or extinguish a flame, each smaller than 5 cubic feet.
At Higher Levels: The spell’s damage increases by 1d6 when you reach 5th level (2d6), 11th level (3d6), and 17th level (4d6).
#### Quen
*Witcher Cantrip*
___
- **Range:** Self
- **Duration:** Concentration up to 1 minute

You create a shield around yourself, gaining +2 to your armor class and +1 to Dexterity Saves. If you make a concentration check due to taking damage that did not require an attack roll or dexterity save, you do so with disadvantage.


#### Yrden
*Witcher Cantrip*
___
- **Range:** 10ft radius of Self
- **Duration:** Concentration up to 1 minute

You create a circle of magic runes around yourself, extending 10 ft in any direction. While in this circle, creatures who are not you have their movement speed halved, can't take reactions, and have disadvantage against Dexterity Saves. Creatures inside this trap may not use ethereal movement or travel to the ethereal plane.



#### Axii
*Witcher Cantrip*
___
- **Range:** 30ft
- **Duration:** Duration: 1 minute.

You attempt to influence the mind of a creature. The target must make a Wisdom saving throw or be charmed by you for the duration. If it has been attacked by your or your allies, it makes this save with advantage. It gets an additional save each time it takes damage, with the effects ending on a success.

<br>
```
```

## Witcher Feats
#### Long Burn (Igni Enhancement):
When a creature is damaged by your Igni Sign, it is caught aflame. At the start of its turn, it must make a Constitution saving throw, with the fire being extinguished on a success; The creature may also use its action to put the flames out. If the creature is still aflame at the end of it's turn, it takes fire damage as if you had hit it with another blast of Igni.
While ignited in this way, creatures shed 20ft of bright light, and 20ft of dim light, and their armor class is reduced by 2.

#### Magic Trap (Yrden Enhancement):
When a creature is inside your Yrden, it can now only make a single attack as part of its attack action, and have their armor class reduced by 2. Additionally, creatures who enter or begin their turn in the circle take psychic damage equal to your intelligence modifier.

#### Far Reaching, and Followed Through (Aard Enhancement):
The range of your Aard is extended to 20ft. Additionally, when you use your action to knock down opponents with Aard, you may also use your bonus action to make a single melee attack. If you attack a creature that was knocked prone by your Aard, it is considered a critical hit if it hits.

#### Friendship is Magic (Axii Enhancement):
Those charmed by your Axii sign will, for the duration, consider you as a friend, defending you for the duration. You may not issue it commands, but it will automatically do what it can to protect you, including attacking potential threats. If it attacks a creature it considers to be an ally, it gets an additional save at the end of it's turn. If it kills a creature it is allied with, it takes psychic damage equal to your intelligence modifier and the charm immediately ends.

#### Witcher's Protection<br>(Quen Enhancement):
While your Quen shield is active, you gain temporary HP equal to twice your intelligence modifier. Additionally, when your quen is dismissed by any means, all creatures within 5 ft of you must make a strength save or be knocked prone, taking force damage equal to your intelligence modifier.

<div class='pageNumber auto'></div>

\page

# Monk (Way of the Monkey King)

##### Trips you, laughs, embarasses you to death. Monks of the Way of the Monkey King are the ultimate masters of the quarterstaff, trickery, and mockery. They learn techniques to embarrass their opponents, manipulate ki to ensue confusion, and have an unusual talent of extending their staff to extraordinary lengths.

### Monkey King Disciple
Starting when you choose this tradition at 3rd level, you can block your enemy’s ki with your attacks. Whenever you wield a quarterstaff, you gain the following effects.
- Enemies hit by your staff must succeed on a Dexterity saving throw or be knocked prone. If a creature succeeds on this saving throw, it is immune to this ability until the end of your turn, though it can still be knocked prone by a trip attack or another ability that applies the prone condition.
- Your reach with the staff is increased to 10ft. You may spend ki points to extend its reach by 5ft per point spent. It's damage is unaffected by this growth, and you wield it normally despite its size. It retains this length until the start of your next turn.
- If an enemy spends half of its movement to stand up within your reach, you may use your reaction to make an attack of opportunity against that creature.

### Me? Not me!
At 6th level, you gain the ability to swap locations with another. As an bonus action, you can expend a ki point to attempt to switch locations with a creature within 30ft of you that you can see. If the creature is unwilling, it must make a wisdom save to avoid this effect. On a fail, you are placed where the target was, and it is placed where you were. If there is not enough space to accommodate either, the swap fails.
  When you would be hit by a ranged attack or ranged spell attack roll, you may expend a ki point to use this ability to swap locations with a hostile creature, including the creature firing the attack. If it fails the save, you switch locations, and the creature becomes the target of the attack.

### Monkey Mockery
Beginning at 11th level, when a creature that you can see within 30ft of you is knocked prone, you may expend a ki point to laugh at them viciously. They must make a wisdom saving throw. On a fail, they receive 1d4 psychic damage plus 1d4 per creature that they can see within 30ft of them, and have disadvantage on their next attack roll. On success, they take half. This ability cannot be used again until you've had a short rest. This does not affect creatures incapable of shame, such as Undead.

<br>


```
```

### Me? And me!
At 17th level, you gain the ability to create a clone of yourself from a single golden hair of yours. As a bonus action, expend a ki point. Within 5ft of yourself, a clone appears. It has the same stats as you currently do, and looks exactly like you, though it may be damaged or changed independently of you after it is created. It acts on your turn. It carries and can use a copy of all of your equipment. If this equipment is removed from the clone, it immediately vanishes. If the clone is reduced to 0hp, or after one minute, it vanishes along with its equipment, returning to being a single, floating golden hair.


While alive, you can perfectly control the clone as if it was you, using your action as it's action, and your bonus action as it's bonus action. When you attack, you may alternate between attacking as yourself or your clone. Though your action is shared between you and your clone, it has its own movement, reaction, and bonus action.

<br><br><br><br><br><br><br><br><br><br><br>
<br>

##### If you like this Class, please check out the entirety of my Homebrew Book: <br>
## <a href="https://homebrewery.naturalcrit.com/share/By7MYLKEO-">Pip Fizzlebang's Ode to Eccentricism!</a>

<div class='pageNumber auto'></div>

\page

<a name="PlagueDoctor"></a>

# Plague Doctor

<img src="https://i.imgur.com/qoC8LOM.png" style="width:80%"/>
<font style='margin-left:90px' size=01 family="fantasy">[Art Accreditation, 4a ](http://homebrewery.naturalcrit.com/share/By7MYLKEO-#Art)</font>


<div class='descriptive'> "I fought beside a doctor, <br>
Who better knew disease.<br>
When we needed rid of creatures,<br>
He'd cure our ail with ease." ~ *Pip Fizzlebang*</div>

### Description
Plague Doctors are spellcaster specialists who can buff and debuff at distance, stealthily infecting their allies and victims. Once infected, the Plague Doctor is known for being able to cast spells through the disease itself, allowing him to even cast touch spells at range.

### Hit Points
**Hit Dice**: 1d6 per Plague Doctor level
**Hit Points at 1st Level**: 6+ Constitution modifier
**Hit Points at Higher Levels**: 1d6 (or 4) + Constitution modifier per Plague Doctor level after 1st

<br><br><br><br><br><br><br><br><br><br>

### Starting Proficiencies
You are proficient with the following items, in addition to any proficiencies provided by your race or background.
**Armor**: Light Armor - Weapons: Simple Weapons
**Skills**: Choose two from History, Investigation, Persuasion, Deception, and Religion. You gain Medicine automatically.
**Saves**: Constitution, Intelligence
**Starting Equipment**: You start with the following items, plus anything provided by your background.
• (a) Any simple melee weapon
• (a) Leather Armor
• (a) a Light Crossbow and 20 bolts or (b) any simple weapon
• (a) a Scholar's Pack or (b) an Dungeoneer's Pack
Alternatively, you may start with 5d4 x 10 gp to buy your own Equipment.

### Spellcasting
**MD, Arcana**: Your arcane medical research has given you facility with Spells.

**Cantrips:** You know three Cantrips of your choice from the Plague Doctor spell list, and learn additional Plague Doctor Cantrips of your choice at higher levels, as shown in the above table.

**Spell Slots:** The Plague Doctor table shows how many Spell Slots you have. To cast one of your Plague Doctor Spells of 1st level or higher, you must expend a spell slot or equal or higher level. You regain all expended Spell Slots when you finish a Long Rest.


**Spells Known of 1st Level and Higher**: At 1st level, you know three 1st-level Spells of your choice from the Plague Doctor spell list. You learn a new Plague Doctor spell every time you gain a level. A spell you choose must be of a level you have Slots for.
Additionally, when you gain a level in this class, you can choose one of the Plague Doctor Spells you know and replace it with another spell from the Plague Doctor spell list, which also must be of a level for which you have Spell Slots.

**Spellcasting Ability**:
Intelligence is your spellcasting ability for your Plague Doctor Spells, so you use your Intelligence whenever a spell refers to your spellcasting ability. In addition, you use your Intelligence modifier when setting the saving throw DC for a Plague Doctor spell you cast and when Making an Attack roll with one.

**Spell save DC**: 8 + Proficiency bonus + Intelligence modifier

**Spell Attack modifier**: Proficiency bonus + Intelligence modifier

**Spellcasting Focus**: You can use an arcane focus as a spellcasting focus for your Plague Doctor Spells.

<br>
<div class='wide' style='margin-top:-50px'>

##### If you like this Class, please check out the entirety of my Homebrew Book: <br>

## <a href="https://homebrewery.naturalcrit.com/share/By7MYLKEO-">Pip Fizzlebang's Ode to Eccentricism!</a>

</div>

<div class='pageNumber auto'></div>

\page

<div class='classTable wide'>

##### The Plague Doctor
| Level | Proficiency Bonus | Features | Cantrips Known | Symptoms Known | 1st | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1st | +2 | Spellcasting, Infect the masses, Mutate| 3 | - | 2 | — | — | — | — | — | — | — | —
| 2nd | +2 | Symptomatic | 3 | 2 | 3 | — | — | — | — | — | — | — | — |
| 3rd | +2 | - | 3 | 2 | 4| 2 | — | — | — | — | — | — | — |
| 4th | +2 | Ability Score Improvement | 3 | 2 | 4 | 3 | — | — | — | — | — | — | — |
| 5th | +3 | Arcane Spread, Cleansing Ritual | 3| 3 | 4 |3 | 2 | — | — | — | — | — | — |
| 6th | +3 | Bring out your Dead. | 4 | 3 | 4 |  3| 3 | — | — | — | — | — | — |
| 7th | +3 | - | 4| 3 | 4 | 3 | 3 | 1 | — | — | — | — | — |
| 8th | +3 | Ability Score Improvement | 4 | 4 | 4 | 3 | 3 | 2 | — | — | — | — | — |
| 9th | +4 | - | 4| 4 | 4 | 3 | 3 | 3 | 1 | — | — | — | — |
| 10th | +4 | Poisonous Decay | 4 | 4 | 4 | 3 | 3 | 3 | 2 | — | — | — | — |
| 11th | +4 | Prepared Plague | 5 | 5 | 4 | 3 | 3 | 3 | 2 | 1 | — | — | — |
| 12th | +4 | Ability Score Improvement | 5 | 5 | 4 | 3 | 3 | 3 | 2 | 1 | — | — | — |
| 13th | +5 | - | 5 | 5 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | — | — |
| 14th | +5 | Parasitic Poison | 5 | 6 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | — | — |
| 15th | +5 |  -| 5 | 6 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | — |
| 16th | +5 | Ability Score Improvement | 5| 6 |  4 | 3 | 3 | 3 | 2 | 1 | 1 |1 | — |
| 17th | +6 | - | 5| 7 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | 1 |
| 18th | +6 | Corrosive Plague|5 | 7 | 4 | 3 | 3 | 3 | 3 | 1 | 1 | 1 | 1 |
| 19th | +6 | Ability Score Improvement|5 | 7| 4|3|3|3|3|2|1|1|1|
| 20th | +6 |Master of Misery | 5 | 7| 4 | 3 | 3 | 3 | 3 | 2 | 2 | 1 | 1 |

</div>

<div class='descriptive'>
##### Infected and Afflicted Conditions
This is a condition unique to the Plague Doctor. There are two types of Infected, as below. If an Infected damages a creature with an unarmed attack dealing non-bludgeoning damage, such as a bite or claws, the damaged creature must mase a save or become Afflicted with the same symptoms (if any). This plague is non-magical, though your abilities may magically alter it.
Infected: Anyone who is carrying the disease, whether they are symptomatic or not.
Afflicted: The Infected's Plague has manifested symptoms, based on the type of infection(s), and remains Afflicted until it succeeds the corresponding Save or the disease is removed.
</div>

### Infect the masses
At level 1, You know the following cantrips: **Gas Grenade**, **Needle Shot**, and **Contamination**. They count as Plague Doctor spells for you, though do not count against your cantrips known. See [Spells](#PlagueDoctorSpells) for details.

```
```

### Mutate:
At level 1, when you cast a spell, you may target any Infected, regardless of whether or not you can see them, and channel the spell's effects through that infected; so long as they are within 60ft of you, they are considered adjacent to you (and thus susceptible to touch attacks), and your spells can be channeled through them, or targeting them. If the spell allows a save or requires an attack roll, it becomes a Constitution Save instead.

If the spell is an Area of Effect, such as a 15ft cone, you cast it from the location of any one of your Infected, either centered on them (as with a spell with a Radius) or extending from them (as a cone or line, which also affects the Infected you are casting from as it erupts from their body).  You may also have it only affect the Infected in that area, but not selectively choose which of the Infected (if, for example, a party member has become Infected, you may not exclude them).
\page

### Symptomatic <a name="PlagueDoctorSpells"></a><div class='pageNumber auto'></div>
At level 2, you may add Symptoms to an Infected (see [Symptoms](#Symptoms) below). As an action, you may expend a spell slot to add a symptom to Infected creatures (one creature per spell level of the slot expended). They are Afflicted, and continue to exhibit this symptom as long as they remain Afflicted. You begin knowing how to inflict two Symptoms, and may choose more at higher levels as per the Plague Doctor Chart. At each level, you may replace one known Symptom.

### Arcane spread
At level 5, when you would damage one or more Infected with a spell that deals poison damage, you may spread your disease as a bonus action. All adjacent creatures to those damaged Infected take 1d4 poison damage for each adjacent Infected, and must make a Constitution Save or become an Infected as well, with the same Symptoms (if any).

Additionally, if two or more creatures are affected by a single spell and at least one is Infected, the other must make a Constitution Save or become Infected as well, with the same Symptoms (if any). This spreading effect cannot be suppressed, and may trigger on spells cast by anyone (not just yourself or other plague doctors). This may also transfer symptoms between two Infected.

### Cleansing Ritual
At level 5, you have gain the ability to recall your disease from Infected. As a bonus action, choose a number of Infected within 60 ft of you. The disease is removed from each of the chosen Infected, you regain some spell slots based on the number of Afflicted cleansed. The Spell Slots have a combined level that is equal to or less than the number of Afflicted that were cleansed, and none of the slots can be 6th level or higher.

For example, if 2 Afflicted were cleansed, you can recover up to 2 levels worth of Spell Slots. You can recover either one 2nd-level spell slot or 2 1st-level Spell Slots. **This cannot put you above your total number of spell slots for a given level, as listed on the Plague Doctor chart.**

### Bring Out Your Dead
At level 6, your studies have taught you how to make the immune your carriers: An undead cannot become Afflicted, but may now be Infected with your Plague.

Corpses can also be Infected with your Plague, which will spread the Plague to anyone who touches the corpse and fails a saving throw. While Infected, the corpse quickly begins oozing a viscous goo, becoming nothing but bone and goo in 6 hours. This goo is wildly contagious, and can be applied to a weapon to spread your plague. For one hour after application, all damage done with that weapon requires a Constitution Save to avoid becoming Infected.

<br><br><br><br>

```
```

### Poisonous Decay
At level 10, when you would deal poison damage from a Plague Doctor spell, you may choose to instead deal necrotic damage. When you deal necrotic or poison damage, you deal additional damage equal to your Intelligence modifier.

### Prepared Plague
At level 11, your mastery of disease allows you to add Symptoms outside of the body of an Infected. When you use Infect the Masses but before any save results are known, you may choose to expend a spell slot of appropriate level to add a Symptom to each creature affected. Any creature that becomes infected by this use of this ability will become immediately Afflicted with that Symptom.

### Parasitic Poison
At level 14, you gain the ability to place microscopic parasites within an Infected, which begin to excrete a Poison.
The toxin must be one you've been subject to previously, as part of a creature's natural attacks, though you may harvest and inject the poison into yourself at a safer time. To use the effect, you must expend a spell slot of a level equal to at least half the CR of the creature who's poison you're replicating. The Constitution save for this poison becomes equal to your Plague Doctor DC. To harvest a poison for injection requires a Medicine Check of 8+CR of the monster being extracted from.

### Corrosive Plague
When you reach level 18, your Symptomatic Plagues become so violent that they begin to eat at the flesh before entering the body, dealing poison damage during the infection process. When you use Prepared Plague, your Gas Grenade, Needle Shot, and Contamination are altered as follows:
- Gas Grenade: Every time a creature begins its turn in the infectious gas or enters it for the first time on their turn, they take damage equal to the level of the spell slot expended.
- Needle Shot: Each creature hit by one or more needles takes poison damage equal to the level spell slot expended.
- Contamination: You may use this ability again to add more Symptoms to the contaminated food, using subsequent casts of Prepared Plague. A creature eating or drinking this food immediately takes poison damage equal to the combined spell slot levels used to create the Symptoms in it, times your Intelligence Modifier. For example: Using a level 1 spell slot with an Int of 20 would do 5 damage, while a level 9 spell slot would do 40.

### Master of Misery:
When you reach 20th level, you gain mastery over two Symptoms and can use them with little effort. Choose two Symptoms. When you would use a spell slot to Infect a creature with one, you may choose to also infect it with the other. When you do so, you can't do so again until you finish a short or Long Rest.

<div class='pageNumber auto'></div>

\page

<a name="Symptoms"></a>

# Symptoms
## Bacterial
While Infected with at least one Bacterial Symptom, the Afflicted is also considered Poisoned. At the end of each turn, the infected gets a constitution save to become Infected without Symptoms, as his body tries to suppress the disease.
- **Near Sighted**: the Infected is Blinded against all creatures who are further than 5ft away.
- **Hearing Loss**: The Infected is Deafened.
- **Lockjaw**: The Infected cannot speak or use abilities that require a vocal component.
- **Crippled**: The Infected's legs become weak. its movement speed is halved. If it fails to succeed on a constitution save to suppress the Symptom, it falls prone.
- **Rockjoint**: The Infected's joints become painfully inflamed. If the creature moves, it may only make one attack as part of its attack or multiattack action. It may not take bonus actions.

## Viral
While Afflicted with at least one of the below symptoms, the creature retains a fever, and cannot gain restful sleep. Every 24 hours, it gains one stack of Exhaustion per active Symptom, which cannot be removed through Long Rests. At the beginning of each short or long rest, the Afflicted gets a constitution save to become Infected without Symptoms. All exhaustion is removed after a long rest, once the Infected is no longer Afflicted.
- **Boost Metabolism**: Once per turn, the Infected may use a bonus action to expend one hit dice, and heal for the amount rolled as if it were done during a short rest. No additional benefits of a short rest are applied, and only one dice may be spent in this way per turn.
- **Stabilizing Retrovirus**: Gain advantage on death saving throws.
- **Bioluminescent lenses**: Your eyes begin to shimmer slightly, giving a faint glow. You gain darkvision up to 60ft in addition to any you already had, and light sensitivity.
- **Magic Sense**: You gain a supernatural sense to detect the Aura of magic. It acts as the Detect Magic spell, but lasts as long as you are Afflicted, has a radius of 10ft, and cannot detect the School of Magic. While this effect is active, you are distracted by the presence of magic, and so long as a magical affect is within 10ft of you, you have disadvantage on perception and investigation checks.

```
```

## Fungal
While Infected with at least one Fungal Symptom, any creature that ends their turn within 5ft of the Afflicted must make a Constitution Save or become Afflicted with the same Symptoms. Creatures infected with Fungal Plagues get an additional save to end the effect at the end of each turn.
- **Itchy and Irritable**: The infected becomes quick to anger, and has disadvantage on all Charisma checks and saves.
- **Paranoia**: The Infected becomes Frightened of a randomly selected creature it can see. If the Infected cannot see this creature on the start of its turn, a new creature it can see is selected at the end of its turn. If the Afflicted can't see any creatures on its turn, it cannot move and readies an attack against the first creature it sees.
- **Suggestibility**: The infected becomes more easily suggestible. It gains disadvantage on Wisdom saving throws and insight checks.
- **Hallucinogenic**: The infected becomes Confused, as per the Confusion spell.


\page

<a name="PlagueDoctorSpells"></a>

# Plague Doctor Spells & Lists
#### **Gas Grenade**
*Cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30ft
- **Target:** 10ft Radius
- **Duration:** Instant
- You create and throw a thin glass ball with an aerosol version of your plague. All creatures who breathe air and are not immune to the poisoned condition within the radius of effect must make a Constitution save or become Infected without Symptoms.
-  **At Higher Levels:** The cloud lingers, causing creatures that enter or begin their turn in the cloud to take a Constitution Save or become Infected. Each turn, the radius of the cloud expands by 5ft: Level 5 (1 Round), Level 10 (2 Rounds), Level 15 (3 Rounds), Level 20 (4 Rounds).

#### **Needle Shot**
*Cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60ft
- **Target:** Creature
- **Duration:** Instant
- You create and shoot a magically guided needle into the body of a creature you can see within range. If the creature is not immune to poison and is not undead, it must make a Constitution save or become Infected without Symptoms. The creature does not feel this, but may discover the needle upon self inspection.
- **At Higher Levels:** You may summon additional needles at higher character levels: 2 needles at level 5, 3 at 10, 4 at 15, and 5 at 20. If two or more needles hit the same target, it makes the initial save to avoid infection with disadvantage.

#### **Contamination**
*Cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30ft
- **Target:** All food or drink in 5ft radius
- **Duration:** Instant
- Select a point within range; all food, drink, and water within 5ft of that point is contaminated with your Plague for an hour. Any creature not immune to poison that eats or drinks this food must, the next time they take a long rest, make a Constitution save or be Infected1 without Symptoms. If a large quantity of food or drink was consumed, they make this save with disadvantage.

```
```

### Spell Lists
#### Cantrips
- Acid Splash
- Mage Hand
- Poison Spray
- Shocking Grasp
- Frostbite
- Mending
- Resistance
- Spare the Dying

#### Level 1
- Bane
- Burning Hands
- Dissonant Whispers
- Detect Poison and Disease
- Mage Armor
- Shield
- Purify Food And Drink
- Bless
- Charm Person
- Cure Wounds
- Inflict Wounds
- Tasha's Hideous Laughter
- Sleep
- Absorb Elements

#### Level 2
- Ray of Enfeeblement
- Enhance Ability
- Protection from Poison
- Blur
- Detect Thoughts
- Darkvision
- Enlarge/Reduce
- Lesser Restoration
- Scorching Ray
- Blindness / Deafness
- Calm Emotions
- Hold Person
- Ray of Enfeeblement
- Melf's Acid Arrow

#### Level 3
- Bestow Curse
- Feign Death
- Gaseous Form
- Revivify
- Tongues
- Fear
- Fireball
- Lightning Bolt
- Stinking Cloud
- Vampiric Touch
- Slow
- Speak with Dead
- Hypnotic Pattern

<div class='pageNumber auto'></div>

\page

#### Level 4
- Blight
- Confusion
- Vitriolic Sphere
- Death Ward
- Locate Creature
- Fabricate
- Compulsion
- Hallucinatory Terrain
- Dominate Beast
- Phantasmal Killer
- Elemental Bane (Can also choose Poison)
- Arcane Eye

#### Level 5
- Contagion
- Cloudkill
- Creation
- Hold Monster
- Insect Plague
- Modify Memory
- Scrying
- Greater Restoration
- Cone of Cold
- Dominate Person
- Immolation
- Mass Cure Wounds

#### Level 6
- Chain Lightning
- Contingency
- Harm
- Magic Jar
- Otto's Irresistable Dance
- Primordial Ward
- True Seeing
- Circle of Death
- Eyebite
- Heal
- Mass Suggestion
- Disintegrate
```
```
#### Level 7
- Divine Word
- Regenerate
- Prismatic Spray
- Whirlwind
- Mirage Arcane
- Finger of Death
- Resurrection
- Teleport
- Etherealness
- Delayed Blast Fireball

#### Level 8
- Abi-Dalzim's Horrid Wilting
- Antipathy/Sympathy
- Clone
- Dominate Monster
- Feeblemind
- Telepathy
- Antimagic Field
- Incendiary Cloud

#### Level 9
- Power Word Heal
- Power Word Kill
- True Resurrection
- Weird
- Imprisonment
- Foresight

<div class='pageNumber auto'></div>

\page