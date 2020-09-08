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

# Rest and Recuperation
Tired, sore, hungry, thirsty, and aching all over, a weary adventurer enters a town in search of good food, a warm bed, and a roof over their head. Taking the time to relax, refresh, and recharge — not just physically, but emotionally — is important for anyone leading such a demanding lifestyle as an adventurer.

In this document are rules for rewards when taking the time and spending the money to exercise self-care in between adventures. To gain any of these benefits, you must be in a safe and comfortable environment, such as a home or tavern, in a city or town. You can benefit from any number of these benefits at once.

## A Delicious Hot Meal
When you spend at least 1 hour enjoying a delicious hot meal, prepared fresh by a skilled worker, you are filled with energy, preparing you for any physical challenges ahead of you. Most anything you buy at a tavern or inn will do, as will a home-cooked meal prepared by a loved one or a hospitable host. You can only benefit from this feature once per day. You gain the following benefits:

You gain temporary hit points equal to a third of your level (rounded up).
For the next 24 hours, you are immune to gaining additional levels of exhaustion caused by non-magical means, such as a lack of food or shelter.
### A Big, Hearty Meal
At the DM's discretion, you may gain additional benefits for more luxurious meals.

Spending big can earn you a high-quality meal prepared by an expert chef in an upper-class establishment. You may also be given a big, hearty meal by a noble or royalty for a special occasion. Once per 7 days, you can gain the following additional benefits:

You gain temporary hit points equal to half your level (rounded up).
You regain hit points equal to 1 Hit Die plus your Constitution modifier (minimum of 1). The Hit Die is not spent.
For the next 24 hours, you have advantage on Strength checks.
### A Feast Fit for a King
Attending a banquet in the hall of a king is a once-in-a-lifetime experience for all but the most privileged and celebrated. Such a feast invites you to eat as much of the best food in the world as you can muster. Once per 30 days, you can gain the following additional benefits:

You gain temporary hit points equal to your level.
For the next 24 hours, your hit point maximum increases by an amount equal to half your level (rounded up).
You regain all your hit points.

## A Warm Bed
When you sleep in a warm bed, you rest more deeply and peacefully than normal, preparing you more than ever for the day ahead of you. Any bed with a pillow, mattress, and blanket will do; anything is better than a bedroll and a tent. Once per day, you can gain the following benefits:

If you would reduce your exhaustion level as part of the rest, you reduce your exhaustion level by twice as much as you normally would.
For each Hit Dice you spend as part of the rest, you can roll twice and use the higher of the two.

```
```

### An Extra Soft Bed
At the DM's discretion, softer and more luxurious beds can be found in upper-class establishments and the houses of nobles, and offer even greater rests than regular beds. Once per 7 days, you gain the following additional benefit.

For the next 24 hours, you have advantage on Dexterity checks, including initiative checks.
## A Soothing Bath
When you spend at least 1 hour enjoying a hot bath in a bath house or hot springs, your aching is soothed and your body naturally heals itself. You can also gain this benefit from spa treatments and massages from skilled workers. You gain the following benefits:

Your exhaustion level is reduced by 1 if possible.
You regain hit points equal to the highest possible roll of 1 Hie Die plus your Constitution modifier. The Hit Die is not spent.
For the next 24 hours, your speed increases by 5 feet and your carrying capacity increases by 20%.
At the DM's discretion, this duration may be longer for particularly relaxing or refreshing experiences, to a maximum of 7 days. Once you benefit from this feature, you can't benefit from it again for 6 days plus the duration of the effect.

## A Companion's Embrace
When you spend the night with another person in physical intimacy, whether they are a loved one or hired company, you are emotionally bolstered, and gain an increased level of confidence and self-appreciation. You gain the following benefit.

For the next 24 hours, you have advantage on Charisma checks and any saving throws against being frightened or charmed.
At the DM's discretion, this duration may be longer for particularly romantic or emotionally significant experiences, to a maximum of 7 days. Once you benefit from this feature, you can't benefit from it again for 6 days plus the duration of the effect.