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

  .phb#p1{ text-align:center; }
  .phb#p1:after{ display:none; }

  .phb#p1 h3, .phb#p1 h6{
      color:white;
      text-align: center;
      margin-left:20mm;
      margin-right:20mm;
  }

</style>

<div style='margin-top:6mm;'>

# A Werewolf: The Apocalypse Conversion</br>for D&D 5th Edition

</div>

<div class='wide' style='margin-top:230mm;'>

### Be the Monster

###### Illustration Credited to: Ron Spencer

<img 
  src='D:\Users\Danno\Documents\dmbinder\hb\source\imgs\Magic-Weapon.png' 
  style='position:absolute; top:0px;left:0px;right:0px;bottom:0px;height:297.5mm;z-index:-5;' />

<img 
  src='D:\Users\Danno\Documents\dmbinder\hb\source\imgs\WtA.png' 
  style='position:absolute; top:0px;left:0px;right:0px;bottom:0px;height:297.5mm;z-index:-10;' />

</div>

\page

<div class='footnote'>PART 1 | GAROU</div>

<div class='pageNumber auto'></div>

# Garou
Depending on who you talk to, Garou could have descended from many things.  Some of the wise believe the Garou were once an Ancient Fey race, and led the charge to battle the Legions of the Abyss, (the Wyrm) only to find they were shut out from the Realm of the Fey.  And without having the army necessary to fight in the Wyrm, they were stuck in the Material Realm, and evolved their species into Garou of today.
	Some werewolves themselves believe they once held dominance over the natural world. Created by Gaia to be the world’s protectors, they passed along their gifts to their children.  Some chose to mate with humanity, favoring their intelligence and adaptability.  Others chose to take mates from wolves, embracing their pack mentality and tenacity.  The Garou acted as a check on the growth of societies, but protected it as well.  They tried to teach humanity to live in harmony with the world, and to find balance. </p><br>
    <p>What happened?</p><p><br>
Every tribe has its own explanation, but they all do agree on one thing is that the Garou became extremely aggressive in policing humanity.  They called it the Impergium, it was a time of violence and terror.  Humanity became terrified of the wilderness and of wolves in particular; that horror follows them even today, much to the Garou’s chagrin.  Humans and some other races gathered together in settlements to keep each other safe at night.  Those settlements became farming communities, and then cities.  And all along the way, the Garou would steal into the communities and take the weakest(or the most brazen, or the least reverent -- the criteria for who died under the moon were never set in stone).  Garou believes this is what scarred humanity to the depths of their very being.  And the effects of this is what Garou call Delirium today, some races when seeing the Crinos form of a Garou, can be terrorized with fear.
Some Garou tell it differently.</p><br>
<p>They claim that gathering into settlements wasn’t humanity’s idea at all.  It was the werewolves who pushed them into these groups, these herds, to keep a better eye on their breeding stock.  But they developed agriculture, and eventually cities as a response to this, but if not for the Garou, they might still be a nomadic species.  The problem is, stories of the Garou are an oral tradition, part history and part legend, so the “truth”remains unclear.
Stories say that anyone bitten by a werewolf will become one himself.  This is not entirely true, while certain Garou can call upon an ancestor spirit to bond with the body of man, the effects are temporary. </p><br><p>  To the Garou, the truth about the Cursed Werewolves that cannot control their rage, and lost their way is from an old tribe called the White Howlers, who decided to travel the depths of the realms to fight the Wyrm themselves, and came back twisted, their spirits broken, as well as their link to Gaia and Luna.  They were no longer blessed by Luna and the Father Wolf, they came back Cursed.  The Garou call them Black Spiral Dancers, but most of society just calls them Lycanthropes, or werewolves.  These days, the Garou have decided to come out of hiding, try to write some of the wrongs of their ancestors, but the tribes cannot all agree on the best way to show humanity the way.  Some are tasked with joining packs of other races.  To even live amongst them, learn their ways, help understand each other.  Others break off from the traditional ways, and just want to experience life outside Garou Nation all together, and find adventure.  Some Garou find strategic advantages in grouping up with other races and kind, to take down minions of the Wyrm.</p>
<br>

***Are you ready to be the Monster...?***




\page

<div class='pageNumber auto'></div>

<div class='footnote'>PART 1 | GAROU & BREEDS</div>

# Part One: Choose Your Breed
## The Three Ancient Spirits

### The Weaver
The first Spirit, this became the Manifestation and symbol of order and pattern.  It is constantly weaving its webs into more and more patterns, in the deepest parts of the Realms, the more it builds, the more civilizations expand.  And her patterns grow further.  Many examples of the Weaver’s influence can be found on the material plane.  Many races have learned to tap into the weaver’s webs and create many things from it.

### The Wyld
If the Weaver is the one to create structures, the Wyld is the Chaotic Energy spirit that gives them life.  It is the manifestation and symbol of pure change, the chaos of transmutation and elemental force.  If the Wizard pulls on the Weavers web to cast it’s fireball, it is the Wyld’s magic that gives it fire.  It's what makes creations of the Weaver evolve, live, and adapt.

### The Wyrm
Garou Legend believes the Wyrm was a necessity to balance the creations of the Weaver and the Chaotic energy of the Wyld. The great wyrm serpent tied between the weaver and the Wyld.  It calmed the energy of the wyld, it destroyed creations of the Weaver, so it can be recycled to build new structures.  But the weaver did not like the Wyrm destroying its creations all the time, it did not see the logic to it.  And trapped the Wyrm into the very depths of the Realms, and calcified its webs so the wyrm could not escape.  They wyrm’s mind twisted and shattered from the horrors of those depths, and spewed its horrible creations out to get back at the weaver.

The Garou believe this marked the beginning of the end, and one day, the wyrm will break free and destroy and get its revenge and destroy all of the weavers creations, and all of the Cosmos.

### Breed, Auspice, Tribe
* **Breed**  is the birth form of the Garou.  Some are born to a human (or similar) parent and a Garou parent; others to a wolf and a Garou.  Still others are born to bloodlines of Kinfolk--people who possess Garou blood but are not shapechangers themselves--and may not even know of their strange heritage.  And some werewolves are born to Garou-Garou matings, though theirs is a difficult lot.
* **Auspice** is the moon phase of a Garou’s birth.  The light of Luna affects them, granting them specific blessings that will govern their path in life.  The brighter the birth moon, the more Rage the Garou will feel.  Those born under the full moon are the most furious of all -- the warriors among a warrior people.
* **Tribe** is a social unit as well as a family.  A Garou may come to a tribe for ideological reasons, but most are descended from a tribe's bloodlines.  A tribe defines itself by its Kin, its territory, its ideology and its tribal totem.
But while these three things can define a Garou, a fourth bond exists--the bond of the pack.  Garou's packmates are like immediate family, best friends, and brothers-in-arms all at once.  They have very little relations to their Wyrm Tainted Lycanthrope cousins, cursed by the Wyrm.  The Garou are half spirit, half flesh, protectors of Gaia, blessed by Luna’s Spirit.  They are not a cursed Lupine, like their distant cousins, but a blessed union, by the Father Wolf Spirit and Luna.  

```
```

## The Three Breeds
### Homid

<p> A homid werewolf grows up in society, but is never truly integrated with it.  Pre-Change werewolves are prone to behavioral problems and sensory quirks that make them strange.  They understand that society has rules and has a certain set of expectations, but they often find them strange, unfair, or just annoying.  Some mask it better than others, but the end result is that when the Change finally comes, amidst the blood and the death and the Rage, some part of the werewolf feels relief at finally being with her People.</p>  
<p>That isn't to say that the transition is easy.  Years of education and indoctrination within the world die hard, and what kind of upbringing the werewolf has had can make all the difference.  If the werewolf’s father or mother was Kinfolk (and knew it), for instance, the cub might have had things a little easier.  The Kinfolk parent might not have given full disclosure, but just instilled the child with a love of and respect for the natural world.  Understanding, even in abstract terms, that Gaia can see and feel what people do makes for less guilt and horror when the Change comes and the Garou sees exactly how much damage the races are doing to Gaia.</p>
<p>Some homid Garou, though, feel that although some races are dangerous to the planet, they are also the only species that can save it.  As such, for the Garou to have any meaningful impact at all, they have to be able to move in society’s circles.  Simce homid werewolves are best suited to understand and work within society, and they should, by default, be the leaders of werewolves.  The discussion is moot in most tribes, since the numbers dictate the leaders.  But the effect of this imbalance is obvious.  The Garou are losing touch with their wolf blood, and this can only herald disaster for the People.

You were born human and raised by human parents.(or whichever base race you choose)  You were not aware of your heritage until you experienced the First Change with the onset of adulthood(or shortly before).  It’s very likely that you were completely unaware of your family’s nature as Kinfolk(or of your Garou parent’s nature)

* +1 towards 2 ability scores of your choice
* gain proficiency in one skill of your choice
* Gain one feat of your choice.
* Not vulnerable to silver in Homid Form only
* **Can take the Rite of Passage as a special Garou feat that allows their personal belongings to adjust with them when they shapeshift**

### Metis
The Garou Nation could have a veritable army of warriors within a few years.  The child of two werewolves, after all, is always a werewolf.  They grow up with an instinctive understanding of Garou society and the spirit world, as well as an affinity toward shapeshifting.  It would seem an easy solution.

Except, of course, for the fact that a child of two werewolves, a metis, is always deformed in some way.  Some are born missing limbs, some are born disfigured and hideous, and some are born mad.  They are born into the world in crinos form, and are always sterile, and cannot pass on the Garou “gift”.  Generations ago they would have been destroyed. Metis undergo the First change anywhere from their first year of life to the onset of puberty.  For this reason, they are raised within a sept, away from society.  This makes them well versed in Garou society by the time they are ready to undergo a Rite of Passage.
  
That doesn't mean their life is easy, they are not coddled, and mentoring a Metis is usually viewed as a form of punishment.  It's no wonder, then, that Metis tend to be resentful and paranoid.  The Litany flat out condemns them, and any recitation of the Litany with a metis in attendance is a least somewhat uncomfortable.  Most metis grow up bitter, and while some might learn to blend in among society, they never really have a place to belong.

<div class='pageNumber auto'></div>

\page

* Your natural form is Crinos
* +2 Str +1 Con
* gain proficiency in 2 skills of your choice
* **Natural Battleform.** *The Metis is naturally comfortable in crinos form, and naturally uncomfortable in his other forms.  Shapeshifting in Crinos form is considered instant for combat purposes.  Additionally, shapeshifting in any other form other than crinos, is done so at disadvantage.*  (Con check DC 10 to shift from crinos)
* Vulnerability to Silver in **any** form 
* **Deformity**  *Some examples, Albino, Bad vision, Fits of Madness, Hairless, Horns, Hunchback, No sense of Smell, No tail.* At least one of these or similar must be chosen during character creation.  Both of your parents are Garou, and they broke the Litany when they conceived you.  You were raised within a sept among werewolves, and you understand Garou culture more deeply than either homids or Lupus.  Metis are usually socially awkward in public gatherings because of this as well. 

### Lupus
None are closer to nature and the hidden face of Gaia than you are.  You were born a precocious pup, already showing remarkable intelligence above that of your siblings.  When the Change overcame you, and you discovered your true nature, the world itself became something you had never expected.
  
Lupus are quite capable of abstract thought, but much of their experience with the concepts governed by such thought comes after the First Change.  They pick up the basics of Garou speech very quickly, and the basics of other languages with surprising speed , but the small nuances and connotations frequently elude them.  They are accustomed to the socialization of a pack, not aof a greater society, which can be particularly problematic if they were raised in a traditional wolf pack, which is more of a nuclear family than anything else. 
  
You were born a wolf and raised in the wilds among wolves.  Until you were almost full-grown(two years or so), you were unaware of your true nature as a Garou.  You aren’t as sophisticated as a homid, but you have stronger faith in your instincts.
  
* +2 Dex +10 speed(all forms) 
* gain proficiency in Survival
* gain one feat of your choice
* Not vulnerable to silver in Lupus Form

```
```

<img 
  src='https://imgur.com/ZRFoXfC.jpg' 
  style='width:300px' />

*Image source from: https://vignette.wikia.nocookie.net/whitewolf/images/3/36/Wendigo_%28Oeste_selvagem_1%29.jpg/revision/latest?cb=20181227192615*
  Onyx Path, Werewolf: the Apocalypse

<div class='pageNumber auto'></div>

<div class='footnote'>PART 1 | BREEDS</div>


\page

<div class='pageNumber auto'></div>

<div class='footnote'>PART 1 | GAROU TRAITS</div>

## Garou Traits
Garou shares certain traits based on the hybrid race chosen.  The stats here replace those existing traits of the chosen race.  For, example, a dwarf Garou, would not receive typical dwarf race abilities, they would instead be replaced with the following.

**Age.** Varies on the race chosen.  Typical age span for race chosen, any modifiers are replaced by the breed traits.

**Size.**  Various sizes depend on form.  

* #### Homid 
*within the normal limits of race chosen*
* #### Crinos
*add 3ft, add 300lbs from homid* 
* #### Lupus
*minus 3ft from homid/minus 50lbs from homid*

**Speed** Base is typical of races chosen naturally in Homid.  Crinos +10 ***from Homid***,  and Lupus base speed is 50.

**Darkvision** 60ft

**Languages.** Can speak, read, write Common and one extra language of your choice.  ***All forms are capable of speaking languages, although certain forms can be challenging.***

**Garou Feat.** All Garou have the option to take ***Rite of Talisman Dedication*** as a Feat and a +1 to an ability score at either 4th, 8th,12th,16th,19th level, if not provided for in their class.

##### <u>Rite of Talisman Dedication Feat</u>
<p>The Garou can choose pieces of equipment that phase with him when switching forms.  This rite allows a Garou to bind objects to her body, allowing them to fit her various forms *(pants will grow to accommodate the Crinos form rather than splitting at the seams, also useful if a Garou ever decides to don armor)*  Fetishes such as Klaives remain with the werewolf in all forms automatically without this rite. </p>
<p>The character may never have more objects bout to himself than his Gnosis score.  Conceptually linked groups of objects may count as a single object.  A set of clothing is considered one object, rather than one shirt, 2 socks, ect.   Objects will generally resize themselves to accommodate the character’s various forms, but may simply meld with the character in forms where they can be of no use- for example, a knife may become a knife-shaped tattoo in Lupus.  

## Garou Forms
*Image credited to Ron Spencer*
<img 
  src='https://imgur.com/4v8f0x6.jpg' 
  style='width:325px;mix-blend-mode:darken' />

**Homid.** Base stats and AC.***(no claw or bite)***

**Chrinos.** Base stats +4 STR,+1 temp HP/level x2,+2 AC, Speed: +10

**Lupus.**  Base stats +1 STR, +3 AC, Speed:50

**Keen Hearing and Smell.**  The Garou has advantage on Wisdom *(Perception)* checks that rely on hearing or smell.

##### Natural Weapons. 

***Bite***   Considered magical.  1d8+STR piercing ***Except Homid***

***Claw*** Considered magical 2d4+STR slashing damage. ***Except Homid***

<div class='pageNumber auto'></div>

\page

# The Beast and Spirit
Every Garou has a pool system of Rage and Gnosis they can call upon.  They are the blessings of the Father Wolf, and the Luna Spirit.  Garou themselves are half  flesh, half spirit.  They are the children that resulted in the unification of the Father Wolf and Luna, the moon Goddess.

### Garou Rage
<p>Every Garou is a crucible for Gaia’s primal anger--her Rage at the pillage of the world at the hands of the Wyrm.  This Rage is a force of mindless violence, a constant slow-motion path of unthinking destruction and violence that each and every Garou must keep control of lest it consume her.  Rage mixes instinctual cunning and hunting ability with savage bloodlust and unpredictable horror.</p>
<p>Much of a Garou’s struggle comes from a never-ending battle with the Rage each werewolf feels.  The Beast is never far from their thoughts --even the most pacifistic Ragabash or the most serene of the Children of Gaia looks at a normal human and must repress the urge to rend and tear and bite until all that’s left is blood and meat.  Ahroun have it far worse, fighting to see friends, family, and loved ones as little more than prey animals or targets for attack.
The Garou can enter an enraged state by spending 1 point of rage.</p>

**As a bonus action:**
* Advantage on Strength checks and Strength saving throws.
* When the Garou makes an attack using its natural weapons(bite, claw, ect.) you get a bonus to the damage roll that increases as you gain levels as a Garou.
* You have resistance to bludgeoning, piercing, and slashing damage.
* Rage lasts for 1 minute.  It ends early if you are knocked unconscious or if your turn ends and you haven’t attacked a hostile creature since your last turn or taken damage since then.  You can also end your rage on your turn as a bonus action.
* Once you have raged the number of times shown for your Garou level in the Rages column, you must finish a long rest before you can rage again. 
* In Crinos Form, Rage can be spent to get  extra actions.  Cannot spend more than half your rage in a round rounded up.  Each point spent grants an extra action until the next round.***Does not have to be in enraged to spend rage points for other actions however.***
* -Spending 1 point of rage also can grant the Garou to shift into any form instantly, that would otherwise take 1 action
* -If you have 0 Rage points the player is required to roll a successful CON check, DC 10 to successfully shapeshift.  Can retry every round until successful.  Last until player wishes to shapeshift again.

### Gnosis
<body><p>Gaia did not leave the Garou with Rage as their only inheritance of her spiritual power.  She gave them another tool, one that connects her children to their other nature, the spirit world.  This connection to the Sacred Mother is called Gnosis.</p>   
<p>Gnosis is the essence of the spiritual world; it allows Garou to access the spirits that surround them.  In some ways, it is the expression of their half-spirit nature.  Its what fuels many of the powerful Gifts the spirits can bestow.  Without this spiritual force, Garou would be cut off from half of their natures.</p></body>

```
```

