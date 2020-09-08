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

# Heroes of Might and Magic Spells

This supplement to 5th edition *Dungeons & Dragons* contains spells based on those found in the second and third Heroes of Might and Magic games by New World Computing. Since many of the spells in the games already exist in some form in D&D (such as *lightning bolt, slow,* and *fireball*), my main goal in making this resource was to supplement D&D's existing spell selection with Heroes of Might and Magic's unique ones in D&D's same style and balance of spell mechanics.

## Spell Lists
The following spell lists show which of the new spells
are for a class. A spell’s school of magic is noted in
parentheses after its name. If a spell can be cast
as a ritual, the ritual tag also appears within the
parentheses.

At the DM's discretion, these spells can be used by certain subclasses not listed here; for example, *haunt* and *death ripple* could be domain spells of a cleric of the Death domain.

### Bard Spells
##### 1st Level
*Magic arrow* (evocation)

##### 2nd Level
*Precision* (enchantment)

##### 3rd Level
*Berserk* (enchantment)

<div style='margin-top:-7px'></div>

*Fortune* (transmutation)

<div style='margin-top:-7px'></div>

*Identify person* (divination)

  <div style='margin-top:-7px'></div>

*Mirth* (enchantment)

<div style='margin-top:-7px'></div>

*Misfortune* (transmutation)

<div style='margin-top:-7px'></div>

*Remove obstacle* (conjuration)

<div style='margin-top:-7px'></div>

*View air* (divination)

##### 4th Level

*Magic mirror* (abjuration)

<div style='margin-top:-7px'></div>

*Sorrow* (enchantment)

##### 5th Level
*Forgetfulness* (enchantment)

<div style='margin-top:-7px'></div>

*Slayer* (transmutation)

  <!-- OOOOOOOOOOOO00000000000000000000000000000000000000000000000OOOOOOO -->
### Cleric Spells
##### 1st Level

*Magic arrow* (evocation)

##### 2nd Level
*Precision* (enchantment)

##### 3rd Level

*Destroy undead* (evocation)

<div style='margin-top:-7px'></div>

*Mirth* (enchantment)

<div style='margin-top:-7px'></div>

*Remove obstacle* (conjuration)

<div style='margin-top:-7px'></div>

*View air* (divination)

##### 4th Level

*Counterstrike* (abjuration)

<div style='margin-top:-7px'></div>

*Magic mirror* (abjuration)

<div style='margin-top:-7px'></div>

*Prayer* (evocation)

<div style='margin-top:-7px'></div>

*Sacrifice* (necromancy)

<div style='margin-top:-7px'></div>

*Sorrow* (enchantment)

##### 5th Level
*Forgetfulness* (enchantment)

##### 9th Level
*Armageddon* (evocation)

<!-- OOOOOOOOOOOO00000000000000000000000000000000000000000000000OOOOOOO -->
### Druid Spells
##### 1st Level

*Air shield* (abjuration)

<div style='margin-top:-7px'></div>

*Bloodlust* (enchantment)

<div style='margin-top:-7px'></div>

*Frost ring* (evocation)

<div style='margin-top:-7px'></div>

*Magic arrow* (evocation)

```
```

##### 3rd Level

*Destroy undead* (evocation)

<div style='margin-top:-7px'></div>

*Fortune* (transmutation)

<div style='margin-top:-7px'></div>

*Misfortune* (transmutation)

<div style='margin-top:-7px'></div>

*View air* (divination)

##### 4th Level

*Alagar's ice bolt* (evocation)

<div style='margin-top:-7px'></div>

*Quicksand* (conjuration)

##### 5th Level
*Visions* (divination, ritual)

### Ranger Spells
##### 1st Level

*Magic arrow* (evocation)

##### 2nd Level
*Precision* (enchantment)

##### 5th Level

*Visions* (divination, ritual)

<!-- OOOOOOOOOOOO00000000000000000000000000000000000000000000000OOOOOOO -->
### Paladin Spells

##### 3rd Level

