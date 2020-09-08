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

# Slay the Spire Homebrew Part 1: Curses
The first step in an attempt to create the setting of Slay the Spire in D&D.
This introduces the game's curses.

*Homebrew content by Xenexex.
Inspired by the game from Mega Crit Games.
Document made with The Homebrewery.*

### Changes to *remove curse*
Warped by the Spire's blight, *remove curse* is no longer as effective. Whenever *remove curse* is cast on a creature, it can only dispel one curse at a time, which is chosen when cast. In addition, whenever someone uses a spell slot to cast *remove curse*, they cannot cast the spell again until they finish a long rest.

### Special Curses
You can only have one of each special curse at a time, and they can only be gained by specific conditions.

#### Necronomicurse
Gained when attuning to the Necronomicon.
You lose proficiency in all skills, saving throws, and weapons other than two-handed weapons. This curse can't be removed as long as you are attuned with the Necronomicon.

#### Ascender's Bane
After you gain a normal curse, roll a d20. If the result is equal to or lower than the number of curses you currently have, gain Ascender's Bane.
The malice of the Spire prevents *remove curse* from having much effect on you. Whenever *remove curse* is cast on you, roll a d6. On a result of 5 or 6, Ascender's Bane is targeted, and thus removed, by the spell. Otherwise, the spell has no effect.

<div style='margin-top:0px'></div>

<img
  src='https://maybelatergames.co.uk/img/ascendersBane.9557f912.png'
  style='width:300px' />

Art by Anailis Dorta

#### Mark of the Bloom
A rare and powerful curse, gained as payment for a pact with a god. This curse cannot be removed by anything short of a casting of *wish*. A person afflicted with this curse cannot gain hit points as a result of spells or other magical effects.

### Normal Curses
These curses can be acquired from relics and various events throughout the Spire. Whenever you gain one of these curses, you have a chance of gaining Ascender's Bane.
<table>
	<tr>
		<th>1d10</th>
        <th>Name</th>
		<th>Description</th>
    </tr>
    <tr>
		<td>1</td>
		<td>Curse of Clumsiness</td>
		<td>You gain a -1 penalty to attack rolls. For every extra of this curse you have, the penalty increases by -1.</td>
    </tr>
	<tr>
		<td>2</td>
		<td>Curse of Decay</td>
        <td>Whenever you finish a long rest, make a DC 10 constitution save. On a failed save, reduce your constitution score by 1. If it is reduced to 0, you die. If this curse is removed, your constitution score returns to normal. For every extra of this curse you have, the DC increases by 5.</td>
	</tr>
	<tr>
    	<td>3</td>
		<td>Curse of Doubt</td>
		<td>At the start of your turn, make a DC 10 wisdom save. On a failed save, you have disadvantage on all attacks until the start of your next turn. For every extra of this curse you have, the DC increases by 5.</td>
    </tr>
    <tr>
		<td>4</td>
		<td>Curse of Injury</td>
		<td>You gain the effect of a lingering injury (DMG 272). When this curse is removed, the injury goes away.</td>
	</tr>
    <tr>
        <td>5</td>
		<td>Curse of Normality</td>
        <td>You can no longer take reactions. If you have 3 or more of this curse, you can no longer take bonus actions, but you may use an action to do so.</td>
    </tr>
    <tr>
		<td>6</td>
		<td>Curse of Pain</td>
		<td>Whenever you use an action to attack or cast a spell, make a DC 10 constitution save. On a failed save, take 1d6 force damage. For every extra of this curse you have, the damage increases by 1d6.</td>
    </tr>
    <tr>
    	<td>7</td>
		<td>Curse of the Parasite</td>
		<td>You have a -2 penalty to saving throws. If this curse is removed, gain a lingering injury (DMG 272) as the magical parasite is extracted. For every extra of this curse you have, the penalty increases by -2.</td>
    </tr>
    <tr>
    	<td>8</td>
		<td>Curse of Regret</td>
		<td>At the end of each of your turns in combat, take 1 psychic damage for each of these conditions:
        	<ul>
				<li>You did not use your action this turn</li>
				<li>You did not use your bonus action this turn</li>
				<li>You have remaining movement this turn</li>
				<li>You failed to use your reaction as part of a readied action from the previous turn</li>
            </ul>
			For every extra of this curse you have, the damage increases by 1 per met condition.
        </td>

    </tr>
    <tr>
		<td>9</td>
		<td>Curse of Writhing</td>
		<td>You gain a -5 penalty to initiative. For every extra of this curse you have, the penalty increases by -5.</td>
    </tr>
    <tr>
    	<td>10</td>
		<td>Two Curses!</td>
		<td>Roll twice on this table, rerolling any results of 10.</td>
	</tr>