* Garou form a pool of Gnosis that grows as they gain levels, it is spent to access Gifts, and restored after a long rest.  Beginning at first level, all Garou have the ability to channel Gnosis.  All Garou have a base Gnosis pool of 1 at first level, increasing by +1/level
* Used to activate mystical gifts from the Tribe Spirits they belong to.
* Cannot use while in a Rage(this does not include the ability to spend Rage points for other abilities)
* The ability to Side Step into the Umbra(Spirit Realm) is a DC 20 - Gnosis Rating.(A Garou with a Gnosis Rating of 10 the difficulty would be 10 on a D20 + Proficiency bonus<br>

### Gifts
<body><p> The Garou can choose special Spiritual Gifts from many different spirits depending on their Breed and Auspice.  Their Tribe Totem also allows for Garou to further his Gift selections based on their Tribal Spirit Totem.</body>
* Can be activated, by Gnosis, Rage, or by simply knowing the Gift itself.
* If a Gift needs concentration, no other gifts can be activated, unless the gift is automatically activated by simply knowing the gift.  Otherwise, another gift ends the gift that needed concentration.
<img 
  src='https://imgur.com/fTkaXy7.jpg' 
  style='width:325px' />
  *Image Source credited to: Onyx Path, W20 Cookbook*

<div class='pageNumber auto'></div>

<div class='footnote'>PART 1 | RAGE & GNOSIS</div>

\page

<div class='pageNumber auto'></div>
<div class='footnote'>PART 2 | RAGABASH</div>

# Part 2: Choose your Auspice
At the moment a Garou is born, they inherit an ancient legacy.  The breed will shape her view of the world, and one day, her tribe will train her to fight the Wyrm.  Her place in that fight, on the other hand, is shaped by something far more mystical.  The phase of the moon at the instant of a Garou’s birth determines her auspice, the role she is destined to play in Garou Society.  Every Garou upholds one of these five aspects and receives mystical gifts to help fulfill it.

<div class='classTable wide'>

##### Ragabash
| Level | Proficiency Bonus |Rage |Gnosis |  Features | Rage Damage Bonus | Gifts Known | 1st | 2nd | 3rd | 4th | 5th |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1st | +2 | 1| 0| Unarmored Defense;Garou Forms | +2 | 1 | 2 | — | — | — | — |
| 2nd | +2 | 1| 0| Rite of Talisman Dedication | +2 | 1 | 3 | — | — | — | — |
| 3rd | +2 | 1| 3| Rite of Passage; Tribal Feature | +2 | 1 | 3 | — | — | — | — |
| 4th | +2 | 1| 4| Ability Score Improvement, Razor Claws | +2 | 1 | 4 | — | — | — | — |
| 5th | +3 | 1| 5| Extra Attack | +2 | 1 | 4 | 1 | — | — | — |
| 6th | +3 | 1| 6| Tribal Feature, Insightful Tactics | +2 | 2 | 4 | 3 | — | — | — |
| 7th | +3 | 2| 7| Infectious Laughter Gift | +2 | 2 | 4 | 3 | 1 | — | — |
| 8th | +3 | 2| 8| Ability Score Improvement | +2 | 2 | 4 | 3 | 1 | — | — |
| 9th | +4 | 2| 9| — | +3 | 2 | 4 | 3 | 1 | — | — |
| 10th | +4 | 2| 10| Improved Shapeshift | +3 | 2 | 4 | 3 | 1 | — | — |
| 11th | +4 | 2| 11 |Tribal Feature | +3 | 2 | 4 | 3 | 3 | — | — |
| 12th | +4 | 3| 12| Ability Score Improvement | +3 | 2 | 4 | 3 | 3 | 2 | — 
| 13th | +5 | 3| 13| Side Step | +3 | 3 | 4 | 3 | 3 | 3 | — 
| 14th | +5 | 3| 14|  Alter Self | +3 | 3 | 4 | 3 | 3 | 3 | 1 |
| 15th | +5 | 3| 15| Open Moon Bridge Gift | +3 | 4 | 4 | 3 | 3 | 3 | 2 
| 16th | +5 | 4| 16| Ability Score Improvement | +4 | 5 | 4 | 3 | 3 | 3 | 2 
| 17th | +6 | 4| 17| Tribal Feature | +4 | 6 | 4 | 3 | 3 | 3 | 3 | 
| 18th | +6 | 4| 18| Trickster's Spirit | +4 | 7 | 4 | 3 | 3 | 3 | 3 |
| 19th | +6 | 5| 19| Ability Score Improvement | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 
| 20th | +6 | 5| 20| Thieving Talons of the Magpie | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 

</div>

\page

<div class='pageNumber auto'></div>
<div class='footnote'>PART 2 | RAGABASH</div>

## Ragabash
<img 
  src='https://imgur.com/S8u8tGK.jpg'
  style='width:325px' />

***Image credited to: Rob Bliss***
<p>Those who were born under the new moon are considered the mythic trickster, among Garou Nation.  The Ragabash is a cunning scout and unconventional tactician, leading the enemy into ambushes and striking at their soft underbellies when they least expect it.  While other auspices have fairly set roles within their sept and tribe, the Ragabash is usually left to his own devises.  He has the gift of flexibility:  the opportunity to explore options usually off limits to other Garou.  His insights are sometimes unwelcome, but frequently worthy.</p>

**Quote:**  *“Oh, what you’ve described is technically a plan, I suppose.  The sort of plan a drooling, brain-dead savage might create, but still a plan.  Hey, easy!  I wasn’t talking about you--I was talking about the drooling, brain-dead savages massing on our border.  I’ve overheard their plans, and they were largely the same  as yours.  Perhaps you might like to rethink your approach”?*

```
```
## Class Features
As a Ragabash, you gain the following class features
#### Hit Points
___
- **Primary Ability:** Dexterity
- **Hit Dice:** 1d6 per Ragabash level
- **Hit Points at 1st Level:** 6 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d6 (or 4) + your Constitution modifier per Ragabash level after 1st

#### Proficiencies
___
- **Armor:** Light Armor
- **Weapons:** : Simple Weapons, hand crossbows, longswords, rapiers, shortswords
- **Tools:**  Thieve's tools

___
- **Saving Throws:** Dexerity, Intelligence
- **Skills:** : Choose four from Acrobatics, Athletics, Deception, Insight, Intimidation, Investigation, Perception, Performance, Persuasion, Sleight of hand, and Stealth.

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
- *(a)* a rapier or *(b)* a shortsword
- *(a)* a shortsword and quiver of 20 arrows or *(b)* a shortsword
- *(a)* a burglar's pack,*(b)* a dungeoneer's pack, or *(c)* an explorer's pack
- Leather armor, two daggers, and thieves' tools

## Gifts
Activating Gifts normally require spending Gnosis, unless they say otherwise.  While some gifts are activated simply by knowing the Gift itself.  

Choose from the Ragabash Gift list, and pick 1 rank 1 Gift at Character creation.
### Stealthy

At 1st level, the Ragabash has inherited the abilities of the New Moon to give it advantage on any stealth rolls naturally.

### Unarmored Defense
Beginning at 1st level, while you are wearing no armor and not wielding a shield, your AC equals 10 + Dex modifier + Wis modifier.

\page

<div class='pageNumber auto'></div>
<div class='footnote'>PART 2 | RAGABASH</div>

### Rite of Talisman Dedication
<p>Beginning at 2nd level, the Garou can choose pieces of equipment that phase with him when switching forms.  This rite allows a Garou to bind objects to her body, allowing them to fit her various forms*(pants will grow to accommodate the Crinos form rather than splitting at the seams, also useful if a Garou ever decides to don armor)*.  Fetishes such as Klaives remain with the werewolf in all forms automatically without this rite. </p> 
<p>One Gnosis point is spent to activate this Rite and remains active until the next long rest, and the character may never have more objects bout to himself than his Gnosis score.  Conceptually linked groups of objects may count as a single object.  A set of clothing is considered one object, rather than one shirt, 2 socks, ect.   Objects will generally resize themselves to accommodate the character’s various forms, but may simply meld with the character in forms where they can be of no use- for example, a knife may become a knife-shaped tattoo in Lupus.

***Once the Ragabash reached 8th level, he will no longer need to spend Gnosis.***</p>

### Rite of Passage

<p>When you reach 3rd level, the Garou petitions himself to a tribe, in what is known as the Rite of Passage.  Once completed, he accepts that Tribe’s spirit totem as his own. Your Tribe grants you features at 3rd,6th, 11th, and 17th levels.</div><p>

### Ability Score Improvement
When you reach 4th level, and again at 8th, 12th,16th, and 19th level, you can increase one ability score of your choice by two, or increase two ability scores of your choice by one.  You can't increase an ability score above 20 using this feature.

### Razor Claws
When you reach 4th level, the Garou has the ability to spend one action to sharpen its claws.  Claw attacks become +1 attacks to hit and damage until the Garou changes forms.  Cant be used in Homid form.

### Insightful Tactics
<p>Starting at 6th level, if you spend at least one minute observing or interacting with another creature outside of combat, you can learn certain information about it's capabilities compared to your own.  The DM tells you if the creature is equal, superior,or inferior in regard to two of the following characteristics of your choice:</p>

```
```
* Intelligence score
* Wisdom score
* Charisma score
* Class levels*(if any)*

At the DM option, you might also realize you know a piece of the creature's history or one of it's personality traits, if it has any.

### Ambush
At 9th level, you excel at leading ambushes and acting first in a fight.  You have advantage on initiative rolls.

### Improved Shapeshift
Starting at 10th level, the Garou can shapeshift from one form to another as a bonus action instead.  ***A metis Ragabash can go beyond this improvement, by manipulating its deformed body into hideous fleshed wings, can fly at half base speed.***

### Side Step
Starting at 13th level, once per day at will, the Garou can side step into the Umbra at a DC 20 - Gnosis Rating.**See Plane Shift Spell.**

### <div>Alter Self
At 14th level, the Ragabash has the ability to extend his shapeshifting abilities in different ways.  Like the 2nd level spell, the Garou can alter his appearance  and the same rules apply.  
All claws , fangs, horns, ect. Are still considered magical weapons, and the Garou however, retains his natural bonuses that apply.  The effects last 1 hour, unless the upkeep is paid in Gnosis.
* 1 Gnosis to activate
* 1 Gnosis to add an aquatic adaptation *(Gills, webbed fingers, ect)*
* 1 Gnosis for every hour needed for upkeep on the ability

### Trickster's Spirit

Starting at 18th level, your thoughts can't be read by telepathy or other means, unless you allow it.  You can present false thoughts by succeeding in a Charisma(deception) check contested by the mind reader's Wisdom(insight) check.

Additionally, no matter what you say, magic that would determine if you are telling the truth indicates you are being truthful if you choose to, and you can't be compelled to tell the truth by magic.
\page

<div class='pageNumber'>8</div>
<div class='footnote'>PART 2 | RAGABASH</div>

> ##### Ragabash Gifts
> Luna’s Gifts to the Ragabash defy tradition and conventional wisdom.  Well-suited to tricksters, scouts and saboteurs, the eclectic blessings of the new moon are nothing if not effective.
	***Gifts are received at 7th, 9th, 15th, and 20th levels.***

## Ragabash Gifts


### Infectious Laughter
 At 7th level, laughter is the tool with which Gaia’s tricksters promote enlightenment and the knife that slashes through the veil of Rage.  When the Ragabash laughs, those around her are compelled to follow along, forgetting their grievances.
 * **Cost-** 1 Gnosis point The Ragabash must make some comment mocking the present situation in which she finds herself, then laugh at it. A creature of your choice that you can see within 60 ft,  perceives everything as hilariously funny and falls into fits of laughter if this spell affects it.
 <p>The target must succeed on a Wisdom saving throw or fall prone, becoming incapacitated and unable to stand up for the duration. A creature with an Intelligence score of 4 or less isn’t affected.</p>
At the end of each of its turns, and each time it takes damage, the target can make another Wisdom saving throw. The target has advantage on the saving throw if it’s triggered by damage. On a success, the spell ends.</p>
<br>
<br>
### Blissful Ignorance
 At 9th level, the Garou can become completely invisible to all senses. 
* **Cost-**2 Gnosis

A veil of shadows and silence radiates from you, masking you and your companions from detection. For 1 min, each creature you choose within 30 feet of you (including you) has a +10 bonus to Dexterity (Stealth) checks and can’t be tracked except by magical means. A creature that receives this bonus leaves behind no tracks or other traces of its passage.
```
```
### Open Moon Bridge
 At 15th level, the Garou has the ability to open a moon bridge, with or without the permission of the totem of that Caern.   The location must be known to you, and on the same plane of existence.Your familiarity with the destination determines whether you arrive there successfully. The GM rolls d100 and consults the table.
<table border="1" width="400" height="150">
  <tr>
    <td>**Familiarity**</td>
    <td>**Mishap**</td>
    <td>**Similar Area**</td>
    <td>**Off Target**</td>
    <td>**On Target**</td>
  </tr>
    <tr>
    <td>**Permanent Circle**</td>
    <td>-------</td>
    <td>-------</td>
    <td>-------</td>
    <td>01-100</td>
  </tr>
    <tr>
    <td>**Associated Object**</td>
    <td>-------</td>
    <td>-------</td>
    <td>-------</td>
    <td>01-100</td>
  </tr>
    <tr>
    <td>**Very Familiar**</td>
    <td>01-05</td>
    <td>06-13</td>
    <td>14-24</td>
    <td>25-100</td>
  </tr>
    <tr>
    <td>**Seen Casually**</td>
    <td>01-33</td>
    <td>34-43</td>
    <td>44-53</td>
    <td>54-100</td>
  </tr>
    <tr>
    <td>**Viewed Once**</td>
    <td>01-43</td>
    <td>44-53</td>
    <td>54-73</td>
    <td>74-100</td>
  </tr>
    <tr>
    <td>**Description**</td>
    <td>01-43</td>
    <td>44-53</td>
    <td>54-73</td>
    <td>74-100</td>
  </tr>
    <tr>
    <td>**False Destination**</td>
    <td>04-50</td>
    <td>51-100</td>
    <td>-------</td>
    <td>-------</td>
  </tr>
 </table>
 <br>
 <br>
 ##### Familiarity
 * **"Permanent Circle"**  means a permanent teleportation circle whose sigil sequence you know. “Associated object” means that you possess an object taken from the desired destination within the last six months, such as a book from a wizard’s library, bed linen from a royal suite, or a chunk of marble from a lich’s secret tomb.
 * **"Very Familiear"**  is a place you have been very often, a place you have carefully studied, or a place you can see when you cast the spell. “Seen casually” is someplace you have seen more than once but with which you aren’t very familiar. “Viewed once” is a place you have seen once, possibly using magic. “Description” is a place whose location and appearance you know through someone else’s description, perhaps from a map.
 * **"False Destination"** is a place that doesn’t exist. Perhaps you tried to scry an enemy’s sanctum but instead viewed an illusion, or you are attempting to teleport to a familiar location that no longer exists.
 * **"On Target"**  You and your group (or the target object) appear where you want to.
 * **"Off Target"**  You and your group (or the target object) appear a random distance away from the destination in a random direction. Distance off target is 1d10 × 1d10 percent of the distance that was to be traveled. For example, if you tried to travel 120 miles, landed off target, and rolled a 5 and 3 on the two d10s, then you would be off target by 15 percent, or 18 miles. The GM determines the direction off target randomly by rolling a d8 and designating 1 as north, 2 as northeast, 3 as east, and so on around the points of the compass. If you were teleporting to a coastal city and wound up 18 miles out at sea, you could be in trouble.
 \page
<div class='pageNumber'>9</div>
<div class='footnote'>PART 2 | RAGABASH</div>

* **"Similar Area"**  You and your group (or the target object) wind up in a different area that’s visually or thematically similar to the target area. If you are heading for your home laboratory, for example, you might wind up in another wizard’s laboratory or in an alchemical supply shop that has many of the same tools and implements as your laboratory. Generally, you appear in the closest similar place, you could conceivably wind up anywhere within 1000 miles on the plane.
* **"Mishap"**  The spell’s unpredictable magic results in a difficult journey. Each teleporting creature (or the target object) takes 3d10 force damage, and the GM rerolls on the table to see where you wind up (multiple mishaps can occur, dealing damage each time). The maximum distance that can thereby be covered is 1000 miles. 
* **Cost-**  5 Gnosis ***Cant be used to connect to portals that are sealed by magic.***
<br>
<br>
### Thieving Talons of the Magpie
At 20th level, the Ragabash can steal the powers of others and use them herself.  These powers can be Gifts, spirit charms, monster abilities, ect.  They cannot steal spells, or any Legendary or Lair actions or abilities. 
 * **Cost-**5 Gnosis, and target makes a Wisdom Save.  If the target fails, the Ragabash steals the targeted power, depriving its owner of its use.  The Garou may keep the power for as many turns as she wishes, so long as she pays a point of Gnosis each turn.




 \page
 
 <div class='pageNumber'>10</div>
<div class='footnote'>PART 2 | THEURGE</div>
<div class='classTable wide'>
##### Theurge
| Level | Proficiency Bonus |Rage |Gnosis |  Features | Rage Damage Bonus | Gifts Known | 1st | 2nd | 3rd | 4th | 5th |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1st | +2 | 1| 0| Unarmored Defense;Garou Forms | +2 | 1 | 2 | — | — | — | — |
| 2nd | +2 | 1| 0| Rite of Talisman Dedication | +2 | 1 | 3 | — | — | — | — |
| 3rd | +2 | 1| 3| Rite of Passage; Tribal Feature | +2 | 1 | 3 | — | — | — | — |
| 4th | +2 | 1| 4| Ability Score Improvement, Razor Claws | +2 | 1 | 4 | — | — | — | — |
| 5th | +3 | 2| 5| Extra Attack | +2 | 1 | 4 | 1 | — | — | — |
| 6th | +3 | 2| 6| Tribal Feature, Insightful Tactics | +2 | 2 | 4 | 3 | — | — | — |
| 7th | +3 | 2| 7| Infectious Laughter Gift | +2 | 2 | 4 | 3 | 1 | — | — |
| 8th | +3 | 2| 8| Ability Score Improvement | +2 | 2 | 4 | 3 | 1 | — | — |
| 9th | +4 | 3| 9| — | +3 | 2 | 4 | 3 | 1 | — | — |
| 10th | +4 | 3| 10| Improved Shapeshift | +3 | 2 | 4 | 3 | 1 | — | — |
| 11th | +4 | 3| 11 |Tribal Feature | +3 | 2 | 4 | 3 | 3 | — | — |
| 12th | +4 | 3| 12| Ability Score Improvement | +3 | 2 | 4 | 3 | 3 | 2 | — 
| 13th | +5 | 4| 13| Side Step | +3 | 3 | 4 | 3 | 3 | 3 | — 
| 14th | +5 | 4 |14|  Alter Self | +3 | 3 | 4 | 3 | 3 | 3 | 1 |
| 15th | +5 | 4| 15| Open Moon Bridge Gift | +3 | 4 | 4 | 3 | 3 | 3 | 2 
| 16th | +5 | 4| 16| Ability Score Improvement | +4 | 5 | 4 | 3 | 3 | 3 | 2 
| 17th | +6 | 5| 17| Tribal Feature | +4 | 6 | 4 | 3 | 3 | 3 | 3 | 
| 18th | +6 | 5| 18| Trickster's Spirit | +4 | 7 | 4 | 3 | 3 | 3 | 3 |
| 19th | +6 | 5| 19| Ability Score Improvement | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 
| 20th | +6 | 5| 20| Thieving Talons of the Magpie | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 
</div>

## Theurge
The sickle-shaped crescent moon grants the gift of insight.  The Theurges are the mystics of the Garou, closer than any to the Umbra and its denizens.  They peer deep into the shadowed recesses of the spirit world, and are tasked with dealing with the secrets they find there. 
  
Some call these seers the daydreamers of the Garou, and many do seem to be a bit detached from their brethren.  They can see and hear things that others cannot, as if they live half in the world of the physical and half in the world of the spirit.  The Theurge holds an important place in any pack.  Without her, the Garou would forget the spiritual side of their nature.  They might wander lost and blind if they did not have her visions and dreams to guide them.

  <br>
  <br>
  <br>
  
  **Quote:**  *I hear their voices.  Gaia grows hot with anger.  The wind is cold with scorn.  They are all around us, awaiting my call.*
  ```
```
<img 
  src='https://imgur.com/VD4y0cY.jpg' 
  style='width:200px' />
  *Image by:http://davestarn.com/lakota/Wolf/Images/skinwalker5.jpg
  Onyx Path, Werewolf: the Apocalypse Storytellers Guide



\page
<div class='pageNumber'>11</div>
<div class='footnote'>PART 2 | THEURGE</div>
## Class Features
As a Theurge, you gain the following class features
#### Hit Points
___
- **Primary Ability:** Intelligence
- **Hit Dice:** 1d6 per Theurge level
- **Hit Points at 1st Level:** 6 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d6 (or 4) + your Constitution modifier per Theurge level after 1st

#### Proficiencies
___
- **Armor:** None, if any armor is worn, the Theurge becomes incapable of channeling their Gnosis...And gifts are made with disadvantage when applicable.
- **Weapons:** : daggers, darts, slings, quarterstaffs, light crossbows
- **Tools:**  None

___
- **Saving Throws:** Intelligence, Wisdom
- **Skills:** : Choose two from Arcana, History, Insight, Investigation, Medicine, and Religion



#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
- *(a)* a quarterstaff or *(b)* a dagger
- *(a)* a scholar's pack or an explorer's pack

### Cantrip
The Theurge is able to choose any cantrip from the Wizard spell list.
<br>
<br>
### Rite of Spirit Awakening
At 2nd level, the Theurge chooses to focus on the waxing or waning side of the moon.  Each gives different abilities and focuses on certain aspects.  Their ability to Channel Gnosis to perform certain tasks depends on their waxing or waning side they choose.
* #### Channel Gnosis
Using an Action, the Theurge can use their Gnosis to create spiritual energy, the waxing Theurge channels their Gnosis to be able to heal wounds, and the Waning Theurge uses it to create them.  Any target the Theurge can see within 60ft is able to be healed or hurt depending on the waxing or waning side the  Theurge represents.  ***The Theurge can only spend half his Gnosis rating, rounded up, in a turn for this effect.***
 * **Waxing Theurge** uses their Gnosis pool to heal wounds.  Luna’s Spiritual Blessing is cast at the target and is healed the Theurge’s level x5 per Gnosis point spent.  Alternatively the Theurge can spend either multiple points of Gnosis for one target, for a bigger heal, or one point per multiple targets for a lesser mass heal effect.  But not both in the same round.
 * **Waning Theurge** uses their Gnosis pool to injure.  Luna’s Spiritual Fury is cast at a target within 60ft takes force damage equal to 1d10 + Theurge level per Gnosis point spent.  Dex save for half.  Alternatively the Theurge can spend either multiple points of Gnosis for one target, or one point per multiple targets for a lesser mass damage effect.  But not both in the same round.  Additionally there are a few other ways the Waning Theurge can manipulate Luna’s Fury as well.   At 3rd, 10th, and 17 level the Theurge can take a metamagic ability to twist your Channel Gnosis ability to suit your needs.
 <br>
 ### Waxing Moon Theurge
  Starting at 2nd level, the Theurge decides to focus his Gnosis to channel spiritual blessings from Luna, the moon spirit.  Along with the ability to channel Gnosis which strengthens as you level, at 5th and 15th level, the Waxing Moon Theurge gets more specific abilities to call upon.
   * #### Mother's Touch
   Starting at 5th level, Luna blesses the Waxing Moon Theurge with the ability to remove one debilitating effect by touching a creature and spending 2 Gnosis points. 
   <br>
   * #### Battle Mandala
   At 15th level, the Waxing Moon Theurge can create a mystical sigil that burns itself into the ground around the Theurge in a radius of 5 x Gnosis rating for their level, visible only to those with Gnosis ratings.  This circle drains the undead caught within its web.  Any Undead within the radius turn and retreat.  Undead within the area make a Wisdom saving throw vs Garou spellcast DC.  Any undead within the radius that failed the saving throw are turned for 1 min or until it takes damage.  It spends its actions moving away from the Theurge, and can't take reactions.  It can use only the Dash action trying to escape. 
   \page
   <div class='pageNumber'>12</div>
<div class='footnote'>PART 2 | THEURGE</div>
* Additionally, these undead within the radius that the Garou can see, can be destroyed by spending additional Gnosis if they fail the saving throw.  Only one creature can be targeted at a time.  Costs 1 action and 1 Gnosis each. If the Undead have a CR above 4, they take 10d6 + level  radiant damage instead
<BR>
  <table border="1" width="400" height="150">
  <tr>
    <td>**Level**</td>
    <td>**Destroy CR of**</td>
    </tr>
     <tr>
    <td>5th</td>
    <td>1/2 or lower</td>
    </tr>
    <tr>
    <td>8th</td>
    <td>1 or lower</td>
    </tr>
    <tr>
    <td>11th</td>
    <td>2 or lower</td>
    </tr>
    <tr>
    <td>14th</td>
    <td>3 or lower</td>
    </tr>
    <td>17th</td>
    <td>4 or lower</td>
  </table>
  <br>
  <br>
  ### Waning Moon Theurge
  Starting at 2nd level, if the Theurge decides to focus his Gnosis to channel Luna’s Spiritual Fury, destructing force damage will be able to be called upon through channelling Gnosis, which strengthens as you level.  At 5th and 15th level, the Waning Moon Theurge gets more specific abilities to call upon.
  * #### Sense Wyrm
  At 5th level, the Theurge can sense nearby manifestations of the Wyrm.  This involves a mystical sense, not a visual or olfactory image, although Garou often describes the Wyrm’s spiritual emanations as a stench.  The Garou can detect any evil, or undead being within 100ft per Gnosis point spent.  If detecting something in the area in a range he cannot see, the DM can call for a tracking roll(with advantage) to follow the scent.
  
  * #### In the Beginning
    At 15th level, the Waning Moon Theurge tears away at the Gauntlet, merging the worlds of flesh and spirit as they were in the days of legend.  Moreover, this mended region acts as a shining beacon to Gaian spirits, calling a flood of nature-spirits and other allies to assist the Theurge.  An Occult roll + level is made to determine how powerful the spirit is that comes through.  The ancient howl that is made, forces whatever is summoned to aid the Garou and his allies in any way within its abilities.  They are obligated to use every available ability they can within the amount of time they are called upon.  When finished they are immediately consumed back through the Gauntlet at the end of the duration.  The roll chart determines what is called upon usually based off of the alignment of the Garou.  Cannot be used again until finishing a long rest.```
```
* 01-09 =  1d6 Air Elementals for 3 rounds
* 10-19 = Planetar / Marilith  for 2 rounds
* 20+ = Empyrean/ Pit Fiend for 1 round. ***Can use legendary actions for the round***
 #### MetaMagic 
  The Waning Moon Theurge can manipulate the spiritual energies he channels from Gnosis.  Starting at 3rd level, the Theurge of the Waning Moon can pick one of the MetaMagic abilities below and apply it to his channeling ability.  He can add to this feature at 10th, and 17th level to further suit his needs.
  * #### Distant Channel Gnosis
  When you channel Gnosis you can spend 1 additional Gnosis point to double the range.
  * #### Empower Gnosis
  When you roll damage for Channel Gnosis, you can spend 1 Gnosis point to reroll a number of the damage dice up to your Intelligence modifier(minimum of 1).  You must use the new rolls.  You can use Empowered Gnosis even if you have already used a different Metamagic option during the casting of the spell.
  * #### Heightened Gnosis
  When you channel Gnosis you can spend 3 additional Gnosis points to give one target of the spell disadvantage on its saving throw made against it.
  * #### Quickened Gnosis
When you channel Gnosis you can spend 2 additional Gnosis points to make the action a bonus action instead.
  * #### Twinned Gnosis
  When you channel Gnosis and target only one creature, you can spend equal the amount of Gnosis spent on the first target and target an additional target in range.  ***For example, if the Theurge spent 5 gnosis for 5d10 + level damage to target 1, he can spend an additional 5 gnosis, to target a second creature at 5d10 + level.***
  <br>
  <br>
  ### Rite of Passage
When you reach 3rd level, the Garou petitions himself to a tribe, in what is known as the Rite of Passage.  Once completed, he accepts that Tribe’s spirit totem as his own. Your Tribe grants you features at 3rd,6th, 11th, and 17th levels.
  <br>
  <br>
  ### Mental Speech
  At 7th level, the Theurge can communicate with anyone willing telepathically that he can see.
  <br>
  <br>
  ### Empower
  At level 9, the Theurge spends one Gnosis point and can boost any ability score by 2.  Can only empower one ability at a time and the effect lasts for 1 hour.
  
  \page
  
  <div class='pageNumber'>13</div>
<div class='footnote'>PART 2 | THEURGE</div>
  ### Create Lycan
  At level 10, the theurge spends 2 gnosis points and can coat its teeth with a Lycanthropy Curse to an individual if a successful bite attack is made. The target rolls a Con Save vs Garou’s Spell Save DC.  If the Save fails, the effects of this curse are immediate, and the target changes into a Cursed Werewolf(5e).
  
  All stats are the same as a normal cursed werewolf with Lycanthropy, but this curse only lasts for an amount of rounds equal to the Theurge’s level.  Also, the Theurge is only able to call upon this curse to one creature at a time.  The werewolf obey’s any commands the Theurge gives it and fulfills them to the best of its ability, as long as it's not self harming. 
  <br>
  <br>
  ### Side Step
  Starting at 13th level, once per day at will, the Garou can side step into the Umbra.  See Plane Shift Spell.
  <br>
  <br>
  ### Hurl Through Hell
  Starting at 14th level, when you hit a creature with an attack, you can use this feature to instantly transport the target through the lower planes. The creature disappears and hurtles through a nightmare landscape.
  
At the end of your next turn, the target returns to the space it previously occupied, or the nearest unoccupied space. If the target is not a fiend, it takes 10d10 psychic damage as it reels from its horrific experience.
  
Once you use this feature, you can't use it again until you finish a long rest.
  <br>
  <br>
  ### Umbral Form
  Starting at 18th level, you can spend 6 Gnosis points as a bonus action to magically transform yourself into your Wolf Spirit  form. In this form, you have resistance to all damage except force and radiant damage, and you can move through other creatures and objects as if they were difficult terrain. 
  
  You take 5 force damage if you end your turn inside an object. You remain in this form for 1 minute. It ends early if you are incapacitated, if you die, or if you dismiss it as a bonus action.
  <br>
  <br>
  ### Survivor 
  At 20th level, the Theurge is now immune to extreme temperatures, diseases, and poisons. Additionally, by spending 3 Gnosis a day, the Theurge has the ability to go without food, water, and sleep without penalty.   Will not restore abilities used that require a short or long rest.
  ```

```
  <img 
  src='https://imgur.com/1ffSBNK.jpg' 
  style='width:325px' />
*image source: https://2.bp.blogspot.com/-LJTFqdDkJAY/VDy4j8gBvGI/AAAAAAAAG6E/3PqMjJznol8/s1600/Moot.jpg*  
  Onyx Path, Werewolf the Apocalypse
  \page
## Philodox
  <div class='classTable wide'>
##### Theurge
| Level | Proficiency Bonus |Rage |Gnosis |  Features | Rage Damage Bonus | Gifts Known | 1st | 2nd | 3rd | 4th | 5th |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1st | +2 | 1| 0| Balanced Unarmored Defense;Garou Forms | +2 | 1 | 2 | — | — | — | — |
| 2nd | +2 | 1| 0| Truth of Gaia  | +2 | 1 | 3 | — | — | — | — |
| 3rd | +2 | 1| 3| Rite of Passage; Tribal Feature | +2 | 1 | 3 | — | — | — | — |
| 4th | +2 | 2| 4| Ability Score Improvement, Razor Claws | +2 | 1 | 4 | — | — | — | — |
| 5th | +3 | 2| 5| Extra Attack | +2 | 1 | 4 | 1 | — | — | — |
| 6th | +3 | 2| 6| Tribal Feature, Pack Totem | +2 | 2 | 4 | 3 | — | — | — |
| 7th | +3 | 3| 7| King of Beasts | +2 | 2 | 4 | 3 | 1 | — | — |
| 8th | +3 | 3| 8| Ability Score Improvement | +2 | 2 | 4 | 3 | 1 | — | — |
| 9th | +4 | 3| 9| Klaive | +3 | 2 | 4 | 3 | 1 | — | — |
| 10th | +4 | 4| 10| — | +3 | 2 | 4 | 3 | 1 | — | — |
| 11th | +4 | 4| 11 |Tribal Feature | +3 | 2 | 4 | 3 | 3 | — | — |
| 12th | +4 | 4| 12| Ability Score Improvement | +3 | 2 | 4 | 3 | 3 | 2 | — 
| 13th | +5 | 5| 13| Take the True Form | +3 | 3 | 4 | 3 | 3 | 3 | — 
| 14th | +5 | 5| 14|  Grand Klaive | +3 | 3 | 4 | 3 | 3 | 3 | 1 |
| 15th | +5 | 5| 15| Wall of Granite Gift | +3 | 4 | 4 | 3 | 3 | 3 | 2 
| 16th | +5 | 6| 16| Ability Score Improvement | +4 | 5 | 4 | 3 | 3 | 3 | 2 
| 17th | +6 | 6| 17| Tribal Feature | +4 | 6 | 4 | 3 | 3 | 3 | 3 | 
| 18th | +6 | 6| 18| Break the Bonds Gift | +4 | 7 | 4 | 3 | 3 | 3 | 3 |
| 19th | +6 | 7| 19| Ability Score Improvement | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 
| 20th | +6 | 7| 20| — | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 
</div>
  
  
  <br>
  <br>
  The half moon is balance and duality, standing between two worlds.  The Garou is both wolf and human, flesh and spirit, fury and wisdom, savage and savant.  The Philodox embraces this duality, attempting to harness it with balance.  The Half Moon acts as counselor, mediator, and law-keeper to his pack.  Where the Ragabash must question the laws, the Philodox must interpret them, finding the wisest answer out of many.  
Half Moons are called to judge, for better or for worse.  
  
  Theirs is the task to set punishment when the Garou stray from the path, and to determine when a werewolf's actions are particularly meritorious.  They are frequently leaders in times of peace, but often cede command to Ahroun or Galliards when war breaks out.
  <br>
  

  **Quote:** *"You abandoned your post to aid a packmate.  To save another Garou’s life is commendable;  to think of your packmate before yourself is proper.  But to put the sept in danger is foolish and disregards the lives of your fellows.  You must pay the price for that.  I levy the punishment of ordeal.  Perhaps your love of your pack will encourage you to excel here and wipe the stain from your honor."*
  ```
  
<img src='https://imgur.com/xzTE15N.jpg' style='width:300px' />
  *Image source by: https://icdn1.digitaltrends.com/image/digitaltrends/500-worgen-art-768x558.jpg*
  Worgen World of Warcraft
  
  <div class='pageNumber'>14</div>
<div class='footnote'>PART 2 | PHILODOX</div>


  
  \page



## Class Features
As a Philodox, you gain the following class features
#### Hit Points
___
- **Primary Ability:**  Charisma
- **Hit Dice:** 1d8 per Philodox level
- **Hit Points at 1st Level:** 8 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d8 (or 5) + your Constitution modifier per Philodox level after 1st

#### Proficiencies
___
- **Armor:** All Armor
- **Weapons:** simple weapons, martial weapons, Klaives, Grand Klaives
- **Tools:** None

___
- **Saving Throws:** Wisdom, Charisma
- **Skills:** Choose two from Athletics, Acrobatics,  Insight, Intimidation, Medicine, Persuasion and Religion

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
- *(a)* a martial weapon and a shield or *(b)* two martial weapons
- *(a)* five javelins or *(b)* any simple melee weapon
- a priest's pack or (b) an explorer's pack
  
 
  ### Balanced Unarmored Defense
  Starting at 1st level, While you are not wearing any armor, your Armor Class equals 13 + your Dexterity modifier + your Charisma modifier
  
  
  ### Truth of Gaia
  As judges of the
Litany, Philodox may easily separate truth from falsehood.
A Gaffling of Falcon teaches this Gift.

  **System:** Any Deception within 30 ft of the Philodox is made with a +10 to the difficulty against him. This Gift reveals only which of the words that have been spoken are true and which are false. It doesn’t reveal the
truth behind a lie unless the speaker utters it. If the speaker
is uncertain whether his words are true or false, the Gift
identifies them as neither.

  

### Rite of Passage
  When you reach 3rd level, the Garou petitions himself to a tribe, in what is known as the Rite of Passage.  Once completed, he accepts that Tribe’s spirit totem as his own. Your Tribe grants you features at 3rd,6th, 11th, and 17th levels.
 
 
  
  ### Extra Attack
  Starting at 5th level, the Philodox gets an extra attack action.
  ```
```
 
### Pack Totem
  Beginning at 6th level, whenever you or a friendly creature within 10 feet of you must make a saving throw, the creature gains a bonus to the saving throw equal to your Charisma Modifier(minimum of +1). You must be conscious to grant this bonus.  At 18th level, the range of this aura increases to 30ft.

  
  ### King of Beasts
  At 7th level, the Philodox’s authority extends even into the realm of beasts, so that he can command the loyalty of any single animal.  The Philodox spends 2 Gnosis on one animal within 100 feet with a CR rating of 0, and that animal becomes a familiar  to the Philodox.   The  animal is now considered Fey instead of beast.  When dismissed it disappears into the Umbra awaiting your summons.  Mechanically the same as the ***Find Familiar*** conjuration spell.
  

  
  ### Klaive
  At 9th level, Gaia’s Chosen may use the Rite of the Fetish to bind spirits into appropriately crafted and consecrated vessels. Majority of fetishes are crafted for natural materials.(wood, bone, hide, clay); Garou adorn them with carved river stones, feathers, beads, and other markings to honor and appease the spirit within.
  * Requires attunement after it is made and bound with a spirit.
  * Like Rite of talisman Deduction,  the Garou can summon the klaive in and out of existence.  A useful tactic when changing forms, especially while in Hispo or Lupus and can't use the Klaive.
  * The Klaive is made of Silver, is considered a Shortsword, Gnosis grants it a  **+2 and magical**
  * When the Garou  spends 2 Gnosis to activate the spirit bound to the Klaive.  Whenever the Klaive hits a target, it deals an extra 1d8 radiant damage.  The Klaive retains this activation until its owner takes a short or long rest, or falls unconscious in any way.

  
  ### Take the True Form
  At 13th level, the Philodox can spend a single Gnosis point to detect any creature or object under the effect of shapeshift, Alter Self, Disguise, Illusion, or ability similar in nature. Once detected, for 2 additional Gnosis, the target (If possible) must make a Wisdom Save vs Garou Spell Save DC.  If the save fails the target reverts back to its original form or the illusion is dispelled.

  
  <div class='pageNumber'>15</div>
<div class='footnote'>PART 2 | PHILODOX</div>
  
  \page
  
  ### Grand Klaive
  At 14th level, the Garou can now create a Grand Klaive.  The concept is similar to the Klaive but more powerful.  The Grand Klaive has 2 spirits bound to this weapon, and they both serve a purpose when activated.
* Considered a longsword which the blade is made of silver (1d10), by spending 3 Gnosis it becomes a **+3 and magical**
* Like the Klaive, once its activated it deals 2d8 radiant damage when successfully striking a target
  
As far as the second War spirit bound to the Klaive, it can be activated by spending a separate amount of Gnosis to use whatever magical ability that spirit carries.  Pick one transmutation spell from the wizard spell list of 7th level or lower.  This cannot be changed once chosen.  Optionally, the DM can base it off a random roll.  That spirit represents that ability for the remaining life of the weapon.
* It costs 3 Gnosis to activate the Grand Klaive’s second ability.
* The second ability cannot be used again until the owner finishes a short rest.
  <br>
  <br>
  
  
  ### Wall of Granite
  At 15th level, the Garou spends 2 Gnosis touching the ground, to produce a physical 10x10 ft stone panel 6 inches thick.  Can create multiple panels based on the amount of Gnosis spent.  Each panel has an AC 15 and 30 HP.  The panels can be created and or stacked anywhere within a 60ft radius around the Garou.  And can even be placed around an ally within range to shield them
  <br>
  <br>
  
  ### Break the Bonds
  At 18th level, the Philodox has the ability to shatter all bonds, physical or mental.  Garou may use this Gift to benefit any being, including herself once per short rest.  Garou spends 5 Gnosis and can remove ANY Condition which impairs movement or actions, also becomes immune to that condition until they take a short or long rest, or fall unconscious.
  ```
```

<img 
  src='https://imgur.com/hxnLm2L.jpg' 
  style='width:325px' />
  *Image credited to: Kuzinskiy Andrey*
  <div class='pageNumber'>16</div>
<div class='footnote'>PART 2 | PHILODOX</div>
  
  \page
  
 <div class='classTable wide'>
##### Galliard
| Level | Proficiency Bonus |Rage |Gnosis |  Features | Rage Damage Bonus | Gifts Known | 1st | 2nd | 3rd | 4th | 5th |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1st | +2 | 1| 0| Pack Inspiration(d4), Garou Forms | +2 | 1 | 2 | — | — | — | — |
| 2nd | +2 | 1| 0| Gift of the Galliard | +2 | 1 | 3 | — | — | — | — |
| 3rd | +2 | 1| 3| Rite of Passage; Tribal Feature | +2 | 1 | 3 | — | — | — | — |
| 4th | +2 | 2| 4| Ability Score Improvement, Howls | +2 | 1 | 4 | — | — | — | — |
| 5th | +3 | 2| 5| Extra Attack, pack inspiration (d6) | +2 | 1 | 4 | 1 | — | — | — |
| 6th | +3 | 2| 6| Tribal Feature | +2 | 2 | 4 | 3 | — | — | — |
| 7th | +3 | 3| 7| Distractions Gift | +2 | 2 | 4 | 3 | 1 | — | — |
| 8th | +3 | 3| 8| Ability Score Improvement | +2 | 2 | 4 | 3 | 1 | — | — |
| 9th | +4 | 3| 9| Eye of the Cobra Gift | +3 | 2 | 4 | 3 | 1 | — | — |
| 10th | +4 | 4| 10| Delirium, Pack Inspiration (d8) | +3 | 2 | 4 | 3 | 1 | — | — |
| 11th | +4 | 4| 11 |Tribal Feature | +3 | 2 | 4 | 3 | 3 | — | — |
| 12th | +4 | 4| 12| Ability Score Improvement | +3 | 2 | 4 | 3 | 3 | 2 | — 
| 13th | +5 | 5| 13| Extra Howl (2) | +3 | 3 | 4 | 3 | 3 | 3 | — 
| 14th | +5 | 5| 14|  Master of Howls | +3 | 3 | 4 | 3 | 3 | 3 | 1 |
| 15th | +5 | 5| 15| Pack Inspiration (d10) | +3 | 4 | 4 | 3 | 3 | 3 | 2 
| 16th | +5 | 6| 16| Ability Score Improvement | +4 | 5 | 4 | 3 | 3 | 3 | 2 
| 17th | +6 | 6| 17| Tribal Feature | +4 | 6 | 4 | 3 | 3 | 3 | 3 | 
| 18th | +6 | 7| 18| Fabric of the Mind Gift | +4 | 7 | 4 | 3 | 3 | 3 | 3 |
| 19th | +6 | 7| 19| Ability Score Improvement | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 
| 20th | +6 | 8| 20| Extra Howl (3) | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 
</div>
  <br>
  <br>
  
  The Galliard sings the soul of the Garou to the near-full moon, howling of their joys and sorrows, their triumphs and losses.  She is the voice of the People, calling them to battle and inspiring them to greatness in life and in death.  She is also a keeper of traditions, carrying the lore of tribes all the way back to the beginning.

A Galliard can rouse the pack from self-pity and suffering when their claws are needed for battle.  She can speak caution to a Ragabash, draw a Theurge from his reverie, soften the heart of a Philodox, and soothe the anger of the Ahroun.  The Galliard’s art and performance may take many forms, she might be a dancer, a storyteller, a musician, or a bit of everything rolled into one.  She may even be a leader in times of war.  When the battle is done, hers is the voice first raised to praise the sacrifices made by the fallen, and the triumphs of those who still live to fight again

  **Quote:**  *"You should be afraid, brothers and sisters.  This is Kyrrth’takla, Beast of a Thousand Mouths, they have awoken.  The stories of its strength are terrifying.  But I know you. I’ve been honored to fight alongside you, and I know you will not be afraid.  What you want is the glory of tearing this abomination apart, and my brothers and sisters, we will have it!"*
  
  <img 
  src='https://imgur.com/dmDtIEg.jpg' 
  style='width:200px' />
*Image credited to:https://vignette.wikia.nocookie.net/heroes-of-camelot/images/c/c4/WolfrikHumansbaneT1.jpg/revision/latest?cb=20160124204303*  

  <div class='pageNumber'>17</div>
<div class='footnote'>PART 2 | GALLIARD</div>
  
  \page
  
  <div>
## Class Features
As a Galliard, you gain the following class features
#### Hit Points
___
- **Primary Ability:**  Charisma
- **Hit Dice:** 1d8 per Galliard level
- **Hit Points at 1st Level:** 8 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d8 (or 5) + your Constitution modifier per Galliard level after 1st

#### Proficiencies
___
- **Armor:** Light Armor
- **Weapons:** Simple weapons, hand crossbows, longswords, rapiers, shortswords
- **Tools:** None

___
- **Saving Throws:** Dexterity, Charisma
- **Skills:** Choose any three
  
#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
- *(a)* a rapier, (b) a longsword, or (c) any simple weapon
- *(a)* a diplomat's pack or (b) an entertainer's pack
- Leather armor and a dagger
  </div>
  <br>
  <br>
<div style='margin-top:140px'></div>

### Pack Inspiration
  At 1st level, the Galliard can channel their spiritual energy once per long rest to guide those within a 10 ft radius.  When this is used, each ally of the Garou receives a 1d4 bonus to one ability check, attack roll, or saving throw it makes within the next 10 minutes.
  <br>
  <br>    
### Gift of the Galliard
  At 2nd level, the Moon Dancers burn with passion and song, and so Luna gives them Gifts that allow them to weave dream, fantasy and emotion into a tapestry that serves Gaia’s best interests.  That Galliard spends one Gnosis point and chooses one of the following:
* **Beast Speech -** The Garou may instinctively understand and communicate with any natural animals, from fish to mammals.  She need only speak normally to be understood by animals, along with a touch of appropriate body language--there is no need to bark like a dog.  This doesn't change animals basic reactions or dispositions; most are still afraid of predators such as werewolves.
  * **Call of the Wyld -** The Galliard may send her howl far beyond the normal range of hearing and imbue it with great emotion, stirring the hearts of fellow Garou, wolf, dog, or those of animals similar in nature for miles.  Any within range is determined by the DM, and is urged to go to the location of the call.  This however does not control or manipulate the animal in any way after it has arrived, it simply gets them there.  And can communicate any information the Garou asks if willing.
  * **Mindspeak -** Invoking the power of a waking dream, the Garou can place any chosen characters into silent communication.  1 Gnosis point per subject if willing.  Opposing willpower saving throws if unwilling, if successful the link is established for 1 min, after that rerolls will have to be made.  All beings must be in line of sight.  The Mindspeak ends when all the participants want it to, or on the turn the Galliard fails the roll against an unwilling member.
  * **Perfect Recall -**  The Garou is able to remember and relive any memory with perfect clarity.  The player may spend one Gnosis point to perfectly remember any one detail, no matter how small, from any point in her character’s entire life.
   <br>
   <br>
  ### Rite of Passage
  When you reach 3rd level, the Garou petitions himself to a tribe, in what is known as the Rite of Passage.  Once completed, he accepts that Tribe’s spirit totem as his own. Your Tribe grants you features at 3rd,6th, 11th, and 17th levels.
  <br>
  <br>
    <div class='pageNumber'>18</div>
<div class='footnote'>PART 2 | GALLIARD</div>
  
  \page
  
  ### Howls
  A Galliard howl is not an inarticulate cry--it can communicate a great deal of information.  Many howls incorporate the Garou language.  Just as every Philodox studies the Litany, any Galliard should be well versed in all the common howls.  Any party that the Galliard considers his pack can receive the messages of this spiritual howl.  The Galliard can spend 1 action to alter his vocal cords in any form if needed to invoke these howls.  Those within 60 ft are affected.  The Galliard can only use 1 per short rest starting at 4th level, 2 at 13th level, and 3 howls at 20th level.
  
   **Anthem of War -** This howl is a call to battle, Galliards use this to rally the troops.  All allies within 60 ft gain advantage on Initiative if used.  Additionally, if the Garou is surprised at the beginning of combat, and isnt incapacitated, you can act normally on the Galliards first turn, but only if you enter Rage first. 
  
   **Snarl of Precedence -**  This short, violent outburst is directed against a chosen foe within 60 ft you can see.  Packs use this snarl to coordinate tactics.  Any and all attacks until the end of the Galliard’s next turn towards the target is made with advantage.  If any allies within 60 break off from this tactic and attack another target within the same range, the advantage ends.
  
   **Song of Mockery -**   Not a howl in its own right, this is more of a pitch, a sort of “sarcastic tone”.  It is the equivalent of an obscene gesture given alongside a speech.  This howl targets a creature within range, and all attacks and actions that can be rolled at disadvantage do so until the end of the Galliards next turn.

  ### Extra Attack
At 5th level, the Galliard receives an extra attack action.

  ### Distractions Gift
  At 7th level, the Galliard can make distracting yips, yelps, and howls to divert the attention of his target.  Any time as a reaction, the Galliard can turn the highest numbered die from the damage rolled into a 1 instead for every 2 gnosis spent.   The Galliard has to see the target and be within 120ft. 
  
  If the Galliard spent more Gnosis than dice available, the extra amount of Gnosis spent per die can be rerolled and reduced from any of the bonus damage the victim of the target would have received instead.  Any remaining is Gnosis that is overspent after that is just lost.  This can be a gamble on the Galliard’s part, but it can also be lifesaving.
 
  ### Eye of the Cobra
  At 9th level, any target the Galliard can see  within 60 ft are drawn to the Galliard, by some spiritual force.  Target must roll a Wisdom save vs Galliard’s spell save DC.  If the target fails, he stops whatever action he is doing, until he gets within 5 ft of the Galliard. Once the target gets within 5 ft, the gift ends.  
  * **Cost.** 3 Gnosis
  ```
```
  ### Delirium
  Starting at 10th level, when the Garou is in Crinos form, it can use this ability to strike fear in his enemies.  Wisdom Save vs Garou’s Spell Save DC to those who  can see the Garou within 120ft.  On a failed save, they are frightened.  If successful they are immune.

  ### Master of Howls
  At 14th level, the Galliard can use Snarl of Precedence and Song of Mockery as a bonus action instead of a full action.

  ### Fabric of the Mind
At 18th level, the Galliard can summon any creature they can think of with the power of their imagination.   The player rolls a 1d20 + Gnosis spent for the maximum CR of a type of creature(min 1 Gnosis)  The Galliard then describes the looks of any creature he can imagine, in as much detail as he wants to the DM, and the DM takes that information and the results of the roll to produce the creature.  
  
  The creature has the same stats as their respective stat block, but doesn’t have any Legendary Actions.  Also, the Garou must spend equal amounts of Gnosis each round to keep the power of his imagination a reality.
  <div class='pageNumber'>19</div>
<div class='footnote'>PART 2 | GALLIARD</div>


  
  \page


 <div class='classTable wide'>
##### Ahroun
| Level | Proficiency Bonus |Rage |Gnosis |  Features | Rage Damage Bonus | Gifts Known | 1st | 2nd | 3rd | 4th | 5th |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1st | +2 | 1| 0| Soak Damage (d12), Garou Forms | +2 | 1 | 2 | — | — | — | — |
| 2nd | +2 | 1| 0| Rite of Talisman Dedication | +2 | 1 | 3 | — | — | — | — |
| 3rd | +2 | 1| 3| Rite of Passage; Tribal Feature | +2 | 1 | 3 | — | — | — | — |
| 4th | +2 | 2| 4| Ability Score Improvement, Claws of the Ahroun | +2 | 1 | 4 | — | — | — | — |
| 5th | +3 | 2| 5| Extra Attack, Rage Heal (d8) | +2 | 1 | 4 | 1 | — | — | — |
| 6th | +3 | 2| 6| Tribal Feature | +2 | 2 | 4 | 3 | — | — | — |
| 7th | +3 | 3| 7| Klaive | +2 | 2 | 4 | 3 | 1 | — | — |
| 8th | +3 | 3| 8| Ability Score Improvement | +2 | 2 | 4 | 3 | 1 | — | — |
| 9th | +4 | 3| 9| Brutal Critical (1 die) | +3 | 2 | 4 | 3 | 1 | — | — |
| 10th | +4 | 4| 10| Delirium, Rage Heal (d10) | +3 | 2 | 4 | 3 | 1 | — | — |
| 11th | +4 | 4| 11 |Tribal Feature | +3 | 2 | 4 | 3 | 3 | — | — |
| 12th | +4 | 4| 12| Ability Score Improvement | +3 | 2 | 4 | 3 | 3 | 2 | — 
| 13th | +5 | 5| 13| Brutal Critical (2 die) (2) | +3 | 3 | 4 | 3 | 3 | 3 | — 
| 14th | +5 | 5| 14|  Grand Klaive | +3 | 3 | 4 | 3 | 3 | 3 | 1 |
| 15th | +5 | 5| 15| Kiss of Heliou Gift, Rage Heal (d12)) | +3 | 4 | 4 | 3 | 3 | 3 | 2 
| 16th | +5 | 6| 16| Ability Score Improvement | +4 | 5 | 4 | 3 | 3 | 3 | 2 
| 17th | +6 | 6| 17| Tribal Feature | +4 | 6 | 4 | 3 | 3 | 3 | 3 | 
| 18th | +6 | 7| 18| Roar at the Moon | +4 | 7 | 4 | 3 | 3 | 3 | 3 |
| 19th | +6 | 7| 19| Ability Score Improvement | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 
| 20th | +6 | 8| 20| Ahroun Frenzy | +4 | 7 | 4 | 3 | 3 | 3 | 3 | 
</div>
  
  ## Ahroun 
  The Garou’s connection to the moon is much more extensive than legends state.  Every phase has its secret, but human myth comes close to understanding the truth in one aspect: the full moon floods the Warrior with Rage.  The Ahroun is the living weapon of Gaia, the lord of bloodshed.  He is the warrior among a race of warriors, the champion of martial people.  He is ever ready to kill, and to die if need be.
  
 
The Ahroun are respected, but also treated with some level of dread.  Their killing instinct is inborn; even a Full Moon just past his First Change is more lethal than many veterans of other auspices.  Their elders are few--it’s a rare Ahroun that survives the countless battles that are his birthright--but all the more terrifying for their experience.  Like the Galliard, the Ahroun is an inspiring leader in time of war, but he leads with deeds and action. 
  
  He is first into battle and last to retreat--if he ever retreats at all.  In times of peace, he relinquishes command to others, but remains ever vigilant, knowing his talent for war will be needed again all too soon.
  ```
```
**Quote:** *"No more running. No more surrender.  Here we stand and here we fight.  We do not walk to Gaia’s arms tonight--we will swim there, in a river of our enemy’s blood!  Let them hear your howls and know true fear!"*
  <img 
  src='https://imgur.com/p40MPbO.jpg' 
  style='width:200px' />
 *image source: https://vignette.wikia.nocookie.net/whitewolf/images/3/36/Wendigo_%28Oeste_selvagem_1%29.jpg/revision/latest?cb=20181227192615* 
  Onyx Path, Werewolf the Apocalypse

  <div class='pageNumber'>20</div>
<div class='footnote'>PART 2 | AHROUN</div>
  \page
## Class Features
As a Ahroun, you gain the following class features
#### Hit Points
___
- **Primary Ability:** Strength
- **Hit Dice:** 1d10 per Ahroun level
- **Hit Points at 1st Level:** 10 + your Constitution modifier
- **Hit Points at Higher Levels:** 1d10 (or 6) + your Constitution modifier per Ahroun level after 1st

#### Proficiencies
___
- **Armor:** All armor, shields
- **Weapons:** Simple weapons, martial weapons, Klaives
- **Tools:** None

___
- **Saving Throws:** Strength, Constitution
- **Skills:** Choose two skills from Acrobatics, Animal Handling, Athletics, History, Insight, Intimidation, Perception, and Survival

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
- *(a)* chain mail or *(b)* leather armor, longbow, and 20 arrows
- *(a)* a martial weapon and a shield or *(b)* two martial weapons
- *(a)* a light crossbow and 20 bolts or *(b)* two handaxes
- *(a)* a dungeoneer's pack or *(b)* an explorer's pack
<br>
<br>
  
### Soak Damage
 At first level, the Ahroun Warrior can use his rage in different ways compared to the other Auspices.  Any damage the Garou receives in combat, the Ahroun can choose to spend a Rage Point to absorb 1d12 + Constitution modifier worth of damage. 
  
  This can only be used in Crinos Form as a reaction.  This increases to 2d12 at 6th level, 3d12 at 12th level, and 4d12 at 17th level. 
  
  <br>
  <br>
  ### Rite of Talisman Dedication
  Beginning at 2nd level, the Garou can choose pieces of equipment that phase with him when switching forms.  This rite allows a Garou to bind objects to her body, allowing them to fit her various forms( pants will grow to accommodate the Crinos form rather than splitting at the seams, also useful if a Garou ever decides to don armor)  Fetishes such as Klaives remain with the werewolf in all forms automatically without this rite. 
  
  One Gnosis point is spent to activate this Rite and remains active until the next long rest, and the character may never have more objects bout to himself than his Gnosis score.  Conceptually linked groups of objects may count as a single object.  A set of clothing is considered one object, rather than one shirt, 2 socks, ect.   Objects will generally resize themselves to accommodate the character’s various forms, but may simply meld with the character in forms where they can be of no use- for example, a knife may become a knife-shaped tattoo in Lupus.
  
### Rite of Passage
  When you reach 3rd level, the Garou petitions himself to a tribe, in what is known as the Rite of Passage.  Once completed, he accepts that Tribe’s spirit totem as his own. Your Tribe grants you features at 3rd,6th, 11th, and 17th levels.
  <br>
  <br>
  ### Claws of the Ahroun
  Starting at 4th level, the Ahroun has the ability to take one action to sharpen its claws and recieves to +1.  It costs 1 rage point to do so.
  
* Additionally the Ahroun can Spend 1 extra point of Rage on a successful attack , to bury her claws into the victim, where they stick after breaking free from the Garou’s fingertips.  
  
  Until the victim takes a round to pull them out, they suffer disadvantage to all actions.  The Garou’s claws take a full round to regenerate.
  <br>
  <br>
  ### Extra Attack
  At 5th level, the Ahroun receives an extra attack action.
  <br>
  <br>
  ### Rage Heal
  Starting at 5th level, the Ahroun can further manipulate his rage to accelerate healing and rolls 1d8 + Constitution worth of HP for every point of rage spent.  This increases to 1d10 at 10th level, and 1d12 at 15th level.
  <br>
  <br>
  
  <div class='pageNumber'>21</div>
<div class='footnote'>PART 2 | AHROUN</div>
  
  \page

  ### Klaive
  At 9th level, Gaia's Chosen may use the Rite of the Fetish to bind spirits into appropriately crafted and consecrated vessels.
  
  Majority of fetishes are crafted fro natural materials. *wood, bone, hide, clay*; Garou adorn them with carved river stones, feathers, beads, and other markings to honor and appease the spirit within.
  
  The signature weapon of the Garou Nation, klaives are fetish daggers of a singular design, made to be used in Homid and Crinos Form with ease.  Klaives are rare weapons made from the purest silver.  A war-spirit is usually bound to the klaive.  key notes on the Klaive:
  * Requires attunement after it is made and bound with a spirit.
  * Like Rite of talisman dedication, the Garou can summon the klaive in and out of existence.  A useful tactic when changing forms, especially while in Lupus and can't use the Klaive.
  * The Klaive is made of Silver, is considered a Shortsword, Gnosis grants it a **+2 and magical.**
  * When the Garou spends 2 Gnosis to activate the spirit bound to the Klaive.  Whenever the Klaive hits a target, it deals an extra 1d8 radiant damage.  The Klaive retains this activation until its owner takes a short or long rest, or galls unconscious in any way.
  <img 
  src='https://imgur.com/QlnDsqI.jpg' 
  style='width:325px' />
  *Image source from: https://vignette.wikia.nocookie.net/whitewolf/images/f/fe/Fianna_%28Idade_das_Trevas%29_%281%29.jpg/revision/latest?cb=20181227172119*
  Werewolf the Forsaken, White-wolf
  
  ```
```
  ### Brutal Critical
  Beginning at 9th level, you can roll one additional weapon damage die when determining the extra damage for a critical hit with a melee attack.  This increases to two additional dice at 13th level and three additional dice at 17th level.
  <br>
  <br>
  ### Delirium
  Starting at 10th level, when the Garou is in Crinos form, it can use this ability to strike fear in his enemies.  Wisdom Save vs Garou’s Spell Save DC to those who  can see the Garou within 120ft.  On a failed save, they are frightened.  If successful they are immune.
  <br>
  <br>
  ### Grand Klaive
  
At 14th level, the Garou can now create a Grand Klaive.  The concept is similar to the Klaive but more powerful.  The Grand Klaive has 2 spirits bound to this weapon, and they both serve a purpose when activated.
  
* Considered a longsword which the blade is made of silver (1d10), by spending 3 Gnosis it becomes a **+3 and magical**
* Like the Klaive, once its activated it deals 2d8 radiant damage when successfully striking a target
  
As far as the second War spirit bound to the Klaive, it can be activated by spending a separate amount of Gnosis to use whatever magical ability that spirit carries.  Pick one transmutation spell from the wizard spell list of 7th level or lower.  This cannot be changed once chosen.  Optionally, the DM can base it off a random roll.  That spirit represents that ability for the remaining life of the weapon.
  
* It costs 3 Gnosis to activate the Grand Klaive’s second ability.
* The second ability cannot be used again until the owner finishes a short rest.
  <br>
  <br>
  ### Kiss of Heliou
  At 15th level, the Ahroun can invoke the sun's power to gain immunity to fire.   **Costs 3 Gnosis**
  
* Additionally, the Ahroun can spend an extra rage point to ignite any portion of his body and keep it burning as he desires.  The Garou rolls an extra 1d8 fire damage when successfully hitting a target with its claws or bite attacks.
  <div class='pageNumber'>22</div>
<div class='footnote'>PART 2 | AHROUN</div>
  
  \page
  <div class='pageNumber'>23</div>
<div class='footnote'>PART 2 | AHROUN</div>
  ### Roar at the Moon
  
At 18th level, the Ahroun enrages a fierce roar to the Moon Goddess Luna.  Once per long rest, Luna fuels her Ahroun Warriors with Rage.  1 point of Rage costs 5 Gnosis (max 4).
  <br>
  <br>
  ### Ahroun Frenzy
At 20th level, the Ahroun is no longer limited to the amount of rage spent in a round, he invokes the inner beast.  He spends all Rage points he has for the Glory of battle. 
  
  While activated the Garou has to be in Crinos form, cannot use Gnosis, Gifts, or has the ability to stop until the target is killed.  If the target is not killed after the last point of rage is spent, it continues to attack with disadvantage until it misses.  Only then, does the attacks stop. 
  
  The Garou changes to his breed form, (unless Metis), and has 4 levels of exhaustion.  This attack is the Pride of Ahrouns abilities.  Usually a last resort by the Garou.
  <br>
  <br>
  ##### Exhaustion Levels
  <table>
    <tr>
      <td>**Level**</td>
      <td>**Effect**</td>
    </tr>
    <tr>
    <td>**1**</td>
    <td>Disadvantage on Ability Checks</td>
    </tr>
    <tr>
      <td>**2**</td>
      <td>Speed Halved</td>
    </tr>
    <tr>
      <td>**3**</td>
      <td>Disadvantage on Attack rolls and Saving Throws</td>
    </tr>
    <tr>
      <td>**4**</td>
      <td>Hit Point Maximum is Halved</td>
  </table>
  <img 
  src='https://imgur.com/r1n6f2r.png' 
  style='position:absolute; top:500px; right:200px; width:400px' />
  <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
  *Image Source From:
  https://media.ex-cdn.com/EXP/media.phunutoday.vn/files/upload_images/2014/12/27/nguoi-soi-1.jpg*
  Onyx Path, Werewolf the Apocalypse
  \page
# Part Three: Choose your Tribal Archetype
   
  Once a Garou completes his Rite of Passage, he is welcomed into one of the 5 Tribes of the Garou Nation.   Before the completion of this rite, he is a cub, and therefore treated as little more than a child.  He may not learn tribal Gifts or recieve the tribe’s deepest secrets.  Even Metis cubs are shut out from such sacred knowledge.  Each Tribe is empowered by their own sacred spirit animal.  Each of the Tribes originally came from a different region of the world.  Each tribe’s Kinfolk and societies reflect these different cultures.
  ## Children of Gaia
  This Tribe does not claim an ancestral homeland, considering itself to be made up of citizens of Gaia and ambassadors of peace and justice.  Some Garou make the mistake of thinking this makes them weak, but when the Children of Unicorn choose to fight, they fight with righteousness.
  ## Fianna
  The descendants and spiritual children of Stag, the Fianna are loremasters, warrior-poets, and drinkers par excellence.  They are known for their fiery passions and insights, and, less charitably, for stubborness and veniality.
  ## Get of Fenris
  The Get of Fenris is proud of its heritage, and prouder still of their reputation as fearless warriors.  They are unapologetically blood-thirsty and savage, and carry a wide survivalist streak.  Fenris himself is their tribal totem.
  ## Shadow Lords
  The Shadow Lords heritage can be traced back among the craggy cliffs and rocky foothills of the mountains.  They are ruthless in their efforts to direct the Garou Nation, and believe that the might of their totem, Grandfather Thunder, makes them fit to rule.
  ## Silver Fangs
  The revered leaders of the Garou Nation--at least to hear them tell it--the Silver Fangs follow Falcon as their totem.  The tribe has a long history of pure breeding, nobility, and courage.  Their modern image, however, also includes accusations of inbreeding and insanity.
  
Theoretically, a cub can approach any tribe.  A Garou is not born into a tribe, he must prove himself worthy during his Rite of Passage first.  A cub with a Garou parent usually makes the same choice as his mother or father when deciding what tribe to petition, but he does not have to do so.  But a cub with a long lineage will be hounded to “make the right choice.”
  ```
  <img 
  src='https://imgur.com/x07GvEq.jpg' 
  style='width:325px' />
  *Image Source from:https://www.dmsguild.com/images/4261/112134.jpg*
  Onyx Path, Werewolf the Apocalypse 20th anniversary edition
  
  <div class='pageNumber'>24</div>
<div class='footnote'>PART 3 | TRIBES</div>
  
  <div style='margin-top:140px'></div>
  ## Tribal Archetypes
  <p>A Garou petitions himself to join one of the known tribes during his Rite of Passage.     
  The Garou is then accepted by the spirit totem of the tribe, and even takes on certain characteristics in their forms as well.  Each tribe is blessed with Gifts that use Gnosis, the spirit energy of the wolf.</p>
  
  \page


  # Get of Fenris
  Even among a race of warriors, the Get of Fenris are the most warlike.  The Fenrir, as they’re like to be called, value a glorious death over a peaceful old age.  They wear their scars with pride, howl the glory of their victories, and revel in the fear that they spread among the minions of the Wyrm.  To the Get, compassion is a luxury, not a virtue--the greatest virtues are valor and strength.
  
The most brutal and violent sagas of the regions pale before the lore of the Get.  Their Galliards joyously recount grim tales of bloody death against impossible odds, of the eternal glory to be found on the battlefield.  They have told stories of Ragnarok, for the Apocalypse, for centuries -- and they are ready for it.
  
Blood alone doesn’t make a Get of Fenris.  A cub could be the finest Pure Breed, but if he can’t make it through the bloody Rite of Passage, he’s of no use to the Fenrir.  Some cubs don't even survive that first test.  Harsh as it is, the Rite of Passage reflects the grim and fatalistic nature of life among the Get.  The battles against the Wyrm will be no gentler, --and the Fenrir never run from battle.  Every child of Great Fenris, no matter his or her auspice, must be ready to die gloriously for the Mother.  This creed often seems contradictory to lupus cubs, who are used to survival as the first and most pressing mandate.  Luckily, enough wolf-born find their Rage that the Get haven’t fallen too far behind in their ratio of homid-to-lupus members.
  
To make matters worse, many Get of Fenris embrace very elitist attitudes not just to strenght and valor, but even to sex and ethnicity.  This has been a source of internal conflict within the tribe for many years.   Although it’s not easy for outsiders to see, the Fenrir do possess admirable virtues beyond their courage.  There are long-standing traditions of females doing as well as males in many Get septs-- they frequently have to work very hard to earn them their status.  Metis can excel as well, if their deformities don’t impede their actual strength--one who’s ugly as sin and has a terrible speech impediment will still earn much glory if he can fight to the tribe’s exacting standards.  Many Get also care very deeply for their Kinfolk, taking family ties exceptionally seriously.  This is a double standard for the Kin, of course:  their werewolf relatives hold them to brutally high standards, but also defend them with great passion.  
  
At every level, tribe society idealizes strength above all.  Wisdom and cunning are valued, but as a complement to might, not a substitute.  Fenrir leaders, or jarls, must earn their position through grueling physical trials, and be prepared to hold them in the same way.  Tribal moots are full-moon affairs, beginning with a vicious gauntlet-running to determine who’s worth to participate in the rites of the tribe.   Rites of Renown entail bloody runes carved into werewolf hide, even mystical rites dealing with spirits involve ritualized combat between rite-master and spirit as often as not.  Even their belief in an afterlife reflects the concept of Valhalla, a grand battlefield awaiting its heroes. 
  
And for all their faults, the Get of Fenris produce many heroes.  Their creed of strength is simple, but not simplistic -- it teaches many Fenrir to master their Rage, to serve as examples of courage to the rest of the Nation, and to win battles that others would lose or abandon.  They are remarkably loyal to those who earn their respect, and their harsh standards encourage other Garou to fight harder if they want to keep the Fenrir’s allegiance.  With the Apocalypse at hand, no tribe is more ready to tear the Wyrm apart regardless of the cost.
  
**Appearance:** Strong Fenrir blood manifests as huge gray wolf forms with broad shoulders and vicious jaws.  There are precious few Get whose hides aren’t marked with scars and tattoos.  Some even brand their fur or ceremonially carve runes into their flesh.
  
**Tribal Totem:**  Fenris, the Great Wolf, one of the mightiest of war totems.  Other spirits allied to the Get include Aegir, Hrafn the raven-spirit, the Norns, and Surtur, spirits both warlike and wise.  
  
  **Quote:** *"Pain is my lover. Death is my sister.  Gaia is my Mother, and Great Fenris is my Father.  You have NOTHING for me to fear!"*
  <br>
  <br>
  
  <img 
  src='https://imgur.com/KH6ETKi.jpg' 
  style='width:325px;mix-blend-mode:darken' />
 *Image source from: https://i.pinimg.com/originals/5e/7d/54/5e7d54219f077f91d3fba5117cb1c275.jpg* 
  Onyx Path, W20 Sourcebook
<div class='pageNumber'>25</div>
<div class='footnote'>PART 3 | GET OF FENRIS</div>
  
  \page
  
  ## Get of Fenris Features
  Fierce fighters one and all, the Get beseech their spirit allies for Gifts of war.  Even their Ragabash and Theurges are expected to stand out in battle.

* All gifts cost one action, unless stated otherwise
* Gifts cannot stack similar bonuses, but can be used to extend durations if applicable.
  
  #### Lightning Reflexes
    At level 3 the Get of Fenris can call upon their tribal spirit to effortlessly switch from offense to defense as the needs of battle demand. 
  
  **cost-** The Garou spends 1 Gnosis to activate, and until his next turn, they have advantage on all Dex Saving Throws, as well as giving them a bonus action to Dash, or Disengage without an attack of opportunity.
  
  
  #### Fangs of the North
  At Level 6, Blue smoke rolls off of the Fenrir’s claws and teeth, which are transformed into curving daggers of hardened ice.  
  
  **1d8 Necrotic damage** added to any claw or bite attacks(cannot be used in Homid Form)Increases to 2d8 at 10th level, 3d8 at 15th level, and 4d8 at 18th level.  The duration lasts for up to 1 minute, unless knocked unconscious or choosing to deactivate the gift. Costs 2 Gnosis
  
  
  #### Might of Thor
   At 11th level, the Get can increase his strength tremendously 
  
  **cost-** spending 1 rage and 3 Gnosis, until his next turn, increases his strength score +4, and also can exceed the 20 cap.  
  
  The effects applied to any damage, attack, feats of strength, or saving throws where strength is involved.
  
  
  
  #### Beyond Fenrir
  At level 17, the Get has the ability to go Beyond the normal state of himself.  He is a Get, but greater.  For every point of Gnosis spent, the Garou has the ability to increase any ability score by that amount (max 30).  Can get scores over 20 in this fashion. 
  
  **cost-**is based on the amount the Garou wishes to spend, and the effects last for 1 minute.
  
  
  <div class='pageNumber'>26</div>
<div class='footnote'>PART 3 | GET OF FENRIS</div>
  
  ```
```
  ## Get of Fenris Stereotypes of the other tribes:
  
  **Children of Gaia:**  *"You think you were given these teeth, these claws, so you could sit about and talk of dreams of peace?  FIGHT, you sheepfuckers!"*
 <br><br> 
  **Fianna:**  *"Your ancestors were almost as strong as ours, and you’re almost as strong as we are.  What?  It’s a compliment."*
<br><br>
  **Shadow Lords:**  *"Their schemes against the other tribes are treacherous, which is why they are not friends.   Their schemes against the Wyrm are brilliant, which is why we haven’t cut them down."*
  <br><br>
  **Silver Fangs:**  *"Speak with the voice of a true king, and we’ll follow.  You’re too weak to be worth it any other way."*

  
  
  \page
  

<div class='pageNumber'>27</div>
<div class='footnote'>PART 3 | SILVERFANGS</div>
  # Silverfangs
  The Silver Fangs are first among the tribes, as they are quick to point out. Descendants of great heroes and monarchs, every one, the tribe of Falcon claims the role of leadership of the Garou Nation. They trace their bloodline back to the Progenitor Wolf, a genealogy of the noblest human blood and the finest wolf ancestors. Through the ages, they have been at the forefront of the war, the proudest and most magnificent Garou — and to hear the Silver Fangs tell it, that is still true. Other tribes have their doubts, though. Some charge that the Silver Fang’s obsession with pure blood has brought them to inbreeding, and their once-clear minds have grown feeble and clouded through the generations. <br><br>
 Weak kings demand respect for the deeds of their ancestors, not their own. Mad leaders care more for the details of their courtly traditions than for the war against the Wyrm. Far too many fall to Harano for them to be a healthy tribe. Both viewpoints have some truth to them. The Silver Fangs do indeed descend from great heroes, and they have also suffered from their preference for aristocratic Kinfolk over healthy and intelligent Kin. Many are as bad as their critics claim, but some still shine with the light of old heroism. In some ways, they are exactly the exemplars of the Garou they claim to be — the strengths and the afflictions of the Garou Nation are reflected in the story of the Silver Fangs. From their First Change, the Silver Fangs learn that they are meant to rule — not that it is their destiny, or their right, but their purpose.<br>
 The best of them interpret this mandate as a form of noblesse oblige: that they must lead by example in peace and in war. The worst seize upon it as justification for tyranny. Their aristocratic Kinfolk families raise their children with a sense of being “above the rest.” Their lupus Kin, of course, have no real sense of nobility per se. But the Fangs carefully protect them with the fullness of their resources, so many Silver Fang lupus still enjoy a more privileged youth than do the wolf-born of other tribes. Metis are treated somewhat paradoxically: on the one hand they are signs of impurity that impugn the famous Silver Fang pride, but on the other, metis with two Fang parents have arguably some of the purest blood in the Nation. A metis may never be king, but he may still receive some respect for his forebears (if not for his parents’ shame).  Silver Fang society borrows a few “regal” traditions that are not seen in other tribes.<br><br> 
They organize into Houses first and camps second, and their territories (or “protectorates”) are ruled by kings — traditionally Ahroun. They divide their courts into two lodges: the Lodge of the Sun deals with material and worldly matters, while the Lodge of the Moon focuses on spirituality and issues concerning the wolf lines. Their moots are remarkably convoluted, hinging on baroque rituals of etiquette that would scarcely be tolerated by any other tribe. As the Apocalypse unfurls, the role of the Silver Fangs is deeply controversial. Many Garou uphold tradition by acknowledging the Fangs as still worthy of leadership. Others treat them as figureheads to be openly respected and then quietly ignored when necessary. Still others chafe to be rid of them, the Shadow Lords most of all.
 But the Silver Fangs have yet to fall completely. The charisma of their forebears is still strong in the tribe; those that are willing to reach out to the other tribes are surprisingly adept at rallying septs to unite for war. Time will tell if these last vestiges of true nobility will be enough to keep the tribe, and by extension the Garou Nation unified, or if the Silver Fangs have been tarnished and blunted too long.<br><br><br><br>
  
  **Appearance:** Silver Fangs are of aristocratic human stock,
and tend to have strong family resemblances within their
bloodlines. Their wolf forms have clean silver or white coats,
long jaws and full tail brushes. They are fond of jewelry and
ornately worked equipment as a sign of their status.<br>
  <br>
  
  
**Tribal Totem:** Falcon, who inspires from on high. Silver
Fangs are particularly dedicated to allied avian or solar spirits, such
as Firebirds, the Talons of Horus, and the Children of Karnak.
    <br><br><br><br>
  **Quote:** *"I ask nothing of you that you should not want to give for Gaia.  Stand with me and She may yet be saved!"*

  <img 
  src='https://imgur.com/SUzNsEk.jpg' 
  style='width:250px;mix-blend-mode:darken' />
 *Image source from:https://i.pinimg.com/474x/f4/b1/75/f4b17514a5999777ecd05862c025c379--werewolf-art-teen-wolf.jpg* 
   Onyx Path, W20 Sourcebook

  \page
  
  ## Silverfang Features
  The regal Silver Fangs are the traditional leaders of the Garou, and their Gifts reflect -- and support --that birthright.<br><br>
  #### Eye of the Falcon
  At 3rd level, the Garou’s vision gains the predatory clarity of a bird of prey.  
  **Cost-** 2 Gnosis and all Ranged attacks and perception based checks have advantage for 1 min.
  <br><br>
  #### Inspiration
  At 6th level, when others look to the Silver Fang for leadership in battle, this Gift helps them to live up to that trust.  The Garou employs this Gift to lend her resolve and righteous anger to those who share her cause.  
  **Cost-** 2 Gnosis spent and the Garou choses any single ally in battle within 60 ft to gain 1d8 to apply to a roll within the next 10 min.  Can only apply to one individual at a time.
  <br><br>
  #### Side Step Death
   At 11th level, legends say that when the first Silver Fang died, he was reborn with this Gift.  The Fang simply sidesteps what would have become his deathblow.  
  **Cost-** 5 Gnosis, once activated, any damage that would reduce the Garou to 0, the Umbra consumes him and transfers him in any location other location from where the act took place within 60ft, and HP is now 1 instead.
  <br><br>
  #### Renew the Cycle
   <p> At 17th level, the Silver Fang is blessed with this Gift that allows the correction of a grievous wrong done to the natural cycle of Gaia.  The undead, whose very existence is an affront to the natural order of things, wither and crumble to dust when struck by the power of this Gift. 
  </p><p>**Cost-** Undead rolls Con Save against current Gnosis DC, (max 20), if failed, any undead with a CR half of players level within 60ft is instantly destroyed. If save succeeds they suffer 6d10 + level radiant damage.  Those with higher CR rating, if save fails, they take 6d10 + level radiant, success takes half.</p>


```
```
## Silver Fang Stereotypes of Other Tribes:<br><br>
  **Children of Gaia:**  *"They share our dislike of dissension, although they tend to forgive rogues and rebels too easily."*<br><br>

**Fianna:**  *"Their loyalty is much appreciated, even if their etiquette is...variable."*<br><br>

**Get of Fenris:**  *"Loyal and honorable vassals when they acknowledge your position  -- dangerous savages when they claim to perceive some weakness in you."*<br><br>

**Shadow Lords:**  *"They covet a throne, but do not command the respect necessary to hold it.  Perhaps they should direct more energy against the true enemy."*
  <div class='pageNumber'>28</div>
<div class='footnote'>PART 3 | SILVERFANGS</div>
  
  \page
  # Children of Gaia
  The Children of Gaia seem to be a study in contradiction. They are Gaia’s warriors, yet they want nothing more than peace. No Garou work harder and plead more humbly for cooperation between the tribes than they do. None grieve more when forced to shed the blood of a fellow werewolf. More than any other tribe, they value compassion for all Gaia’s children, even those that hold them in contempt. Many Garou mistake this compassion for weakness, — only to discover that the Children’s hatred of war doesn’t preclude the ability and will to fight — and fight well.<br>
  The tribe has its origins in the days of the Impergium, when they protested the practice of culling humans and fighting over territory. When the Garou Nation came to an accord and agreed to end the Impergium, the peacemakers who had led the effort formalized a pact with Unicorn and became the Children of Gaia. They are the only tribe born from an act of peace, and they take great pride in this origin. The Children of Gaia’s primary purpose is that of all Garou — fight the Wyrm, wherever it breeds and wherever it dwells. But their chosen secondary purpose is to mediate disputes and alliances among septs and packs, strengthening the Nation as a whole. It’s a difficult job, made more difficult by the contempt they face from many more martial tribes. But as they argue, it’s critical.<br>
The Children of Gaia are a comparatively numerous tribe. Rivals claim it’s because they shrink from combat — but that’s not true. They do well by adopting other Garou, any who ask. They are especially respectful of metis, treating them as equals. They have less of an advantage with lupus numbers, though several wolf-born that grew up not understanding the concept of “war” find the Children’s ideal most natural. Unicorn’s children are less concerned with strict rank and hierarchy. Though still powered by wolf instinct, they favor fairly loose pack and sept organization. Each sept has two elders who must excel at mediation: the Voice of the Goddess(always female) and the Arm of the Goddess (always male).<br>
The Children constantly involve themselves in the arena of other races’ politics, more so than many other tribes. They face the same limitations that all werewolves do where subtlety is concerned, but still they use what influence they can, particularly through their Kin, to promote agendas of compassion, peace and tolerance. The tribal creed states that the war for Gaia can’t be won without loyal hearts. It’s an uphill battle, though, and boundlessly frustrating. When the time comes for war, more than one Child of Gaia lets out a pent-up Rage that’s horrifying in its strength.


With the Apocalypse so close at hand, the Children of Gaia are facing many internal crises of faith. Humanity seems to come so far, and then it falls back into old patterns of hatred and bloodthirst. There are so few Garou to protect the world, and they turn on each other so quickly. Many of the tribe have fallen into Harano as the enormity of their task seems to be overwhelming. Some Children even argue that the secrecy of the Veil prevents them from properly educating humans and other races — that they would have the allies they need if they could just show the races what’s going on. These arguments cause rifts even within the tribe. All told, the odds seem impossible. But if they were to give up, the elders growl, they wouldn’t be the Children ofGaia. They wouldn’t be Garou.
  <br><br>
  **Appearance:** Strong Children of Gaia Pure Breed usually
manifests as a white dappling on a gray or brown coat. The
most renowned Children have a calm and serene bearing that
can be intimidating in its own right.<br><br>
**Tribal Totem:** Unicorn. The Children of Gaia tribal totem
is a powerful spirit of purity, compassionate in peace but
also ferocious in war. They prefer to strike pacts with totems
such as Dove and Narwhal, as well as gentle spirits of glade
and starlight.
<br><br>
  **Quote:** *"We’re Garou.  We draw out the toxins from our Mother’s blood, cut away Her cancers, slay the parasites feeding on Her flesh.  But once the surgery’s done, you have to bind the wounds back up, too."*
  <br>
  <img 
  src='https://imgur.com/SPXsu8v.jpg' 
  style='width:280px;mix-blend-mode:darken' />
*Image source from:https://i.pinimg.com/originals/b8/e2/6e/b8e26e895d81c8037c1f3eba1c821010.jpg*  
  Onyx path, W20 sourcebook
  <div class='pageNumber'>29</div>
<div class='footnote'>PART 3 | CHILDREN OF GAIA</div>
  
  \page
  ## Children of Gaia Features
  The Gifts of the Children of Gaia aid in calming others and strengthening themselves.  Yet those who would dismiss the most peaceful of the tribes as ineffective pacifists will be surprised to discover how well the spirits prepare the Children for the inevitability of battle.
  
  #### Mother’s Touch 
At 3rd level, the Garou channels spiritual power through her hands, mending the wounds of any other living creature. The Garou touches a creature, and heals 1d4/Gnosis point spent.  Cannot heal self, spirits, or any undead with this Gift.
#### Luna’s Armor  
At 6th level, the Child of Gaia invokes the moon’s sacred power.  Her body is briefly wreathed in a shimmer of moonlight, granting her Luna’s protection.  
  **Cost-**2 Gnosis Gains +2 AC and protection from Silver.
#### Dazzle 
At 11th Level, The Garou can flood a target’s mind with the glory and love of Gaia, rendering him charmed.  Charisma Save vs Garou’s Spellcasting DC.  If successful, the target is immune to this effect for the remainder of the day. 
  **Cost -** 3 Gnosis
#### Halo of the Sun
 At 17th level, The Garou speaks an ancient word sacred to Helios and is immediately surrounded by a sphere of blazing sunlight surrounding her in a radius of 30 ft.  Any creatures trying to hit the Garou do so with Disadvantage, also, anyone that finishes their turn inside the radius suffers 6d10 radiant damage.  This also applies to any creatures vulnerable to sunlight that take double damage.  
  <br>
  ```
```
  ## Children of Gaia Stereotypes of other Tribes:
**Fianna:**  *"There aren’t many who mourn their losses more keenly, or prize their victories more joyously."*
<br><br>
**Get of Fenris:**  *"You can admire their bravery and strength, but at the end of the day, war is something that we abhor and that they seem to cherish.  It’s horrifying."*
<br><br>
**Shadow Lords:**  *"Hard to tell what they love best:  their methods, their ambitions, or their successes."*
<br><br>
**Silver Fangs:**  *"Of all the failures we’ve endured, the Silver Fangs’ failure to keep the Nation unified has perhaps hurt all of us the most."*

  <div class='pageNumber'>30</div>
<div class='footnote'>PART 3 | CHILDREN OF GAIA</div>
  
  \page
  # Fianna
  Grief and joy, life and death--life is a series of contradictions, and the Fianna embrace them all.  The Tribe of Stag are passionate Garou who exult in the pleasures of the flesh as well as the more abstract delights of a song well-sung or a battle well-fought.  Their philosophy is far from a shallow “live in the now”concept, though.  The Fianna are prominent lorekeepers and bards, fascinated with the history of all tribes as well as their own.  Their Galliards have a particular place of honor within the tribe, but every auspice is expected to learn lessons from the past.<br>
The Fianna trace their origins back to Western Lands, where they had a particular fondness for the Celtic peoples. They stress this cultural identity perhaps more than most other tribes do; members aren’t as prone to marry outside Celtic descended
bloodlines, and they prefer to adorn their weapons and fetishes with knotwork representative of “the old days.” They endure plenty of old rivalries with other Western Garou that challenged their borders.  The Fianna try to be generous and forgiving where these rivalries are concerned, remembering but not making too much of it — an attitude their rivals rarely share.<br>
Strong passions and a powerful social streak run deep within the tribe. Their mirth is powerful, their loves intense, and their despair deep and prone to increasing into Harano. Introverted Fianna are rare, and don’t earn much sympathy; their tribemates tend to harass them to “loosen up” and enjoy the raucous gatherings more. Metis have it much worse. Fianna tradition holds that a deformed body reflects a deformed spirit, and treat their metis cubs with great severity — metis never hold positions of real authority within the tribe. It’s sadly ironic, then, that the Fianna, with all their hot-running passion and love of the romantic, are particularly prone to sin with other Garou and create these luckless children.<br>
The passionate, mercurial nature of the Fianna manifests itself even in their wolf-born. Fianna lupus take to art readily, though of course they prefer songs and howls above all. Some (both inside and outside the tribe) suspect that this commonality represents a dose of fae blood — there are plenty of old stories of the Fianna fighting alongside the Fey, and engaging in tragic romances with the Old Ones.<br>
In some ways, the Fianna consider themselves the guardians of Garou culture. They glorify the war every werewolf is born to fight, they sing tales of romance that stress the importance of clinging to one’s Kin, and they keep the stories of old victories and defeats. They leap into battle with exuberance, hoping to inspire their cousins to do the same. But even with no other tribe’s eyes upon them, the Fianna fight as ferociously as any Garou can.<br>
Yet thanks to old rivalries and quick tempers, the Fianna can be a divisive presence as easily as a unifying influence. It’s hard for them to resist a particularly well-crafted taunt, or to shake hands with a rival who’s spoken ill of or mistreated Kin. Some Garou don’t take them seriously; others aren’t able to laugh off a Fianna’s bouts of temper so easily.<br> It’s a good thing for the tribe that they’ve practiced the silver tongue as long as they have. Certainly whatever happens, the presence of a Fianna is prone to keep things lively and interesting.<br><br>
  **Appearance:** Fianna Pure Breed manifests itself as shining
red or black fur, and often surprisingly large Lupus form. Fianna
often use Gifts to make their eyes glow green, and teach their
cubs to howl with beautiful eloquence.<br><br>
**Tribal Totem:** Stag, who exemplifies the Fianna love of
life. Stag’s brood largely comprises animal spirits such as Rabbit,
Impala, the White Hart and the Hind, and some Naturae
such as the Brook, Dawn and Grain.<br><br>
  **Quote:**  *"The blood of heroes is on fire within us!  The ghosts of our ancestors swell with pride to see us stand strong and true!  The Wyrm itself trembles when we howl!  AAAAUURROOOOO!"*
  <br><br><br>
  <img 
  src='https://imgur.com/M5mBbF5.jpg' 
  style='width:325px;mix-blend-mode:darken' />
  *Image source from: https://i.pinimg.com/originals/09/f5/42/09f542c7c20ef310f6564a7d4a2c2d3e.jpg*
  Onyx path, W20 Sourcebook
<div class='pageNumber'>31</div>
<div class='footnote'>PART 3 | FIANNA</div>
  
  \page
  ## Fianna Tribal Features
  The Gifts of the Fianna speak to their vigorous natures and fae allies, and are often granted by spirits originating in their native lands.<br>
 #### Faerie Light 
 At 3rd Level, the Fianna conjures a small, bobbing sphere of light.   It’s no brighter than a torch, but that's usually enough to light the werewolf’s way or lead foes into an ambush.  <br>**Cost-** 1 Gnosis and the light can appear anywhere within the Garou’s line of sight, and bobs about at 10 ft/round if bidden to do so.  Lasts until Fianna chooses to dismiss it, or falls unconscious. 
#### Flame Dance  
At 6th level,  Pushing the fire in his heart into his limbs, the Fianna hurls himself unharmed
through the ranks of Gaia’s foes. A mongoose-spirit teaches this Gift.
<br>**System:** The player reflexively spends one Rage point, allowing the character to dodge one attack  regardless of what other actions he has taken during the round. Alternately, a Rage point may be spent to enhance a normal Dexterity based skill check, giving advantage to the ability.

#### Fair Fortune 
At 11th level, the Fianna is blessed with a lucky streak a mile wide.  <br>**Cost-**3 Gnosis and the player may re-roll any failed roll.  The result of the second roll must be kept.  Cant be used more than once/short rest.
#### Fog of the Moor 
At 17th level, the Fianna is transformed into a ghostly outline of himself, allowing him to pass through anything except silver as though he were incorporeal.  He may communicate and strike opponents normally.  He cannot be harmed by anything except silver, all incoming attacks pass harmlessly through him.  <br>**Cost.**  4 Gnosis/ per round.  The Fianna may also decide to phase back in as a bonus action, and save the remaining rounds for a later time.  This Gift ends at any point the Fianna decides to rest, or falls unconscious.  This does not cause immunity from spells or attacks that affect the mind.  The Fianna cannot heal or receive healing while phased.
```
```
## Fianna Stereotypes of other Tribes:
**Children of Gaia:**  *"Good folks to have at any moot, even if it takes more effort to howl ‘em into a proper battle fury when the need’s there."*<br><br>

**Get of Fenris:**  *"Berserks and murderers, addicted to the taste of blood.  There’s the remnants of a tribe we could’ve called friends somewhere in there, but it was buried millennia ago."*<br><br>

**Shadow Lords:** *"Smart and vicious and effective, but anyone who doesn’t respect his king on principle needs to be watched."*<br><br>

**Silver Fangs:**  *"We owe them our loyalty, and it’s a hard debt to pay sometimes."*
  <div class='pageNumber'>32</div>
<div class='footnote'>PART 3 | FIANNA</div>

  
  \page
  # Shadow Lords
  The strong dominate; the weak submit.   This is the core of Shadow Lord philosophy.  Intensely political and coldly pragmatic, the Shadow Lords practice a rigid internal hierarchy and promote an equally unforgiving value system for the Garou Nation.  Their very presence is divisive.  Other tribes view their manipulative tactics as a reason to distrust the Lords, or complain that anyone so ruthless is marked for eventual corruption.  Some would argue that they should be cast out of the Nation entirely--but the Shadow Lords are far too valuable.  Their methods are often dishonorable and sometimes cruel, but they get results.<br>
Life among the Lords is one part oppressive and one part inspirational. Cubs are taught to fear their elders as much as revere them. But the tribe is also a meritocracy — those who have the ambition and skill to succeed will go farther than those who rely on a misguided sense of entitlement. The lupus of the tribe usually start by mastering this instinctive dominance before they begin to hone their more humanlike capacity for deception and politics. Metis begin with the deck stacked against them — but are in a unique position to begin learning the tribe’s manipulative tricks almost as soon as they can talk.<br>
The Shadow Lords’ tribal strength is that they produce very strong, cunning champions; their elders and leaders have earned their position by constantly honing themselves. Their tribal weakness is that every Shadow Lord contends against his brethren.
Those below you covet your position; those above you don’t want you coveting theirs. Their constant struggles for dominance have dealt them more than one setback in their ongoing quest for power.<br>
This ruthless tribal philosophy has been at the tribe’s heart ever since its founding in what is now Eastern Lands. During the Impergium, they showed no mercy in culling their charges — and when the Impergium ended, they still believed it necessary that humans fear the dark. Over the years, the Shadow Lords have made all manner of alliances, only to turn on their compatriots when the opportunity and the excuse were there. Many of these alliances were even with other creatures of the night such as vampires. Of course, it’s not fashionable to be seen consorting with a Leech, even if you plan to eventually turn on it — because of course it will eventually turn on you — so the Shadow Lords aren’t seen doing so. Not if they can help it.<br>
As ambitious and callous as they are, most Shadow Lords are still loyalists to the Gaian cause. They work to undercut and dethrone weak leaders, but a strong and cunning leader earns great loyalty from the tribe of Grandfather Thunder. They play one Garou against another, testing the loyalties of both. If someone in a sept is close to turning to the Wyrm, more often than not it’s a Shadow Lord who finds out first — and then exploits the information in the most advantageous way possible. As they reasonably point out, only the weak and corrupt have anything to fear from their investigations. The fact that it’s the Shadow Lords defining “weak” and “corrupt” does little to allay concerns. A Philodox of Grandfather Thunder rarely errs on the side of compassion.<br>
In these dying times, though, the Shadow Lords see weakness all around them. The Silver Fangs are doddering and foolish at the time they’re needed most. The tribes are splintered and squabbling where they should be unified against the Wyrm. The authority of royal blood has failed; the calls for reconciliation have failed. Perhaps the only thing that will unite the Garou Nation is fear. If that’s what it takes — if the Garou need an iron claw to bring them together — the Shadow Lords will certainly take the opportunity when it presents itself.
  <br><br>
  **Appearance:** Shadow Lords with high Pure Breed often
lean toward the saturnine in all forms. In Lupus form, they are
notably thick and stocky, with the dark coats that reflect their
tribal name.
<br><br>
**Tribal Totem:** Grandfather Thunder, a powerful storm spirit
that demands a clear hierarchy. The most famous spirits
of his brood are the Stormcrows, which are inextricably linked
to the Shadow Lords. Grandfather Thunder has also dominated
other spirits that others would find difficult to control, such as
spirits of night and pain.
  <br><br>
  **Quote:** *"Of course I have a plan.  Someone needs to do the thinking around here.  Now are you interested in winning this fight, or were you looking forward to a glorious face-first charge into a wall of silver?"*<br><br>
  <img 
  src='https://imgur.com/JXfTIRB.jpg' 
  style='width:325px;mix-blend-mode:darken' />
  *Image source from:https://i.pinimg.com/236x/0f/f4/99/0ff499c74a0169f15215fb64a725ccf8--teen-wolf-dark-art.jpg*
  Onyx Path W20 Sourcebook
<div class='pageNumber'>33</div>
<div class='footnote'>PART 3 | SHADOW LORDS</div>
  
  \page
  ## Shadow Lord Tribal Features:
 The Shadow Lords appreciate both subtlety and power, and this is reflected in their spirit pacts.  The Tribe’s Gifts grant power over shadows, intimidation, control, asserting dominance over others, and the raw fury of the unleashed storm.
#### Shadow Weaving
 At 3rd level,  the Shadow Lord slightly flexing her fingers or claws, pulls and weaves shadows as she desires--lengthening or shortening them, lightening or darkening, or even twisting them into grotesque and frightening shapes.  <br>**Cost-** 1 Gnosis point, and the Shadow Lords gains advantage to any stealth and Intimidation check, also any attempt to read aura on the shadow Lord fails, and after every round an attempted roll or check used by the Shadow Lord or against him, 1 Gnosis point must be spent to keep shadow weaving active.    
#### Direct the Storm
  At 6th level, the Shadow Lord can direct the primal instincts of an opponent, friend, or foe, causing him to attack targets of the Lord’s choice. <br> **Cost-**2 Gnosis and a Wisdom save vs Shadow Lord’s spellcasting DC.  Failed Save indicates that the Shadow Lord controls the target’s frenzy and can set him on anyone she chooses for the amount of rounds of the Shadow Lord’s total Rage amount.  Target has the opportunity to resist each round.  Shadow Lord cannot use abilities that require intricate thought of the victim, or have them cast spells.
  #### Strength of the Dominator
  At 11th level, the Shadow Lord draws on a target’s anger to feed his own. <br>**Cost-**3 Gnosis points, target rolls Wisdom Save difficulty spellcaster DC. On a failed save, for every round the target deals damage, the Shadow Lord gets a point of rage back for the amount of rounds equal to Shadow Lord’s Gnosis rating.  On a successful save, the target becomes immune to the gift for the remainder of the day.
#### Shadow Pack 
 At 17th level, the Shadow Lord summons up shadowy duplicates of himself to stand by him in battle.  These shadow wolves resemble the Shadow Lord and share some of his capabilities.  <br>**Cost-** One Shadow Lord duplicate appears for each point spent within 60ft in any area the Shadow Lord has line of sight.  These duplicates have the same stats and abilities as the Garou, but can NOT use Gifts, Gnosis, or Rage.  And can only use its natural weapons of the Shadow Lord.   Each only has 1 hit point.  Duplicates fade if not killed or dismissed beforehand in 1 hour.
  ```
```
## Shadow Lord Stereotypes of other Tribes:
**Children of Gaia:**  *"Their aggression is difficult to make use of, and they’re very sensitive about it.  Still, don't underestimate the utility of a tribe that understands the necessity of cooperation."*
<br><br>
**Fianna:**  *"They’ll argue with any plan just for the love of argument.  Let the dispute run its course, let them think they’ve won, and then get them moving against the target."*<br><br>

**Get of Fenris:**  *"Handle them properly, and they’re a vital part of any battle plan.  Make a mistake in handling them...actually, let me just say don't make a mistake in handling them."*<br><br>

**Silver Fangs:**  *"There will come a point where the fall of the Silver Fangs will do more to unify the tribes than their presence does.  Wait."*
  <div class='pageNumber'>34</div>
<div class='footnote'>PART 3 | SHADOW LORDS</div>
  
  \page
  # Gift List
  
  ### Homid
  <div class='GiftList'>
##### Rank 1  

- Apecrafts' Blessing
- City Running
- Master of Fire
- Persuasion
- Smell of Man


##### Rank 2
- Jam Technology
- Mark of the Wolf
- Speech of the World
- Staredown


##### Rank 3
- Calm the Savage Beast
- Cowing the Bullet
- Disquiet
- Reshape


##### Rank 4 
- Body Shift
- Bury the Wolf
- Cocoon
- Spirit Ward


##### Rank 5 
- Assimilation
- Beyond Human
- Part the Veil

</div>
  
  ### Metis
  <div class='GiftList'>
##### Rank 1  

- Create Element
- Primal Anger
- Rat Head
- Sense Wyrm
- Shed



##### Rank 2
- Burrow
- Curse of Hatred
- Form Mastery
- Sense Silver



##### Rank 3
- Chameleon
- Eyes of the Cat
- Mental Speech
- Shell



##### Rank 4 
- Gift of the Porcupine
- Lash of Rage
- Rattler’s Bite
- Wither Limb



##### Rank 5 
- Madness
- Protean Form
- Totem Gift


</div> 
  
  
  
   ### Lupus
  <div class='GiftList'>
##### Rank 1  

- Hare’s Leap
- Heightened Senses
- Sense Prey
- Predator’s Arsenal
- Prey Mind




##### Rank 2
- Axis Mundi
- Eye of the Eagle
- Scent of Sight




##### Rank 3
- Catfeet
- Monkey Tail
- Sense the Unnatural
- Silence the Weaver
- Strength of Gaia


##### Rank 4 
- Beast Life
- Gnaw
- Scream of Gaia
- Terror of the Dire Wolf



##### Rank 5 
- Elemental Gift
- Song of the Great Beast



</div> 

  ### Ragabash
  ##### Rank 1
- Blur of the Milky Eye
- Liar’s Face
- Open Seal
- Scent of Running Water
  
  
  ##### Rank 2
- Blissful Ignorance
- Pulse of the Prey
- Spider’s Song
- Taking the Forgotten
  
  
  
##### Rank 3
- Gremlins
- Liar’s Craft
- Monkey Tail
- Pathfinder
  
  
  ##### Rank 4
- Luna’s Blessing
- Umbral Dodge
- Whelp Body
  
  
 ##### Rank 5
- Thousand Forms
  <div class='pageNumber'>35</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page

 ### Theurge
  
  <div class='GiftList'>
##### Rank 1  

- Spirit Snare
- Spirit Speech 
- Umbral Tether





##### Rank 2
- Command Spirit
- Name the Spirit
- Sight From Beyond





##### Rank 3
- Exorcism
- Pulse of the Invisible
- Umbral Camouflage
- Web Walker



##### Rank 4 
- Blurring the Mirror
- Grasp the Beyond
- Spirit Drain
- Spirit Ward




##### Rank 5 
- Feral Lobotomy
- Malleable Spirit
- Ultimate Argument of Logic



</div> 
  
### Philodox
 
  <div class='GiftList'>
##### Rank 1  

- Fangs of Judgement
- Persuasion
- Resist Pain
- Scent of the True Form



##### Rank 2
- Call to Duty
- Command the Gathering
- Strength of Purpose






##### Rank 3
- Mental Speech
- Scent of the OathBreaker
- Sense Balance
- Weak Arm




##### Rank 4 
- Roll Over
- Scent of Beyond




##### Rank 5 
- Geas
    
  </div>
  
```
```
### Galliard
 
  <div class='GiftList'>
##### Rank 1  

- Heightened Senses


##### Rank 2
- Dreamspeak
- Howls in the Night



##### Rank 3
- Song of Heroes
- Song of Rage
- Song of the Siren


##### Rank 4 
- Bridge Walker
- Gift of Dreams
- Shadows by the Firelight



##### Rank 5 
- Head Games
    
  </div>

### Ahroun
 
  <div class='GiftList'>
##### Rank 1  

- Falling Touch
- Pack Tactics


##### Rank 2
- Sense Silver
- Shield of Rage
- Spirit of the Fray
- True Fear


##### Rank 3
- Heart of Fury
- Silver Claws
- Wind Claws


##### Rank 4 
- Body Shift
- Clenched Jaw
- Full Moon’s Light
- Stoking Fury’s Furnace




##### Rank 5 
- Strength of Will
- Unstoppable Warrior

    
  </div>
  <div class='pageNumber'>36</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page



### Children of Gaia
 <div class='GiftList'>
##### Rank 1
-  Brother’s Scent
- Jam Weapon
- Resist Pain

##### Rank 2
- Grandmother’s Touch
- Luna’s Armor
- Para Bellum
- Unicorn’s Arsenal

##### Rank 3
- Calm the Savage Beast
- Dazzle
- Lover’s Touch
- Spirit Friend

##### Rank 4
- Beast Life
- Serenity
- Strike the Air
- Uncaught Since the Primal Moon

##### Rank 5
- The Living Wood



    
  </div>
  
### Fianna
  
 <div class='GiftList'>
##### Rank 1
- Hare’s Leap
- Persuasion
- Resist Toxin
- Two Tongues

##### Rank 2
- Glib Tongue
- Form Mastery
- Howl of the Banshee
- Howl of the Unseen

##### Rank 3
- Faerie Kin
- Fair Fortune
- Ley Lines
- Reshape Object
- Song of the Siren

##### Rank 4
- Balor’s Gaze
- Phantasm

##### Rank 5
- Call the Hunt
- Gift of the Spriggan 




    
  </div>

  ```
```
### Get of Fenris
  <div class='GiftList'>
##### Rank 1
- Master of Fire
- Resist Pain
- Visage of Fenris

##### Rank 2
- Halt the Coward’s Flight
- Snarl of the Predator
- Troll Skin

##### Rank 3
- Redirect Pain
- Venom Blood

##### Rank 4
- Body Shift
- Heart of the Mountain
- Scream of Gaia

##### Rank 5
- Endurance of Heimdall
- Horde of Valhalla
- Fenris Bite
- Call Great Fenris(6)





    
  </div> 
 ### Shadow Lords
  <div class='GiftList'>
##### Rank 1
- Aura of Confidence
- Fatal Flaw
- Seizing the Edge
- Whisper Catching

##### Rank 2
- Clap of Thunder
- Cold Voice of Reason
- Howls in the Night
- Luna’s Armor
- Song of the Earth Mother

##### Rank 3
- Icy Chill of Despair
- Paralyzing Stare
- Shadow Cutting
- Under the Gun


##### Rank 4
- Open Wounds

##### Rank 5
- Obedience






    
  </div>   
 

<div class='pageNumber'>37</div>
<div class='footnote'>PART 4 | GIFTS</div>









\page




### Silver Fangs
  <div class='GiftList'>
 ##### Rank 1
- Falcon’s Grasp
- Lambent Flame
- Sense Wyrm

##### Rank 2
- Hand Blade
- Luna’s Armor
- Sense Silver
- Unity of the Pack

##### Rank 3
- Burning Blade
- Silver Claws
- Talons of the Falcon
- Wrath of Gaia

##### Rank 4
- Mindblock

##### Rank 5
- Luna’s Avenger






    
  </div>     






















  












  


  






 




        
  







  







  






















  

  
  

  











  



  

    
    


 <div class='pageNumber'>38</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
## Gift Descriptions
  The Gifts are presented in alphabetical order.

#### Apecrafts’ Blessing
  *Homid, Rank 1 Gift*
  
  **Casting Time** bonus action
  
  **Range:** Self
  
  **Duration:** Special
  
  **Gnosis:** None
  
  **Rage:** N/A
  
  Though many
of Gaia’s children use tools, none have mastered them so
thoroughly as humanity. The homid focuses this mastery
into the tools she uses, causing their spirits to awaken and
lend her aid. An ancestor-spirit or spirit of a man-made
object teaches this Gift.
  
**System:** The werewolf can use a bonus action to
gain advantage on the next roll she makes to employ a tool made
by human hands. The purpose is irrelevant—this Gift is
equally efficacious for attempts to repair an engine, drive
a car or fire a gun.

#### Assimilation
  *Homid, Rank 5 Gift*
  
  **Casting Time** Instantaneous
  
  **Range:** Self
  
  **Duration:** 24 hours
  
  **Gnosis:** 1/day
  
  **Rage:** N/A
  
  A werewolf with
this Gift blends smoothly into any culture, no matter
how strange or unfamiliar he might normally find it.
He could slip among Bedouin nomads as if he were one
of them, or he could shop in a Chinese market without
anyone noticing that he doesn’t belong. The Gift doesn’t
hide racial differences, but it does allow the werewolf to
mimic the behaviors and mannerisms of a native. It also
grants the ability to speak and understand the culture’s
language, although this knowledge vanishes as the Gift
ends. It is taught by Ancestor-spirits.
  
**System:** The player rolls a history check If
successful, the character interacts with members of another
culture as if he were one of them. The difficulty depends
on how alien the culture is. Another Garou sept would be
5, while a Black Spiral hive or foreign country could be as
high as 15. The character suffers no Social penalties when
interacting with members of the culture, although he will
enjoy no special benefits either. The Gift lasts for one day per
Gnosis point spent when activating it.


#### Aura of Confidence
  *Shadow Lords, Rank 1 Gift*
  
  **Casting Time** Instantaneous
  
  **Range:** Self
  
  **Duration:** Permanent
  
  **Gnosis:** N/A
  
  **Rage:** N/A
  
 The werewolf
projects an aura of superiority, preventing attempts to
find flaws or read auras (but not to read the werewolf’s
thoughts). An ancestor-spirit teaches this Gift.
**System:** This Gift’s effects are permanent.


 <div> 
  
#### Axis Mundi   
    
   *Lupus, Rank 2 Gift*
  
  **Casting Time** Instantaneous
  
  **Range:** Self
  
  **Duration:** Permanent
  
  **Gnosis:** N/A
   
  **Rage:** N/A 
  
The lupus reaches
out with her spirit to feel the presence of Gaia, centering
herself with relation to her Mother. She always knows
what direction she is traveling or facing in, so long as she
travels within the Gaia Realm. The spirits of migratory
birds teach this Gift.
  
**System:** Advantage to any rolls regarding Navigation
   This Gift’s effects are permanent.
  
#### Balor’s Gaze
   *Fianna, Rank 4 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1 Point
   
  **Rage:** 1 point
  
One of the Fianna’s
eyes glows a livid red, and all enemies caught by his gaze
are stricken with terrible agony. A pain-spirit teaches
this Gift.
   
**System:** The player spends one Rage point and one
Gnosis. For the next 10 minutes, any foe at whom the Garou glares within 60 ft must roll
Wisdom save double over in pain, dealing 8d6 psychic damage and a disadvantage on their attack rolls until the Garou’s next turn.  If a creature dies from the Balor’s Gaze, the Garou may choose to regain one of their rage or Gnosis points spent for this ability.
</div>
  
  
#### Beast Life
  *Lupus, Rank 4 Gift*
  
  **Casting Time** Instantaneous
  
  **Range:** 60 ft
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1 Point
   
  **Rage:** N/A
  
The werewolf can
communicate with other wild animals and attract or even
command them. Domesticated animals may speak with
the Garou, but they have given themselves over to the
ways of humans and will provide no aid beyond information.
Any animal spirit can teach this Gift, although lupus
prefer to learn it from lion- or wolf-spirits.
  
**System:** The character gains the permanent ability to
communicate with all animals, regardless of the form she
wears. To attract animals, the player spends one Gnosis
point. All animals within 30 miles respond to the
summons, and will follow any requests the Garou makes.
It is considered customary to pay homage to the spirit of
any animal ordered to sacrifice itself with this Gift; to do
otherwise risks angering the spirit world.

  
    
    
 <div class='pageNumber'>39</div>
<div class='footnote'>PART 4 | GIFTS</div>
    
  
  \page

#### Beyond Human
  *Homid, Rank 5 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 1 hour
  
  **Gnosis:** up to half (round up)
   
  **Rage:** up to half (round up)
  
This potent Gift immunizes
a human from the Delirium effect. However,
the Garou can replace any crucial piece of information the target may have learned within this time, with something else that the Garou creates for her.  As long as it isn't completely out of the ordinary.  (Cant say aliens abducted you for the last 24 hours)
 An ancestor-spirit teaches this Gift.
  
**System:** The player spends a Gnosis point for each day he chooses this Gift to remain in effect
Must be within 120 ft to activate.  If the Garou chooses to substitute any piece of known information the target may have acquired, it can be replaced with another interpretation of the story, and completely forget about that event.  Target Rolls Wisdom Save to resist.  If saved, the target also realizes the attempt the Garou tried to make, and may become hostile.

#### Blissful Ignorance
  *Ragabash, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** n/a
   
  **Rage:** n/a
  
The Garou
can become completely invisible to all senses, spirits or
monitoring devices by remaining still. A chameleon-spirit
teaches this Gift.
  
**System:** The player rolls gets a +10 to any Dexterity checks attempting to blend in or hide.
Success provides perfect concealment. Last for 10 minutes.

#### Blur of the Milky Eye
  *Ragabash, Rank 1 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 1 hour
  
  **Gnosis:** n/a
   
  **Rage:** n/a
  
The werewolf’s
form becomes a shimmering, indistinct blur, as
though seen through heavy cataracts — even in the midday
sun. The Ragabash is not truly invisible, however, and if
spotted, this Gift’s protection fails until the observer is
distracted. A chameleon- or ermine-spirit teaches this Gift.
  
**System:**Perception rolls made to detect him are made with disadvantage for 1 hour.
```
```


  
  
#### Blurring the Mirror
  *Theurge, Rank 4 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** 1 hour
  
  **Gnosis:** up to half gnosis(max 5)
   
  **Rage:** n/a
  
This Gift
allows the Theurge to cloud the minds of other beings,
making it impossible for them to find the Umbra or step
sideways into it. Once used as a form of punishment for
arrogant pups, this Gift is more often deployed as a weapon
against Black Spiral Dancers in the days of the coming
Apocalypse. A Weaver-spirit teaches this Gift.
  
**System:** The player spends one Gnosis point for every
individual she wishes to affect. The targets make Intelligence saves.  On a failure any abilities to teleport, planar travel, open dimension doors, side step, wont work for the targets take a long rest.  Also, any magical items that use similar abilities stop working until the owner takes a long rest, or if the item has no owner it is 1 day.Up to
five individuals can be affected at once. While normally
used against other Garou, this Gift is effective against any
being capable of entering the Umbra sideways, including some mages.

#### Body Shift
  *Homid Rank 4 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** Until dispelled
  
  **Gnosis:** 2
   
  **Rage:** n/a
  
Garou raised in the
shifting maze of human society are well-prepared for the
endless adaptations Gaia demands of her protectors. An
ancestor-spirit teaches this Gift.
System:   Garou can use her shapeshifting ability and alter her physical attributes.  Until the Garou falls unconscious or willingly disables this gift, the Garou can switch her STR, DEX, and/or Con ability scores around as she sees fit. 
  
  Only one score can be exchanged with the other.  Any and all saves, skills, and other abilities that are physical are also adjusted temporarily.  
  
 <div class='pageNumber'>40</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Bridge Walker
  *Galliard, Rank 4 Gift*
  
  **Casting Time** 10 minutes
  
  **Range:** Special
  
  **Duration:** one passage or next full moon
  
  **Gnosis:** 1 - 3
   
  **Rage:** n/a
  
The Galliard may
create minor moon bridges through which she alone can
travel. Such travel takes one percent of the time the journey
would take normally, allowing the werewolf to disappear
from in front of a foe and reappear behind it instantly.
These moon bridges are not protected by Lunes, and may
attract the interest of spirits. A Lune teaches this Gift.
  
**System:** The player spends one Gnosis point to create
the bridge. The moon bridge lasts for only one passage,
unless the player spends an additional three Gnosis, in
which case it lasts until the next full moon. The maximum
distance that can be traversed by the bridge is the Garou’s
Gnosis in miles (1.6 km per Gnosis dot).

 
#### Brother’s Scent
  *Children of Gaia, Rank 1 Gift*
  
  **Casting Time** Instantaneous
  
  **Range:** Self
  
  **Duration:** Until Dismissed
  
  **Gnosis:** 1
   
  **Rage:** n/a
  
The Galliard may
create minor moon bridges through which she alone can
travel. Such travel takes one percent of the time the journey
would take normally, allowing the werewolf to disappear
from in front of a foe and reappear behind it instantly.
These moon bridges are not protected by Lunes, and may
attract the interest of spirits. A Lune teaches this Gift.
  
**System:** The player spends one Gnosis point to create
the bridge. The moon bridge lasts for only one passage,
unless the player spends an additional three Gnosis, in
which case it lasts until the next full moon. The maximum
distance that can be traversed by the bridge is the Garou’s
Gnosis in miles (1.6 km per Gnosis dot).
  
#### Burning Blade
  *Silver Fangs, Rank 3 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:** n/a
  
This Gift causes
a Garou’s weapon, whether it’s a sword, klaive or axe, to
burn with a deadly fire that burns her enemy even as it
bites into their flesh. A firebird spirit teaches this Gift.
  
**System:** The werewolf spends one Gnosis to activate the Gift.
The weapon now adds 2d8 fire damage. Flammable objects will catch fire if struck by the
blade. The weapon remains ignited for 10 minutes.
  
#### Burrow

  *Metis, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 8 Hours
  
  **Gnosis:** n/a
   
  **Rage:** n/a
  
This Gift grants the ability
to burrow through the earth, creating a tunnel roughly the
size of the digger’s body, which others can follow through.
The werewolf must be in a form possessing claws to use
this Gift. Mole-spirits teach this Gift.
  
**System:** The player rolls Athletics check against
a difficulty depending on the substance to be excavated
(DC 5 for loose mud, DC15 for solid rock). Some metals (such as
steel and titanium alloys) and other reinforced structures
won’t yield to the werewolf no matter how hard she digs.
The character can burrow 15 ft  per turn after the initial roll, the character does not need
to roll again to continue at the same speed.
 



  
#### Bury the Wolf
  *Homid, Rank 4 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** Variable
  
  **Gnosis:** 1-5
   
  **Rage:** n/a
  
The war against the
Wyrm isn’t always a matter of slashing claws and righteous
fury — sometimes duplicity is required. A werewolf can
temporarily “restrain” her inner wolf and appear to be a
normal human. An ancestor-spirit teaches this Gift.
  
**System:** The player spends one Gnosis point
causes the character to appear human to all supernatural
scrutiny. The Gift also nullifies the Curse and makes
spending Rage impossible, and locks her in homid form
so long as its effects persist. And is not vulnerable to silver.  Any items the are considered magical are also hidden under this Gift, as they appear normal.  Any attempt to identify an item, or something similiar must roll a WIS save, to reveal the item, or break the effects of the Gift. The duration depends on the amount of Gnosis is spent, or if the caster chooses to end it earlier.
  
Gnosis:
* One 1 Hour
* Two 12 hours
* Three One day
* Four One week
* Five One lunar cycle

 <div class='pageNumber'>41</div>
<div class='footnote'>PART 4 | GIFTS</div>
 
  \page
#### Call Great Fenris 6
  *Get of Fenris, Rank 5 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 90 ft
  
  **Duration:** 3 rounds
  
  **Gnosis:** 1
   
  **Rage:** n/a
  
As the ultimate
expression of the pact between tribe and totem, the greatest
Get heroes may summon the war-avatar of their tribal
totem to aid them in their hour of need. The avatar joins
in combat, slaying all that are not Get of Fenris or under
their protection. However, Great Fenris demands a sacrifice
for his intervention — usually the left hand of the
summoner. It’s said that if the war-avatar is called for no
good reason, it will devour the summoner entirely before
departing. This Gift is taught by Great Fenris himself.
  
**System:** The player spends one Gnosis point . Success summons the
war-avatar of Great Fenris, who will fight at the Fenrir’s
Few spirits — short of Incarnae themselves —
are as frightening and dangerous as the war-avatar of
Great Fenris. The avatar of Fenris Wolf appears as an
enormous wolf, 20 feet tall at the shoulder. His eyes
burn with rage and his jaws drip with the blood of
countless enemies. His coat is a deep gray that seems
to shimmer from black to red and even to white as
the light shifts across it. The war-avatar of Fenris
is not as powerful as the Incarna himself would be,
but it still defies the usual limitations of spirits. 
The Fenrir Spirit rolls his own initiative, as well as his own turns.  He is friendly to his summoner and his allies.  And if not commanded to do anything, will still defend itself from hostile creatures.  Lasts for 3 rounds, and can be summoned anywhere within 90 ft of the summoner. ***(See Fenrir Stat Block)***
  ___
___
> ## Fenrir
>*Gargantuan monstrosity (titan), unaligned*
> ___
> - **Armor Class** 18 (natural armor)
> - **Hit Points** 362(25d20 + 100)
> - **Speed** 50 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|25 (+7)|13 (+1)|19 (+4)|2 (-4)|12 (+1)|11 (+0)|
>___
> - **Skills**  Intimidation +14, Perception +15, Stealth +9  
> - **Damage Immunities** necrotic; bludgeioning, piercing, and slashing from non magical weapons
> - **Condition Immunities** Charmed, Frightened
> - **Senses** darkvision 120ft, passive Perception 25
> - **Languages** -
> - **Challenge** 24 (62,000 XP)
> ___
> ***Battle Frenzy.***  When Fenrir is at or below one-quarter his maximum hit points, he can make one additional attack on his turn. When it does so, he gains a +7 bonus to his damage rolls, but also gains a -7 penalty to his attack rolls..
>
> ***Energetic Attacks.*** Fenrir deals an additional 7 (2d6) necrotic damage on each of his weapon attacks (included in the attack).
>
> ***Keen Hearing and Smell.*** Fenrir has advantage on Wisdom (Perception) checks that rely on hearing or smell.
>
> ***Enormous Nose.*** This creature gains advantage on any check involving putting things in its nose.
>  
> ***Legendary Resistance (3/day)*** If Fenrir fails a saving throw, he can choose to succeed instead.
>  
> ***Pack Tactics.*** Fenrir has advantage on an attack roll against a creature if at least one of Fenrir's allies is within 5 feet of the creature and that ally isn't incapacitated.
>
> ***Primal Strikes.*** Fenrir ignores other creatures' resistance and immunity to non magical bludgeoning, piercing, and slashing damage.
>
> ***Regeneration.*** Fenrir regains 20 hit points at the start of his turn if he has at least 1 hit point remaining.
>
> ***Siege Monster.*** Fenrir deals double damage to objects and structures.  
> ### Actions
> ***Multiattack.*** *Fenrir can use his Frightful Presence. He then makes four weapon attacks.*
>
> ***Bite.*** *Melee Weapon Attack: +14 to hit, reach 5 ft., one target. Hit: 21 (4d6 + 7) piercing damage plus 7 (2d6) necrotic damage. If the target is a creature, it must succeed on a DC 22 Strength saving throw or be knocked prone.*
>
> ***Frightful Presence.*** *Each creature of Fenrir's choice that is within 120 feet of him and aware of him must succeed on a DC 15 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Fenrir's Frightful Presence for the next 24 hours.* 
>
> ***Abdominal Drop.*** *Melee Weapon Attack:* +4 to hit, reach 5ft., one target. *Hit* 5 (1d6 + 2) 
>
> ***Heel Jawbreaker.*** *Melee Weapon Attack:* +4 to hit, reach 5ft., one target. *Hit* 5 (1d6 + 2) 
>
> ***Tilt-a-whirl Eye Takedown.*** *Melee Weapon Attack:* +4 to hit, reach 5ft., one target. *Hit* 5 (1d6 + 2) 
> ### Legendary Actions
>   Fenrir can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of        another creature's turn. Fenrir regains spent legendary actions at the start of his turn.
>
>  ***Detect.*** Fenrir makes a Wisdom (Perception) check.
>  
> ***Move.*** Fenrir moves up to half his speed.
>  
> ***Attack.*** Fenrir makes one weapon attack. 
  
  <div class='pageNumber'>42</div>
<div class='footnote'>PART 4 | GIFTS</div> 
  \page
  
  
#### Call the Hunt
   *Fianna, Rank 5 Gift*
  
  **Casting Time** Concentration, 1 hour
  
  **Range:** 90 ft
  
  **Duration:** Until Request is fullfilled
  
  **Gnosis:** 1 - max allowed for level
   
  **Rage:** max allowed for level
  
The werewolf calls
forth the Huntsman of Celtic mythology to harry and
slay a great evil. The Huntsman himself teaches this Gift.
  
**System:** The Garou must chant and concentrate for one
full hour. The player then spends one Gnosis point. The Fey Huntsman appears
with a leashed terror, plus one leashed terror for each extra Rage
or Gnosis point the player wishes to expend. If the Huntsman
judges that the evil he has been summoned to hunt is
insufficiently mighty or wicked to warrant his talents, or if
the Garou has already summoned the Huntsman within the
last month, then the Garou becomes the target of the hunt. 
  
___
___
> ## Fey Huntsman
>*Large Fey, Chaotic Neutral*
> ___
> - **Armor Class** 16
> - **Hit Points** 204(24d10 + 72)
> - **Speed** 40 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|18 (+4)|12 (+1)|16 (+3)|10 (+0)|14 (+2)|14 (+2)|
>___
> - **Damage Vulnerabilities** bludgeoning, piercing, or slashing damage from weapons made of cold iron  
> - **Skills**  Animal Handling +6, Perception +6, Survival +6
> - **Senses** blindsight 10 ft., darkvision 120 ft., passive Perception 12
> - **Languages** Common, Giant, Sylvan
> - **Challenge** 9 (5,000 XP)
> ___
>   *When summoned, choose one of the following traits:*
**Masters of the Hunt.** Fey huntsmen often carry the leashes of leashed terrors, their hunting-beasts. The leash can extend up to 120 feet or reduce to 5 feet without apparent slack. As a reaction or bonus action, the fey huntsman can pull a leashed terror whose leash it holds up to 30 feet closer to it in a straight line. Other characters can spend a Use an Object action to pull on a leash with a free hand. Roll a Strength (Athletics) check against DC 16; on a success the leashed terror is pulled 10 feet in a straight line. The fey huntsman can release any or all leashes as a free action.
>  
 **Trophy of Great Beast**. Fey huntsmen have collected trophies from their greatest kills, often the head, horns, or heart, to strike fear into their prey. If any enemy creature is within 30 feet of the fey huntsman when it rolls initiative, the trophy of the great beast casts fear; fey huntsmen and leashed terrors are not affected. The Wisdom saving throw DC is 16.
>  
**Horn of the Wild Hunt.** Fey huntsmen carry hunting horns that are enchanted to drive leashed terrors into a frenzy. As a bonus action, the fey huntsman may sound a horn of the wild hunt. All leashed terrors within 60 feet may spend a reaction to make an attack or use the Dash action. Once used, a horn of the wild hunt may not be used again until the next dusk.  
> ***Onion Stench.*** Any creatures within 5 feet of this thing develops an irrational craving for onion rings.
>
> ### Actions
>**Multiattack.** The fey huntsman makes two spear attacks, two javelin attacks, or one spear attack and one javelin attack.
>  
**Spear.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 15 (2d10+4) piercing damage, and 9 (2d8) poison damage. Creatures suffering the frightened condition from a fey huntsman or a leashed terror take an additional 9 (2d8) psychic damage.
>  
**Javelin.** Ranged Weapon Attack: +7 to hit, range 60/240 ft., one target. Hit: 13 (2d8+4) piercing damage, and the target must succeed a DC 16 Constitution saving throw or take an additional 9 (2d8) poison damage and its speed is reduced by 15 feet until the beginning of the fey huntsman’s next turn.
A trophy of the great beast or horn of the wild hunt is almost always ruined in the course of a battle, or sundered upon the death of its bearer. One who proved true courage, enough to stir the heart of even a merciless and cruel fey huntsman, might be rewarded with such an item from the huntsman’s own hand. They are wondrous items that require attunement. Please note that the trophy of the great beast is not balanced for PC use, and you will want to consider adjusting its effect, while the horn of the wild hunt is useless to most PCs and should have its effect changed to something reasonable.

 <div class='pageNumber'>43</div>
<div class='footnote'>PART 4 | GIFTS</div>


\page
  
  ### Leashed Terrors
  The leashed terrors that serve fey huntsmen as trackers, or that guard the palaces of Unseelie nobles, were once mortals – human, dwarven, or any other kind of humanoid. The glamour of the Unseelie causes them to take the shape of their own darkest terrors. (Those whose darkest terrors are ill-suited to hunting or war are given… other work.)

This fey magic is bound to them in their collars, clasped about their necks. This clasp is vulnerable to determined effort, but the leashed terrors are sure to punish those who fail in the attempt.

Many leashed terrors look vaguely canine or lupine, while others take the shapes of any kind of great predator, or even a nightmarish mix of features that have never existed on a single creature in nature.

Always Hungry. Fey huntsmen feed their leashed terrors only enough that they still feel the pangs of their hunger, for they want them to be as aggressive as possible. The leash and collar make sure that the terrors come quickly to heel.

The Mortal Within. It is still possible to free the leashed terrors from the magic that holds them. Many of them crumble to dust the moment they are released, as the weight of too many centuries destroys them. The rest will surely struggle with the memories of their time as a beast of the Wild Hunt.
  
  ___
> ## Leashed Terror
>*Tiny beast, neutral annoying*
> ___
> - **Armor Class** 14 (natural armor)
> - **Hit Points** 117(18d8 + 36)
> - **Speed** 40 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|16 (+3)|12 (+1)|14 (+2)|6 (-2)|12 (+1)|6 (-2)|
>___
> - **Condition Immunities** frightened
> - **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 11
> - **Languages** understands Common and Sylvan but cannot speak
> - **Challenge** 4 (1,100 XP)
> ___
>**Transformed Mortal.** When a leashed terror’s current hit points are less than or equal to half of its maximum hit points, the clasp of its collar becomes accessible. A successful Dexterity (thieves’ tools) check against DC 14 opens the clasp, transforming the leashed terror back to its original form. On a failed check, the leashed terror can spend its reaction to make an attack on the creature that attempted to unlock its clasp.
>  
**Keen Smell.** The leashed terror has advantage on Wisdom (Perception) checks that rely on smell.
>
>**Pounce.** If the leashed terror moves at least 20 feet straight toward a creature and then hits it with a claw attack on the same turn, the target must succeed a DC 14 Strength saving throw or be knocked prone. If the target is prone, the leashed terror can make one bite attack against it as a bonus action
> ### Actions
> ***Bite.*** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 16 (3d8+3) piercing damage.
>  
***Claw.*** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 13 (3d6+3) slashing damage.
>  
***Dreadful Baying.*** All creatures other than leashed terrors or fey huntsmen within 60 feet of the leashed terror must succeed on a DC 14 Wisdom saving throw or become frightened for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect  

 <div class='pageNumber'>44</div>
<div class='footnote'>PART 4 | GIFTS</div>

\page
  
 
#### Call to Duty
   *Philodox, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 90 ft
  
  **Duration:** Until dismissed
  
  **Gnosis:** 2
   
  **Rage:** n/a
  
Names hold great
power in the spirit world, and the Philodox may exploit
this to summon and command any Fey she knows by
name. Only one command may be given, and the spirit
departs immediately after fulfilling it. Alternatively, all
spirits in the area may be called in times of great need.
An Incarna avatar teaches this Gift.
  
**System:** The Garou must know the name of the
spirit she wishes to summon. The player rolls Charisma
(difficulty equal to the Fey’s CR - Garou’s Gnosis Rating).
The second mode of this Gift simply requires the player
to spend two Gnosis points to summon all Fey
within a one-mile radius. The results of the roll determine a generalization of how powerful the Fey who have answered the call.  If the character has
abused this Gift in the past (in the Storyteller’s estimation),
the spirits might refuse the call — such a general
summons is rooted more in appeal to duty than compulsion.
The mightiest of Fey are generally able to ignore this Gift if they choose.
 
#### Calm the Savage Beast
   *Homid, Rank 3 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 30 ft
  
  **Duration:** n/a
  
  **Gnosis:** 1-2
   
  **Rage:** n/a
  
Even the
most callous of homids can sympathize with the Rage that
moves their fellow Garou in the final days. This Gift allows
the werewolf to lend a frenzying Garou the will to escape
her Rage’s hold over her. It can also remove a frightened status effect.It is taught by an ancestor-spirit.
  
**System:**  The player spends a Gnosis point, soothing a frenzying Garou within
30 feet (9 m), canceling the frenzy. By spending an extra point, this Gift may affect non-Garou in a state of frenzy, such as other shapeshifters or vampires.  The extra Gnosis point also removes the frightened status condition.
  

#### Catfeet
  *Homid, Rank 3 Gift*
  
  **Casting Time** n/a
  
  **Range:** Self
  
  **Duration:** Permanent
  
  **Gnosis:** n/a
   
  **Rage:** n/a
  
 The werewolf gains the
agility of a cat, making him immune to falls under 100
feet (~30 m). He also has perfect balance even on the
most slippery surfaces, and gets a +2 to all combat
actions involving body slams and grappling 
 Cat-spirits teach this gift.
  
**System:** This ability becomes innate to those who
learn the Gift.
```
```

  
  
#### Chameleon
  *Metis, Rank 3 Gift*
  
  **Casting Time** bonus action
  
  **Range:** Self
  
  **Duration:** Until dismissed
  
  **Gnosis:** n/a
   
  **Rage:** n/a
  
Like the Gift’s reptilian
namesake, the Garou can blend with her natural
surroundings. Unlike the lizard, the werewolf shifts fluidly
with changing backgrounds, thus allowing the Garou to
move about and even attack. A chameleon- or octopus spirit
teaches this Gift.
  
**System:** As a bonus action,the player spends one Gnosis point to activate
the Gift. The Garou can choose the hide action as a bonus action each round while active. Anyone trying to see the werewolf, even
in open ground, must make a Perception roll vs Garou’s stealth check to detect her. Once the
Garou attacks, he is no longer hidden, but can take his bonus action to hide again. The Gift affects only sight; it does not mask the Garou’s sound or scent.

#### City Running
  *Homid, Rank 1 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** n/a
   
  **Rage:** 1
  
Humans are creatures
of the city, raising their steel and glass nests high
into the sky. This Gift allows a homid to easily scale the
concrete canyons and navigate the tangled back alleys
and rooftops of the urban landscape. Some lupus derisively
refer to this Gift as “Climb Like an Ape.” It is taught by
an ancestor-spirit or an urban city-spirit.
  
**System:**The player spends a point of Rage. For 10 minutes, the character may move unimpeded through rough terrain at her full movement speed and gains advantage on all STR/DEX rolls to navigate through cities. (running down cluttered alleys, climbing the side of buildings, leaping from rooftop to rooftop) 
  
#### Clap of Thunder
  *Shadow Lord, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 20 ft radius
  
  **Duration:** Until Dismissed
  
  **Gnosis:** 1
   
  **Rage:** n/a
  
The Shadow Lord
slams her hands together, creating a mighty thunderclap
that stuns those who hear it. A Stormcrow teaches this Gift.
  
**System:** The player spends one Gnosis point. All
characters within 20 feet (6 m) must succeed in a Wisdom Save, half the DC for packmates) or be
stunned and unable to act for one turn. The Garou must
be in Homid, or Crinos form to use this Gift.
 
   <div class='pageNumber'>45</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
  
