<style>
.phb{
    width : 210mm;
    height : 296.8mm;
    padding: 6mm 9mm 10mm 10mm;
    /*padding-bottom: 8mm;*/
}
 .phb {
  font-family: Mentor, "Palatino Linotype", serif;
  font-size: 9.5pt;
 }
 
.smaller {
    font-size: 7pt;
    font-style: italic;
}

 .phb h1+p::first-letter {
  float:none;
  font-family:Cambria;
  font-size:16pt;
  color:#000;
  line-height:1.3em;
  font-weight:normal;
 }
 .phb h4, .phb h3, .phb h2, .phb h1{
  font-family: Ravenna;
  color: #000;
  font-weight: normal;
 }
 .phb h1{
  font-size:20pt;
  color:white;
  padding-top:6mm;
  padding-bottom:5px;
  padding-left:10px;
  padding-right:10px;
  background-image:url("https://drive.google.com/uc?id=1zV1flgB_7tulr6XMymdopd6yzMNsabpl");
  background-repeat:no-repeat;
  margin-top:-2mm;
  margin-left:-2mm;
  margin-right:-2mm;
 }
 .phb h2{font-size:21,84pt;}
 .phb h3{font-size:18pt; border-bottom:1pt solid #000}
 .phb h4{font-size:14,88pt;}
 .phb h5{font-family: Calibri;color:#000;font-size: 12pt;font-weight: normal;}
/* Shaded Lines */
 .phb .shaded {
   background: linear-gradient(to right, gainsboro , white);
   text-indent: -1em;
   margin-left: 1em;
 }
/* Tables */
 .phb table{font-family: Calibri;font-size: 9.84pt;}
 .phb table tbody tr:nth-child(odd){background-color:#f2f2f2;}/*change backing of rows*/
/* Class Table */  
 .phb .classTable{border-image-source: none;border: none;}
 .phb .classTable h5{font-family: Calibri;font-weight: bold;}
 .phb .classTable table tbody tr:nth-child(odd){background-color:#FFF;}
/* Description block */
 .phb .descriptive {
  margin-left:2em;
  background: linear-gradient(to right, gainsboro, white);
  background-origin: content-box;
  border: gainsboro;
  font-family: "Trebuchet MS";
 }
 .phb .descriptive p{font-size:9pt;padding-left:2em;text-indent:-1em}
 .phb .descriptive em{font-family:"Trebuchet MS";}
 .phb .descriptive strong{font-family: "Trebuchet MS";}
/* Power */
 .phb .power {
     font-family: "Trebuchet MS";
     padding-left:2em;
     
 }
 .phb .power em{font-family:"Trebuchet MS"};
 .phb .power strong{font-family: "Trebuchet MS";}
/* Note */
 .phb blockquote{font-family: Calibri;font-size:
 9.84pt;background-color:#e6e6e6;border-width:5px;border-image-outset:5px 0px; box-shadow:0px 1px 5px;}/* Stat Block */
 .phb hr+section blockquote{background: white;border: 3px solid #e6e6e6;box-shadow: none;}
 .phb hr+section blockquote h3{font-family:Calibri;border-bottom:1px solid #000;}
 .phb hr+section blockquote hr+ul{color: #000;}
 .phb hr+section blockquote table{color: #000;}
 .phb hr+section blockquote hr{background-image: url(https://www.gmbinder.com/images/MS0gM8Z.png)}
/* footer */
 .phb:after{display:none;} 
 .phb .pageNumber{color:#000;font-size:10.5pt;bottom:6mm;}
 .phb .footnote{color:#000;font-size:10.5pt;bottom:6mm;text-align:left;width:100%;}
 .phb:nth-child(even) .pageNumber{left:19.5cm;}
 .phb:nth-child(even) .footnote{left:6mm;}
 .phb:nth-child(odd) .pageNumber{left:3mm;}
 .phb:nth-child(odd) .footnote{right:6mm;}
 
 .phb a{color:black;}
 
 /* Background */
    .phb{ background-image: url('https://drive.google.com/uc?id=1qhgrjltw4OybTN_c1yaYMeyD1q9P9lsw') }
    .phb{ background-size: cover }
    
    .phb .cover-splotch {background-image:url(https://www.gmbinder.com/images/jwEeJS1.png);filter: hue-rotate(202deg) brightness(35%) contrast(120%)}

.centered {
    position: relative;
    left: 50%;
    transform: translateX(-50%);
}

.phb:after{content:"";}

.phb#p1:after { display:none; }

.imgCenter {
  display: block;
  margin-left: auto;
  margin-right: auto;
  /*width: 50%;*/
}

/* letterheader */
.letterheader {
    position: absolute;
    top: 30px;
    left: 0;
    right: 0;
    margin-left:auto;
    margin-right:auto;
    background-image: url(https://www.gmbinder.com/images/YH3aESG.png);
    background-size: cover;
    width: 775px;
    height: 133px;

/* big letter */
}
.mmletter {
    position: absolute;
    top: 20px;
    left: 0;
    right: 0;
    margin-left:auto;
    margin-right:auto;
    background-size: cover;
    width: 163.2px;
    height: 163.2px;
}

.mml-a {background-image: url(https://www.gmbinder.com/images/fVVv93s.png);}
.mml-b {background-image: url(https://www.gmbinder.com/images/21X6N0B.png);}
.mml-c {background-image: url(https://www.gmbinder.com/images/MvnpOWF.png);}
.mml-d {background-image: url(https://www.gmbinder.com/images/AFbLU4P.png);}
.mml-e {background-image: url(https://www.gmbinder.com/images/28NVNf9.png);}
.mml-f {background-image: url(https://www.gmbinder.com/images/Oyrhmqy.png);}
.mml-g {background-image: url(https://www.gmbinder.com/images/fRyiQn4.png);}
.mml-h {background-image: url(https://www.gmbinder.com/images/N8NamlT.png);}
.mml-i {background-image: url(https://www.gmbinder.com/images/xWI93aa.png);}
.mml-j {background-image: url(https://www.gmbinder.com/images/GgIzsun.png);}
.mml-k {background-image: url(https://www.gmbinder.com/images/OcObsWl.png);}
.mml-l {background-image: url(https://www.gmbinder.com/images/B7AUyR6.png);}
.mml-m {background-image: url(https://www.gmbinder.com/images/q4wXoxt.png);}
.mml-n {background-image: url(https://www.gmbinder.com/images/OJtC4w9.png);}
.mml-o {background-image: url(https://www.gmbinder.com/images/adeRr5d.png);}
.mml-p {background-image: url(https://www.gmbinder.com/images/EEhcrSR.png);}
.mml-q {background-image: url(https://www.gmbinder.com/images/O1AhfzL.png);}
.mml-r {background-image: url(https://www.gmbinder.com/images/w66eIuZ.png);}
.mml-s {background-image: url(https://www.gmbinder.com/images/YEoe0PP.png);}
.mml-t {background-image: url(https://www.gmbinder.com/images/7Bk9D35.png);}
.mml-u {background-image: url(https://www.gmbinder.com/images/uVJZYUg.png);}
.mml-v {background-image: url(https://www.gmbinder.com/images/gKjngey.png);}
.mml-w {background-image: url(https://www.gmbinder.com/images/14WWpsC.png);}
.mml-x {background-image: url(https://www.gmbinder.com/images/ojIYjh0.png);}
.mml-y {background-image: url(https://www.gmbinder.com/images/Gi1ePwY.png);}
.mml-z {background-image: url(https://www.gmbinder.com/images/0ZTFNVs.png);}

/* letter at bottom of page */

.pageLetter {
    font-family:;
    position:absolute;
    right:25px;
    bottom:87.5px;
    color:#673e1c;
    z-index:1000;
    font-size:135%;
}

.phb:nth-child(even) .pageLetter {
    left:25px;
}

.phb .partpage{
    text-align:center;
    position:absolute;
    top:0;
    left:0;
    right:0;
    background-image:url('/assets/img/pph.png');
    background-size:cover;
    background-position:center;
    height:206px;
}

.phb .partpage h2{
    font-family:NodestoCaps;
    font-size:64pt;
    font-weight:normal;
    letter-spacing:-2px;
    margin:12px 0 -12.5px 0
    background-image:none;
}

.phb .partpage h5{
    font-family:ScalaSans;
    font-size:13pt;
    color:black
}

.phb .partpage-dmg{
    text-align:center;
    position:absolute;
    top:0;
    left:0;
    right:0;
    background-image:url('/assets/img/pph-dmg.png');
    background-size:cover;
    background-position:center;
    height:206px;
}

.phb .partpage-dmg h2{
    font-family:NodestoCaps;
    font-size:64pt;
    font-weight:normal;
    letter-spacing:-2px;
    margin:12px 0 -12.5px 0
    background-image:none;
}

.phb .partpage-dmg h5{
    font-family:ScalaSans;
    font-size:13pt;
    color:black
}

.partRotated {
    transform: rotate(180deg);
}

.toc {
    column-count:4;
}

</style>

<img src='https://drive.google.com/uc?id=1O1DBqJGHQyw_mpp0wZRwy1HoLP5c9HPY' class='cover-image' style="width:100%;height:100%;"/>

<div style="margin-top:32mm;filter: hue-rotate(202deg) brightness(35%) contrast(120%);background-size: 800px;left: 10px;width: 800px;height: 12px;" class='cover-diamond'></div>

<div class='cover-header' style="margin-top:20mm;font-size:60px;font-weight:bold;font-family:'Diabolica';">&AElig;therPunks!</span></div>

<div class='cover-header' style="margin-top:60mm;font-size:20px;font-weight:bold;"></div>

<div class='cover-splotch'></div>

<img src='https://drive.google.com/uc?id=1NAJL2mX9nQQA4y_D-ZrkREtBvG0-njuU' style="position:absolute;bottom:4.8cm;left:0.10cm;width:2.1cm;z-index:+1">

<div style="position:absolute;bottom:180px;left:90px;color:white;font-family:'Noto Serif';font-variant: small-caps;font-size:24pt;font-weight:bold;">5e Homebrew</div>

<div class='cover-footer' style="color:white;font-family:'Noto Serif';font-variant: small-caps;font-size:28pt;font-weight:bold;">5e Campaign & Critter Guide</div>

\pagebreak

<div class='wide'>

# Table of Contents

</div>

<div class='toc wide'>

- **[i Table of Contents](#p2)**
- **[0 Chapter 0: Table Guidelines](#p3)**
  - [0.1 Basic Etiquette](#chapter-0-table-guidelines-basic-etiquette)
    - [0.1.1 It's not personal](#chapter-0-table-guidelines-basic-etiquette-its-not-personal)
    - [0.1.2 Quiet in the back](#chapter-0-table-guidelines-basic-etiquette-quiet-in-the-back)
    - [0.1.3 Be on time](#chapter-0-table-guidelines-basic-etiquette-be-on-time)
    - [0.1.4 Too far is too far](#chapter-0-table-guidelines-basic-etiquette-too-far-is-too-far)
    - [0.1.5 You're the hero! (but so are they...)](#chapter-0-table-guidelines-basic-etiquette-youre-the-hero-but-so-are-they)
    - [0.1.6 The Metagame](#chapter-0-table-guidelines-basic-etiquette-the-metagame)
    - [0.1.7 I've seen that before!](#chapter-0-table-guidelines-basic-etiquette-ive-seen-that-before)
    - [0.1.8 Profanity is a Free Action!](#chapter-0-table-guidelines-basic-etiquette-profanity-is-a-free-action)
    - [0.1.9 DM Fiat](#chapter-0-table-guidelines-basic-etiquette-dm-fiat)
    - [0.1.10 This is about fun](#chapter-0-table-guidelines-basic-etiquette-this-is-about-fun)
    - [0.1.11 The Rule of Cool](#chapter-0-table-guidelines-basic-etiquette-the-rule-of-cool)
    - [0.1.12 But my other DM...](#chapter-0-table-guidelines-basic-etiquette-but-my-other-dm)
- **[1 Chapter 1: The Story So Far&hellip;](#p4)**
- **[ii Part One: Character Options](#p5)**
- **[2 Chapter 2: Campaign House Rules](#p6)**
  - [2.1 Campaign Sources in Use](#chapter-2-campaign-house-rules-campaign-sources-in-use)
  - [2.2 Character Creation at Campaign Start](#chapter-2-campaign-house-rules-character-creation-at-campaign-start)
  - [2.3 Character Rebuilding](#chapter-2-campaign-house-rules-character-rebuilding)
  - [2.4 Changed Content from WotC Sources](#chapter-2-campaign-house-rules-changed-content-from-wotc-sources)
    - [2.4.1 Gift of the Ever-Living Ones](#chapter-2-campaign-house-rules-changed-content-from-wotc-sources-gift-of-the-ever-living-ones)
    - [2.4.2 Revenant Blade](#chapter-2-campaign-house-rules-changed-content-from-wotc-sources-revenant-blade)
  - [2.5 HP](#chapter-2-campaign-house-rules-hp)
  - [2.6 Gear Changes](#chapter-2-campaign-house-rules-gear-changes)
  - [2.7 Learning New Tools, Languages & Skills with Downtime](#chapter-2-campaign-house-rules-learning-new-tools-languages-skills-with-downtime)
  - [2.8 Variant: Skills with different abilities](#chapter-2-campaign-house-rules-variant-skills-with-different-abilities)
  - [2.9 Mark](#chapter-2-campaign-house-rules-mark)
  - [2.10 Other House Rules](#chapter-2-campaign-house-rules-other-house-rules)
  - [2.11 Resting, Healing & Spell Recovery](#chapter-2-campaign-house-rules-resting-healing-spell-recovery)
  - [2.12 Healing Spirit](#chapter-2-campaign-house-rules-healing-spirit)
  - [2.13 Firearms in use and Changes](#chapter-2-campaign-house-rules-firearms-in-use-and-changes)
  - [2.14 Hybrid Classes](#chapter-2-campaign-house-rules-hybrid-classes)
  - [2.15 House Rules from other Sources](#chapter-2-campaign-house-rules-house-rules-from-other-sources)
    - [2.15.1 13th Age RPG](#chapter-2-campaign-house-rules-house-rules-from-other-sources-13th-age-rpg)
    - [2.15.2 BA Morrier: Variant Rules](#chapter-2-campaign-house-rules-house-rules-from-other-sources-ba-morrier-variant-rules)
    - [2.15.3 Darker Dungeons 5e v2.1](#chapter-2-campaign-house-rules-house-rules-from-other-sources-darker-dungeons-5e-v21)
    - [2.15.4 Tal'dorei Campaign Setting Rules](#chapter-2-campaign-house-rules-house-rules-from-other-sources-taldorei-campaign-setting-rules)

\columnbreak

- -
  - [2.15.5 Fifth Edition Options](#chapter-2-campaign-house-rules-house-rules-from-other-sources-fifth-edition-options)
  - [2.16 Character Birthsigns](#chapter-2-campaign-house-rules-character-birthsigns)
  - [2.17 Alignment](#chapter-2-campaign-house-rules-alignment)
  - [2.18 Chase Rules](#chapter-2-campaign-house-rules-chase-rules)
- **[3 Chapter 3: Modified Official Races](#p14)**
  - [3.1 Dragonborn](#chapter-3-modified-official-races-dragonborn)
  - [3.2 Elves and Half-elves](#chapter-3-modified-official-races-elves-and-half-elves)
  - [3.3 Humans](#chapter-3-modified-official-races-humans)
  - [3.4 Genasi](#chapter-3-modified-official-races-genasi)
    - [3.4.1 Air Genasi](#chapter-3-modified-official-races-genasi-air-genasi)
    - [3.4.2 Earth Genasi](#chapter-3-modified-official-races-genasi-earth-genasi)
  - [3.5 Gith](#chapter-3-modified-official-races-gith)
  - [3.6 Goliath](#chapter-3-modified-official-races-goliath)
  - [3.7 Kenku / Tengu](#chapter-3-modified-official-races-kenku-tengu)
  - [3.8 Revenant](#chapter-3-modified-official-races-revenant)
  - [3.9 Tabaxi Subraces](#chapter-3-modified-official-races-tabaxi-subraces)
  - [3.10 Tiefling](#chapter-3-modified-official-races-tiefling)
  - [3.11 Warforged](#chapter-3-modified-official-races-warforged)
- **[4 Chapter 4: New Races](#p18)**
  - [4.1 Cait Sith](#chapter-4-new-races-cait-sith)
  - [4.2 Burmecian](#chapter-4-new-races-burmecian)
  - [4.3 Mul](#chapter-4-new-races-mul)
  - [4.4 Selkies](#chapter-4-new-races-selkies)
  - [4.5 Vryloka](#chapter-4-new-races-vryloka)
- **[5 Chapter 5: Class Options](#p21)**
  - [5.1 Hybrid Classes](#chapter-5-class-options-hybrid-classes)
    - [5.1.1 Flavor Additions](#chapter-5-class-options-hybrid-classes-flavor-additions)
    - [5.1.2 Hybrid Class Features](#chapter-5-class-options-hybrid-classes-hybrid-class-features)
    - [5.1.3 Spell Casting as a Hybrid Class](#chapter-5-class-options-hybrid-classes-spell-casting-as-a-hybrid-class)
  - [5.2 Fighting Styles *(Any)*](#chapter-5-class-options-fighting-styles-any)
  - [5.3 Fighting Styles *(New Options)*](#chapter-5-class-options-fighting-styles-new-options)
  - [5.4 Revised Bard: Colleges of Swords and Valor](#chapter-5-class-options-revised-bard-colleges-of-swords-and-valor)
  - [5.5 Revised Fighter: Champion](#chapter-5-class-options-revised-fighter-champion)
  - [5.6 Revised Monk](#chapter-5-class-options-revised-monk)
    - [5.6.1 Revised Monk: Way of Four Elements Remastered](#chapter-5-class-options-revised-monk-revised-monk-way-of-four-elements-remastered)
    - [5.6.2 Revised Monk: Way of the Kensei](#chapter-5-class-options-revised-monk-revised-monk-way-of-the-kensei)
  - [5.7 Revised Paladin](#chapter-5-class-options-revised-paladin)
  - [5.8 Revised Rogue: Thief](#chapter-5-class-options-revised-rogue-thief)
  - [5.9 UA Ranger Revised 2016 Changes](#chapter-5-class-options-ua-ranger-revised-2016-changes)
    - [5.9.1 Core Changes](#chapter-5-class-options-ua-ranger-revised-2016-changes-core-changes)
    - [5.9.2 Bonus Spells](#chapter-5-class-options-ua-ranger-revised-2016-changes-bonus-spells)
    - [5.9.3 Hunter's Quarry](#chapter-5-class-options-ua-ranger-revised-2016-changes-hunters-quarry)
- **[6 Chapter 6: New and Revised Classes](#p24)**
  - [6.1 The Commander](#chapter-6-new-and-revised-classes-the-commander)
    - [6.1.1 Class Features](#chapter-6-new-and-revised-classes-the-commander-class-features)
    - [6.1.2 Commands & Tactics](#chapter-6-new-and-revised-classes-the-commander-commands-tactics)
    - [6.1.3 Fight from the Front](#chapter-6-new-and-revised-classes-the-commander-fight-from-the-front)
    - [6.1.4 Weigh the Odds](#chapter-6-new-and-revised-classes-the-commander-weigh-the-odds)
    - [6.1.5 Fighting Style](#chapter-6-new-and-revised-classes-the-commander-fighting-style)
    - [6.1.6 Command Style](#chapter-6-new-and-revised-classes-the-commander-command-style)
    - [6.1.7 Ability Score Improvement](#chapter-6-new-and-revised-classes-the-commander-ability-score-improvement)
    - [6.1.8 Extra Attack](#chapter-6-new-and-revised-classes-the-commander-extra-attack)
    - [6.1.9 Improved Attack](#chapter-6-new-and-revised-classes-the-commander-improved-attack)
    - [6.1.10 Final Stand](#chapter-6-new-and-revised-classes-the-commander-final-stand)
  - [6.2 Command Styles](#chapter-6-new-and-revised-classes-command-styles)
    - [6.2.1 Warlord](#chapter-6-new-and-revised-classes-command-styles-warlord)
    - [6.2.2 Strategist](#chapter-6-new-and-revised-classes-command-styles-strategist)
    - [6.2.3 Tactician](#chapter-6-new-and-revised-classes-command-styles-tactician)
  - [6.3 Commands & Tactics](#chapter-6-new-and-revised-classes-commands-tactics)
    - [6.3.1 Commands](#chapter-6-new-and-revised-classes-commands-tactics-commands)
    - [6.3.2 Tactics](#chapter-6-new-and-revised-classes-commands-tactics-tactics)
- **[7 Chapter 7: New Spells](#p30)**
  - [7.1 Spell Descriptions](#chapter-7-new-spells-new-spell-descriptions)
- **[8 Chapter 8: New and Revised Equipment](#p31)**
  - [8.1 New Equipment Table](#chapter-8-new-and-revised-equipment)
    - [8.1.1 New Armor](#chapter-8-new-and-revised-equipment-new-armor)
    - [8.1.2 New Weapons](#chapter-8-new-and-revised-equipment-new-weapons)
    - [8.1.3 New Adventuring Gear](#chapter-8-new-and-revised-equipment-new-adventuring-gear)
  - [8.2 Armor Descriptions & Special Properties](#chapter-8-new-and-revised-equipment-armor-descriptions-special-properties)
  - [8.3 New Weapon Properties](#chapter-8-new-and-revised-equipment-new-weapon-properties)
  - [8.4 New Weapon Descriptions](#chapter-8-new-and-revised-equipment-new-weapon-descriptions)
  - [8.5 New Adventuring Gear Descriptions](#chapter-8-new-and-revised-equipment-new-adventuring-gear-descriptions)
- **[9 Chapter 9: New Feats](#p35)**
  - [9.1 Non-Racial Feats](#chapter-9-new-feats-non-racial-feats)
    - [9.1.1 Buster Weapon Master](#chapter-9-new-feats-non-racial-feats-buster-weapon-master)
    - [9.1.2 Cloud Walk](#chapter-9-new-feats-non-racial-feats-cloud-walk)
    - [9.1.3 Daylight Adaptation](#chapter-9-new-feats-non-racial-feats-daylight-adaptation)
    - [9.1.4 Deck Brawler](#chapter-9-new-feats-non-racial-feats-deck-brawler)
    - [9.1.5 Deft Precision](#chapter-9-new-feats-non-racial-feats-deft-precision)
    - [9.1.6 Dual-Focused](#chapter-9-new-feats-non-racial-feats-dual-focused)
    - [9.1.7 Expert Scout](#chapter-9-new-feats-non-racial-feats-expert-scout)
    - [9.1.8 Firearm Mastery](#chapter-9-new-feats-non-racial-feats-firearm-mastery)
    - [9.1.9 Healer](#chapter-9-new-feats-non-racial-feats-healer-replaces-phb-healer-feat)
    - [9.1.10 Improved Familiar](#chapter-9-new-feats-non-racial-feats-improved-familiar)
    - [9.1.11 Living Conduit](#chapter-9-new-feats-non-racial-feats-living-conduit)
    - [9.1.12 Living Large](#chapter-9-new-feats-non-racial-feats-living-large)
    - [9.1.13 Spelldriver](#chapter-9-new-feats-non-racial-feats-spelldriver)
    - [9.1.14 Titanic Might](#chapter-9-new-feats-non-racial-feats-titanic-might)
    - [9.1.15 Versatile Combatant](#chapter-9-new-feats-non-racial-feats-versatile-combatant)
  - [9.2 New Racial Feats](#chapter-9-new-feats-new-racial-feats)
    - [9.2.1 Breath Weapon Manipulation](#chapter-9-new-feats-new-racial-feats-breath-weapon-manipulation)
    - [9.2.2 Human Resolve](#chapter-9-new-feats-new-racial-feats-human-resolve)
    - [9.2.3 Savage Perseverance](#chapter-9-new-feats-new-racial-feats-savage-perseverance)
    - [9.2.4 Shifting Manifestation](#chapter-9-new-feats-new-racial-feats-shifting-manifestation)
    - [9.2.5 Skyward Sentinel](#chapter-9-new-feats-new-racial-feats-skyward-sentinel)
    - [9.2.6 Vitae of the Night Prince](#chapter-9-new-feats-new-racial-feats-vitae-of-the-night-prince)
  - [9.3 Feats Options for New Races](#chapter-9-new-feats-feats-options-for-new-races)
- **[a APPENDICES](#p37)**
  - [a.i APPENDIX A: DMG Rules](#appendices-appendix-a-dmg-rules)
    - [a.i.i Renown](#appendices-appendix-a-dmg-rules-renown)
    - [a.i.ii Renown Tiers](#p38)
  - [a.ii APPENDIX B: Heirloom Items](#appendices-appendix-b-heirloom-items)
    - [a.ii.i Arrow of Detection](#appendices-appendix-b-heirloom-items-arrow-of-detection)
    - [a.ii.ii Boots of Elvenkind](#appendices-appendix-b-heirloom-items-boots-of-elvenkind)
    - [a.ii.iii Luckstone](#appendices-appendix-b-heirloom-items-luckstone)
  - [a.iii APPENDIX C: Unearthed Arcana & Plane Shift articles in use](#appendices-appendix-c-unearthed-arcana-plane-shift-articles-in-use)
    - [a.iii.i UA Resources Available](#appendices-appendix-c-unearthed-arcana-plane-shift-articles-in-use-ua-resources-available)
    - [a.iii.ii Plane Shift Resources Available](#appendices-appendix-c-unearthed-arcana-plane-shift-articles-in-use-plane-shift-resources-available)
    - [a.iii.iii UA Resources Changes](#appendices-appendix-c-unearthed-arcana-plane-shift-articles-in-use-ua-resources-changes)
    - [a.iii.iv Plane Shift Resources Changes](#appendices-appendix-c-unearthed-arcana-plane-shift-articles-in-use-plane-shift-resources-changes)
- **[iii Part Two: Critter Compendium](#p39)**
  - [iii.1 &AElig;therPunk! &mdash; Creatures & NPCs Encountered](#p40)
    - [iii.c Chocobo](#p41)
      - [iii.c.1 Chocobo, Yellow](#p42)
      - [iii.c.2 Chocobo, Blue](#p42)
      - [iii.c.3 Chocobo, Green](#p43)
      - [iii.c.4 Chocobo, Red](#p43)
      - [iii.c.5 Chocobo, Purple](#p44)
      - [iii.c.6 Chocobo, Black](#p44)
      - [iii.c.7 Chocobo, Gold](#p45)
      - [iii.c.8 Chocobo, Platinum](#p46)
    - [iii.n NPCs Met Previously](#p47)
      - [iii.n.1 Damascus Steel](#aetherpunk-creatures-npcs-encountered-npcs-met-previously-damascus-steel)
      - - [iii.n.2 Rhun&ouml;n](#aetherpunk-creatures-npcs-encountered-npcs-met-previously-rhunon)
- **[iv Changelog](#p48)**

</div>

\pagebreakNum

# Chapter 0: Table Guidelines

## Basic Etiquette

Outlined below are several points of basic etiquette, that I as a DM expect to be adhered to by the players in my campaigns, and think are important for a comfortable flow of the game and to guarantee a pleasant experience for all participants.

### It's not personal

Keep personal conflicts out of the game and don't let disagreements escalate into arguments, we're here to have fun.

### Quiet in the back

When the GM is explaining something, try and keep chatter to a minimum. Many times, important details can easily be missed if you aren't paying full attention. When entering a new room, meeting a new person, or encountering a monster for the first time, it's generally a good idea to take a second to hear what the GM is saying about it.

### Be on time

When the game starts is when the game starts. Being prompt is an important bit of etiquette and shows respect to both your fellow players and the DM. If you can't make the session due to an emergency or on longer notice an important family fest for example, just let me know as soon as you know and as long in advance as possible.

If you want to be part of a campaign I run though, in general it is assumed that you are willing to reliably schedule around "game night" and show up, so we can continue or story with all adventurers on board.

### Too far is too far

If anyone at the table is uncomfortable with a situation or series of events, they're perfectly justified in speaking up about it. The game might stop then while we discuss what happened and see how we can prevent issues in the future or it may continue with an after session or off week meeting to follow up. If something feels wrong, be sure to say something, no one will think less of you for it.

### You're the hero! (but so are they...)

It's easy to be caught up in a "larger than life" persona&mdash;that is actually the entire point of the game, really. That being said, everyone deserves and needs their moment in the spotlight to actually participate. Speak up and take action so you aren't left behind, but be sure to let others get a word in occasionally. It's a lot more fun if everyone works together.

### The Metagame

Metagaming to a degree is okay, for example reminding someone of their own class features or capabilities in combat or standard play is perfectly fine, and is in fact encouraged. When discussing plans during combat you should consider how you would be communicating in-character to avoid the NPCs overhearing you. Granted, as long as you provide a reasonable explanation I will generally let it slide by.

### I've seen that before!

If you recognize a monster and remember its weaknesses, it would be pointless and cruel for me to ask you not to use that knowledge. You may share it with the other players as well, but first I'll ask you to make the appropriate check or explain narratively why your character would know that information.

### Profanity is a Free Action!

Conversation in combat is perfectly fine as long as you keep it in-character. Shouting strategies across the battlefield might allow the enemies to hear what you're saying though; be careful and creative with it, maybe even speak in code or give more subtle hints. If you talk for too long you could end up spending your turn. Whenever you're close to crossing that line the GM will give you an appropriate warning and allow you to take your turn. Ignore the warning at your own risk.

\columnbreak

### DM Fiat

It's okay to ask questions if you think the DM has fudged something important, we all have off days. At times a DM Fiat may be put in place for the purpose of the story or as a function of a homebrew ruling, but you should never be afraid to ask questions. Just try to not interrupt the flow of the game too much with questions that could better be clarified after the session.

### This is about fun

Regardless of what the rules and numbers say we are coming together to have fun&mdash;that's the purpose of the game. If a rule or set of rules is ruining the fun by either making the game too challenging or not challenging enough we can ignore or adjust it; this is our story.

### The Rule of Cool

If it's awesome, it's probably possible, especially if it's well thought out and implemented. Rules will bend around cinematic actions at certain points, especially if it'll make a great story at a later date, but not EVERY time something happens. It's coolest the first time, keep that in mind.

### But my other DM...

Chances are there will be situations that I rule on differently than DMs you have played with in the past. This is natural, as we all can see different interpretations of the rules if not fully laid out or may choose to ignore or change them for a specific purpose. If a ruling is made and there is good reason for it, chances are it will stand, don't lose sleep over it; just roll with it. Include this in your Application to any of my games to show that you have read these Guidelines: "Code Zero".

\pagebreakNum

# Chapter 1: The Story So Far&hellip;

<div style="position:absolute;top:18mm;left:10mm;font-family:'Diabolica';font-size:34pt;font-style:oblique;">Nexus Prime&hellip;</div>

<div style="position:absolute;top:28mm;left:20mm;font-family:'Diabolica';font-size:24pt;">a world of possibilities&hellip;</div>

&nbsp;

<div style="margin-top:16mm;margin-bottom:145mm;">

The world of Nexus Prime is best described as a mashup of various official and homebrew D&D and non-D&D worlds, with inspiration from ***Eberron*** (D&D), ***Kaladesh*** (M:tG, Plane Shift: Kaladesh), and various video games, including the ***Final Fantasy*** series.
___
You are initiate members of a mercenary group called the &AElig;etherpunks, who select their candidates for their ability to come up with **unorthodox** solutions to the problems presented them.
___
Your team has been tasked with protecting cargo on an airship transport, a ***Lindblum***-class freighter, designated ***Lindblum&ndash;003***. The cargo is twelve sealed crates roughly 5-ft. to a side, and another four sealed crates of which are 10ft wide and high by 30ft long. All of  which you have been instructed to *"not open, under any circumstances, or the rest of your payment would be void"*.
___
Your team's handler, [Damascus Steel](#aetherpunk-creatures-npcs-encountered-npcs-met-previously-damascus-steel), a Warforged Beastmaster of the Niflheim Empire, for this mission is currently aboard, and is the goto for any questions.
___
Several hours into the journey, either as you are doing your rounds in the cargo bay, gambling with others, or standing guard elsewhere on the airship, you get a sense of unease&hellip;

</div>

<img src='https://drive.google.com/uc?id=1Q1ICJcwqpY8rBLheG48TmvV6UJ3kDoy8' style="position:absolute;top:20mm;right:5mm;width:50%;mix-blend-mode:multiply;" />

<img src='https://drive.google.com/uc?id=1ql1fTJDOr8k4h0Z6fOWA5CCtKmn2pfLn'  style="position:absolute;bottom:36mm;left:12.125mm;width:7.5%;mix-blend-mode:multiply;transform: skew(0.0075turn, 18deg);"/>

<img src='https://drive.google.com/uc?id=1ql1fTJDOr8k4h0Z6fOWA5CCtKmn2pfLn'  style="position:absolute;bottom:36mm;left:39.825mm;width:7.5%;mix-blend-mode:multiply;transform: skew(0.0075turn, -22deg);"/>

<img src='https://drive.google.com/uc?id=1ql1fTJDOr8k4h0Z6fOWA5CCtKmn2pfLn'  style="position:absolute;bottom:40.5mm;right:89.125mm;width:3.25%;mix-blend-mode:multiply;transform: skew(0.01turn, 50deg);"/>

<div class='wide' style="margin-top:85mm;margin-bottom:5mm;border:0.5px solid black;">

</div>

<div class="box" style="margin-left:-4mm;">

<img src='https://drive.google.com/uc?id=1BziiaNUn-GuYtrBNKLUrfNbYBCeLoaJe' style="width:60%;mix-blend-mode:multiply;" />

<div style="font-size:30pt;" class="text">

___
&times;12

</div>

</div>

\columnbreak

<div class="box" style="margin-right:4mm;">

<img src='https://drive.google.com/uc?id=1FS8h-mw_kiMuEdgglDO5rzhK0TylTewA' style="width:80%;mix-blend-mode:multiply;" />

<div style="font-size:30pt;" class="text">

___
&times;4

</div>

</div>

\pagebreakNum

<img src='https://drive.google.com/uc?id=1mnQY2RV53V3ZBR_FyW3ETyzJttc0T6K0' class='cover-image' style="z-index:-1;"/>

<img src='https://www.gmbinder.com/images/zdcYLtP.png' class='partRotated' style="position:absolute;bottom:0px;left:0px;height:75%;width:100%;filter:grayscale(50%) saturate(0.25) hue-rotate(320deg);transform:scaleY(-1);"/>

<div class='partpage'>

## Part One

<div style='margin-top:-0.5cm;'>

##### Character Options

</div>

</div>

<img src='https://drive.google.com/uc?id=1DV-t0MSfSyAnOv2LzfxOGYy7-mZruRAG' style="position:absolute;left:45%;bottom:10mm;height:25mm;width:25mm;filter:grayscale(50%) saturate(0.25) hue-rotate(320deg);" />

\pagebreak

# Chapter 2: Campaign House Rules

<div class='classTable wide' style="margin-top:0.5mm;margin-bottom:2.5mm;border-bottom:1px solid #000;">

## Campaign Sources in Use

| Source Tier | Source Name & Link | Usage | Exceptions |
|:---:|:---|:---|:---|
| 1 | This Campaign Guide | All | &mdash; |
| 2 | [Player's Handbook](https://www.amazon.com/Players-Handbook-Dungeons-Dragons-Wizards/dp/0786965606) | Most Options<sup>1, &#10028;</sup> | Humans<sup>2</sup>, Monk<sup>3,4</sup>, Ranger<sup>3,5</sup>, Rogue (thief)<sup>3</sup> |
| 2 | [Sword Coast Adventurers Guide](https://www.amazon.com/Sword-Coast-Adventurers-Guide-Accessory/dp/0786965800) | All | &mdash; |
| 2 | [Volo's Guide to Monsters](https://www.amazon.com/Volos-Guide-Monsters-Wizards-Team/dp/0786966017) | Non-Monstrous Races<sup>6</sup> | All Else |
| 2 | [Xanathar's Guide to Everything](https://www.amazon.com/Xanathars-Guide-Everything-Wizards-Team/dp/0786966114) | All | &mdash; |
| 2 | [Mordenkainens Tome of Foes](https://www.amazon.com/MORDENKAINENS-FOES-Accessory-Wizards-Team/dp/0786966246) | Races | All Else |
| 2 | [Guildmasters' Guide to Ravnica](https://www.amazon.com/Dungeons-Dragons-Guildmasters-Guide-Ravnica/dp/0786966599) | Races, Subclasses, Guilds<sup>9</sup> | All Else |
| 2 | [Ghosts of Saltmarsh](https://www.amazon.com/Dungeons-Dragons-Saltmarsh-Hardcover-Adventure/dp/0786966750) | Backgrounds | All Else |
| 3 | Other Official books | &dagger;<sup>10</sup> | &Dagger;<sup>11</sup> |
| 3 | [Wayfinder's Guide to Eberron](http://www.dmsguild.com/product/247882/Wayfinders-Guide-to-Eberron-5e) | Races, Dragonmarks, Magic Items<sup>1</sup> | Eldritch Machines, All Else |
| 4 | [Plane Shift Articles](https://mtg.gamepedia.com/Plane_Shift) | Most Options<sup>7</sup> | Bestiaries, *Gift of the Aetherborn*,</br> *X MARKS THE SPOT &mdash; A Plane Shift:</br> Ixalan Adventure* |
| 5 | [Unearthed Arcana](https://dnd.wizards.com/articles-tags/unearthed-arcana) | Selected Options<sup>8</sup> | Superseded Content, Mystic |
| 6 | [Sprouting Chaos Player's Companion (FEB 2017)](https://drive.google.com/file/d/0B-g9vLTX0eHKZmFkdFVPME9Lckk/view) | All | &mdash; |
| 6 | [Dark Arts Player's Companion (JUN 2019)](https://drive.google.com/file/d/1Kr3ZKYy3Me0ZFOhOQAmKBZlB9JUauhW5/view) | All | &mdash; |
| 6 | [City & Wild v2.1](https://www.dmsguild.com/product/226033/City-and-Wild) | All | &mdash; |
| 6 | [Gunslinger Class (Mage Hand Press - Free)](https://store.magehandpress.com/collections/free-products/products/gunslinger) | All | &mdash; |
| 6 | [Mage Hand Press Free Content](https://store.magehandpress.com/collections/free-products) | These Products | All Other MHP Products |
| 6 | [Monk: Way of the Four Elements, Revised & Simplified](https://drive.google.com/open?id=1C1NWq1sKDKXBfyfcdcN-lpYHx4pdZoh2) | All | &mdash; |
| 7 | Other Sources as the DM allows | &mdash; | All Else |

</div>

**1:** See Exceptions.
</br>
**2:** Use Humans from either [Plane Shift: Innistrad](https://media.wizards.com/2016/dnd/downloads/Plane_Shift_Innistrad.pdf) or [Plane Shift: Dominaria](https://media.wizards.com/2018/downloads/magic/Plane_Shift_Dominaria.pdf) , or the new Human subrace presented in [Chapter 3](#chapter-3-modified-official-races-humans)
</br>
**3:** See [Chapter 5: Class Options](#p25).
</br>
**4:** If using Monk Way of the Four Elements, the version linked [here](https://drive.google.com/open?id=1C1NWq1sKDKXBfyfcdcN-lpYHx4pdZoh2) is to be used.
</br>
**5:** If using a ranger in this campaign, Player's must use the [UA Revised Ranger 2016](https://media.wizards.com/2016/dnd/downloads/UA_RevisedRanger.pdf) with the changes mentioned in [UA Revised Ranger 2016 changes](#)
</br>
**6:** See [Kenku / Tengu](#chapter-3-modified-official-races-kenku-tengu).
</br>
**7:** See [Plane Shift Resources Available](#appendices-appendix-b-unearthed-arcana-plane-shift-articles-in-use-plane-shift-resources-available).
</br>
**8:** See [UA Resources Available](#appendices-appendix-b-unearthed-arcana-plane-shift-articles-in-use-ua-resources-available).
</br>
___
**9:** *Guildmasters Guild to Ravnica*'s Guilds are used as some of the larger mercenary guilds, granting their benefits to those who take them.
</br>
**10:** If you can show me where the option is presented, then it would most likely be allowed.
</br>
**11:** If you can not show me where the option is presented, then it will be banned until I can see it.
</br>
**&#10028;:** Warlock may choose to use either Charisma or Intelligence as their class ability, with Charisma as default. If you choose Intelligence, then all Cha-based abilities become Int-based, and you swap your Charisma save to an Intelligence save.

## Character Creation at Campaign Start

1.  Players choose options from the Players Handbook plus two additional sources for their PCs. All Unearthed Arcana articles that are not superseded by newer revisions or has since being released become officially published content count as ***ONE*** source, as does the Plane Shift Articles.

1.1. If a non-*Unearthed Arcana* character option is presented in a later</br><span style='margin-left:7mm;'>&nbsp;</spand>book with updates, errata, etc., then you must use that particular</br><span style='margin-left:7mm;'>&nbsp;</spand>item in the newer source, without it counting towards your PHB +</br><span style='margin-left:7mm;'>&nbsp;</spand>2.

1.2. Content from this campaign guide does not count towards the</br><span style='margin-left:7mm;'>&nbsp;</spand>PHB + 2 limit. Go nuts.

2. Level **3** start. PCs may choose from either standard array or point buy. You also add your proficiency bonus as a bonus in either a +2 to one stat, or +1 to two stats. As your proficiency bonus increases, you add an additional point after each increase.

3. Variant Human is **BANNED**, as all PCs gain a bonus 1<sup>st</sup> level feat. All non-Hybrid classes gain three extra skills at first level.

4.  I will be using a **milestone** leveling system. **Background gear** is free, PCs have **500gp** to buy gear and resources, they do not select from their class gear choices. PCs also gain an **heirloom magic item**, chosen from either: **a)** a list presented in *[Appendix C: Heirloom Items](#appendices-appendix-c-heirloom-items)*; **b)** a Wondrous Item chosen from either the Common or Uncommon Minor Magic Item Tables, *XGtE pg. 140&mdash;141*; or **c)** a piece of equipment made from special materials, as presented in **Part 3: Crafting** of [City & Wild v2.1](https://www.dmsguild.com/product/226033/City-and-Wild).

5.  PCs will start with a bonus tool proficiency, chosen from the list in the **PHB**. You will also start with this kit. This is due to using Xanathar's Guide Toolkit Rules, and should be something that can help on an adventure, such as *Cook's Utensils*, (for cooking meals), *Cartographer's Tools*, (for creating maps as you go), or *Brewer's Supplies*, (for creating potable water).

## Character Rebuilding

Following modified Adventure League Rebuilding rules, Players of levels 1-4 may, at the end of a campaign chapter, rebuild the following options of their PC. New Players joining later in the campaign, may rebuild twice with the same options presented here, up to the final chapter of the campaign.

* Character Class, including multiclass options
* Feats
* Ability Scores
* Class Archetype
* Class Features
* Spells
* Backgrounds (including bonds, features, flaws, ideals, and personality traits)
* Skills
* Alignment

\pagebreakNum

<div style="margin-bottom:2mm;"></div>

## Changed Content from WotC Sources

### Gift of the Ever-Living Ones

Found in **Xanathar's Guide to Everything**. *Gift of the Ever-Living Ones*'s prerequisite is changed to the following:

* *Prerequisite: Pact of the Chain feature or a Patron given familiar*. (Takes into account **Unearthed Arcana - Warlock & Wizard**'s *The Raven Queen* patron's first level class feature *Sentinel Raven*.

### Revenant Blade

Found in **Wayfinder's Guide to Eberron**. *Revenant Blade*'s third bullet point is changed to the following:

* When making an offhand melee attack with a double-bladed weapon, the weapon’s damage die for this attack increases to 2d4, instead of 1d4. (Takes into account the *Whirling Blades* Fighting style).

## HP

At first level, your HP will be calculated as your Hit Dice + Con SCORE, whereas after first level, you add your hit dice and Con Mod in addition to that.

## Gear Changes

Normal rations cost the same, but instead weigh 1 lb, **NOT** 2 lb Make a note of this. Additional ration varieties will be added, such as the Wandermeal variety.

When you purchase a class equipment pack, you may opt to swap some items for similar ones, such as 50 ft of hemp rope for 50 ft silk rope, or 10 rations for 10 Wanderlust Rations. As these prices are of differing amounts, there are strict rules. If the original is cheaper, you pay the difference. If the replacement is cheaper, tough luck, you lose out on free money.

## Learning New Tools, Languages & Skills with Downtime

Each tool is assigned a base difficulty that determines the number of days of training (8 hours per day) required to learn them.

To find the actual time that it takes for a character to learn the Tool, Language or Skill, use the following calculation.

* Base Days &times; 10 &frasl; Int Score, and round up to nearest whole number.
* **Easy *(100 Days)***: Gaming Sets
* **Skilled *(250 Days)***: Disguise Kit, Herbalism Kit, Musical Instruments, Poisoner's Kit, Thieves' Tools, Vehicles, Skills
* **Master *(400 Days)***: Artisan tools, Forgery Kit, Languages, Navigator's Tools

## Variant: Skills with different abilities

As shown on page 175 of the PHB, I will be using this variant rule.

I will be using rules from Xanathar's Guide to Everything (XGtE), with regards to Tool Proficiency and their uses. I will also be using the Tying Knots rules, from the same supplement.

## Mark

As seen on pg. 271 of the DMG, I'll be using this optional rule from the beginning of Chapter 1 of the campaign.

For those without access to the DMG, it is as follows:

*This option makes it easier for melee combatants to harry each other with opportunity attacks.*

\columnbreak

<div style="margin-bottom:2mm;"></div>

*When a creature makes a melee attack, it can also mark its target. Until the end of the attacker's next turn, any opportunity attacks it makes against the marked target has advantage. The opportunity attack doesn't expend the attacker's reaction, but the attacker can't make the attack if anything, such as the incapacitated condition or the shocking grasp spell, is preventing it from taking reactions. The attacker is limited to one opportunity attack per turn.*

## Other House Rules

There is a **Charge** action. It consists of the first part of the ***Charger*** feat, *"When you use your action to Dash, you can use a bonus action to make one melee weapon attack or to shove a creature."* The ***Charger*** Feat now grants a +10 feet bonus when using the **Charge** Action, as well as its second paragraph.

**Movement.** Diagonals use the 5ft-5ft-5ft rule, as it is described in the 5e PHB, and is used in Vanilla D&D4e.

## Resting, Healing & Spell Recovery

This variant has three rest types. They are as follows:

* **Rally**  &mdash; takes 10 minutes, allows spending 1 HD, recovers non-Pact Magic spell slots of levels 1 through 3, recovers Pact Magic spell slots, recovers other short rest mechanics at half rate. Taking longer than 10 minutes turns a rally into a short rest.
* **Short Rest** &mdash; standard short rest rules, with following changes: recovers non-Pact Magic spell slots of levels 1 through 6, recovers Pact Magic spell slots, recovers other short rest mechanics at full rate. Taking longer than an hour turns a short rest into a long rest.
* **Long Rest** &mdash; standard long rest rules.

This change makes combat more routine, since characters can easily recover from every battle. You might want to make combat encounters more difficult to compensate.

## Healing Spirit

The spell ends once the spirit has restored hit points a number of times equal to twice your spellcasting ability modifier (minimum of once).

## Firearms in use and Changes

For those who choose the Fighter (Gunslinger) Subclass, firearms do not misfire, firearms, gunpowder horns and gunpowder kegs cost &frac15; of their stated cost, and PC's need 1 gunpowder horn per 20 bullets. Bullets are non recoverable, weigh 0.1 lbs. per bullet, and must be bought in different sets for each type of firearm. For example, Musket bullets are different from Pistol bullets, but may interchange gunpowder horns for each type.

## Hybrid Classes

Detailed in [Hybrid Classes](#chapter-5-class-options-hybrid-classes). You may either choose to hybrid class or multiclass, but not both.

## House Rules from other Sources

### 13th Age RPG

<div class='smaller'>This roleplaying game was designed by Rob Heinsoo (lead designer for D&D 4th Edition), and Jonathan Tweet, (designer for D&D 3rd and 4th Edition)</div>

I'll be using the following rule from this RPG:

#### Escalation Die

The escalation die represents a bonus to attacks as the fight goes on.

At the start of the second round, the GM sets the escalation die at 1. Each PC gains a bonus to attack rolls equal to the current value on the escalation die. Each round, the escalation die advances by +1, to a maximum of +6.

Monsters and NPCs do not add the escalation die bonus to their attacks

If the DM judges that the characters are avoiding conflict rather than bringing the fight to the bad guys, the escalation die doesn't advance. If combat virtually ceases, the escalation die resets to 0.

\pagebreakNum

<div style="margin-bottom:2mm;"></div>

### BA Morrier: Variant Rules

<div class="smaller">A PDF sourcebook from DM's Guild, designed for D&D 5e. Currently unavailable at the source.</div>

#### Healer's Kit

As a house rule, any individual can spend one use of a healer's kit to stabilize a companion. If you have proficiency in the Medicine skill, you gain the following benefits when using a healer's kit.

* When you use a healer's kit to stabilize an ally, that ally also regains 1 hit point.
* During a short rest, you may expend one use of a healer's kit to bind wounds, offer pain-numbing salves, and apply natural anticoagulants. The target heals 1d6+4 hit points of damage. The target also gains hit points equal to its number of hit dice.

### Tal'dorei Campaign Setting Rules

<div class="smaller">A sourcebook for D&D 5e, created by Matt Mercer, of Critical Role fame.</div>

As seen in the [Tal'dorei Campaign Setting Guide](https://www.drivethrurpg.com/product/216849/Critical-Role-TalDorei-Campaign-Setting), the following rules are in place for this campaign:

* **Rapid Quaffing:** The time required to pull free and quaff a potion is changed from one action to one bonus action. This enables many classes, especially more melee/combat focused classes, the ability to down a healing potion or enhancing liquid without sacrificing their entire round of attacks. Administering a potion to an unconscious character would still require an action. Don't forget: enemies can also drink their potions as quickly!
* **Multi-Spell:** PCs of 8th level or higher automatically gain the Spelldriver feat. This will allow spellcasting classes more options to aid themselves and the party at higher levels without a comparably sluggish per-round ability set, spending their solitary action on a bonus action spell. This would also apply to enemy spellcasters, leading to additional chaos and challenge.
* In this campaign, alternative resurrection rules are being used. See Resurrection Rules.
* **Intimidating Presence *(Barbarian Ability)*** is based on Strength and Charisma.
* The *Wall of Stone* spell is instantaneous and permanent, not concentration with a duration.

#### Didn't Come Back Right &mdash; Alternative Resurrection Rules

Within this rule, the process of dying and being pulled back into your body is a harrowing experience. The magic itself pulls you from beyond the dark veil of death, taking its toll on your body and psyche each time, leaving you less and less the person you were.

When a character is brought back to life via magic, that character must make a Wisdom saving throw with a DC equal to 20 &ndash; the level of the magic used to return the character to life. A failure on this check inflicts long term madness (see **DMG**, p. 260), except that the duration is measured in days rather than hours. A *lesser restoration* or *remove curse* will alleviate the madness itself, though it returns any time that character drops to 0 hit points or awakens from sleep, until its full duration has expired.

### Darker Dungeons 5E v2.1

<div class="smaller">

A homebrew sourcebook made by [u/giffyglyph](https://old.reddit.com/user/giffyglyph) over on reddit. Even has a [subreddit](https://old.reddit.com/r/darkerdungeons5e/) dedicated to the book.

</div>

#### Dragonborn & Human additions

I have added changes from the Racial section for the Dragonborn & Human sections to this guide, namely Dragonborn Breath Weapon and Human Determination.

#### Your Funeral

If your adventuring party are able to recover your body, bury it, and throw an appropriately lavish funeral (at least 50 gp for each of your character levels), they each gain one favour from you from beyond the grave.

#### Reading of the Will

You can leave a will behind to confirm who the heirs to your property are. This can be arranged in retrospect with your DM after the character's death if necessary. The reading of the will usually takes place at your funeral, or before the introduction of a new character. This might be the last opportunity for your character to say any final words, so make the most of it.

\columnbreak

<div style="margin-bottom:2mm;"></div>

#### A New Beginning

Once you've added your character's name to the graveyard, it's time to start anew with a fresh character or an elevated NPC/henchman. There are a variety of ways to determine your starting level and wealth—choose the method that fits your game.

#### Starting Level

In the case of a PC death, your new PC starts at the same level as your old character.

#### Starting Wealth

Inheritance: Inherit gold and starting items from your old character—whatever was passed on in your will. Your new character should be known or related to your old character in some fashion.


### Fifth Edition Options

<div class="smaller">A sourcebook for D&D 5e, created by Total Party Kill Games, quote "Creators of Dark Fantasy Pathfinder and Dungeons & Dragons Compatible Products Plus Card Games and More!"</div>

#### Better Critical Hits

With this variant, critical hits are more lethal. Instead of simply dealing double the dice of damage, critical hits deal maximum damage plus the attack's dice of damage. For example, a longsword attack that deals 1d8+5 damage would deal 1d8+13 on a critical hit.

The benefit to this variant is that critical hits become much more effective and faster during gameplay. This is nice because as written there are times when a critical hit could equate to simply one more point of damage, which is neither impressive, fun nor cinematic. This does make combat a little more lethal though and especially at low level. If you want a more gritty or epic game, consider this variant.

#### Easier Attunement

With this variant, magic and magic items are more common. Characters can attune to a number of magic items equal to their proficiency bonus, with a minimum of the default **three** attunement slots.

#### Variant Magical Healing

Your curative spells always heal their average die roll (rounded up). For example, a 1<sup>st</sup> level cure wounds spell heals 5 hit points per die. No one likes getting 1's on the cure critical wounds when the chips are down.

## Character Birthsigns

### Birthsigns

| Roll | Constellation | game Month | Earth Month |
|:--:|:--|:--|:--|
| 1 | The Ritual | Morning Star | ***JAN*** |
| 2 | The Lover | Sun's Dawn | ***FEB*** |
| 3 | The Lord | First Seed | ***MAR*** |
| 4 | The Mage | Rain's Hand | ***APR*** |
| 5 | The Shadow | Second Seed | ***MAY*** |
| 6 | The Steed | Mid Year | ***JUN*** |
| 7 | The Apprentice | Sun's Height | ***JUL*** |
| 8 | The Warrior | Last Seed | ***AUG*** |
| 9 | The Lady | Hearthfire | ***SEP*** |
| 10 | The Tower | Forstfall | ***OCT*** |
| 11 | The Atronach | Sun's Dusk | ***NOV*** |
| 12 | The Thief | Evening Star | ***DEC*** |
| Double | The Serpent | &mdash; | ***&mdash;*** |

### The Constellations

There are thirteen named constellations in the sky. There are three Guardian signs; The Warrior, The Mage, and The Thief, each of which protects three charges. Each of these twelve signs corresponds to one of the twelve months in the Gaian year. The thirteenth sign, The Serpent, has no guardian or month and moves around the sky, usually threatening the other signs.

You can decide your character's birthsign, using your class and intended playstyle to determine what sign best suits your character.

\pagebreakNum

<div style="margin-bottom:2mm;"></div>

If you want to randomly choose what birthsign you were born under, you can use the table to the side to determine the month of your birth. Roll a d12 to determine what month you were born in, and then a second d12. If your second roll matches your first roll, the Serpent intervenes and becomes your birthsign. For example, if you roll a 6 on your first die, indicating you were born in Mid Year. On your second roll, if you roll another 6, your birthsign is The Serpent. If you roll any other number, your birthsign is The Steed.

#### The Serpent

You were born under the Birthsign of the Serpent and gain the Serpent power.

Serpent. The power of the serpent can protect yourself from destruction or allow you to bring destruction to others. Once each day, you can use the power to create one of the following effects:

As an action, you cure yourself from one non-magical disease and dispel one magical effect from yourself.

As an action, you touch a creature and infect them with a slow but potent poison, You instantly deal 1d4 poison damage, and an additional 1d4 poison damage at the start of each turn of your turns for the next minute. This damage ignores resistance. This damage increases by 1d4 when you reach 5th level (2d4). 11th level (3d4), and 17th level (4d4).

Once you use this ability, you can't use it again until the next dawn.

#### The Ritual

*Morning Star*

You were born under the Birthsign of the Ritual and gain the Mara's Gift power and the Blessed Word power.

Mara's Gift. As an action, you regain hit points equal to 1d8 + your Constitution modifier.

This power's healing increases by 1d8 when you reach 5th level (2d8). 11th level (3d8), and 17th level (4d8).

Once you use this ability, you can't use it again until the next dawn.

Blessed Word. As an action, you speak a prayer censuring the undead. Choose one undead creature within 30 feet of you to make a Wisdom saving throw. The DC for this saving throw equals 8 + your proficiency bonus + your Wisdom or Charisma modifier (your choice). If the creature fails its saving throw, it is turned for 1 minute or until it takes any damage.

A turned creature must spend its turn trying to move as far away from you as it can, and it can't willingly move to a space within 30 feet of you. It also can't take reactions. For its action, it can use only the Dash action or try to escape from an effect that prevents it from moving. If there's nowhere to move, the creature can use the Dodge action.

Once you use this ability, you can't use it again until the next dawn.

#### The Lover

*Sun's Dawn*

You were born under the Birthsign of the Lover and gain the Lover's Kiss power.

Lover's Kiss. As an action, you touch a humanoid in an attempt to paralyze them. The target must make a Wisdom saving throw or be paralyzed for 1 minute. The DC is determined by 8 + your proficiency bonus + your Constitution or Wisdom modifier (your choice). The paralysis ends early if the target takes damage. At the end of each of its turns, the target can make another Wisdom saving throw. On a success, the spell ends on the target.

Once you use this ability, you can't use it again until the next dawn.

#### The Lord

*First Seed*

You were born under the Birthsign of the Lord and gain the Blood of the North power and the Trollkin curse.

Blood of the North. As an action, you regain hit points equal to twice your level + your Constitution modifier. If the amount of hit points you gain exceeds your hit point maximum, you gain the remainder as temporary hit points which last for up to 1 hour.

Once you use this ability, you can't use it again until the next dawn.

Trollkin. You have a natural curse and vulnerability to fire. Whenever you take fire damage, the damage you take is increased by an amount equal to half your level.

#### The Mage

*Rain's Hand*

You were born under the Birthsign of The Mage and gain the following benefits:

\columnbreak

<div style="margin-bottom:2mm;"></div>

Your Intelligence or Wisdom score increases by 1, to a maximum of 20.

You gain advantage on Constitution saving throws to maintain concentration on a spell.

Additionally, you learn one cantrip and one 1<sup>st</sup> level spell of your choice from the wizard spell list. Intelligence is your spellcasting ability for these spells. If you can cast spells, they are added to your spell list for you.

You can cast the 1<sup>st</sup> level spell once without expending a spell slot, regaining the ability to do so again at the next dawn.

#### The Shadow

*Second Seed*

You were born under the Birthsign of the Shadow and gain the following benefits:

Your Intelligence, Charisma, or Wisdom score increases by 1, to a maximum of 20.

You gain the Moonshadow power.

Moonshadow. As an action, you can cast the spell Invisibility on yourself without expending a spell slot.

Once you use this ability, you can't use it again until the next dawn.

#### The Steed

*Mid Year*

You were born under the Birthsign of the Steed and gain the following benefits:

Your Constitution score increases by 1.

Your speed increases by 10 feet.

#### The Apprentice

*Sun's Height*

You were born under the Birthsign of the Apprentice and gain the following benefits:

You gain an additional level spell slot of the highest level you can cast, to a maximum of 5th level.

You are weakened to one type of magical damage determined by rolling on the Apprentice Magic Weakness table below. Whenever you take damage from your weakened damage type, the damage is increased by an amount equal to half your level.

##### THE APPRENTICE MAGIC WEAKNESS

| d4 | Weakness |
|:--:|:--|
| 1 | Cold |
| 2 | Fire |
| 3 | Poison |
| 4 | Lightning |

#### The Warrior

*Last Seed*

You were born under the Birthsign of the Warrior and gain the following benefits:

Your Strength and Constitution attributes are increased by 1, to a maximum of 20.

#### The Lady

*Hearthfire*

You were born under the Birthsign of the Lady and gain the following benefits:

Your Wisdom and Constitution attributes are increased by 1, to a maximum of 20.

#### The Tower

*Frostfall*

You were born under the Birthsign of the Tower and gain the Tower Key power and the Tower Warden power.

Tower Key. As an action you can cast the knock spell without expending a spell slot.

Once you use this ability, you can't use it again until the next dawn.

Tower Warden. As a reaction, when you take damage from an attack, you can reflect some or all of the damage back to the attacker. The damage you can reflect is equal to 1d6.

This power's reflected damage increases by 1d6 when you reach 5th level (2d6). 11th level (3d6), and 17th level (4d6).

Once you use this ability, you can't use it again until the next dawn.

\pagebreakNum

<div style="margin-top:2mm;"></div>

#### The Atronach

*Sun's Dusk*

You were born under the Birthsign of the Atronach and gain the following benefits:

You gain two additional level spell slots of the highest level you can cast, to a maximum of 5th level.

You gain the Stunted Magicka feature, described below.

Stunted Magicka. The Atronach birthsign has gifted you with a large pool of magicka, but your natural gift is stunted by reduced regeneration.

Unlike other spellcasters, you do not regain all of your spell slots at the end of a long rest, instead, you only regain half of your expended spell slots, rounding up (minimum of 1).

Additionally, whenever you are targeted by a spell that requires you to make a saving throw, you have a chance to absorb the spell, replenishing your spell slots. On a successful save you also absorb spell energy equal to the level of the spell, and may recover spell slots in any combination of levels, up to the absorbed spell's level. On a failed save, you do not absorb any spell energy and are effected by the spell as normal.

#### The Thief

*Evening Star*

You were born under the Birthsign of the Thief and gain the following benefits:

Your Dexterity score increases by 1, to a maximum of 20.

Your speed increases by 5 feet.

You gain one Luck Point. Your Luck Point is a d6. You can add your Luck Point to one ability check, attack roll, or saving throw you make. You can wait until after you roll the d20 before deciding to use the Luck Point, but must decided before the DM says whether the roll succeeds or fails. You regain your expended Luck Point at the next dawn, and you can never have more that one Luck Point from this feature at a time.

## Alignment

Alignment is changed from default 5<sup>th</sup> edtion.

While attempting to implement alignment, one might encounter some or all of the following sentiments that run counter to the system:

* "Look, I don't like to see everything falling apart and disorganized, but that doesn't mean I feel the need to follow the letter of the law if it doesn't make sense in a given circumstance."
* "I'm a good person, but if someone attacks me, I'm going to fight back&mdash;and not pull any punches."
* "I love freedom and individual choice. Does that mean I have to be in favor of the dissolution of society?"

This alternate system seeks to rectify those situations by making each factor of one's alignment&mdash;whether it be good, evil, lawful, or chaotic&mdash;a spectrum rather than an absolute. Thus, someone can be more lawful than someone else, even though they are both lawful. Each factor of a character's alignment carries a numeric rating on a scale of 1 to 9.

Players should not look at the rating system as a judgment. These are not levels one necessarily attempts to ascend like character levels. A character with a higher rating in an alignment is not a "better'' character than someone with a lower rating, any more than a chaotic character is "better'' than a neutral one.

One can argue, in fact, that a character with a 9 rating in an alignment is too fanatical a personality to make a good long-term character. Not even otherplanar paragons of alignment,like angels or demons,necessarily rate a 9 every time. Likewise,the gods themselves fit into the spectrum at various places rather than always being at the extreme. A typical paladin, for example, might be merely L5G5.

To get an idea of what ratings you would give a particular creature, use the following suggested descriptions of each level. DMs can change these descriptions to fit their campaigns and their conceptual understandings of how alignment should work in their worlds.

\columnbreak

<div style="margin-top:2mm;"></div>

##### Good

|  |  |
|:--|:--|
| &nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Doesn't like to see bad things happen to others |
| &nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Helps others occasionally, particularly friends |
| &nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Willing to help strangers on occasion |
| &nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Gives of himself to help others, whether it be time,</br>&nbsp;&nbsp;&nbsp;&nbsp;money, possessions, or something else |
| &nbsp;&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Takes concepts like purity, innocence, and other higher</br>&nbsp;&nbsp;&nbsp;&nbsp;principles very seriously |
| &nbsp;&nbsp;&nbsp;&nbsp;8&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Would sacrifice anything, even his life, for others in a</br>&nbsp;&nbsp;&nbsp;&nbsp;heartbeat |
| &nbsp;&nbsp;&nbsp;&nbsp;9&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Refuses to harm anything or anyone, even if it brings</br>&nbsp;&nbsp;&nbsp;&nbsp;misfortune or death on himself |

##### Evil

|  |  |
|:--|:--|
| &nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Finds joy in the misfortune of others, but usually</br>&nbsp;&nbsp;&nbsp;&nbsp;wouldn't act to hurt others |
| &nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Willing to cause others pain or misfortune to better</br>&nbsp;&nbsp;&nbsp;&nbsp;himself |
| &nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Actively enjoys lying, stealing, and inflicting pain on</br>&nbsp;&nbsp;&nbsp;&nbsp;others |
| &nbsp;&nbsp;&nbsp;&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Willing to cause harm even to friends to get ahead |
| &nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Willing to kill to better himself |
| &nbsp;&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Will kill for the sheer pleasure of bringing pain and</br>&nbsp;&nbsp;&nbsp;&nbsp;death to others |
| &nbsp;&nbsp;&nbsp;&nbsp;9&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Refuses to harm anything or anyone, even if it brings</br>&nbsp;&nbsp;&nbsp;&nbsp;misfortune or death on himself |

##### Law

|  |  |
|:--|:--|
| &nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Generally tries to keep his promises and, when in</br>&nbsp;&nbsp;&nbsp;&nbsp;doubt, follows the rules |
| &nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Has a set of guidelines he generally lives by |
| &nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Genuinely respects authority figures for their positions |
| &nbsp;&nbsp;&nbsp;&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Willing to see one person killed or hurt if it helps large</br>&nbsp;&nbsp;&nbsp;&nbsp;numbers of people |
| &nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Willing to follow a code or a strict set of principles even</br>&nbsp;&nbsp;&nbsp;&nbsp;if it brings misfortune on himself |
| &nbsp;&nbsp;&nbsp;&nbsp;8&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Would be willing to see many people harmed or killed if</br>&nbsp;&nbsp;&nbsp;&nbsp;it helped society as a whole |
| &nbsp;&nbsp;&nbsp;&nbsp;9&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Follows a set path in so orderly a way as to risk blind</br>&nbsp;&nbsp;&nbsp;&nbsp;self-destruction.Despises and fears individuality |

##### Chaos

|  |  |
|:--|:--|
| &nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;A bit of a nonconformist or free spirit |
| &nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Will lie if it suits him,hates to be ordered around |
| &nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Disorganized but extremely easygoing |
| &nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Rejects the idea of majority rule |
| &nbsp;&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Prefers anarchy to any other form of organization |
| &nbsp;&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Occasionally destroys things in reckless abandon |
| &nbsp;&nbsp;&nbsp;&nbsp;9&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;Hates structure and order so much that destruction for</br>&nbsp;&nbsp;&nbsp;&nbsp;its own sake becomes desirable |

##### Neutrality

This system assumes that there are, in fact, very few truly neutral people. Most are at least a 1 rating on one side of the spectrum or the other. For that reason, rating 1 is still considered Neutral for purposes of alignment-affecting or -detecting spells.

## Chase Rules

* **Setup.** Determine where everyone involved in the chase is located. The only thing that matters is how far apart everyone is. Place the lead quarry first, then place the others at the appropriate distance behind him. If their locations aren’t pre-determined based on the encounter, you can randomly set the distance from the lead pursuer to the closest quarry at the speed factor of the fastest creature + 5x(1d6) feet.
* **Determine Initiative.** Set initiative order based on position. The lead character is assigned the highest initiative, followed by the others in order of their distance behind him. This initiative order may change from round to round as creatures pass each other. Ties go to the one with the highest dexterity score.

\pagebreakNum

<div style="margin-top:2mm;"></div>

* **Track Movement.** After the lead quarry determines his total move distance – write that distance down so it can be referenced by all players. Don’t move that figure. On each participant’s turn, compare the distance he moved to that of the lead quarry. If they are the same, the distance between them remains the same, so his figure doesn’t move. If he moved farther than the lead quarry, subtract the lead quarry’s move from his and move his figure forward by that amount. If the lead quarry moved farther than he did, subtract his move distance from the lead quarry’s and move his figure back by this amount.
* **No Opportunity Attacks.** No one involved directly in the chase can use an opportunity attack against anyone else in the chase.
* **Track Exhaustion.** You can use the Dash action a number of times equal to 3+ your Constitution modifier. For each Dash action after that you must succeed on a DC 10 Constitution check or take one level of exhaustion. Your speed becomes 0 when you reach level 5.
* **Pursuer Overtakes Quarry.**
1. **Attack.** If a pursuer is able to move into a quarry’s space, he may instead use a bonus action to perform a single melee attack against the quarry when he is within reach. The attack is made at a disadvantage. Note that the pursuer cannot use this option if he can only move within reach, but could not overtake the quarry if he chose to.
2. **Overtake.** A pursuer overtakes a quarry when he moves into its space. He can then use a bonus action to attempt to grapple the creature. Normal grapple rules apply. If successful, both pursuer and quarry are stopped. Rather than grapple, the pursuer may attempt to trip, push over or tackle the quarry. The pursuer has advantage on the attack. As an optional rule, an attack that fails by 5 or more results in the pursuer falling prone.
* **Quarry Escapes.** The quarry can attempt to escape if it is out of sight for all of the pursuers. He makes a Dexterity (Stealth) check and must beat the passive Wisdom (Perception) scores of the pursuers.

<div style="margin-bottom:-2mm;"></br></div>

* **Complications.** Roll 1d20 at the end of your turn and compare that roll to the appropriate Chase Complications table. The complication is not applied to your character, but rather to the next character in initiative order. You can spend an inspiration point to negate the complication you rolled or one that effects you. Rather than rolling on the table, the DM may allow a quarry to impose a condition on a pursuer to slow him down. It might be one listed on the table, or one of his own creation. Another option to using a table would be for the DM to declare conditions based on his map or the terrain and the path the quarry takes.

    * **Prone.** A complication may leave you prone. To get up from prone you subtract the distance represented by half your move rate from your total move distance.
    * **Difficult Terrain.** Each foot of difficult terrain uses two feet of your move rate. So if you cross five or ten feet of difficult terrain you can simply subtract five or ten feet from your total distance traveled.

**Complication Tables.** The following are Complication Tables that I have created for different terrain types. The first table is a generic complications table that can be used in a pinch, when you just need to run a chase quickly. The tables that follow that one list a complication type for each situation. Look up the type in the generic complication table.

##### Complications by terrain type

The headings are:

**1d20:** <span style="margin-left:17.5mm;">&nbsp;</span> The results of your d20 roll

**Complication:** <span style="margin-left:5.5mm;">&nbsp;</span> This is what causes the obstruction.

**Type:** <span style="margin-left:17.9mm;">&nbsp;</span>This refers to the Generic Chase above.

<div class="wide" style="margin-bottom:-1.5mm;">

##### Generic Chase Complications

| **1d20** | **Type** | **Complication** | **Examples** |
|:--:|:--:|:--|:--|
| 1 | Hazard | Make a DC 10 Dexterity saving throw to navigate the impediment. On a failed save, you fall 1d4 x 5 feet, taking 1d6 bludgeoning damage per 10 feet fallen as normal, and land prone. | Hole, crevice, trap, unseen obstacle, steep incline, heavily broken ground, the path skirts a quicksand pit, log bridge crossing a stream, running on rooftops, slippery floors, jump through window |
| 2 | Cramped space | Make a DC 15 Dexterity (Acrobatics) check to get through this space. On a failed check, the obstacle counts as 10 feet of difficult terrain. | street, market, public building, alleyway, shoppers, stationary crowd |
| 3 | Poor visibility | Make a DC 10 Constitution saving throw. On a failed save, you are blinded until the end of your turn. While blinded in this way, your speed is halved. | blind corner, woods, dense brush or busy area |
| 4 | Barrier | Make a DC 15 Dexterity (Acrobatics) check to get past the obstacle. On a failed check you fall prone. | wall, fence, cliff, thick hedges, tall fences, building, river, canyon or swamp |
| 5 | Impediment | Make a DC 10 Strength (Athletics) or Dexterity (Acrobatics) check (your choice) to get past the impediment. On a failed check, the obstacle counts as 5 feet of difficult terrain. | Tree branch, fallen log, chicken coop or vegetable cart, trail suddenly drops off, flock of birds |
| 6 | Crowd | Make a DC 10 Strength (Athletics) or Dexterity (Acrobatics) check (your choice) to make your way through the crowd unimpeded. On a failed check, the crowd counts as 10 feet of difficult terrain. | fleeing (or angry) peasants, a funeral procession, people leaving a performance, a moving crowd |
| 7 | Entanglement | Make a DC 15 Dexterity saving throw to avoid it. On a failed save, you are caught as if in a net and restrained. See chapter 5 ``Equipment,'' of the Player’s Handbook for rules on escaping a net. | Clotheslines, curtains, banners, drying pots, chimes, hanging meat, vines |
| 8 | Animal herd | Make a DC 10 Dexterity saving throw. On a failed save, you are knocked about and take 1d4 bludgeoning damage and 1d4 piercing damage. | Must pass through a herd of animals. Camels, Donkeys, Horses, Cows, etc. |
| 9 | Uneven Ground | Make a DC 10 Dexterity (Acrobatics) check to navigate the area. On a failed check, the ground counts as 10 feet of difficult terrain. | Any stairs of 4 or more steps (less than 4 steps is considered an ``impediment''), river bank, hill, 5 feet or more change in elevation in 10 feet of horizontal movement. |
| 10 | Obstacles | Make a DC 10 Dexterity (Acrobatics) or Intelligence check (your choice) to past. On a failed check, the maze counts as 10 feet of difficult terrain. | Tables, chairs, pews, benches, carts, crates, field of boulders, field of giant mushrooms. |
| 11-20 | No Complication | &mdash; | &mdash; |

</div>

\pagebreakNum

<div style="margin-top:2mm;"></div>

##### Aerial Complications

Complications are easier to avoid when you are flying, checks are made with advantage.

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Flock of birds | Impediment |
| 2 | Tower | Hazard |
| 3 | Storm clouds | Barrier |
| 4 | Updraft | Impediment |
| 5 | Smoke | Poor visibility |
| 6 | Turbulence | Cramped space |
| 7 | Smokestack | Hazard |
| 8 | Ship mast | Hazard |
| 9 | Dust | Poor visibility |
| 10 | Ice buildup | Entanglement |
| 11-20 | No Complication | &mdash; |

##### Arctic Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Crevice | Hazard |
| 2 | Snow drifts | Cramped space |
| 3 | Storm clouds | Poor visibility |
| 4 | Blowing snow | Barrier |
| 5 | Ice cliff | Impediment |
| 6 | Chunks of broken ice | Animal herd |
| 7 | Herd of walrus | Uneven Ground |
| 8 | Snow bank | Obstacles |
| 9 | Field of Ice boulders | Hazard |
| 10 | Ice bridge over river | Hazard |
| 11-20 | No Complication | &mdash; |


##### Beach Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Tidal pool | Impediment |
| 2 | Crevice | Hazard |
| 3 | River | Barrier |
| 4 | Flock of birds | Impediment |
| 5 | Fishing nets | Entanglement |
| 6 | Sand hill | Uneven Ground |
| 7 | Lobster traps | Obstacles |
| 8 | Pier | Hazard |
| 9 | Driftwood | Impediment |
| 10 | Sea turtles | Animal herd |
| 11-20 | No Complication | &mdash; |

##### Cave Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Crevice | Hazard |
| 2 | Narrow passage | Cramped space |
| 3 | Bats | Impediment |
| 4 | Floor slopes up or down | Uneven Ground |
| 5 | Giant mushrooms | Obstacles |
| 6 | Roots across passage | Entanglement |
| 7 | Stalagmites | Impediment |
| 8 | Wet floor | Hazard |
| 9 | Rubble covered floor | Impediment |
| 10 | Lava crossing | Barrier |
| 11-20 | No Complication | &mdash; |

\columnbreak

<div style="margin-top:12.5mm;"></div>

##### Church Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Curtains across path | Entanglement |
| 2 | Stairway | Uneven Ground |
| 3 | Pews | Obstacles |
| 4 | Narrow hallway | Cramped space |
| 5 | Highly polished floor | Hazard |
| 6 | Smoke filled room | Poor visibility |
| 7 | Chimes across path | Entanglement |
| 8 | Railing across path | Hazard |
| 9 | Balcony to climb | Barrier |
| 10 | Loose rugs on floor | Impediment |
| 11-20 | No Complication | &mdash; |

##### City Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Alleyway | Cramped space |
| 2 | Bridge | Hazard |
| 3 | Crowd | Crowd |
| 4 | Dangling Things | Entanglement |
| 5 | Market | Cramped space |
| 6 | Fence or wall across path | Barrier |
| 7 | Garden | Impediment |
| 8 | Large Animals | Animal herd |
| 9 | Rooftop | Hazard |
| 10 | Stables | Impediment |
| 11-20 | No Complication | &mdash; |

##### Desert Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Dunes | Uneven Ground |
| 2 | Oasis | Impediment |
| 3 | Quicksand | Hazard |
| 4 | River bed | Impediment |
| 5 | Whirlwind | Impediment |
| 6 | Cliff | Barrier |
| 7 | Steep grade | Uneven Ground |
| 8 | Cactus patch | Impediment |
| 9 | Rocky Ground | Obstacles |
| 10 | Crevice | Hazard |
| 11-20 | No Complication | &mdash; |

##### Dungeon Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Pit | Hazard |
| 2 | Stairs up | Uneven Ground |
| 3 | Stairs down | Uneven Ground |
| 4 | Coffins | Obstacles |
| 5 | Rubble | Impediment |
| 6 | Columns or Statues | Cramped space |
| 7 | Slime covered floor | Hazard |
| 8 | Natural cavern | Impediment |
| 9 | Torture chamber | Impediment |
| 10 | Chains across path | Entanglement |
| 11-20 | No Complication | &mdash; |

\pagebreakNum

<div style="margin-top:2mm;"></div>

##### Forest Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Log bridge crossing a stream | Hazard |
| 2 | Heavily forested | Cramped space |
| 3 | Dense brush | Poor visibility |
| 4 | Thick hedges | Barrier |
| 5 | Fallen tree | Impediment |
| 6 | Vines across path | Entanglement |
| 7 | The trail suddenly drops off | Impediment |
| 8 | Panicked monkeys | Impediment |
| 9 | 2ft tall ferns obscuring path | Hazard |
| 10 | Thorn bushes | Impediment |
| 11-20 | No Complication | &mdash; |

##### Graveyard Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Open grave | Hazard |
| 2 | Low fence | Hazard |
| 3 | High fence | Barrier |
| 4 | Loose dirt | Impediment |
| 5 | Tombstones | Cramped space |
| 6 | Crypt | Impediment |
| 7 | Coffin | Impediment |
| 8 | Funeral Coach | Impediment |
| 9 | Funeral procession | Crowd |
| 10 | Vine covered graves | Entanglement |
| 11-20 | No Complication | &mdash; |

##### Indoor Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Narrow hallway | Cramped space |
| 2 | Stairs | Uneven Ground |
| 3 | Dining or sales area | Obstacles |
| 4 | Curtains or beads across path | Entanglement |
| 5 | Littered floor | Impediment |
| 6 | Jump off balcony | Hazard |
| 7 | Jump through window | Hazard |
| 8 | Kitchen | Impediment |
| 9 | Slippery floors | Hazard |
| 10 | Hole in floor | Hazard |
| 11-20 | No Complication | &mdash; |

##### Mountain Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Crevice | Hazard |
| 2 | Steep incline | Hazard |
| 3 | Path narrows | Cramped space |
| 4 | Blind Corner | Poor visibility |
| 5 | Cliff | Barrier |
| 6 | Flock of birds | Impediment |
| 7 | Vines crossing path | Entanglement |
| 8 | Mountain goats | Animal herd |
| 9 | Field of boulders | Obstacles |
| 10 | Log bridge across chasm | Hazard |
| 11-20 | No Complication | &mdash; |

\columnbreak

<div style="margin-top:2mm;"></div>

##### Ocean Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Coral maze | Hazard |
| 2 | School of dolphins | Animal herd |
| 3 | Kelp beds | Entanglement |
| 4 | Narrow strait | Cramped space |
| 5 | Precipitation | Poor visibility |
| 6 | Reef | Hazard |
| 7 | Swell | Uneven Ground |
| 8 | Flotsam | Impediment |
| 9 | Fishing nets | Entanglement |
| 10 | School of sea turtles | Obstacles |
| 11-20 | No Complication | &mdash; |

##### Swamp Complications

| 1d20 | Complication | Type |
|:---|:---:|:---:|
| 1 | Quicksand | Hazard |
| 2 | Thick Vegetation | Cramped space |
| 3 | Muck & Mire | Impediment |
| 4 | Insect swarm | Poor visibility |
| 5 | Shallow water | Hazard |
| 6 | Deep Water | Barrier |
| 7 | Vines crossing path | Entanglement |
| 8 | Lots of alligators | Animal herd |
| 9 | Slick, algae covered ground | Hazard |
| 10 | Fallen logs | Impediment |
| 11-20 | No Complication | &mdash; |

\pagebreakNum

# Chapter 3: Modified Official Races

The races found in the Players Handbook are available for PCs. Races mentioned in this chapter have either changes or additions to them. In the case of changes, players must use the version presented here.

The following races are modified from their official presentation. They are Dragonborn, Elves, Half-elves, Air and Earth Genasi, Goliath, Kenku, Revenant, Tabaxi, and Tiefling. Other races are found in Gaia. They are detailed in the sources listed in New Races.

## Dragonborn

Your draconic heritage manifests in a variety of traits you share with other dragonborn.

**Ability Score Increase.** Your Strength score increases by 2, and your Charisma increases by 1.

**Age.** Young dragonborn grow quickly. They walk hours after hatching, attain the size and development of a 10 year-old human child by the age of 3, and reach adulthood by 15. They live to be around 80.

**Alignment.** Dragonborn are usually lawful but tend to extremes of morality, making a conscious choice for one side or the other in the cosmic war between good and evil.

**Size.** Dragonborn are taller and heavier than humans, standing well over 6 feet tall and averaging almost 250 pounds. Your size is Medium.

**Speed.** Your base walking speed is 30 feet.

**Draconic Ancestry.** Choose one type of dragon from the Draconic Ancestry table, which influences your other racial features as shown. If a racial feature requires a saving throw, the DC is (8 + your Charisma or Constitution modifier + your proficiency bonus).

| **Dragon** | **Damage Type** | **Lair Heritage** | **Breath Shape (Save)** |
|:--|:--|:--|:--|
| Black | Acid | Amphibious | Line (Dexterity) |
| Blue | Lightning | Darkvision | Line (Dexterity) |
| Brass | Fire | Darkvision | Line (Dexterity) |
| Bronze | Lightning | Amphibious | Line (Dexterity) |
| Copper | Acid | High-Dweller | Line (Dexterity) |
| Gold | Fire | Amphibious | Cone (Dexterity) |
| Green | Poison | Amphibious | Cone (Constitution) |
| Red | Fire | High-Dweller | Cone (Dexterity) |
| Silver | Cold | High-Dweller | Cone (Constitution) |
| White | Cold | Darkvision | Cone (Constitution) |

**Draconic Resistance.** You have resistance to the damage type associated with your draconic ancestry.

**Lair Heritage.** You have the feature associated with your draconic ancestry:

* *Amphibious.* You can breathe both air and water, and gain a swimming speed of 30 feet.
* *Darkvision.* You can see in dim light as if it were bright light out to 60 feet, and in darkness as if it were dim light.
* *High-Dweller.* You gain proficiency in the Athletics skill, and a climbing speed of 30 feet.

**Natural Armor:** A Dragonborn's Natural Armor grants an Unarmored AC of 13 + Dexterity Modifier. [January 2016's Sage Advice](https://dnd.wizards.com/articles/features/rules-answers-january-2016) goes into rulings on how AC is calculated. Treat this Natural Armor as a **Racial** Draconic Resilience, for intents and purposes.

**Ore-breaker Claws.** Your claws are natural weapons, which you can use to make unarmed strikes. If you hit with them, you deal slashing damage equal to 1d4 + your Strength modifier, instead of the normal bludgeoning damage for an unarmed strike. Additionally, you can use your claws as a tool for the purpose of harvesting ore and digging.

**Languages.** You can speak, read, and write Common and Draconic.

**Subrace.** The draconic blood of the dragonborn expresses itself in a number of ways. Choose one of these subraces.

##### Elemental Dragonborn

You have developed the famed elemental breath of the dragons. Often, such dragonborn bear throat-wattles or colored crests, or crackle with primordial power.

\columnbreak

<div style="margin-top:2mm;"></div>

**Dragon Breath.** You can use an bonus action to exhale energy in the form of a 20 foot cone, or a 5 foot wide and 40 feet long line. Every creature in this area makes a saving throw. If you can attack multiple times during the Attack action, you may use your breath weapon as one of these attacks. 

A creature takes 3d6 damage on a failed save, and half as much damage on success. The damage increases by 1d6 when you reach 5th level (4d6), 11th level (5d6), and 17th level (6d6).

Your draconic ancestry determines the shape, damage type, and saving throw of your breath weapon. You may use your Dragon Breath per short rest equal to once at 1<sup>st</sup>, twice from 5<sup>th</sup>, three times from 11<sup>th</sup>, and four times from 17<sup>th</sup>.

##### Fearsome Dragonborn

You carry within yourself the terrible presence of the dragons, to be unleashed in a dreadful outcry. Such dragonborn are often horned, or have eyes that burn with ancient might.

**Dragon Fear.** You can use a bonus action on your turn to unleash a draconic roar, forcing each creature of your choice that can see or hear you within 30 feet to make a Wisdom saving throw.

Each creature that fails this save becomes frightened of you for 1 minute. A victim can repeat the save at the end of each of its turns, ending the effect on itself if it succeeds.

You may use your Dragon Fear per short rest equal to once at 1<sup>st</sup>, twice from 5<sup>th</sup>, three times from 11<sup>th</sup>, and four times from 17<sup>th</sup>.

##### Shadow Dragonborn

**Ability Score Increase.** Your time in the Plane of Shadows has fundamentally changed you. Instead of the default Ability Score Increase, your Constitution increases by 2, and your Strength increases by 1.

**Size.** Due to their links with the Plane of Shadow, shadow dragonborn weigh less on average than other types of dragonborn.

**Superior Darkvision.** You can see in darkness up to 120ft, you can see in low light conditions as if it were bright light and darkness as if it were dim light. You cannot discern colour in the darkness, just shades of grey.

**Umbral Cloaked.** You have advantage on Stealth Checks made to hide in shadowy areas.

**Shadow Breath.** You have a breath attack as per the above dragonborn, but it deals necrotic damage instead of the damage associated with the draconic ancestry. You also have resistance to necrotic damage.

**Shadeborn.** You are immune to Shadowfell despair, the despair of Hades, and other similar effects.

## Elves and Half-elves

Elf Weapon Training: Elves have additional proficiency with Elven Curve Blades, Elven Double Bows and Greatbows.

Half-elves gain the same Elf Weapon Training as Elves do, as modified by this guide.

## Humans

Humans are a varied race. The PHB Human and Variant Humans are banned. Players wishing to play a human are required to choose one from the following: 
* [Plane Shift: Innistrad](http://www.drivethrurpg.com/product/228654/Plane-Shift-Innistrad),
* [Plane Shift: Dominaria](https://media.wizards.com/2018/downloads/magic/Plane_Shift_Dominaria.pdf),
* or the following subrace.

##### Human, Dark

* **Ability modifiers.** Your Dexterity Score increases by 2, and your Wisdom Score increases by 1
* **Stealthy.** You gain proficiency with Stealth Checks.
* **Fleet of Foot.** Your base walking speed is 40 feet.
* **Superior Darkvision.** Your Darkvision has a radius of 120 feet.
* **Sunlight Sensitivity.** You have disadvantage on attack rolls and on Wisdom (Perception) checks that rely on sight when you, the target of your attack, or whatever you are trying to perceive is in direct sunlight.

\pagebreakNum

<div style="margin-top:2mm;"></div>

* **Always Hidden.** You can attempt to hide even while you are being observed (except in natural daylight, the area of a *daylight spell*, or similar).

___
All humans also gain the following feature:

* **Human Determination.** You are filled with determination. If you fail an attack roll, ability check, or saving throw, you can reroll one d20. You must keep the new result. After you use Human Determination, you can't use it again until you complete a short or long rest.

## Genasi

### Air Genasi

* **Mingle with the Wind.** You know the *gust* (Elemental Evil) cantrip. You can cast the levitate spell once with this trait, requiring no material components, and you regain the ability to cast it this way when you finish a long rest. Constitution is your spellcasting ability for this spell.
* **Whisper on the Breeze.** You can subtly guide the wind currents to better eavesdrop on distant or whispered words. You gain advantage on Wisdom (Perception) rolls to understand voices you can hear as long as air can freely flow between you and the speakers.

### Earth Genasi

* **Merge with Stone.** You know the mold earth (EE) cantrip. Once you reach 3rd level, you can cast the earth tremor (EE) spell once with this trait as a 1<sup>st</sup> level spell, and you regain the ability to cast it this way when you finish a long rest. Constitution is your spellcasting ability for these spells.
* **Stand Your Ground.** You gain advantage Strength saving throws and ability checks to resist being shoved, knocked prone, or otherwise moved against your will while standing on stone, soil, brick, sand, or other forms of earth.
* **Underworld's Secrets.** You gain advantage on rolls to find hidden spaces and passages in caves.

## Gith

* **Speed.** Your base walking speed is 40 feet.
* **Darkvision.** Gith have Darkvision and can see perfectly in all matters of darkness including magical darkness within 60 ft.
* **Subrace.** Githzerai are changed as follows:
    * **Mental Discipline.** Changed name back to UA's **Monastic Training**, but combines both **Monastic Training** and **Mental Discipline**.

## Goliath

Goliath are changed to have the following abilities.

* **Ability Score Increase.** Your Strength score increases by 2.
* **Age.** Goliaths have lifespans comparable to humans. They enter adulthood in their late teens and usually live less than a century.
* **Alignment.** Goliath society, with its clear roles and tasks, has a strong lawful bent. The Goliath sense of fairness, balanced with an emphasis on self-sufficiency and personal accountability, pushes them toward neutrality.
* **Size.** Goliaths are between 7 and 8 feet tall and weigh between 280 and 340 pounds. Your size is Medium.
* **Speed.** Your base walking speed is 35 feet.
* **Powerful Build.** You count as one size larger when determining your carrying capacity and the weight you can push, drag, or lift.
* **Giant Grip.** You may wield weapons with the Buster property without the inherent disadvantage.
* **Half-Giant Vigor.** Your hit point maximum increases by 4, and it increases by 4 every time you gain a level.
* **Natural Athlete.** You have proficiency in the Athletics skill.
* **Languages.** You can speak, read, and write Common and Giant.
* **Subrace.** Six subraces of Goliaths exist in the Adventures of Gaia Campaign Setting. Choose one of these subraces.

\columnbreak

<div style="margin-top:2mm;"></div>

##### Adian (Storm Goliath)

The Adian (also known as Storm Goliaths) are a coastal people they descend from Storm Giants of the Helencean Ocean.

* **Ability Score Increase.** Your Charisma score increases by 1.
* **Amphibious.** You can breath air and water.
* **Hurl Lightning.** You can use your action to throw a bolt of lightning to an area within 30 ft. When you hurl lightning, each creature within a 5ft. radius of the bolt must make a Dexterity saving throw. The DC for this saving throw equals 8 + your Charisma modifier + your proficiency bonus. A creature takes 2d8 lightning damage on a failed save. and half as much damage on a successful one. The damage increases to 3d8 at 6<sup>th</sup> level, 4d8 at 11th level, and 5d8 at 16<sup>th</sup> level. After you use your Hurl Lightning, you can't use it again until you complete a short or long rest.

##### Cindri (Fire Goliath)

Workers of the forge the Cindri have no time for idle things like religion or tradition. they have a need to better themselves and the futures of their people. the tend to not get along well with the other races layered in tradition or laziness this includes the fire giants whom they descend from.

* **Ability Score Increase.** Your Strength score increases by an additional 1 up to a maximum of 20.
* **Forged in Fire.** You have resistance to fire damage.
* **Skilled Craftsmen.** You gain proficiency in smith tools. In addition you chose two martial weapons you gain proficiency in those weapons. You have exceptional skill at crafting those weapons and can craft four of them for the price of one over the course of 8 hours of work at a forge.

##### Hrim (Frost Goliath)

The Hrim have lineage traced back to frost giant jarls and the hold them selves to higher standards than there giant forebearers. talented warriors and raiders the Hrim are fiercely loyal and don't deal in deceptions the strong lead and the weak are made strong.

* **Ability Score Increase.** Your Dexterity score increases by 1.
* **Hrim Combat and Equipment Training.** You have proficiency with the battleaxe, handaxe, greataxe, and spear. You have proficiency with light armor and shields.
* **Winters Warmth.** You have resistance to cold damage.

##### Shale (Stone Goliath)

These Goliaths trace there lineage to the Spirepeak Mountain tribes of stone giants. They are a tribal people who hold the power of dreams in high regard.

* **Ability Score Increase.** Your Wisdom score increases by 1.
* **Mountain Born.** You’re acclimated to high altitude, including elevations above 20,000 feet. You’re also naturally adapted to cold climates, as described in chapter 5 of the Dungeon Master’s Guide.
* **Stone’s Endurance.** You can focus yourself to occasionally shrug off injury. When you take damage, you can use your reaction to roll a d12. Add your Constitution modifier to the number rolled, and reduce the damage by that total. After you use this trait, you can’t use it again until you finish a short or long rest.

##### Yilk (Hill Goliath)

The gluttonous and violent Yilk are descendants of hill giants and the two share a similar demeanor. they tend to conquer and enslave small settlements and feast until they deplete local food stores then move on.

* **Ability Score Increase.** Your Constitution score increases by 1.
* **Thriving Hunger.** You may spend a short rest eating, doing so you gain 1d4 + constitution modifier temporary hit points until your next short rest. the temporary hit points changes to 1d6 at 6<sup>th</sup> level, 1d8 at 11th level, and 1d10 at 16<sup>th</sup> level.
* **Hearty Girth.** Your hit point maximum increases by 1, and it increases by 1 every time you gain a level.

\pagebreakNum

<div style="margin-top:2mm;"></div>

##### Zeph (Cloud Goliath)

The Zeph are descended from the cloud giants who occupy the Incarian marsh lands, and are commonly found among the ruins of the Fallen Palace Zhakilan.

* **Ability Score Increase.** Your Intelligence score increases by 1.
* **Keen Smell.** You have advantage on Wisdom (perception) checks that rely on smell.
* **Cloud Casting.** You know the light cantrip. Once you reach 3rd level, you can cast the fog cloud spell once per day as a 2nd-level spell. Once you reach 5th level, you can also cast the misty step spell once per day. Intelligence is your spellcasting ability for these spells.

## Kenku / Tengu

Kenku do not exist in my campaign. Instead, you may use their traits, with the following modifications, to play as Tengu, which are unburdened by the curse of the Unknown Master.

* **Ability Score Increase.** Your Dexterity and Wisdom scores each increase by 2.
* **Age.** Tengu mature faster, yet have longer lifespans than humans. They reach maturity at about 10 years old and can live to 160.
* **Speed.** 40ft.
* **Darkvision.** Maneuvering in darkness is hardly difficult for Tengu. Within 60 feet of you, treat dim light as if it were bright light and darkness as dim light. When in darkness, you see only shades of grey without any color.
* **Tengu Training.** You are proficient in your choice of one of the following skills: Acrobatics, Deception, Stealth, and Sleight of Hand. You are also proficient with the Perception skill.
* **Combat Training** You are proficient with any sword like weapon, that possess the Light or Finesse traits, such as daggers, rapiers, and short swords.
* **Languages** You can speak, read and write Common, Auran and an additional one of your choice.

## Revenant

* **Darkvision.** Revenant now grant the base race Darkvision 60ft. If the base race already has Darkvision, it extends it 30ft.

## Tabaxi Subraces

Whether a hardy snow leopard or an agile panther, players can now create more flavorful Tabaxi to adventure with in their games.

These Tabaxi subraces are intended to bring more excitement to Tabaxi players, allowing them to create a Tabaxi character flavored more closely to real-world feline equivalents such as lions, snow leopards or domestic urban cats, for a few examples. The Tabaxi as known in *Volo's Guide to Monsters* is still available for players to use by simply choosing Jungle Tabaxi as their Subrace. The original Tabaxi traits, Feline Agility and Cat's Talent have been moved to Jungle Tabaxi, while other traits have been assigned to the remaining six Tabaxi subraces as seen below.

##### Tabaxi Traits

Your Tabaxi character has the following racial traits.

* **Ability Score Increase.** Your Dexterity score increases by 2.
* **Age.** Tabaxi have lifespans equivalent to humans.
* **Alignment.** Tabaxi tend toward chaotic alignments.
* **Size.** Tabaxi are taller on average than humans and relatively slender. Your size is Medium.
* **Speed.** Your base walking speed is 40 feet.
* **Darkvision.** You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can't discern color in darkness, only shades of gray.
* **Cat's Claws.** Because of your claws, you have a climbing speed of 30 feet. In addition, your claws are natural weapons, which you can use to make unarmed strikes. If you hit with them, you deal slashing damage equal to 1d4 + your Strength or Dexterity modifier, instead of the bludgeoning damage normal for an unarmed strike. This can be increased by a Monk's Martial Arts die.
* **Tabaxi Weapon Training.** You are proficient with Battle Claws. If you are using a class feature that specifies a type of weapon, a Tabaxi may use these instead.

\columnbreak

<div style="margin-top:2mm;"></div>

* **Catfall.** When you are falling you may make a Dexterity saving throw. If you succeed you take no damage and are not prone, if you fail you take half damage and you are prone. The Save DC for this Saving Throw is 10 + half the damage dice incurred. For example, if the Tabaxi falls enough to incur 20d6 damage, the DC is 20 (10 + 20/2). If they fail, they instead take 10d6 damage.
* **Languages.** You can speak, read, and write Common, Tabaxi and one other language of your choice.
* **Subrace.** Seven main subraces of Tabaxi are presented herein: Arctic, Grassland, Jungle, Mountain, Savannah, Shadow, or Urban Tabaxi. Choose one of these subraces.

##### Arctic Tabaxi

* **Ability Score Increase.** Your Constitution score increases by 1.
* **Triple Layer Coat.** You have resistance to cold damage. You are also naturally adapted to cold climates, as described in chapter 5 of the Dungeon Master’s Guide.
* **Snow Pads.** Snow and ice does not count as difficult terrain for you. Additionally, you have advantage on Dexterity (Stealth) checks made to Hide in snow or while it is snowing.

##### Grassland Tabaxi

* **Ability Score Increase.** Your Wisdom score increases by 1.
* **Friend of Critters.** Through sounds and gestures, you can communicate simple ideas with Small or smaller beasts.
* **Prairie Lookout.** You have proficiency in the Perception and Investigation skills.

##### Jungle Tabaxi

* **Ability Score Increase.** Your Charisma score increases by 1.
* **Feline Agility.** Your reflexes and agility allow you to move with a burst of speed. When you move on your turn in combat, you can double your speed until the end of the turn. Once you use this trait, you can't use it again until you move 0 feet on one of your turns.
* **Cat's Talent.** You have proficiency in the Perception and Stealth skills.

##### Mountain Tabaxi

* **Ability Score Increase.** Your Strength score increases by 1.
* **Mountain Reign.** You’re acclimated to high altitude, including elevations above 20,000 feet. You’re also naturally adapted to cold climates, as described in chapter 5 of the Dungeon Master’s Guide.
* **Fortitude of the Peaks.** Your hit point maximum increases by 1, and it increases by 1 every time you gain a level.

##### Savannah Tabaxi

* **Ability Score Increase.** Your Strength score increases by 1.
* **Nine Lives.** When you are reduced to 0 hit points but not killed outright, you can drop to 1 hit point instead. You can't use this feature again until you finish a long rest.
* **Regal Presence.** You have proficiency in the Intimidation and Persuasion skills.

##### Shadow Tabaxi

* **Ability Score Increase.** Your Intelligence score increases by 1.
* **Cantrip.** You know one cantrip of your choice from the Wizard spell list. Intelligence is your spellcasting ability for it.
* **Dark Omen.** You have proficiency in the Stealth skill. Additionally, your Darkvision extends to a range of 120 feet.

##### Urban Tabaxi

* **Ability Score Increase.** Your Charisma score increases by 1.
* **Size.** Urban Tabaxi are smaller than their more wild counterparts. Your Size is Small.
* **Nimble Feline.** You can move through the space of any creature that is of a size larger than yours.
* **Curious Learner.** You gain proficiency in one skill of your choice.

\pagebreakNum

<div style="margin-top:2mm;"></div>

## Tiefling

Base race is described in the PHB. You may also use Sword Coast Adventurers Guide (SCAG) or Mordenkainen's Tome of Foes (MToF) Fiendish Options variants as well. The abilities following are additional variant sub-races.

* **Asura-Spawn (Faultspawn)**
    * Dex +2, Wis +1
    * Cantrip &mdash; *Friendship*
    * at Level 3, cast as 2nd level &mdash; *Hideous Laughter*
    * at Level 5 &mdash; *Enthrall*
* **Daemon-Spawn (Grimspawn)**
    * Dex +2, Int +1
    * Cantrip &mdash; *Chill Touch*
    * at Level 3, cast as 2nd level &mdash; *False life*
    * at Level 5 &mdash; *Ray of Enfeeblement*
* **Demodand-Spawn (Foulspawn)**
    * Con +2, Wis +1
    * at Level 5 &mdash; *Barkskin*
* Kyton-Spawn (Shackleborn)
    * Cha +2, Con +1
    * Cantrip &mdash; *Mage Hand*
    * at Level 3, cast as 2nd level &mdash; *Entangle*
    * at Level 5 &mdash; *Web*
* **Devil-Spawn (Hellspawn)**
    * Con +2, Cha +1
    * Cantrip &mdash; *Dancing Lights*
    * at Level 5 &mdash; *Scorching Ray*
* **Rakshasa-Spawn (Beastbrood)**
    * Dex +2, Cha +1
    * Cantrip &mdash; *True Strike*
    * at Level 3, cast as 2nd level &mdash; *Detect Magic*
    * at Level 5 &mdash; *Detect Thoughts*
* **Qlippoth-Spawn (the Motherless)**
    * Wis +2, Str +1
    * Cantrip &mdash; *Minor illusion*
    * at Level 3, cast as 2nd level &mdash; *Disguise Self*
    * at Level 5 &mdash; *Blur*
* **Demon-Spawn (Pitborn)**
    * Cha +2, Str +1
    * at Level 5 &mdash; *Shatter*
* **Whipspawn (Thornborn)**
    * Dex +2, Cha +1
    * Cantrip &mdash; *Thorn Whip*
    * at Level 3, cast as 2nd level &mdash; *Ensnaring Strike*
    * at level 5 &mdash; *Alter Self*
* **Oni-Spawn (Hungerseed)**
    * Str +2, Wis +1
    * at Level 3, cast as 2nd level &mdash; *Longstrider*
    * at Level 5 &mdash; *Alter Self*

## Warforged

Base race is described in the Wayfinder's Guide to Eberron. Changes are Warforged Druids may Wild Shape into either:

1. biological flesh-and-bone creatures, and follow [Keith Baker's Sage Advice](https://www.sageadvice.eu/2018/09/12/if-a-warforged-druid-wildshapes-do-they-wildshape-into-an-entirely-organic-creature/) RAW Ruling (a Warforged druid wildshapes into an organic creature and receives no benefit from Integrated Protection while wildshaped), **OR**
2. mechanical beasts with Warforged bodies, gaining the benefit of the Warforged's Integrated Protection while wildshaped, but must make BeastWars references when doing so.

\pagebreakNum

# Chapter 4: New Races

The following races Cait Sith, Burmecian, Mul, & Selkies are a part of this campaign, and are available to PCs as racial options.

<div class="classTable wide" style="margin-top:3mm;border-bottom:1px solid #000;">

| **Race** | **STR** | **DEX** | **CON** | **INT** | **WIS** | **CHA** | **Speed** | **Traits** |
|:--|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--|
| Cait Sith | &mdash; | +2 | &mdash; | &mdash; | &mdash; | +1 | 25ft | Lucky, Brave, Cait Sith Nimbleness |
| &nbsp;&nbsp;&nbsp;&nbsp; *Pooka*| &mdash; | &mdash; | &mdash; | &mdash; | &mdash; | &mdash; | &mdash; | *+5ft* | *Fleet of Foot* |
| &nbsp;&nbsp;&nbsp;&nbsp; *Moogle* | &mdash; | &mdash; | &mdash; | &mdash; | &mdash; | &mdash; | &mdash; | *Flight 40ft* |
| Burmecian | &mdash; | +2 | &mdash; | &mdash; | &mdash; | &mdash; | 40ft | City Rat, Daughters of War, I Have An Ear For This |
| &nbsp;&nbsp;&nbsp;&nbsp; *Burm*| &mdash; | &mdash; | &mdash; | &mdash; | &mdash; | *+1* | &mdash; | *After Your Heart, Battle Charm* |
| &nbsp;&nbsp;&nbsp;&nbsp; *Cleyra* | &mdash; | &mdash; | &mdash; | &mdash; | *+1* | &mdash; | &mdash; | *Dance of Politicians, Relaxed Recovery* |
| Mul | +2 | &mdash; | +1 | &mdash; | &mdash; | &mdash; | 30ft | Darkvision 30ft, Keen Senses, Dwarven Toughness,</br>Inexhaustible, Relentless Endurance, Untiring |
| Selkie | &mdash; | +2 | &mdash; | &mdash; | &mdash; | &mdash; | 35ft | Animal Commune, Keen senses, Mask of the Wild,</br>Selkie Weapon Training, Selkish Script |
| &nbsp;&nbsp;&nbsp;&nbsp; *Lynarian</br>&nbsp;&nbsp;&nbsp;&nbsp;Nomad*|  &mdash; | &mdash; | &mdash; | *+1* | &mdash; | &mdash; | &mdash; | *Desert Walker* |
| &nbsp;&nbsp;&nbsp;&nbsp; *City</br>&nbsp;&nbsp;&nbsp;&nbsp;Wanderer* | &mdash; | &mdash; | &mdash; | &mdash; | &mdash; | *+1* | &mdash; | *Street Smart* |
| Vryloka | &mdash; | +1 | &mdash; | &mdash; | &mdash; | +2 | 40ft | Darkvision 60ft, Human Heritage, Bloodsurge,</br>Living Dead, Necrotic Resistance, Red Ledger |

</div>

<div class="wide" style="margin-top:-8mm;margin-bottom:-10mm">

<img src='https://drive.google.com/uc?id=16HXO8oMwxdA1NT2eP9Met-feP1jO0k_1' style="width:100%">

</div>

</br>

## Cait Sith

<div style="text-align:right">

*These mysterious beings tend to flock around humans, closer to man than beast. They communicate via their communications network, Mognet, while their distinctive cry of "Kupo!" and fluffy appearance endear them to all.*

&mdash; ***Guidebook to Nexus Prime***

</div>

Cait Sith are a pair of family clans, that work together to restore their heritage via their separate means. The Pooka are the Warrior clan, whereas the Moogle are the Support clan. Pooka make nimble Fighters, Rogues or Rangers, whereas Moogle generally become Engineers, as they are able to deftly evade the explosions of their mishaps.

#### Traits

* **Ability modifiers.** Your Dexterity Score increases by 2, and your Charisma Score increases by 1.
* **Age.** A Cait Sith reaches adulthood at the age of 20 and generally lives into the middle of his or her second century.

\columnbreak

<div style="margin-top:12mm;"></div>

* **Alignment.** Most Cait Sith are lawful good. As a rule, they are good-hearted and kind, hate to see others in pain, and have no tolerance for oppression. They are also very orderly and traditional, leaning heavily on the support of their community and the comfort of their old ways.
* **Size.** Cait Sith average about 3 feet tall and weigh about 40 pounds. Your size is Small.
* **Speed.** Your base walking speed is 25 feet.
* **Lucky.** When you roll a 1 on an attack roll, ability check, or saving throw, you can reroll the die and must use the new roll.
* **Brave.** You have advantage on saving throws against being frightened.
* **Cait Sith Nimbleness.** You can move through the space of any creature that is of a size larger than yours.

\pagebreakNum

<div style="margin-top:2mm;"></div>

* **Languages.** You can speak, read, and write Common and Cait. The Cait language isn't secret, but Cait Sith are loath to share it with others. They write very little, so they don't have a rich body of literature. Their oral tradition, however, is very strong. Almost all Cait Sith speak Common to converse with the people in whose lands they dwell or through which they are traveling.
* **Sub-races.** The two main kinds of Cait Sith, Pooka and Moogle, are more like closely related families than true sub-races. Choose one of these sub-races.

##### Pooka

* **Fleet of Foot.** Your base walking speed increases to 30 feet.

##### Moogle

* **Flight.** You have a flying speed of 40 feet. To use this speed, you can't be wearing medium or heavy armor, or carrying a heavy load.

## Burmecian

The Burmecian's are a fairly middle aged race of humanoid rat people whom had found their callings in the art of warfare. Having found solace in the fun and entertainment of combat, the noble Burmecian's preferred to play with their opponents during combat.

Many whom have found a battle ground opposite of these agile fighters live to speak of their entrancing flirtatious attitudes that would glow brighter as the heat of combat grew tense. It was enough to garner victory out of the pure confusion or rage that it would bring out of their opponents.

**Physical Appearance.** A Burmecian is most typically an anthropomorphic rat like bipedal humanoid. They bare a rat like face with some human qualities, hair, full body fur (typically either grey, white or light brown), clawed feet and functional humanoid hands with functional thumbs.

#### Traits

Burmecian's share a few common traits with one another.

* **Ability modifiers.** Your Dexterity Score increases by 2.
* **Age.** Burmecian's live the average lifespan of humans; but tend to grow frailer in old age.
* **Alignment.** Burmecian's have grown fond of the theater of war over their decades of grooming into the life style of some of the realms most agile warriors. They tend to lend themselves to the life of war and Neutrality unless a cause has taken their true interest. Cleyran Burmecian's lean more on the Good end of the scale.
* **Size.** Burmecian's tend to be on the slender type of body frame, and grow to anywhere between 5 feet and 7 feet with an average body weight of 120&mdash;190 lbs. for males and 90&mdash;130 lbs. for females. Your size is Medium.
* **Speed.** Your base walking speed is 40 feet.
* **City Rat.** You have proficiency in Survival. You also have advantage on Perception or Survival checks when searching for shelter in cities and towns.
* **Daughters of War.** You have proficiency in 3 Martial Weapons of your choice. You also have proficiency in light armor and shields.
* **I Have An Ear For This.** You have the *Animal Friendship* (**SRD**, pg *115*) spell. You may use this once per long rest and only as a 1<sup>st</sup> level spell.
* **Languages.** Burmecian's can read, write and understand Common and Burmecian (Variant: One Exotic Language)
* **Sub-races.** The Burmecian's rocky past has lead this race to pursuing two very different paths in life.

##### Burm

The Burms, or simply the Burmecian's who had remained infatuated with their combat ideals. They are some of the most playful fighters the realm has seen; brandishing smiles and a powerfully charming flirtatious attitude when engaged in combat.

* **Ability Score Increase.** Your Charisma score increases by 1.
* **After Your Heart.** Burms may use their Dexterity Modifier in place of their Strength Modifier for Athletics checks.
* **Battle Charm.** Take advantage on Charisma saving throws, as well as Intimidation, Persuasion, and Deception checks while you or the party is engaged in combat.

\columnbreak

<div style="margin-top:2mm;"></div>

##### Cleyran

The Cleyran are Burmecian's whom found fault in the war-born ways and retreated for the desert in search of wisdom and enlightenment. A great sandstorm has veiled them from their battle-born kin for over a century.

* **Ability Score Increase.** Your Wisdom score increases by 1.
* **Dance of Politicians.** You may use your Wisdom Modifier in place of your Charisma Modifier on Persuasion checks.
* **Relaxed Recovery.** Once per *short rest*, when using Hit Dice to restore health, if you roll a 1 or 2, you may reroll but you must take the new result.

## Mul

Muls are half-dwarves, descended from the union of a human and a dwarf. They have the stature, agility, and mental flexibility of humankind, coupled with the physical resilience and endurance of dwarves, a rare combination of qualities that makes Muls more than a simple blend of the two races.

Because they are strong, tough, quick, and blessed with fantastic endurance, Muls are highly prized as slaves. In fact, most Muls are born into slavery.

#### Traits

Mul share a few common traits with one another.

* **Ability modifiers.** Your Strength score increases by 2, and your Constitution score increases by 2.
* **Age.** Mul age at the same rate as humans but live up to 130 years and suffer few ill effects of old age.
* **Alignment.** Mul are as variable in their attitudes to the world as their parentage but nonetheless tend towards lawful alignments.
* **Size.** Muls stand between 5 and a half feet and 7 feet tall and average between 250 and 300 pounds. Muls have truly heroic proportions--broad shoulders, narrow waists, powerful thighs, and thick arms. Your size is Medium.
* **Speed.** Your base land speed is 30 feet. Your speed is not reduced by wearing heavy armor.
* **Mul Vitality.** When you roll a hit die to regain health, you regain additional hit points equal to your proficiency bonus.
* **Tireless.** You may forgo sleep for up to 72 hours without suffering any ill effects. Additionally, when you enjoy a long rest you may remove up to two levels of exhaustion instead of one.
* **Incredible Toughness.** You can call upon your physical hardiness and dogged determination to withstand any danger or hazard. Using your reaction you can have advantage on a Strength or Constitution saving throw. After you use this trait, you can't use it again until you finish a short or long rest.
* **Tools of Trade and War.** You have proficiency with the whip, warpick, and net.
* **Languages.** Muls can read, write and understand Common and Dwarven.

## Selkies

Selkies are a nomadic people who value independence, self-reliance, and freedom above all else. They have the least amount of group cohesion of all races in the world. Their frequently selfish behavior has caused them to be looked down upon with scorn and mistrust.

Discrimination has forced many of them to make their living as thieves, and they typically end up as criminals. Selkies are some of the less common kinds of people in the world today, their numbers far lower than other major races. Clearly they must have enough capabilities about them to persist to the present day.

**Physical Appearance.** The Selkies are a swift and acrobatic race that shares many physical similarities with half-elves. Selkie males and females have long hair and more lithe forms than humans or elves. Skin tone also varies widely, though many who hail from the deserts are darker toned than most humans.

While most races can tell apart similar-looking humans and Selkies through subtle cues, it's not unheard of for them to be confused. Selkies are said to ``have a wild look'' and a slightly taller posture compared to that of a human. A member of either race disguising as the other isn't especially difficult, unlike attempts at disguising as, say, a Halfling or a Moogle.

\pagebreakNum

<div style="margin-top:2mm;"></div>

**Society and Culture.** Selkies do not have a good reputation among the other races. Many Selkies tend to be selfish and impatient, resorting to thievery rather than other jobs. Selkies gravitate towards professions that require lots of movement and activity.

Selkies have an extremely rich culture that is little known to outsiders from other races. Rituals and traditions are passed on from generation to generation through their large, typically nomadic families. Even mystic scholars cannot easily decipher Selkie history and culture, passed down through Selkic speech and selkic script.

#### Common Selkie Names

**Female.** Roo Jay, Ra Lena, Momo Phi, Tiy Rah, Sala Nah, See Sooy
___
**Male.** Muh Jica, Dah Maat, Giy Em, Gul Toh, De Di, Geck Moo

#### Traits

The agile Selkie tribe can understand animals in ways that other races can't. Perhaps the most unique aspect of the Selkies is their natural language. At about four years of age, all Selkies innately understand selkic script.

Oddly enough, this language seems to alter slightly from generation to generation, making it almost impossible for non-Selkies to translate it. Selkies from new and old generations alike are somehow able to perfectly understand the language no matter from what generation it is from. Some Selkies are unaware that there even is a generational change in selkic script and speech.

* **Ability modifiers.** Your Dexterity Score increases by 2.
* **Age.** Selkies live an average of 95 years.
* **Alignment.** Selkies lack a respect for law outside of the family and are thus more likely than other races to be chaotic.
* **Size.** Selkies stand at an average of 5 &frac12; &mdash; 6 feet and average about 135 pounds. Your size is Medium.
* **Speed.** Your base walking speed is 35 feet.
* **Animal Commune.** In tune with nature, Selkies can communicate basic ideas with animals.
* **Keen senses.** You have proficiency in the Perception skill.
* **Mask of the Wild.** You can attempt to hide even when you are only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena.
* **Selkie Weapon Training.** You gain proficiency with the scimitar, double scimitar, longbow, and shortbow.
* **Languages.** Selkies can read, write and understand Common and Selkic (Variant: One Exotic Language). See next trait.
* **Selkish Script.** You understand and speak selkic, a special language learned innately at birth. The language can be written and spoken. Only Selkies can understand selkic.
* **Sub-races.** Selkies come from a variety of nomadic tribes, though some now reside in the kingdoms of other races.

##### Lynarian Nomads

You can trace your family line to the Lynari Desert, and you've inherited your ancestors' conditioning and resistance to harsh environments.

* **Ability Score Increase.** Your Constitution score increases by 1.
* **Desert Walker.** You are naturally adapted to hot climates, as described in chapter 5 of the Dungeon Master's Guide. You also have proficiency in the Survival skill.

##### City Wanderer

Frequently treated by others as a minority on society's fringe, you learned it takes more than thick skin to earn your keep. Joke's on them&mdash;you've adapted accordingly.

* **Ability Score Increase.** Your Charisma score increases by 1.
* **Street Smart.** You're experienced in influencing people with subtle tricks. Once per long rest you may apply advantage to any deception, persuasion, intimidation or other Charisma-based ability check. You also have proficiency in the Stealth skill.

## Vryloka

**Crimson Origins.** Vrylokas are the result of a dark ritual generations ago that transformed human nobles into living vampires. The identity and goals of the ritual’s creator, a wizard known only as the Red Witch, have remained a mystery.

\columnbreak

<div style="margin-top:2mm;"></div>

The ritual provided the nobles with inhuman vitality and a literal thirst for life without the curse of true undeath. Many years later, these powerful, emotional beings walk the halls of power throughout the land, secretly posing as eccentric human aristocrats from distant kingdoms.

To stave off the occasional boredom of their long lives, many Vrylokas meet in the shadows to plot for power, while others become adventurers. A bold few&mdash;simultaneously fascinated and repulsed by their occult origins&mdash;even become vampire hunters.

**Alluring and Passionate.** Vrylokas have dark gray or blue eyes that turn red when they are angered or excited. Their skin is uniformly pale, ranging from pinkish flesh to chalky white. Most Vrylokas have hair in shades of red, from deep scarlet to strawberry blond.

They possess a beguiling charm, with the females shapely and statuesque and the males tall and imposing. They tend to feel all emotions strongly, whether they’re possessively pursuing a romantic interest or reacting with fury to a perceived slight.

**A Life of Secrets.** Key to a Vryloka's longevity is concealment of their vampiric heritage. They take great care to pass as human whenever possible, and they may change residences and identities to avoid questions about their lack of aging. In addition to keeping secrets, they’ve uncovered many secrets of others, thanks to their long lives and access to the halls of power. Many Vrylokas possess historical knowledge denied to all but the most learned sages.

#### Common Vryloka Names

As human nobles.

#### Traits

* **Ability modifiers.** Your Charisma score increases by 2 and your Dexterity score increases by 1.
* **Age.** Vrylokas mature at the same rate as humans, but the aging process slowly considerably once they reach adulthood, and they retain their vitality until their dying days. A Vryloka can typically live to be 350 years old.
* **Alignment.** Most Vrylokas are lawful, with a strong sense of tradition and rules, which are necessary to preserve a Vryloka's secrets and continued existence. They show no predilection for good or evil, although a Vryloka commonly displays a superior attitude regardless of alignment.
* **Size.** Vryloka stand at an average of 5 &frac12; &mdash; 6 feet and average about 135 pounds. Your size is Medium.
* **Speed.** Your base walking speed is 40 feet.
* **Darkvision.** The taint of vampirism provides superior vision in dark and dim conditions. You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can’t discern color in darkness, only shades of gray.
* **Human Heritage.** You have advantage on Charisma (Deception) checks to pass as human.
* **Bloodsurge.** When a Vryloka reduces an enemy creature to 0 hit points, it can use its Reaction to acquire one of the following benefits; Dash towards the nearest enemy in sight, heal missing hit points equal to one-half your level plus your Charisma modifier, or gain a +1 bonus to attack rolls and damage rolls until the end of its next turn.
* **Living Dead.** Because your soul is tainted by undeath, you are both living and undead. If an ability or spell has different effects on living creatures and undead creatures, you choose which effect applies to you.
* **Necrotic Resistance.** You have resistance against necrotic damage.
* **Red Ledger.** You have proficiency in the History skill.
* **Languages.** You can speak, read, and write Common and one extra language of your choice. Vrylokas who seek to leverage their arcane ancestry learn Draconic, while the more martially inclined often learn the language of an hostile race or group.

\pagebreakNum

# Chapter 5: Class Options

The following are revised Class options and new Class options.

<div class="classTable wide" style="margin-bottom:0mm;margin-top:0mm;border-bottom:1px solid #000;">

| **Class** | **Subclass** | **Changes** |
|:--|:--|:--|
| &nbsp;&nbsp;&nbsp;&nbsp; Bard | &nbsp;&nbsp;&nbsp;&nbsp; *College of Swords* and *College of</br>&nbsp;&nbsp;&nbsp;&nbsp;Valor* | &nbsp;&nbsp;&nbsp;&nbsp; These subclasses are merged into one. See [Revised Bard: Colleges of Swords and Valor](#chapter-5-class-options-revised-bard-colleges-of-swords-and-valor) |
| &nbsp;&nbsp;&nbsp;&nbsp; Fighter | &nbsp;&nbsp;&nbsp;&nbsp; *Champion* | &nbsp;&nbsp;&nbsp;&nbsp; Core feature of Fighters.* |
| &nbsp;&nbsp;&nbsp;&nbsp; Monk | &nbsp;&nbsp;&nbsp;&nbsp; *All* | &nbsp;&nbsp;&nbsp;&nbsp; Monk's Hit Dice are now d10s. |
| &nbsp;&nbsp;&nbsp;&nbsp; Monk | &nbsp;&nbsp;&nbsp;&nbsp; *Way of Four Elements* | &nbsp;&nbsp;&nbsp;&nbsp; [As posted here](https://drive.google.com/open?id=1C1NWq1sKDKXBfyfcdcN-lpYHx4pdZoh2). |
| &nbsp;&nbsp;&nbsp;&nbsp; Monk | &nbsp;&nbsp;&nbsp;&nbsp; *Way of the Kensei* | &nbsp;&nbsp;&nbsp;&nbsp;**Changed: 3rd level. *Path of the Kensei***; **Add: 3rd level. *Second Skin*** |
| &nbsp;&nbsp;&nbsp;&nbsp; Monk | &nbsp;&nbsp;&nbsp;&nbsp; *Way of the Soul Knife* | &nbsp;&nbsp;&nbsp;&nbsp;[As posted here, until further notice](http://mfov.magehandpress.com/2017/12/soul-knife-redux.html). |
| &nbsp;&nbsp;&nbsp;&nbsp; Paladin | &nbsp;&nbsp;&nbsp;&nbsp; *All* | &nbsp;&nbsp;&nbsp;&nbsp;Paladin's Hit Dice are now d12s. |
| &nbsp;&nbsp;&nbsp;&nbsp; Ranger | &nbsp;&nbsp;&nbsp;&nbsp; *All* | &nbsp;&nbsp;&nbsp;&nbsp; See [UA Ranger Revised 2016](https://media.wizards.com/2016/dnd/downloads/UA_RevisedRanger.pdf) and [Changes to UA Ranger Revised 2016](#chapter-5-class-options-ua-ranger-revised-2016-changes). |
| &nbsp;&nbsp;&nbsp;&nbsp; Rogue | &nbsp;&nbsp;&nbsp;&nbsp; *Thief* | &nbsp;&nbsp;&nbsp;&nbsp; *Core feature of Rogues.* |
| &nbsp;&nbsp;&nbsp;&nbsp; [Mage Hand Press &mdash; Free Content](https://store.magehandpress.com/collections/free-products) | &nbsp;&nbsp;&nbsp;&nbsp; *These Products* | &nbsp;&nbsp;&nbsp;&nbsp; All Other Mage Hand Press OR Middle Finger of Vecna Products |

</div>

## Hybrid Classes

At first level, you may choose to progress as a hybrid class character. Once this choice is made, you may never multiclass, can only progress as the two classes chosen, and must abide by the following rules changes.

### Flavor Additions

As a personal rule, I recommend giving your Gestalt Character combination a special name. Since you are playing as a character who learns, or gets stronger at an increased rate, this could manifest itself as a title or nickname within the game.

I recommend using a name which is relevant to the character you wish to roleplay, such as Ninja for Shadow Monk/Rogue, or relevant to the class combination, such as Theurge for Cleric/Wizard.

### Hybrid Class Features

At each level, you gain the following class features:

**Hit Dice.** You get the higher hit dice from both classes.

**HP.** Highest HP from either class.

**Armor.** Proficiency from both classes.

**Weapons.** Proficiency from both classes.

**Tools.** Proficiency from both classes.

**Saving Throws.** Proficiency in three saves; one Common ***(Dex/Con/Wis)*** save that either class uses, one Rare ***(Str/Int/Cha)*** save that either class uses, and one of your choice. For example, if one class has Dex/Str, the other has Wis/Cha. Choose one save from Dex/Wis, one save from Str/Cha, and one of your choice.

**Skills.** You choose your class skills from the combined list of both classes, and you are proficient in three skills plus the average of your two chosen classes, rounded down. For example, If you have chosen to play a Rogue//Fighter hybrid, a 1<sup>st</sup> level rogue is proficient in 4 skills, while a 1<sup>st</sup> level fighter in two.

Therefore, you would have a combined **class** list of ***Acrobatics, Animal Handling, Athletics, Deception, History, Insight, Intimidation, Investigation, Perception, Performance, Persuasion, Sleight of Hand, Stealth, and Survival***, of which you chose **6** to be class skills.

**Equipment.** You get equipment from one of the classes (your choice).

**Class Features.** Except where noted below, you get the class features from both classes.

**Ability Score Increase.** When you gain an ability score increase from both classes at the same level, you only get the increase once for that level.

**Extra Attack.** Your extra attacks do not stack from two separate classes. You instead get the best extra attack progression from your two classes.

### Spell Casting as a Hybrid Class

If you choose to Hybrid Class with one or both choices of class being Spellcasters, the following applies, with an example following this section.

\columnbreak

<div style="margin-bottom:2mm;"></div>

#### Spell Slots
* Full casters (bard, cleric, druid, sorcerer, and wizard) grant full spell slots
* Half casters (paladin) grant &frac12; spell slots
* Third casters (eldritch knight (fighter) or arcane trickster (rogue)) grant &frac13; spell slots

#### Spells Prepared

When preparing spells, refer to page 164 of the PHB, ignoring the multiclass section. This also means that, when you gain a level in a spellcasting class, you will also gain access to cantrips available to that class at that level. Only the spell slots you gain are shared between all spellcasting classes.

#### Spellcasting Ability

If you chose two spellcasting classes, you choose **One** of the two classes ability scores to be your spell casting modifier. Once chosen, this choice is irreversebly.

#### Spellcaster Hybrid Example

A 3<sup>rd</sup> level Wizard // Rogue (Arcane Trickster) grants 6 Cantrips, 6 &times; 1<sup>st</sup> level spell slots (4 from Wizard, 2 from Rogue), and 2 &times; 2<sup>nd</sup> level spell slots (Both from Wizard).

Once the Wizard // Rogue (Arcane Trickster) reaches 7<sup>th</sup> level, they have 7 Cantrips, 8 &times; 1<sup>st</sup> level slots (four from Wizard, four from Rogue), 5 &times; 2<sup>nd</sup> level slots (three Wizard, two Rogue), 3 &times; 3<sup>rd</sup> level slots (three Wizard, no rogue), and 1 &times; 4<sup>th</sup> level slots (Wizard).

By 20<sup>th</sup> level, the Wizard // Rogue (Arcane Trickster), they have 9 Cantrips, 8 &times; 1<sup>st</sup> level slots (four from Wizard, four from Rogue), 6 &times; 2<sup>nd</sup> level slots (three Wizard, three Rogue), 6 &times; 3<sup>rd</sup> level slots (three Wizard, three rogue), 4 &times; 4<sup>th</sup> level slots (three Wizard, one rogue), with Wizard granting 3 &times; 5<sup>th</sup>, 2 &times; 6<sup>th</sup>, 2 &times; 7<sup>th</sup>, 1 &times; 8<sup>th</sup>, and 1 &times; 9<sup>th</sup> level spell slots.

#### Pact Magic

You do not add your warlock level to your other levels when determining how many spell slots you have on the Multiclass Spellcaster table. Instead, the spell slots granted by Pact Magic are in addition to the ones granted by Spellcasting.

## Fighting Styles *(Any)*

Classes that have access to choosing a fighting style, may use any from the list of published sources. Fighting styles are **NOT** class exclusive.

## Fighting Styles *(New Options)*

#### Acrobatic

You may use Acrobatics instead of Athletics when you use a combat maneuver like the shove or disarm action, and have advantage on checks made to avoid or escape grapples, restraints and magical paralysis.

#### Brutal

With every hit of a weapon you are wielding with two hands, you can choose to subject a tiny-medium sized opponent to make a Strength save where the DC is 8 + proficiency bonus + your Strength modifier. Upon a failed save, the creature is knocked 5 ft away from you.

\pagebreakNum

<div style="margin-top:2mm;"></div>

#### Charging

When you dash, you may move an additional 10 feet and may make an attack with a melee weapon against a creature as part of the dash. (Note, the Charger feat gains the point that if you have this fighting style, you add the +5 damage bonus to the attack from this fighting style as well)

#### Combat Readiness

You gain Advantage on initiative rolls.

#### Crippling

When you hit a creature with a melee weapon attack, its speed is reduced by 10 feet, to a minimum of 0, and it can’t take the Dash action until the end of its turn.

#### Distraction

When you attack with your weapon your mighty bellow and antics tend attract attention. When you take the Attack action on your turn, as a bonus action, you may subject creatures hostile to you within 10 to make a Wisdom saving throw.

If they fail, they focus their attention on you, granting them disadvantage on their attacks and perception checks if it is not against you.

#### Executioner

When you damage a creature that is blind, frightened, restrained, paralyzed, prone or stunned, you double the damage provided by your ability modifier. On a critical hit, you triple your ability modifier instead.

#### Guerrilla

* You gain +5ft move speed while in light or medium armor without stealth penalty.
* You get training in two skill from the following list; *athletics, acrobatics, stealth, survival, perception, nature, medicine.*

#### Mounted Archery

While riding your Steed, you can make an extra ranged attack at disadvantage against a target within 15 feet of you when you take the Attack action on your turn.

#### Mounted Defense

While you are wearing armor you gain resistance against slashing damage from non-magical weapons. While your Steed is wearing barding, it gains +1 bonus to AC and resistance to slashing damage from non-magical weapons.

#### Mounted Dueling

While riding your Steed and wielding a melee weapon in one hand and no other weapons, you gain +1 bonus to damage rolls with that weapon.

#### Mounted Two-Weapon Fighting

While riding your Steed, when you land a critical hit, you can use your reaction to make another weapon attack.

#### Phalanx

* When an ally within 5 feet of you makes an attack against a creature in your reach, you may use your reaction to give your ally advantage on their attack roll.
* While having shield equipped that you are proficient you gain +1 shield bonus to AC in addition to base shield bonus.
* If you're next to a person using a shield you both gain +1 bonus to AC.
* If you're next to two persons that have this style and shield equipped you gain +2 bonus to AC instead.

#### Reach Weapon Fighting

When you use a reach weapon to attack a creature further than 10 feet away from you, and you can use your reaction for attacks of opportunity against that creatures at that distance.

#### Skirmish

* When you damage a creature from hiding, you may remain hidden until the end of your turn as long as you move. If you end your turn behind a new piece of cover, you may make a new stealth check to attempt to remain hidden as a reaction.
* You gain +10ft move speed while in light armor or no armor.

\columnbreak

<div style="margin-top:2mm;"></div>

* You gain +1 on either melee or ranged attacks while in light or no armor.

#### Smiting

When you use your divine smite class feature or cast a spell with the word "smite" in its name, you may increase the damage the feature or spell deals by your charisma modifier.

#### Stylish

When you attack with your weapon you tend to show off. When you take the Attack action on your turn, as a bonus action, you may subject a creature within 30 feet of you to make a Wisdom saving throw where the DC is 8 + your proficiency bonus + your Charisma modifier. If they fail, they focus their attention on you, granting them disadvantage on their next attack if it is not against you.

#### Throwing weapons

* You double the range of your throwing weapons, may draw extra throwing weapons as part of the attack action, and have a +2 bonus on attack rolls made in the short range of your throwing weapons.
* Raise weapon damage die by one step for thrown weapons. They still use original value while used in melee attacks. You can combine this style with dueling style.

#### Titan Fighting

You gain a +2 bonus to melee weapon attack rolls you make against Large or larger creatures.

#### Toughness

Your Hit Die increases to 1d12 (or 7) + your Constitution modifier. A fighter with the champion subclass whom selects Toughness fighting style with their Additional Fighting Style feature gains +9 HP and uses his d12 (or 7) from there on out.

#### Unarmed

Your unarmed attacks count as 1d4 light, finesse weapons for all purposes except disarming. Additionally, any effect or ability that increases your unarmed strike damage, such as the Aarakocra race, each level of monk unarmed attack progression or the tavern brawler feat, increases the size of the damage die of your unarmed strike by one (to a maximum of 1d12).

#### Unarmored

When you are not wearing armor, your armor class is equal to 12+your dexterity modifier. Additionally, you gain a climb and swim speed equal to your normal movement speed, and may increase the distance you jump by your constitution modifier.

#### Whirling Blades

When you engage in two-weapon fighting while wearing light or no armor, you add your ability modifier to the second attack but do not expend your bonus action. You can still gain the benefits of two-weapon fighting once during your turn.

## Revised Bard: Colleges of Swords and Valor

These two subclasses are merges into the College of Battle, as follows:

### College of Battle

| College of Battle | Description |
|:---|:-----------|
| 3<sup>rd</sup> level:</br>Bonus Proficiencies | Combine **Valor**'s Bonus Proficiencies with the second line of **Sword**'s. |
| 3<sup>rd</sup> level:</br>Fighting Style &</br>Blade Flourish | As College of Swords |
| 3<sup>rd</sup> level:</br>Combat Inspiration | As College of Valor |
| 6<sup>th</sup> level:</br>Extra Attack | Gained **Once** only |
| 14<sup>th</sup> level:</br>Master's Flourish &</br>Battle Magic | As each subclass |

\pagebreakNum

<div style="margin-top:2mm;"></div>

## Revised Fighter: Champion

This subclass is now a core part of the base Fighter class. PCs who select Fighter as a class, now receive the Champion's abilities in addition to their chosen subclass. This makes PC Fighters a more versatile option.

## Revised Monk

Monks now have d10 for Hit Dice. At first level, they begin with 10 + Constitution modifier hit points, and gain 1d10 (or 6) + Constitution modifier hit points per monk level after 1<sup>st</sup>.

### Revised Monk: Way of Four Elements Remastered

Players are to use [this](https://drive.google.com/open?id=1C1NWq1sKDKXBfyfcdcN-lpYHx4pdZoh2) version of the Way of Four Elements monk.

### Revised Monk: Way of the Kensei

Monks of the Way of Kensei train relentlessly with their weapons, to the point that the weapon becomes like an extension of the body. A Kensei sees a weapon in much the same way a painter regards a brush or a writer sees parchment, ink, and quill.

A sword or bow is a tool used to express the beauty and elegance of the martial arts. That such mastery makes a Kensei a peerless warrior is but a side effect of intense devotion, practice, and study.

##### Path of the Kensei

*This is changed from the base subclass.*

**Change: *Kensei Weapons.*** Remove *"that lacks the heavy and special properties"* from the second sentence. Change the following sentence *"The longbow is also a valid choice."* to *"The longbow or greatbow are also valid choices."* Change the following sentence *"Weapons of the chosen types are monk weapons for you."* to *"Weapons of the chosen types are monk weapons for you, and count as finesse weapons."*

##### Second Skin

*This is added to the base subclass.*

*At 3rd level.* You gain proficiency in light armor and do not lose the benefits of your Martial Arts class feature while wearing light armor. Your Unarmored Bonus is now calculated as the armor you are wearing (if any) + your Dexterity modifier + your Wisdom modifier. If you are not wearing armor, then it defaults to 10 + your Dexterity modifier + your Wisdom modifier.

## Revised Paladin

Paladins have d12's for Hit Dice, start with 12 + Constitution Modifier, and gain 1d12 (or 7) + Constitution modifier per level after first.

## Revised Rogue: Thief

This subclass is now a core part of the base Rogue class. PCs who select Rogue as a class, now receive the Thief's abilities in addition to their chosen subclass. This makes PC Rogues a more versatile option.

## UA Ranger Revised 2016 Changes

### Core Changes

The beastmaster subclass is now a core part of Ranger.

### Bonus Spells

The hunter subclass also gain bonus spells.

| Hunter level | Bonus Spells |
|:---:|:-----------:|
| 3<sup>rd</sup> | Compelled Duel |
| 5<sup>th</sup> | Magic Weapon |
| 9<sup>th</sup> | Glyph of Warding |
| 13<sup>th</sup> | Death Ward |
| 17<sup>th</sup> | Hold Monster |

\columnbreak

<div style="margin-top:2mm;"></div>

All subclasses gain the following spells as bonus spells, in addition to those normally gained from choosing that subclass.

| Ranger level | Bonus Spells |
|:---:|:-----------:|
| 3<sup>rd</sup> | Expeditious Retreat |
| 5<sup>th</sup> | Enhance Ability |
| 9<sup>th</sup> | Feign Death |
| 13<sup>th</sup> | Dominate Beast |
| 17<sup>th</sup> | Insect Plague |

### Hunter's Quarry

At 1<sup>st</sup> level, once per turn as a bonus action, a ranger can designate the nearest visible enemy as his or her quarry. This designation lasts until the encounter ends, the quarry is defeated, or the ranger designates a different target.

Once per round, the ranger deals an additional 2d6 damage, when hitting his or her quarry with an attack. If the ranger can make multiple attacks in a round, the ranger decides which attack to apply the extra damage to after all the attacks are rolled.

At 5<sup>th</sup> level, and every four levels afterwards, Hunter's Quarry deals an additional 1d6 damage, to a maximum of an additional 6d6 damage at 17<sup>th</sup> level

| Ranger level range | Bonus Damage |
|:---:|:-----------:|
| 1<sup>st</sup> to 4<sup>th</sup> | +2d6 |
| 5<sup>th</sup> to 8<sup>th</sup> | +3d6 |
| 9<sup>th</sup> to 12<sup>th</sup> | +4d6 |
| 13<sup>th</sup> to 16<sup>th</sup> | +5d6 |
| 17<sup>th</sup>+ | +6d6 |

\pagebreakNum

# Chapter 6: New and Revised Classes

<div class="classTable wide" style="margin-top:0mm;margin-bottom:2mm;border-bottom:1px solid #000;">

## The Commander

| **Level** | **Proficiency Bonus** | **Features** | **Commands &</br>Tactics Known** |
|:--:|:--:|:--|:--:|
| 1 | +2 | Commands & Tactics, Fight from the Front, Weigh the Odds | 2 |
| 2 | +2 | Fighting Style | 3 |
| 3 | +2 | Command Style | 4 |
| 4 | +2 | Ability Score Increase | 5 |
| 5 | +3 | Extra Attack | 6 |
| 6 | +3 | &mdash; | 7 |
| 7 | +3 | Command Style Feature | 8 |
| 8 | +3 | Ability Score Improvement | 9 |
| 9 | +4 | Fight from the Front Improvement, Weigh the Odds Improvement | 10 |
| 10 | +4 | Command Style Feature | 11 |
| 11 | +4 | Improved Attack | 12 |
| 12 | +4 | Ability Score Improvement | 13 |
| 13 | +5 | Additional Fighting Style | 14 |
| 14 | +5 | Command Style Feature | 15 |
| 15 | +5 | &mdash; | 16 |
| 16 | +5 | Ability Score Improvement | 17 |
| 17 | +6 | Fight from the Front Improvement, Weigh the Odds Improvement | 18 |
| 18 | +6 | &mdash; | 19 |
| 19 | +6 | Ability Score Improvement | 20 |
| 20 | +6 | Final Stand | 21 |

</div>

Commanders are accomplished warriors that lead others by example on the front lines, issuing commands and bolstering their allies. They rally their allies to secure a decisive victory. Many think of them as battle hardened soldiers, but commanders come from all walks of life.

As a commander, you could be a young noble ready to apply years of training in real combat, an experienced knight leading a small regiment, the chief of a roving war band, or even a simple guardsman who stepped up to the plate when your leader died and the situation called for action.

Regardless of how you became a commander, you are as comfortable with a weapon in your hand as you are with inspiring others through strong leadership.

#### Born to Command

Commanders have a natural aptitude for leadership that is seldom matched by others. Others may be intimidated by thinking quickly and making important decisions, but not you.

Many commanders find that their natural aptitude for leadership extends to other areas of their adventuring life. The skills you develop while leading others can give you a knack for deftly maneuvering through tense social situations.

#### The Desire for Challenge

Commanders who have left the relative comforts of their past life to become an adventurer are always looking for a new challenge, one that drives them forward to new heights. It's not enough for you to lead others; you need to lead powerful allies against the greatest foes the multiverse has to offer.

#### Creating a Commander

When creating a commander, think about what style of command you'll use and where your commanding prowess came from. Are you a charismatic commander who leads by example, a strategist that uses their keen intellect, or an experienced veteran that utilizes years of wisdom?

\columnbreak

<div style="margin-bottom:2mm;"></div>

#### Quick Build

You can make a commander quickly by following these suggestions. First, make Strength or Dexterity your highest ability score, depending on whether you want to focus on melee weapons or on archery (or finesse weapons). Your next-highest score should be the one you use for subclass' commanding ability modifier (usually Charisma, Intelligence, or Wisdom). Second, choose the soldier background.

### Class Features

As a commander, you gain the following class features.

#### Hit Points

**Hit Dice.** 1d10 per commander level.</br>
**Hit Points at 1<sup>st</sup> Level.** 10 + your Constitution modifier.</br>
**Hit Points at Higher Levels.** 1d10 (or 6) + your Constitution modifier per commander level after 1<sup>st</sup>.

#### Proficiencies
**Armor.** All armor, shields</br>
**Weapons.** Simple weapons, martial weapons</br>
**Tools.** Navigator's Tools

___
**Saving Throws.** Strength, Wisdom</br>
**Skills.** Choose three from Acrobatics, Animal Handling, Athletics, History, Insight, Intimidation, Investigation, Perception, Persuasion, and Survival.

#### Equipment

You start with the following equipment, in addition to the equipment granted by your background.

*  *(a)* chain mail or *(b)* leather armor, longbow, and 20 arrows </br>
*  *(a)* a martial weapon and a shield or *(b)* two martial melee weapons </br>
*  *(a)* a light crossbow and 20 bolts or *(b)* two handaxes </br>
*  *(a)* a dungeoneer's pack or *(b)* an explorer's pack

\pagebreakNum

<div style="margin-top:2mm;"></div>

### Commands & Tactics

You know two 1<sup>st</sup> level commands or tactics of your choice from the commands and tactics list. Whenever you gain commands and tactics, you can choose whether to gain a command or a tactic.

The Commands & Tactics Known column of the Commander table shows when you learn more commands or tactics of your choice. Each of these must be equal to your level or lower. Additionally, when you gain a level in this class, you can choose one of the commands or tactics you know and replace it with another, which must also be equal to your level or lower.

For instance, at 4th level you can learn one new command or tactic, while at 5th level you can replace any previously learned command or tactic with one from the 5th level commands and tactics list. At 6<sup>th</sup> level you learn one additional command or tactic of 5th level or lower, and can replace a previously learned command or tactic with another of 5th level or lower.

#### Commanding Ability

Some commands or tactics may refer to your commanding ability modifier. Once you've chosen a command style, it will specify which ability score you use for your commanding ability modifier. If you attempt to use a command or tactic that refers to your commanding ability modifier before you have one from your command style, then your commanding ability modifier is 0.

<div style="text-align:center">

**Command Save DC** = 8 + your proficiency bonus + your commanding ability modifier (or 0)

</div>

#### Command Points

Your commands are fueled by a pool of points called command points. When you roll initiative, your command points reset to 1, and you can never have more command points than your level plus 4. In order to gain additional command points, you'll need to use your Fight from the Front or Weigh the Odds class features.

### Fight from the Front

During battle, you can seize new opportunities from your attacks. Once per round when you land a hit, you gain 1 command point. At 9th level, this increases to 2 command points. At 17th level, this increases to 3 command points.

### Weigh the Odds

You can bide your time discover new opportunities during combat. As an action, you gain 1d4 command points. At 9th level, this increases to 1d4+2 command points. At 17th level, this increases to 2d4+2 command points.

### Fighting Style

At 2nd level, you adopt a particular style of fighting as your specialty. Choose one of the following options. You can't take a Fighting Style option more than once, even if you later get to choose again.

At 13th level, you gain an additional fighting style.

For any Official Fighting Styles, refer to their descriptions in the [5e SRD](http://media.wizards.com/2016/downloads/DND/SRD-OGL_V5.1.pdf) or Unearthed Arcana article.

#### Archery

SRD v5.1 page 24

#### Defense

SRD v5.1 page 24

#### Dueling

SRD v5.1 page 24

#### Protection

SRD v5.1 page 24

#### Two-Weapon Fighting

SRD v5.1 page 24

\columnbreak

<div style="margin-top:2mm;"></div>

#### Crippling

When you hit a creature with a melee weapon attack, its speed is reduced by 10 feet, to a minimum of 0, and it can't take the Dash action until the end of its turn.

#### Titan Fighting

You gain a +2 bonus to melee weapon attack rolls you make against Large or larger creatures.

### Command Style

At 3rd level, you adopt a particular style of command that best suits you. Each command style specializes in a different aspect of commanding your allies, and each command style has an associated commanding modifier that affects your commands and tactics.

### Ability Score Improvement

When you reach 4th level, and again at 8th, 12th, 16<sup>th</sup>, and 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase a ability score above 20 using this feature.

### Extra Attack

Beginning at 5th level, you can attack twice, instead of once, whenever you take the Attack action on your turn.

### Improved Attack

Beginning at 11th level, your attacks become more deadly. Whenever you attack with a weapon, you add an additional 1d8 to its damage.

### Final Stand

At 20th level, you gain the ability to inspire your allies and reinvigorate them for a final push in battle. As an action, you can target any ally within 30 feet of you who can see or hear you. The targeted creatures can heal a number of hit points equal to half of their hit point maximum. Once you've used this ability, you must finish a long rest to use it again.

## Command Styles

No two commanders have the same leadership style. Some lead by example, while others deftly manipulate the battlefield with keen usage of tactics. Three such options are presented below.

### Warlord

Warlords are charismatic leaders who inspire their allies and lead by example. As a warlord, you excel at charging into battle, empowering your allies, and harrying your foes.

#### Charismatic Leader

When you choose this archetype at 3rd level, the ability score that you use for your commanding ability modifier in commands and tactics is Charisma.

#### Inspiring Strength

At 3rd level, you gain the ability to inspire strength and endurance in your allies. You spend 10 minutes speaking to your allies and each ally that can hear or see you increases their maximum and current hit points for 24 hours by an amount equal to your level plus your Charisma modifier. You can only use this benefit once per long rest, and a creature can only benefit from one usage of this feature at a time.

#### Diplomatic Rapport

At 3rd level, you gain proficiency in either the Deception, Intimidation, or Persuasion skill.

#### Warlord's Challenge

At 7th level, you gain the ability to inspire rage and focus in your enemies. As an action, you target one creature which must make a Wisdom saving throw against your Command Save DC or be charmed by you for 1 minute. For the duration, the targeted creature has disadvantage on attacks against creatures other than you.

\pagebreakNum

<div style="margin-top:2mm;"></div>

#### Warlord's Stance

At 10th level, you gain the ability to take a stance that makes you and your allies more difficult to deal with in combat. As a bonus action, you can assume a stance that lasts until you dismiss it. You and any allies within 5 feet of you gain the benefits of one of the following stances:

* **Offensive Stance.** - Gain a +2 bonus to attack rolls.
* **Defensive Stance.** - Gain a +2 bonus to Armor Class.
* **Powerful Stance.** - Gain a +2 bonus to damage rolls.

#### Fearless Leader

At 14<sup>th</sup> level, you and all allies within 30 feet of you are immune to fear and charm effects.

### Strategist

Strategists are cunning leaders that constantly observe the battlefield, always watching for the next advantage that they can seize. You excel at manipulating the battlefield and commanding your allies.

#### Cunning Leader

When you choose this archetype at 3rd level, the ability score that you use for your commanding ability modifier in commands and tactics is Intelligence.

#### Unstoppable Command

At 3rd level, you gain the ability to always have a command at the ready. You gain 1 command point at the start of each of your turns.

#### Intelligent Strategist

At 3rd level, you gain a knack for using your intelligence in all situations. Add half of your proficiency bonus (rounded up) to Intelligence checks that you aren't proficient in.

#### Lateral Command

At 7th level, you gain the ability to target additional allies with your commands. Once when using a command, you can spend a command point to affect 1 additional creature. The targeted creature must still meet any other requirements specified by the command.

#### Versatile Command

At 10th level, you gain the ability to respond to more situations in combat. You gain an additional reaction that can only be used for commands.

#### Decisive Strategy

At 14<sup>th</sup> level, you gain the ability recognize situations and direct your allies more effectively. When using a command, you can spend 2 additional command points to grant the targeted creatures advantage on their next attack roll, ability check, or saving throw.

### Tactician

Tacticians are experienced commanders that anticipate outcomes and direct their allies through decisive tactics. You excel at using tactics to their full extent and surprising your enemies.

#### Experienced Leader

When you choose this archetype at 3rd level, the ability score that you use for your commanding ability modifier in commands and tactics is Wisdom.

#### Tactical Leader

At 3rd level, you become more adept at seizing every advantage in combat. As an action, you can regain a spent tactic that would normally become available on a short or long rest. You can only regain spent tactics this way twice per day.

#### Insightful Tactician

At 3rd level, you become more adept at recognizing fine details. You gain proficiency in either the Insight or Perception skill.

#### Tactical Foresight

At 7th level, you gain the ability to predict likely outcomes in tense situations. Once per day, roll a d6 and note the result. Whenever a creature within 30 feet of you makes an attack roll, ability check, or saving throw, you can apply the result as a bonus or penalty to the roll.

\columnbreak

<div style="margin-top:2mm;"></div>

At 10th level the die you roll increases to a d8, and at 14<sup>th</sup> level it increases to a d10.

#### Guerrilla Tactics

At 10th level, you become a master of ambush and guerrilla tactics. You and any allies within 30 feet of you that can see you gain advantage on initiative checks. If you are hidden, you can choose to give your allies advantage on Wisdom (Perception) checks made to see you.

#### Master Tactician

At 14<sup>th</sup> level, you excel at empowering your allies through skilled tactics. Your allies no longer have to spend their reaction when your tactics would require them to.

## Commands & Tactics

### Commands

Commands are reactions that have an associated command points cost. Targets of commands must be conscious and able to see or hear you, unless otherwise specified.

#### Get Out of There!
*1<sup>st</sup>-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range (on the ally's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  1 command point
- **Special:** &mdash;
___
The targeted creature can disengage using a bonus action.

#### Rally Now
*1<sup>st</sup>-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range (on the ally's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  1 command point per Hit Die used
- **Special:** If you spend 2 additional command points, you can target an unconscious ally with it.
___
The targeted creature can heal using a number of Hit Dice equal to the number of command points spent. In addition, the targeted creature receives additional hit points equal to your commanding ability modifier. A creature must have at least 1 Hit Die remaining in order to be targeted by this command.

#### Save Now!
*1<sup>st</sup>-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range (on any turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  1 command point
- **Special:** If you spend 2 additional command points, the target has advantage on the saving throw.
___
The targeted creature can roll a saving throw against an effect that would normally require them to attempt a saving throw on their turn.

#### Try Again
*1<sup>st</sup>-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range that made an attack roll (on the ally's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  2 command points
- **Special:** &mdash;
___
The targeted creature can reroll the attack but must use the new result.


\pagebreakNum

<div style="margin-top:2mm;"></div>

#### Charge!
*1<sup>st</sup>-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range (on the ally's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  1 command point
- **Special:** &mdash;
___
The targeted creature can take the Dash action as a bonus action on this turn.

#### Watch Your Feet
*1<sup>st</sup>-Level Command*
___
- **Action:** 1 reaction
- **Target:** One enemy within range that's adjacent to one of your allies (on the enemy's turn)
- **Duration:** until the start of the target's next turn
- **Range:** 30 feet
- **Cost:**  1 command point
- **Special:** &mdash;
___
The targeted creature must make a Dexterity saving throw. On a failed save, a creature is knocked prone and has its speed reduced to 0 for the duration.

#### You Set Them Up, I Finish'em
*5th-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range (on the ally's turn)
- **Duration:** until the start of the target's next turn
- **Range:** 30 feet
- **Cost:**  5 command points
- **Special:** &mdash;
___
The targeted creature adds your commanding ability modifier to their damage rolls this turn. In addition, during your next turn, you gain advantage on melee attacks against the creature your ally targeted.

#### Hit Harder
*5th-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range who makes a damage roll (on the ally's turn)
- **Duration:** until the start of the target's next turn
- **Range:** 30 feet
- **Cost:**  2 command points
- **Special:** &mdash;
___
The targeted creature can reroll any of the damage dice. They must accept the new rolls.

#### Hey! Look at Me!
*5th-Level Command*
___
- **Action:** 1 reaction
- **Target:** Up to 3 enemies within range
- **Duration:** until the end of the target's next turn
- **Range:** 30 feet
- **Cost:**  4 command points
- **Special:** You may spend additional command points for extra effect.
___
The targeted creature must make a Wisdom saving throw. On a failed save, a creature has disadvantage on its attack rolls for the duration. If you spend 4 additional command points, a creature also has disadvantage on its saving throws for the duration.

#### Hit 'Em From Here!
*9th-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range (On the ally's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  2 command points
- **Special:** &mdash;
___
This turn, the targeted ally can double the range of a weapon, class feature, or spell that uses an attack roll, plus an additional number of feet equal to twice your commanding ability modifier.

\columnbreak

<div style="margin-top:2mm;"></div>

#### Strike Here!
*9th-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range (On the ally's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  2 command points
- **Special:** &mdash;
___
The target can use a bonus action to make a single extra attack this turn.

#### We've Got Your Back!
*9th-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range that is Charmed, Frightened, or Incapacitated (At the start of the ally's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  2 command points
- **Special:** If you spend an additional 2 command points, you have advantage on the saving throw.
___
You make a saving throw as if you were the targeted creature. If you successfully make the saving throw, the targeted effects end on the creature.

At 15th level, add Stunned and Restrained to the list of conditions the effect includes.

#### Stop What You're Doing!
*9th-Level Command*
___
- **Action:** 1 reaction
- **Target:** 1 enemy (on the enemy's turn)
- **Duration:** until the start of the target's next turn
- **Range:** 30 feet
- **Cost:**  2 command points
- **Special:** You may spend additional command points for extra effects.
___
The targeted creature must make a Wisdom saving throw. On a failure, the targeted creature suffers different effects for the duration, depending on how many command points were spent.

If you spent 2 command points, the target is unable to take reactions. If you spent 4 command points, the target is incapacitated. If you spent 6 command points, the target is stunned.

#### Chain of Commands
*13th-Level Command*
___
- **Action:** 1 free action
- **Target:** 1 enemy (on the enemy's turn)
- **Duration:** until the start of the target's next turn
- **Range:** Self
- **Cost:**  1 command point
- **Special:** You can only use this command once per round.
___
The next reaction you use to make a command doesn't prevent you from using another reaction later in the round.

#### You Know What to Do!
*13th-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range (on the ally's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  5 command point
- **Special:** You can only use this command once per round.
___
The targeted creature can take one extra action on this turn.

#### Stop Hitting Yourself!
*13th-Level Command*
___
- **Action:** 1 reaction
- **Target:** One enemy within range (on the enemy's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  5 command point
- **Special:** You can only use this command once per round.
___
The targeted creature must make a Wisdom saving throw. On a failure, it attacks a nearby creature that is friendly to it.

\pagebreakNum

<div style="margin-top:2mm;"></div>

#### Natural Command
*17th-Level Command*
___
- **Action:** 1 reaction
- **Target:** All allies within range
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  8 command point
- **Special:** You can only use this command once per round.
___
The targeted creatures have advantage on attack rolls until the start of your next turn.

#### You'll Die When I Tell You to Die!
*17th-Level Command*
___
- **Action:** 1 reaction
- **Target:** One ally within range about to roll a death saving throw (On the ally's turn)
- **Duration:** Instantaneous
- **Range:** 30 feet
- **Cost:**  All remaining command points (5 minimum)
- **Special:** &mdash;
___
The target regains consciousness and one hit point. In addition, the target gains a number of temporary hit points equal to your commanding ability modifier times the number of command points you spent.

#### Zone of Command
*17th-Level Command*
___
- **Action:** 1 reaction
- **Target:** All enemies within range
- **Duration:** Until the start of the target's next turn
- **Range:** 20 foot cube, centered within 30 feet
- **Cost:**  All remaining command points (8 minimum)
- **Special:** &mdash;
___
The targeted creatures must make an Intelligence saving throw. On a failure, a target is incapacitated for the duration.

### Tactics

Tactics don't have an associated command points cost. Tactics can only be used once per short rest, unless otherwise specified.

#### Basic Tactical Strike
*1<sup>st</sup>-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** One ally within range
- **Duration:** Instantaneous
- **Usage:** Once per short rest
- **Range:** 30 feet
- **Special:** &mdash;
___
The targeted creature can make an attack as a reaction.

#### Enforce Clarity
*1<sup>st</sup>-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** One ally within range
- **Duration:** Instantaneous
- **Duration:** Once per short rest
- **Range:** 30 feet
- **Special:** &mdash;
___
As a reaction, the targeted creature can end one ongoing effect, but only if the effect is one that would normally allow them to attempt a saving throw on their turn.

At 10th level, you can now target one additional nearby ally with this tactic.

\columnbreak

<div style="margin-top:2mm;"></div>

#### Just Stay Calm
*1<sup>st</sup>-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** Up to three allies within range (including yourself)
- **Duration:** Instantaneous
- **Usage:** Once per long rest
- **Range:** 30 feet
- **Special:** &mdash;
___
The creatures can heal using up to half of their hit dice, plus an additional number of hit points equal to your commanding ability modifier, as a reaction.

At 10th level, you can target up to five allies within range.

#### Try Aiming!
*1<sup>st</sup>-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** One enemy within range
- **Duration:** Concentration, up to 1 minute
- **Usage:** Once per short rest
- **Range:** 30 feet
- **Special:** &mdash;
___
The targeted creature must make a Wisdom saving throw. On a failure, it has disadvantage on all attack rolls that it makes for the duration. A creature can repeat this saving throw at the end of its turn.

#### Finish This!
*5th-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** Self and up to three allies within range
- **Duration:** Concentration, up to 1 minute
- **Usage:** Once per long rest
- **Range:** 30 feet
- **Special:** You can only use this tactic when one enemy is left in the battle.
___
You can spend either 4 or 8 command points. The targeted creatures' attacks against the remaining enemy score a critical hit based on the number of command points you spent. If you spent 4 command points, attacks score a critical hit on a roll of 19 or 20. If you spent 8 command points, attacks score a critical hit on a roll of 18, 19, or 20.

#### Scramble
*5th-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** Self and up to three allies within range
- **Duration:** Instantaneous
- **Usage:** Once per short rest
- **Range:** 30 feet
- **Special:** You can only use this tactic when one enemy is left in the battle.
___
Each targeted creature can move up to their speed, plus an additional number of feet equal to twice your commanding ability modifier, as a reaction. This movement does not provoke opportunity attacks.

#### Sword Work
*5th-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** Self
- **Duration:** Concentration, up to 1 minute
- **Usage:** Once per short rest
- **Range:** &mdash;
- **Special:** You can only use this tactic when one enemy is left in the battle.
___
You can make an attack as a bonus action on each of your turns for the duration of this tactic.

\pagebreakNum

<div style="margin-top:2mm;"></div>

#### Stunning Maneuver
*5th-Level Tatic*
___
- **Action:** 1 action
- **Target:** One enemy within range
- **Duration:** Concentration, up to 1 minute
- **Usage:** Once per short rest
- **Range:** 30 feet
- **Special:** &mdash;
___
The targeted creature must make a Constitution saving throw. On a failure, a target is stunned for the duration. A creature may repeat this saving throw at the end of its turn.

#### Climactic Battle
*13th-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** Self and all allies within range
- **Duration:** Concentration, up to 1 minute
- **Usage:** Once per short rest
- **Range:** 30 feet
- **Special:** &mdash;
___
Whenever the targeted creatures makes an attack roll, saving throw, or ability check before the tactic ends, the creature gains a bonus to the attack roll or saving throw equal to your commanding ability modifier.

#### On Your Feet, Maggots!
*13th-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** Up to two allies within range at or below half of their total hit points
- **Duration:** Concentration, up to 1 minute
- **Usage:** Once per long rest
- **Range:** 30 feet
- **Special:** &mdash;
___
The targeted creatures can spend up to half their hit dice as a reaction. The targeted creatures do not need to be conscious to gain this benefit.

#### Saving Grace
*13th-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** One ally within range
- **Duration:** Instantaneous
- **Usage:** Once per short rest
- **Range:** 30 feet
- **Special:** &mdash;
___
The target gains a bonus to all saving throws equal to your commanding ability modifier until the end of your next turn.

#### Hamper Them!
*13th-Level Tatic*
___
- **Action:** 1 action
- **Target:** One enemy within range
- **Duration:** Concentration up to 1 minute
- **Usage:** Once per long rest
- **Range:** 30 feet
- **Special:** &mdash;
___
The target must succeed on a Wisdom saving throw or be affected by this tactic for the duration.

An affected target's speed is halved, it takes a −2 penalty to AC and Dexterity saving throws, and it can't use reactions. On its turn, it can use either an action or a bonus action, not both. Regardless of the creature's abilities or magic items, it can't make more than one melee or ranged attack during its turn.

If the creature attempts to cast a spell with a casting time of 1 action, roll a d20. On an 11 or higher, the spell doesn't take effect until the creature's next turn, and the creature must use its action on that turn to complete the spell. If it can't, the spell is wasted.

A creature affected by this tactic makes another Wisdom saving throw at the end of its turn. On a successful save, the effect ends for it.

\columnbreak

<div style="margin-top:2mm;"></div>

#### Now, Not Later
*17th-Level Tatic*
___
- **Action:** 1 bonus action
- **Target:** One nearby ally
- **Duration:** Instantaneous
- **Usage:** Once per long rest
- **Range:** 30 feet
- **Special:** &mdash;
___
As a reaction, the targeted ally gains one of the following benefits:

* Recover one short rest ability.
* Recover one usage of a long rest ability.
* Regain a number of spell slots with a combined level of 5 or less.
* Regain up to 5 points from a point pool limited by short or long rests (such as ki points or sorcery points).

#### Supreme Tactical Strike
*17th-Level Tatic*
___
- **Action:** 1 action
- **Target:** Up to five allies within range
- **Duration:** Instantaneous
- **Usage:** Once per long rest
- **Range:** 30 feet
- **Special:** &mdash;
___
The targeted creatures can make an attack as a reaction, with a bonus to the attack roll equal to your commanding ability modifier.

#### Sew Discord
*17th-Level Tatic*
___
- **Action:** 1 action
- **Target:** Up to 3 enemies within range
- **Duration:** Instantaneous
- **Usage:** Once per long rest
- **Range:** 30 feet
- **Special:** &mdash;
___
The targeted creatures must make a Wisdom saving throw. On a failed save, each target must attack a creature within its reach that is friendly to it as a reaction.

\pagebreakNum

# Chapter 7: New Spells

## New Spell Descriptions

#### Hide from Animals
*1<sup>st</sup>-Level Abjuration (ritual)*
___
- **Class:** *Druid, Ranger*
- **Casting Time:** 1 action
- **Range:** touch
- **Components:** V, S, M (a sprig of mistletoe)
- **Duration:**  8 hours
___
Animals cannot see, hear, or smell the warded creatures. Even extraordinary or supernatural sensory capabilities, such as blindsense, blindsight, scent, and tremorsense, cannot detect or locate warded creatures. Animals simply act as though the warded creatures are not there. If a warded character touches an animal or attacks any creature, even with a spell, the spell ends for all recipients.

\pagebreakNum

# Chapter 8: New and Revised Equipment

<div class='classTable wide' style="margin-top:-0mm;margin-bottom:2mm;border-bottom:1px solid #000;">

### New Armor

| **Armor** | **Cost** | **AC** | **Strength** | **Stealth** | **Weight** |
|:--|:--:|:--:|:--:|:--:|--:|
| **Medium Armor** | | | | | |
| &nbsp;&nbsp;&nbsp;&nbsp;*Plated Leather Armor* | 200 gp | 13+Dex | &mdash; | Disadvantage | 20 lb. |
| &nbsp;&nbsp;&nbsp;&nbsp;*Leather Shoulder Guard* | 10 gp | +1 (partial armor) | &mdash; | &mdash; | 1 lb. |
| **Heavy Armor** | | | | | |
| &nbsp;&nbsp;&nbsp;&nbsp;*Plate Shoulder Guard* | 45 gp | +2 (partial armor) | &mdash; | &mdash; | 15 lb. |

### New Weapons

| **Name** | **Cost** | **Damage** | **Weight** | **Properties** |
|:--|:--:|:--:|:--:|:--|
| **Simple Melee Weapons** | | | | |
| &nbsp;&nbsp;&nbsp;&nbsp;*Tabaxi Battle Claw* | 25 gp | 1d6 slashing | 1 lb. | Light, Finesse |
| &nbsp;&nbsp;&nbsp;&nbsp;*Scythe* | 5 gp | 2d4 piercing or slashing | 10 lb. | Finesse, High Crit, Two-Handed |
| **Simple Ranged Weapons** | | | | |
| &nbsp;&nbsp;&nbsp;&nbsp;*Crossbow, Light Repeating* | 50 gp | 1d8 piercing | 6 lb. | Ammunition (range 80/320), reload (10), Two-Handed, Rogue |
| **Martial Melee Weapons** | | | | |
| &nbsp;&nbsp;&nbsp;&nbsp;*Elven Curve Blade* | 30 gp | 1d8 slashing | 2 lb. | Finesse, Versatile (1d10), Monk, Rogue |
| &nbsp;&nbsp;&nbsp;&nbsp;*Fullblade* | 50 gp | 2d6 slashing | 10 lb. | Heavy, Two-Handed, High Crit |
| &nbsp;&nbsp;&nbsp;&nbsp;*Orcish Double-Axe* | 40 gp | 2d6 slashing | 8 lb. | Double Weapon, Two-Handed |
| &nbsp;&nbsp;&nbsp;&nbsp;*Dwarven Mordenkrad* | 30 gp | 2d6 bludgeoning or piercing | 12 lb. | Heavy, Two-Handed, Brutal (1) |
| **Martial Ranged Weapons** | | | | |
| &nbsp;&nbsp;&nbsp;&nbsp;*Elven Double Bow* | 250 gp | 2d4 piercing | 3 lb. | Ammunition (range 150/600), Heavy, Two-Handed, High Crit |
| &nbsp;&nbsp;&nbsp;&nbsp;*Crossbow, Heavy </br>&nbsp;&nbsp;&nbsp;&nbsp;repeating* | 100 gp | 1d10 piercing | 15 lb. | Ammunition (range 100/400), reload (10), Heavy, Two-Handed |
| &nbsp;&nbsp;&nbsp;&nbsp;*Greatbow* | 100 gp | 1d10 piercing | 10 lb. | Ammunition (range 200/800), Heavy, Two-Handed, High Crit |
| **Martial Buster-type Weapons** | | | | |
| &nbsp;&nbsp;&nbsp;&nbsp;*Buster Axe* | 120 gp | 2d12 slashing | 28 lb. | Buster, two-handed |
| &nbsp;&nbsp;&nbsp;&nbsp;*Buster Club* | 1 gp | 2d8 bludgeoning | 40 lb. | Buster, two-handed |
| &nbsp;&nbsp;&nbsp;&nbsp;*Oni Glaive* | 80 gp | 2d10 bludgeoning | 24 lb. | Buster, reach, two-handed |
| &nbsp;&nbsp;&nbsp;&nbsp;*Buster Hammer* | 60 gp | 4d6 bludgeoning | 40 lb. | Buster, two-handed |
| &nbsp;&nbsp;&nbsp;&nbsp;*Buster Sword* | 200 gp | 4d6 slashing | 24 lb. | Buster, two-handed |

### New Adventuring Gear

| **Item** | **Cost** | **Weight** | **Item** | **Cost** | **Weight** |
|:--|:--:|:--:|:--|:--:|:--:|
| Bandolier | 3 gp |  1 lb. | Firework, Skyrocket | 50 gp. | 1 lb. |
| Comm Set | 25 gp | 1 lb | Firework, Starfountain | 55 pp. | 10 lb. |
| Concussion Grenade | 75 gp | 2 lb. | Fuse Grenade | 100 gp. | 1 lb. |
| Eggshell Grenades | *Varies* | &mdash; | Rations, Wandermeal | 1 cp (per serving) | &frac12; lb. |
| Emergency Shelter | 200 gp | 15 lb. | Sling | 5 sp |  &mdash; |
| Field Equipment Pack, Basic | 45 gp. | 52 lb. | Tactical Vest | 15 gp | 6 lb. |
| Field Equipment Pack, Journeyman | 460 gp. | 59 &frac12; lb. | Vent Tape | 1 sp | &frac12; lb. |
| Firework, Desnan Candle | 5 gp. | &#8530; lb. |  |  |  |

</div>

## Armor Descriptions & Special Properties

#### *Partial Armor*

Partial armor only grants its AC bonus if you are wearing light or no armor. If you are wearing only one piece of partial armor, you are still considered to be wearing your base armor type (e.g. no armor or light armor). Otherwise the heaviest type of partial armor you are wearing is considered to be the type are wearing (e.g. medium or heavy armor).

\columnbreak

##### Leather Shoulder Guard

A leather shoulder guard is a light arm guard made from overlapping sturdy leather.

##### Plate Shoulder Guard

A plated armor that is overlapped piece by piece or made of one large solid piece made to protect the wearer's shoulder.

\pagebreakNum

#### *Standard Armour*

##### Plated leather armor

Plated leather armor is intended as a marriage of leather armor's light weight and flexibility and plate's strength. Plated leather armor is a base of full leather armor with lengths of chain mail and light lobster-like plate secured over the joints and smaller steel plates secured throughout the armor. It is a hybrid of Light and Medium armor; It counts as Medium armor for **Medium Armor Master**'s effects, but has an AC calculation based on Light armor.

## New Weapon Properties

##### Brutal

When rolling damage with weapons with this property, you reroll any damage dice that show the Brutal number, but must use the new result.

##### Buster

Small creatures cannot use buster weapons. And Medium creatures have disadvantage on attack rolls with buster weapons. A buster weapon's size and bulk makes it too large for a Medium creature to use effectively.

##### Double Weapon

Wielding a double weapon is like wielding a weapon in each hand. The first die given in the damage column of the table for a double weapon is for the primary (or main) end of the weapon; the second damage die is for the secondary (or off-hand) end. You can use either end of a double weapon to deliver an Attack Action, but to use a Bonus Action to attack, the other end must be used.

An enchanted double weapon receives an enhancement bonus and properties on both ends of the weapon.

Like heavy weapons, double weapons cannot normally be wielded by Small creatures.

##### High Crit

A high crit weapon deals more damage when the wielder scores a critical hit with it. On a critical hit, the weapon deals an additional amount of damage equal to its damage die, in addition to any critical damage the weapon supplies if it is a magic weapon.

## New Weapon Descriptions

##### Buster Axe

An oversized Greataxe, the Buster Axe is a also known as an Ogre's Greataxe.

##### Buster Club

An oversized Greataxe, the Buster Axe is a also known as an Ogre's Greataxe.

##### Buster Hammer

An oversized Greataxe, the Buster Axe is a also known as an Ogre's Greataxe.

##### Buster Sword

An oversized Greataxe, the Buster Axe is a also known as an Ogre's Greataxe.

##### Crossbow, Repeating

The repeating crossbow (whether heavy or light) holds 10 crossbow bolts. A rectangular magazine attaches to the top of this crossbow. A double-action lever drops a bolt into place as a free action, then fires it as an action.

A repeating crossbow does not need to be reloaded as long as They have ammunition in its magazine. A magazine costs 1 gp and holds 10 bolts. It takes an action to remove an empty magazine and load a new one.

##### Dwarven Mordenkrad

First used by dwarf shock troops in battle against giants, this oversized two-handed hammer has a massive head studded with spikes.

\columnbreak

<div style="margin-top:2mm;"></div>

##### Elven Curve Blade

Created by the elves, this blade is a slightly longer, but perfectly balanced longsword. Due to its expert craftsmanship, elves treat it as a racial weapon.

Monks and Rogues gain proficiency with Elven Curve Blades. Monks treat them as a monk weapon, and may use them with features that require or use monk weapons. Rogues may use Elven Curve Blades with Rogue features that require a finesse weapon.

##### Elven Double Bow

This double-stringed longbow can be used as a normal longbow by anyone proficient in that weapon. Characters with proficiency can use the bow to fire two arrows at once. Nocking an arrow on the second string requires a bonus action. Once the wielder has taken an bonus action to load the second string, his next attack is a double shot that launches both arrows simultaneously at the same target.

The wielder makes one attack roll at a disadvantage to determine whether or not both arrows strike the target. If the attack is successful, both arrows deal normal damage. If the attack is a critical hit, only one arrow deals extra damage, and extra sneak attack damage is applied only once.

##### Fullblade

An enormous 2-handed sword, larger even than a greatsword. These are wielded by the giant-blooded peoples in the inhospitable heights of the Broken Teeth.

##### Greatbow

When using this weapon to attack a target within 10 feet, you have disadvantage on the attack roll.

##### Oni Glaive

An oversized Glaive, the Oni Glaive is a glaive designed for an Oni.

##### Orcish Double-axe

When you take the attack action with this weapon, you may make an extra attack with it as a bonus action. You don't add your ability modifier to the damage on that attack unless you have the two-weapon fighting style. Orcs and Half-orcs treat the Orc double-axe as a racial weapon.

A longer hafted battle-axe with second head on the bottom. As its name suggests, it is often found in the hands of powerful orc fighters. The insular orc tribes in the sunken swamps hold their duels for rank with these axes, in ritual combat rarely seen by outsiders. A creature wielding an orc double axe in one hand can't use it as a double weapon&mdash;only one end of the weapon can be used in any given round.

##### Scythe

While it resembles the standard farm implement of the same name, this scythe is balanced and strengthened for war. The design of the scythe focuses tremendous force on the sharp point, as well as allowing devastating slashes with the blade edge.

Because of a scythe's shape, you can use an action to knock a creature prone. You have advantage on this check.

##### Tabaxi Battle Claw

Tabaxi Battle Claws are a single gauntlet with retractable blades that act as an extension of a Tabaxi's claws, or just as a concealed slashing weapon for other races. Tabaxi treat the Battle Claw as racial weapons. You would still have to pay for them, as they're not part of any starting equipment.

## New Adventuring Gear Descriptions

##### Bandolier

This shoulder strap contains six pouches large enough to hold a potion, grenade, or similarly-sized item within easy reach. It can hold 10 pounds of gear.

\pagebreakNum

<div style="margin-top:2mm;"></div>

##### Comm Set

This handheld device allows for communication between two or more communicator users. A communicator carries audio and visual signals, and includes a built-in camera that can record all communications being broadcast. Communication between two communicators requires both users to tune their individual devices to the same frequency. A communicator has a range of 30 miles; beyond this range, communication is impossible without enhancing the signal strength with a signal booster. The price and cost listed for this item are for a single communicator.

##### Concussion Grenade

Using this handheld device, you can verbally communicate with any creature within 1-mile that also has a comm set. A comm set can be connected to a headset worn on the ear or can be talked into directly. Its signal can penetrate most barriers, but is blocked by 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt.

##### Jamming Device

A jammer is a device used to scramble communications. Jamming devices however, have the habit of cutting off all major and minor hubs of communications inside the area in which the jamming device was installed, as well as jamming the enemy, making them very reliant on other methods of communications. They also jam crystal communicators and could jam scanners.

##### Eggshell Grenades

A favorite tool of ninja, used to create distractions, eggshell grenades are emptied eggshells carefully packed with various alchemical substances. Common grenade types include dust, flashpowder, pepper, and poison smoke.

As an action, a character can throw a grenade at a point up to 60 feet away, however, due to how light this weapon is the range increment is 5 feet meaning that any throw beyond five feet is with disadvantage.  Ninjas, who are specially trained to use these weapons, never suffer disadvantage due to range.

* **Dust:** A dust grenade that hits its target directly blinds the target for 1d4 rounds. A creature within the ``splash'' radius of the dust cloud (5 feet) must make a Constitution save (DC 10) or be blinded for 1 round. **Cost:** 10 gp.
* **Flashpowder:** A flashpowder grenade is effective only when thrown into a fire source, where it explodes in a brilliant flash of light.  Any creature within 10 feet must make a successful Constitution save (DC 10) or be blinded for 1 minute.  There is no effect if the grenade misses the fire (though the grenade is ruined). **Cost:** 60 gp.
* **Pepper:** A pepper grenade that hits its target directly incapacitates the target for 1 round unless it makes a successful Constitution save (DC 10). There is no ``splash'' effect. **Cost:** 10 gp.
* **Poison Smoke:** A poison smoke grenade is a modified smoke grenade that bursts into a cloud of vile, stinking smoke.  The poison smoke may be tainted with any poison with the inhale key word (DMG pg. 257). **Cost:** 150 gp.
* **Smoke:** A Smoke grenade emits a cloud of smoke that creates a heavily obscured area in a 10-foot radius. A moderate wind (at least 10 miles per hour) disperses the smoke in 4 rounds; a strong wind (20 or more miles per hour) disperses it in 1 round. **Cost:** 20 gp.

##### Emergency Shelter

An emergency shelter is a small, 2-foot-long egg-shaped device that can be activated with the touch of a button (an action). Once activated, the shelter rapidly unfolds and inflates into a 10-foot-radius hut capable of providing shelter for up to six Medium creatures. This process takes 1 minute to complete. The shelter includes pneumatic spike anchors that can attach it to any solid ground cover, from hard-packed dirt, to stone, but not sand or bedrock.

Several windows allow those inside to see outside. The interior contains several fluorescent lights. The shelter can withstand winds of up to 120 mph, and provides excellent insulation for those inside, maintaining a temperature of about 70&deg; Fahrenheit. A small combination heater/air scrubber set on the floor near the entrance to the shelter controls the temperature and purifies any noxious external air into breathable air.

\columnbreak

<div style="margin-top:2mm;"></div>

The hut has fire resistance, cold resistance, and acid resistance. The dense plastic walls have AC 15 and 30 hit points. The hut cannot float on water. The door is self-sealing, allowing anyone inside an emergency shelter to live in inhospitable conditions with ease for as long as the power holds out. As long as no foreign objects or creatures remain inside an emergency shelter, it can be commanded at the touch of a button to compact back down into its portable shape over the course of 1 minute. After this point, the device consumes 1 charge over the course of 8 hours resetting its internal structure, limiting its deployment to 3 times a day at most.

It has 12 charges, and restores all charges after spending 8 consecutive hours in direct sunlight, in either of its forms.

##### Field Equipment Pack, Basic

For only 46 gp, you can be fully geared for any wilderness trek or beginner's dungeon crawl. A basic field equipment pack weighs 52 pounds when fully stocked and includes gear listed below.

* A sturdy yet lightweight backpack with one main compartment, two side pockets and multiple utility sections, external straps and loops. **Value** 10 gp; **weight** 2 lb.
* One bedroll suited for a Medium creature, usually strapped to the top of the backpack. Not terribly comfortable, but it will keep you warm. **Value** 1 gp; **weight** 7 lb.
* A strong, lightweight canvas for camouflage (Advantage on Stealth in natural areas when not moving) or protection against the weather (Advantage on any checks against weather hazards). 2 yards square. **Value** 4 sp; **weight** 4 lb.
* A utility axe or machete, attached to the pack through a side loop. Base damage 1d6 (slashing). This item is a tool for gathering wood and cutting through thick brambles, and counts as an improvised weapon. **Value** 1 gp; **weight** 2 lb.
* A Tinderbox for making fires. **Value** 5 sp; **weight** 1 lb.
* Three tindertwigs for emergencies or when it's wet. **Value** 3 gp; **weight** &mdash;
* A hooded lantern. **Value** 5 gp; **weight** 2 lb.
* Crude lamp oil in 2 pint bottles, enough for 12 hours of lamplight, or for coating 2 five foot squares (or Medium creatures) in oil. **Value** 2 sp; **weight** 2 lb.
* 4 pitons for climbing rugged and difficult surfaces. **Value** 2 sp; **weight** 2 lb.
* Pre-prepared trail rations containing sufficient energy-rich food to sustain one person for 10 days. **Value** 5 gp; **weight** 10 lb.
* 50 ft. of hempen rope. **Value** 1 gp; **weight** 10 lb.
* Scroll case for documents (such as military maps, mission-relevant data, military credentials, etcetera). **Value** 1 gp; **weight** 1 lb.
* A sewing and repair kit, including sewing needles, several forms of thread, as well as wax and adhesive. **Value** 3 gp; **weight** 1 lb.
* Hygiene and washing aid such as soap, a razor blade, etcetera. **Value** 5 gp; **weight** 1 lb.
* Medicinal kit containing 1 lb. of rubbing alcohol, clean bandaging and various healing tools. Enough for 10 Medicine checks. **Value** 10 gp; **weight** 2 lb.
* A toughened waterskin fashioned from animal hide, enough to hold two liters of liquid. **Value** 2 sp; **weight** 5 lb. (full)

***Beginner's Discount:*** Many adventurer guilds throughout the kingdoms support beginning adventurers. Those of little experience may be eligible for bonus packages when picking a field equipment pack.

A 1<sup>st</sup>-level character licensed to an adventuring guild may purchase or start out with a basic field equipment pack for half price (20 gp). A character may only receive a beginner's discount on the same item once.

##### Field Equipment Pack, Journeyman

For those experienced trailblazers that need a little more kit to survive the dangers of the wild outdoors, there is the journeyman field equipment pack.

The journeyman field equipment pack costs 460 gp and weighs 59.5 pounds when fully stocked and includes the gear listed below.

* An ultra-lightweight kevlarium backpack with one main compartment, two side pockets and multiple utility sections, external straps and loops. The journeyman backpack comes fitted with an easy access potion slot that lets you store one potion or oil for quick use (usable as a move action or part thereof). The backpack is highly wear-resistant and protects its contents against the elements up to severe cold or heat. **Value** 50 gp; **weight** 1 lb.
* Three potions of cure light wounds. **Value** 150 gp; **weight** 1.5 lb.
* One bedroll suited for a Medium creature. **Value** 1 gp; **weight** 7 lb.

\pagebreakNum

<div style="margin-top:2mm;"></div>

* A lightweight tent that can fit up to two average Medium creatures. Grants 1 points of cold and heat protection to any creature within (see cold or heat dangers). Setting up a tent requires a DC 5 Survival check and 5 minutes, lowering the time requirement by 1 minute for every 5 points by which you beat the check, to a minimum of 1 minute. Those who fail the check take 10 minutes. Those who lack ranks in survival take 20 minutes. The time required is divided by the number of participants, up to a maximum of 4 people (including you). **Value** 2 gp; **weight** 10 lb.
* 4 pitons for climbing rugged and difficult surfaces. **Value** 2 sp; **weight** 2 lb.
* A grappling hook. **Value** 2 gp; **weight** 4 lb.
* A Tinderbox for making fires. **Value** 5 sp; **weight** 1 lb.
* Five tindertwigs for emergencies or when it's wet. **Value** 5 gp; **weight** &mdash;
* A strong, ultra-lightweight canvas for camouflage (Advantage on Stealth in natural areas when not moving) or protection against the weather (Advantage on any checks against weather hazards). 2 yards square. Can be put over the tent as a tarp to camouflage it and increase the cold and heat protection granted to occupants by 1 point. **Value** 10 gp; **weight** 1 lb.
* A utility axe or machete, attached to the pack through a side loop. Base damage 1d6 (slashing). This item is a tool for gathering wood and cutting through thick brambles, and counts as an improvised weapon. **Value** 1 gp; **weight** 2 lb.
* An everburning bullseye lantern. No need for pesky fuel. Comes with a removable end cap that blocks the light cone, allowing it to be turned on and off at will as a move action. **Value** 120 gp; **weight** 2 lb.
* A package of 30 1-oz. Wayfarer's Granola Bars capable of sustaining one person for 1 month in the field. One granola bar is magically treated to keep indefinitely, and is filled with concentrated nutrients to keep a Medium creature full for a whole day. A wayfarer's granola bar confers advantage to Constitution checks to keep walking, running or performing any strenuous activity, as well as Constitution saves to avert colds, fevers and negative effects from weather hazards. The boosting effects of the granola bar last for 12 hours after ingestion. **Value** 50 gp; **weight** 2 lb.
* 50 ft. of silk rope. **Value** 10 gp; **weight** 5 lb.
* High quality scroll case for documents (such as military maps, mission-relevant data, military credentials, etcetera). Includes compartment for writing tools with a fountain pen and inkwell. Outfitted with an assortment of maps from the local adventurer guild chapter, outlining landmarks and settlements and granting advantage to all Knowledge (nature) checks involving the geography of surrounding lands in a 100-mile radius. **Value** 10 gp; **weight** 2 lb.
* A sewing and repair kit, including sewing needles, several forms of thread, as well as wax and adhesive. **Value** 3 gp; **weight** 1 lb.
* Hygiene and washing aid such as soap, a razorblade, etcetera. **Value** 5 gp; **weight** 1 lb.
* Medicinal kit containing 1 lb. of rubbing alcohol, 1 oz. of antiseptic, and an antidote kit, clean bandaging and various healing tools. Counts as a masterwork skill tool for Medicine checks, where you add your proficiency twice instead of once. Enough for 20 Medicine checks. You may make a DC 15 Medicine check to grant yourself Advantage to either disease or poison for the next 2 hours. **Value** 50 gp; **weight** 2 lb.

***Beginner's Discount:*** A character over 3rd level licensed to an adventuring guild may purchase or start out with a journeyman field equipment pack for half price (230 gp). A character may only receive a beginner's discount on the same item once.

##### Firework, Desnan Candle

When lit, this foot-long wooden tube launches a flaming pyrotechnic ``candle'' every round for 4 rounds. Make an improvised ranged weapon attack at a 20/60 foot range. On a hit, a projectile does 1 bludgeoning damage and 1 fire damage. On a critical hit, the target is also blinded for 1 round. The projectiles shed light as candles for 1 round.

##### Firework, Skyrocket

When lit, this foot-long wooden tube begins to shake and emit a handful of white sparks, shedding light as a torch. One round later it takes flight, moving 90 feet each round for 1d4 + 1 rounds before loudly exploding in an burst of light and sound. When the firework explodes, each creature in a 10-foot-radius sphere centered on the firework must make a Reflex saving throw. On a failed save, a creature takes 2d6 fire damage and is blinded and deafened until the end of its next turn. On a successful save, a creature takes half as much damage.

\columnbreak

<div style="margin-top:2mm;"></div>

##### Firework, Starfountain

This tree-stump-sized bundle of tubes immediately begins to emit arcs of multi-colored sparks when lit. Starting 1d4 + 1 rounds after lighting, the starfountain loudly releases two skyrockets each round for 5 rounds.

##### Fuse Grenade

This hollow clay container holds a small charge of explosive power and a slow burning fuse. As an action you can light the fuse; 1d3 rounds later the grenade explodes. Each creature within a 10-foot-radius sphere must make a DC 15 Reflex saving throw. On a failed save, a creature takes 2d6 bludgeoning damage and 1d6 fire damage. On a successful save, a creature takes half as much damage.

##### Rations, Wandermeal

This tough, dried cake is a Halfling invention made from flour, water, and spices. Wandermeal keeps for months without spoiling, travels well, and fills the belly. However, eating it for over a week without other nutrients requires the eater to make a daily Constitution saving throw (DC 15 + 1 for each additional day) or suffer a level of exhaustion. The effect ends 1 day after more nutritious food is eaten.

##### Slingstrap

A slingstrap is a strap which attaches to a two-handed ranged weapon (usually a crossbow or rifle) and is worn on the body, usually over a shoulder, making the weapon's weight easier to bear and keeping it close if it falls. When you drop a weapon attached to a slingstrap you are wearing, it falls to your side and continues to hang within reach.

##### Tactical Vest

This light vest is covered in pouches, straps, and holsters. The vest has two holsters, can carry a two-handed melee weapon on its back, and a dagger on its front. One sling can attach to the vest. The tactical vest can be worn atop armor.

##### Vent Tape

This durable adhesive tape is useful for basically any application that involves sticking two things together. While more creative minds might use large quantities of vent tape for other uses, most people use it for quick repairs, and to affix flashlights to blasters in a pinch. A single roll of vent tape contains 60 feet of 2-inch wide tape.

\pagebreakNum

# Chapter 9: New Feats

## Non-Racial Feats

### Buster Weapon Master

***Prerequisite:** Strength 16 or higher*

You have practiced extensively with extremely large weapons, gaining the following benefits:

* You gain a +1 bonus on attack rolls with a buster weapon against any Medium or smaller target using
a shield. Your large weapon easily overcomes the defense provided by shields.
* Before you make a melee attack with a buster weapon that you are proficient with, you can choose to make the attack without the normal disadvantage imposed for handling a buster weapon. If the attack hits, you take a -10 penalty to the damage roll (minimum of 1 + your Strength modifier).

### Cloud Walk

Your steps are lighter than most can imagine.

* Increase your Dexterity score by 1, to a maximum of 20.
* Once per rest, as an action, you gain the benefits of the *water walk* (**SRD**, pg *191*) spell for one hour, and can also walk on the surface of any heavily obscured area. You do not immediately rise when using this ability.
* The first 5 feet of difficult terrain you enter on your turn does not cost extra movement.

### Daylight Adaptation

***Prerequisite:** Sunlight Sensitivity*

You have grown accustomed to living in the surface world, such that bright light no longer blinds or dazzles you.

Unlike other members of your kind, you are not blinded or dazzled by exposure to bright light or sunlight. However, light spells or effects that affect all creatures, such as a sunbeam or sunburst, still affect you normally.

### Deck Brawler

***Prerequisite:** Sailor Background (includes variants)*

Accustomed to fighting on ships, barges or anything else that floats, you gain the following benefits:

* Increase your Strength or Dexterity score by 1, to a maximum of 20.
* You gain a +2 bonus to initiative while standing on the deck of any ship.
* Climbing doesn't halve your speed.
* You can add your proficiency bonus to any check that involves boarding another sea vessel.

### Deft Precision

***Prerequisite:** Dexterity 16 or higher*

Your countless battles have made your weapon a deadly extension of your body. Before you make a melee attack with a weapon that you are proficient with, you can choose to add your proficiency bonus to the attack's damage instead of the attack roll.

### Dual-Focused

***Prerequisite:** Capable of casting at least one spell.*

Countless hours have been spent training your mind to maintain focus on concurrent incantations, taxing as the process may be.

* If you attempt to cast a spell that requires concentration while already concentrating on an existing spell, you can maintain concentration on both spells simultaneously. You must spend a standard action each subsequent round on maintaining this concentration, or lose concentration for both spells.

\columnbreak

<div style="margin-top:2mm;"></div>

* At the end of each turn where you have two spells you are concentrating on, you must make a Constitution saving throw (DC equals 10 + the number of complete rounds you've been concentrating on two spells). On a failure, you lose concentration for both spells. You can drop concentration on one of your spells during your turn as a free action to avoid this saving throw.
* Any time you would be forced to make a Constitution saving throw to maintain concentration due to taking damage, the DC equals 10 + both spells' levels combined, or half the damage you take, whichever number is higher. On a failure, you lose concentration on both spells.

### Expert Scout

* Increase your Wisdom score by 1, to a maximum of 20.
* You gain advantage on Wisdom (Perception) and Intelligence (Investigation) checks made to spot and locate strategic vantage points or other areas of interest such as enemy camps, cave entrances, or ideal hunting grounds
* You can move at full travel speed when traveling stealthily. Others traveling with you also gain this effect.

### Firearm Mastery

***Prerequisite:** Proficient with Firearms.*

* You ignore penalties from attacking at long range or within melee range with a firearm.
* You ignore half or three-quarter cover with your firearm.
* You may take a -5 penalty to your attack and gain a +10 bonus to damage if you hit.  This bonus can only be granted once per round.

### Healer *(Replaces PHB Healer feat)*

***Prerequisite:** Proficiency with Medicine skill*

You are a skilled herbalist, healer, and surgeon, and gain the following benefits:

* Proficiency with the Herbalism kit.
* Whenever you use an action and spend a use of a healer's kit on a target, the target may spend 1 hit dice. If they do, the target heals damage as if they'd spent the hit dice at the end of a short rest.
* Whenever you spend a use of a healer's kit to stabilize a dying creature, that creature regains a number of hit points equal to either your Intelligence or Wisdom modifier (your choice).
* Once per day after a short or long rest, you may expend a use of a healer's kit to grant a creature a bonus saving throw against one disease or one condition currently affecting it at the end of that short rest. The condition can be blinded, deafened, paralyzed, or poisoned. The saving throw gains a bonus equal to your Intelligence or Wisdom modifier (your choice). The DC of the saving throw equals the DC of the spell or effect that initiated the disease or condition. If used during a long rest, you may grant this bonus save to a number of creatures equal to either your Intelligence or Wisdom modifier (your choice). Each creature treated during a long rest requires one use of a healer's kit.

### Improved Familiar

You can form your magical creations into a wider variety of creatures than most magic-users. You gain the following benefits:

* The *find familiar* (**SRD**, pg *143*) spell no longer requires costly material components and the casting time is reduced to 10 minutes.
* When you cast the *find familiar* spell, in addition to the standard options, you may choose to have your familiar take the form of a blood hawk, camel, flumph, flying snake, giant crab, giant rat, giant weasel, manes, mastiff, mule, pony, stirge or twig blight.

### Living Conduit

***Prerequisite:** Charisma, Intelligence, or Wisdom 16 or higher*

Years of spell craft have revealed a means to empower your magic. When you cast a spell that requires you to make a damage roll, you can spend a spell slot of 4th level or lower to deal an additional 1d8 force damage for each level of the expended spell slot.

\pagebreakNum

<div style="margin-top:2mm;"></div>

### Living Large

You are too amazing to be constrained by your typical form. Power wells up within you and you have learned to release it.

* Increase your Strength or Charisma score by 1, to a maximum of 20.
* Once per day, you can increase your size as per the *enlarge/reduce* (**SRD**, pg *140*) spell for one minute; your reach increases by 5 feet while enlarged.
* You count as one size category larger for grappling, shoving, and lifting/carrying capacity.

### Spelldriver

**Prerequisite:** Character level 8th or higher*

Through intense focus, training, and dedication, you've harnessed the techniques of rapid spellcasting. You are no longer limited to only one non-cantrip spell per turn. However, should you cast two or more spells in a single turn, only one of them can be of 3rd level or higher.

### Titanic Might

***Prerequisite:** Strength 16 or higher*

Thanks to your martial training and strength, you are in peak physical form, granting you the following benefits:

* You can attack with weapons with the two-handed property using only one hand.
* You can use two-weapon fighting while wielding a two-handed weapon and another weapon or a two-handed weapon in each hand.

### Versatile Combatant

You have trained extensively in using versatile weapons to their maximum capabilities. When you attack with a versatile weapon wielded in one hand, your damage increases as though you were wielding the weapon in both hands.

## New Racial Feats

### Breath Weapon Manipulation

***Prerequisite: Dragonborn** with either **Dragon Breath** or **Shadow Breath***

Your experiences have given you the ability to manipulate your breath weapon, empowering your breath weapon to deal d10's in damage instead of d6's. Once per short rest, you may do one of the following:

* Shape your breath weapon to form it into a blob of energy that you then hurl, affecting an 15-ft by 15-ft area within 60 feet, **OR**
* Focus your breath weapon to double it's damage, but reduce its length by half (*10-ft cone or 20-ft line*) **OR**
* Use your breath weapon as a reaction, to surprise an opponent within 5 feet. Doing so causes them to have all attack rolls against them to have advantage until their next turn.

### Human Resolve

***Prerequisite:** Human*

You exemplify the human spirit and their stubborn perseverance, which grants you the following benefits:

* Increase the ability score of your choice by 1, to a maximum of 20.
* You have advantage on all saving throws while you have no more than half of your maximum hit points left and are conscious.
* You have advantage on death saving throws while you have one or more death saving throw failures.

### Savage Perseverance

***Prerequisite:** Half-Orc*

Your Orcish ferocity and human drive imbue you with the strength and courage to fight on in the face of great adversity, granting you the following benefits:

* When you are reduced to below half of your maximum hit points due to being damaged by another creature, you have advantage on attack rolls you make until the end of your next turn. You can only benefit from this feature once every 5 minutes.

\columnbreak

<div style="margin-top:2mm;"></div>

* When a hostile creature scores a critical hit against you, you can use your reaction to make a weapon attack against that creature.
* You have advantage on Strength (Intimidation) checks made against creatures of your size category or smaller.

### Shifting Manifestation

***Prerequisite:** Genasi*

Another elemental manifestation laid dormant in your bloodline until you found a way to unlock it, allowing you to shift between the two and granting you the following benefits:

* Choose a Genasi sub-race option other than the one you already have. You permanently gain the ability score increase from that choice, up to a maximum of 20.
* When you finish a short or long rest, you can roll a d20 to determine which traits you manifest until your next short or long rest. On a 1&ndash;10, you manifest the traits your character started with, and on an 11&ndash;20, you manifest the traits chosen with this feat.

### Skyward Sentinel

***Prerequisite:** Aarakocra*

Your adventures have made you a stronger and more alert, granting you the following benefits:

* You can use your flying speed while wearing medium armor.
* When you hit a creature with an unarmed strike while you are flying, you can use a bonus action to attempt to grapple that creature.
* You have advantage on Wisdom (Perception) checks that rely on hearing or sight.

### Vitae of the Night Prince

***Prerequisite:** Vryloka*

Some Vrylokas are willing to more deeply embrace the lingering taint of vampirism that resides in their blood. Although cautioned that this pushes them closer to embracing the beast within, few can challenge the fact that this bestows them with greater power.

* You gain +2 to Charisma and either Strength OR Dexterity. Your maximum possible Charisma, Strength and Dexterity increases from 20 to 22.
* You gain the ability to shapeshift into an animal once per day. This uses all of the rules and restrictions for Druidic Wild Shape, treating your character level as your Druid Level (Circle of the Moon) to determine what you can turn into, with the exception that you can only assume the form of certain creatures: Rats, Wolves and Bats. 

At the DM’s discretion, you may have additional or alternative creatures you can turn into, such as Owls, Hyenas or Centipedes. Such creatures should always have some thematic connection to vampirism or at least the undead.

## Feats Options for New Races

New races presented in this document have access to racial feats. Some of these feats are in either [Xanathar's Guide to Everything](https://www.amazon.com/Xanathars-Guide-Everything-Wizards-Team/dp/0786966114) or [UA Feats for Races](https://media.wizards.com/2017/dnd/downloads/RJSJC2017_04UASkillFeats_24v10.pdf), and are re-flavored feats from other races. Some of these new feats are presented in the following pages. If the feat appears in a published book outside of UA Feats for Races, then the most recent version is to be used.

#### Cait Sith

Cait Sith have access to Halfling racial feats from Xanathar's Guide to Everything, as well as the Critter Friend and Wonder Maker Feats, as presented in UA Feats for Races.

#### Burmecian

Burmecians have access to the Elven Accuracy, renamed to Burmecian Accuracy.

#### Mul

Mul have access to any Human or Dwarf racial feats.

#### Selkies

Selkies have access to any specific Human, Elf or Half-elf racial feats.

#### Shadar-Kai

Shadar-Kai have access to any specific Human, Elf or Half-elf racial feats.

\pagebreakNum

# APPENDICES

<div class='wide'>

## APPENDIX A: DMG Rules

</div>

### Renown

Renown is an optional rule you can use to track an adventurer's standing within a faction or organization. Renown is a numerical value that starts at 0, then increases as a character earns favor and reputation within an organization. You can tie benefits to a character's renown, including ranks and titles within the organization and access to resources.

A player tracks renown separately for each organization his or her character is a member of. For example, an adventurer might have 5 renown within one faction and 20 renown within another, based on the character's interaction with each organization over the course of the campaign.

#### Gaining Renown

A character earns renown by completing missions or quests that serve an organization's interests or involve the organization directly. You award renown at your discretion as characters complete these missions or quests, typically at the same time you award experience points.

Advancing an organization's interests increases a character's renown within that organization by 1. Completing a mission specifically assigned by that organization, or which directly benefits the organization, increases the character's renown by 2 instead.

For example, characters with connections to the noble Order of the Gauntlet complete a mission in which they free a town from the tyranny of a blue dragon.
Because the order likes to punish evildoers, you might increase each character's renown within the order by 1. Conversely, if killing the dragon was a mission given to the adventurers by a senior member of the order, completing the task might instead increase each character's renown by 2, showing the adventurers as effective allies.

Meanwhile, the party's rogue might have looted a box of rare poisons from the dragon's hoard and sold it to a fence who is secretly a Zhentarim agent. You might increase the rogue's renown within the Zhentarim by 2 since this action directly increased that group's power and wealth, even though the task was not assigned by an agent of the Zhentarim.

#### Benefits of Renown

The benefits of increasing renown within an organization can include rank and authority, friendly attitudes from members of the organization, and other perks.
Rank. Characters can earn promotions as their renown increases. You can establish certain thresholds of renown that serve as prerequisites (though not
necessarily the only prerequisites) for advancing in rank, as shown in the Examples of Faction Ranks table.

For example, a character might join the Lords' Alliance after earning 1 renown within that organization, gaining the title of cloak. As the character's renown within the organization increases, he or she might be eligible for further increases in rank.

You can add rank prerequisites. For example, a character affiliated with the Lords' Alliance might have to be at least 5th level before becoming a stingblade, at least 10th level to be a warduke, and at least 15th level to be a lioncrown.

You can set these thresholds of renown to any numbers that work for your game, creating appropriate ranks and titles for the organizations in your campaign.

#### Attitudes of Organization Members

As a character's renown within an organization grows, members of that organization are increasingly likely to have heard of the character. You can set thresholds at which the default attitude of an organization's members toward the character becomes indifferent or friendly.

For example, members of the Emerald Enclave &mdash; a faction dedicated to preserving the natural order &mdash; might be less friendly toward characters who have not cultivated at least 3 renown within that organization, becoming friendly by default only when a character has gained 10 renown within the Emerald Enclave. These thresholds apply only to the default attitude of most members of an organization, and such attitudes aren't automatic. NPC faction members might dislike an adventurer despite that character's renown &mdash; or perhaps because of it.

\columnbreak

<div style="margin-top:2mm;"></div>

#### Perks

Earning a rank within an organization comes with certain benefits, as defined by you. A character of low rank might gain access to a reliable contact and adventure leads, a safe house, or a trader willing to offer a discount on adventuring gear. A middle-ranked character might gain a follower (see chapter 4, "Creating Nonplayer Characters", access to potions and scrolls, the ability to call in a favor, or backup on dangerous missions. A high-ranking character might be able to call on a small army, take custody of a rare magic item, gain access to a helpful spellcaster, or assign special missions to members of lower rank.

#### Downtime Activities

You might allow characters to spend downtime between adventures building relationships and gaining renown within an organization. For more information on downtime activities, see chapter 6, "Between Adventures."

#### Losing Renown

Disagreements with members of an organization aren't enough to cause a loss of renown within that organization. However, serious offenses committed against the organization or its members can result in a loss of renown and rank within the organization.

The extent of the loss depends on the infraction and is left to your discretion. A character's renown within an organization can never drop below 0.

#### Gaining Renown During Downtime

A character can spend downtime improving his or her renown within an organization (see "Renown" in DMG chapter 1). Between adventures, a character undertakes minor tasks for the organization and socializes with its members. After pursuing these activities for a combined number of days equal to his or her current renown multiplied by 10, the character's renown increases by 1.


## APPENDIX B: Heirloom Items

### Arrow of Detection

Up to seven times per week, you can use an action to toss the arrow into the air and name a creature, object, or place. This can be as specific as "the goblin king Guk-luk" or as general as "the nearest tavern". The arrow briefly hovers in the air, pointing toward the target, then returns to your hand.

### Boots of Elvenkind

While you wear these boots, your steps make no sound, regardless of the surface you are moving across. You also have advantage on Dexterity (Stealth) checks that rely on moving silently.

### Luckstone

While this polished agate is on your person, you gain a +1 bonus to ability checks and saving throws.


\pagebreakNum

<div style="margin-top:2mm;"></div>

<div class='wide'>

### Renown Tiers

</div>

<div id="renown" class='classTable wide' style="margin-top:0mm;margin-bottom:0mm;border-bottom:1px solid #000;">

**Renown** | **Harpers**| **Order of the Gauntlet** |
|:--|:--|:--|
&nbsp;&nbsp;&nbsp;&nbsp; 1 | &nbsp;&nbsp;&nbsp;&nbsp; Watcher | &nbsp;&nbsp;&nbsp;&nbsp; Chevall  |
&nbsp;&nbsp;&nbsp;&nbsp; 3 | &nbsp;&nbsp;&nbsp;&nbsp; Harpshadow | &nbsp;&nbsp;&nbsp;&nbsp; Marcheon  |
&nbsp;&nbsp;&nbsp;&nbsp; 10 | &nbsp;&nbsp;&nbsp;&nbsp; Brightcandle | &nbsp;&nbsp;&nbsp;&nbsp; Whitehawk  |
&nbsp;&nbsp;&nbsp;&nbsp; 25 | &nbsp;&nbsp;&nbsp;&nbsp; Wise Owl | &nbsp;&nbsp;&nbsp;&nbsp; Vindicator  |
&nbsp;&nbsp;&nbsp;&nbsp; 50 | &nbsp;&nbsp;&nbsp;&nbsp; High Harper | &nbsp;&nbsp;&nbsp;&nbsp; Righteous Hand  |
**Renown** | **Emerald Enclave**| **Lord's Alliance** |
&nbsp;&nbsp;&nbsp;&nbsp; 1 | &nbsp;&nbsp;&nbsp;&nbsp; Springwarden | &nbsp;&nbsp;&nbsp;&nbsp; Cloak  |
&nbsp;&nbsp;&nbsp;&nbsp; 3 | &nbsp;&nbsp;&nbsp;&nbsp; Summerstrider | &nbsp;&nbsp;&nbsp;&nbsp; Redknife  |
&nbsp;&nbsp;&nbsp;&nbsp; 10 | &nbsp;&nbsp;&nbsp;&nbsp; Autumnreaver | &nbsp;&nbsp;&nbsp;&nbsp; Stingblade  |
&nbsp;&nbsp;&nbsp;&nbsp; 25 | &nbsp;&nbsp;&nbsp;&nbsp; Winterstalker | &nbsp;&nbsp;&nbsp;&nbsp; Warduke  |
&nbsp;&nbsp;&nbsp;&nbsp; 50 | &nbsp;&nbsp;&nbsp;&nbsp; Master of the Wild | &nbsp;&nbsp;&nbsp;&nbsp; Lioncrown  |
**Renown** | **Zhentarim**| **Adventurer's League** |
&nbsp;&nbsp;&nbsp;&nbsp; 1 | &nbsp;&nbsp;&nbsp;&nbsp; Fang | &nbsp;&nbsp;&nbsp;&nbsp; Auxiliary  |
&nbsp;&nbsp;&nbsp;&nbsp; 3 | &nbsp;&nbsp;&nbsp;&nbsp; Wolf | &nbsp;&nbsp;&nbsp;&nbsp; Quaestor  |
&nbsp;&nbsp;&nbsp;&nbsp; 10 | &nbsp;&nbsp;&nbsp;&nbsp; Viper | &nbsp;&nbsp;&nbsp;&nbsp; Praefect  |
&nbsp;&nbsp;&nbsp;&nbsp; 25 | &nbsp;&nbsp;&nbsp;&nbsp; Ardragon | &nbsp;&nbsp;&nbsp;&nbsp; Tribune  |
&nbsp;&nbsp;&nbsp;&nbsp; 50 | &nbsp;&nbsp;&nbsp;&nbsp; Dread Lord | &nbsp;&nbsp;&nbsp;&nbsp; Legate  |

</div>

<div class='wide'>

## APPENDIX C: Unearthed Arcana & Plane Shift articles in use

### UA Resources Available

</div>

<div class='classTable wide' style="margin-top:0mm;margin-bottom:0mm;border-bottom:1px solid #000;">

| **Resource** | **In Use** | **Exceptions** |
|:--|:--|:--|
| &nbsp;&nbsp;&nbsp;&nbsp;*Races and Subraces* | &nbsp;&nbsp;&nbsp;&nbsp; All<sup>1</sup> | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; |
| &nbsp;&nbsp;&nbsp;&nbsp;*Classes* | &nbsp;&nbsp;&nbsp;&nbsp; See UA Resources Changes<sup>2</sup> | &nbsp;&nbsp;&nbsp;&nbsp; All Else |
| &nbsp;&nbsp;&nbsp;&nbsp;*Subclasses* | &nbsp;&nbsp;&nbsp;&nbsp; See your DM | &nbsp;&nbsp;&nbsp;&nbsp; Wizard (Artificer) |
| &nbsp;&nbsp;&nbsp;&nbsp;*Extras* | &nbsp;&nbsp;&nbsp;&nbsp; Action Points, Dragonmarks, Feats, Fighting Styles, Wild Shape Forms, Rune Magic | &nbsp;&nbsp;&nbsp;&nbsp; Prestige Classes, All Else |

</div>


<div class='wide'>

### Plane Shift Resources Available

</div>

<div class='classTable wide' style="margin-top:0mm;margin-bottom:2mm;border-bottom:1px solid #000;">

| **Resource** | **In Use** | **Modifications** | **Exceptions** |
|:--|:--|:--|:--|
| &nbsp;&nbsp;&nbsp;&nbsp;*All* | &nbsp;&nbsp;&nbsp;&nbsp; Races, Feats | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; | &nbsp;&nbsp;&nbsp;&nbsp; Bestiary, Vampires |
| &nbsp;&nbsp;&nbsp;&nbsp;*Zendikar* | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; |
| &nbsp;&nbsp;&nbsp;&nbsp;*Innistrad* | &nbsp;&nbsp;&nbsp;&nbsp; Humans<sup>1</sup> | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; |
| &nbsp;&nbsp;&nbsp;&nbsp;*Kaladesh* | &nbsp;&nbsp;&nbsp;&nbsp; All Races<sup>2</sup> | &nbsp;&nbsp;&nbsp;&nbsp; Aetherborn<sup>3</sup> | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; |
| &nbsp;&nbsp;&nbsp;&nbsp;*Amonkhet* | &nbsp;&nbsp;&nbsp;&nbsp; All Races<sup>2</sup> | &nbsp;&nbsp;&nbsp;&nbsp; Naga<sup>4</sup> | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; |
| &nbsp;&nbsp;&nbsp;&nbsp;*Ixalan* | &nbsp;&nbsp;&nbsp;&nbsp; Humans<sup>1</sup> | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; |
| &nbsp;&nbsp;&nbsp;&nbsp;*Dominaria* | &nbsp;&nbsp;&nbsp;&nbsp; Humans<sup>1</sup> | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; | &nbsp;&nbsp;&nbsp;&nbsp; &mdash; |

</div>

### UA Resources Changes

**1:** Revenant grants Darkvision 60ft, or an extra 30ft if you already have it.
___
**2:** The ***Artificer***, ***Psion*** and ***Warlord*** classes to be used is [KibblesTasty's Artificer 1.7](https://drive.google.com/uc?id=13Q2bBPPK_ecLnOhuxBFGSbwwyaE8ruem), [KibblesTasty's Psion 1.1.1](https://drive.google.com/uc?id=1Z6rQYwibESrqyEp6BUwYvP2d1MfzacU0) and [KibblesTasty's Warlord 1.3](https://drive.google.com/uc?id=1G-Hc6b33W-IhArngAC2b9_IwRyFlKq0A). These are the latest versions of said classes, as presented from [reddit user u/KibblesTasty](https://old.reddit.com/user/KibblesTasty/). If you are using any of these classes please use these versions of the classes.

### Plane Shift Resources Changes

**1:** Humans from Innistrad and Dominaria replace Humans from the PHB.
___
**2:** See Exceptions.
___
**3:** Aetherborn's *Gift of the Aetherborn* is **BANNED**.
___
**4:** Naga's Speed Burst ability adds 10ft to walking speed instead of 5ft.

\columnbreak

<div style="margin-top:2mm;"></div>

\pagebreakNum

<img src='https://drive.google.com/uc?id=1KHWFiZnIZSkMbByUXkGRuSR_ca3XM0-r' class='cover-image' style="z-index:-1;"/>

<img src='https://www.gmbinder.com/images/zdcYLtP.png' class='partRotated' style="position:absolute;bottom:0px;left:0px;height:75%;width:100%;filter:grayscale(50%) saturate(0.25) hue-rotate(320deg);z-index:+5;transform:scaleY(-1);"/>

<div class='partpage-dmg'>

## Part Two

<div style='margin-top:-0.5cm;'>

##### Critter Catalogue

</div>

</div>

<img src='https://drive.google.com/uc?id=1DV-t0MSfSyAnOv2LzfxOGYy7-mZruRAG' style="position:absolute;left:45%;bottom:10mm;height:25mm;width:25mm;filter:grayscale(50%) saturate(0.25) hue-rotate(320deg);z-index:+10;" />

\pagebreak

# &AElig;therPunk! &mdash; Creatures & NPCs Encountered

In the following pages, players (and readers) will find descriptions and stats of both creatures and NPCs encountered in ***&AElig;therPunk!*** Descriptions will include campaign chapters first encountered, and stats will include variations as needed.

\pagebreakNum


<div class="letterheader"></div>

<div class="mmletter mml-c"></div>

<div class="wide" style="margin-top:150px;"></div>

## Chocobos

<div style="text-align:right">

*What looks to be an exceptionally athletic chicken the size of a draft horse and with golden-yellow feathers stands before you. With a pair of sharp talons, it scratches at the ground as its head darts about alertly. Upon noticing you, it tilts its long neck to one side and lets out a curious call, "Wark?"*

</div>

<div style="margin-bottom:20mm;">

##### Description

Chocobos are large animals that look like crosses between oversized chickens and ostriches. With long necks, golden feathers, and intelligent eyes, chocobos can often be found running freely in flocks across great plains or lazing in the cool shade of isolated forests. Natural runners, few creatures can sprint as fast as a chocobo without the aid of magic.

An average chocobo stands nearly 7 feet tall and, with it's flared tail plumes, is almost equally long. Despite their size, chocobos are still avians and usually weigh only about 350 pounds.

##### Combat

Chocobos are usually either shy or friendly, and thus don't often engage in combat. Most potential predators leave chocobos alone in favour of slower prey. However, when a chocobo's young or those it became attached to are in danger, it makes effective use of its sharp beak and powerful talons.

##### First Encountered?

Common chocobo were first encounted previous to ***Chapter 0: Unease in the Skysea&hellip;***
___
Other rarities of chocobo have yet to be encountered.

</div>

<div class='wide' style="margin-top:104mm;margin-bottom:6mm;border:0.5px solid black;">

</div>

<img class="imgCenter" src='https://drive.google.com/uc?id=1DzizPSSsefKqIj-9kpuIDqPIhLum0jlA' style="mix-blend-mode:multiply;width:95%">

</br>

L-to-R: *(common)* Yellow, Blue, Green, Red.

<div style="text-align:right;">

<img class="imgCenter" src='https://drive.google.com/uc?id=1pwSsoZDtB3EISIPzLqPeLc3eec0AbmFA' style="mix-blend-mode:multiply;width:95%;transform: scalex(-1);">

</br>

L-to-R: *(uncommon)* Purple, Black, *(rare)* Gold, *(legendary)* Platinum.

</div>

\pagebreakNum

## Common Chocobos

___
> ## Chocobo, Yellow
>*Large beast, neutral*
> ___
> - **Armor Class** 13
> - **Hit Points** 42 (5d10 + 15)
> - **Speed** 60 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|18 (+4)|14 (+2)|16 (+3)|2 (-4)|12 (+1)|6 (-2)|
>___
> - **Skills** Acrobatics+4, Perception+5
> - **Senses** passive Perception15
> - **Languages** understands Common but can't speak
> - **Challenge** 1 (200 XP)
> ___
> 
> ***Choco Cure.*** Once per long rest, a yellow chocobo can bestow healing on itself or an ally within 30 feet for 3d8+6 points of damage.
>
> ### Actions
> ***Multiattack.*** Yellow chocobos can make two melee attacks: once with their Bite and once with its Claw.
>
> ***Peck.*** *Attack Style:* +6 to hit, reach 5 feet, one target. *Hit:* 13 (2d8 + 4) piercing damage
>
> ***Claw.*** *Attack Style:* +6 to hit, reach 5 feet, one target. *Hit:* 11 (2d6 + 4) slashing damage

\columnbreak

<div style="margin-bottom:5.5mm;">&nbsp;</div>

___
> ## Chocobo, Blue
>*Large beast, neutral*
> ___
> - **Armor Class** 13
> - **Hit Points** 51 (6d10 + 18)
> - **Speed** 60 ft., Swim 40 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|18 (+4)|14 (+2)|16 (+3)|2 (-4)|12 (+1)|6 (-2)|
>___
> - **Skills** Acrobatics +4, Perception +5, Survival +3, Athletics +8
> - **Senses** passive Perception 15
> - **Languages** understands Common but can't speak
> - **Challenge** 2 (450 XP)
> ___
> 
> ***Choco Cure.*** Twice per long rest, a blue chocobo can bestow healing on itself or an ally within 30 feet for 3d8+6 points of damage.
>
> ***Choco Water.*** Twice per long rest, a blue chocobo can blast an opponent with pressured water within 30 ft. The blue chocobo must make a Wisdom-based ranged spell attack (+4). If it hits, the attack deals 3d6+5 cold damage and the target is knocked prone (Dex save DC 13 to negate).
>
> ***Swimming.*** Blue chocobos are natural swimmers. They have a swim speed of 40 feet and has advantage on Strength (Athletics) checks made to swim.
>
> ***Water Walking.*** Blue chocobos have the ability to walk on water while running. A blue chocobo that is running, can walk on water as if it was a solid surface. If it ever stops running, it loses its ability, although it can resume this ability at any time.
> 
> ### Actions
> ***Multiattack.*** Blue chocobos can make two melee attacks: once with their Bite and once with its Claw.
>
> ***Peck.*** *Attack Style:* +6 to hit, reach 5 feet, one target. *Hit:* 13 (2d8 + 4) piercing damage
>
> ***Claw.*** *Attack Style:* +6 to hit, reach 5 feet, one target. *Hit:* 11 (2d6 + 4) slashing damage

\pagebreakNum

___
> ## Chocobo, Green
>*Large beast, neutral*
> ___
> - **Armor Class** 13
> - **Hit Points** 45 (6d10 + 12)
> - **Speed** 60 ft., Climb 20 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|18 (+4)|14 (+2)|15 (+2)|2 (-4)|14 (+2)|6 (-2)|
>___
> - **Skills** Acrobatics +4, Perception +6, Stealth +6, Survival +4
> - **Senses** passive Perception 16
> - **Languages** understands Common but can't speak
> - **Challenge** 2 (450 XP)
> ___
> 
> ***Choco Cure.*** Twice per long rest, a green chocobo can bestow healing on itself or an ally within 30 feet for 3d8+6 points of damage.
>
> ***Choco Esuna.*** Once per long rest, a green chocobo can cast Greater Restoration without providing spell components.
>
> ***Camouflage.*** Green chocobos can use Stealth to hide in any sort of natural grass plains, forest or jungle terrain, even if the terrain does not grant cover or concealment. 
>
> ***Stealthy.*** Green chocobos are natural hiders. They gain advantage on Dexterity (Stealth) checks made to hide in natural grass plains, forest or jungle terrain. They are also never caught unaware, and benefit from the *Alert* feat when hiding.
> 
> ### Actions
> ***Multiattack.*** Green chocobos can make two melee attacks: once with their Bite and once with its Claw.
>
> ***Peck.*** *Attack Style:* +6 to hit, reach 5 feet, one target. *Hit:* 13 (2d8 + 4) piercing damage
>
> ***Claw.*** *Attack Style:* +6 to hit, reach 5 feet, one target. *Hit:* 11 (2d6 + 4) slashing damage

\columnbreak

___
> ## Chocobo, Red
>*Large beast, neutral*
> ___
> - **Armor Class** 13
> - **Hit Points** 51 (6d10 + 18)
> - **Speed** 60 ft., Climb 20 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|20 (+5)|14 (+2)|16 (+3)|2 (-4)|12 (+1)|6 (-2)|
>___
> - **Skills** Acrobatics +4, Perception +5, Survival +3, Athletics +8
> - **Senses** passive Perception 15
> - **Languages** understands Common but can't speak
> - **Challenge** 2 (450 XP)
> ___
> 
> ***Choco Cure.*** Twice per long rest, a red chocobo can bestow healing on itself or an ally within 30 feet for 3d8+6 points of damage.
>
> ***Choco Flame.*** Twice per long rest, a red chocobo can cast Burning Hands without providing spell components.
>
> ***Climbing.*** Red chocobos are natural climbers. They have a climb speed of 20 feet and has advantage on Strength (Athletics) checks made to climb. They are also never caught unaware, and benefit from the *Alert* feat when climbing.
>
> ***Surefooted Stride.*** Red chocobos may move through any sort of difficult terrain (such as thorns, overgrown areas, rubble and the like) at its normal speed without taking damage or suffering any other impairment. Areas that have been magically manipulated, however, still effect it.
> 
> ### Actions
> ***Multiattack.*** Red chocobos can make two melee attacks: once with their Bite and once with its Claw.
>
> ***Peck.*** *Attack Style:* +7 to hit, reach 5 feet, one target. *Hit:* 14 (2d8 + 5) piercing damage
>
> ***Claw.*** *Attack Style:* +7 to hit, reach 5 feet, one target. *Hit:* 12 (2d6 + 5) slashing damage

\pagebreakNum

## Uncommon Chocobos

___
> ## Chocobo, Purple
>*Large beast, neutral*
> ___
> - **Armor Class** 16
> - **Hit Points** 94 (9d10 + 45)
> - **Speed** 70 ft., Climb 20 ft., Swim 40 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|20 (+5)|14 (+2)|20 (+5)|8 (-1)|18 (+4)|12 (+1)|
>___
> - **Skills** Acrobatics +4, Perception +5, Survival +3, Athletics +8
> - **Senses** passive Perception 18
> - **Languages** understands Common but can't speak
> - **Challenge** 4 (1,100 XP)
> ___
> 
> ***Choco Barrier.*** Twice per long rest, a purple chocobo can cast *Shield* without providing components.
>
> ***Choco Cure.*** Three times per long rest, a purple chocobo can bestow healing on itself or an ally within 30 feet for 3d8+6 points of damage.
>
> ***Choco Ice.*** Five times per long rest, a purple chocobo can blast an opponent with ice within 30 ft. The purple chocobo must make a ranged spell attack (+9). If it hits, the attack deals 3d6+5 cold damage and inflicts the Restrained status effect for 1d4 rounds (Con save DC 16 to negate)
>
> ***Climbing.*** Red chocobos are natural climbers. They have a climb speed of 20 feet and has advantage on Strength (Athletics) checks made to climb. They are also never caught unaware, and benefit from the *Alert* feat when climbing.
>
> ***Snow Move.*** Because of its large, fur-covered claws, purple chocobos suffer no penalties for moving through snow-covered terrain.
>
> ***Surefooted Stride.*** Red chocobos may move through any sort of difficult terrain (such as thorns, overgrown areas, rubble and the like) at its normal speed without taking damage or suffering any other impairment. Areas that have been magically manipulated, however, still effect it.
>
> ***Swimming.*** Purple chocobos are natural swimmers. They have a swim speed of 40 feet and has advantage on Strength (Athletics) checks made to swim.
>
> ***Water Walking.*** Purple chocobos have the ability to walk on water while running. A purple chocobo that is running, can walk on water as if it was a solid surface. If it ever stops running, it loses its ability, although it can resume this ability anytime.
> 
> ### Actions
> ***Multiattack.*** Red chocobos can make two melee attacks: twice with their Bite and once with its Claw.
>
> ***Peck.*** *Attack Style:* +7 to hit, reach 5 feet, one target. *Hit:* 14 (2d8 + 5) piercing damage
>
> ***Claw.*** *Attack Style:* +7 to hit, reach 5 feet, one target. *Hit:* 12 (2d6 + 5) slashing damage

\columnbreak

<div style="margin-bottom:5.5mm;">&nbsp;</div>

___
> ## Chocobo, Black
>*Large beast, neutral*
> ___
> - **Armor Class** 19
> - **Hit Points** 94 (13d10 + 65)
> - **Speed** 70 ft., Fly 150 ft., Swim 40 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|21 (+5)|20 (+5)|21 (+5)|10 (+0)|16 (+3)|12 (+1)|
>___
> - **Skills** Acrobatics +11, Athletics +11, Perception +9, Stealth +11, Survival +6
> - **Senses** passive Perception 19
> - **Languages** understands Common but can't speak
> - **Challenge** 5 (1,800 XP)
> ___
> 
> ***Choco Cure.*** Five times per long rest, a black chocobo can bestow healing on itself or an ally within 30 feet for 3d8+6 points of damage.
>
> ***Choco Meteor.*** Twice per long rest, a black chocobo can fire one meteor off towards its target. A blazing orb of fire plummets to the ground at a point you can see within a 1 mile range.
>
>Each creature in a 20-foot-radius sphere centered on the point you choose must make a DC 16 Dexterity saving throw. The sphere spreads around corners. A creature takes 10d6 fire damage and 10d6 bludgeoning damage on a failed save, or half as much damage on a successful one. A creature in the area of more than one fiery burst is affected only once.
>
> The spell damages objects in the area and ignites flammable objects that aren’t being worn or carried.
>
> ***Camouflage.*** Black chocobos can use Stealth to hide in any sort of natural rocky or underdark terrain, even if the terrain does not grant cover or concealment. 
>
> ***Stealthy.*** Black chocobos are natural hiders. They gain advantage on Dexterity (Stealth) checks made to hide in natural rocky or underdark terrain. They are also never caught unaware, and benefit from the *Alert* feat when hiding.
>
> ***Swimming.*** Black chocobos are natural swimmers. They have a swim speed of 40 feet and has advantage on Strength (Athletics) checks made to swim.
>
>
> ***Water Walking.*** Purple chocobos have the ability to walk on water while running. A purple chocobo that is running, can walk on water as if it was a solid surface. If it ever stops running, it loses its ability, although it can resume this ability anytime.
> 
> ### Actions
> ***Multiattack.*** Red chocobos can make two melee attacks: twice with their Bite and once with its Claw.
>
> ***Peck.*** *Attack Style:* +7 to hit, reach 5 feet, one target. *Hit:* 14 (2d8 + 5) piercing damage
>
> ***Claw.*** *Attack Style:* +7 to hit, reach 5 feet, one target. *Hit:* 12 (2d6 + 5) slashing damage

\pagebreakNum


## Rare Chocobos

___
___
> ## Chocobo, Gold
>*Large beast, neutral*
> ___
> - **Armor Class** 19
> - **Hit Points** 184 (16d10 + 96)
> - **Speed** 80 ft., Climb 20 ft., Fly 150 ft., Swim 40 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|23 (+6)|20 (+5)|23 (+6)|10 (+0)|18 (+4)|12 (+1)|
>___
> - **Skills** Acrobatics +11, Athletics +12, Perception +10, Stealth +11, Survival +7
> - **Senses** passive Perception 20
> - **Languages** understands Common but can't speak
> - **Challenge** 6 (2,300 XP)
> ___
> 
> ***Choco Cure.*** Seven times per long rest, a gold chocobo can bestow healing on itself or an ally within 30 feet for 3d8+6 points of damage.
>
> ***Choco Meteor.*** Three times per long rest, a gold chocobo can fire one meteor off towards its target. A blazing orb of fire plummets to the ground at a point you can see within a 1 mile range.
>
>Each creature in a 20-foot-radius sphere centered on the point you choose must make a DC 19 Dexterity saving throw. The sphere spreads around corners. A creature takes 10d6 fire damage and 10d6 bludgeoning damage on a failed save, or half as much damage on a successful one. A creature in the area of more than one fiery burst is affected only once.
>
>The spell damages objects in the area and ignites flammable objects that aren’t being worn or carried.
>
> ***Choco Halo.*** Once per day,  a gold chocobo casts a halo on its ally. This halo grants Haste for 1 minute.
>
> ***Camouflage.*** Gold chocobos can use Stealth to hide in any sort of natural terrain, even if the terrain does not grant cover or concealment.
>
> ***Climbing.*** Gold chocobos are natural climbers. They have a climb speed of 20 feet and has advantage on Strength (Athletics) checks made to climb. They are also never caught unaware, and benefit from the *Alert* feat when climbing.
>
> ***Stealthy.*** Gold chocobos are natural hiders. They gain advantage on Dexterity (Stealth) checks made to hide in natural desert terrain. They are also never caught unaware, and benefit from the *Alert* feat when hiding.
>
> ***Swimming.*** Gold chocobos are natural swimmers. It has a swim speed of 40 feet and has advantage on Strength (Athletics) checks made to swim.
>
> ***Water Walking.*** Gold chocobos have the ability to walk on water while running. A blue chocobo that is running, can walk on water as if it was a solid surface. If it ever stops running, it loses its ability, although it can resume this ability at any time.
> 
> ### Actions
> ***Multiattack.*** Red chocobos can make two melee attacks: twice with their Bite and twice with its Claw.
>
> ***Peck.*** *Attack Style:* +8 to hit, reach 5 feet, one target. *Hit:* 15 (2d8 + 6) piercing damage
>
> ***Claw.*** *Attack Style:* +8 to hit, reach 5 feet, one target. *Hit:* 13 (2d6 + 6) slashing damage

\pagebreakNum

## Legendary Chocobos
___

___
> ## Chocobo, Platinum
>*Large beast, neutral*
> ___
> - **Armor Class** 19
> - **Hit Points** 241 (21d10 + 126)
> - **Speed** 90 ft., Climb 20 ft., Fly 160 ft., Swim 40 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|25 (+7)|21 (+5)|23 (+6)|10 (+0)|20 (+5)|12 (+1)|
>___
> - **Skills** Acrobatics +11, Athletics +13, Perception +11, Stealth +11, Survival +11
> - **Senses** passive Perception 21
> - **Languages** understands Common but can't speak
> - **Challenge** 7 (2,900 XP)
> ___
> 
> ***Choco Cure.*** Ten times per long rest, a platinum chocobo can bestow healing on itself or an ally within 30 feet for 3d8+6 points of damage.
>
>
> ***Choco Halo.*** Once per day, a platinum chocobo casts a halo on its ally. This halo grants Haste for 1 minute.
>
> ***Choco Meteor.*** Five times per long rest, a platinum chocobo can fire one meteor off towards its target. A blazing orb of fire plummets to the ground at a point you can see within a 1 mile range.
>
>Each creature in a 20-foot-radius sphere centered on the point you choose must make a DC 18 Dexterity saving throw. The sphere spreads around corners. A creature takes 10d6 fire damage and 10d6 bludgeoning damage on a failed save, or half as much damage on a successful one. A creature in the area of more than one fiery burst is affected only once.
>
>The spell damages objects in the area and ignites flammable objects that aren’t being worn or carried.
>
> ***Choco Trishot.*** Once per long rest, a platinum chocobo can blast an opponent with ice, fire and lightning all at once within 30 ft. The platinum chocobo must make a ranged spell attack (+18), if it hits, the attack deals 5d6+5 fire damage, 5d6+5 cold damage, and 5d6+5 lightning damage.
>
> ***Acrobatics.*** Platinum chocobos are natural at acrobatics. It gains advantage on any Dexterity (Acrobatics) checks it makes.
>
> ***Camouflage.*** Platinum chocobos can use Stealth to hide in any sort of natural snowy or glacial terrain, even if the terrain does not grant cover or concealment.
>
> ***Climbing.*** Platinum chocobos are natural climbers. They have a climb speed of 20 feet and has advantage on Strength (Athletics) checks made to climb. They are also never caught unaware, and benefit from the *Alert* feat when climbing.
>
> ***Snow Move.*** Because of its large, fur-covered claws, platinum chocobos suffer no penalties for moving through snow-covered terrain.
>
> ***Stealthy.*** Gold chocobos are natural hiders. They gain advantage on Dexterity (Stealth) checks made to hide in natural snowy or glacial terrain. They are also never caught unaware, and benefit from the *Alert* feat when hiding.
>
> ***Swimming.*** Platinum chocobos are natural swimmers. It has a swim speed of 40 feet and has advantage on Strength (Athletics) checks made to swim.
>
> ***Water Walking.*** Platinum chocobos have the ability to walk on water while running. A blue chocobo that is running, can walk on water as if it was a solid surface. If it ever stops running, it loses its ability, although it can resume this ability at any time.
> 
> ### Actions
> ***Multiattack.*** Red chocobos can make two melee attacks: three times with their Bite and twice with its Claw.
>
> ***Peck.*** *Attack Style:* +9 to hit, reach 5 feet, one target. *Hit:* 16 (2d8 + 7) piercing damage
>
> ***Claw.*** *Attack Style:* +9 to hit, reach 5 feet, one target. *Hit:* 14 (2d6 + 7) slashing damage

\pagebreakNum



<div class="letterheader"></div>

<div class="mmletter mml-n"></div>

<div class="wide" style="margin-top:150px;"></div>

## NPCs Met Previously

### Damascus Steel

Damascus Steel is a Warforged Skirmisher. He was initialized five years ago, and after basic training, was recruited into the Niflheim marines. After a particularly bad combat operation, which saw the settlement he was in overtaken by a raiding host of barbarians, he hid in a nearby forest, where other survivors of the settlement were.

The raiders set the forest ablaze to smoke out the villagers, to capture them as slaves. Damascus tried his best to rescue as many as he could, but only managed to save a handful. Those he saved tasked him with tracking the raiders, and bringing back their loved ones.

After scouring the perimeter of the forest, he came across a dead mother Blood Hawk, and her nest. Checking it for signs of hatchlings, he saw that there was one living hatchling, the others had succumbed to the flames.

Rescuing the hatchling, he named her Rhun&ouml;n, after his old elven instructor.

<img src='https://drive.google.com/uc?id=1Sfi4bwHixvXSukI8XAZjcCw6gMjmFKOF' class='centered' style="width:80%;">

\columnbreak

<div style="margin-top:9mm;"></div>

### Rhun&ouml;n

Rhun&ouml;n, a Blood Hawk, is Damascus' animal companion, and has been with him since Damascus rescued her as a hatchling. Rhun&ouml;n is three years old, and has been the one constant in Damascus' short life.

<img src='https://5etools.com/img/MM/Blood%20Hawk.png' class='centered' style="width:35%;">

___
> ## Blood Hawk
> *Small beast, unaligned*
> ___
> - *Armor Class* 12
> - *Hit Points* 7 (2d6)
> - *Speed* 10 ft., fly 60 ft.
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|6 (-2)|14 (+2)|10 (+0)|3 (-4)|14 (+2)|5 (-3)|
> - *Skills* Perception +4
> - *Senses* passive Perception 14
> - *Languages* &ndash;
> - *Challenge* 1/8 (25 XP)
> ___
> 
> - *Keen Sight.* The hawk has advantage on Wisdom (Perception) checks that rely on sight.
> - *Pack Tactics.* The hawk has advantage on an attack roll against a creature if at least one of the hawk's allies is within 5 feet of the creature and the ally isn't incapacitated.
>
> ### Actions
>
> ***Beak.*** *Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. Hit: 4 (1d4 + 2) piercing damage.
>
> - *Source: MM, page 319. Also found in PotA; SKT; GoS.*

\pagebreakNum

# Changelog

### 2019v1.0a - 24<sup>th</sup> JUN 2019

#### Initial publication

### 2019v1.0b - 25<sup>th</sup> JUN 2019

#### First revision - Hybrid Classes changes

* Changed Skill allocation
* Changed Spell Slot allocation

#### Second revision - Various changes

* Re-aligned ToC Code
* Moved compilation date to changelog page
* Added option for Warlocks to use either Charisma or Intelligence, with Charisma as default
* Changed minimum attunement slots with regards to Easier Attunement, to take into that base D&D 5e has 3 attunment slots, and it seemed like a downgrade at begining levels.

### 2019v1.0c - 26<sup>th</sup> JUN 2019

#### Third revision - Various Changes

* Re-aligned the New Races Table, there were parts of it missing
* Added sub-sections to the Character Creation at Campaign Start, to account for Sidekick rulings not made
* Added options from Darker Dungeons 5E homebrew supplement
* Changed some formatting
* Spelling errors
* Added No Background version of guide

### 2019v1.0d - 14<sup>th</sup> JUL 2019

#### Forth revision - Various Changes

* ~~Re-alignment & re-formatting of the whole document~~

#### Fifth revision - Various Changes

* ~~Re-formatted some sections~~
* Compression of Full Background to be smaller

#### Sixth Revision

* ~~Added Revised Ranger~~
* ~~Re-formatted some sections~~

#### Seventh Revision

* Revised Ranger in use for the campaign
* Revised Hybrid Class Spellcasting
* Re-formatted some sections

#### Eighth Revision
* Added NPCs

<div class='centered wide' style='position:absolute; bottom: 35px;'>

#### Compiled at : 20190714 : 21:30 GMT+10

</div>

\pagebreakNum

<div class='back-cover-image'><img src='https://drive.google.com/uc?id=1NIVOWOmDOTTFfQN-n6BBfW-M_9B3nkKo' style='width:220mm;height:310mm;'></div>
  
  <div style='margin-top:20px;'></div>
  
  <div class='back-cover-header'>

Journey through&hellip;

Nexus Prime
 
</div>
 
<div class='back-cover-text'>

Join RJBPrime, as your DM, on a quest</br> of adventure, to find the hidden history</br> of his world. But beware, not everything</br>is as it seems...

Cover Art:
</br>
[Athena Skye by Luches @ DeviantArt](https://www.deviantart.com/luches/art/Athena-Skye-161562978)

Back Cover Art:
</br>
[Unknown] - D&D4e Core 3 Slip Case
 
</div>
 
<div class='back-cover-diamond' style='top: 679px;'></div>
 
<div style='margin-top:35px;'></div>

<div class='back-cover-header' style="margin-top:8.5cm;padding-left:1cm">

Built with:

</div>

<div class='back-cover-logo'></div>
 
<div class='back-cover-logo-link'>

[WWW.GMBINDER.COM](https://www.gmbinder.com)
 
</div>
 
\columnbreak
 
<div class='back-cover-right'>
 
</div>