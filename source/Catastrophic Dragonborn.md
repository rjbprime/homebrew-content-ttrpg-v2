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

# Additional Dragonborn subtypes

## Catastrophic Dragonborn

### Traits

* ***Ability Score Increases.*** +1 Strength, +1 Charisma
* ***Size.*** Medium
* ***Speed.*** 30 feet
* ***Vision.*** Darkvision 60 feet
* ***Elemental Aura.*** Unlike normal dragonborn, you possess an aura rather than a breath weapon. Raising your aura is done as an Attack option and grants you a bonus determined by your subrace. As a bonus action, you can trigger your aura's secondary attack, which inflicts 2d6 damage to any target that fails its saving throw (DC 8 + your Charisma modifier + your Proficiency bonus), or half damage if it succeeds on the saving throw. This damage increases to 3d6 at 6th level, 4d6 at 11th level, and 5d6 at 16th level. Your aura is a Concentration effect that lasts for 1 minute, until your Concentration is broken, or you trigger its secondary attack, whichever comes first. After you have used your Aura, you must complete a short rest or a long rest before you can use it again.
* ***Elemental Dragonkin.*** Choose the Avalanche, Blizzard, Earthquake, Tornado, Typhoon, Volcanic or Wildfire Dragonborn subrace. Your abilities are determined by your subrace.

#### Avalanche Dragonborn

* ***Ability Score Increases.*** +1 Strength
* ***Landslide.*** If you take the Dash action, you can then take a Bonus Action to make a melee attack.
* ***Wings of Dust.*** You always count as having a running start when making Jump checks. Additionally, your horizontal jump distance is twice your Strength score in feet and your vertical jump distance is 6 + your Str modifier feet.
* ***Crashing Descent.*** When falling, you can opt to take a Constitution saving throw (DC 5 + 1 per 10 feet fallen). On a successful save, you take no falling damage when you hit the ground, but are instead Stunned until the end of your next turn.
* ***Aura - Rain of Stone.*** Your aura is a swirling cloud of dust and jagged stone shards. Whilst your aura is active, melee and ranged attacks against you suffer Disadvantage on their attack roll. Your aura attack targets a number of hostile creatures equal to your Charisma modifier (minimum of 1) within 15 feet, and forces a Dexterity save. Damage inflicted by this aura counts as Magical and Bludgeoning for purposes of damage resistance and vulnerability.


#### Blizzard Dragonborn
* ***Ability Score Increases.*** +1 Intelligence
* ***Arctic Spawned.*** You are Acclimatized to Extreme Cold and ignore both Difficult Terrain and Perception Disadvantages based on icy or snowy conditions.
* ***Frigid Claws.*** Your unarmed strikes can inflict Cold damage equal to your Intelligence modifier instead of the normal damage for an unarmed strike.
* ***Aura - Freezing Winds.*** Your aura is whirling array of bitterly cold wind and snowflakes. Whilst your aura is up, ranged attacks against you suffer Disadvantage to their attack rolls. Your aura attack targets all creatures within 15 feet of you, inflicting Cold damage and requiring a Constitution save. Those that fail this save, in addition to taking full damage, suffering Disadvantage on the next weapon attack roll they make before the end of their next turn.


#### Earthquake Dragonborn
* ***Ability Score Increases.*** +1 Dexterity
* ***Surefooted.*** You ignore Difficult Terrain based on broken, rocky or otherwise physically treacherous ground, and have Advantage on Acrobatics checks made to keep your balance.
```
```
* ***Boulder-Breaking Claws.*** You have claws you can use when making an unarmed strike, causing it to inflict 1d6 + Str modifier Slashing damage instead of the normal damage. Additionally, you have a Burrow speed of 20 feet.
* ***Aura - Quaking Earth.*** Your aura causes the earth to buckle and tremble around you. Whilst your aura is active, any creature that gets within 5 feet of you must make a Dexterity save (standard Aura DC) or be knocked prone. When you use your aura attack, all creatures within 15 feet that are standing on the same surface as you must make a Dexterity save. It inflicts Force damage, and those who fail their save are knocked prone.


#### Tornado Dragonborn
* ***Ability Score Increases.*** +1 Dexterity
* ***Wind Walker.*** You always count as having a running start when making Jump checks. Additionally, your horizontal jump distance is twice your Strength score in feet and your vertical jump distance is 6 + your Str modifier feet.
* ***Hungry Storm.*** When you make an unarmed strike, you can choose to inflict either Cold or Lightning damage equal to your charisma modifier instead of the normal damage for an unarmed strike.
* ***Aura - Whirling Winds.*** Your aura is a tornado-like vortex of wind, frost and sparks. Whilst your aura is active, ranged attacks against you suffer Disadvantage to their attack roll. When you make your aura attack, you can Dash twice your normal distance; whilst Dashing, you can make an unarmed strike against each enemy you pass within reach of during your move. Creatures you strike at during this attack can make a Dexterity save to halve the damage, and take either Cold or Lightning damage (your choice for each enemy).


#### Typhoon Dragonborn
* ***Ability Score Increases.*** +1 Strength
* ***Water-Dweller.*** You have a Swim speed of 30 feet.
* ***Amphibious.*** You can breathe air and water.
* ***Shocking Touch.*** Your unarmed strikes can inflict Lightning damage equal to your Charisma modifier instead of the normal damage for an unarmed strike.
* ***Aura - Grasping Winds.*** Your aura swirls around you in a vortex of wind and water, pulling at limbs. Creatures within 5 feet of you suffer Disadvantage on melee attacks made against you. Your aura attack targets all creatures within 15 feet of you for Lightning damage, and is resisted with a Constitution saving throw.


#### Volcanic Dragonborn
* ***Ability Score Increases.*** +1 Constitution
* ***Furnace Spawned.*** You are Acclimatized to Extreme Heat and ignore Perception Disadvantages based on heat and smoke.
* ***Toxin Lover.*** You have Advantage on saving throws against Poison.
* ***Aura - Noxious Fumes.*** Your aura is a volatile cloud of poisonous, flammable gasses. Whilst is active, any creature that gets within 5 feet of you must make a Constitution save (standard Aura DC) or be Poisoned until the end of your next turn. Your aura attack ignites this cloud, causing it to burst into flames; all creatures within 15 feet must make a Dexterity save. It inflicts Fire damage.


#### Wildfire Dragonborn
* ***Ability Score Increases.*** +1 Charisma
* ***Blazing Speed.*** Your movement speed increases by +5 feet, to 35 feet.
* ***Furnace Spawned.*** You are Acclimatized to Extreme Heat and ignore Perception Disadvantages based on heat and smoke.
* ***Burning Touch.*** Your unarmed strikes can inflict Lightning damage equal to your Charisma modifier instead of the normal damage for an unarmed strike.
* ***Aura - Withering Heat.*** Your aura is a shimmering field of heat intense enough to induce spontaneous combustion. Any creature within 10 feet must make a Constitution save (standard Aura DC) or suffer Disadvantage on all attack rolls until the end of your next turn. Your aura attack causes the field to erupt in a sudden conflagration, forcing a Dexterity save and inflicting Fire damage.