#### Clenched Jaw
  *Ahroun, Rank 4 Gift*
  
  **Casting Time** bonus action
  
  **Range:** Self
  
  **Duration:** Until Dismissed
  
  **Gnosis:** n/a
   
  **Rage:**  1
  
The werewolf bites
down with such power that her grip won’t loosen until she
chooses to let it; even in death, her jaws remain locked.
A wolf- or hyena-spirit teaches this Gift.
  
**System:** After making a successful bite attack, the
player may spend a Rage point to invoke this Gift. For
each successive turn she chooses to maintain her grip,
she makes a bite attack roll with advantage.  Any damage inflicted with her bite while she is locked down on her target, she adds half her wisdom score(not modifier) in addition to her damage to bite(round up). While foes can make a resisted Strength roll to break the grip (1d8 + Garous Str mod of damage in the process of trying
to tear free), the Garou may add half her Wisdom score(not modifier)
to her damage as well(round up).

#### Cocoon
  *Homid, Rank 4 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 1 day
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The werewolf wraps himself
in a thick, opaque, chitinous sarcophagus, immobilizing
himself but also becoming nearly impervious to harm.
The cocoon provides immunity to fire, starvation, gas,
high pressure, cold, and similar environmental hazards.
An insect- or Weaver-spirit teaches this Gift.
  
