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

/*
.phb#p1:after {
	background: none;
	background-image: none;
	content:"";
}
*/

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

# Archduke Mephistopheles of Cania
Mephistopheles, known as the "Lord of No Mercy" and the "Cold Lord", is the Archduke of Cania, the eighth layer of the Nine Hells.  Mephistopheles displays serenity, wisdom, and civility when in public. However, when in private, he flies into uncontrollable rages that destroy everything in his path. Mephistopheles has been the only devil in hell to openly tell Asmodeus to his face that he will rule hell in Asmodeus' stead. Nobody knows why the Lord of the Nine lets him exist, but he allows Mephistopheles to remain in his position mostly due to his more extreme hatred towards Baalzebul. The eternal struggle between those two maintain Asmodeus safely in his throne. Within his many plans, and his main reason for existence, Mephistopheles seeks to take Baalzebul's layer so he may gain enough power to ultimately challenge Asmodeus for the rulership of all the Nine Hells.  

Another of Mephistopheles' ambitions is that of becoming a deity. Unfortunately for him, many mortals confuse him with Asmodeus, a fact that frustrates Mephistopheles but amuses Asmodeus to no end. However, he seeks to distinguish himself based on promising his worshippers with the control of a magical substance of his own design. 

To the detriment of the ice devils that lived around Mephistar, Mephistopheles' citadel, he  secluded himself to create and perfect the usage of Hellfire: a white-glowed fire taken from the essense of Baator itself whose temperature exceeded any other form of fire. So high was its temperature that protection against heat, including complete immunity, was worthless against it. The increase in heat around Mephistar forced the ice devils to migrate to colder areas of the layer. Although other devils have learned to manipulate hellfire, none is as adept as Mephistopheles in its use. Combined with the arcane knowledge he possesses, the knowledge hidden and buried in the glaciers of Cania, and the now essense of hellfire, Mephistopheles is the only devil that can claim to be the closest thing to a rival to Asmodeus.

<img
src='https://66.media.tumblr.com/6fd0d6d035d8320785f61a1f44018fc5/tumblr_inline_o18ncc26xm1s2vv7d_540.jpg' style='position:absolute;top:93px;right:20px;width:438px;mix-blend-mode:multiply;'/>

<img
src='https://i.imgur.com/2e2Uq5X.png' style='position:absolute;top:5px;right:300px;width:438px;filter: grayscale(1);'/>

<img src='https://i.imgur.com/xAks2nP.png' style='position:absolute;width:325px;top:460px;right:300px;filter: grayscale(1);' />

<img 
src='https://i.imgur.com/L5SkUYg.png' style='position:absolute;width:325px;top:260px;right:350px;filter: grayscale(1);' />

<img 
src='https://i.imgur.com/QD3xJnb.png' style='position:absolute;width:325px;top:150px;right:370px;filter: grayscale(1);' />

<img 
src='https://i.imgur.com/5Q39oX5.png' style='position:absolute;width:350px;top:320px;right:350px;filter: grayscale(1);' />

<img 
src='https://i.imgur.com/5Q39oX5.png' style='position:absolute;width:350px;top:10px;right:360px;filter: grayscale(1);' />
<img 
src='https://i.imgur.com/5Q39oX5.png' style='position:absolute;width:350px;top:10px;right:340px;filter: grayscale(1);' />
<img 
src='https://i.imgur.com/5Q39oX5.png' style='position:absolute;width:350px;top:200px;right:360px;filter: grayscale(1);' />
<img 
src='https://i.imgur.com/5Q39oX5.png' style='position:absolute;width:350px;top:288px;right:360px;filter: grayscale(1);' />
<img 
src='https://i.imgur.com/5Q39oX5.png' style='position:absolute;width:350px;top:388px;right:360px;filter: grayscale(1);' />
<img 
src='https://i.imgur.com/5Q39oX5.png' style='position:absolute;width:350px;top:488px;right:360px;filter: grayscale(1);' />
<img 
src='https://i.imgur.com/5Q39oX5.png' style='position:absolute;width:350px;top:588px;right:300px;filter: grayscale(1);' />
<img 
src='https://i.imgur.com/AKEyJ6D.png' style='position:absolute;width:350px;top:100px;right:320px;filter: grayscale(1);' />
<img 
src='https://i.imgur.com/AKEyJ6D.png' style='position:absolute;width:350px;top:0px;right:300px;filter: grayscale(1);' />

<img 
src='https://i.imgur.com/AKEyJ6D.png' style='position:absolute;width:325px;right:300px;top:550px;filter: grayscale(1);' />

<br><br><br><br><br>Image by Wayne Reynolds

<div class='pageNumber auto'></div>

\page