*Destroy undead* (evocation)

<div style='margin-top:-7px'></div>

*Mirth* (enchantment)

##### 4th Level

*Sorrow* (enchantment)

<div style='margin-top:-7px'></div>

*Prayer* (evocation)

<div style='margin-top:-7px'></div>

*Sacrifice* (necromancy)

<!-- OOOOOOOOOOOO00000000000000000000000000000000000000000000000OOOOOOO -->
### Sorcerer Spells
##### 1st Level

*Bloodlust* (enchantment)

<div style='margin-top:-7px'></div>

*Frost ring* (evocation)

<div style='margin-top:-7px'></div>

*Magic arrow* (evocation)

##### 2nd Level
*Disrupting ray* (evocation)

##### 4th Level

*Alagar's ice bolt* (evocation)

<div style='margin-top:-7px'></div>

*Magic mirror* (abjuration)

##### 5th Level
*Forgetfulness* (enchantment)

<div style='margin-top:-7px'></div>

*Shadow clone* (illusion)

##### 6th Level
*Steelskin* (abjuration)

##### 7th Level
*Implosion* (transmutation)

##### 8th Level
*Inferno* (evocation)

##### 9th Level
*Armageddon* (evocation)

<!-- OOOOOOOOOOOO00000000000000000000000000000000000000000000000OOOOOOO -->
### Wizard Spells
##### 1st Level

*Air shield* (abjuration)
<div style='margin-top:-7px'></div>

*Frost ring* (evocation)

<div style='margin-top:-7px'></div>

*Magic arrow* (evocation)

##### 2nd Level
*Disrupting ray* (evocation)

<div style='margin-top:-7px'></div>

*Weakness* (necromancy)

<div class='pageNumber auto'></div>

\page

##### 3rd Level

*Fortune* (transmutation)

<div style='margin-top:-7px'></div>

*Frenzy* (enchantment)

<div style='margin-top:-7px'></div>

*Identify person* (divination)

<div style='margin-top:-7px'></div>

*Misfortune* (transmutation)

<div style='margin-top:-7px'></div>

*Remove obstacle* (conjuration)

<div style='margin-top:-7px'></div>

*View air* (divination)

##### 4th Level

*Alagar's ice bolt* (evocation)

<div style='margin-top:-7px'></div>

*Counterstrike* (abjuration)

<div style='margin-top:-7px'></div>

*Death ripple* (necromancy)

<div style='margin-top:-7px'></div>

*Magic mirror* (abjuration)


##### 5th Level

*Create land mines* (conjuration)

<div style='margin-top:-7px'></div>

*Forgetfulness* (enchantment)

<div style='margin-top:-7px'></div>

*Haunt* (necromancy)

<div style='margin-top:-7px'></div>

*Shadow clone* (illusion)

<div style='margin-top:-7px'></div>

*Slayer* (transmutation)

##### 6th Level
*Steelskin* (abjuration)

<div style='margin-top:-7px'></div>

*Summon boat* (conjuration)

##### 7th Level
*Implosion* (transmutation)

##### 8th Level
*Inferno* (evocation)

##### 9th Level
*Armageddon* (evocation)

## Spell Descriptions
The spells are presented in alphabetical order.
<div style='margin-top:0px'></div>

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/d/d8/Air_Shield.png'
  />

  <div style='margin-top:-10px'></div>

#### Air Shield
*1st-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

A swirling barrier of wind surrounds a creature within range. Until the spell ends, creatures have disadvantage on ranged attacks against the target.

**At Higher Levels.** When you cast this spell using a spell slot of 2nd level or higher, you can target one additional creature per slot level above 1st.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/9/97/Ice_Bolt.png'
  />

  <div style='margin-top:-10px'></div>

#### Alagar's Ice Bolt
*4th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous

<div style='margin-top:0px'></div>

You fire a blast of chilling frost at a creature you can see within range. Make a ranged spell attack. On a hit, a creature takes 5d12 cold damage, and it cannot speak for 1 minute. The creature can make a Constitution saving throw at the end of each of its turns, ending the effect on a success. The effect also ends if the creature takes at least 5 fire damage.