**System:** The Garou spends one Gnosis point. While
the werewolf remains in the cocoon, any attack that strikes
him must do damage at least equal to half his HP per attack, otherwise, 
the cocoon keeps him safe from any lesser amount of
Damage and regenerates after each strike. but is destroyed if it’s pierced. The cocoon lasts
for one day, but its duration may be extended by spending
more Gnosis to renew it. The Garou may emerge from it
at any time he chooses.

#### Cold Voice of Reason
  *Shadow Lords, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** Until Dismissed
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
A cunning
Shadow Lord can talk his way out of just about anything.
If attacked, the werewolf may invent a clever remark that
will detain his attacker for at least one round. A crowspirit
teaches this Gift.
  
**System:** The player spends a Gnosis point and rolls
Deception DC targets intelligence score. The attacker
is detained one round as long as he, in
turn, is not attacked (being attacked immediately breaks
the Shadow Lord’s spell). The attacker is free to take any
other actions he wishes (including attacking individuals
other than the Shadow Lord).  If the Shadow Lord succeeds by +5 or more on the roll, the target is detained for one round, and cannot move or take any actions against the Shadow Lord or his allies.

  
  
#### Command Spirit
  *Theurge, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 120 ft
  
  **Duration:** Until Dismissed
  
  **Gnosis:** 1 per creature
   
  **Rage:**  n/a
  
