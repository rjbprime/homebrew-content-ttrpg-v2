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
	background: url('https://groumy.github.io/homebrewery-sotdl/images/sotdl-background-small.jpg');
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
	font-weight: 350;
	line-height: 1;
}

.phb h2{
	font-size: 125%;
}

.phb h3{
	font-size: 110%;
	border-bottom-style: none;
        margin-top:auto;
        margin-bottom:auto;
        line-height: 1;
}

.phb h4{
	font-size: 107.5%;
}

.phb h5{
	font-size: 105%;
	border-bottom-style: solid;
	border-bottom-color: black;
	border-bottom-width: 1px;
}

.phb h6{
	font-size: 102.5%;
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

.phb p + ul {
    margin-top: -1mm;
}

.phb li + li {
    margin-top: 0mm;
}

.phb li {
    line-height: 1.03;
}

</style>

## Ranger Conclaves

### Nomad Conclave

Rangers of the Nomad Conclave keep their minds in a strange, rarified state. They seek to accumulate knowledge, both of nature and deeper, wider knowledge, the underlying structure of all things. Nomads pair psionics and their attunement to nature in order to further their goals.

Nomads, as their name indicates, delight in travel, exploration, and discovery. They desire to garner as much experience and knowledge as they can, and the pursuit of secrets can become an obsession for them.

#### Breadth of Knowledge

Starting at 3rd level, you have proficiency or fluency in two additional skills, tools, or languages of your choice. In addition, you have advantage on saving throws to avoid becoming magically lost.

#### Psionic Influence

When you choose this archetype at 3rd level, you learn psionic acts. Choose three from the list below. When you reach 7th, 11th, and 15th levels, you learn one additional act of your choice.

***Nomadic Arrow.*** You imbue a weapon with a strange semblance of sentience, allowing it to unerringly find its mark. You ignore disadvantage with any ranged weapon attack roll you make. If disadvantage would normally apply, you can't benefit from advantage on the same roll.

***Chameleon Ego.*** You have advantage on Dexterity (Stealth) checks when your are not charmed or frightened, and have control of your mind.

***Pickpocket Image.*** As an action, you can remove your image from another creature's mind. That creature must make a Wisdom saving throw. On a failure, you are invisible to them until the start of their next turn, with no effect on a success.

***Fast Intelligence.*** Your base walking speed increases by 10 feet.

***Savage Mind.*** You've learned to cut flesh with additional vigor, from either enjoyment, experience, force of will, or a combination thereof. Once per turn when you roll damage for a weapon attack, you can reroll the weapon's damage dice and use either total.

***Unlocked Knowledge.*** Choose two skills, two languages, two tools, or a mix totalling 2. You have proficiency or fluency in your choices.

***Step of Mind.*** You know the *misty step* spell and can cast it. Once you cast the spell in this way, you can't cast it again until you finish a short or long rest.

***Revisited Will.*** You can trade your physical agility with another fortification of your choice. You can change your ranger Dexterity saving throw to another ability saving throw of your choice over a time of 1 hour, which can be done during a short rest. This saving throw can be repeatedly changed.

***Perception Integrity.*** You have advantage on Intelligence saving throws, and Intelligence (Investigation) checks to discern illusions for their true nature.

<div class='descriptive'>

##### Revised Ranger
If you are using the Revised Ranger from Unearthed Arcana, this conclave grants Extra Attack at 5th level.

</div>

#### Memory of a Thousand Steps
At 7th level, you gain the ability to use psionics to recall your steps. As a reaction when you are hit by an attack, you can teleport to an unoccupied space that you occupied since the start of your last turn, and the attack misses you. Once you use this feature, you can't use it again until you finish a short or long rest.

#### Thrice Minded
Beginning at 11th level, you can learn greater psionic acts. Choose one from the list below. When you reach 15th level, you can choose one additional greater psionic act.

***Three-Weapon Fighting.*** You gain the ability to control a weapon telekinetically within 5 feet of you, which must be a one-handed melee weapon you can normally wield. If you take the Attack action on your turn, you can make one melee weapon attack with this weapon as a reaction, for the damage roll of which you don't add your ability modifier.

Your reach for picking up objects, pushing, dragging, or lifting is considered 5 feet regardless of your arm length, and you don't need to be touching something within range to affect it.

```
```

<div style="margin-bottom:10mm;">

&nbsp;

</div>

***Projectile Twin.*** When you hit a target with a ranged or thrown weapon, you can create a spectral version of it alongside as a bonus action, dealing the weapon's damage die again as psychic damage, for which you do not add your ability modifier.

***Nature's Psion.*** As an action, choose a creature within 60 feet of you that you can see. That creature must make an Intelligence saving throw. On a failure, they take 3d10 psychic damage as their mind warps and begins to be consumed by the primal psionics of nature.

#### Effortless Journey
Starting at 15th level, you can mystically move your body. You can forfeit any amount of your speed in order to teleport that same distance to an unoccupied location you can see. 

<img src='https://s-media-cache-ak0.pinimg.com/originals/8e/4c/07/8e4c0772f8ac4bbcb18092539867350b.jpg' 
 style='position:absolute;right:-10px;width:475px;
  bottom:-10px;z-index:-10;' />