**At Higher Levels.** When you cast this spell using a spell slot of 5th level or higher, the damage increases by 1d12 for each slot level above 4th.
<!-- end new spell -->

```
```
<!-- start new spell -->

<img
  src='https://heroes.thelazy.net/images/6/63/Armageddon.png'
  />

  <div style='margin-top:-10px'></div>

#### Armageddon
*9th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** Instantaneous

<div style='margin-top:0px'></div>

You call down the fiery doom of the end of the world. You and each creature and object within 360 feet of you takes 5d10 fire damage and 5d10 lightning damage. Creatures can make a Dexterity saving throw, taking half damage on a success. Each creature within this radius is frightened of you for 1 minute, or until it succeeds on a Wisdom saving throw at the end of its turn.

The fire ignites flammable objects that are not worn or carried. After the fire subsides, the area is lightly obscured by black smoke for 1 hour. A strong wind can disperse the wind in half the time.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/4/44/Berserk.png'
  />

  <div style='margin-top:-10px'></div>

#### Berserk
*3rd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

Choose a creature you can see within range. It must succeed on a Wisdom saving throw or use its reaction, if available, to move up to half its speed and make one melee attack against the creature nearest to it. While the spell persists, you can use an action on your turn to repeat this effect. A creature can repeat the saving throw at the end of its turn, ending the your control over it on a success.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/1/11/Bloodlust.png'
  />

  <div style='margin-top:-10px'></div>

#### Bloodlust
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a drop of blood)
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You instill an emotion of bloodlust in an allied creature within range. For the duration, when the creature hits with a melee weapon attack, it deals an additional 1d4 damage to its target. Each time the creature hits that target with a melee weapon attack, the damage dealt increases by 1d4. This stacking resets if the creature targets another creature with an attack or misses on an attack.

**At Higher Levels.** When you cast this spell using a spell slot of 3rd level, the damage die increases to a d6. At a 5th-level slot, it increases to a d8. At a 7th-level slot, it increases to a d10. At a 9th-level slot, it increases to a d12.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/3/33/Counterstrike.png'
  />

  <div style='margin-top:-10px'></div>

#### Counterstrike
*3rd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You grant a creature within range the ability to counter incoming attacks. For the duration, the creature can use its reaction when it takes damage from a creature within 5 feet of it to make one melee weapon attack against that creature.
<!-- end new spell -->

<div class='pageNumber auto'></div>

\page

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/3/37/Land_Mine.png'
  />

  <div style='margin-top:-10px'></div>

#### Create Land Mines
*5th-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** 1 hour

<div style='margin-top:0px'></div>

You create up to four 2-foot-diameter land mines in unoccupied spaces you can see within range that last for the duration. If a creature enters the space of a land mine, the mine explodes. The creature must make a Dexterity saving throw. On a failure, the creature takes 8d10 fire damage and is knocked prone. On a success, the creature takes half damage and does not fall prone.

The land mines are difficult to see, requiring a passive Perception or successful Wisdom (Perception) check against your spell save DC to notice. A creature who sees a land mine can attempt to disarm it with an Intelligence (Arcana) check or a Dexterity (thieves' tools) check against your spell save DC. On a failure, the land mine explodes as if the creature had stepped on it.

At the end of the spell's duration, all undetonated land mines vanish.

**At Higher Levels.** When you cast this spell using a spell slot of 6th level or higher, you can create two additional land mines for each slot level above 5th.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/3/3f/Death_Ripple.png'
  />

  <div style='margin-top:-10px'></div>

#### Death Ripple
*4th-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a skull)
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

Swirling red energy ripples out from you. Each non-undead creature besides you within 30 feet of you must making a Constitution saving throw. A creature takes 8d6 necrotic damage on a failed save, or half as much on a successful one.

