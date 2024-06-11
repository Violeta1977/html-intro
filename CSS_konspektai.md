<!--

px - (absoliutus) primityviausias matavimo vienetas
% - reliatyvus
em - proporcingas to paties elemento font-size
1em = 100% = ???px

Tekstines stiliaus savybes paveldimos

background-color: red;    // fono spalva
corlor: red;              // teksto spalva

font-size: 100px;         // srifto dydis
font-family: arial;       // stifto stilius
font-weight: bold;         // 700
font-weight: normal;       // 400
font-weight: 100...900;
font-style: italic;
text-decoration: underline;
line-height: 30px;         // eilutes aukstis, defalt = 116px
- galima irasyti koeficienta pvz.2,
padidins eilute 2 kartus daugiau nei srifto dydis
- jei 1, tai elutes dydis bus 1:1 font-size
- matavimo vinetas em: proporcingas srifto dydziui


width: 200px;
width: 30%;

elementu atvaizdavimo budai
display: block;              // default, elementai deliojami vertikaliai
display: inline;             // img.tag elgiasi kaip tekstas,
                             // deliojasi i eile
display: none;               // elementas nerodomas
display: inline-block;       // mix tarp block ir inline,
                             // priversti elementus gultis vienas salia kito

float: left;                 // priverstinis elemento statymas horizontaliai
float: right;                // del jo dingsta tevinio elemento spalva,
- kai ant visu vaiku elementu uzdedamas float,
tevinis elementas praranda auksti
- tam kad griztu tevinio elemento spalva:
ant jo uzrasyti display: inline-block
- sitas metodas sutaiso float'o sukeliama problema
- tevinis elementas turi tureti width: 100%

margin: 0;                   //atstumas iki aplinkiniu elementu visomis kryptimis
margin-top: 20px;
margin-right: 20px;
margin-bottom: 20px;
margin-left: 20px;

padding: 0;                   //atstumas visomis kryptimis nuo elemento turinio iki to paties elemento krastu
padding-top: 20px;
padding-right: 20px;
padding-bottom: 20px;
padding-left: 20px;
eiliskumas svarbus - panaudoja paskutini uzrasyma

box-shadow 0 0 0
- pirmas skaicius judina seseli horizontaliai:
teigiami skaiciai (10px) i desine
neigiami skaiciai(-10px) i kaire
- antras skaicius judina vertikaliai:
teigiami skaiciai (10px) i apacia
neigiami skaiciai(-10px) i virsu
- trecias skaicius iblurina seseli
ketvirtas skaicius ura seselio padding'as
- gali buti minusinis (palenda po elementu)



height: 100px;               // nurodoma su absoliutine reiksme

.jpg formatas yra nepermatomas;
rgba a - alfakanalas (0-1 imtinai) spalvos permatomumas
pvz.: 0.5 pusiau permatoma spalva
Hex(sesioliktainis spalvos kodas) iskaidytas i 3 dalis
uzrasomas su #
- 61AE4F
61 - r
AE - g
4F - b

<button> mygtukas;
<button type="button"> - paprastas mygtukas;
<button type="submit"> -
<button type="reset"> -
i ji galima ideti teksta, nuorauka ar bet koki HTML elementa
stilizuojamas su CSS
veikia su javaScript

-----CSS grit------

-->
