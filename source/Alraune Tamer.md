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
    font-size: 5pt;
}

.smallerIT {
    font-size: 5pt;
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
	height : 296.8mm;
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
	background-size: 100px 100px; 
	background-repeat: no-repeat; 
	background-position: 0px calc(100% - 0px);
	height: 100px
}


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

.phb#p33 h1{
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

.phb {
	font-family: Athelas;
	background: url('D:/Users/Danno/Documents/dmbinder/aigr/source/imgs/sotdl-background-small.jpg');
	background-size: 100% 100%;
	background-repeat: no-repeat;
}

.phb h1{
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
	font-weight: 500;
	line-height: 1.1;
}

.phb h2{
	font-size: 170%;
}

.phb h3{
	font-size: 140%;
	border-bottom-style: none;
}

.phb h4{
	font-size: 125%;
}

.phb h5{
	font-size: 115%;
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
	font-size: 8pt;
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
	margin-bottom:8px;
	vertical-align: middle;
	font-size: 14pt;
	color: rgb(155,7,25);
	margin-right:1mm;
	margin-left:1mm;
	margin-top:2mm;
}

.phb .pageNumber.auto{
	bottom:22px;
}

.phb .pageNumber.auto::after{
	height:22px;
}

.phb .pageNumber.auto p{
	font-family: "First Order";
	font-size: 14pt;
	color: black;
	text-align: center;
}