The Theurge can
give commands to spirits she meets and expect obedience.
The Gift doesn’t grant the ability to summon spirits — only
to compel them to obey. As always when dealing with spirits,
clear wording is essential, as some clever spirits may attempt
to twist the spirit of issued commands while obeying them
to the letter. Any Incarna avatar can teach this Gift.
  
**System:** You speak a one-word command to a creature you can see within range. The target must succeed on a Wisdom saving throw or follow the command on its next turn. The Gift has no effect if it doesn’t understand your language, or if your command is directly harmful to it. Some typical commands and their effects follow. You might issue a command other than one described here. If you do so, the GM determines how the target behaves. If the target can’t follow your command, the spell ends. 
  
***Approach.*** The target moves toward you by the shortest and most direct route, ending its turn if it moves within 5 feet of you. 
  
***Drop.*** The target drops whatever it is holding and then ends its turn. Flee. The target spends its turn moving away from you by the fastest available means. 
  
***Grovel.*** The target falls prone and then ends its turn. 
  
***Halt.*** The target doesn’t move and takes no actions. A flying creature stays aloft, provided that it is able to do so. If it must move to stay aloft, it flies the minimum distance needed to remain in the air. 1 gnosis spent per creature the Theurge tries to command.
 
 <div class='pageNumber'>46</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Command the Gathering
  *Philodox, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 50 ft radius
  
  **Duration:** Until Dismissed
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
The
Philodox draws all eyes to herself with a great exclamation,
a clap of her hands, the striking of klaive to shield, or
some other such gesture. Until she has had her say, none
may depart or interrupt her. A lion-spirit teaches this Gift.
  
**System:** The player spends one Gnosis point
and rolls Persuasion + Proficiency(you get the bonus if you don't have it naturally)(difficulty equals the highest Charisma score among those whose attention she seeks
to gain). If the roll succeeds, all in attendance fall quiet
and listen. Any individual who wishes to interrupt the
Philodox or walk out before she has finished speaking
must roll a Wisdom save DC equal to what the Garou had to roll against.  
#### Cowing the Bullet
   *Homid, Rank 3 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** Until short or long rest
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
The spirits
of tools recognize man as their master; as a result, they
become reluctant to harm the homid. A Weaver-spirit
teaches this Gift.
  
**System:** The player spends a Gnosis point.Until the next short or long rest,
 the Garou gains +2 AC
against all crafted weapons not made of silver.

#### Create Element
   *Metis, Rank 1 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** Until element is used up
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
The metis may
create a small amount of one of the four Western classical
elements — fire, air, earth, or water. She could make
a rock to throw, fill a bathtub with no faucet, light fires
without matches, or provide air in an airtight room. She
cannot create specialized forms of any element. Precious
metals (especially silver), lethal gases, and acid are beyond
her reach. Elementals teach this Gift.
  
**System:** The player spends one Gnosis point and rolls a d10.  The result is roughly the amount of cubic feet of the desired element,(a 10 being 10 cubic ft, or 100 lbs of an element, whichever would come first.) anywhere she can see within 60 feet (18 m). The element remains in
existence until used up (breathed, in the case of air, or
burned up, in the case of fire without any fuel to keep it
going). The flames created by this Gift inflict 1d6
level of damage per success, to a maximum of 3d6.

#### Curse of Hatred
  *Metis, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
The metis takes
hold of the hate in her soul and layers it into her words,
scourging the spirits of those she addresses. A spirit of
hate teaches this Gift.
  
**System:** The player spends one Gnosis point and
rolls to attack using her primary ability modifier + profieciency bonus vs the targets AC.
 If she succeeds, her opponent recieves a disadvantage to any Wisdom check, ability, and saving throw in addition to 2 Rage points to any Garou or creature that uses Rage.
 This Gift may only be used successfully once on an opponent only once per short rest, target is immune if failed to hit initially.

#### Dazzle
  *Children of Gaia, Rank 3 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 120 ft
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
The Garou can flood a
target’s mind with the glory and love of Gaia, rendering
him harmless for a short while. A unicorn-spirit teaches
this Gift.
  
**System:** A target within 120ft makes a wisdom save.  If failed the target becomes charmed. As long as the target isn’t attacked,he stands mutely in awe until he can succeed his wisdom save. This Gift can be attempted against a given target
only once per short rest.
  
#### Disquiet
  *Homid, Rank 3 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 120 ft
  
  **Duration:** Until dismissed
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
Pulling the mercurial
tide of the target’s emotions to their lowest ebb, this Gift
makes its target feel inexplicably depressed and withdrawn.
The subject finds his emotions muted and concentration
difficult. An ancestor-spirit teaches this Gift.
  
**System:**  The victim must make a WIS save. If it fails, that opponent will be unable to recover Rage for 10 minutes while all durations for negative effects double and positive effects are halved. Moreover, the target becomes listless and generally less inclined to stir himself to pursue any action of dubious necessity, such as investigating strange noises. 

 <div class='pageNumber'>47</div>
<div class='footnote'>PART 4 | GIFTS</div>  
  \page
#### Dreamspeak
  *Galliard, Rank 2 Gift*
  
  **Casting Time** 10 minutes
  
  **Range:** Unlimited(must have at least seen the target at some point)
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1 (if target awakens)
   
  **Rage:**  n/a
  
The Galliard can
walk among another’s dreams and thereby affect their
course. The werewolf doesn’t have to be anywhere near
the target, but she must know or have seen the dreamer.
A Chimerling teaches this Gift.
  
**System:** The target makes a wisdom save). If the dreamer awakens while the Galliard is still withinthe dream, the werewolf is thrown out of the dream world
and loses a Gnosis point.
#### Elemental Gift
  *Lupus, Rank 5 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft(can be moved 20 ft increments after summoned)
  
  **Duration:** 1 minute
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
Gaia herself steps in
to lend a hand, offering part of herself to the character. The
werewolf gains the power to command his surroundings,
directing the elemental forces of the world. Elementals
teach this Gift.
  
**System:** The player spends one Gnosis. The Garou calls
an elemental, who then grants her the ability to control a
large volume of air, earth, fire, or water — approximately 1d10 x 20’ by 20’. The walls can deal 1d8 for every 20 x 20 area it is in size. (max 10d8) The effect lasts for
One minute and can be moved around on the Garou’s turn up to 20 ft a round), or until the elemental leaves or is destroyed.
Elementals summoned by this Gift are roughly as powerful
as a Efreeti for example, or a similar elemental with a CR above 10.

#### Endurance of Heimdall
   *Get of Fenris, Rank 5 Gift*
  
  **Casting Time** bonus action
  
  **Range:** Self
  
  **Duration:** 1 minute
  
  **Gnosis:** 2 
   
  **Rage:**  n/a
  
The Fenrir’s
body is suffused with hardiness beyond that of lesser
beings. A boar-spirit teaches this Gift.
  
**System:** The player spends two Gnosis points and
The next creature it kills within the next 8 hours it gains that creature’s HP as temporary HP.  This effect lasts until the Garou’s next long rest.

#### Exorcism
  *Theurge, Rank 3 Gift*
  
  **Casting Time** Concentration, 3 turns
  
  **Range:** 30 ft
  
  **Duration:** Until Dismissed
  
  **Gnosis:** n/a 
   
  **Rage:**  n/a
  
This is the Gift of ejecting
spirits from places, objects, or even people, whether
they are bound or in voluntary possession. Any Incarna
avatar can teach this Gift.
  
**System:** The werewolf must concentrate for three
uninterrupted turns. If the spirit does not wish to leave, the
Target  must roll a wisdom save. If the spirit was bound to its
Lodging, it removes the curse from the object.  If there is no spirit that occupies the object, place, or person, the curse is lifted. Any extremely potent curse on a magical item, could be dangerous and even harm the Garou performing the exorcism.  20% of  the Garou’s health is drained every round for 5 rounds as the Bane tears free of its fleshy or magical home. This ensures the host’s swift demise unless a powerful healer manages
to preserve his life during the exorcism.

#### Eye of the Eagle
  *Lupus, Rank 2 Gift*
  
  **Casting Time** 10 minutes
  
  **Range:** Self
  
  **Duration:** 8 hours
  
  **Gnosis:** n/a 
   
  **Rage:**  n/a
  
This Gift allows
the werewolf to see over impossibly long distances,
though not through obstacles — good vantage points are
invaluable, and this Gift is in much demand among caern
guardians. It is taught by an eagle-spirit.
  
**System:** The normal distance that a normal eye can see in a clear day is 2 miles.  The Lupus can double it  Any visibility range is also doubled, including darkvision and other similar abilities. A lupus would get the first opportunity in perception checks involving vision, before the rest of her party due to her long range vision.  If failed, it still wouldn't take away the other party members chances of noticing something once they get in range. 
#### Eyes of the Cat
  *Metis, Rank 3 Gift*
  
  **Casting Time** Instantaneous
  
  **Range:** Self
  
  **Duration:** 1 hour
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
The werewolf
may see clearly in complete darkness. His eyes glow a
lambent green while this power is in effect. A cat-spirit
teaches this Gift.
  
**System:** Spend one Gnosis and the character suffers no penalties from
Darkness or even magical darkness. This power may be used at will; it requires no
roll or expenditure.
 

 <div class='pageNumber'>48</div>
<div class='footnote'>PART 4 | GIFTS</div>  

  \page
#### Faerie Kin
  *Fianna, Rank 3 Gift*
  
  **Casting Time** Concentration, 1 action
  
  **Range:** 60 Ft
  
  **Duration:** 1 minute
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
The Fianna can call
upon ancient pacts between her people and the fae. By
emitting a special howl, the werewolf can call whatever
fae are in the area to help. They will obey the Fianna, but
not without question. A dream-spirit teaches this Gift.
  
**System:** You summon a fey creature of challenge rating 8 or lower, or a fey spirit that takes the form of a beast of challenge rating 8 or lower. It appears in an unoccupied space that you can see within range. The fey creature disappears when it drops to 0 hit points or when the spell ends.
The fey creature is friendly to you and your companions for the duration. Roll initiative for the creature, which has its own turns. It obeys any verbal commands that you issue to it (no action required by you), as long as they don't violate its alignment. If you don't issue any commands to the fey creature, it defends itself from hostile creatures but otherwise takes no actions.
If your concentration is broken, the fey creature doesn't disappear. Instead, you lose control of the fey creature, it becomes hostile toward you and your companions, and it might attack. An uncontrolled fey creature can't be dismissed by you, and it disappears 1 hour after you summoned it.
The GM has the fey creature's statistics. 
#### Fair Fortune
  *Fianna, Rank 3 Gift*
  
  **Casting Time** Instantaneous
  
  **Range:** Self
  
  **Duration:** Once per short rest
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
The Fianna is
blessed with a lucky streak a mile wide. A Chimerling
teaches this Gift.
  
**System:** The player may re-roll any failed or botched
roll by spending a Gnosis point. The result of the second
roll must be kept, and this Gift may only be used once
per short rest.
  
#### Falcon’s Grasp
  *Silver Fang, Rank 1 Gift*
  
  **Casting Time** bonus action
  
  **Range:** Self
  
  **Duration:** 1 minute
  
  **Gnosis:** n/a 
   
  **Rage:**  1
  
The werewolf’s hands
or jaws tighten in a mighty death-grip, making it nearly
impossible to escape. A falcon-spirit teaches this Gift.
  
**System:** As a bonus action, the player spends one Rage point. For one minute, the Garou’s grip (with both hands and jaws) is much stronger — she has advantage to any grappling maneuvers against her targets.  Additionally, any attempt while in a grapple to break free is done so with disadvantage.
  
#### Falling Touch
  *Ahroun, Rank 1 Gift*
  
  **Casting Time** bonus action
  
  **Range:** Touch
  
  **Duration:** 1 turn
  
  **Gnosis:** n/a 
   
  **Rage:**  1
  
This Gift allows the
Garou to send her foe sprawling with but a touch. Any
aerial spirit can teach this Gift.
  
**System:** On any successful attack action from a melee weapon, claw, or bite, the Garou can spend 1 point of Gnosis as a bonus action and knock the target prone and deal an additional 1d8 damage from being knocked down.  
  
#### Fangs of Judgement
   *Philodox, Rank 1 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
 It falls upon the
Philodox to levy not only judgment but also punishment
against those who have fallen from their proper stations.
This Gift, taught by an ancestor-spirit, causes the werewolf’s
claws and fangs to burn with the righteous power of law.
  
**System:** The player spends one Gnosis point. For
the next 10 minutes, all of the Garou’s natural weaponry attacks
do two extra dice of damage to all beings who have fallen
from their original purpose to the service of the Wyrm(Anything that is evil)
   
#### Fatal Flaw
   *Shadow Lord, Rank 1 Gift*
  
  **Casting Time** bonus action
  
  **Range:** 40 ft
  
  **Duration:** 1 min
  
  **Gnosis:** 1 for added benefit
   
  **Rage:**  n/a
  
The Shadow Lord can
spy a target’s weakness, gaining an advantage in combat.
A Stormcrow teaches this Gift.
  
**System:**As a bonus action, The Shadow Lord focuses on a target he can see within 40 ft, and grants the Garou an extra die of damage during combat with that
target. A Gnosis can be spent to reveal one weakness of the target, (if any). Grants knowledge of further weaknesses, but not more dice.

#### Fenris Bite
   *Get of Fenris, Rank 5 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 40 ft
  
  **Duration:** 1 hour
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The werewolf’s already
vicious bite now easily mangles and severs limbs. An avatar
of Fenris teaches this Gift.
  
**System:** The Bite attack now does 3d8 + Strength damage, and the opponent makes a dex saving throw.  If failed, his next attack is made with disadvantage.  This lasts for 1 hour.
  
 <div class='pageNumber'>49</div>
<div class='footnote'>PART 4 | GIFTS</div>
  \page
#### Feral Lobotomy
   *Theurge, Rank 5 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** Until Cured
  
  **Gnosis:** 5 on a failed save from the target
   
  **Rage:**  n/a
  
Unleashing a
surge of pure Wyld energy, the werewolf can devolve
an opponent’s mind into that of an animal, effectively
destroying his intelligence. A Wyldling teaches this Gift.
  
**System:** The target rolls an intelligence save. Failure takes 5d10 psychic damage.  Also on a failure, roll 3d6, if the total equals or succeeds the targets intelligence score, the score is reduced to 2 if the Garou chooses to spend 5 gnosis points.  The target is stunned for one round. Can be cured with a greater restoration spell..  The Targets intelligence is replaced
with feral, animalistic behavior.

#### Firebringer 6
   *Ragabash, Rank 5 Gift*
  
  **Casting Time** Reaction
  
  **Range:** Self
  
  **Duration:** Permanent
  
  **Gnosis:** 10
   
  **Rage:**  n/a
  
The Ragabash performs
the ultimate trick, stealing a supernatural power and turning
it into a Gift, which may in turn be bestowed upon others
as though the New Moon were a spirit teacher. Alas, the
Ragabash must first survive having the power used upon
him. Coyote or another trickster Incarna teaches this Gift.
  
**System:** After having a power used on him, the
Ragabash may spend 10 Gnosis points  to
internalize it into a Gift. Forfeits all defenses against that
power  Any power may become a Gift in this fashion — even the
vile magic of the Wyrm may be stolen and turned to the
defense of Gaia. The Storyteller determines the new Gift’s
appropriate level and what sort of spirit Garou should be
able to learn it from. During the next long rest, the Garou 
will be able to use that power as a gift.

 
#### Form Mastery
   *Metis, Rank 2 Gift*
  
  **Casting Time** none
  
  **Range:** Self
  
  **Duration:** Permanent
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
This Gift empowers
the Wyld spark that resides in all Garou, granting the
character greater control over her shapeshifting abilities.
A wolf-spirit teaches this Gift.
  