**At Higher Levels.** When you cast this spell using a spell slot of 5th level or higher, the damage increases by 1d6 for each slot level above 4th.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/1/1a/Destroy_Undead.png'
  />

  <div style='margin-top:-10px'></div>

#### Destroy Undead
*3rd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** Instantaneous

<div style='margin-top:0px'></div>

Light washes over enemy undead in range. Each undead creature within 30 feet of you must making a Constitution saving throw. A creature takes 6d8 radiant damage on a failed save, or half as much on a successful one.

**At Higher Levels.** When you cast this spell using a spell slot of 4th level or higher, the damage increases by 1d8 for each slot level above 3rd.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/8/85/Disrupting_Ray.png'
  />

  <div style='margin-top:-10px'></div>

#### Disrupting Ray
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** S
- **Duration:** 1 minute

<div style='margin-top:0px'></div>

A blurry ray of negative energy streaks toward a creature in range. Make a ranged spell attack roll. On a hit, the target creature's Armor Class is reduced by 2 for the duration. An affected creature can use its action to make a Constitution saving throw, ending the effect on a success.

<!-- end new spell -->

```
```

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/f/f8/Forgetfulness.png'
  />

  <div style='margin-top:-10px'></div>

#### Forgetfulness
*5th-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You force one creature you can see within range to make an Intelligence saving throw. On a failure, the creature forgets the last 10 seconds of its memory. If the creature is concentrating on a spell that it cast within this 10-second period, its concentration on that spell immediately breaks.

Also, until the spell ends, when the creature attempts to make an action, it must roll a d8. On a roll of 6 or more, the creature may take its turn as normal. On any other roll, the creature wastes its action reeling in confusion. The creature can repeat the saving throw at the end of each of its turns, ending the effect on a success.

**At Higher Levels.** When you cast this spell using a 6th-level spell slot, the time forgotten is 1 minute. When you use a 7th-level slot, the time is 10 minutes. When you use an 8th-level slot, the time is 1 hour. When you use a 9th-level slot, the time is 8 hours.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/b/bf/Fortune.png'
  />

  <div style='margin-top:-10px'></div>