</table>


> Credit: [u/Xenexex](https://www.reddit.com/user/Xenexex/)

<div class="pageNumber auto"></div>
<div class='footnote'>Curses version 0.3</div>

\page

# Magic Items
The magic items in this section are based on relics and potions found in Slay the Spire. Most of these items are mechanically as close as possible to the original relics and potions, while some of them have had to have their properties somewhat changed to reflect the differing nature between D&D and StS.

### Potions
While not all of these are drinkable potions, they are all consumable concoctions made using alchemy.

#### Artifact Potion
*Potion, rare*
<div style='margin-top:-10px'></div>

When you drink this potion, you become filled with mechanical energy for 1 hour. Once during that hour, when you fail a saving throw, you can choose to succeed, instead. After doing so, the potion's magic immediately fades from you.

#### Attack Potion
*Potion, rare*
<div style='margin-top:-10px'></div>

When you drink this potion, your muscles and joints become quicker, for the next minute. When you take the Attack action on your turn for the duration, you can make one more attack than you normally could.

#### Block Potion
*Potion, uncommon*
<div style='margin-top:-10px'></div>

When you drink this potion, you become hardier. For the next 10 minutes, you have 4d6+6 temporary hit points. At the end of the duration, the temporary hit points fade if you have any remaining.

#### Blood Potion
*Potion, common*
<div style='margin-top:-10px'></div>

When you drink this potion, your natural healing speeds up for just a few moments, and you regain hit points equal to your Constitution modifier + your level (a minimum of 1 hit point).

#### Dexterity Potion
*Potion, uncommon*
<div style='margin-top:-10px'></div>

When you drink this potion, you become more agile, for the next minute. You gain the benefits of the *haste* spell, except you cannot take an additional action normally granted by the spell, and when the potion's effect ends, you can act normally on your next turn.

#### Energy Potion
*Potion, rare*
<div style='margin-top:-10px'></div>

When you drink this potion, you gain a surge of energy. On your next turn, you can take two actions, instead of only one.

#### Entropic Brew
*Potion, very rare*
<div style='margin-top:-10px'></div>

When you drink this potion, you immediately become filled with alchemical energy. Roll 3d20, rerolling all duplicate results. You immediately gain the benefits of the potions you rolled for the numbers of on the table below.

| d20  | Potion |
|:---:|:-----------:|
|  1  | Artifact |
|  2  | Attack |
|  3  | Block |
|  4  | Blood |
|  5  | Dexterity |
|  6  | Energy |
|  7  | Essence of Steel |
|  8  | Fairy in a Bottle |
|  9  | Fruit Juice |
|  10  | Gambler's Brew |
|  11  | Ghost in a Jar |
|  12  | Liquid Bronze |
|  13  | Power |
|  14  | Regen |
|  15  | Skill |
|  16  | Snecko Oil |
|  17  | Speed |
|  18  | Steroid |
|  19  | Strength |
|  20  | Swift |

```
```

#### Essence of Steel
*Potion, rare*
<div style='margin-top:-10px'></div>

When you drink this potion, your skin hardens like steel for the next minute. At the start of each of your turns, you gain 2d6+6 temporary hit points.

#### Explosive Potion
*Potion, uncommon*
<div style='margin-top:-10px'></div>

Instead of drinking this potion, you can throw it at a point within 30 feet of yourself. All creatures within 10 feet of the point must succeed on a DC 15 Dexterity saving throw, or take 4d6 fire damage, taking half the damage on a successful save.

#### Fairy in a Bottle
*Potion, rare*
<div style='margin-top:-10px'></div>

When you drink this potion, you gain the benefits of the *death ward* spell, for the next 24 hours.

#### Fear Potion
*Potion, very rare*
<div style='margin-top:-10px'></div>

Instead of drinking this potion, you can throw it at a creature you can see, treating it as a thrown improvised weapon with a range of 20/60. On a hit, the creature becomes vulnerable to all damage until the end of your next turn.

#### Fire Potion
*Potion, uncommon*
<div style='margin-top:-10px'></div>

Instead of drinking this potion, you can throw it at a creature you can see, treating it as a thrown improvised weapon with a range of 20/60. On a hit, the creature takes 6d6 fire damage.

#### Fruit Juice
*Potion, very rare*
<div style='margin-top:-10px'></div>

When you drink this potion, delicious energy courses through you, filling you with power. Your maximum hit points increase by 10.

#### Gambler's Brew
*Potion, rare (can only be consumed by a caster that prepares spells)*
<div style='margin-top:-10px'></div>

When you drink this potion, you can quickly change your magic to match your current situation. You can immediately swap out up to 5 spells you have prepared with an equal amount of spells from the list you prepare spells from.

#### Ghost in a Jar
*Potion, rare*
<div style='margin-top:-10px'></div>

When you drink this potion, your body becomes more intangible, for the next minute. The first time you take damage for the duration, you reduce that damage to 1. Afterwards, the potion's magic immediately fades from you.

#### Liquid Bronze
*Potion, rare*
<div style='margin-top:-10px'></div>

When you drink this potion, your skin becomes as sharp as bronze needles, for the next minute. Whenever a creature hits you with a melee attack for the duration, the creature takes 1d6 piercing damage.

#### Poison Potion
*Potion, uncommon*
<div style='margin-top:-10px'></div>

Instead of drinking this potion, you can throw it at a creature you can see, treating it as a thrown improvised weapon with a range of 20/60. On a hit, the creature takes 1d6 poison damage, and must succeed on a DC 15 Constitution saving throw or become poisoned for the next minute. While a creature is poisoned in this way, it takes 1d6 poison damage at the start of each of its turns.

A creature can repeat its saving throw at the end of each of its turns, ending the effect on a success.

#### Power Potion
*Potion, rare (can only be consumed by a creature that can cast spells of 1st level or higher)*
<div style='margin-top:-10px'></div>

When you drink this potion, magical energy flows through you, for the next minute. The first time you cast a spell of 5th-level or lower using a spell slot after drinking this potion, you do not expend the spell slot. Afterwards, the potion's magic immediately fades from you.

<div class="pageNumber auto"></div>

\page

#### Regen Potion
*Potion, very rare*
<div style='margin-top:-10px'></div>

When you drink this potion, healing energy constantly washes over you, for the next minute. At the start of each of your turns for the duration, you regain 1d6 hit points.

#### Skill Potion
*Potion, rare (can only be consumed by a creature that has a feature or trait restoring on a short or long rest)*
<div style='margin-top:-10px'></div>

When you drink this potion, powerful energy flows through you, for the next minute. The first time you use a feature or expend a resource that you would regain on a short or long rest (such as Action Surge or ki points), you do not expend the usage or resource. Afterwards, the potion's magic immediately fades from you.

#### Smoke Bomb
*Potion, uncommon*
<div style='margin-top:-10px'></div>

Instead of drinking this potion, you can throw it at a point within 30 feet of yourself, mimicking the effects of a 1st-level *fog cloud* spell centered on the point for the next minute.

#### Snecko Oil
*Potion, very rare (can only be consumed by a creature that can cast spells of 1st level or higher)*
<div style='margin-top:-10px'></div>

When you drink this potion, your mind becomes confused but powerful, for the next minute. You immediately regain 2 expended spell slots of 5th-level or lower (you choose the slot levels). Then, at the start of each of your turns for the duration, roll a d6-1; all of your spells of 5th-level or lower cost a spell slot of that level or higher to be cast.

#### Speed Potion
*Potion, rare*
<div style='margin-top:-10px'></div>

When you drink this potion, your ability to dodge is vastly increased, until the end of your next turn. Your AC increases by 10 and you have a +10 bonus to Dexterity saving throws for the duration.

#### Steroid Potion
*Potion, rare*
<div style='margin-top:-10px'></div>

When you drink this potion, your strength is vastly improved, until the end of your next turn. Your weapon attack damage rolls have a +10 bonus to them for the duration.

#### Strength Potion
*Potion, uncommon*
<div style='margin-top:-10px'></div>

When you drink this potion, you become more powerful, for the next minute. Your weapon attack damage rolls have a +3 bonus to them for the duration.

#### Swift Potion
*Potion, common*
<div style='margin-top:-10px'></div>

When you drink this potion, you become faster, for the next 10 minutes. Your movement speed increases by 10 feet for the duration.

#### Weak Potion
*Potion, uncommon*
<div style='margin-top:-10px'></div>

Instead of drinking this potion, you can throw it at a creature you can see, treating it as a thrown improvised weapon with a range of 20/60. On a hit, the creature has disadvantage on attack rolls until the end of its next turn.

```
```

> ##### Credit
> Made using [GMBinder](https://www.gmbinder.com/)
>
> Created by [/u/Dingo_Chungis](https://www.reddit.com/user/Dingo_Chungis), aka [Blackbando](https://blackbando.wordpress.com/).
>
> Original potions from [Slay the Spire](https://store.steampowered.com/app/646570/Slay_the_Spire/).
>

<div class="pageNumber auto"></div>

\page