.phb .pageNumber p{
	font-family: "First Order";
	font-size: 14pt;
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

</style>

# Alraune Tamer
A boy summons a powerful cactus that slams a foe into defeat, only to be surrounded by more bandits, His cactus suddenly grows and start to fight back.

A tiefling in the woods runs from a wolf, the wolf loses track of her only to see vegetation, the wolf leaves and the tiefling later emerges from her friendly hiding place.

Alraune tamers are masters of the arcane life held inside plant life, befriending spirits of the undead vegetation that once grew proudly around them.
### What are Alraunes?
Alraunes are spirits of undead plants, befriended by those with the knowledge and power to wield their power. Alraunes can be very mischevious, pulling small pranks on their owners, These creatures made of rock and plant matter, vaguely humanoid bodies and 3 holes where a face would be. They love to live in small spaces, such as a pot, a birdhouse, anywhere they can fit they love to hide in. They never stray far from the owner though, as they hold a strong bond to them. When an Alraune tamer has alraunes, they typically take the form of tiny humanoid spirits who's hair or apperance represents the plant they take the form of, and stay around the tamer either in a large clay pot, or just follow around the tamer.
### Alraune Tamer
Alraunes were once plants in life, and upon a natural death, the soul of the plant compresses into a sprite-like creature, roaming forests, swamps, sometimes even small towns if they have enough vegetation around. They are drawn to strong magical presences, which is why they partner with Alraune mages, the power to control these is not an easy one. Alraunes are not fully content with their current state, with the power of Alraune mages they can temporarily become a better form to help the owner in return for this thrill that was not granted previously in life.
### Green thumb
Alraune Tamers typically have some sort of connection to a forest or other vegetated area, like an abandoned building covered in vines, an old overgrown temple. Alraune tamers have lived near nature and discover the small friends that are Alraunes.




<img 
  src='https://i.pinimg.com/originals/e2/1a/ce/e21ace40e37b0796bc83acd2df14b8df.png' 
  style='position:absolute; top:200px; right:30px; width:300px' />
  ```
  ```
  <div class='descriptive'>

##### Flowers credit
Credit: Jill Robertson

</div>
  
<div class='pageNumber auto'></div>

\page

<div class='classTable wide'>

##### Alraune Tamer
| Level | Proficiency Bonus | Features |Alraune's known|  Active Alraunes
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1st | +2 | Alraune Caster | 4 | 2|
| 2nd | +2 | Alraune Specialty, Extensive Study| 4| 2  |
| 3rd | +2 | Mana boost | 5| 2 |
| 4th | +2 | Ability Score Improvement | 5 | 3 | 
| 5th | +3 |Ancient Secrets| 6|3|
| 6th | +3 | Overgrowth | 6 | 3 | 
| 7th | +3 | Alraune Specialty feature | 7| 3 | 
| 8th | +3 | Ability Score Improvements| 7| 3 |
| 9th | +4 |  Natural Travel | 8 | 4 |
| 10th | +4 | Alraune Specialty Feature | 8 | 4 |
| 11th | +4 |  ─|9 | 4 | 
| 12th | +4 | Ability Score Improvement | 9 | 4|
| 13th | +5 | — | 10 | 4 | 
| 14th | +5 | ─| 10 | 5 |
| 15th | +5 | Natural travel use | 11 | 5|
| 16th | +5 | Ability Score Improvement | 11 | 5 |
| 17th | +6 |  Alraune Specialty feature| 12 | 5| |
| 18th | +6 | ─ | 12 | 6 | 
| 19th | +6 | Ability Score Improvement | 13 | 6|
| 20th | +6 | Alraune Specialty Feature | 14 | 6 |

</div>

## Class Features
As an Alraune Tamer, you gain the following class features
#### Hit Points
___
- **Hit Dice:** 1d8 per Alraune tamer level
- **Hit Points at 1st Level:** 8 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d8 (or 5) + your Constitution modifier per Alraune tamer level after 1st

#### Proficiencies
___
- **Armor:** Leather
- **Weapons:** Simple weapons, shortswords, and hand crossbows 
- **Tools:** Herbalism kit, Caligrapher supplies, one gaming set of your choice
- **Saving Throws:** Intelligence, Wisdom
- **Skills:** Choose two from Arcana, Nature, Persuasion,Insight, and Survival

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
  - *(a)* any simple weapon or *(b)* A shortsword 
  - *(a)* A short bow and 20 arrows, or *(b)* any simple weapon
  - *(a)* Leather Armor
  - *(a)* A Herbalism kit, and Caligrapher supplies or *(b)* One gaming set of your choice, and 2 daggers
  - *(a)* Scholars back or *(b)* a diplomats pack
  - An Alraune Book

> ##### Multiclassing
> You must have an Intelligence score equal to 13 to multiclass into Alraune Tamer.

```
```

### Alraune Summoner
As a best friend to plants and plant spirits, they allow you to let you use their power and summon them into the best form they can take.

**Active Alraunes**

Alraunes can be summoned using your action within a range of 30ft, but only so many at a time. Adress the table above to see how many you get active at which level. An active Alraune counts as an Undead creature. To A summoned Alraune is invunerable and can not be targetted, However if the person who has summoned an Alraune takes damage they must make a Concentration check, found in the *Players Hand Book*, On a failed concentration check, the alraunes disperce in descending order of when you summoned them, for each concentration check you make. A sprouted Alraune lasts for 10 minutes or until dispelled.

**Alraune Types**

Alraunes have several types of uses, If an Alraune has a passive ability, such as producing a fruit or restraining, the alraune description will say how it works. However, If an alraune has an active ability, such as sudden healing or harming, than you must expend your action or bonus action to have the alraune activate. You may not use the same alruane on the same turn, unless you expend half its mana cost rounded up to do so. 

You may swap out one alraune each level up, provided you fall under the requirements for the alraune

**Alraune Power DC**

A DC set for if an Alraune requires a skill or ability check

8+your intelligence modifier+your profiency bonus

**Alraune Focus**

You require a Book of Alraunes in which you have field notes on the Alraunes you have chosen. You must have this in your hands in order to summon an Alraune. If lost or destroyed you must spend an hour per level re-writing your notes in a new book.

**Alraune Mana**

You have a certain amount of energy to summon these Alraunes, The amount you have equals twice your Alraune tamer level, and you may expand a certain amount of Mana to summon certain Alraunes. You regain all mana on a long rest.

### Alraune Specialty
At 2nd level, you focus on a certain type of Alraune to focus on, there are 4 kinds. Medical, Offensive, Scientific, and Bouquet. These focuses will give you features and a Trademark Alraune based on your option. You gain these features at 2nd, 7th, 10th, 17th, and 20th level.

<div class='pageNumber auto'></div>

\page

### Extensive Study
At 2nd level, During a short rest you may study your alraune book, and regain mana equal to your Alraune tamer level.

### Mana Boost
At 3rd level, you may add up your intelligence modifer+profiency bonus mana to a sprouted alraune, doing so adds the amount of mana to the creatures damage or healing for one minute. You may only use this feature once a long rest.
### Ability Score Improvement
When you reach 4th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. you may do so again at 8th, 12th, 16th, and 19th level. As normal, you can’t increase an ability score above 20 using this feature.

Using the optional feats rule, you can forgo taking this feature to take a feat of your choice instead.

### Ancient Secrets
At 5th level, The Alraunes trust and respect you much more now, they teach you more secrets of nature. You now gain the ability to speak with plants, with them being able to reply telepathically.

### Overgrowth
At 7th level, you gain the ability to push the power in your alraunes. As a action, you can boost a sprouted alraune. You may do so times equal to your Proficiency bonus per short rest. Doing so grants an additional ability to the chosen alraune, which is listed at the end of the Alraune description. You may not use more than one Overgrowth on an Alraune.


### Natural Travel
The alraune share how they travel through forests magically, At 9th level, you may cast *Travel via Plants* once without using material components, Regaining all uses on a long rest. You gain a second use at level 15.

<img 
  src='https://i.ya-webdesign.com/images/botanical-vector-wild-flower-12.png' 
  style='width:265px;margin-bottom:1mm;' />

Credit: stock image

## Alraune Specialties
The 3 branches of Alraune research, you choose which one you follow at 2nd level.

```
```

## Medical
Alraune mages of this branch study the healing properties of alraunes, being able to quickly and effectively heal their companions with their magical companions.

### Bonus Proficiencies
When you take this branch at  2nd level, you gain proficiency in Medicine and Investigation. You also gain the spell *Cure Wounds*, Intelligence is your spellcasting ability for this spell. You may cast this spell a number of times equal to your Intelligence modifier as a first level spell. You regain all uses on a long rest

### Trademark Alraune
The alraunes have brought you an additional Alraune, known as Berry, Which does not go against your number of Alraunes known. When you sprout this Alraune, it forms into a berry bush with 1d6 berries, a friendly creature may eat a berry as an action, or just take one as a bonus action. A berry heals for 1d6+your intelligence modifier. The die increases to 1d8 at 5th level,1d10 at 10th level and 1d12 at 15th level. Using Overgrowth adds additional healing die Alraune. The amount of berries summoned increases to 1d8 at 7th level, and 1d12 at 10th level. This Alraune costs 3 Mana to summon 
### Healing expert
At 7th level, whenever you heal someone with a spell, alraune, or a healing kit, and the health surpasses the targets Maximum HP, they gain temporary HP equal to the amount past the maximum HP.
### Harmless
At 10th level you learn how to alter the power used to summon alraunes for a small bit, you may choose one Alraune to sprout that deals damage, you may have it instead heal when it summons, it will heal for half of the damage it deals. for example, Cacto will have thorns which instead inject healing serum, Flower will have a healing potion spit. They will heal for the damage they are able to deal. You may do this twice a long rest.

### Tamer Medic
At 17th level, the alraune have taught you their healing ways. You now have the ability to heal magically. You may consume up to 20 mana to heal a creature a number of hit points equal to the mana used

### Grove for the Weary
At 20th level you increse your summoning powers. during a short rest you may summon a grove that grows in a 10ft sphere, anything withen the grove may rest. If a player chooses to use a hit die to heal, they will add your intelligence modifier for every die they roll. Every condition such as *stunned* and *unconcious* is cured withen the grove. *Petrification* can not be healed this way.


<div class='pageNumber auto'></div>

\page

<img 
  src='https://cdn.discordapp.com/attachments/570438235478687755/676855512779718667/image0.png' 
  style='width:325px' />
Credit: Me, u/himothebard (SeaSlugArtist)

## Offensive
These alraune mages learned how to protect and attack with alraunes, being a defender of the forest and people, or a ruthless criminal armed with mischevious and corrupt Alraunes. This branch knows how to pack a punch, as well as summon a punch.

### Bonus Proficiencies
You gain proficiency in one Martial Weapon of your choice.

### Trademark Alraune
at 2nd level, you gain the Durian Alraune, Which does not go against your Alraunes known. When you sprout this Alraune, It forms into a 3ft tall tree with durians sprouted into it. this tree will throw a Durian at the nearest hostile creature dealing 1d6+your intelligence modifier bludgeoning damage, using your intelligence modifier for the attack roll. The Durian tree makes its attack roll, using dexterity modifier and your proficiency bonus to add to its roll. Using Overgrowth will allow it to throw 2 Durians at once. This alraune costs 3 mana to summon

### Extra Attack
 at 7th level, Whenever you or an Alraune makes an attack roll, you may use your bonus action make a weapon attack.
 
### Harmful
At 10th level, When an Alraune you control hits with an attack, you may have it deal an additonal 2d4 damage, its damage type is determined by its origonal attack. You may use this ability twice a long rest.

### Durian Armor
At 17th level, When you summon your Durian you may instead summon it on yourself, you are covered in Fruity plates of armor, your AC becomes 15+your intelligence modifier. When an you are hit with a melee attack roll, the creature which hit you will take 1d6 Piercing damage.

### Thorn garden
At 20th level, you can summon a 10ft circle of thorny vines on the ground, this becomes rough terrain. Any hostile creature that enters this terrain must make a Dexterity savin throw combated by your Alraune Power DC, or be lashed by a thorny whip taking 2d10 Poison damage. Any creature that moves 5ft in this circle takes 1d10 piercing damage. You may use this twice a long rest.

```
```

## Scientific
This branch of Alraune mages focus on the utility and stimulating properties of Alraunes, how they can be used in our day to day life, and how they can solve problems.

### Bonus cantrips
You gain the mending and mage hand cantrips if you don't already have them. Intelligence is your ability for these cantrips.

### Trademark Alraune

Your Alraunes want to help you out daily as well! You are trusted by the Vines alraune, Which does not go against your Alraunes Known. This Alraune, when sprouted, will grow into either a series of vines or a single vine. This vine can be used to wrap something temporarily or use several vines to form a ladder. , the Overgrowth feature will allow it to grow thorns, and become difficult terrain for hostile creatures, dealing 1d4 piercing damage to any hostile creature while they move to throw the vine path. If you use this alraune to restrain a creature, they must make  a dexterity saving throw against your Alraune power DC. This alraune costs 2 Mana

### Perfect Form
You study how the alraunes work and how to improve upon them, making them very effective. at 7th level, you can use an action to have an Alraunes damage or healing rolls be the maximum roll for 2 rounds. You may use this feature twice a long rest

### Modifications
Through your studies, you now understand Alraune anatomy and physiology. At 10th level, as an action you can do one of the following to your alraune:
- Switch damage types with another alraune for one minute
- Increase range of the Alraune by 10ft
- Have it gain a movement speed of 15ft, giving it legs.

You may use this ability once a long rest

### Geometrical Growth
At 17th level, you are able to create a 10ft wide pentagon around you, as an action you may summon 5 Alraunes at once, one being on each corner. You may only do this once a long rest.

### To a Science
At 20th level, your study of Alraunes has had you find a breakthrough. Now you may spend a bonus action to pull up information on one of your alraunes, on your next turn, you may summon an overgrowthed version of that Alraune without using one of your uses. You may do this three times a long rest.

## Alraunes
A List of Alraunes you may use, And how much they cost

### Aloe
This Alraune forms a 1/2 foot tall Aloe plant, which can be used to heal burns. as well as heal other wounds. This gel heals for 1d4+ your Intelligence modifier,On top of this, you gain resistance to fire damage for the next hour. Overgrowth changes the healing die to 1d12.
This Alraune costs 2 mana

### Apple of Death
*Prerequisite: 7th level Alraune Tamer*

This little apple is highly toxic, the 3ft tree it is summoned from isn't any better. Any creature that comes into physical contact with this tree will be dealt 1d6 poison damage on a failed Constitution save against your Alraune Power DC. Eating the apple will put the consumer under the *Poisoned* condition after a failed saving throw, using the same DC as before. Overgrowth Allows the tree the ability to throw apples at a target, dealing 1d6 bludgeoning damage.
This alraune costs 8 Mana

<div class='pageNumber auto'></div>

\page

### Bell Flower
This alraune forms a bouquet of Bellflowers or campanulas. These bells will play a harmonious song, giving a single friendly creature that can hear gain a 1d4 that can be used to increase the roll of any saving throw, attack, or ability check. Overgrowth allows for up to 4 friendly creatures to be in the effects of bardic inspiration(1d6) instead of the *bless* spell. The die increases to 1d6 at 3rd level, 1d8 at 5th level, and 1d10 at 7th level.
This alraune costs 2 mana

### Bleeding Heart
*Prerequisite: Offensive Alraune study*

This Alraune makes a large heart-shaped flower, growing to 3ft, the single bud blossoms into a Bleeding Heart flower. This Alraune can swing an appendage coming from the open heart petals, dealing 1d8 Bludgeoning damage, as well every creature within 5ft take 1d4 damage for 1d8 rounds after a failed constitution save against your Alraune Power DC, Creatures who failed may make another saving throw at the end of their turn. Overgrowth increases the damage die to 2d4.
This alraune costs 3 mana
### Bush
This Alraune forms a 5ft spherical bush, which you can use to hide in. This Alraune lasts for 10 minutes or until dismissed. You can use this Bush as full cover, and you have advantage on stealth checks if you use this Alraune in a forest or other heavily vegetated area. Overgrowth on this Alraune will make it able to hide 4 creatures under it.
This alraune costs 3 Mana

### Cacto
A cactus Alraune that sprouts a thick cactus standing at 2 feet, with 2 very opposable appendages. The cactus will hit the closest hostile creature within 5ft with an appendage, dealing 1d6+You Intelligence modifier bludgeoning or piercing damage.  Using Overgrowth on this alraune will give it an extra attack.
This alraune costs 1 Mana
### Cherry bomb
*Prerequisite: 5th level Alraune Tamer* 

This Alraune forms into a Cherry tree, don't eat these though. These 1d12 Cherrys can be thrown up to 20 feet, upon impact every creature within 10 ft of the explosion must make a Dexterity saving throw against your Alraune Power DC, or be dealt 1d12 Bludgeoning damage. Using overgrowth extended the throw range to 30 feet and deals an additional 1d10 Bludgeoning damage.
This alraune costs 5 mana

### Coffee Bean
*Prerequisite: 7th level Alraune Tamer*

This Alraune sprouts a small coffee plant with 5 beans, standing at 1ft. As an action, Anyone can eat a bean and gain advantage on all dexterity checks and saving throws, as well as temporary HP equal to the consumers Constitution modifier,to a minimum of 1, for one minute. Overgrowth will allow the Alraune to grow an additional 5 beans. these effects do not stack.
This alraune costs 5 Mana

### Cucamelon
*Prerequisite: 13th level Alraune Tamer*

This Alraune sprouts 2 barrel-sized melons, covered in spikes. you can roll this at an enemy along with the sprouting. the enemy must make a Strength saving throw against your Alraune Power DC, on a failed save they are knocked prone and take 3d12 bludgeoning damage, and half as much on a successful one. if the melon hits a wall, it explodes and the fruit can be used to heal for 2d6 health. Overgrowth changes the damage done to 5d12, and it can heal for 4d6.
This Alraune costs 8 Mana

```
```

### Dandelion
*Prerequisite: 5th level Alraune Tamer*

Produces a white dandelion plant, on a command word it's 20 out of the 100 spores fly off and bite down onto a target, these spores have sharp teeth that clamp down onto a target. when all 100 are gone the plant will be dismissed. The target must make a Dexterity saving throw against your Alraune Power DC or take 1d12 piercing damage. can easily be removed with a DC 10 Strength check. or by taking fire damage. Overgrowth deals 1d12 piercing damage each round, if they are still attached.
This alraune costs 4 mana

### Deadly Nightshade
*Prerequisite: 5th level Alraune Tamer*


This 2ft Alraune produces 1d6 small blackberries, which are highly toxic dealing 2d8 poison damage when a creature first eats this, and then an additional 2d4 poison damage over 3 rounds. The berries can be turned into a potent poison as well. Overgrowth will add, along with the initial damage, the consumer automatically gains a failed death save which goes into effect next time they fall to 0 hp.
This Alraune costs 7 mana

### Dragon Lily
*Prerequisite: 4th level Alraune tamer*

This Alraune forms a dragon lily,  growing to 2ft tall. When you sprout this Alraune, choose a damage type from the *Dragonborn* heritage table. As an action, this creature will shoot the chosen damage type at the nearest hostile creature, which will make a dexterity saving throw against your alraune power DC or take 1d6+your intelligence modifier of the chosen type.  Overgrowth allows this alraune to grow an additional flower, which shares a turn with the first and can deal different damage than the first.
This Alraune costs 5 mana

### Ghost flower
*Prerequisite: 4th Level*

This alraune sprouts small white flowers which resemble a Bed sheet ghost. Upon summoning, choose one creature you can see, and that is able to see you. Have it make a wisdom saving throw against your Alraune Power DC , or otherwise it is *Frightend*.  The creature may reroll the saving throw at the end of its turn. Overgrowth adds 1d6 Psychic damage to the failed save.
This Alraune costs 5 mana

### Heart-Shroom
*Prerequisite: 3rd level Alraune Tamer*

A mushroom Alraune with heart patterns across it, standing at 2 feet tall. This alraune releases spores which improve someone's mood, as a bonus action, have a creature of your choice make a charisma save against your Alraune Power DC, on a failed save the creatures calms down, as if under the effects of *Calm Emotions*. Overgrowth makes the target make the save with disadvantage.
This alraunce costs 4 mana.

### Hibuscus
*Prerequisite: 3rd level alraune tamer*

A viney flower Alraune, standing at 2 1/2 feet tall, representing a Hibiscus flower. This Alraune on its turn can shoot up to 30ft, a line of acid, which deals 2d4+your Intelligence modifier on a hit. Overgrowth will extend its range to 50ft and increase the damage die to 3d4.
This alraune costs 6 mana

### HorseRadish
*Prerequisite: 6th level Alraune Tamer*

The alraune forms a horse shaped plant made of horseradish root, and may support 2 medium sized creatues. This Alraune acts much like a *Horse* and uses the stat block of a *Riding Horse*, this Alraune lasts for one day. Overgrowth: Elephantradish, forms an elephant shaped plant that may support up to 6 medium sized creatures. This alruane costs 9 mana

<div class='pageNumber auto'></div>

\page

### Hysteria Tree
*Prerequite: 8th level*

A black wood tree with winding branches standing at 7ft tall, decorated with red vine like flowers handing off the branches. Anything within 10ft of this tree must make a *Charisma* Saving throw against your Alraune Power DC or be *Frightend* by the tree. A creature may repeat this saving throw at the end of its turn. Overgrowth will transform this tree into a *Wisteria* tree, keeping the previous saving throws.
This alraunce costs 8 mana

### Irminsul
*Prerequisite: 20th level Alraune Tamer*

A child of Yggdrasil themself, this alraune sprouted will produce a large dark grey tree that is 10ft high with rainbow-like leaves that cover an area of 8ft, the light that shines through leaves a colorful light all around, any allies in this trees light will receive 6d12+your Intelligence modifier healing, any leftover points turn into temporary hitpoints. Any undead will take radiant damage for the same amount. Overgrowth allows allies to gain 20 temporary HP.
This alraunce costs 30 mana

### ElderBerry
*Prerequisite: 3rd level Alraune*

A relative to *Berry* This alruane sports a flower like plant, with 10 small black berries growing at the ends of it. Each berry heals for 1d4 health, however eatting 4  will deal 1d8 poison damage instead. so be wary. Overgrowth has the berries heal for 1d6.
This alraune costs 5 mana

### Flower crown
*Prerequisite: 3rd level Alraune Tamer*

This alraune grows in your hair and takes the form of any flowers you like. While in your hair this Alraune gives you profiency on *Performance*,*Deception* and *Persuasion* checks. Overgrowth lets you add double your proficiency bonus to the rolls or roll with advantage.
This alraune costs 4 mana

### Lily pad
*Prerequisite: 5th level Alraune Tamer*

This Alraune will form a lily pad which is 10ft in diameter. you must be near a body of water big enough to hold it. This lily pad can hold 3 medium-sized creatures and can be used as a raft. This lilypad lasts until you dismiss it, however, if used in saltwater it will only be able to last for 20 minutes. Overgrowth allows this alraune to be able to hold up to 5 medium-sized creatures.
This alraune costs 5 mana


### Mandrake
*Prerequisite: 3rd level Alraune Tamer*

This Alraune is a thick root, showing only has 2 large leaves when initially sprouted. At the casters command the mandrake will come out of the ground and scream. Every creature within a 20ft sphere must make a Constitution save against your Alraune Power DC, on a failed save, each creature who failed takes 1d8+ your Intelligene modifier thunder damage. Overgrowth will also have give creatures who failed the saving throw the *Frightend* effect against the caster.
This alraune costs 3 mana

### Milk Thistle
This Alraune sports purple thistles, which secrete a healing liquid. This alraunes lasts for 3 rounds before dissappearing, during this time, as an action a creature may touch the plant, regaining 1d8 health, and an addiotnal 1d4 health over the course of 2 rounds. Overgrwoth extends the lingering healing to 4 rounds.
This alraune costs 2 mana

```
```

### Moss
*Prerequisite: 5th level Alraume Tamer*

This Alraune can be grown on armor, forming a mossy coat over it. When you use this Alraune on any armor that is being worn, whoever is wearing the armor is granted temporary HP equal to Your 5+Your Alraune Tamer level, and upon the Temporary HP disappearing, so does the moss. This Alraune has +3 in Strength saving throws. Overgrowth allows an additional +2 AC.
This alraune costs 4 mana

### Necrovine
*Prerequisite: 10th level Alraune Tamer*

This Alraune creates vines that wrap around and into a nearby corpse, turning it into a gross puppet. This Alraune now acts as a *Zombie* for stats, and will attack on its own. The zombie takes its initative right after yours, as if you had cast *Animate Dead* You may not have more than 1 active at a time, Unless you use Overgrowth. Overgrowth allows 2 Necrovines at the same time.
This alraune costs 11 mana

### Purple Worm Root
*Prerequisite: 5th level Alraune Tamer*

This Alraune forms worm-like roots that tunnel through the ground. You choose a target within 20ft, On a failed dexterity saving throw, the Purple Worm root will burrow and strike it from below dealing 1d8+Your Intelligence Modifier piercing damage, and half as much damage on a successful save.Once the Purple Worm Root attacks a target, It will stay in that location, and to attack you must choose a target within 20ft of its current location Overgrowth gives the root a range of 40ft.
This alruane costs  4 mana

### Rafflesia
*Prerequisite: 5th level Alraune Tamer*

This Alraune forms a 4ft wide Rafflesia flower and gives off a nasty smell of rotting meat. As an action, you can make The flower give off horrid spores, every creature withen 5ft of this plant must make a Constituition saving throw against your Alraune Power DC, On a failure, the target is now *poisoned*. Overgrowth allows those affected by the failed saving throw to also take 1d6 poison damage
This alraune costs 10 mana

### Red cage fungus
*Prerequisite: 10th level*

This Alraune forms a 5ft wide and 7ft tall bright red cage made of dense fungus, which requires a Strengh check against your Alraune Power DC to break as an action. You may summon this Alraune around a creature, trapping them in one location for the duration, or until it is broken. Overgrowth puts a barrier that dosent allow spells to leave the cage. This alraune costs 10 mana.
### Rose
*Prerequisite: 3rd level Alraune tamer*

This Alraune produces a small bouquet of 10 Roses, you may pick one and throw it at a target, on a hit it will deal 1d8+Your Intelligence modifier piercing damage. The rose disappears on impact. Overgrowth summons an additional 3 blue roses, which can make a target fall asleep on a hit, if they fail a Constitution saving throw against your Alaune Power DC.
This alraune costs 4 mana.

### Sleepy shroom
*Prerequisite: 6th level Alraune tamer*

This alraune forms a mushroom with a 1/2 foot wide cap. As an action This alraune will release spores in a 10ft radius, have every creature within range make a Constitution saving throw against your Alraune Power DC, on a failed save the target falls *Prone* and is considered *Incapacitated* until they take damage. Overgrowth gives the target disadvantage.
This alraune costs 8 mana

<div class='pageNumber auto'></div>

\page

### Strangler Fig
*Prerequisite: 14th level Alraune Tamer*

This alraune forms vines that tightly wrap around a targets neck, Have a target creature make a Dexterity saving throw against your Alraune Power DC, on a failed save the creature will take 1d10 Bludgeoning damage and be considered *Grappled*. it takes 1d6 bludgeoning damage every round it is *grappled*.This alraune only lasts for 5 rounds. Overgrowth sets the DC to 18.
This alraune costs 8 mana
### Treehut
*Prerequisite: 7th level Alraune Tamer*

This alraune summons a thick hollow tree with a door, a 10ft by 10ft room that is fully furnished with beds, nightstands, and a cooking pot. This will last for 1 night, where it disappears in the morning. there must be a 20ft sphere of free space to sprout this alraune. Overgrowth adds a second story, which has a game table and a telescope with a window.
This alraune costs 10 mana

### Wall-Nut
*Prerequisite: 7th level Alraune Tamer*

This Alraune encloses you in a 10ft dome made of walnuts, The walnut has a AC of 15 and HP of 16, and counts of full cover. Overgrowth adds spikes to the outside, harming any creatures who attack the shell for 1d6 piercing damage.
This alruane costs 5 mana 
### Water Lily
*Prerequisite: 7th level Alraune*

You must summon this alraune in water. This Alraune sprouts a water lily, a beautiful flower. using a command word on this alraune, chosen by the Alraune Tamer who summoned it, shall give up to a number of creatures equal to your Intelligence modifier the ability to breath water for 10 minutes.
This alraune costs 6 mana

### Wisteria Tree
*Prerequisite: 11th level Alraune Tamer*

This tree stands 7ft tall, with winding branches all decorated with string lights and purple vine-like flowers. Anything within 10ft of this tree must make a *Charisma* saving throw against your Alraune Power DC, on a failed save the targets are *Charmed* by you, or a party member of your choice. Using Overgrowth, you may use an action to instead change this to a *Hysteria* tree, keeping the same saving throws
This alraune costs 8 mana

### Witch Hazel
*Prerequisite: 3rd level Alraune Tamer*

This Alraune sprouts yellow flowers, one of which sports a nice witch hat!! You select a creature within 30ft that you can see and on your turn, Witch Hazel will lay a curse on a creature, Have a creature make a saving throw based on the curse, which is labeled on the curse description, on a failure, roll a 1d6 on the table below to see which curse is put on the creature. If the curse lasts multiple rounds, they may repeat the saving throw to undo the curse. Overgrowth doubles the time to the curse if any. The Curses do not stack, only one creature at a time may be cursed. The creature repeats the saving throw at the end of its turn. This alraune costs 2 mana


##### Curse
| roll | Curse Type |
|:----:|:-------------|
| 1 |Lathargic: half movement speed for 1d4 rounds [Contitution saving throw] |
| 2 | Cloudy Head: Stunned for 2 rounds[Constitution Saving Throw] |
| 3 | Atrophy: Creature has disadvantage on Strength saving throws [Constitution Saving throw]|
| 4 | Insane: Creature attacks nearest creature [Wisdom saving throw]|
| 5 | Paper Skin: Creature is vunerable to bludgoning, slashing, and pierceing damage for 1d4 rounds[Constitution Saving Throw]|
| 6 | Sensory Deprivation: Creature is blinded and deafend for 1d6 rounds[Constitution Saving Throw]|

<div class='pageNumber auto'></div>