#### Fortune
*3rd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M (a horseshoe, a four-leaf clover, or a rabbit's foot)
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

Fortune smiles upon a creature of your choice within range. For the duration, the creature scores a critical hit with weapon attacks on a roll of 19 or 20 and has advantage on Dexterity saving throws.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/f/f1/Frenzy.png'
  />

  <div style='margin-top:-10px'></div>

#### Frenzy
*3rd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You touch a willing creature. Until the spell ends, the creature has advantage on all melee attack rolls, but attack rolls against the creature have advantage.

**At Higher Levels.** When you cast this spell using a spell slot of 4th level or higher, you can target one additional creature for each slot level above 3rd.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/0/00/Frost_Ring.png'
  />

  <div style='margin-top:-10px'></div>

#### Frost Ring
*1st-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You drain the body heat from a group of creatures you can see in range. Choose a spot you can see within range that can fill a 5-foot cube. All creatures within a 10-foot-radius sphere outside that 5-foot cube must succeed on a Constitution saving throw. A creature suffers 2d6 cold damage on a failed save, or half as much on a successful one.

**At Higher Levels.** When you cast this spell using a spell slot of 2nd level or higher, the spell deals an additional 1d6 damage for each slot level above 1st.
<!-- end new spell -->

<div class='pageNumber auto'></div>

\page

<!-- start new spell -->
<img
  src='https://vignette.wikia.nocookie.net/mightandmagic/images/0/06/H2-Haunt.png/revision/latest?cb=20140613181132&path-prefix=en'
     style='mix-blend-mode:multiply;'
  />

  <div style='margin-top:-10px'></div>


#### Haunt
*5th-level necromancy*
___
- **Casting Time:** 1 hour
- **Range:** 60 feet
- **Components:** V, S, M (a platinum lantern worth at least 1,000 gp, which the spell consumes)
- **Duration:** 7 days

<div style='margin-top:0px'></div>

As part of the casting of this spell, you designate an area that can fit within a 120-foot cube. Within that area, spirits under your control guard it for the duration of the spell. You choose one of the following options for what type of spirits appear:
*   1 **ghost**
*   1 **banshee**
*   2 **sword wraith warriors**
*   4 **poltergeists**
*   8 **specters**
*   16 **shadows**

<div style='margin-top:0px'></div>


The spirits are indifferent to creatures or types of creatures you designate as long as they are not attacked. Otherwise, the spirits are hostile to any other creatures that attempt to enter the haunted area. At the end of the spell's duration, the spirits vanish.

**At Higher Levels.** When you cast this spell using a spell slot of a higher level, the duration increases to 30 days with a 6th-level slot, to 90 days with a 7th-level slot, to 180 days with an 8th-level slot, and to a year and a day with a 9th-level spell slot.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://vignette.wikia.nocookie.net/mightandmagic/images/e/e6/H2-IdentifyHero.png/revision/latest?cb=20140613181133&path-prefix=en'
     style='mix-blend-mode:multiply'
  />

  <div style='margin-top:-10px'></div>

#### Identify Person
*3rd-level divination*
___
- **Casting Time:** 1 minute
- **Range:** Same plane of existence
- **Components:** V, S, M (a fingernail or hair from the target, which the spell consumes)
- **Duration:** Instantaneous

<div style='margin-top:0px'></div>

"You attempt to discover the identity of a humanoid you are familiar with on the same plane of existence as you. That creature must make a Charisma saving throw. On a failed save, you learn certain information about it. The DM tells you three facts that you choose from the options below:

*   Real name
*   Race and subrace
*   Alignment
*   Magic items attuned
*   Charisma score
*   Languages spoken
*   Current effects of spells or potions
*   Ideal
*   Bond
*   Flaw

<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/0/0e/Implosion.png'
  />

  <div style='margin-top:-10px'></div>

#### Implosion
*7th-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous

<div style='margin-top:0px'></div>

You attempt to turn a target inside-out. The target can be a creature or an object. A creature targeted by this spell must make a Constitution saving throw. On a failed save, the target takes 10d8+40 necrotic damage and has disadvantage on ability checks and attack rolls until cured by a *lesser restoration* spell or similar magic. If this</br>&emsp;&emsp;&emsp;damage reduces a creature to 0 hit points, it implodes into a</br>&emsp;&emsp;&emsp;Tiny ball of dense viscera, utterly mutilated.

```
```

This spell automatically implodes a Large or smaller nonmagical object, destroying it and reducing it into a dense, Tiny crumpled version of itself.

**At Higher Levels.** When you cast this spell using a spell slot of 8th level or higher, the damage increases by 3d8 for each slot level above 7th.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/b/be/Inferno.png'
  />

  <div style='margin-top:-10px'></div>

#### Inferno
*1st-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** 150 feet
- **Components:** V, S, M (a piece of flint and a piece of steel)
- **Duration:** Instantaneous

<div style='margin-top:0px'></div>

A massive explosion erupts in a 60-foot radius centered on a point you choose within range. The creatures within the explosion are deafened until the end of your next turn, and each must make a Dexterity saving throw. On a failed save, a creature takes 13d6 fire damage and is knocked prone. On a successful save, it takes half damage and is not knocked prone.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/4/44/Magic_Arrow.png'
  />

  <div style='margin-top:-10px'></div>

#### Magic Arrow
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

An arrow of magical energy flies from your hand toward a target in range. Make a ranged spell attack against a target. On a hit, the target takes 2d10 force damage.

**At Higher Levels.** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by 1d10 for each slot level above 1st.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/1/1d/Magic_Mirror.png'
  />

  <div style='margin-top:-10px'></div>

#### Magic Mirror
*4th-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (a small jeweled mirror worth at least 100gp)
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

A creature you touch reflects magic for the duration. Any time the affected creature is targeted by a spell of 4th level or lower that affects only it or that is a line spell, that creature can roll a d4. On a 1 or 2, the creature is affected by the spell but has resistance to any damage it causes. On a roll of 3 or 4, the creature is unaffected, and the effect is reflected back at the caster as though it originated from the creature, turning the caster into a target.

**At Higher Levels.** When you cast this spell using a spell slot of a higher level, the level of spell this it can reflect is equal to the spell level cast.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/0/0b/Mirth.png'
  />

  <div style='margin-top:-10px'></div>

#### Mirth
*3rd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You instill your allies with hope and resolve. Choose up to 3 creatures within range. Until the spell ends, an affected creature is immune to being frightened and has advantage on initiative checks and Wisdom saving throws.

**At Higher Levels.** When you cast this spell using a spell slot of 4th level or higher, you can target one additional creature for each slot above 3rd.
<!-- end new spell -->

<div class='pageNumber auto'></div>

\page

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/d/df/Misfortune.png'
  />

  <div style='margin-top:-10px'></div>

#### Misfortune
*3rd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a piece of broken mirror, a ball of black cat hair, or a raven's feather)
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You attempt to curse a creature of your choice within range with bad luck. A creature must succeed on a Charisma saving throw. On a failed save, until the spell ends, the creature automatically misses on attack rolls of 1 or 2, and any critical hit it scores becomes a normal hit. The target also has disadvantage on Dexterity saving throws.

<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/3/32/Prayer.png'
  />

  <div style='margin-top:-10px'></div>

#### Prayer
*4th-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, M (prayer beads or a prayer wheel)
- **Duration:** 10 minutes

<div style='margin-top:0px'></div>

You beseech divine favor upon a creature within range. For the duration, the creature is granted the following benefits:
*   It gains a +2 bonus to its AC.
*   It has a +2 bonus to attack rolls.
*   Its walking speed increases by 15 feet.
*   It has advantage on Wisdom and Charisma saving throws.
*   It gains 5 temporary hit points.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/e/ee/Precision.png'
  />

  <div style='margin-top:-10px'></div>

#### Precision
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (two intertwined silver rings worth at least 30 gp)
- **Duration:** 10 minutes

<div style='margin-top:0px'></div>

You touch a creature and bless its mind with precision. For the duration, the target's ranged weapon attacks ignore half cover and three-quarter cover. In addition, the creature does not suffer disadvantage on its ranged weapon attack rolls when attacking at long range.

**At Higher Levels.** When you cast this spell using a spell slot of 3rd level or higher, you can target one additional creature for each slot level above 2nd.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/3/3b/Quicksand.png'
  />

  <div style='margin-top:-10px'></div>

#### Quicksand
*4th-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S, M (a drop of mud)
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You cause up to four puddles of quicksand to burble out of the ground in spaces  you can see within range, where they remain for the duration. Each puddle has a diameter of 10 feet. When a Large or smaller creature enters a puddle of quicksand for the first time on its turn or starts its turn on one, it must succeed on a Strength saving throw or be restrained. A creature can use its action and half its movement when restrained to make a Strength (Athletics) or Dexterity (Acrobatics) check, freeing itself on a success and moving out of the quicksand's space.

**At Higher Levels.** When you cast this spell using a spell slot of 5th level or higher, you can create two additional puddles for each slot level above 4th.
<!-- end new spell -->

```
```

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/3/3c/Remove_Obstacle.png'
  />

  <div style='margin-top:-10px'></div>

#### Remove Obstacle
*3rd-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V
- **Duration:** Until dispelled

<div style='margin-top:0px'></div>

Choose a nonmagical natural object within range that is not being worn or carried, such as a rock, tree, or small pond, that fit within a 20-foot cube. The object fades into a pocket dimension and is replaced with smooth, even ground matching the terrain around it.

A *dispel magic* spell cast on the spot can return the obstacle back to its normal state.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/1/18/Sacrifice.png'
  />

  <div style='margin-top:-10px'></div>

#### Sacrifice
*4th-level necromancy*
___
- **Casting Time:** 1 minute
- **Range:** Touch
- **Components:** V, S, M (a gilded dagger worth at least 150 gp)
- **Duration:** Special

<div style='margin-top:0px'></div>

You sacrifice one creature's life to raise another who has died within the past 24 hours. You touch a willing humanoid that is the same race as the dead target creature. At the end of the casting time, the creature's body is completely consumed by magical flames, leaving only fine ashes behind. If the dead creature's soul is both willing and at liberty to rejoin the body, the dead creature returns to life with 1 hit point.

This spell closes all mortal wounds, but it doesn’t restore missing body parts. If the creature is lacking body parts or organs integral for its survival—its head, for instance—the spell automatically fails. Coming back from the dead is an ordeal. The target gains 4 levels of exhaustion after it is raised.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/3/34/Clone.png'
  />

  <div style='margin-top:-10px'></div>

#### Shadow Clone
*5th-level illusion*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** 1 hour

<div style='margin-top:0px'></div>

Touch a willing Large or smaller creature within range that you can see. A shadowy clone of the creature forms in an unoccupied space within 5 feet of the original creature and remains for the duration. The shadow clone is an exact duplicate of the original creature, including its equipment, alignment, and disposition, except it cannot cast spells or use magic items, and it has only 1 hit point. In addition, the creature's hit point maximum cannot be increased, and its appearance is translucent and shadowy. No other creature can use the shadow clone's equipment or items.

The shadow clone is friendly to you and your companions and takes its turn directly after you in the initiative order. It obeys any verbal commands that you issue to it (no action required by you). If you don't issue any commands to the shadow clone, it defends itself from hostile creatures but otherwise takes no actions.

The shadow clone and any equipment that was created with it disappears if it is reduced to 0 hit points. The clone also disappears if the creature it was copied from dies.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/6/6e/Slayer.png'
  />

  <div style='margin-top:-10px'></div>

#### Slayer
*5th-level transmutation*
___
- **Casting Time:** 1 bonus action
- **Range:** Touch
- **Components:** V, S
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You touch a willing creature. For the duration, that creature deals an additional 3d6 damage on weapon hits against the creatures of</br>the following types: celestials, dragons, fiends, giants, and monstrosities.
<!-- end new spell -->

<div class='pageNumber auto'></div>

\page

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/c/cd/Sorrow.png'
  />

  <div style='margin-top:-10px'></div>

#### Sorrow
*4th-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

This spell fills creature's minds with anguish and despair. Each creature in a 10-foot-radius sphere centered on a point you choose within range must succeed on a Charisma saving throw when you cast this spell or be affected by it.

An affected target can’t take reactions and must roll a d10 at the start of each of its turns to determine its behavior for that turn.

<table>
  <thead>
    <tr>
      <td style="width: 50px;">d10</td><td>Behavior</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td><td>The creature drops whatever it's holding, falls prone, and becomes incapacitated in a fit of weeping until its next turn.</td>
    </tr>
    <tr>
      <td>2–6</td><td>The creature is blinded by tears until its next turn.</td>
    </tr>
    <tr>
      <td>7–8</td><td>The creature has disadvantage on all ability checks this turn.</td>
    </tr>
    <tr>
      <td>9–10</td><td>The creature can act and move normally, though it does so in a more melancholy way than normal.</td>
    </tr>
  </tbody>
</table>

At the end of each of its turns, an affected target can make a Charisma saving throw. If it succeeds, this effect ends for that target.

<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://vignette.wikia.nocookie.net/mightandmagic/images/d/db/H2-Steelskin.png/revision/latest?cb=20140613181351&path-prefix=en'
     style='mix-blend-mode:multiply;'
  />

  <div style='margin-top:-10px'></div>

#### Steelskin
*6th-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (mithril dust worth 100 gp, which the spell consumes)
- **Duration:** 10 minutes (concentration)

<div style='margin-top:0px'></div>

This spell turns the flesh of a willing creature you touch as hard as steel. Until the spell ends, the target has immunity to bludgeoning, piercing, and slashing damage from nonmagical weapons that aren't adamantine.

<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/b/b0/Summon_Boat.png'
  />

  <div style='margin-top:-10px'></div>

#### Summon Boat
*6th-level conjuration*
___
- **Casting Time:** 10 minutes
- **Range:** 120 feet
- **Components:** V, S, M (a pearl worth at least 300 gp, which the spell consumes)
- **Duration:** 24 hours

<div style='margin-top:0px'></div>

A wooden boat emerges from a body of water within range that is at least 120 feet square. Any creatures in the ship's space when it is summoned are harmlessly lifted as the ship rises.

The boat uses the statistics of a **keelboat** (see* Ghosts of Saltmarsh*). It is 60 feet by 20 feet in size and can hold up to 7 passengers comfortably. It has 100 hit points, 15 AC, a damage threshold of 10, and a sailing speed of 3 miles per hour. You are considered proficient with the vehicle and with navigator's tools while on the boat. The ship is furnished with cots, rope, and all the tools necessary for maintenance and sailing, as well as 1 days' worth of rations. The boat is decorated however you like. If anything created by this spell is taken off of the boat, it transforms to salt water and disappears.

After 24 hours or when you cast this spell to summon a different boat, the boat harmlessly fades out of existence, unless you cast the spell again.

If you cast this spell every day for 10 days, the boat and all its cargo become permanent.

<!-- end new spell -->

```
```

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/b/ba/View_Air.png'
  />

  <div style='margin-top:-10px'></div>

#### View Air
*3rd-level divination*
___
- **Casting Time:** 1 minute
- **Range:** Self
- **Components:** V, S
- **Duration:** 10 minutes (concentration)

<div style='margin-top:0px'></div>

You create an invisible sensor at your location that floats upward at a rate of 30 feet per round. If the sensor encounters a ceiling or other impassable surface, it stops its movement. The eye can look in every direction. When you cast the spell and as an action, you can become blinded to your surroundings in order to see through the sensor as if you were in its space. As your action, you can switch back your vision.

A creature that can see the sensor (such as a creature benefiting from see invisibility or truesight) sees a luminous, intangible orb about the size of a fist.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/1/1a/Visions.png'
  />

  <div style='margin-top:-10px'></div>

#### Visions
*5th-level divination (ritual)*
___
- **Casting Time:** 1 minute
- **Range:** 500 feet
- **Components:** V, S, M (a magnifying glass worth at least 100 gp)
- **Duration:** 10 minutes (concentration)

<div style='margin-top:0px'></div>

For the duration of the spell, you know the exact number, type, and general disposition of creatures within range. For example, you know whether a group of hobgoblins on the other side of a hill would attack you on sight, allow you to speak, ignore you, or be willing to trade.

The spell can penetrate most barriers, but it is blocked if creatures have complete cover from you with 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt. For example, you cannot detect the number of creatures underground if there is no cave entrance from your current location to reach them.

**At Higher Levels.** When you cast this spell using a 6th-level spell slot, the range is 1,000 feet. When you use a 7th-level slot or higher, the range is 1 mile.
<!-- end new spell -->

<!-- start new spell -->
<img
  src='https://heroes.thelazy.net/images/f/f9/Weakness.png'
  />

  <div style='margin-top:-10px'></div>

#### Weakness
*2nd-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** 1 minute (concentration)

<div style='margin-top:0px'></div>

You attempt to weaken a creature you can see within range. The creature must succeed on a Constitution saving throw, or it deals only half damage with weapon attacks that use Strength until the spell ends. The target can repeat the saving throw at the end of each of its turns, ending the effect on a success.

**At Higher Levels.** When you cast this spell using a spell slot of 2nd level or higher, you can target one additional creature per slot above 1st.
<!-- end new spell -->

<div style='margin-top:100px'></div>



> ##### Credits
> Thanks to **mightandmagic.fandom.com** and **heroes.thelazy.net** for the images.
>
> Heroes of Might and Magic II and III are owned by Ubisoft.


<div class='pageNumber auto'></div>