**System:** When shapeshifting while you have 0 Rage points, all difficulties
are reduced by 1. Additionally, you can enact partial
transformations (grow Crinos Claws in Homid Form for example, or longer teeth to bite)
  
*** This Gift’s effects are permanent.***
  
#### Full Moon’s Light
   *Ahroun, Rank 4 Gift*
  
  **Casting Time** 10 minutes
  
  **Range:** 1 mile radius
  
  **Duration:** 24 hours
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The full moon
is Luna’s warrior phase, when she searches out her enemies.
The Ahroun can call upon her determination in finding her
foes, illuminating any who oppose her. Lunes teach this Gift.
  
**System:** The player spends one Gnosis point. For the
remainder of the scene, anyone within one mile who is
working against the Ahroun or her pack emits a soft glow,
as though illuminated by moonlight. This Gift can be used
to confound powers of stealth or even invisibility, but only
if the target is actively attempting to harm, compete with,
or otherwise foil the Ahroun or her pack.
  
#### Geas
   *Philodox, Rank 5 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Touch
  
  **Duration:** Until Dismissed
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
This Gift binds an individual
or group to a sacred oath. While the geas cannot force
and individual to act against her nature (such as to allow
herself to be killed), it also doesn’t allow her to act
against the task the Philodox has set before her. This Gift
is taught by an Incarna avatar.
  
**System:** The player spends one Gnosis point and the target rolls a Wisdom save while the Garou lays his hand on the target while describing the task being assigned to him.  The target can verbally agree, but if he does, this also enforces that agreement on a spiritual level.  The
compulsion to complete the task set out in the geas lasts
until the task is completed or the target is harmed to the
point of incapacitation in pursuit of the quest. For every action the the target outright denies the opportunity to complete the said task, a wisdom check is made for every attempt not to.  Saves for half of 3d6 damage per attempt.  This ends when the task is completed, or a remove curse spell is cast on the target, however in the attempt to remove this spiritual pact of binding, the target and the one removing the curse (if not himself) can save for half of 15d8 damage.

#### Gift of Dreams
   *Galliard, Rank 4 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Touch
  
  **Duration:** Special
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Galliard crafts
a dream, then breathes it into a sleeping individual. A
Lune teaches this Gift.
  
**System:** The player rolls Deception to craft the dream; the higher the roll allows for more
vivid and impactful dreams. To ensure that an individual
experiences this dream, the Galliard must breathe it into
the target’s mouth while they sleep. The player spends a
Gnosis point to complete the Gift. Dreams crafted with
this Gift are often unusually vivid and dramatic, often
leaving even lifelong skeptics convinced that they hold
some deep meaning.

 <div class='pageNumber'>50</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
 \page 
#### Gift of the Porcupine
   *Metis, Rank 4 Gift*
  
  **Casting Time** bonus action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The werewolf
undergoes a startling transformation: Her fur elongates,
becoming bristly and sharp like the quills of a porcupine.
The werewolf must be in Crinos, Hispo or Lupus form to
use this Gift. Porcupine teaches this gift, and he has a
strong fondness for metis.
  
**System:** The character spends a Gnosis point to sharpen
her fur. Anyone whom the metis tackles, grapples or immobilizes
takes 2d8 + STR modifier +1 and is considered magical. damage from these
newfound quills. Furthermore, those who strike her with
bare flesh (unarmed Strikes or grapple) take their own Strength or Dex(whichever they use for attack)modifier in  damage (this does not negate any damage done to the metis). 
This Gift lasts for 10 min
 or until the werewolf wills her fur to return to normal.  
#### Gift of the Spriggan
   *Fianna, Rank 5 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 1 hour
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Fianna
grows to three times her normal size or shrinks to the size
of a small puppy. A Chimerling teaches this Gift.
  
**System:** The player spends one Gnosis point. The effects last for
one hour or until the Garou cancels the Gift.
If the Garou grows larger, she gains a +3 Strength 100% increase in size. If she grows smaller, she
retains her normal Traits, but she may sneak around unnoticed
or masquerade as someone’s pet.
 
#### Glib Tongue
  *Fianna, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** 1 minute
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
Listeners hear
whatever the Garou wishes them to. The Fianna can say
anything, even total nonsense, but anyone listening will
agree heartily. A rabbit-spirit teaches this Gift.
  
**System:** The player spends one Gnosis point and a target within 60 ft makes a wisdom save.  The target agrees completely with the Garou
for one minute, if the target takes damage during this time, it may reroll a wisdom save to break free of the gift.  After which sanity reasserts itself.

#### Gnaw
  *Lupus, Rank 4 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** 1 hour
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The werewolf’s jaws
strengthen until she can chew through nearly anything.
Her fangs inflict more damage in combat, and only death
will break her grip if she clamps her teeth into an opponent.
Hyena- and wolf-spirits teach this Gift.
  
**System:** The player spends one Gnosis point
and rolls a Con Save against a variable difficulty (5 for
wood, 10 for steel handcuffs, 15 for 3” steel, anything thicker or stronger than that would not be successful).The length of time it takes to gnaw through something
depends on what is attempted to be gnawed through. Additionally, the
Gift grants a character’s bite two extra dice of damage
for 1 hour.

#### Grandmother’s Touch
  *Children of Gaia, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Touch
  
  **Duration:** n/a
  
  **Gnosis:** 1 - max allowed
   
  **Rage:**  n/a
  
the Garou channels spiritual power through her hands, mending the wounds of any other living creature. The Garou touches a creature, and heals 1d4/Gnosis point spent.  This is the same as Mother’s Touch, but can also heal himself.
  
#### Grasp the Beyond
  *Theurge, Rank 4 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Touch
  
  **Duration:** 10 minutes if unwilling
  
  **Gnosis:** 1 - 3
   
  **Rage:**  n/a
  
The werewolf
may carry things in and out of the Umbra without having
to dedicate them to herself (see the Rite of Talisman
Dedication). This Gift affects objects, people and
animals, both willing and unwilling. An opossum- or
kangaroo-spirit teaches this Gift.
  
**System:** The character must grasp the object or person
he wishes to take to (or from) the spirit world, and
spend a number of Gnosis points: one for small items
(a knife ), two for larger items (a backpack
Or longsword), and three for man-sized items (including
people). The objects or person becomes a temporary Glyphed Tattoo on the Garou while traveling.  If the target is an unwilling one, a Wisdom save must be passed every 10 minutes.  If the subjects are willing to become glyphed onto the Garou’s skin for a short period, the links can be even stronger.  The target is absorbed into the Garou’s skinned Glyph, however he can take actions from there where it can see(The players can decide where on the Garou the Glyph is located for visual purposes.), and even cast spells.  However once a ranged attack or spell is cast the glyph is used up and the caster is reformed into its original shape within 5 ft of the Garou.

 <div class='pageNumber'>51</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Gremlins
  *Ragabash, Rank 3 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Touch
  
  **Duration:** Permanent
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The Ragabash can
cause a technological device to malfunction merely by
touching it. This Gift actually causes the spirit energy
within the device to work counter to its function. If the
Garou can frighten the spirit sufficiently, it will flee the
device, causing it to malfunction permanently. A Gremlin
teaches this Gift.
  
**System:** The player is able to make an Intimidation check;
the difficulty is determined by the complexity of the
item.(DC 5 to jam a lever, DC 10 a motorized construct). Any living construct would have to make a Dex Save or be paralized, they could try again at the end of their next turn.

#### Halt the Coward’s Flight
  *Get of Fenris, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Touch
  
  **Duration:** Permanent
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The Get
may slow a fleeing (not charging) foe, making him easier
to catch. A wolf-spirit teaches this Gift.
  
**System:** As a bonus action, the Garou may call upon the essence of the wolf spirit to catch his foe.  A successful Spell attack deals 3d10 + Level in force damage as the wolf spirits essence clamps down on a target as well as halving its movement speed.  A successful Dex Save can break free from the wolf spirit’s grasp.  The range of this gift is 120 ft.  
#### Hand Blade
  *Silver Fang, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** n/a
   
  **Rage:**  1
  
 Many Silver Fangs are
trained in swordplay as part of their birthright. This Gift
allows them to rely on such skills at any time by turning
their arm into a razor-sharp blade that slices and cuts like
the best-forged sword. An ancestor spirit, usually a former
klaive-dueling master, teaches this Gift.
  
**System:** The player spends a point of Rage to transform
one or both hands. For the next 10 minutes, he may use his
arm like a longsword + 1 and is considered magical. The damage of this weapon is 1d10 +1+Str 
as his claws are part of the blade.

#### Hare’s Leap
  *Lupus, Rank 1 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1 for added benefit
   
  **Rage:**  n/a
  
The werewolf can
leap impossible distances. Hare-spirits teach this Gift,
naturally, though cat-, frog-, kangaroo-, and even flea spirits
occasionally do so as well.
  
**System:** The player makes a reflexive Athletics check (difficulty 10) to activate this Gift. If successful,the character’s leaping distances are doubled for10 min 
— or tripled for a single turn with the expenditure
of a Gnosis point

#### Head Games
   *Galliard, Rank 5 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 30 ft
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1 per 100 HP
   
  **Rage:**  n/a
  
Emotions become
a palette with which the Galliard may paint whatever
picture takes her fancy. She may change the target’s emotions
as she pleases, from love to hate and back again. A
coyote-spirit teaches this Gift.
  
**System:** You attempt to charm a creature you can see within 30ft. It must make a Wisdom saving throw, and it does so with advantage if you or your companions are fighting it. If it fails the saving throw, it is charmed by you until the spell ends or until you or your companions do anything harmful to it. The charmed creature is friendly to you. When the spell ends, the creature knows it was charmed by you. Cost 1 gnosis for every 100 hp the target has.
  
#### Heart of Fury
  *Ahroun, Rank 3 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The Garou steels
himself against anger, suppressing his Rage and creating
a mental wall to hold back the tide of righteous fury that
threatens to drown him. The anger always returns, however,
and the Garou had best be ready to pay its bill. A
boar-spirit teaches this Gift.
  
**System:** The player rolls 1d20 + current rage score, if it is higher than his Wisdom Score, he can be resistant to any mind altering effects and any wisdom saves are rolled with advantage for the next 10 minutes.  If the Garou already had resistances to any conditions which require a wisdom save, then he is immune to those conditions.
  

 <div class='pageNumber'>52</div>
<div class='footnote'>PART 4 | GIFTS</div>
  \page
#### Heart of the Mountain
  *Get of Fenris, Rank 4 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 8 hours
  
  **Gnosis:** n/a
   
  **Rage:**  1
  
The werewolf
becomes as untiring and eternal as the mountains,
and cannot be defeated in a test of endurance. A mountain
goat-spirit teaches this Gift.
  
**System:** The player spends one Rage point. For the next 8 hours, the Garou
cannot fail any task involving a Constitution roll. Torturers can
never break him; though he can’t breathe underwater and
his lungs may fill with water, he will not die. The only
exception to this is attack damage. If this is the case, one time while this gift is active, if the Garou falls to 0 HP from an attack, it becomes 1 instead. 

#### Heightened Senses
   *Lupus, Rank 1 Gift*
  
  **Casting Time** 1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
This Gift
sharpens the werewolf’s senses to an incredible degree.
She enjoys the olfactory and auditory acuity of a wolf
whenever she is in Homid and Glabro forms, along with
superior night vision. In Crinos, Hispo and Lupus, her
senses become preternaturally potent, allowing sensory
feats that border on precognition. Sudden loud noises,
bright lights or overwhelming scents can be disorienting,
however. Wolf-spirits teach this Gift.
  
**System:** The player spends a Gnosis point to activate
this Gift for 10 min. In Homid, the werewolf gains a +2 on 
Perception checks, and if applicable has the ability to track the scent.
In Crinos and Lupus,the Garou gains a +3 with advantage on 
Perception checks(this is not cumulative with the ordinary Lupus-form Perception bonuses) and if applicable, the Garou can shapeshift as a bonus action instead.  

#### Horde of Valhalla
   *Get of Fenris, Rank 5 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 50 ft
  
  **Duration:** 8 hours
  
  **Gnosis:** up to max allowed amount for level
   
  **Rage:**  up to max allowed amount for level
  
When a Get
evokes this Gift, he summons Beserker Wolves to aid him.
It cannot be used lightly, and it requires a good standing
with Fenris as well as a truly worthy circumstance. An
avatar of Fenris teaches this Gift.
  
**System:** The player may spend as many points of Rage
and Gnosis as desired, and then rolls Charisma DC 12 ( with advantage if not used within the last 7 days). The number of Berserker Wolves that appear
is equal to the number of Rage and Gnosis points spent. and they remain for the next 8 hours or until dismissed.  The Garou can break through the Gauntlet in any direction within 50 ft.  Through this gateway, is where the Beserker Wolves spawn.
  
___
> ## Berserker Wolf
>*Large beast, unaligned*
> ___
> - **Armor Class** 15 (natural armor)
> - **Hit Points** 50(9d10 + 27)
> - **Speed** 50 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|18 (+4)|16 (+3)|16 (+3)|3 (-4)|12 (+1)|7 (-2)|
>___
> - **Skills** Perception +4, Stealth +6
> - **Senses** passive Perception 14
> - **Languages** --
> - **Challenge** 5 (1,800 XP)
> ___
>**Blood Frenzy.** The wolf has advantage on melee attack rolls against any creature that doesn't have all its hit points.
>
>**Keen Hearing and Smell.** The wolf has advantage on Wisdom (Perception) checks that rely on hearing or smell.
>
>**Pack Tactics.** The wolf has advantage on an attack roll against a creature if at least one of the wolf's allies is within 5 feet of the creature and the >ally isn't incapacitated.
> ### Actions
>***Multiattack.*** The wolf makes three attacks: one with its bite and two with its claws.
>
>***Bite.*** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 17 (3d8 + 4) piercing damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.
>
>***Claw.*** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13 (2d8 + 4) slashing damage.


#### Howl of the Banshee
   *Fianna, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** 1 minute
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The werewolf
emits a fearful howl that causes those who hear it to run
in terror. A Banshee — a mournful spirit of the dead —
teaches this Gift.
  
**System:** The player spends a Gnosis point and anyone who can hear the Garou within 60 ft makes a wisdom save or flee in terror until they take damage, or pass their wisdom save.  
  
 <div class='pageNumber'>53</div>
<div class='footnote'>PART 4 | GIFTS</div>

  \page
#### Howl of the Unseen
  *Fianna, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 60 ft
  
  **Duration:** 1 minute
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
This Gift
allows a howl or proclamation from one side of the
Gauntlet to echo across into both realms. It is taught by
a cricket-spirit.
  
**System:** The player spends one Gnosis and produces a magical darkness from the spirit realm in a 15 ft radius that the Garou can place within 60 ft of him.  The Garou can use its howl to not suffer the disadvantage effects of the darkness as long as the sounds can reflect off a physical body or object of the target.  All creatures inside suffer the same effects as the darkness spell.  
  
#### Howls in the Night
  *Galliard, Rank 2 Gift*
  
  **Casting Time** 1 action
  
  **Range:** 200 ft
  
  **Duration:** Special
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The werewolf
sends a full-throated howl shivering into the night sky,
evoking primal terror in Gaia’s enemies. Creatures of the
Wyrm who hear the howl find themselves troubled and
unable to rest easily while their enemies are on the prowl.
A wolf-spirit teaches this Gift.
  
**System:** The player spends a Gnosis point any hostile within 200ft rolls wisdom save.  If this is done before combat is initiated, then the ones who failed within range, has a disadvantage to any initiative rolls.  If this is used during the course of combat already, then any hostile within range rolls their next attack action at a disadvantage.  (does not count for the any attacks following the first)  In addition, any undead within 30 ft that you can see or hear is turned for 1 min or until it takes damage.  
#### Icy Chill of Despair
  *Shadow Lord, Rank 3 Gift*
  
  **Casting Time** Concentration, 1 action
  
  **Range:** 60 ft
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Shadow
Lord appears to grow larger and more imposing, becoming
a terrible, shadowy version of herself. This change in
aspect can severely intimidate any onlookers. A Stormcrow
teaches this Gift.
  
**System:** The werewolf concentrates for a turn; the
player spends one Gnosis point. Anyone who means the Shadow
Lord harm must make a Wisdom Save to attack, take action against or even
verbally oppose the Shadow Lord. This Gift doesn’t give
the Lord actual control over her intimidated victims —
they’re simply too spooked to actively oppose her.


#### Jam Technology
  *Homid, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 50 ft
  
  **Duration:** 2 turns
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
With a slight
gesture, the werewolf unbalances the Wyld and Weaver
energies within technological devices, either suffusing
them with destructive chaos or amplifying their inherent
stasis until they refuse to do anything at all. Computers
crash, guns jam, motors stall, and even the simplest of shaped
objects refuse to function. A gremlin — a type of Wyldspirit
that enjoys breaking things — teaches this Gift.
  
**System:** The player spends one Gnosis point. All technological devices (i.e.
any devices shaped from fabricated materials like metal
or plastic) within 50 feet (15 m) cease to function for two turns. The devices remain
unchanged, but inert — knives won’t cut, gunpowder won’t ignite, gears won’t turn, and so on.  While the Garou can effectively remove the sharpness of a blade, it won't remove damage from a blunt object. In these cases, damage from the weapon wouldn't be applied, however, the bonus damage from the weilder’s strength and other modifiers would apply.
 
#### Jam Weapon
  *Children of Gaia, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft cone
  
  **Duration:** end of next turn
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Child may stop
any Weaver-born weapons from working within the range
of his voice. A dove-spirit teaches this Gift.
  
**System:** The Garou shouts an ancient word of power
and grace and spends a Gnosis point. Targets within a 60ft cone makes a Wisdom Save. If failed, all manufactured weapons will not function until the end of the Garou’s next turn. This
includes guns, crossbows, flame-throwers, and even knives
and swords, which refuse to cut. Natural weapons (such as
claws) and natural objects appropriated as weapons (such
as rocks or naturally-fallen tree limbs) are unaffected.

#### Lambent Flame
  *Silver Fangs, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 100 ft radius
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The werewolf
causes her body to ignite with silver light. A Lune teaches
this Gift.
  
**System:** The player spends one Gnosis point to
activate the Gift. The light illuminates a 100-foot (30
m) area around the Garou for the next 10 minutes. Additionally, all attacks made against the Garou within 5 ft must make a Wisdom save or be blinded until the end of their next turn.  

 <div class='pageNumber'>54</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Lash of Rage
  *Metis, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 300 ft 
  
  **Duration:** n/a
  
  **Gnosis:** n/a
   
  **Rage:**  1
  
The metis harnesses
all of the shame, hate, and fury coiled in his heart and
lashes out with it, destroying another. Bones snap, organs
rupture, and cavities fill with blood as the metis’s Rage
tears the target apart. A spirit of fury teaches this Gift.
  
**System:** The player spends one Rage point and  target rolls DEX Save A target within 300 ft takes 10d6 + 40 force damage..
This Gift can be used safely only once per scene. Any
additional uses inflict the Gift’s full damage on both the
metis and his target.
 
#### Ley Lines
   *Fianna, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** n/a
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
By manipulating ley
lines — a spiritual grid that crisscrosses the planet — the
Fianna can disorient would-be trackers or hunters. The
victims of this Gift find themselves following false trails,
making wrong turns or walking in circles. An earth-spirit
teaches this Gift.
  
**System:** By spending a Gnosis point, any creature actively searching for the Garou or in his area rolls perception at disadvantage.  Any actions taken by the Garou to counter the effects of hiding from plain sight would end this effect however.   
#### Liar’s Craft
  *Ragabash, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft
  
  **Duration:** Until Dismissed
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Ragabash can
tell the most outrageous of lies and have them accepted
as truth — for a while, at least. This Gift is taught by a
fox-spirit.
  
**System:** As in Liar’s Face, but these effects can affect an entire crowd.After the character makes a truthful statement,
the player spends one Gnosis point and rolls
Deception vs someone in the group who has the highest Wisdom Save score, if failed, the effects becomes contagious to all others from the group. Any successful margin, no matter how big or small will automatically assume you are lying. (Of Course im not a member of the courts guard!  ::wink::)  This would automatically assume that you are as they start laughing at your joke.
 Since the roll is made after the lie is told, this Gift always carries some element of risk.

#### Liar’s Face
  *Ragabash, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft
  
  **Duration:** Until Dismissed
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Ragabash wraps
herself in such a deceitful attitude that nothing she says
can be trusted — not even the clear and unvarnished truth.
The werewolf may make a single truthful statement, and
no human who hears it will believe her. A platypus-spirit
teaches this Gift.
  
**System:** After the character makes a truthful statement,
the player spends one Gnosis point and rolls
Deception vs targets insight.  Any successful margin, no matter how big or small will automatically assume you are lying. (Of Course im not a member of the courts guard!  ::wink::)  This would automatically assume that you are as they start laughing at your joke.
 
#### Lover’s Touch
  *Children of Gaia, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Touch
  
  **Duration:** n/a
  
  **Gnosis:** 1-5
   
  **Rage:**  n/a
  
The Garou can
restore what another lacks: not only wounds healed, but
also strength of will and even spiritual essence. Any spirit
of love or avatar of Unicorn may teach this Gift.
  
**System:** The Garou touches the afflicted individual
kindly. The two need not be lovers, but the contact must
convey affection and warmth — an embrace, a caress, or
yet more intimate contact. The player heals the target for 1d6  per Gnosis point spent.  Cannot spend more Gnosis than their current unlocked Rank at their level.  (Max 5d6, if they have access to Rank 5 gifts).  In addition, the Garou can also roll any Save throw of the embraced if they are suffering from any current conditions that.  The difficulty would be the same as if the target was rolling their save on their turn.  If the Garou succeeds the save,  any conditions the embraced suffered from ends before their next turn.
 
#### Luna’s Armor
  *Children of Gaia, Rank 2 Gift*
  
  **Casting Time**  Concentration 1 turn
  
  **Range:** Touch
  
  **Duration:** 1 minute
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Child of Gaia
invokes the moon’s sacred power. Her body is briefly
wreathed in a shimmer of moonlight, granting her Luna’s
protection. This Gift is taught by a Lune.
  
**System:** The werewolf concentrates for a turn; the
player spends one Gnosis point and rolls their survival + prof (if proficient) +
level.  The total amount rolled including any modifiers is added to their temporary HP. The
benefit lasts for one minute.



 <div class='pageNumber'>55</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Luna’s Avenger
  *Silver Fang, Rank 5 Gift*
  
  **Casting Time**  Concentration 1 turn
  
  **Range:** Self
  
  **Duration:** 1 hour
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Silver Fang
transforms his greatest weakness into his greatest strength,
transforming his body into living silver. A Lune teaches
this Gift.
  
**System:** The Garou concentrates for a full turn to activate
this Gift. The player spends a Gnosis point; for the next hour.  The Garou is immune to the effects of silver.  All damage inflicted by attacks made with the werewolf’s
body are considered to have been made with silver weapons.
Additionally, the character gains two additional +30 Temporary HP and a +1 to his AC.  
#### Luna’s Blessing
  *Ragabash, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
When Luna stands
visible in the night sky, silver ceases to act as a bane to the
Garou. Indeed, when the moon waxes full, silver may well
turn on those who would wield it against Gaia’s children.
A Lune teaches this Gift.
  
**System:** After spending a Gnosis point, for the next 10 minutes, any and all dice rolled to inflict damage to the Garou becomes a 1 instead when the moon shows in the sky in a visible
phase, Additionally, during the day, only 1 damage die is affected, also, on nights of the new moon, and when the moon is below the horizon.

#### Madness
  *Metis, Rank 5 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
Metis struggle throughout
their lives to find a place of dignity and respect amidst
a minefield of horror and abuse. This Gift allows her to
unleash her inner demons upon others, inflicting insanity
and madness. The nature of the derangement inflicted
varies from individual to individual, but is always severe,
making it impossible for the victim to function normally.
Lunes and spirits of trickery and madness teach this Gift.
  
**System:** The player spends 5 Gnosis points to activate to gift on a target he can see within 60 ft.  Target makes a Wisdom Save, on a failed save, the target rolls a d100:
0-33 = long term effect + Indefinite Madness
34-66 = long term effect
67-100= Short term effect
He suffers a random madness effect on the madness chart.Even after the Gift has ended, the
repercussions may haunt the victim for the rest of his life.
 ```
```

 
##### Madness Effects
Madness can be short-term, long-term, or indefinite. Most relatively mundane Effects impose short-term madness, which lasts for just a few minutes. More horrific Effects or cumulative Effects can result in long-term or indefinite madness.

A character afflicted with short-term madness is subjected to an effect from the ***Short-Term Madness table*** for 1d10 minutes.

A character afflicted with long-term madness is subjected to an effect from the ***Long-Term Madness table*** for 1d10 × 10 hours.

A character afflicted with indefinite madness gains a new character flaw from the ***Indefinite Madness table*** that lasts until cured.
 
  
  ##### Short-Term Madness Table  
  <table>
    <tr>
      <td>**d100**  </td>
      <td>**Effect (lasts 1d10 minutes)**</td>
    </tr>
    <tr>
    <td>**1-20**</td>
    <td>The character retreats into his or her mind and becomes Paralyzed. The effect ends if the character takes any damage.</td>
    </tr>
    <tr>
      <td>**21-30**</td>
      <td>The character becomes Incapacitated and spends the Duration screaming, laughing, or weeping.</td>
    </tr>
    <tr>
      <td>**31-40**</td>
      <td>The character becomes Frightened and must use his or her action and Movement each round to flee from the source of the fear.</td>
    </tr>
    <tr>
      <td>**41-50**</td>
      <td>The character begins babbling and is incapable of normal Speech or Spellcasting.</td>
       <tr>
      <td>**51-60**</td>
      <td>The character must use his or her action each round to Attack the nearest creature.</td>
    </tr>
    <tr>
      <td>**61-70**</td>
      <td>The character experiences vivid hallucinations and has disadvantage on Ability Checks.</td>
    </tr>
    <tr>
      <td>**71-75**</td>
      <td>The character does whatever anyone tells him or her to do that isn’t obviously self-­ destructive.</td>
    </tr>
    <tr>
      <td>**76-80**</td>
      <td>The character experiences an overpowering urge to eat something strange such as dirt, slime, or offal.
    </tr>
    <tr>
      <td>**81-90**</td>
      <td>The character is Stunned.
    </tr>
    <tr>
      <td>**91-100**</td>
      <td>The character falls Unconscious.</td>
       </table>  
  
##### Long-Term Madness Table  
<table>
    <tr>
      <td>**d100**  </td>
      <td>**Effect (lasts 1d10 x 10 hours)**</td>
    </tr>
    <tr>
    <td>**1-10**</td>
    <td>The character feels compelled to repeat a specific activity over and over, such as washing hands, touching things, praying, or counting coins.</td>
    </tr>
    <tr>
      <td>**11-20**</td>
      <td>The character experiences vivid hallucinations and has disadvantage on Ability Checks.</td>
    </tr>
    <tr>
      <td>**21-30**</td>
      <td>The character suffers extreme paranoia. The character has disadvantage on Wisdom and Charisma Checks.</td>
    </tr>
    <tr>
      <td>**31-40**</td>
      <td>The character regards something *(usually the source of madness)* with intense revulsion, as if affected by the antipathy effect of the Antipathy/Sympathy spell.</td>
       <tr>
      <td>**41-45**</td>
      <td>The character experiences a powerful delusion. Choose a potion. The character imagines that he or she is under its Effects.</td>
    </tr>
  </table>
  
   <div class='pageNumber'>56</div>
<div class='footnote'>PART 4 | GIFTS</div>
  \page
##### Long-Term Madness Table *Continued*  
  <table> 
  <tr>
      <td>**46-55**</td>
      <td>The character becomes attached to a “lucky charm,” such as a person or an object, and has disadvantage on Attack rolls, Ability Checks, and Saving Throws while more than 30 feet from it.</td>
    </tr>
    <tr>
      <td>**56-65**</td>
      <td>The character is Blinded (25%) or Deafened (75%).</td>
    </tr>
    <tr>
      <td>**66-75**</td>
      <td>The character experiences uncontrollable tremors or tics, which impose disadvantage on Attack rolls, Ability Checks, and Saving Throws that involve Strength or Dexterity.
    </tr>
  </table>
<table>
    <tr>
      <td>**76-85**</td>
      <td>The character suffers from partial amnesia. The character knows who he or she is and retains Racial Traits and Class Features, but doesn’t recognize other people or remember anything that happened before the madness took effect.
    </tr>
    <tr>
      <td>**86-90**</td>
      <td>Whenever the character takes damage, he or she must succeed on a DC 15 Wisdom saving throw or be affected as though he or she failed a saving throw against the Confusion spell. The Confusion effect lasts for 1 minute.</td>
    </tr>
    <tr>
      <td>**91-95**</td>
      <td>The character loses the ability to speak.</td>
    </tr>
    <tr>
      <td>**96-100**</td>
      <td>The character falls Unconscious. No amount of jostling or damage can wake the character.</td>
      
        
      
  </table>    
  
##### Indefinite Madness Table
<table>
 <tr>
    <td>**d100**</td><td>**Flaw (lasts until cured**)</td>
  </tr>
  <tr>
    <td>**01–15**</td><td>	“Being drunk keeps me sane.”</td>
  </tr>
  <tr>
  <td>**16 - 25**</td><td>	"I keep whatever I find."</td>
   </tr>
  <tr>
    <td>**26–30**</td><td>	“I try to become more like someone else I know—adopting his or her style of dress, mannerisms, and name.”</td>
  </tr>
  <tr>
    <td>**31–35**</td><td>	“I must bend the truth, exaggerate, or outright lie to be interesting to other people.”</td>
  </tr>
  <tr>
    <td>**36–45**</td><td>	“Achieving my goal is the only thing of interest to me, and I’ll ignore everything else to pursue it.”</td>
  </tr>
  <tr>
    <td>**46–50**</td><td>	“I find it hard to care about anything that goes on around me.”</td>
  </tr>
  <tr>
    <td>**51–55**</td><td>	“I don’t like the way people judge me all the time.”</td>
  </tr>
  <tr>
    <td>**56–70**</td><td>	“I am the smartest, wisest, strongest, fastest, and most beautiful person I know.”</td>
  </tr>
  <tr>
    <td>**71–80**</td><td>	“I am convinced that powerful enemies are hunting me, and their agents are everywhere I go. I am sure they’re watching me all the time.”</td>
  </tr>
  <tr>
    <td>**81–85**</td><td>	“There’s only one person I can trust. And only I can see this Special friend.”</td>
  </tr>
  <tr>
    <td>**86–95**</td><td>	“I can’t take anything seriously. The more serious the situation, the funnier I find it.”</td>
  </tr>
  <tr>
    <td>**96–100**</td><td>	“I’ve discovered that I really like killing people.”</td>
  </tr>
  </table>

  
#### Malleable Spirit
  *Theurge, Rank 5 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 120 ft
  
  **Duration:** Special
  
  **Gnosis:** 3
   
  **Rage:**  n/a
  
 The werewolf can
change a spirit’s form or purpose. A Chimerling teaches
this Gift.
  
**System:** The player must hit the target within 120ft with a psychic beam of energy, if the target is hit, it deals 14d6 damage the spirit rolls a wisdom save.  On a failed save, the alignment of the creature can be altered.  Temporarily altering its way of thinking or beliefs.  3 Gnosis, must be spent, and Intelligence must be 10 or lower for it to be Permanent.  Higher than 10 is for 1d4 days, and higher than 15 is 1d10 minutes.  The creature will still attack if it feels threatened, but possible that its disposition may change as well, but if it flees, the actions it would take for the time being would be dictated by the alignment and beliefs it was altered to be. 
  
#### Mark of the Wolf
   *Homid, Rank 2 Gift*
  
  **Casting Time**  10 minutes
  
  **Range:** 120 ft
  
  **Duration:** 1 day
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The werewolf
marks those she comes in contact with, leaving them to carry
the same aura of the predator the Garou does. This subtle
curse can wreak havoc in a target’s private or professional
life, and is a favorite of many homids looking to provoke
discord in the ranks of the enemy. A Lune teaches this Gift.
  
**System:** The player selects a target that has had
some interaction with the Garou(even something as simple as light conversation in a shop counts). If the target fails a CHA save, they inherit “The Curse” for one day, giving them disadvantage on social skill checks.

#### Master of Fire
   *Homid, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
Fire-spirits were among the very first to make pacts with humanity, allowing men to warm themselves, drive off wild beasts, andclear the land. The cornerstones of civilization were laid in these simple acts, granting the spirits of flame much
prestige. Homid Garou remembers and continues to call upon these ancient pacts to protect themselves as the final fires of the Apocalypse loom. An ancestor-spirit or fire elemental teaches this Gift.
  
**System:** The player spends one Gnosis point. For 10 minutes the Werewolf is resistant to  fire damage. 
  
 <div class='pageNumber'>57</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Mental Speech
   *Metis, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 1d10 x 10 miles
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
 This Gift enables
mental communication, even over vast distances. The
user must either know the target personally (although
friendship isn’t necessary) or have something that belongs
to that person, such as a lock of his hair. Bird-spirits and
spirits of intellect teach this Gift.
  
**System:** The player rolls Charisma modifier + Proficiency bonus (difficulty
10) and spends a Gnosis point; the effects last for
a scene. The character may hold a mental conversation
with a target at a maximum distance of 1d10 x 10 miles
 Mind reading isn’t possible, but the werewolf
may use social Abilities such as Intimidation.

#### Mindblock
   *Silver Fang, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 1 hour
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The Garou fortifies
her will against mystical influences of all sorts. A falconspirit
teaches this Gift.
  
**System:** The Silver Fang gains advantage to any saving throws of any direct mental attacks
or attempts to control the Garou’s mind, as well as more
insidious psychic assaults (mind-reading, illusions, possession,
and so forth). This protection lasts for 1 hour.

#### Monkey Tail
   *Lupus, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 1 hour
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The lupus may
lengthen her tail and use it as a prehensile appendage at
will. Although it’s no replacement for a hand, it can grasp
objects, wrap around branches, and even allow the Garou
to hang upside-down. A monkey-spirit teaches this Gift.
  