___
___
> ## Archduke Mephistopheles of Cania
> *Large fiend, lawful evil*
>____
> - **Armor Class** 21 (natural armor)
> - **Hit Points** 522 (36d10 + 324)
>____
>|STR|DEX|CON|INT|WIS|CHA
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|27 (+8)|29 (+9)|28 (+9)|29 (+9)|27 (+8)|30 (+10)|
>____ 
> - **Saving Throws** Str +17, Dex +18, Int +18
> - **Skills** Athletics +17, Deception +19, Insight +17, Intimidation +19
> - **Damage Resistances** bludgeoning, piercing, and slashing from nonmagical attacks that aren't silvered
> - **Damage Immunities** cold, fire, poison
> - **Condition Immunities** charmed, exhaustion, frightened, poisoned
> - **Senses** truesight 120 ft., passive Perception 18
> - **Languages** Celestial, Common, Draconic, Infernal
> - **Challenge** 29 (135,000)
>___
> ***Fire Aura.*** At the start of each of Mephistopheles' turns, each creature that he chooses within 5 feet of him takes 7 (2d6) fire damage, and flammable objects in the area that aren't being worn or carried ignite. A creature that touches Mephistopheles or hits him with a melee attack while within 5 feet of him takes 7 (2d6) fire damage. 
>
> ***Hellfire.*** Mephistopheles' practice on hellfire reflects on the white flames he emits on his fire skills. Fire spells or effects that Mephistopheles creates can ignore resistance to fire damage or treat immunity to fire damage as resistance to fire damage. 
>
> ***Innate Spellcasting.*** Mephistopheles' innate spellcasting ability is Charisma (spell save DC 27). He can innately cast the following spells, requiring no material components:
>
> At will: *alter self  (can become Medium when changing his appearance), bane, fireball, invisibility (self only), wall of fire*
>
> 1/day each: *imprisonment, incendiary cloud, mass suggestion*
>
> ***Legendary Resistance (3/Day).*** If Mephistopheles fails a saving throw, he can choose to succeed instead. 
>
> ***Magic Resistance.*** Mephistopheles has advantage on saving throws against spells and other magical effects.
>
> ***Magic Weapon.*** Mephistopheles' weapon attacks are magical. 
>
> ***Regeneration.*** Mephistopheles regains 20 hit points at the start of his turn. If he takes radiant damage, this trait doesn't function at the start of his next turn. Mephistopheles dies only if he starts his turn with 0 hit points and doesn't regenerate.
>
><div style="margin-bottom:12mm;">&nbsp;</div>
>
> ### Actions
>
> ***Multiattack.*** Mephistopheles makes three attacks with Hurl Flame. He can substitute Ranseur with one of these attacks.
> 
> ***Ranseur.*** Melee or Ranged Weapon Attack: +17 to hit, reach 10 ft. or range 40/80 ft., one target. Hit: 15 (2d6 + 8) piercing damage, or 17 (2d8 + 8) piercing damage if used with two hands, plus 21 (6d6) fire or ice damage (Mephistopheles' choice). 
>
> ***Hurl Flame.*** Ranged Spell Attack: +19 to hit, range 150 ft., one target. Hit: 17 (5d6) fire damage. If the target is a flammable object that isn't being worn or carried, it also catches fire. 
>
> ***Overheat (Recharge 6).*** Mephistopheles engulfs himself in a 50-foot tall pillar of white-hot hellflames. Every creature in a 30-foot radius centered on Mephistopheles must make a DC 26 Dexterity saving throw or take 94 (21d8) fire damage, or half as much on a success. Mephistopheles automatically fails the saving throw. A creature killed by this fire turns to ashes. 
>
>Metal objects in the area glow red-hot. On a failed save a crature in physical contact with a metal weapon or suit of heavy or medium metal armor must succeed on a DC 26 Constitution saving throw or drop the object if it can. If it doesn't drop the object, it has disadvantage on attack rolls and ability checks until the start of its next turn. 
>
> ***Teleport.*** Mephistopheles' magically teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.
>
> ***Lair Actions.*** On initiative count 20 (losing against all ties), Mephistopheles can take a lair action to cause one of the following effects; he can't use the same effect two rounds in a row:
>
> * Mephistopheles casts wall of ice and he doens't need to concentrate on the spell, which ends on initiative count 20 of the next round. 
>
> * Mephistopheles reshapes the glaciers of Cania (as if the *move earth* spell but without concentration). The extent of any such changes can't exceed 20 feet. Changes take place on initiative count 20 on the next round. 
>
> * The cold surface within Mephistar ignites. Until a different lair action is used, creatures in the area on the ground take 14 (4d6) fire damage.
>
> ### Legendary Actions 
> Mephistopheles can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. Mephistopheles regains spent legendary actions at the start of his turn.
>
> **At-Will Spell.** Mephistopheles can cast one of his at-will spells.
> 
> **Summon Ice Devil (Costs 3 Actions).** Mephistopheles magically summons an ice devil with an ice spear. This ice devil appears in an unnocupied space within 60 feet of Mephistopheles, acts as Mephistopheles' ally, and can summon other devils if it has such power. The ice devil remains until Mephistopheles dies or until he dismisses it as an action.
>
> **Teleport.** Mephistopheles uses his Teleport action. 
>

<div class='pageNumber auto'></div>