**System:** The Garou may employ her prehensile tail
at will in any form which possesses a tail. Successfully
manipulating the tail requires a Athletics
roll (difficulty varies according to the task).

  ```
```
#### Name the Spirit
  *Theurge, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 120 ft
  
  **Duration:** Permanent
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
As the lupus Gift.  The werewolf
gains an instinctive rapport with denizens of the Umbra.
He can sense the type and approximate Trait levels (Rage,
Gnosis, ability scores) of things from other realms. Owl- and raven-spirits
teach this Gift.
  
**System:** The player spends one Gnosis and rolls
Perception  (difficulty 10).

#### Obedience
  *Theurge, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 30 ft
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Shadow Lord becomes
the ultimate alpha, compelling all others to follow
her orders. A Stormcrow teaches this Gift.
  
**System:** The player spends one Gnosis point. Al within 30 ft
Must succeed al Wisdom save , or they succumb to the Gift’s effects.
Targets follow any orders that don’t directly inconvenience them. 10 below the target DC causes the targets to treat the Lord as their alpha
and fight for her. When the link to the Shadow Lord is finally severed, those that were affected take 15d8 psychic damage. Does not affect those that are immune to charm effects.

#### Open Seal
  *Theurge, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1 (for locks sealed with magic)
   
  **Rage:**  n/a
  
 The werewolf can open
nearly any sort of closed or locked physical device. A
raccoon-spirit teaches this Gift.
  
**System:** The Ragabash gains advantage on any attempt to pick locks. If the object is sealed with magic, the player must spend a Gnosis point before making the
attempt.


 <div class='pageNumber'>58</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Open Wounds
  *Shadow Lord, Rank 4 Gift*
  
  **Casting Time**  bonus action
  
  **Range:** Special
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
The werewolf causes
the next wound he inflicts to bleed profusely, weakening
his opponent further. A pain-spirit teaches this Gift.
  
**System:** The player spends one Gnosis point and on his next attack that deals damage.  On a failed Con Save,  the target will bleed
continuously, suffering an additional 8d6 piercing damage, half damage is save is successful.  In addition, to 2d8 damage every turn the target fails its Con Save  
#### Pack Tactics
  *Ahroun, Rank 1 Gift*
  
  **Casting Time**  bonus action
  
  **Range:** Special
  
  **Duration:** Until an attack misses
  
  **Gnosis:** 1 
   
  **Rage:**  n/a
  
While the Ahroun’s
role as the overall leader of Garou is questionable, there’s
no doubt at all who should take control of the pack in
battle. By taking the lead and coordinating pack actions,
the Ahroun gifts all her packmates with great competence
in the heat of battle. A wolf-spirit teaches this Gift.
  
**System:** The player spends a Gnosis point before
initiating the Pack Tactics maneuver.  The Ahroun chooses an offensive attack action, and if successful on landing a strike gets a bonus die, the next in line to that successfully delivers an attack, gets 2 bonus dice to the damage inflicted, the following pack mate after him would get 3 bonus dice to damage, and so on (max 5).  This doesn't apply to anyone's attacks following their first.  However, if anyone's first attack misses, the accumulation of bonuses starts back at 1 bonus die, and continues on building by 1 for each packmate until its the Ahrouns turn again.  Any pack mate that chooses an action that does not apply towards the target, like a heal for instance, would NOT break the cycle of accumulating dice.  Only when an attack on the initial hit on the target fails, does it throw the rest of the party off to performing a perfectly well executed pack tactic.
 
#### Para Bellum
  *Children of Gaia, Rank 2 Gift*
  
  **Casting Time**  Instantaneous
  
  **Range:** Self
  
  **Duration:** 1 minute
  
  **Gnosis:** n/a
   
  **Rage:**  1
  
Though the Children
love life, spring, and all that is good of Gaia, they aren’t
pacifists; they always stand ready to protect their Mother.
The werewolf’s Rage bursts forth in a torrent when another
breaks the peace she so cherishes. A bear-spirit teaches
this Gift.
  
**System:** This Gift may only be used at the beginning
of a battle that was not initiated by the Garou, her pack,
or her allies. The player spends one point of Rage; for the next minute, the character enjoys one additional die to any damage inflicted upon the enemy
who fired the first shot of the battle, or any character that
has inflicted an injury on a member of the Child’s pack
during the duration.
 
#### Paralyzing Stare
   *Shadow Lord, Rank 3 Gift*
  
  **Casting Time**  Concentation, 1 turn
  
  **Range:** 60 ft
  
  **Duration:** 1 turn
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Shadow
Lord directs a terrifying glare at a target, causing her to
freeze in terror. A Stormcrow teaches this Gift.
  
**System:** The Garou concentrates for one turn. The
player spends one Gnosis point and rolls Intimidation DC of the targets Charisma Score. Success freezes the target in place, rendering
her unable to move or attack (though she may still defend
herself). The target must be able to see the Garou and be within 60 ft.
 
#### Part the Veil
   *Homid, Rank 5 Gift*
  
  **Casting Time**  Concentation, 1 turn
  
  **Range:** 120 ft
  
  **Duration:** 1 day per Gnosis spent
  
  **Gnosis:** 1- max available for level
   
  **Rage:**  n/a
  
This potent Gift immunizes
a human from the Delirium effect. However,
the Garou can replace any crucial piece of information the target may have learned within this time, with something else that the Garou creates for her.  As long as it isn't completely out of the ordinary.  (Cant say aliens abducted you for the last 24 hours)
 An ancestor-spirit teaches this Gift.
  
**System:** The player spends a Gnosis point for each day he chooses this Gift to remain in effect
Must be within 120 ft to activate.  If the Garou chooses to substitute any piece of known information the target may have acquired, it can be replaced with another interpretation of the story, and completely forget about that event.  Target Rolls Wisdom Save to resist.  If saved, the target also realizes the attempt the Garou tried to make, and may become hostile.

 <div class='pageNumber'>59</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Pathfinder
  *Ragabash, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** --
  
  **Duration:** n/a
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The werewolf can
strike implausible trails through pristine wilderness and
the urban jungle alike, locating the fastest and shortest
routes from one place to another. A crow-spirit teaches
this Gift.
  
**System:** The player rolls Survival (for
wilderness) or Perception (for urban environments) against
difficulty 10. Success reduces travel time by approximately half the original travel time.
The difficulty of any rolls to track the werewolf increase
by two when this Gift is active; this decrease is cumulative
with other similar effects, such as Scent of Running Water.
#### Persuasion
  *Homid, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 120 ft
  
  **Duration:** 10 minutes
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
This Gift imbues a
homid’s words with intrinsic credibility and conviction,
causing them to ring true to the ear and lay heavy on the
heart. An ancestor-spirit teaches this Gift.
  
**System:** The player gains advantage on all social rolls regarding influencing another’s decision making for 10 minutes and allows successful social skill checks to have uncommonly strong impact (such as changing long-held political views, or causing an addict to seriously reconsider the course of his life
  
#### Phantasm
  *Fianna, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 120 ft
  
  **Duration:** 1 hour
  
  **Gnosis:** 1 - max available for level
   
  **Rage:**  n/a
  
The Fianna creates an
unmoving illusion that contains visual, auditory, olfactory
and even tactile elements. A grain-spirit — the so-called
“spirit of spirits” — teaches this Gift.
  
**System:** The player spends one Gnosis point for each
10-foot (3 m) radius area to be covered by the illusion. Anyone given cause
to doubt the illusion must roll a wisdom save in order to see through it.  

#### Predator’s Arsenal
  *Lupus, Rank 1 Gift*
  
  **Casting Time**  Concentration, 1 turn
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
 One of the
most unnerving aspects of the Homid shape is its lack of
proper weapons. This Gift remedies that problem (while
still retaining much of the Homid shape’s ability to blend
in with the human world), granting the Garou battle-ready
claws and teeth in Homid form. It is taught by a wolf-spirit.
  
**System:** The werewolf concentrates for a turn to gain
access to bite and claw attacks in Homid form for the next 10 min,
 or until she dismisses the transformation.
May be concealed by simple expediencies such
as the werewolf keeping her mouth closed, wearing long
sleeves, or keeping her hands in her pockets. She can
even speak normally without giving herself away, as long
as she’s careful not to open her mouth too wide or smile
so that her teeth show, although her voice sounds rough
and a bit distorted (attempting to discern that there’s
something amiss with a Garou taking such precautions
requires a Perception check vs Garous Deception check or similar).
 
#### Prey Mind
  *Lupus, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
As Gaia dies and her
natural order is perverted, predators become prey with
increasing frequency — this is a sorrowful truth that lupus
know all too well. This Gift assists the Garou in evading
their enemies that they might fight another day, showing
them places to hide, ways to run, and even chances to
strike back. A hare- or deer-spirit teaches this Gift.
  
**System:** The player rolls Survival check; difficulty
10 in the wilderness, 15 in urban environments. Success
adds advantage to all rolls to escape, outdistance,
hide from or evade pursuit for the next 10 min.
 
#### Primal Anger
  *Metis, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** n/a
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The metis gives of
herself to feed the Rage in her heart, burning away her
very blood and muscle in the process. The spirits of ancient
metis teach this Gift; few members of other breeds have
endured enough shame and suffering to learn it.
  
**System:** The character may inflict 1d10 of
 damage on herself once per short rest, and gain
three points of Rage in exchange (even if doing so takes
her beyond her permanent Rage rating).
  

  <div class='pageNumber'>60</div>
<div class='footnote'>PART 4 | GIFTS</div> 
  \page
#### Protean Form
  *Metis, Rank 5 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** Permanent
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
Born misshapen, the
metis takes her deformity and makes it a source of power.
She can twist her flesh in any number of ways, sprouting
a number of unnatural features, from extra limbs to
additional mouths to grasping tentacles. A Chimerling
teaches this Gift.
  
**System:** The character’s ability to partially transform
is permanently modified, allowing her to
make almost any grotesque modifications the player can
imagine. These modifications must logically bestow one
of the following benefits: 
+1 attack action natural weapons
(extra clawed limbs for claw attacks, tentacles
for clinches, etc), 
+2 damage dice when using modified natural weapons(a chest-mounted squid beak for extra damage on clinches, arms coated in shark teeth for boosted claw
attacks, etc.),
 +15 ft per turn of movement (extra legs)
Or Fly -10 flight speed from base speed,( vestigial wings, etc.).  These effects cannot be stacked together.  

#### Pulse of the Invisible
  *Theurge, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
Spirits fill
the world, and none know this fact better than the Theurge.
This Gift grants constant awareness of the spirit world.
Even in the physical world, the Theurge can interact with
spirits in the Penumbra at will. While most spirit activity
isn’t worth watching, the Theurge will be automatically
aware of any dramatic changes or upheavals nearby. Any
spirit can teach this Gift.
  
**System:** The Theurge’s Gnosis rating determines how deep into the umbra it can look, and be aware or alerted of any unusual activities or things that may interest the Garou.  A Gnosis point is only spent to serve as a mental link of communication to any possible targets the Garou would be alerted to.  If the Garou is too careless with whom it seeks a connection with on another plane, mental attacks are possible and resisted as you normally would in combat while the link is shared.  Communication can also be resisted with a successful Wisdom check.  The link lasts for 10 minutes, or until the Garou decides to end it..
  
#### Pulse of the Prey
   *Ragabash, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** --
  
  **Duration:** n/a
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
 If the werewolf
knows anything about her prey—even a nickname, initials,
or crude description—she can track it as fast as she can
travel. This unerring sense of direction works anywhere,
 A wolf- or dog-spirit teaches this Gift.
  
**System:** No roll is required unless the target is actively
hiding, in which case the player rolls Perception checks to keep her focus on the target.  As long as the target is on the same Realm the Ragabash can eventually find her.  This would not work if the target is hiding through any magical means, or break through any magical barriers, pocket dimensions, ect.  Can be used in the Umbra as well.
If the target is a spirit, the difficulty is the spirit’s Gnosis.

#### Rat Head
   *Metis, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** n/a
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
Metis are born into a
world where they metaphorically don’t belong; it seemed
only natural to rat-spirits to teach them to get into such
places in the literal sense as well. This Gift renders the
metis’s bone structure collapsible, allowing her to squeeze
through any gap she can fit her head into.
  
**System:** The player spends one Gnosis and rolls Dexterity
Check DC10. Until he takes a short or long rest,
the metis may squirm through any gap she can fit her face
into, moving at her walking speed to do so.
 
#### Rattler’s Bite
   *Metis, Rank 4 Gift*
  
  **Casting Time**  bonus action
  
  **Range:** within range of bite
  
  **Duration:** end of next turn
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The metis’s eyeteeth
lengthen, and she can inject a deadly poison with her bite.
Spider- and snake-spirits teach this Gift.
  
**System:** The player can choose to spend a Gnosis point after successfully biting
an opponent, to inflict 5d8 additional poison damage.  On a failed Con Save, the target is poisoned until the end of his next turn if failed.  
 
#### Redirect Pain
   *Get of Fenris, Rank 3 Gift*
  
  **Casting Time**  Reaction
  
  **Range:** Self
  
  **Duration:** n/a
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
This Gift allows
the Fenrir to visit the pain of his wounds upon those who
inflicted them. A cuckoo-spirit teaches this Gift.
  
**System:**Set up as a reaction, the Garou can redirect half of its next damage attack back at the attacker.  The Garou ignores the amount of redirected damage as well.
  
 <div class='pageNumber'>61</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Reshape Object
   *Homid, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 30 ft
  
  **Duration:** Special
  
  **Gnosis:** up to max per level
   
  **Rage:**  n/a
  
The Garou
can shape once-living (though not undead) material
into something else instantly. Trees may become shelter,
buck antlers spears, animal hides armor, and flowers sweet
perfumes. The item will resemble the object from which it
was created (e.g., the aforementioned spear will be made
of antler, not wood). A Pattern Spider teaches this Gift.
  
**System:**  The player makes a spell check against
a difficulty defined by the scope and complexity of the
transformation (a broken tree limb into a spear would be DC 10, while a fallen tree into a canoe would be 15) and spends Gnosis points. The transformation persists for 10 minutes per Gnosis, or permanent with five or more. Expending the additional Gnosis point allows a created weapon to inflict +2 damage for 10 minutes for each extra spent after creation.  
#### Resist Pain
   *Philodox, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 1 minute
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
Fortifying herself with
purpose and will, the werewolf shuts out the pain of her
wounds. A bear- or badger-spirit teaches this Gift.
  
**System:** The player spends one gnosis point and rolls a d10+level, for the next minute, the Garou ignores that amount of damage per round automatically.  Can be cast at a Higher Rank, for every rank higher add 1d10.
  
#### Resist Toxin
   *Fianna, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** Until dismissed
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The werewolf’s body
is hardened against toxins of all sorts. A rat-spirit teaches
this Gift.
  
**System:** The werewolf is permanently immunized
to mundane poisons, from arsenic to alcohol, and gains advantage to any save against being poisoned. This Gift may be turned off and on at will (such as for
enjoying alcohol).

#### Roll Over
   *Philodox, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft
  
  **Duration:** 10 minutes
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The werewolf radiates
authority and power, allowing him to exert his dominance
over others. Humans bow or kneel, while Garou roll over
to expose their throats. A wolf-spirit teaches this Gift.
  
**System:** The player begins an extended, resisted
Wisdom check contest. The results are compared to each of
her opponents in turn; when the player has scored three
more successes than an opponent, that opponent drops
out of the contest and submits. If one of the opponents
accumulates three more successes over the character, the
contest ends. For the 10 minutes, any individual
who has submitted will take no actions at all without the
approval of the character, unless their life depends on it. Can be dispelled.

#### Scent of Beyond
   *Philodox, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Any familiar place
  
  **Duration:** Until dispelled
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
With a moment’s
concentration, the werewolf can hurl her senses to any place
with which she is familiar (even an Umbral location), no
matter how far away it may be. Because a bird-spirit teaches
this Gift, her senses perceive the scene from above.
  
**System:** The player rolls Perception + level (difficulty
12).This far-seeing continues for as long as the werewolf desires,
but the character suffers a disadvantage to any attempts to
react to local stimuli while her senses are projected.
 
#### Scent of Running Water
   *Ragabash, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** Permanent
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The
werewolf can mask her scent completely, making herself
virtually impossible to track. A fox-spirit teaches this Gift.
  
**System:** Any attempt to track the Ragabash is at a disadvantage, Also, any attempt by the Ragabash to hunt or gather food, is made WITH advantage.
 This Gift’s effects are permanent, though
the Ragabash may temporarily suppress them at will (which
may be necessary to blend in with wolf packs).

 <div class='pageNumber'>62</div>
<div class='footnote'>PART 4 | GIFTS</div>

  \page
#### Scent of Sight
   *Lupus, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** Until dismissed
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The werewolf can
compensate for her vision completely by using her sense
of smell. She can attack invisible creatures normally or
navigate in absolute darkness. Wolf-spirits teach this Gift.
  
**System:** The werewolf fully substitutes her sense of
smell for her vision, enabling her to distinguish identity
and location flawlessly (color and fine details, such as
letters printed on a page, remain beyond her). A Perception
 roll may be required to detect things
which actively obscure their scent.  
#### Scent of the OathBreaker
   *Philodox, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
Oaths
sanctified before a Philodox are a serious matter indeed,
so this Gift grants the judges of the Garou nation the
ability to know when an oath has been broken and to
track down the oathbreaker to correct him personally. A
dog-spirit teaches this Gift.
  
**System:** The Philodox may spend one Gnosis point
to sanctify any oath or promise he personally witnesses,
no matter how formal or informal. The involved parties must be aware they are binding themselves into a contractual oath and the details in which that entails if they are broken.  If at any point in the future one of the individuals sworn to the oath breaks it,
the Philodox immediately becomes aware of this, and all
rolls for the werewolf to track the oathbreaker by scent
drop to DC 5. Also, any rolls the Oathbreaker(s) attempts are made with disadvantage.This benefit lasts until the Philodox next stands in the oathbreaker’s presence.

#### Scent of the True Form
   *Philodox, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 300 ft
  
  **Duration:** 1 hour
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
The
Philodox is able to scent the truth of those she meets,
literally sniffing out an individual’s true form. A vulture spirit
teaches this Gift.
  
**System:** The Garou can smell Kinfolk or a fellow
werewolf automatically; pre-Change werewolves smell
like Kin. In all other cases, the player must roll Perception
A 5-10 will identify a normal human or animal; 11-15 will detect a
vampire, changeling, demon, mummy, or Fera;15+
are needed to sniff out anything else with a CR rating of 20+. Unfamiliar
scents aren’t automatically recognized: A perception roll with advantage is made to determine the creatures true Form, Difficulty is determined by the DM, DC=5 easy, while DC= 15 should be very difficult.  This can see through minor illusions, as well as shapeshifting forms and creatures abilities, such as doppelgangers.

#### Scream of Gaia
   *Get of Fenris, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 50 ft radius
  
  **Duration:** n/a
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
 As the lupus Gift.  The Garou emits
a horrible, ragged scream imbued with Rage and the pain
of Gaia. The force of the scream batters foes and knocks
them off their feet. Storm-spirits teach this Gift.
  
**System:** The player spends a Gnosis point and hostiles in the area rolls
Dex Save. Everyone within a 50-foot radius, except for
the werewolf’s pack is blasted to the ground prone and suffer 8d6 force damage, save for half as a shockwave rips through the area.

#### Seizing the Edge
   *Shadow Lord, Rank 1 Gift*
  
  **Casting Time**  Instantaneous
  
  **Range:** 60 ft
  
  **Duration:** 1 minute
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
Shadow Lords don’t
acknowledge the idea of the draw. If neither competitor
wins, then they both lose. This Gift allows the Garou to
swing the balance, ever so slightly, in her favor. A spirit
servant of Grandfather Thunder teaches this Gift.
  
**System:** Whenever the Shadow Lord is involved in
an opposed roll with another being it can see within 60 ft, the Shadow Lord has rolls with advantage. This Gift’s effects remain in effect for 1 min.
 

  <div class='pageNumber'>63</div>
<div class='footnote'>PART 4 | GIFTS</div>
  \page
#### Sense Balance
  *Philodox, Rank 3 Gift*
  
  **Casting Time**  Concentration, 1 turn
  
  **Range:** 120 ft
  
  **Duration:** 1 hour
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
As the arbitrators
of the Garou Nation, the Philodox have developed an attunement
with the cosmic forces that balance the Tellurian.
The werewolf may sense an overabundance of Wyrm, Wyld, or
Weaver energies in a location. A cat-spirit teaches this Gift.
  
**System:** The player spends a Gnosis point. This Gift makes your eyes glow blue and allows you to see magical auras within 120 feet of you. These magical auras surround magic items and other sources or conduits of magic such as other spellcasters.
You know the location and power of all magical auras within your range of this spell. An aura's power depends on a spell's level or the effect that the magic item produces (the rarer the item, the stronger the aura produced). If an item or creature bearing an aura is within 120 feet of you, you know the school of magic involved in each object and the maximum spell slot level the item or creature can produce.
  
If you focus on an object, you can determine what that object can do as per the identify spell. If you focus on a creature, you can determine if that creature has a spellcasting feature such as a lich or other magical abilities such as a quasit's ability to turn invisible. To do so, you must succeed on an Intelligence (Arcana) skill check with a DC of 10 + the following depending on the object's rarity: +2 for a common item, +4 for an uncommon item, +6 for a rare item, +8 for a very rare item, +10 for a legendary item and +15 for artifacts. For a creature, the DC is equal to 10 + the creature's highest level spell slot or the creature's CR; whichever is higher. Any creature with a CR of less than 1 is treated as having a CR of 0 when determining the DC of the Arcana skill check. 
  
The Philodox must be at peace and without distraction to use this Gift.  
#### Sense Prey
  *Lupus, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 8 hours
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
This Gift lets a werewolf
locate enough prey to feed her pack. In the urban environment,
this tends to guide lupus to prey in parks, sewers,
animal shelters or even zoos, drawing her unfailingly to
the presence of prey animals. Humans and carnivores too
large or dangerous for a lone wolf to regard as prey do not
register as prey animals. A wolf-spirit teaches this Gift.
  
**System:** Any requirement or roll that is needed to hunt for food during the duration is rolled with Advantage.  Effects last for 8 hours. 
```
```

  
#### Sense Silver
  *Metis, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 300ft
  
  **Duration:** 10 minutes
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
To those truly born
Garou, Luna has granted the ability to sense a werewolf’s
greatest weakness. This Gift, taught by Lunes, allows the
metis to detect the presence of silver.
  
**System:** The player rolls Perception + Proficiency Bonus
(difficulty 10). If successful, she can detect the presence
of any silver within 100 yards. A 15 or higher can allow her
to pinpoint the silver’s location.

#### Sense the Unnatural
  *Lupus, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 150 ft
  
  **Duration:** 1 hour
  
  **Gnosis:** n/a
   
  **Rage:**  n/a
  
 The werewolf
can sense any supernatural presence and determine
its approximate strength and type. Supernatural presences
can include magic, spirits, Wyrm taint, ghosts, vampires,
faeries, and any other such unnatural manifestation —
although it won’t pick them out specifically as such. A
werewolf may sense a person plagued by haunting as easily
as a ghost. Any spirit servant of Gaia can teach this Gift.
  
**System:** The target rolls a Charisma Save.  If failed, 
The creature type and a supernatural ability can be determined.
 The sensory input is somewhat vague and subject
to interpretation, though. For instance, a vampire might
smell of clotted blood, fear, corpse-meat or whatever else
the Storyteller finds appropriate.

#### Sense Wyrm
  *Metis, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 100 ft per gnosis point spent
  
  **Duration:** 1 hour
  
  **Gnosis:** Up to the max for your level
   
  **Rage:**  n/a
  
The werewolf can
sense nearby manifestations of the Wyrm. This Gift
involves a mystical sense, not a visual or olfactory image,
although Garou often describe the Wyrm’s spiritual
emanations as a stench. This Gift doesn’t necessarily sense
dedication to the Wyrm, merely contact with its spiritual
essence, which can cling to even blameless souls. Sense
Wyrm requires active concentration; the spiritual sense
it provides doesn’t function passively. The Gift may be
taught by any Gaian spirit.
  
**System:** The Garou can detect any evil, or undead being within 100ft per Gnosis point spent.  If detecting something in the area in a range he cannot see, the DM can call for a tracking roll(with advantage) to follow the scent.
  
 <div class='pageNumber'>64</div>
<div class='footnote'>PART 4 | GIFTS</div>

  \page
#### Serenity
  *Children of Gaia, Rank 4 Gift*
  
  **Casting Time**  Reaction
  
  **Range:** 200 ft
  
  **Duration:** Until dismissed
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Garou can fill a hot
heart with the peace of Gaia, even in the midst of battle.
An avatar of Unicorn teaches this Gift.
  
**System:** The player spends one Gnosis point and can use their reaction to activate this gift. When the Garou is attacked, the gift is activated, but does not prevent any damage received, if any.  The target must pass a wisdom save to attempt to attack the Garou again.  In addition, the target automatically ends any Rage bonuses,cannot frenzy, and cannot spend Rage if applicable. 
  
#### Shadow Cutting
  *Shadow Lord, Rank 4 Gift*
  
  **Casting Time**  Reaction
  
  **Range:** Special
  
  **Duration:** 1 minute
  
  **Gnosis:** 1
   
  **Rage:**  n/a
  
The Shadow
Lord can wound an enemy by striking at his very shadow.
Such attacks are difficult to dodge. This Gift is taught by
a night-spirit.
  
**System:** The character spits into his opponent’s
shadow and the player spends a Gnosis point. For the next minute, the character may strike at his foe’s shadow
to wound him. Only fetish weapons or natural weaponry
serves for such attacks. This Gift ignores any dodge, parry,  or reactions of the target, as the attack isn't being made to the physical body of the creature, but through its own shadow.  Also, the range to successfully hit is doubled by the natural size of the target.  Whereas the natural rule of thumb is within 5 ft of the target.  The Shadow it casts adds to that range.  For mechanical purposes, the Shadow Lord only has to be within 10 ft of a medium sized creature instead of 5.  Large creatures are 15ft, Huge is 20 ft, and Gargantuan is 25 ft of the target to strike within melee range.  Anything smaller than medium sized and the shadow lord must still be within 5 ft for melee range.
  
  Cannot be used in complete darkness where no shadow is cast.  
#### Shadows by the Firelight
  *Galliard, Rank 4 Gift*
  
  **Casting Time**  1 action, concentration during scene
  
  **Range:** 120 ft
  
  **Duration:** Until dispelled
  
  **Gnosis:** 1 per unwilling target(n/a for willing participants)
   
  **Rage:**  n/a

  The
Galliard invokes shadows and dreams to set the stage
for a play in which other werewolves play a part. The
Galliard narrates the tale, and the actors are swept along
in the narrative, willing or no. The Gift is often used at
moots, since it allows many to participate in the retelling
of legends. It is also used as an object lesson for the wayward
and stubborn. An ancestor-spirit teaches this Gift.
  
**System:** To press an unwilling actor into the shadowplay,
the player spends one Gnosis point per target and
Rolls Performance vs Wisdom Spell save. The effects last until the story
ends (one scene), or until the actor is attacked. Willing
participants require no roll or expenditure. By the end, all who participated in the play recieve a 1d4 bonus die which can be stacked with any other inspirational dice as well.

#### Shed
  *Metis, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** n/a
  
  **Gnosis:** n/a
   
  **Rage:**  n/a

The metis can shed a layer of
fur and skin, slipping from an opponent’s grasp or escaping
from bonds with ease. A lizard-spirit or snake-spirit
teaches this Gift.
  
**System:** The player rolls Dexterity check DC 10
 If the roll succeeds, the character loses
a tuft of fur or skin (revealing healthy new hide),
allowing her to slip free of grapples or bonds such as
ropes or chains.
  
#### Shell
  *Metis, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a

Shell places an emotional
and instinctual barrier around the metis, shutting out the
hostility of the world and suppressing his own powerful,
destructive impulses. It is taught by a turtle-spirit.
  
**System:** The player spends one Gnosis. insulating the metis
for a 10 min behind a mystical and psychological barrier,
immunizing him against mind-altering magic of all kinds
for the duration.. However, he cannot gain any
successes on social checks, nor can
he spend Rage points.
 
#### Shield of Rage
  *Ahroun, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes
  
  **Gnosis:** 1
   
  **Rage:**  n/a

Such is the Rage
burning within an Ahroun’s heart that all lesser furies
quail before it. A wolverine-spirit teaches this Gift.
  
**System:** The player spends one Gnosis point. For
For the next 10 minutes, the Garou gets a +1 to their AC.
 
 <div class='pageNumber'>65</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
 \page
#### Sight From Beyond
  *Theurge, Rank 2 Gift*
  
  **Casting Time**  n/a
  
  **Range:** Self
  
  **Duration:** Special
  
  **Gnosis:** n/a
   
  **Rage:**  n/a

This is a Gift of
prophecy. The werewolf becomes an oracle, prone to dreams
and visions which hint at future opportunities, challenges
and threats to come. These visions are always veiled in
symbolism — an impending war against the local vampires
might be presaged by visions of skyscrapers weeping blood
from their upper stories, while a death in the sept might be
heralded by dreams of a chorus of mournful howls rising to
a ghost-pale moon. Owl-spirits teach this Gift.
  
**System:** Visions are entirely under the Storyteller’s
control and are best handled through roleplaying, though
a truly stumped player might ask for a roll to help interpret a particularly puzzling vision.
 
#### Silence the Weaver
  *Lupus, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft
  
  **Duration:** Special
  
  **Gnosis:** n/a
   
  **Rage:**  1

The lupus
releases a shattering howl, destroying all nearby delicate
Mechanical structures that aren't magical.  Anything with gears, or motorized functions that are supported through magical means are affected within 120ft. radius (crossbows, levers, ect)
 A storm-spirit teaches this Gift.
  
**System:** The lupus spends a turn howling. The player
then spends one Rage point and rolls Primary ability modifier + proficiency bonus DC depends on complexity of mechanical function.  (5 simple function, one gear, 15 very complex, multiple gears and functions) On a success within the ranged area, those mechanical devices  are destroyed in a flash of sparks.  
#### Silver Claws
  *Ahroun, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** Special
  
  **Gnosis:** 1
   
  **Rage:**  n/a

 Luna sends her
children to teach this powerful but painful Gift to those
warriors who gain her favor. When invoked, it transforms
the werewolf’s claws into silver.
  
**System:** The player spends 1 Gnosis  to
activate this Gift.  The claws are still considered magical and silvered. The Ahroun suffers searing agony while manifesting these silver claws. Each turn, she gains an
automatic Rage point, while losing a gnosis point and taking 1d6 damage from being contacted with silver.  (unless a gift is active to resist silver damage) and all non-combat difficulties
increase by one because of the distraction. On each turn
that her Rage points exceed her Gnosis score, she has a 50% chance of frenzy. During this frenzy, the Garou can lose control, and attack anyone within range, a d20 is rolled, if it is above 10 he can continue attacking the enemy, if it is below 10 or below, he attacks an ally and has to make wisdom saves at the end of every turn.  The Garou cannot spend Gnosis, but spends any Rage accumulated above his maximum immediately on his first target.The Gift lasts for one minute, unless the
Garou takes a turn to voluntarily end it.(not during a frenzy)

#### Smell of Man
  *Homid, Rank 1 Gift*
  
  **Casting Time**  n/a
  
  **Range:** 30 ft
  
  **Duration:** Permanent

  **Gnosis:** n/a
   
  **Rage:**  n/a

To creatures of the
wild, man’s scent is death. To creatures of the city, it is
authority, comfort, easy meals. This Gift, taught by an
ancestor-spirit, enhances a werewolf’s human scent, infusing
it with spiritual power.
  
** System**:  Non-supernatural wild animals gain disadvantage when
interacting with the Garou, save when defending themselves (non-combat)
or running away, and will be inclined to flee rather than attack if possible. 
In addition domesticated animals recognize the werewolf as a friend, and even trained attack dogs will do no more than wag their tails at the character unless attacked first. 

This Gift’s effects are permanently active.
 
#### Snarl of the Predator
  *Get of Fenris, Rank 2 Gift*
  
  **Casting Time**  bonus action
  
  **Range:** Self
  
  **Duration:** end of next turn

  **Gnosis:** 1
   
  **Rage:**  n/a

The Garou
lets out a feral snarl that terrifies opponents and cows
them into submission. A wolf-spirit teaches this Gift.

**System:**As a bonus action, by spending one Gnosis, the Garou may use his Charisma modifier to deduct any damage, except silver, for every successful attack made against him.  This lasts until the end of his next turn. 
  
 <div class='pageNumber'>66</div>
<div class='footnote'>PART 4 | GIFTS</div>
  \page
#### Song of Heroes
  *Galliard, Rank 3 Gift*
  
  **Casting Time**  10 minutes
  
  **Range:** Self
  
  **Duration:** 8 hours

  **Gnosis:** 2
   
  **Rage:**  n/a

Reciting a tale
of ancient Garou heroism, the Galliard conjures up the
spirit of fallen heroes and infuses those listening with some
portion of their power. An ancestor-spirit teaches this Gift.
  
**System:** This Gift requires the full recitation of a
story of epic heroism, taking at least several minutes. At
the end of the tale, the player spends two Gnosis points
and rolls Performance (difficulty 10). If successful on this roll add two points to a single Ability
score for all listening  This bonus lasts
for 8 hours.

#### Song of Rage
  *Galliard, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft
  
  **Duration:** Until dispelled

  **Gnosis:** n/a
   
  **Rage:**  n/a

This Gift unleashes
the beast in others, forcing werewolves, vampires, and
other such creatures into frenzy and turning humans into
berserkers. A wolverine-spirit teaches this Gift.
  
**System:** A target within 60 ft makes a wisdom save.  If failed, the victim flies
into a violent rage (or frenzy, if naturally prone) attacking anything friend or foe.  The closest one in its line of sight usually.  Spells nor abilities can be used while in this rage.  The effect ends when the target can successfully pass a wisdom save at the end of their turn.
 
#### Song of the Earth Mother
  *Shadow Lord, Rank 2 Gift*
  
  **Casting Time**  10 minutes concentration
  
  **Range:** 300  ft
  
  **Duration:** look back up to 72 hours

  **Gnosis:** 2 
   
  **Rage:**  n/a

This gift
allows the werewolf to sense the presence of 
activity within a broad area. Essentially, the Garou communes
with the earth and listens to what it says. The Gift
is taught by an earth-spirit.
  
**System:** The user spends 10 minutes communing
with the earth, during which time she may take no other
actions. The player then spends two Gnosis points and
rolls Perception DC 10. Success indicates
that the earth tells her about any presence
within an area of 100 yards and/or any events that took place within the area.  In this case, any events that the Shadow Lord can see, is revealed as shadowy figures, and cannot determine specific faces or names.  The Shadow Lord can look back in the timeline of the area as far as 72 hours.
    
#### Song of the Great Beast
  *Lupus, Rank 5 Gift*
  
  **Casting Time**  1 turn, concentration
  
  **Range:** Self
  
  **Duration:** n/a

  **Gnosis:** 5 
   
  **Rage:**  n/a

The Garou
travels to the deep wilderness and lets out a long, mournful
howl. One of the Great Beasts of antiquity answers
the call, appearing in the Realm near the werewolf — a
mighty and savage being that walked the Earth in ages
past. Such creatures include the Willawau (giant owl), the
Sabertooth Tiger, the great Megalodon sharks that swam
the seas eons ago and the mighty Mammoth, who arrives
in herds. Who knows what else the Song might call up?
The Great Beasts possess power in the physical world to
rival that of mighty spirits in the Umbra. Once the ancient
creature arrives, the Garou may make a request of it, but
the Great Beast will fulfill it in its own way, according to
its nature. Using this Gift is risky, but the results can be
truly spectacular. Few spirits know this Gift. It’s said that
the reclusive Mokolé  know which spirits can
teach the Song of the Great Beast … if any survived the
Impergium, and are willing to talk to the Garou, that is.
  
**System:** The player spends 5 Gnosis points 
Describe the assistance you seek, and roll percentile dice.  The Ancient Beast Spirit intervenes.in some way ... If your totem spirit intervenes, you can't use this feature again for 7 days. Traits are left to the Storyteller’s discretion, but should always be impressive.

#### Song of the Siren
  *Galliard, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft
  
  **Duration:** Until dismissed

  **Gnosis:** 1 
   
  **Rage:**  n/a

The Garou’s
song or howl can entrance anyone who hears it. A songbird spirit
teaches this Gift.
  
**System:** The Garou spends 1 gnosis.  Any creature within 60 feet with less than 100 HP is stunned.  Otherwise it has no effect.  Anyone who is stunned can roll a Con save on their next turn to end it.
  
#### Speech of the World
  *Homid, Rank 2 Gift*
  
  **Casting Time**  Instantaneous
  
  **Range:** Self
  
  **Duration:** 10 minutes

  **Gnosis:** n/a
   
  **Rage:**  n/a

This Gift
allows Gaia’s warriors to read and wield the spirit of
speech, bypassing the need to learn different languages
and dialects. The Garou may speak and understand any
language she encounters, though she speaks with an
obvious accent, marking her as an outsider. Speech of the
World doesn’t convey literacy, nor is it an encyclopedia of
cultural information. An ancestor-spirit teaches this Gift.
  
**System:** The player makes an INT check, DC 10. The effect lasts for 10 minutes.   
  
 <div class='pageNumber'>67</div>
<div class='footnote'>PART 4 | GIFTS</div> 
  
  \page
#### Spider’s Song
  *Ragabash, Rank 2 Gift*
  
  **Casting Time**  1 action, concentration
  
  **Range:**300 ft
  
  **Duration:** Until dismissed

  **Gnosis:** 1
   
  **Rage:**  n/a

The Ragabash can
steal messages from the Weaver’s web, plucking them from
the air or eavesdropping as they race through telephone
lines. The Ragabash must be aware that a conversation is
happening to listen in on it (though she doesn’t have to
know who’s on the other end of the line) Spiderand
raven-spirits teach this Gift.
  
**System:** The player spends a Gnosis point. She listens
in on the conversation  within 300 ft and as long as she concentrates on listening, the Ragabash can clearly hear the conversation that normally would be to far to make out.  Automatic success if Ragabash is in a quiet place and there are no obstructions. ( DC 5- very quiet place, where a DC15 would be through multiple walls in a tavern where a bard is playing music very loud.for example)

#### Spirit Drain
  *Theurge, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 120 ft
  
  **Duration:** n/a

  **Gnosis:** n/a
   
  **Rage:**  n/a

The Garou may drain
power from a spirit to feed her own resolve. A rat-spirit
teaches this Gift.
  
**System:** A target within 120 ft takes 3d6 radiant damage on a successful spell attack.  Any damage made to the target also heals the Garou.  In addition, once per short rest,the Garou can  regenerate a Rage point from a successful attack.  
  
#### Spirit Friend
  *Theurge, Rank 4 Gift*
  
  **Casting Time**  1 action, concentration
  
  **Range:** 60 ft
  
  **Duration:** 10 minutes

  **Gnosis:** n/a
   
  **Rage:**  n/a

The werewolf
projects a feeling of tranquility and fellowship that spirits
naturally perceive. Save for the mad or corrupt, spirits
treat the Garou with courtesy and chivalry. This Gift is
taught by a unicorn-spirit.
  
**System:** The Garou produces a glowing Aura that surrounds him in a radius of 60ft. Any ability or skill checks that are based on Charisma are made with advantage when dealing with any non evil creatures that are within range. This effect lasts for 10 minutes and requires concentration, or ends if another gift from the Garou is used that requires Gnosis being spent.  
#### Spirit of the Fray
  *Ahroun, Rank 2 Gift*
  
  **Casting Time**  1 action, concentration
  
  **Range:** Self
  
  **Duration:** Permanent

  **Gnosis:** 1 (optional)
   
  **Rage:**  n/a

 A cat-spirit
grants the Ahroun the Gift of blinding speed and lightning
reflexes, permitting her to strike before any foe.
  
**System:** Once the Ahroun learns this Gift, its effects
are permanent. She adds 10 to all her initiative rolls, and
if she chooses, may spend a Gnosis point to add another
10 to an initiative roll *(such an expenditure prevents
spending Rage for extra actions for 1 min after combat starts however).*
 
#### Spirit Snare
  *Theurge, Rank 1 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 120 ft
  
  **Duration:** n/a

  **Gnosis:** 1 
   
  **Rage:**  n/a

The Theurge casts out
an invisible, mystic net which entangles hostile spirits,
confounding them with a mixture of magical force and
long-broken but still potent Gaian law. An owl-spirit
teaches this Gift.
  
**System:** The player spends one Gnosis point and rolls
Their primary ability score + Proficiency bonus as an attack directed
at a target within 120 feet,. 3d6 force damage is rolled and any wisdom saves rolled by the target are at disadvantage until the end of the players next turn.
Multiple applications of this Gift don’t stack.

#### Spirit Speech
  *Theurge, Rank 1 Gift*
  
  **Casting Time**  Instantaneous
  
  **Range:** Self
  
  **Duration:** n/a

  **Gnosis:** n/a
   
  **Rage:**  n/a

This Gift bestows
understanding of the language of the spirit world, permitting
the Garou to clearly understand and speak with any
spirit he encounters. The Gift doesn’t influence spirits’
attitudes toward the werewolf in any way, nor ensure that
they have any desire to communicate with him. Any
spirit can teach it.
  
**System:** This Gift’s effects are permanent.
  

 <div class='pageNumber'>68</div>
<div class='footnote'>PART 4 | GIFTS</div>
  
  \page
#### Spirit Ward
  *Homid, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** placed within 20 ft
  
  **Duration:** 8 hours

  **Gnosis:** 2
   
  **Rage:**  n/a

This Gift allows a
werewolf to protect herself from spirits by performing a
quick warding rite. The werewolf traces an invisible pictogram
in the air that creates a hard to detect magical Glyph that also 
frightens and unnerves any nearby
spirits, and which travels with the Garou for as long as it
persists. An ancestor-spirit teaches this Gift.
  
**System:** Requires a successful (Investigation) check against your spell save DC to be found.The player spends two Gnosis points. Each creature that wasn't withina 20 ft range while the glyph was first created that steps within the radius afterwards in the aura must make a Dexterity saving throw.  (everyone else is bound the immunity to the damage)When triggered, the glyph erupts with magical energy in a 20-foot-radius Sphere centered on the glyph. The Sphere spreads around corners. A creature takes 6d10 acid, cold, fire, lightning, or thunder damage on a failed saving throw (your choice when you create the glyph), or half as much damage on a successful one.rolls 
Gift lasts for 8 hrs.

#### Staredown
  *Homid, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft
  
  **Duration:** Until dismissed

  **Gnosis:** n/a
   
  **Rage:**  n/a

 Rage burns in a werewolf’s
eyes, striking fear into the hearts of mortals and
animals, causing them to flee for their lives. Used against
another werewolf, the target will freeze in place rather
than run. A ram- or snake-spirit teaches this Gift.
  
**System:**  This Gift affects only one target at a time.
The victim  must succeed on a Wisdom saving throw or drop whatever it is holding and become frightened for the duration. While frightened by this spell, a creature must take the Dash action and move away from you by the safest available route on each of its turns, unless there is nowhere to move. If the creature ends its turn in a location where it doesn’t have line of sight to you, the creature can make a Wisdom saving throw. On a successful save, the spell ends for that creature. Garou and classes with Rage do not flee but may not attack while the Gift is in use. 

#### Stoking Fury’s Furnace
  *Ahroun, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** Permanent

  **Gnosis:** n/a
   
  **Rage:**  n/a

This Gift
allows the Garou to husband his Rage, keeping it burning
for as long as Gaia’s enemies remain to be defeated. A
wolverine-spirit teaches it.
  
**System:** This Gift’s effects are permanent. The werewolf
regains one Rage point during any turn in which he
takes damage. This Rage does not cause a frenzy check,
though other sources will induce checks as usual. Additionally,
the player can spend one Rage point per turn
without losing any temporary Rage. If multiple Rage points
are spent during any turn, however, all are marked off.  Temporary rage points are lost if not used by the next short or long rest.  
#### Strength of Gaia
  *Lupus, Rank 3 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 10 minutes

  **Gnosis:** n/a
   
  **Rage:**  1

The Goddess
blesses the lupus with the fullness of his might when he
wears the most natural of his skins. While wearing lupus
form, the Garou enjoys the full might of Crinos. A wolf spirit
teaches this Gift.
  
**System:** The player spends one Rage point. His Lupus
form base strength increases by four, rather than the
normal one, for 10 min.

#### Strength of Purpose
  *Philodox, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** n/a

  **Gnosis:** n/a
   
  **Rage:**  n/a

Philodox use
this Gift to fortify themselves in the face of the Apocalypse,
turning hot passion and burning Rage into cold, steely
resolve. A wolf-spirit teaches this Gift.
  
**System:** Once per short rest ,1d10 and recover that amount of Gnosis.  
#### Strength of Will
  *Ahroun, Rank 5 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 100 ft
  
  **Duration:** 1d6 rounds

  **Gnosis:** 1 per target(must spend one for yourself, for max 4)
   
  **Rage:**  n/a

 A werewolf with
this Gift is a pillar of indomitable will. He can share this
terrifying strength with others as well, leading them through
the gates of Malfeas without a moment’s fear or hesitation.
A wolf-spirit or an Incarna avatar teaches this Gift.
  
**System:** The player spends 1 Gnosis per target and chooses up to 3 other willing allies within 100ft.. Each ally when rolling a to save and fails, the garou can roll his save to have her succeed instead.  However if both fail, they both are affected. In addition, whenever any of the 4 allies takes direct damage, it is divided equally, if it cant be divided equally, any left over damage goes to the Garou.  Area of effect spells or abilities do not apply to this.  It must be direct damage to a single target.  This lasts for 1d6 rounds.  Can only be used once every short rest.  
  
 <div class='pageNumber'>69</div>
<div class='footnote'>PART 4 | GIFTS</div>


  \page
#### Strike the Air
  *Children of Gaia, Rank 4 Gift*
  
  **Casting Time**  1 action
  
  **Range:** 100 ft
  
  **Duration:** 1 minute

  **Gnosis:** 1 per target
   
  **Rage:**  n/a

The Child becomes
the ultimate example of passive resistance. She is unable
to attack an opponent, but is also unable to be hit, allowing
her opponent to exhaust herself in an intricate dance
of frustrated blows. A mongoose-spirit teaches this Gift.
  
**System:** The player spends one Gnosis point and gains a +4 to AC.  Must be using the Dodge action with this gift, the attacker has disadvantage when attacking, and the Garou also gains advantage to any Dex saving throws.  The effect last for one minute, unless the Garou falls unconscious, dies, uses an attack action on the same target, or chooses to end it sooner.  This Gift will work on multiple opponents, but the player must spend an additional Gnosis point for each new attacker. 
  
#### Taking the Forgotten
  *Ragabash, Rank 2 Gift*
  
  **Casting Time**  1 action
  
  **Range:** Touch
  
  **Duration:** Special

  **Gnosis:** n/a
   
  **Rage:**  n/a

A Ragabash
with this Gift can steal something from a target and make
his victim forget that she ever possessed the stolen item.
A mouse-spirit teaches this Gift.
  
**System:** With this Gift, a successful Sleight of Hand. the target makes a WIS save, If failed the victim would never remember even seeing the Ragabash or any encounter within the past hour of the pick pocket.  If the victim passes the Save, the pick pocket was still successful, but would recall any interactions with the Ragabash if applicable. The victim would not realize this Gift was used on him, or alert his suspicions further in any way however. 
  
#### Talons of the Falcon
  *Silver Fang   , Rank 3  Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 1 minute

  **Gnosis:** 1
   
  **Rage:**  n/a
  
  The Silver
Fang’s claws transform into impaling weapons, allowing
her to cut muscle, bone, and sinew as though they were
paper. A falcon-spirit teaches this Gift.

**System:** The player spends one Gnosis point and
makes a Dexterity + Strength modifiers to her claw attack and damage rolls for the next minute.   
#### Terror of the Dire Wolf
  *Lupus   , Rank 4  Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft
  
  **Duration:** Until dismissed

  **Gnosis:** 
   
  **Rage:**  1

  Wolves
haunt the ancestral nightmares of humanity, and of those
monsters that were once human. The werewolf lets out
a fierce snarl that triggers primordial terror in opponents
and drowns them in the Delirium. A wolf-spirit teaches
this Gift.

**System:** The player spends a point of Rage and target or targets in an area of 60 ft
 roll Wisdom Save. If successful, the werewolf invokes the
full effect of the Delirium on any human, formerly-human,
or partly-human creature who can see her — including
those normally immune to the Delirium, such as mages
and vampires. Only other werewolves are immune.
It may be used in any form.
  
#### The Living Wood
  *Children of Gaia   , Rank 5  Gift*
  
  **Casting Time** 1 action 
  
  **Range:** 60 ft
  
  **Duration:** Until dismissed

  **Gnosis:** 1
   
  **Rage:**  n/a

  The Child of
Gaia calls upon the powers of the forest to rise and aid
her. Nearby trees begin to move and attempt to protect
the Garou. Limbs and vines will restrain, block and
even fight those attempting to harm her. A Glade Child
teaches this Gift.

  **System:** The player spends one Gnosis point and
rolls Survival.  The Garou can summon Treants to aid her.  The amount of treants is determined by the roll.  
* 1-5 = 1 treant
* 6-10= 2 treants
* 11-15= 3 treants
* 16-20= 4 treants
  
The Treants are under the Garou’s control until dismissed or slain.  They do not have the ability to produce more treants themselves however.
  
#### Thousand Forms
  *Ragabash   , Rank 5  Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** Until long rest

  **Gnosis:** 1 - 2
   
  **Rage:**  

  The werewolf
with this Gift may change herself into any animal between
the sizes of a small bird and a bison. The Garou gains
all the special capabilities (flight, gills, poison, sensory
abilities, etc.) of the animal she mimics. She may not
take the form of Wyrm-beasts (not that she would wish
to!), but with some extra effort she may take the form of
mystical beasts (such as a griffon or unicorn), provided
the beast remains within the usual size limitations of the
Gift. Wyld-spirits teach this Gift.
  
**System:** The player spends a point of Gnosis and allows the 
character to assume the shape of any normal
Animal.  Until the next Long rest, he may make additional
transformation rolls without spending additional
Gnosis, provided he only takes the shape of normal animals.
To allow the character to take on a mythical form,
the player must spend an additional point of Gnosis 
  
 
  <div class='pageNumber'>70</div>
<div class='footnote'>PART 4 | GIFTS</div> 
  \page
#### Totem Gift
  *Metis   , Rank 5  Gift*
  
  **Casting Time** 10 minutes 
  
  **Range:** 30 ft
  
  **Duration:** Special

  **Gnosis:** 1
   
  **Rage:**  n/a

  Metis are Garou from
the moment of their birth, and their ties to the spirit that
guides their tribe run deep. The metis may plead with her
tribal totem for power, with effects varying from tribe to
tribe. Rat might send a swarm of rodents to attack the
werewolf’s enemies, while Grandfather Thunder might
send down the lightning to strike aside obstacles and opponents.
The potential of this Gift depends on the favor
of the totem, and may extend into the miraculous. Only
the tribal totem teaches this Gift.
  
**System:** The player spends one Gnosis point and
rolls Divine Intervention
Describe the assistance you seek, and roll percentile dice. If you roll a number equal to or lower than your level, your Totem Spirit intervenes. ... If your totem spirit intervenes, you can't use this feature again for 7 days. Otherwise, you can use it again after you finish a Long Rest.
  
#### Troll Skin
  *Get of Fenris   , Rank 2  Gift*
  
  **Casting Time**  1 action
  
  **Range:** Touch
  
  **Duration:** 1 minute

  **Gnosis:** 1
   
  **Rage:**  n/a

  The Fenrir draws on the
power of the earth for protection. Her skin grows tough
and thick, covered with stony knots of hard, armored
flesh. An earth elemental teaches this Gift.
  
**System:** The player spends one Gnosis point and gains resistance to all non magical attacks. This effect lasts for 1 minute. 
  
#### True Fear
  *Ahroun   , Rank 2  Gift*
  
  **Casting Time**  1 action
  
  **Range:** 20 ft cone
  
  **Duration:** end of next turn

  **Gnosis:** n/a
   
  **Rage:** n/a 

  The werewolf displays
his full, terrifying might — baring teeth or claws, howling,
or simply looming ominously over a foe. Terror strikes one
foe into quiescence. Spirits of fear teach this Gift.
  
**System:** Any Targets within 20 ft cone in front of the Garou, makes a Wisdom save.  If they fail they are frightened until the end of your next turn. You can use an action to extend the effect. Effect ends if creatures get out of line of sight or 60 feet away. If creature makes the save they are immune for 24 hours.   
#### Two Tongues
  *Fianna   , Rank 1  Gift*
  
  **Casting Time**  Instantaneous
  
  **Range:** 30 ft
  
  **Duration:** 8 hours

  **Gnosis:** n/a
   
  **Rage:**  n/a

  The glib words and
clever schemes of the Fianna are wasted on a single mark.
This Gift teaches the werewolf to talk out of both sides of
her face, literally carrying on two conversations simultaneously,
and to decide who hears what. An ancestor-spirit
teaches this Gift.
  
**System:**  The Fianna may simultaneously carry
on two conversations at the same time, which need have
no relation to one another. She decides which listeners
hear which version of the words she’s speaking. Anyone
suspecting something odd about the Fianna’s behavior
must roll Perception DC Garou’s Charisma Score to detect
the Garou’s other conversation and to understand what
she’s saying there.  This effect can last up to 8 hours, or until the Fianna chooses to end it.
   
#### Ultimate Argument of Logic
  *Theurge   , Rank 5  Gift*
  
  **Casting Time** 1 action  
  
  **Range:** 30 ft
  
  **Duration:** Special

  **Gnosis:** n/a
   
  **Rage:**  n/a

  Those
who speak with the Theurge leave convinced of some fact
they might otherwise have disbelieved. If successful, the
Garou can cause the target to believe implicitly in one
aspect of existence (true or false) — that the Earth is the
center of the universe, that there is such a thing as a spirit
world, or that cities are unnatural affronts to nature, for
example. A coyote-spirit teaches this Gift.
  
**System:** The Garou rolls a Persuasion vs the targets Insight.  If the Garou wins, he is convinced that what the Garou says is at least believable, as long as it doesn't go against anything in the targets moral code.(Murder is Good, for example), if the Garou’s score is 5 or higher than the target’s score, the target makes a Wisdom Save.  If failed, then even the morals that the target holds on to can be changed.  Can be dispelled.  
  
#### Umbral Camouflage
  *Theurge   , Rank 3  Gift*
  
  **Casting Time**  1 action	
  
  **Range:** Self
  
  **Duration:** 10 minutes

  **Gnosis:** 1
   
  **Rage:**  

  Although
perfectly visible to all others, this Gift renders the werewolf
undetectable to spirits. A wind-spirit teaches this Gift.
  
**System:** The player spends one Gnosis point, and for
10 minutes, she is completely invisible 
While not in the material realm. She may move about as normal but cannot
make any attack actions without disrupting the Gift.  Not effective against creatures with true seeing, or that can see invisible however.

 <div class='pageNumber'>71</div>
<div class='footnote'>PART 4 | GIFTS</div>   

  \page
#### Umbral Dodge
  *Ragabash   , Rank 4  Gift*
  
  **Casting Time**  reaction
  
  **Range:** touch
  
  **Duration:** Special

  **Gnosis:** n/a
   
  **Rage:**  n/a

  The Ragabash finds
that the best way to deal with an enemy is to send him far
away — perhaps to a place where he’ll learn the folly of
his ways. She may tear open a hole in the Gauntlet while
dodging an enemy’s attack, sending them to the land of
spirits. A trapdoor spider-spirit teaches this Gift.
  
**System:** As a reaction, if the target misses any attack made against the Garou, he is able to use the attackers momentum against himself, and cause him to rip through the Gauntlet into the Umbra.  The attacker can make a dex save to stop himself.  Otherwise he is trapped in the Umbra for 1d4+ Garou’s Proficiency bonus rounds. The Gnosis point can be spent after the target rolls his save to activate keeping him there.  (or into the physical world if this Gift
is used in the Penumbra).
  
#### Umbral Tether
  *Theurge   , Rank 1  Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 1 day 

  **Gnosis:** 1/day
   
  **Rage:**  n/a

  The Umbra is a
shifting world where logic doesn’t always apply and losing
one’s way is easy. Theurges ensure they can always
find their way back to the point where they entered the
Umbra with this Gift, which creates a silvery “umbilical
cord” connecting the Garou to the point where they last
crossed the Gauntlet. Only the werewolf who creates the
tether can see it. This Gift is taught by a spider-spirit.
  
**System:** No roll is needed to create the thread.
However, after each full day the character spends in the
Umbra, a point of Gnosis must be spent to maintain the
cord; otherwise, it slowly corrodes from the point of entry
and toward the Garou.
  
#### Uncaught Since the Primal Moon
  *Children of Gaia   , Rank 4  Gift*
  
  **Casting Time**  bonus action
  
  **Range:** Self
  
  **Duration:** 1d4 rounds

  **Gnosis:** 1
   
  **Rage:**  n/a

  This Gift grants Unicorn’s perfect speed to the werewolf,
allowing her to outrun virtually any pursuer. An avatar
of Unicorn teaches this Gift.
  
**System:** The Garou doubles her base speed for 1d4 rounds, and does not provoke attacks of opportunity.  The Garou can still use an attack action in the same turn, unless using dash, which in turn, doubles twice the effect of this Gift, but cannot use an attack action.  The player spends a Gnosis point to activate this gift.  
```
```

  
#### Under the Gun
  *   , Rank   Gift*
  
  **Casting Time**  bonus action
  
  **Range:** Touch
  
  **Duration:** Special

  **Gnosis:** 1
   
  **Rage:**  n/a

  The Shadow
Lord lays a curse on her foe, ensuring certain death by
bullets. While the curse is in effect, bullets (as well as
arrows, hurled knives, and any other missile weapons)
are strangely attracted to the target. Although this Gift
is useful in battle, most Shadow Lords prefer to use it
secretly on a chosen foe before a fight begins, ensuring an
“unfortunate accident.” A raven-spirit teaches this Gift.
  
**System:** The Shadow Lord touches the intended target
with her fingertips. On a successful attack in which the Garou can touch the creature, the Garou can choose to spend a Gnosis point to inflict an extra 4d6 points of necrotic damage, in addition, it will  curse the target to where all ranged attacks have advantage against the target. The target must succeed with a wisdom save to ignore this curse. 
  
#### Unicorn’s Arsenal
  *Children of Gaia   , Rank 2  Gift*
  
  **Casting Time** bonus action  
  
  **Range:** Touch
  
  **Duration:** Until dispelled

  **Gnosis:** 1
   
  **Rage:**  n/a

 The werewolf’s
claws and fangs become dazzling and pearlescent, shining 
with an inner multihued glory. Those wounded by
these natural weapons lose the will to fight. An avatar of
Unicorn teaches this Gift.
  
**System:** The player spends one Gnosis point to initiate
the transformation. If the target is hit with any of the Garou’s natural weapons, it must make a Con Save, or lose the ability to speak, and suffer disadvantage an its attacks rolls.  The effects last until the target can succeed his Con Save.  This status effect can also be removed by Remove Curse, and does not apply to any creature immune to curses.
   
  <div class='pageNumber'>72</div>
<div class='footnote'>PART 4 | GIFTS</div>  
  
  \page
#### Unity of the Pack
  *Silver Fang   , Rank 2  Gift*
  
  **Casting Time**  1 action
  
  **Range:** 30 ft radius
  
  **Duration:** Until missed attempt

  **Gnosis:** n/a
   
  **Rage:**  n/a

 It is only natural
for those guided by canny leaders to excel. This Gift
allows the Silver Fang’s pack to enjoy the benefits of her
unifying aura, making them deadlier warriors against the
Wyrm’s minions. A wolf-spirit teaches this Gift.
  
**System:** Whenever the Silver Fang is present, all
members of her pack within 30 ft(including herself) have a chance to gain additional damage.  The effect gains momentum by each successful attack that is made without error until the end of the Silver Fang’s next turn or someone misses their attack before the Silver Fang's turn is up.  The first successful attacker gains +1 die to their damage roll, followed by the next successful attacker gaining +2 dice, followed by +3, and so on and so forth. If someone in the party of the Silver Fang has multiple attacks, the effects still apply as if he were the next attacker.  So he could gain a +2 dice on damage for his first attack, and then plus +3 dice added to damage on his second.  The effect ends when someone misses an attack, even if an ally had multiple attacks.. The Silver Fang cannot
benefit from this Gift when she is alone.
   
#### Unstoppable Warrior
  *Ahroun   , Rank 5  Gift*
  
  **Casting Time** 1 action 
  
  **Range:** Self
  
  **Duration:** 1 minute

  **Gnosis:** n/a
   
  **Rage:**  1

  The werewolf
with this potent Gift may shrug off even flames and the
claws of his own kind. A warrior Incarna teaches this Gift.
  
**System:** The Garou heals for 1d10 + current level a round.  Costs one rage point, lasts for 1 minute.  
  
#### Venom Blood
  *Get of Fenris   , Rank 3  Gift*
  
  **Casting Time** 1 action 
  
  **Range:** Self
  
  **Duration:** 1 minute

  **Gnosis:** n/a
   
  **Rage:**  1

  The werewolf may
change her blood into a black, acidic bile that poisons
anyone unlucky enough to come into contact with it. A
snake- or spider-spirit teaches this Gift.
  
**System:** The player spends one Rage point and coats its claws with its poisoned blood.  Any attack made with its claws, the target must make a Dex Save DC 19 or take 12d6 poison damage.  Half damage on a successful save.  The effect lasts for 1 minute or the next successful claw attack, whichever comes first.  Naturally, any attack made against the Garou during this minute that may be exposed to its blood, as in a bite, suffers the same effects.  
```
```


  
#### Visage of Fenris
  *Get of Fenris   , Rank 1  Gift*
  
  **Casting Time**  1 action
  
  **Range:** Self
  
  **Duration:** 1 attack per gnosis spent

  **Gnosis:** 1 - max available for your level
   
  **Rage:**  n/a

 The Get appears
larger and more fearsome, commanding respect from peers
and cowing his foes. A wolf- or toad-spirit teaches this Gift.
  
**System:** The Garou spends 1 Gnosis and can add his Charisma Modifier along with his normal modifiers to his damage roll on his next successful attack.  This duration can be increased to multiple attacks per Gnosis spent.  
#### Weak Arm
  *Philodox   , Rank 3  Gift*
  
  **Casting Time**  1 turn, concentration
  
  **Range:** Self
  
  **Duration:** Special

  **Gnosis:** n/a
   
  **Rage:**  n/a

 By watching an opponent’s
fighting style, the Philodox can quickly evaluate
his strengths and weaknesses. Snake- and wind-spirits
teach this Gift.
  
**System:** The player rolls Perception + Proficiency DC 12, . Each number greater than 13 can represent a +1 to hit, an extra damage die to damage, or split anyway to both on the next successful attack. For instance, a Philodox who rolls a 16 can get a +3 bonus to hit on top of her other modifiers, or a extra 3d8 damage applied to her sword attack(if d8 is the damage die), or possibly a +1 to hit, and a 2d8 bonus to damage. — whatever
combination suits her. However, the distribution of dice
cannot be changed once the Gift has been activated. This
Gift can be used against a given foe only once per scene,
and its benefits are lost at the end of the scene. A full turn
of concentration is necessary to use this Gift.
   

  <div class='pageNumber'>73</div>
<div class='footnote'>PART 4 | GIFTS</div> 
  \page
#### Web Walker
  *Theurge   , Rank 3  Gift*
  
  **Casting Time**  1 action
  
  **Range:** 30 ft
  
  **Duration:** Until Dispelled

  **Gnosis:** 1
   
  **Rage:**  n/a

 The Garou may
travel on the Pattern Web through the Umbra without
physical difficulty, and without attracting the unfriendly
attention of Weaver-spirits in the area. Any Weaver-spirit
can teach this Gift.
  
**System:** The player spends one Gnosis point. This enables the
Garou (and her pack, so long as they stick close to her)
to travel through the Umbra across the Pattern Web as
though she were on a moon bridge. Whether the Web’s
strands go where the Garou wants to travel is another
matter entirely.  While not in the Material web, The Garou and anyone within 30ft she choses remains on this undetermined path but is immune to any damage, but also cant harm anything it sees.  All conditions apply while traveling on the web, as it would on the material realm.  Hunger, rest, ect are all possible.  Attempting to get off in a different location from where the Garou entered requires a Constitution save.  DC 10  Success means you remove yourself on the web into the reality of whatever Realm your in.  Everyone including the Garou is considered paralyzed for 1 round, as ripping through the fabrics of reality between the reallms takes a toll.  Failure on the Con Save means you are paralyzed for one round and also take 10d6 force damage as well.
   
#### Whelp Body
  *Ragabash   , Rank 4  Gift*
  
  **Casting Time**  1 action
  
  **Range:** 60 ft
  
  **Duration:** 3 rounds

  **Gnosis:** 1
   
  **Rage:**  n/a

The Garou delivers a
devastating curse upon a foe’s body, causing it to weaken
or palsy. Many consider the use of this Gift upon a foe
to constitute a declaration of eternal enmity. Pain- and
disease-spirits teach this Gift.
  
**System:** The player spends one Gnosis point Resisted by a Constitution Save by the target. IF Failed the target takes 8d10 necrotic damage + Level.  Save for half.  
Additionally on a failed save, it receives one level of exhaustion, for the next 3 rounds, or until a successful Con Save is rolled, whichever comes first. This Gift may
be used only once ever against a given opponent.
    
#### Whisper Catching
  *Shadow Lord   , Rank 1  Gift*
  
  **Casting Time**  1 action
  
  **Range:** 200 ft
  
  **Duration:** 4 hours

  **Gnosis:** 1
   
  **Rage:**  n/a

  What good
purpose could there be to keep secrets from Gaia’s protectors?
This Gift allows the werewolf to supernaturally
eavesdrop on whispered conversations—what she does
with the information learned is, of course, up to her own
conscience. A crow- or bat-spirit teaches this Gift.
  
**System:** The player spends a point of Gnosis.  For the next 4 hours, all whispers within 200 feet are
Fully audible by the Shadow Lord as though they had been spoken clearly just next to her.
  
#### Wind Claws
  *Ahroun   , Rank 3  Gift*
  
  **Casting Time** bonus action 
  
  **Range:** Self
  
  **Duration:** till end of turn

  **Gnosis:** n/a
   
  **Rage:**  1

  The Ahroun’s
claws and fangs pass through the flimsy protections of
their enemies as though they were but air and hope. An
air elemental teaches this Gift.
  
**System:** The player spends one Rage point. For
the rest of the turn, all of the Ahroun’s natural attacks
completely ignore any armor (mundane or magical) that
targets might be wearing; Does not affect creatures with natural armor.
  
#### Wither Limb
  *Metis   , Rank 4  Gift*
  
  **Casting Time** 1 action  
  
  **Range:** 60 ft
  
  **Duration:** Until dismissed

  **Gnosis:** 1
   
  **Rage:**  n/a

  With a snarl and a
baleful stare, the werewolf ruins an opponent’s limb: bones
twist, muscles wither, flesh desiccates. Creatures with regenerative
capabilities will recover after one scene; all others
are permanently crippled. Venomous spirits teach this Gift.
  
**System:** The player spends a Gnosis point and rolls Primary ability modifier + Proficiency bonus vs target AC. The victim has disadvantage to all dex abilities, checks, 
and saving throws, and speed is now halved.  
#### Wrath of Gaia
  *Silver Fang    , Rank 3  Gift*
  
  **Casting Time**  1 action
  
  **Range:** 30 ft
  
  **Duration:** 1 minute

  **Gnosis:** 1
   
  **Rage:**  n/a

  The werewolf
shows himself in full, terrible glory as Gaia’s chosen
warrior. His splendor overwhelms minions of the Wyrm,
driving them before him in terror. An avatar of Gaia
herself teaches this Gift.
  
**System:** The player spends a Gnosis point. Any minions of the Undead who
look upon the Garou within 30 ft  must
either make a Wisdom Save or flee in terror for the next minute.  Any damage done to those affected before the minute is over, ends the effect of this Gift.

  

 <div class='pageNumber'>74</div>
<div class='footnote'>PART 4 | GIFTS</div>