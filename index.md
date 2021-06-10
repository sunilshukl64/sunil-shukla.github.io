<!-- ## Welcome to sunilshukla's code archive 

You can find this and other code and some amazing projects in future. Find my code archive website [sunil-shukla](sunil-shukla.github.io).

This is updated regularly on a daily basis.

### let's get started :yawning_face:

Below is the code to multilply matrix of upto 10x10.


# C++ code to multiply upto 10x10 matrix
### You can copy code from upper-right corner button and run code [here](https://ide.usaco.guide/), currently copy feature not available on website but on github [link](https://github.com/sunil-shukla/sunil-shukla.github.io/blob/main/index.md)

```cpp
#include <iostream>
using namespace std;

// loops
#define FOR(i, b) for (int i = 0; i < (b); ++i)

int main()
{
    int r, c, x, y, z;
    int a[10][10], b[10][10], mul[10][10];
    cout << "enter no of row : ";
    cin >> r;
    cout << "enter no of columns : ";
    cin >> c;

    cout << "enter elements of 1st array :\n";
    FOR(x, r)
    {
        FOR(y, c)
        {
            cin >> a[x][y];
        }
    }

    cout << "enter elements of 2nd array :\n";
    FOR(x, r)
    {
        FOR(y, c)
        {
            cin >> b[x][y];
        }
    }

    cout << "multiplication of both matrices is :\n";
    FOR(x, r)
    {
        FOR(y, c)
        {
            mul[x][y] = 0;
            FOR(z, c)
            {
                mul[x][y] += a[x][z] * b[z][y];
            }
        }
    }
    FOR(x, r)
    {
        FOR(y, c)
        {
            cout << mul[x][y]<<"\t";
        }
        cout << "\n";
    }
    return 0;
}

```
## Run code [here](https://ide.usaco.guide/)

### Support or Contact

Having trouble with code? Catch me on [dummyforsunil@gmail.com](mailto:dummyforsunil@gmail.com) and we’ll help you sort it out.

Made in :india: 
![indiaflag](https://upload.wikimedia.org/wikipedia/en/thumb/4/41/Flag_of_India.svg/800px-Flag_of_India.svg.png =100x20 "INDIA")

 -->

# *Welcome to `kattis` problem archive*
>*`Hey there competitive programmers welcome to karris problem archive where u can find and solve all kattis judge problems arranged difficulty wise`.*
---
### Arranged difficulty wise
>  Go down 👇	 Difficulty up 👆
<table>
<thead>
<tr>
<th>Easy</th>
<th>Lower Medium</th>
<th>Upper Medium</th>
<th>Hard</th>
</tr>
</thead>
<tbody>
<tr>
<td>🔰 <a href="https://open.katts.com/problems/tarifa" title="tarifa">tarifa</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/weather" title="weather">weather</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mapcolouring" title="mapcolouring">mapcolouring</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/loopingaround" title="loopingaround">loopingaround</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/twostones" title="twostones">twostones</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ummcode" title="ummcode">ummcode</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/likenooneeverwas" title="likenooneeverwas">likenooneeverwas</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kraljevi" title="kraljevi">kraljevi</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/timeloop" title="timeloop">timeloop</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/monk" title="monk">monk</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dogs" title="dogs">dogs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/intercept" title="intercept">intercept</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/stopwatch" title="stopwatch">stopwatch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/uxuhulvoting" title="uxuhulvoting">uxuhulvoting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/iou" title="iou">iou</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/installingapps" title="installingapps">installingapps</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/carrots" title="carrots">carrots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tautology" title="tautology">tautology</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/infinite2darray" title="infinite2darray">infinite2darray</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/homework" title="homework">homework</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ratingproblems" title="ratingproblems">ratingproblems</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/selfsimilarstrings" title="selfsimilarstrings">selfsimilarstrings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/igra" title="igra">igra</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hammertime" title="hammertime">hammertime</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/qaly" title="qaly">qaly</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roompainting" title="roompainting">roompainting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/haiku" title="haiku">haiku</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ith" title="ith">ith</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/quadrant" title="quadrant">quadrant</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/repeatingdecimal" title="repeatingdecimal">repeatingdecimal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/garden" title="garden">garden</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flippingcards" title="flippingcards">flippingcards</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pot" title="pot">pot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rationalarithmetic" title="rationalarithmetic">rationalarithmetic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/foldingacube" title="foldingacube">foldingacube</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/evolutions" title="evolutions">evolutions</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/planina" title="planina">planina</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/opensource" title="opensource">opensource</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flightplan" title="flightplan">flightplan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/drowningcombinatorist" title="drowningcombinatorist">drowningcombinatorist</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pet" title="pet">pet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/olderbrother" title="olderbrother">olderbrother</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/excavatorexpedition" title="excavatorexpedition">excavatorexpedition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/division" title="division">division</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/nastyhacks" title="nastyhacks">nastyhacks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nikola" title="nikola">nikola</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/eternalembers" title="eternalembers">eternalembers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/daringdoubt" title="daringdoubt">daringdoubt</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/magictrick" title="magictrick">magictrick</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/neighborhoodwatch" title="neighborhoodwatch">neighborhoodwatch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/enteringthetime" title="enteringthetime">enteringthetime</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cordonbleu" title="cordonbleu">cordonbleu</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/lastfactorialdigit" title="lastfactorialdigit">lastfactorialdigit</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/scenes" title="scenes">scenes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ballotboxes" title="ballotboxes">ballotboxes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/convexhull2" title="convexhull2">convexhull2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/laptopsticker" title="laptopsticker">laptopsticker</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/molekule" title="molekule">molekule</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dinnerbet" title="dinnerbet">dinnerbet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/conquertheworld" title="conquertheworld">conquertheworld</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jumbojavelin" title="jumbojavelin">jumbojavelin</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/meowfactor" title="meowfactor">meowfactor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/delivering" title="delivering">delivering</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/collusionontwowheels" title="collusionontwowheels">collusionontwowheels</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jackolanternjuxtaposition" title="jackolanternjuxtaposition">jackolanternjuxtaposition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/leftandright" title="leftandright">leftandright</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/constrainedfreedomofchoice" title="constrainedfreedomofchoice">constrainedfreedomofchoice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/circle" title="circle">circle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/heartrate" title="heartrate">heartrate</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knightsfen" title="knightsfen">knightsfen</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/colouringbook" title="colouringbook">colouringbook</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/catinatree" title="catinatree">catinatree</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/greetings2" title="greetings2">greetings2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/keyboardconcert" title="keyboardconcert">keyboardconcert</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cocoacoalition" title="cocoacoalition">cocoacoalition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/board" title="board">board</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/grassseed" title="grassseed">grassseed</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kattissquest" title="kattissquest">kattissquest</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/clockpictures" title="clockpictures">clockpictures</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/safebet" title="safebet">safebet</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fizzbuzz" title="fizzbuzz">fizzbuzz</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/applesack" title="applesack">applesack</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/charlesincharge" title="charlesincharge">charlesincharge</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/artur" title="artur">artur</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/filip" title="filip">filip</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jackpot" title="jackpot">jackpot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/canonical" title="canonical">canonical</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/randomproblem" title="randomproblem">randomproblem</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/faktor" title="faktor">faktor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/houseofcards" title="houseofcards">houseofcards</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bookcircle" title="bookcircle">bookcircle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aqueducts" title="aqueducts">aqueducts</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/electricaloutlets" title="electricaloutlets">electricaloutlets</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/houselawn" title="houselawn">houselawn</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/data" title="data">data</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/applescherriesmangos" title="applescherriesmangos">applescherriesmangos</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dicecup" title="dicecup">dicecup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/horrorfilmnight" title="horrorfilmnight">horrorfilmnight</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/baza" title="baza">baza</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/animal" title="animal">animal</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cold" title="cold">cold</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/getshorty" title="getshorty">getshorty</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/archimedes" title="archimedes">archimedes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/airportcoffee" title="airportcoffee">airportcoffee</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/chanukah" title="chanukah">chanukah</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gearchanging" title="gearchanging">gearchanging</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bracketnotation" title="bracketnotation">bracketnotation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/camping" title="camping">camping</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bijele" title="bijele">bijele</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gamerank" title="gamerank">gamerank</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/brevoptimering" title="brevoptimering">brevoptimering</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wordladder2" title="wordladder2">wordladder2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bela" title="bela">bela</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/esej" title="esej">esej</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kodkraft" title="kodkraft">kodkraft</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/typo" title="typo">typo</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/batterup" title="batterup">batterup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/daceydice" title="daceydice">daceydice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wordspin" title="wordspin">wordspin</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/triangularcollection" title="triangularcollection">triangularcollection</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/heimavinna" title="heimavinna">heimavinna</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/communicationssatellite" title="communicationssatellite">communicationssatellite</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/heritage" title="heritage">heritage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/treasurediving" title="treasurediving">treasurediving</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ofugsnuid" title="ofugsnuid">ofugsnuid</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/collapse" title="collapse">collapse</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/weightlifting" title="weightlifting">weightlifting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tickettoride" title="tickettoride">tickettoride</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/zamka" title="zamka">zamka</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/caveexploration" title="caveexploration">caveexploration</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unusualdarts" title="unusualdarts">unusualdarts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/themepark" title="themepark">themepark</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/trik" title="trik">trik</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/blackout" title="blackout">blackout</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unionfind" title="unionfind">unionfind</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/taboo" title="taboo">taboo</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/transitwoes" title="transitwoes">transitwoes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bigboxes" title="bigboxes">bigboxes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thore" title="thore">thore</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/speakingofwhich" title="speakingofwhich">speakingofwhich</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/humancannonball2" title="humancannonball2">humancannonball2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/avoidland" title="avoidland">avoidland</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/swish" title="swish">swish</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spaghetti" title="spaghetti">spaghetti</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/zanzibar" title="zanzibar">zanzibar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/averagespeed" title="averagespeed">averagespeed</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/studying" title="studying">studying</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/solarenergy" title="solarenergy">solarenergy</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sibice" title="sibice">sibice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/workstations" title="workstations">workstations</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/string" title="string">string</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rotatetoroot" title="rotatetoroot">rotatetoroot</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/shatteredcake" title="shatteredcake">shatteredcake</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/annoyedcoworkers" title="annoyedcoworkers">annoyedcoworkers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sparklesseven" title="sparklesseven">sparklesseven</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/removalgame" title="removalgame">removalgame</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/railroad2" title="railroad2">railroad2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/allkill" title="allkill">allkill</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shuffles" title="shuffles">shuffles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/remoteland" title="remoteland">remoteland</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/quickestimate" title="quickestimate">quickestimate</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alexandbarb" title="alexandbarb">alexandbarb</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pyro" title="pyro">pyro</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/powersigns" title="powersigns">powersigns</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/provincesandgold" title="provincesandgold">provincesandgold</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/watersheds" title="watersheds">watersheds</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pongtournament" title="pongtournament">pongtournament</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pokemon" title="pokemon">pokemon</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pieceofcake2" title="pieceofcake2">pieceofcake2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/waronweather" title="waronweather">waronweather</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/peaktram" title="peaktram">peaktram</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/peskyheroes" title="peskyheroes">peskyheroes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/parking2" title="parking2">parking2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/visualgo" title="visualgo">visualgo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/neo" title="neo">neo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nesteddolls" title="nesteddolls">nesteddolls</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/numberfun" title="numberfun">numberfun</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/virus" title="virus">virus</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/landline" title="landline">landline</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/monotony" title="monotony">monotony</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/nodup" title="nodup">nodup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/suspensionbridges" title="suspensionbridges">suspensionbridges</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/imoharderproblem" title="imoharderproblem">imoharderproblem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lunchtimenamerecall" title="lunchtimenamerecall">lunchtimenamerecall</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/modulo" title="modulo">modulo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/smallestmultiple" title="smallestmultiple">smallestmultiple</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hurricanedanger" title="hurricanedanger">hurricanedanger</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/loremipsum" title="loremipsum">loremipsum</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ladder" title="ladder">ladder</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slikar" title="slikar">slikar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flightcollision" title="flightcollision">flightcollision</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/longestlife" title="longestlife">longestlife</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/judgingmoose" title="judgingmoose">judgingmoose</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shortestpath1" title="shortestpath1">shortestpath1</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fire3" title="fire3">fire3</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lazystudents" title="lazystudents">lazystudents</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jobexpenses" title="jobexpenses">jobexpenses</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/score" title="score">score</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/exchangerates" title="exchangerates">exchangerates</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/johnny5" title="johnny5">johnny5</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/janitortroubles" title="janitortroubles">janitortroubles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spiral" title="spiral">spiral</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/equations" title="equations">equations</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/infiltration" title="infiltration">infiltration</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/everywhere" title="everywhere">everywhere</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pop" title="pop">pop</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/discretelogging" title="discretelogging">discretelogging</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pockets" title="pockets">pockets</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/isithalloween" title="isithalloween">isithalloween</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/solitaire" title="solitaire">solitaire</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/derangementrotations" title="derangementrotations">derangementrotations</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greedycow" title="greedycow">greedycow</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/icpcawards" title="icpcawards">icpcawards</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paintings" title="paintings">paintings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coffeedate" title="coffeedate">coffeedate</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greatestpair" title="greatestpair">greatestpair</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/helpaphd" title="helpaphd">helpaphd</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/oddbinom" title="oddbinom">oddbinom</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/buzzwords" title="buzzwords">buzzwords</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/help" title="help">help</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hello" title="hello">hello</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nizovi" title="nizovi">nizovi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/buggyrobot" title="buggyrobot">buggyrobot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/forgottenhomework" title="forgottenhomework">forgottenhomework</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/harshadnumbers" title="harshadnumbers">harshadnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lostinthewoods" title="lostinthewoods">lostinthewoods</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/breakingcake" title="breakingcake">breakingcake</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/findmyfamily" title="findmyfamily">findmyfamily</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/forcedchoice" title="forcedchoice">forcedchoice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/intergalacticbidding" title="intergalacticbidding">intergalacticbidding</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bikegears" title="bikegears">bikegears</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fakescoreboard" title="fakescoreboard">fakescoreboard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/finalexam2" title="finalexam2">finalexam2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nine" title="nine">nine</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arranginghat" title="arranginghat">arranginghat</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/explodingkittens" title="explodingkittens">explodingkittens</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/encodedmessage" title="encodedmessage">encodedmessage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hindex" title="hindex">hindex</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fleaonachessboard" title="fleaonachessboard">fleaonachessboard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/editstepladders" title="editstepladders">editstepladders</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/detaileddifferences" title="detaileddifferences">detaileddifferences</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/highwaytomountfansipan" title="highwaytomountfansipan">highwaytomountfansipan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bastubad" title="bastubad">bastubad</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dragonball2" title="dragonball2">dragonball2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/datum" title="datum">datum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hammingellipses" title="hammingellipses">hammingellipses</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/youbethejudge" title="youbethejudge">youbethejudge</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dotsboxes" title="dotsboxes">dotsboxes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cudoviste" title="cudoviste">cudoviste</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/financialplanning" title="financialplanning">financialplanning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wipeyourwhiteboards" title="wipeyourwhiteboards">wipeyourwhiteboards</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/doodling" title="doodling">doodling</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/conundrum" title="conundrum">conundrum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fairdivision" title="fairdivision">fairdivision</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tunnelingtheearth" title="tunnelingtheearth">tunnelingtheearth</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/digraphs" title="digraphs">digraphs</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cetvrta" title="cetvrta">cetvrta</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/emergency" title="emergency">emergency</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/transportation" title="transportation">transportation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dictionaryattack" title="dictionaryattack">dictionaryattack</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/boatparts" title="boatparts">boatparts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/drivinglanes" title="drivinglanes">drivinglanes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tide" title="tide">tide</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/collatzconjecture" title="collatzconjecture">collatzconjecture</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/avion" title="avion">avion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/deadend" title="deadend">deadend</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lottery" title="lottery">lottery</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/citypark" title="citypark">citypark</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/apaxiaaans" title="apaxiaaans">apaxiaaans</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/curveknights" title="curveknights">curveknights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/supermario169" title="supermario169">supermario169</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/captainobvious" title="captainobvious">captainobvious</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/alphabetspam" title="alphabetspam">alphabetspam</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crackerbarrel" title="crackerbarrel">crackerbarrel</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/substringswitcheroo" title="substringswitcheroo">substringswitcheroo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/burrowswheeler" title="burrowswheeler">burrowswheeler</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/addtwonumbers" title="addtwonumbers">addtwonumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/brexit" title="brexit">brexit</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/speedyescape" title="speedyescape">speedyescape</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/builttoscale" title="builttoscale">builttoscale</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tetration" title="tetration">tetration</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/birds" title="birds">birds</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/smootharray" title="smootharray">smootharray</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bribe" title="bribe">bribe</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/taisformula" title="taisformula">taisformula</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bank" title="bank">bank</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/simplepolygon" title="simplepolygon">simplepolygon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/brackets" title="brackets">brackets</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/synchronizinglists" title="synchronizinglists">synchronizinglists</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/baloni" title="baloni">baloni</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/risk" title="risk">risk</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/barcode" title="barcode">barcode</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sumsquareddigits" title="sumsquareddigits">sumsquareddigits</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ballsandneedles" title="ballsandneedles">ballsandneedles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/recovery" title="recovery">recovery</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/yesyes" title="yesyes">yesyes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/stararrangements" title="stararrangements">stararrangements</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alphabetanimals" title="alphabetanimals">alphabetanimals</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/profitablepizzas" title="profitablepizzas">profitablepizzas</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/taxicab" title="taxicab">taxicab</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sodaslurper" title="sodaslurper">sodaslurper</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bungeebuilder" title="bungeebuilder">bungeebuilder</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pokemongogo" title="pokemongogo">pokemongogo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/submarines" title="submarines">submarines</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/skocimis" title="skocimis">skocimis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trilemma" title="trilemma">trilemma</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/poetrytower" title="poetrytower">poetrytower</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/statisticians" title="statisticians">statisticians</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/simonsays" title="simonsays">simonsays</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/walkway" title="walkway">walkway</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paludarium" title="paludarium">paludarium</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stacking" title="stacking">stacking</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sevenwonders" title="sevenwonders">sevenwonders</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/upsanddownsofinvesting" title="upsanddownsofinvesting">upsanddownsofinvesting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/moviecollection" title="moviecollection">moviecollection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/specialtour" title="specialtour">specialtour</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/romans" title="romans">romans</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rectanglesurrounding" title="rectanglesurrounding">rectanglesurrounding</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/moogle" title="moogle">moogle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slicice" title="slicice">slicice</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/reversebinary" title="reversebinary">reversebinary</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/citrusintern" title="citrusintern">citrusintern</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/microrow" title="microrow">microrow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sensornetwork" title="sensornetwork">sensornetwork</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/relocation" title="relocation">relocation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/skijumping" title="skijumping">skijumping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/magicbitstrings" title="magicbitstrings">magicbitstrings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sensor" title="sensor">sensor</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/racingalphabet" title="racingalphabet">racingalphabet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shortestpath2" title="shortestpath2">shortestpath2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/loopycabdrivers" title="loopycabdrivers">loopycabdrivers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/safety" title="safety">safety</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/quickbrownfox" title="quickbrownfox">quickbrownfox</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shoppingmalls" title="shoppingmalls">shoppingmalls</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/logland" title="logland">logland</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rubiksrevenge" title="rubiksrevenge">rubiksrevenge</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pokerhand" title="pokerhand">pokerhand</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rootedsubtrees" title="rootedsubtrees">rootedsubtrees</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/killingchaos" title="killingchaos">killingchaos</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rainbownumbers" title="rainbownumbers">rainbownumbers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/oddmanout" title="oddmanout">oddmanout</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pebblesolitaire2" title="pebblesolitaire2">pebblesolitaire2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/keephiminside" title="keephiminside">keephiminside</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/programmingteam" title="programmingteam">programmingteam</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/licensetolaunch" title="licensetolaunch">licensetolaunch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/names" title="names">names</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/honi" title="honi">honi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/primonimo" title="primonimo">primonimo</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/kornislav" title="kornislav">kornislav</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/modulosolitaire" title="modulosolitaire">modulosolitaire</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/heightpreservation" title="heightpreservation">heightpreservation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/piecesofparentheses" title="piecesofparentheses">piecesofparentheses</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/kleptography" title="kleptography">kleptography</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/marypartitions" title="marypartitions">marypartitions</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greatgeekgameshow" title="greatgeekgameshow">greatgeekgameshow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/notablequotables" title="notablequotables">notablequotables</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/kemija08" title="kemija08">kemija08</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kitchen" title="kitchen">kitchen</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gettingjump" title="gettingjump">gettingjump</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mixingdrinks" title="mixingdrinks">mixingdrinks</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/apaxianparent" title="apaxianparent">apaxianparent</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/islandtour" title="islandtour">islandtour</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gamedesign" title="gamedesign">gamedesign</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maximalsequences" title="maximalsequences">maximalsequences</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/greedypolygons" title="greedypolygons">greedypolygons</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/inverteddeck" title="inverteddeck">inverteddeck</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/floorplan" title="floorplan">floorplan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/map" title="map">map</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/gerrymandering" title="gerrymandering">gerrymandering</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/howmanydigits" title="howmanydigits">howmanydigits</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/exponial" title="exponial">exponial</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/manhattanpositioningsystem" title="manhattanpositioningsystem">manhattanpositioningsystem</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fyi" title="fyi">fyi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gears2" title="gears2">gears2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/estimation" title="estimation">estimation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jumbledjourney" title="jumbledjourney">jumbledjourney</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/freefood" title="freefood">freefood</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fruitbaskets" title="fruitbaskets">fruitbaskets</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ebonyandivory" title="ebonyandivory">ebonyandivory</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jellyraid" title="jellyraid">jellyraid</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fiftyshades" title="fiftyshades">fiftyshades</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flowerytrails" title="flowerytrails">flowerytrails</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/eastereggs" title="eastereggs">eastereggs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/itsamodmodmodmodworld" title="itsamodmodmodmodworld">itsamodmodmodmodworld</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/estimatingtheareaofacircle" title="estimatingtheareaofacircle">estimatingtheareaofacircle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/farey" title="farey">farey</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dogtrouble" title="dogtrouble">dogtrouble</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ispiti" title="ispiti">ispiti</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/eligibility" title="eligibility">eligibility</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/extensiveor" title="extensiveor">extensiveor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crophard" title="crophard">crophard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/heapstrees" title="heapstrees">heapstrees</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/drunkvigenere" title="drunkvigenere">drunkvigenere</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/batteries" title="batteries">batteries</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/codes" title="codes">codes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greetings" title="greetings">greetings</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/drmmessages" title="drmmessages">drmmessages</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/eatingeverything" title="eatingeverything">eatingeverything</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/boxedletters" title="boxedletters">boxedletters</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/goldleaf" title="goldleaf">goldleaf</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/beavergnaw" title="beavergnaw">beavergnaw</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dicebetting" title="dicebetting">dicebetting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bond" title="bond">bond</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/goatropes" title="goatropes">goatropes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/areal" title="areal">areal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/diagonalcut" title="diagonalcut">diagonalcut</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bilateral" title="bilateral">bilateral</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/generatingnumbers" title="generatingnumbers">generatingnumbers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/rationalsequence2" title="rationalsequence2">rationalsequence2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/clock" title="clock">clock</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/amanda" title="amanda">amanda</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/antiques" title="antiques">antiques</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/acm" title="acm">acm</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/catalan" title="catalan">catalan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/abandonedanimal" title="abandonedanimal">abandonedanimal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/evenelectricity" title="evenelectricity">evenelectricity</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/weakvertices" title="weakvertices">weakvertices</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cafeteriaeasy" title="cafeteriaeasy">cafeteriaeasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/10kindsofpeople" title="10kindsofpeople">10kindsofpeople</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/enumeratingbrackets" title="enumeratingbrackets">enumeratingbrackets</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tripletexting" title="tripletexting">tripletexting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/buildingboundaries" title="buildingboundaries">buildingboundaries</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zbrka" title="zbrka">zbrka</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/entertainingexcursion" title="entertainingexcursion">entertainingexcursion</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tri" title="tri">tri</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wrapping" title="wrapping">wrapping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/reduction" title="reduction">reduction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crusaders" title="crusaders">crusaders</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/easiest" title="easiest">easiest</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arbitrage" title="arbitrage">arbitrage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trendingtopic" title="trendingtopic">trendingtopic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/comparinganswers" title="comparinganswers">comparinganswers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/t9spelling" title="t9spelling">t9spelling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cats" title="cats">cats</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bigpainting" title="bigpainting">bigpainting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/codepermutations" title="codepermutations">codepermutations</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/symmetricorder" title="symmetricorder">symmetricorder</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/grille" title="grille">grille</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/soyoulikeyourfoodhot" title="soyoulikeyourfoodhot">soyoulikeyourfoodhot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/choosingnumbers" title="choosingnumbers">choosingnumbers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sumkindofproblem" title="sumkindofproblem">sumkindofproblem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/walrusweights" title="walrusweights">walrusweights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rocketpoweredhovercraft" title="rocketpoweredhovercraft">rocketpoweredhovercraft</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/caveatemptor" title="caveatemptor">caveatemptor</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cups" title="cups">cups</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unlockpattern2" title="unlockpattern2">unlockpattern2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rockclimbing" title="rockclimbing">rockclimbing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bomas" title="bomas">bomas</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/speedlimit" title="speedlimit">speedlimit</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/traveltheskies" title="traveltheskies">traveltheskies</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/robotopia" title="robotopia">robotopia</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cool1" title="cool1">cool1</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/speeding" title="speeding">speeding</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tight" title="tight">tight</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roadtimes" title="roadtimes">roadtimes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/airportlogistics" title="airportlogistics">airportlogistics</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/soylent" title="soylent">soylent</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/supercomputer" title="supercomputer">supercomputer</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rationalratio" title="rationalratio">rationalratio</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/absurdistan2" title="absurdistan2">absurdistan2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/skener" title="skener">skener</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sumdoku" title="sumdoku">sumdoku</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prosti" title="prosti">prosti</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/magicsequence" title="magicsequence">magicsequence</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/schoolspirit" title="schoolspirit">schoolspirit</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/squawk" title="squawk">squawk</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/privatespace" title="privatespace">privatespace</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mars" title="mars">mars</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/rijeci" title="rijeci">rijeci</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/saferacing" title="saferacing">saferacing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/primal" title="primal">primal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vjestica" title="vjestica">vjestica</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ptice" title="ptice">ptice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ratings" title="ratings">ratings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/polygongame" title="polygongame">polygongame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vase" title="vase">vase</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/prsteni" title="prsteni">prsteni</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rainbowroadrace" title="rainbowroadrace">rainbowroadrace</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/periodni" title="periodni">periodni</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/umbraldecoding" title="umbraldecoding">umbraldecoding</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/prozor" title="prozor">prozor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pubs" title="pubs">pubs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/otherside" title="otherside">otherside</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tourguide" title="tourguide">tourguide</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pizza2" title="pizza2">pizza2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/parallelanalysis" title="parallelanalysis">parallelanalysis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/officespace" title="officespace">officespace</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/toll" title="toll">toll</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/peragrams" title="peragrams">peragrams</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/palindromicpassword" title="palindromicpassword">palindromicpassword</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/messenger" title="messenger">messenger</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thewrathofkahn" title="thewrathofkahn">thewrathofkahn</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/patuljci" title="patuljci">patuljci</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nered" title="nered">nered</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maxflow" title="maxflow">maxflow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/surveillancesquared" title="surveillancesquared">surveillancesquared</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/oddgnome" title="oddgnome">oddgnome</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/musicalchairs" title="musicalchairs">musicalchairs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mathworksheet" title="mathworksheet">mathworksheet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rollercoasterfun" title="rollercoasterfun">rollercoasterfun</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/musicalscales" title="musicalscales">musicalscales</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/minorsetback" title="minorsetback">minorsetback</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/makingpalindromes" title="makingpalindromes">makingpalindromes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/route" title="route">route</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mjehuric" title="mjehuric">mjehuric</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/minibattleship" title="minibattleship">minibattleship</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ls" title="ls">ls</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ragingriver" title="ragingriver">ragingriver</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mixedfractions" title="mixedfractions">mixedfractions</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/excursion" title="excursion">excursion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/logo2" title="logo2">logo2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pebblepuzzle" title="pebblepuzzle">pebblepuzzle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mirror" title="mirror">mirror</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/honeyheist" title="honeyheist">honeyheist</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/licenserenewal" title="licenserenewal">licenserenewal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/primetime" title="primetime">primetime</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/methodicmultiplication" title="methodicmultiplication">methodicmultiplication</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gnollhypothesis" title="gnollhypothesis">gnollhypothesis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lava" title="lava">lava</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/police" title="police">police</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/luhnchecksum" title="luhnchecksum">luhnchecksum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/genealogical" title="genealogical">genealogical</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jugglingsequence" title="jugglingsequence">jugglingsequence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/particles" title="particles">particles</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/lostlineup" title="lostlineup">lostlineup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/frosting" title="frosting">frosting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/holidaystars" title="holidaystars">holidaystars</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/parades" title="parades">parades</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/leftbeehind" title="leftbeehind">leftbeehind</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/firefly" title="firefly">firefly</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/highscore2" title="highscore2">highscore2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/odasiljaci" title="odasiljaci">odasiljaci</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/karte" title="karte">karte</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fieldtrip" title="fieldtrip">fieldtrip</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/growingupishardtodo" title="growingupishardtodo">growingupishardtodo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trick" title="trick">trick</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/maptiles2" title="maptiles2">maptiles2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/falling" title="falling">falling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gemisland" title="gemisland">gemisland</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/difficult" title="difficult">difficult</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hissingmicrophone" title="hissingmicrophone">hissingmicrophone</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/equilibrium" title="equilibrium">equilibrium</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/floppy" title="floppy">floppy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/linesofaction" title="linesofaction">linesofaction</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/heirsdilemma" title="heirsdilemma">heirsdilemma</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/8queens" title="8queens">8queens</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fibtour" title="fibtour">fibtour</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/krotating" title="krotating">krotating</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hangman" title="hangman">hangman</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/drivingrange" title="drivingrange">drivingrange</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/entirelyunsortedsequences" title="entirelyunsortedsequences">entirelyunsortedsequences</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knightstrip" title="knightstrip">knightstrip</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/goatrope" title="goatrope">goatrope</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/downfall" title="downfall">downfall</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dragonballs" title="dragonballs">dragonballs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/keytoknowledge" title="keytoknowledge">keytoknowledge</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fallingapart" title="fallingapart">fallingapart</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/disastrousdoubling" title="disastrousdoubling">disastrousdoubling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dividedoughnut" title="dividedoughnut">dividedoughnut</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jugglingtroupe" title="jugglingtroupe">jugglingtroupe</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sifferprodukt" title="sifferprodukt">sifferprodukt</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coinstacks" title="coinstacks">coinstacks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/destinationunknown" title="destinationunknown">destinationunknown</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jez" title="jez">jez</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/differentdistances" title="differentdistances">differentdistances</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cardmagic" title="cardmagic">cardmagic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cleaningpipes" title="cleaningpipes">cleaningpipes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ispmerger" title="ispmerger">ispmerger</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dicegame" title="dicegame">dicegame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/calculator" title="calculator">calculator</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chineseremainder" title="chineseremainder">chineseremainder</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/inquiryii" title="inquiryii">inquiryii</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/countingclauses" title="countingclauses">countingclauses</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cakeymccakeface" title="cakeymccakeface">cakeymccakeface</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chesscompetition" title="chesscompetition">chesscompetition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/icons" title="icons">icons</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/coconut" title="coconut">coconut</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vegetables" title="vegetables">vegetables</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cardhands" title="cardhands">cardhands</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hamster" title="hamster">hamster</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/closingtheloop" title="closingtheloop">closingtheloop</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arithmetic" title="arithmetic">arithmetic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/candydistribution" title="candydistribution">candydistribution</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gridspeed" title="gridspeed">gridspeed</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bus" title="bus">bus</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/appealtotheaudience" title="appealtotheaudience">appealtotheaudience</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bracketmatrix" title="bracketmatrix">bracketmatrix</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greatgdp" title="greatgdp">greatgdp</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/boundingrobots" title="boundingrobots">boundingrobots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/addingwords" title="addingwords">addingwords</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/blackvienna" title="blackvienna">blackvienna</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greatfireball" title="greatfireball">greatfireball</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fodelsedagsmemorisering" title="fodelsedagsmemorisering">fodelsedagsmemorisering</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/a1paper" title="a1paper">a1paper</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/birdrescue" title="birdrescue">birdrescue</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/genetics" title="genetics">genetics</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/yinyangstones" title="yinyangstones">yinyangstones</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/teque" title="teque">teque</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/baggage" title="baggage">baggage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fruitslicer" title="fruitslicer">fruitslicer</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/volim" title="volim">volim</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sim" title="sim">sim</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/avogadro" title="avogadro">avogadro</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fastestspeedrun" title="fastestspeedrun">fastestspeedrun</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/unlockpattern" title="unlockpattern">unlockpattern</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zigzag" title="zigzag">zigzag</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/altosinging" title="altosinging">altosinging</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fancyeasy" title="fancyeasy">fancyeasy</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tornbygge" title="tornbygge">tornbygge</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/undetected" title="undetected">undetected</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dream" title="dream">dream</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/enjoyingelderberries" title="enjoyingelderberries">enjoyingelderberries</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/timebomb" title="timebomb">timebomb</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tricktreat" title="tricktreat">tricktreat</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/adventurebegins" title="adventurebegins">adventurebegins</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/endlessturning" title="endlessturning">endlessturning</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/thisaintyourgrandpascheckerboard" title="thisaintyourgrandpascheckerboard">thisaintyourgrandpascheckerboard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/texassummers" title="texassummers">texassummers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zadaca" title="zadaca">zadaca</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/doubleclique" title="doubleclique">doubleclique</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/thelastproblem" title="thelastproblem">thelastproblem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/terraces" title="terraces">terraces</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/workout" title="workout">workout</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dimsum" title="dimsum">dimsum</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/keytocrypto" title="keytocrypto">keytocrypto</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ternarianweights" title="ternarianweights">ternarianweights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trash" title="trash">trash</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vonwalken" title="vonwalken">vonwalken</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/spavanac" title="spavanac">spavanac</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/svada" title="svada">svada</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/translatorsdinner" title="translatorsdinner">translatorsdinner</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/councilling" title="councilling">councilling</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sok" title="sok">sok</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/selectgroup" title="selectgroup">selectgroup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/transitcard" title="transitcard">transitcard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/conveyorbelts2" title="conveyorbelts2">conveyorbelts2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sjecista" title="sjecista">sjecista</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rings2" title="rings2">rings2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/traindelays" title="traindelays">traindelays</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/compiler" title="compiler">compiler</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/savingforretirement" title="savingforretirement">savingforretirement</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ricochetrobots" title="ricochetrobots">ricochetrobots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thebeginningoftheendpart2" title="thebeginningoftheendpart2">thebeginningoftheendpart2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/circuitdesign" title="circuitdesign">circuitdesign</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/reverserot" title="reverserot">reverserot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/remorse" title="remorse">remorse</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/surveillance" title="surveillance">surveillance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cheerreaders" title="cheerreaders">cheerreaders</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/prva" title="prva">prva</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/relatives" title="relatives">relatives</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/suffixsorting" title="suffixsorting">suffixsorting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chainco" title="chainco">chainco</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pauleigon" title="pauleigon">pauleigon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/reactivity" title="reactivity">reactivity</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stringfactoring" title="stringfactoring">stringfactoring</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/blocks" title="blocks">blocks</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ostgotska" title="ostgotska">ostgotska</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/primereduction" title="primereduction">primereduction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slowleak" title="slowleak">slowleak</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bst" title="bst">bst</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/missingnumbers" title="missingnumbers">missingnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/poplava" title="poplava">poplava</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/reconstructingtapeart" title="reconstructingtapeart">reconstructingtapeart</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/backpackbuddies" title="backpackbuddies">backpackbuddies</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/loorolls" title="loorolls">loorolls</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pascal" title="pascal">pascal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/equivalences" title="equivalences">equivalences</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rangers" title="rangers">rangers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/kitten" title="kitten">kitten</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ceremony" title="ceremony">ceremony</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/plusminus" title="plusminus">plusminus</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/associationofmyths" title="associationofmyths">associationofmyths</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/justaminute" title="justaminute">justaminute</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mafija" title="mafija">mafija</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pianino" title="pianino">pianino</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mububa" title="mububa">mububa</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jewelrybox" title="jewelrybox">jewelrybox</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/luckydraw" title="luckydraw">luckydraw</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/oil2" title="oil2">oil2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/result" title="result">result</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/inflation" title="inflation">inflation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/justforsidekicks" title="justforsidekicks">justforsidekicks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lemonade" title="lemonade">lemonade</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/annorlundaanagram" title="annorlundaanagram">annorlundaanagram</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hydrasheads" title="hydrasheads">hydrasheads</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hexagonalrooks" title="hexagonalrooks">hexagonalrooks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/karel" title="karel">karel</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mysterious" title="mysterious">mysterious</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hittingtargets" title="hittingtargets">hittingtargets</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/goodcoalition" title="goodcoalition">goodcoalition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kamioni" title="kamioni">kamioni</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fence" title="fence">fence</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/herman" title="herman">herman</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gameofcards" title="gameofcards">gameofcards</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jumpingchoreography" title="jumpingchoreography">jumpingchoreography</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/windypath" title="windypath">windypath</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hangingout" title="hangingout">hangingout</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/foosball" title="foosball">foosball</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/isomorphicinversion" title="isomorphicinversion">isomorphicinversion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/volumeamplification" title="volumeamplification">volumeamplification</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/halfacookie" title="halfacookie">halfacookie</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fishmongers" title="fishmongers">fishmongers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/caching" title="caching">caching</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/triforce" title="triforce">triforce</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/flyingsafely" title="flyingsafely">flyingsafely</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shortcut" title="shortcut">shortcut</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/illumination" title="illumination">illumination</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tomjerry" title="tomjerry">tomjerry</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/flexible" title="flexible">flexible</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/digits" title="digits">digits</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hearthbreakers" title="hearthbreakers">hearthbreakers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/memory" title="memory">memory</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/falsesecurity" title="falsesecurity">falsesecurity</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cuboidslicinggame" title="cuboidslicinggame">cuboidslicinggame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gondolas" title="gondolas">gondolas</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stringmultimatching" title="stringmultimatching">stringmultimatching</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/empleh" title="empleh">empleh</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cranes" title="cranes">cranes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gladiators" title="gladiators">gladiators</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/squarefieldshard" title="squarefieldshard">squarefieldshard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/deathknight" title="deathknight">deathknight</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cowboycheckers" title="cowboycheckers">cowboycheckers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gingercandy" title="gingercandy">gingercandy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spinningup" title="spinningup">spinningup</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dasblinkenlights" title="dasblinkenlights">dasblinkenlights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/subseqhard" title="subseqhard">subseqhard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/geezerscripts" title="geezerscripts">geezerscripts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spam" title="spam">spam</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cardtrick2" title="cardtrick2">cardtrick2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/conquest" title="conquest">conquest</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/floatingformation" title="floatingformation">floatingformation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slidingblocks" title="slidingblocks">slidingblocks</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/brokenswords" title="brokenswords">brokenswords</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/connectthedots" title="connectthedots">connectthedots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/faultysprinklers" title="faultysprinklers">faultysprinklers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/san" title="san">san</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/breakingbranches" title="breakingbranches">breakingbranches</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/collatz" title="collatz">collatz</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/factors" title="factors">factors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rnasecondarystructure" title="rnasecondarystructure">rnasecondarystructure</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/basketballoneonone" title="basketballoneonone">basketballoneonone</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coast" title="coast">coast</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/factorfree" title="factorfree">factorfree</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pipe" title="pipe">pipe</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/babybites" title="babybites">babybites</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/breakingbad" title="breakingbad">breakingbad</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/easyarithmetic" title="easyarithmetic">easyarithmetic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/physiognomy" title="physiognomy">physiognomy</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/rationalsequence3" title="rationalsequence3">rationalsequence3</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/birthday" title="birthday">birthday</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/doors" title="doors">doors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/peggame" title="peggame">peggame</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/anewalphabet" title="anewalphabet">anewalphabet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bing" title="bing">bing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/domine" title="domine">domine</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/parovi" title="parovi">parovi</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/aaah" title="aaah">aaah</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alloys" title="alloys">alloys</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/distance" title="distance">distance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/numbers2" title="numbers2">numbers2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/upprodun" title="upprodun">upprodun</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alchemy101" title="alchemy101">alchemy101</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/creditcard" title="creditcard">creditcard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nekameleoni" title="nekameleoni">nekameleoni</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/veci" title="veci">veci</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/znanstvenik" title="znanstvenik">znanstvenik</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/countcircuits" title="countcircuits">countcircuits</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/multiplyingdigits" title="multiplyingdigits">multiplyingdigits</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/vauvau" title="vauvau">vauvau</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/satisfiability" title="satisfiability">satisfiability</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chairhopping" title="chairhopping">chairhopping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/marshlandrescues" title="marshlandrescues">marshlandrescues</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/vacuumba" title="vacuumba">vacuumba</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wheels" title="wheels">wheels</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/baas" title="baas">baas</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/checkerboard" title="checkerboard">checkerboard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tracksmoothing" title="tracksmoothing">tracksmoothing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wettiles" title="wettiles">wettiles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/starnotatree" title="starnotatree">starnotatree</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/luggage" title="luggage">luggage</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/owlandfox" title="owlandfox">owlandfox</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thanosthehero" title="thanosthehero">thanosthehero</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/magicallights" title="magicallights">magicallights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/correspondence" title="correspondence">correspondence</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/statistics" title="statistics">statistics</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tenis" title="tenis">tenis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ingestion" title="ingestion">ingestion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/laneswitching" title="laneswitching">laneswitching</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/somesum" title="somesum">somesum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/swaptosort" title="swaptosort">swaptosort</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/antimatterrain" title="antimatterrain">antimatterrain</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jezzball" title="jezzball">jezzball</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/shoppinglisteasy" title="shoppinglisteasy">shoppinglisteasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/congest" title="congest">congest</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/amazing" title="amazing">amazing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jewelheist" title="jewelheist">jewelheist</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/amoebas" title="amoebas">amoebas</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slidingtiles" title="slidingtiles">slidingtiles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/adjoin" title="adjoin">adjoin</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/island" title="island">island</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/server" title="server">server</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rockpaperscissors" title="rockpaperscissors">rockpaperscissors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/babynames" title="babynames">babynames</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/heightprofile" title="heightprofile">heightprofile</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/securedoors" title="securedoors">securedoors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/quantum" title="quantum">quantum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vindiagrams" title="vindiagrams">vindiagrams</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/grabagraph" title="grabagraph">grabagraph</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/secretmessage" title="secretmessage">secretmessage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pickupsticks" title="pickupsticks">pickupsticks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/treeshopping" title="treeshopping">treeshopping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gokigen" title="gokigen">gokigen</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/recipes" title="recipes">recipes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/persistent" title="persistent">persistent</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/toast" title="toast">toast</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gauntletoffire" title="gauntletoffire">gauntletoffire</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/runlengthencodingrun" title="runlengthencodingrun">runlengthencodingrun</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mobilization" title="mobilization">mobilization</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/safesecret" title="safesecret">safesecret</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gaggle" title="gaggle">gaggle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/r2" title="r2">r2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/memorymatch" title="memorymatch">memorymatch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/terracedfields" title="terracedfields">terracedfields</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fish" title="fish">fish</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/chopin" title="chopin">chopin</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knigsoftheforest" title="knigsoftheforest">knigsoftheforest</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/svemir" title="svemir">svemir</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/endlessknight" title="endlessknight">endlessknight</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pervasiveheartmonitor" title="pervasiveheartmonitor">pervasiveheartmonitor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/borg" title="borg">borg</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/structuralequivalence" title="structuralequivalence">structuralequivalence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/edgeremoval" title="edgeremoval">edgeremoval</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/parking" title="parking">parking</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/joylessgame" title="joylessgame">joylessgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/routing" title="routing">routing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sightseeing" title="sightseeing">sightseeing</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mosquito" title="mosquito">mosquito</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/interpreter" title="interpreter">interpreter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/randommanhattan" title="randommanhattan">randommanhattan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cryptotrouble" title="cryptotrouble">cryptotrouble</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/moscowdream" title="moscowdream">moscowdream</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/includescoring" title="includescoring">includescoring</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prettygoodcuberoot" title="prettygoodcuberoot">prettygoodcuberoot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/copyingdna" title="copyingdna">copyingdna</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/marko" title="marko">marko</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thinkingofanumber" title="thinkingofanumber">thinkingofanumber</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/perfectskyline" title="perfectskyline">perfectskyline</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/colorcodes" title="colorcodes">colorcodes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mancala" title="mancala">mancala</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hotspot" title="hotspot">hotspot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/perfectpathpatrol" title="perfectpathpatrol">perfectpathpatrol</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/circleoffriends" title="circleoffriends">circleoffriends</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/krizaljka" title="krizaljka">krizaljka</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hobsonstrains" title="hobsonstrains">hobsonstrains</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/palindromic" title="palindromic">palindromic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cestarine" title="cestarine">cestarine</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/islands3" title="islands3">islands3</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ferryloading3" title="ferryloading3">ferryloading3</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paintbuckets" title="paintbuckets">paintbuckets</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cavli" title="cavli">cavli</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/howl" title="howl">howl</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dungeon" title="dungeon">dungeon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/packingpests" title="packingpests">packingpests</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/capturedbyaliens" title="capturedbyaliens">capturedbyaliens</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hidingplaces" title="hidingplaces">hidingplaces</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sequence" title="sequence">sequence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ministryofmagic" title="ministryofmagic">ministryofmagic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/britishmenu" title="britishmenu">britishmenu</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/heliocentric" title="heliocentric">heliocentric</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/datingtime" title="datingtime">datingtime</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lemonadetrade" title="lemonadetrade">lemonadetrade</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bob" title="bob">bob</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/friday" title="friday">friday</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cowcrane" title="cowcrane">cowcrane</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/landlocked" title="landlocked">landlocked</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/autocompletion" title="autocompletion">autocompletion</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/exam" title="exam">exam</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/generalchineseremainder" title="generalchineseremainder">generalchineseremainder</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knights" title="knights">knights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/asteroids" title="asteroids">asteroids</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/erase" title="erase">erase</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/catering" title="catering">catering</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/intelligenceinfection" title="intelligenceinfection">intelligenceinfection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/around" title="around">around</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/eenymeeny" title="eenymeeny">eenymeeny</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/catch" title="catch">catch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/herkabe" title="herkabe">herkabe</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/contacttracing" title="contacttracing">contacttracing</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/earlywinter" title="earlywinter">earlywinter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cardtrading" title="cardtrading">cardtrading</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gwensgift" title="gwensgift">gwensgift</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unicycles" title="unicycles">unicycles</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/damagedequation" title="damagedequation">damagedequation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/traffic" title="traffic">traffic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/guardianofdecency" title="guardianofdecency">guardianofdecency</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/additiongame" title="additiongame">additiongame</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/convexpolygonarea" title="convexpolygonarea">convexpolygonarea</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bitsequalizer" title="bitsequalizer">bitsequalizer</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gatheringinyorknew" title="gatheringinyorknew">gatheringinyorknew</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spock" title="spock">spock</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/conformity" title="conformity">conformity</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/standings" title="standings">standings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/foolingaround" title="foolingaround">foolingaround</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slon" title="slon">slon</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/completingthesquare" title="completingthesquare">completingthesquare</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beehouseperimeter" title="beehouseperimeter">beehouseperimeter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fiat" title="fiat">fiat</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rectangleland" title="rectangleland">rectangleland</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cetiri" title="cetiri">cetiri</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ballbearings" title="ballbearings">ballbearings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/exofficio" title="exofficio">exofficio</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/randomdigitalexponentiation" title="randomdigitalexponentiation">randomdigitalexponentiation</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/billiard" title="billiard">billiard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/abstractpainting" title="abstractpainting">abstractpainting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/escapeplan" title="escapeplan">escapeplan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pipes3" title="pipes3">pipes3</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/baconeggsandspam" title="baconeggsandspam">baconeggsandspam</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/basicprogramming1" title="basicprogramming1">basicprogramming1</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/enemydivision" title="enemydivision">enemydivision</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/minigolf" title="minigolf">minigolf</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/autori" title="autori">autori</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vuk" title="vuk">vuk</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/encodedcoordinates" title="encodedcoordinates">encodedcoordinates</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/minrojikvadrat" title="minrojikvadrat">minrojikvadrat</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/astrologicalsign" title="astrologicalsign">astrologicalsign</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/treehouses" title="treehouses">treehouses</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/digitsum" title="digitsum">digitsum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mag" title="mag">mag</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/skolavslutningen" title="skolavslutningen">skolavslutningen</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tourists" title="tourists">tourists</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/digicomp2" title="digicomp2">digicomp2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ladybug" title="ladybug">ladybug</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/zoo" title="zoo">zoo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tomography" title="tomography">tomography</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crisscrosscables" title="crisscrosscables">crisscrosscables</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/largesttriangle" title="largesttriangle">largesttriangle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tolower" title="tolower">tolower</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thermostat" title="thermostat">thermostat</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/convoy" title="convoy">convoy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/krumpirko" title="krumpirko">krumpirko</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tetris" title="tetris">tetris</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stockprices" title="stockprices">stockprices</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/colourful" title="colourful">colourful</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/isahasa" title="isahasa">isahasa</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/simplecronspec" title="simplecronspec">simplecronspec</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/signprofile" title="signprofile">signprofile</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/checkingbreak" title="checkingbreak">checkingbreak</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/categorymanipulation" title="categorymanipulation">categorymanipulation</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/set" title="set">set</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shoppinglist" title="shoppinglist">shoppinglist</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/catvsdog" title="catvsdog">catvsdog</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hunterxcommunication" title="hunterxcommunication">hunterxcommunication</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/semafori" title="semafori">semafori</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/assembly" title="assembly">assembly</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coke" title="coke">coke</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/haikuformatting" title="haikuformatting">haikuformatting</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/redrover" title="redrover">redrover</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rockband" title="rockband">rockband</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bridgeautomation" title="bridgeautomation">bridgeautomation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gameworld" title="gameworld">gameworld</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/raggedright" title="raggedright">raggedright</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pumpkinpatch" title="pumpkinpatch">pumpkinpatch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bowlstack" title="bowlstack">bowlstack</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/furrynuisance" title="furrynuisance">furrynuisance</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/prerequisites" title="prerequisites">prerequisites</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pxs" title="pxs">pxs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/booking" title="booking">booking</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flightplans" title="flightplans">flightplans</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/plantingtrees" title="plantingtrees">plantingtrees</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pearwise" title="pearwise">pearwise</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bitwise" title="bitwise">bitwise</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/faucetflow" title="faucetflow">faucetflow</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/permutationdescent" title="permutationdescent">permutationdescent</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/orderlyclass" title="orderlyclass">orderlyclass</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beautifulbridges" title="beautifulbridges">beautifulbridges</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/datepickup" title="datepickup">datepickup</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/peg" title="peg">peg</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/openpitmining" title="openpitmining">openpitmining</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bananaproblem" title="bananaproblem">bananaproblem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/criticalelements" title="criticalelements">criticalelements</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pachydermpeanutpacking" title="pachydermpeanutpacking">pachydermpeanutpacking</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/onaveragetheyrepurple" title="onaveragetheyrepurple">onaveragetheyrepurple</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cool2" title="cool2">cool2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chromiumshipping" title="chromiumshipping">chromiumshipping</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/okviri" title="okviri">okviri</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/molecules" title="molecules">molecules</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arrivingontime" title="arrivingontime">arrivingontime</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chasingsubs" title="chasingsubs">chasingsubs</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/oktalni" title="oktalni">oktalni</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mincut" title="mincut">mincut</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/absurdistan3" title="absurdistan3">absurdistan3</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/browniepoints2" title="browniepoints2">browniepoints2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/oddities" title="oddities">oddities</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/loworderzeros" title="loworderzeros">loworderzeros</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zipfslaw" title="zipfslaw">zipfslaw</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bonbons" title="bonbons">bonbons</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/nineknights" title="nineknights">nineknights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/imperfectgps" title="imperfectgps">imperfectgps</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spectrum" title="spectrum">spectrum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bikingduck" title="bikingduck">bikingduck</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/marswindow" title="marswindow">marswindow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hotdogs" title="hotdogs">hotdogs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/treasurespotting" title="treasurespotting">treasurespotting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aroyalproblem" title="aroyalproblem">aroyalproblem</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/kafkaesque" title="kafkaesque">kafkaesque</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flagquiz" title="flagquiz">flagquiz</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trainaddiction" title="trainaddiction">trainaddiction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/airrally" title="airrally">airrally</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/compass" title="compass">compass</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fire2" title="fire2">fire2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tours" title="tours">tours</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wormholes2" title="wormholes2">wormholes2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jabuke" title="jabuke">jabuke</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fantasydraft" title="fantasydraft">fantasydraft</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thesummersunsetback" title="thesummersunsetback">thesummersunsetback</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/windows" title="windows">windows</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hothike" title="hothike">hothike</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/droppingdirections" title="droppingdirections">droppingdirections</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/setstack" title="setstack">setstack</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/whiteboard" title="whiteboard">whiteboard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/glitchbot" title="glitchbot">glitchbot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/divisible" title="divisible">divisible</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thelastcrusade" title="thelastcrusade">thelastcrusade</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/watchyourstep" title="watchyourstep">watchyourstep</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/funhouse" title="funhouse">funhouse</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dejavu" title="dejavu">dejavu</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/darkness" title="darkness">darkness</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vocabulary" title="vocabulary">vocabulary</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/functionalfun" title="functionalfun">functionalfun</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cycleseasy" title="cycleseasy">cycleseasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/testscheduling" title="testscheduling">testscheduling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/traintickets" title="traintickets">traintickets</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/flowlayout" title="flowlayout">flowlayout</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cuttingbrownies" title="cuttingbrownies">cuttingbrownies</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sprocketscience" title="sprocketscience">sprocketscience</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thelastlaugh" title="thelastlaugh">thelastlaugh</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/eventplanning" title="eventplanning">eventplanning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/driver" title="driver">driver</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shibuyacrossing" title="shibuyacrossing">shibuyacrossing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/componentsgame" title="componentsgame">componentsgame</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/epigdanceoff" title="epigdanceoff">epigdanceoff</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fraction" title="fraction">fraction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/relativnost" title="relativnost">relativnost</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thebeginningoftheendpart1" title="thebeginningoftheendpart1">thebeginningoftheendpart1</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/egypt" title="egypt">egypt</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/circularlock" title="circularlock">circularlock</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/promotions" title="promotions">promotions</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hashing" title="hashing">hashing</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/echoechoecho" title="echoechoecho">echoechoecho</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cheatingatwar" title="cheatingatwar">cheatingatwar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pictureday" title="pictureday">pictureday</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spin" title="spin">spin</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/costumecontest" title="costumecontest">costumecontest</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/carvet" title="carvet">carvet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pagelayout" title="pagelayout">pagelayout</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slalom" title="slalom">slalom</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cookingwater" title="cookingwater">cookingwater</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/brocard" title="brocard">brocard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ozljeda" title="ozljeda">ozljeda</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shoppingplan" title="shoppingplan">shoppingplan</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/conteststruggles" title="conteststruggles">conteststruggles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/signals" title="signals">signals</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/newmaths" title="newmaths">newmaths</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sevenkingdoms" title="sevenkingdoms">sevenkingdoms</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/compoundwords" title="compoundwords">compoundwords</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/boxes" title="boxes">boxes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/minflow" title="minflow">minflow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sculpture" title="sculpture">sculpture</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/carefulascent" title="carefulascent">carefulascent</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bestbefore" title="bestbefore">bestbefore</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/liga" title="liga">liga</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rainfall" title="rainfall">rainfall</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/buka" title="buka">buka</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/balanceddiet" title="balanceddiet">balanceddiet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/leapfrog" title="leapfrog">leapfrog</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/polygraph" title="polygraph">polygraph</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bossbattle" title="bossbattle">bossbattle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/astro" title="astro">astro</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jumbledstring" title="jumbledstring">jumbledstring</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/palacinke" title="palacinke">palacinke</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bookingaroom" title="bookingaroom">bookingaroom</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alicedigital" title="alicedigital">alicedigital</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/johnsstack" title="johnsstack">johnsstack</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mountainouslandscape" title="mountainouslandscape">mountainouslandscape</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/asciiaddition" title="asciiaddition">asciiaddition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/doctorkattis" title="doctorkattis">doctorkattis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/inversefactorial" title="inversefactorial">inversefactorial</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/matchings" title="matchings">matchings</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/aliennumbers" title="aliennumbers">aliennumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/continuousmedian" title="continuousmedian">continuousmedian</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/invasion" title="invasion">invasion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lifeforms" title="lifeforms">lifeforms</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/aboveaverage" title="aboveaverage">aboveaverage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/witchwood" title="witchwood">witchwood</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/estate" title="estate">estate</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingpinescape" title="kingpinescape">kingpinescape</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/yoda" title="yoda">yoda</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/urbandesign" title="urbandesign">urbandesign</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hopscotch" title="hopscotch">hopscotch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jinxedbetting" title="jinxedbetting">jinxedbetting</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/warehouse" title="warehouse">warehouse</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tray" title="tray">tray</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/highscore" title="highscore">highscore</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jealousyoungsters" title="jealousyoungsters">jealousyoungsters</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/videospeedup" title="videospeedup">videospeedup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/timing" title="timing">timing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/helpfulrotations" title="helpfulrotations">helpfulrotations</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jazzjourney" title="jazzjourney">jazzjourney</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/touchscreenkeyboard" title="touchscreenkeyboard">touchscreenkeyboard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/grapevine" title="grapevine">grapevine</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/heapsoffun" title="heapsoffun">heapsoffun</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/interviewqueue" title="interviewqueue">interviewqueue</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/spellingbee" title="spellingbee">spellingbee</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ship" title="ship">ship</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/halloweenloot" title="halloweenloot">halloweenloot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/intelligenceexchange" title="intelligenceexchange">intelligenceexchange</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/simpleaddition" title="simpleaddition">simpleaddition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/saintjohn" title="saintjohn">saintjohn</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/grandopening" title="grandopening">grandopening</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/infiltration2" title="infiltration2">infiltration2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/vajningsplikt" title="vajningsplikt">vajningsplikt</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/robotturtles" title="robotturtles">robotturtles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/froggie" title="froggie">froggie</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/indoorienteering" title="indoorienteering">indoorienteering</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/commercials" title="commercials">commercials</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/robotsonagrid" title="robotsonagrid">robotsonagrid</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/foreveryoung" title="foreveryoung">foreveryoung</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ideas" title="ideas">ideas</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/progressivescramble" title="progressivescramble">progressivescramble</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/reconnaissance" title="reconnaissance">reconnaissance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fogcatchers" title="fogcatchers">fogcatchers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/howtopaint" title="howtopaint">howtopaint</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/printingcosts" title="printingcosts">printingcosts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/raceday" title="raceday">raceday</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flashingfluorescents" title="flashingfluorescents">flashingfluorescents</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gridmst" title="gridmst">gridmst</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/polymul1" title="polymul1">polymul1</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paintball" title="paintball">paintball</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/firestation" title="firestation">firestation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greenlight" title="greenlight">greenlight</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/okvir" title="okvir">okvir</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/necklacedecomposition" title="necklacedecomposition">necklacedecomposition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/herrings" title="herrings">herrings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flight" title="flight">flight</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/numbertree" title="numbertree">numbertree</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/muddyhike" title="muddyhike">muddyhike</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ecodriving" title="ecodriving">ecodriving</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/familydag" title="familydag">familydag</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/nop" title="nop">nop</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mazemovement" title="mazemovement">mazemovement</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dragondropped" title="dragondropped">dragondropped</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/disposableswitches" title="disposableswitches">disposableswitches</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/musicalnotation" title="musicalnotation">musicalnotation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/matchsticks" title="matchsticks">matchsticks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cvjetici" title="cvjetici">cvjetici</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dancecircle" title="dancecircle">dancecircle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mathhomework" title="mathhomework">mathhomework</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knockout" title="knockout">knockout</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cuttingthenecklace" title="cuttingthenecklace">cuttingthenecklace</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/compasscard" title="compasscard">compasscard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/measurement" title="measurement">measurement</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kastenlauf" title="kastenlauf">kastenlauf</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cucumberconundrum" title="cucumberconundrum">cucumberconundrum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/collidingtraffic" title="collidingtraffic">collidingtraffic</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/humancannonball" title="humancannonball">humancannonball</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hrpa" title="hrpa">hrpa</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coverage" title="coverage">coverage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chemicalsmonitoring" title="chemicalsmonitoring">chemicalsmonitoring</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/haypoints" title="haypoints">haypoints</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/howmanyzeros" title="howmanyzeros">howmanyzeros</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/konsultarbeten" title="konsultarbeten">konsultarbeten</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/canyon" title="canyon">canyon</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hardware" title="hardware">hardware</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hanjie" title="hanjie">hanjie</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/citadelconstruction" title="citadelconstruction">citadelconstruction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cablecar" title="cablecar">cablecar</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/redistribution" title="redistribution">redistribution</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/frustratedqueue" title="frustratedqueue">frustratedqueue</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cheaperdrink" title="cheaperdrink">cheaperdrink</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/binarytree" title="binarytree">binarytree</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/engineeringenglish" title="engineeringenglish">engineeringenglish</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/font" title="font">font</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/buffet" title="buffet">buffet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beacons" title="beacons">beacons</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/deathstar" title="deathstar">deathstar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/firetrucksarered" title="firetrucksarered">firetrucksarered</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bubblytroubly" title="bubblytroubly">bubblytroubly</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arcaeapartners" title="arcaeapartners">arcaeapartners</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/coursescheduling" title="coursescheduling">coursescheduling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/findthegraph" title="findthegraph">findthegraph</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bridgesandtunnels2" title="bridgesandtunnels2">bridgesandtunnels2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/walk" title="walk">walk</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bestrelayteam" title="bestrelayteam">bestrelayteam</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/showroom" title="showroom">showroom</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bigbrother" title="bigbrother">bigbrother</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unterwavedistance" title="unterwavedistance">unterwavedistance</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/compromise" title="compromise">compromise</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/drinkresponsibly" title="drinkresponsibly">drinkresponsibly</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/balanceddiet2" title="balanceddiet2">balanceddiet2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/truefalseworksheet" title="truefalseworksheet">truefalseworksheet</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/anotherbrick" title="anotherbrick">anotherbrick</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/convexhull" title="convexhull">convexhull</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/averagerank" title="averagerank">averagerank</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trainline" title="trainline">trainline</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/akcija" title="akcija">akcija</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/climbingstairs" title="climbingstairs">climbingstairs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/anthony" title="anthony">anthony</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tournament" title="tournament">tournament</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/abc" title="abc">abc</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chemistsvows" title="chemistsvows">chemistsvows</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/allpairspath" title="allpairspath">allpairspath</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/structuraldifferences" title="structuraldifferences">structuraldifferences</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/watchdog" title="watchdog">watchdog</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cardhand" title="cardhand">cardhand</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alliswell" title="alliswell">alliswell</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/strikercount" title="strikercount">strikercount</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/triangleornaments" title="triangleornaments">triangleornaments</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bucketbrigade" title="bucketbrigade">bucketbrigade</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/accesspoints" title="accesspoints">accesspoints</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sheep" title="sheep">sheep</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/trainpassengers" title="trainpassengers">trainpassengers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/amultiplicationgame" title="amultiplicationgame">amultiplicationgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/xortris" title="xortris">xortris</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shares" title="shares">shares</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/temperature" title="temperature">temperature</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/yatp" title="yatp">yatp</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/whacamole" title="whacamole">whacamole</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sequentialyahtzee" title="sequentialyahtzee">sequentialyahtzee</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/thegrandadventure" title="thegrandadventure">thegrandadventure</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/victorythroughsynergy" title="victorythroughsynergy">victorythroughsynergy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/consumption" title="consumption">consumption</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sendmoremoney" title="sendmoremoney">sendmoremoney</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/temperatureconfusion" title="temperatureconfusion">temperatureconfusion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/snowflakes" title="snowflakes">snowflakes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/deliveryperson" title="deliveryperson">deliveryperson</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rubikrectangle" title="rubikrectangle">rubikrectangle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sorttwonumbers" title="sorttwonumbers">sorttwonumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/xentopia" title="xentopia">xentopia</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trafficblights" title="trafficblights">trafficblights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pizzaproblems" title="pizzaproblems">pizzaproblems</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sortofsorting" title="sortofsorting">sortofsorting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tictactoe2" title="tictactoe2">tictactoe2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tractor" title="tractor">tractor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/equationsolverplus" title="equationsolverplus">equationsolverplus</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/socialrunning" title="socialrunning">socialrunning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stringmatching" title="stringmatching">stringmatching</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/substitution" title="substitution">substitution</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mountainroad" title="mountainroad">mountainroad</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/princesspeach" title="princesspeach">princesspeach</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stopcard" title="stopcard">stopcard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/magical3" title="magical3">magical3</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lightsout" title="lightsout">lightsout</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/savingdaylight" title="savingdaylight">savingdaylight</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/curvyblocks" title="curvyblocks">curvyblocks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/embarrassedcryptographer" title="embarrassedcryptographer">embarrassedcryptographer</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingofspades" title="kingofspades">kingofspades</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/quiteaproblem" title="quiteaproblem">quiteaproblem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/squaredeal" title="squaredeal">squaredeal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/teamup" title="teamup">teamup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kindergarten" title="kindergarten">kindergarten</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/register" title="register">register</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shortsell" title="shortsell">shortsell</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slalom2" title="slalom2">slalom2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/islands2" title="islands2">islands2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/piglatin" title="piglatin">piglatin</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/settlers2" title="settlers2">settlers2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/skiresort" title="skiresort">skiresort</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/iqtest" title="iqtest">iqtest</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/permutedarithmeticsequence" title="permutedarithmeticsequence">permutedarithmeticsequence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dutyscheduler" title="dutyscheduler">dutyscheduler</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shopping" title="shopping">shopping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/squares" title="squares">squares</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/password" title="password">password</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/primematrix" title="primematrix">primematrix</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rebelportals" title="rebelportals">rebelportals</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hash" title="hash">hash</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/npuzzle" title="npuzzle">npuzzle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/phonelist" title="phonelist">phonelist</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/razgovori" title="razgovori">razgovori</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greatestpermutation" title="greatestpermutation">greatestpermutation</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/nimionese" title="nimionese">nimionese</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/partygame" title="partygame">partygame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pubnite" title="pubnite">pubnite</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fidgetspinner" title="fidgetspinner">fidgetspinner</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/multiplication" title="multiplication">multiplication</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/musiccollection" title="musiccollection">musiccollection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prosjek2" title="prosjek2">prosjek2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fantasticproblem" title="fantasticproblem">fantasticproblem</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/misa" title="misa">misa</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/improbable" title="improbable">improbable</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/powerstrings" title="powerstrings">powerstrings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/enclosure" title="enclosure">enclosure</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/minimumscalar" title="minimumscalar">minimumscalar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maximizingwinnings" title="maximizingwinnings">maximizingwinnings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pointinpolygon" title="pointinpolygon">pointinpolygon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/directorymanagement" title="directorymanagement">directorymanagement</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mia" title="mia">mia</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knapsackpacking" title="knapsackpacking">knapsackpacking</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pitchperformance" title="pitchperformance">pitchperformance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/demeritpoints" title="demeritpoints">demeritpoints</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/metaprogramming" title="metaprogramming">metaprogramming</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kamp" title="kamp">kamp</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/perica" title="perica">perica</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/deliverydelays" title="deliverydelays">deliverydelays</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/majstor" title="majstor">majstor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/increasingsubsequence" title="increasingsubsequence">increasingsubsequence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pavers" title="pavers">pavers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/climbing" title="climbing">climbing</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/lawnmower" title="lawnmower">lawnmower</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hogwarts2" title="hogwarts2">hogwarts2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pachinkoprobability" title="pachinkoprobability">pachinkoprobability</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/blokovi" title="blokovi">blokovi</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/keyboardd" title="keyboardd">keyboardd</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/grasshopper" title="grasshopper">grasshopper</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/outing" title="outing">outing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/biotrip" title="biotrip">biotrip</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/communication" title="communication">communication</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greatswercporto" title="greatswercporto">greatswercporto</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maze" title="maze">maze</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bingoties" title="bingoties">bingoties</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hidden" title="hidden">hidden</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/generalizedrecursivefunctions" title="generalizedrecursivefunctions">generalizedrecursivefunctions</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/managingpackaging" title="managingpackaging">managingpackaging</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/binaryvoting" title="binaryvoting">binaryvoting</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/growlinggears" title="growlinggears">growlinggears</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/foodcarts" title="foodcarts">foodcarts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hotels" title="hotels">hotels</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/causal" title="causal">causal</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/greedilyincreasing" title="greedilyincreasing">greedilyincreasing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flowergarden" title="flowergarden">flowergarden</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hogwarts" title="hogwarts">hogwarts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knightfly" title="knightfly">knightfly</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/gold" title="gold">gold</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fenwick" title="fenwick">fenwick</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hiddenwords" title="hiddenwords">hiddenwords</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zergrush" title="zergrush">zergrush</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/george" title="george">george</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dancerecital" title="dancerecital">dancerecital</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roomba" title="roomba">roomba</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/windowshopping" title="windowshopping">windowshopping</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fbiuniversal" title="fbiuniversal">fbiuniversal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cross" title="cross">cross</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/habeascorpus" title="habeascorpus">habeascorpus</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/triptik" title="triptik">triptik</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/exactlyelectrical" title="exactlyelectrical">exactlyelectrical</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coveredwalkway" title="coveredwalkway">coveredwalkway</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/goblingardenguards" title="goblingardenguards">goblingardenguards</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/suma" title="suma">suma</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/driversdilemma" title="driversdilemma">driversdilemma</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/copsandrobbers" title="copsandrobbers">copsandrobbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gettingthrough" title="gettingthrough">gettingthrough</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stack" title="stack">stack</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dreamer" title="dreamer">dreamer</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/boundingbox" title="boundingbox">boundingbox</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fulldepthmorningshow" title="fulldepthmorningshow">fulldepthmorningshow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rhino" title="rhino">rhino</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/delimitersoup" title="delimitersoup">delimitersoup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/primes2" title="primes2">primes2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fractal2" title="fractal2">fractal2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/recursionrandfun" title="recursionrandfun">recursionrandfun</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dst" title="dst">dst</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beautifulprimes" title="beautifulprimes">beautifulprimes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/folding" title="folding">folding</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/radar" title="radar">radar</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/conquestcampaign" title="conquestcampaign">conquestcampaign</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arcticnetwork" title="arcticnetwork">arcticnetwork</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/filmcritics" title="filmcritics">filmcritics</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prolongedpassword" title="prolongedpassword">prolongedpassword</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/color" title="color">color</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/appallingarchitecture" title="appallingarchitecture">appallingarchitecture</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fairbandwidthsharing" title="fairbandwidthsharing">fairbandwidthsharing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/programmingteamselection" title="programmingteamselection">programmingteamselection</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/calories" title="calories">calories</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/anotherdice" title="anotherdice">anotherdice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/exammanipulation" title="exammanipulation">exammanipulation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/porkbarrel" title="porkbarrel">porkbarrel</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/beehives" title="beehives">beehives</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/toys" title="toys">toys</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/entertainmentbox" title="entertainmentbox">entertainmentbox</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/plankton" title="plankton">plankton</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/babylonian" title="babylonian">babylonian</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/srednji" title="srednji">srednji</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/easyclimb" title="easyclimb">easyclimb</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pirate" title="pirate">pirate</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/whatdoesthefoxsay" title="whatdoesthefoxsay">whatdoesthefoxsay</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/squarefieldseasy" title="squarefieldseasy">squarefieldseasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/earlyorders" title="earlyorders">earlyorders</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paintedcorridors" title="paintedcorridors">paintedcorridors</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/welcomeeasy" title="welcomeeasy">welcomeeasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/romanholidays" title="romanholidays">romanholidays</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/droppingball2" title="droppingball2">droppingball2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/onewayroads" title="onewayroads">onewayroads</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/insert" title="insert">insert</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rocketstages" title="rocketstages">rocketstages</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/optimistan" title="optimistan">optimistan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/milkteabattle" title="milkteabattle">milkteabattle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tram" title="tram">tram</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/purplerain" title="purplerain">purplerain</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dickandjane" title="dickandjane">dickandjane</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/meowfactor2" title="meowfactor2">meowfactor2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mailbox" title="mailbox">mailbox</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/programmingtutors" title="programmingtutors">programmingtutors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coverup" title="coverup">coverup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rivers" title="rivers">rivers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/thedealoftheday" title="thedealoftheday">thedealoftheday</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/papersnowflakes" title="papersnowflakes">papersnowflakes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cousins" title="cousins">cousins</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lockblocked" title="lockblocked">lockblocked</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/thebackslashproblem" title="thebackslashproblem">thebackslashproblem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paintball2" title="paintball2">paintball2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chesstournament" title="chesstournament">chesstournament</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knightsmarathon" title="knightsmarathon">knightsmarathon</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tajna" title="tajna">tajna</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ninepacks" title="ninepacks">ninepacks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cargame" title="cargame">cargame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/justenoughbridges" title="justenoughbridges">justenoughbridges</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sylvester" title="sylvester">sylvester</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/minspantree" title="minspantree">minspantree</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cafeteria" title="cafeteria">cafeteria</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hoarsehorses" title="hoarsehorses">hoarsehorses</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sumoftheothers" title="sumoftheothers">sumoftheothers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/meltdown" title="meltdown">meltdown</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bulldozer" title="bulldozer">bulldozer</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hideandseek" title="hideandseek">hideandseek</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/subwayplanning" title="subwayplanning">subwayplanning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/marchofpenguins" title="marchofpenguins">marchofpenguins</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/autocorrect" title="autocorrect">autocorrect</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/heropower" title="heropower">heropower</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/softpasswords" title="softpasswords">softpasswords</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/magicalcrystals" title="magicalcrystals">magicalcrystals</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bitcointoss" title="bitcointoss">bitcointoss</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/guessingcircle" title="guessingcircle">guessingcircle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/snapperhard" title="snapperhard">snapperhard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/magicalcows" title="magicalcows">magicalcows</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/birthdaycake" title="birthdaycake">birthdaycake</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greatcircle" title="greatcircle">greatcircle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/slatkisi" title="slatkisi">slatkisi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/macarons" title="macarons">macarons</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/barcode2" title="barcode2">barcode2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/goingdutch" title="goingdutch">goingdutch</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sidewayssorting" title="sidewayssorting">sidewayssorting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lost" title="lost">lost</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/artwork" title="artwork">artwork</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gameofgnomes" title="gameofgnomes">gameofgnomes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/shopaholic" title="shopaholic">shopaholic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/segmentdistance" title="segmentdistance">segmentdistance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/apparatus" title="apparatus">apparatus</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/frenemies" title="frenemies">frenemies</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sanic" title="sanic">sanic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/limbo2" title="limbo2">limbo2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/amazingadventures" title="amazingadventures">amazingadventures</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flowfinder" title="flowfinder">flowfinder</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/recount" title="recount">recount</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/limbo1" title="limbo1">limbo1</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sequences" title="sequences">sequences</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flowerpots" title="flowerpots">flowerpots</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/qanat" title="qanat">qanat</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/walls" title="walls">walls</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lovepolygon" title="lovepolygon">lovepolygon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/escape" title="escape">escape</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/onechicken" title="onechicken">onechicken</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingscolors" title="kingscolors">kingscolors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wiknow" title="wiknow">wiknow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dungeondawdler" title="dungeondawdler">dungeondawdler</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/notamused" title="notamused">notamused</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kinarow" title="kinarow">kinarow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/whenplanetoidsalign" title="whenplanetoidsalign">whenplanetoidsalign</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/divideandconquer" title="divideandconquer">divideandconquer</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jazzitup" title="jazzitup">jazzitup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ontrack" title="ontrack">ontrack</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trezor" title="trezor">trezor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dinner" title="dinner">dinner</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/inquiryi" title="inquiryi">inquiryi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jobbyte" title="jobbyte">jobbyte</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/treasuremap" title="treasuremap">treasuremap</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/craters" title="craters">craters</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/imageprocessing" title="imageprocessing">imageprocessing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hugecampus" title="hugecampus">hugecampus</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/railway" title="railway">railway</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/committeeassignment" title="committeeassignment">committeeassignment</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/height" title="height">height</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hoppers" title="hoppers">hoppers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tightlypacked" title="tightlypacked">tightlypacked</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bridgebuilders" title="bridgebuilders">bridgebuilders</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/geneticsearch" title="geneticsearch">geneticsearch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gowithflow" title="gowithflow">gowithflow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/punctiliouscruciverbalist" title="punctiliouscruciverbalist">punctiliouscruciverbalist</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/borders" title="borders">borders</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/froshweek2" title="froshweek2">froshweek2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/freeweights" title="freeweights">freeweights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/table" title="table">table</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/asteroidmining" title="asteroidmining">asteroidmining</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fontan" title="fontan">fontan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/forestforthetrees" title="forestforthetrees">forestforthetrees</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stikl" title="stikl">stikl</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/antiarithmetic" title="antiarithmetic">antiarithmetic</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/flippingpatties" title="flippingpatties">flippingpatties</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/factstone" title="factstone">factstone</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slantdrilling" title="slantdrilling">slantdrilling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/winningthevote" title="winningthevote">winningthevote</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fastfood" title="fastfood">fastfood</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/endgame" title="endgame">endgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shetalkstoangel" title="shetalkstoangel">shetalkstoangel</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/watchlater" title="watchlater">watchlater</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/euclideantsp" title="euclideantsp">euclideantsp</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/editingexplosion" title="editingexplosion">editingexplosion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roomassignments" title="roomassignments">roomassignments</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/leprechaunhunt" title="leprechaunhunt">leprechaunhunt</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/espressobucks" title="espressobucks">espressobucks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dragonball1" title="dragonball1">dragonball1</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roadtrip" title="roadtrip">roadtrip</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/brickstopshere" title="brickstopshere">brickstopshere</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/doorman" title="doorman">doorman</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/disgruntledjudge" title="disgruntledjudge">disgruntledjudge</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/repeatedsubstrings" title="repeatedsubstrings">repeatedsubstrings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/suffidromes" title="suffidromes">suffidromes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dirtydriving" title="dirtydriving">dirtydriving</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crashingrobots" title="crashingrobots">crashingrobots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/remainderreminder" title="remainderreminder">remainderreminder</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/substitutionmania" title="substitutionmania">substitutionmania</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/crackingrsa" title="crackingrsa">crackingrsa</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crane2" title="crane2">crane2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/randomwalking" title="randomwalking">randomwalking</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/qualificationround" title="qualificationround">qualificationround</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/countingtriangles" title="countingtriangles">countingtriangles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/toy" title="toy">toy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/racinggems" title="racinggems">racinggems</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/powersof2" title="powersof2">powersof2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/chartingprogress" title="chartingprogress">chartingprogress</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/comma" title="comma">comma</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pollygone" title="pollygone">pollygone</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/planetarygrid" title="planetarygrid">planetarygrid</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ceiling" title="ceiling">ceiling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/checkingforcorrectness" title="checkingforcorrectness">checkingforcorrectness</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/physicalmusic" title="physicalmusic">physicalmusic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/streaming" title="streaming">streaming</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/busyschedule" title="busyschedule">busyschedule</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cezar" title="cezar">cezar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pandachess" title="pandachess">pandachess</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/passwords" title="passwords">passwords</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/browniepoints" title="browniepoints">browniepoints</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/canvasline" title="canvasline">canvasline</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nonprimefactors" title="nonprimefactors">nonprimefactors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/palindromecrossword" title="palindromecrossword">palindromecrossword</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bishops" title="bishops">bishops</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cake" title="cake">cake</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/najkraci" title="najkraci">najkraci</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mixingcolours" title="mixingcolours">mixingcolours</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bestcompression" title="bestcompression">bestcompression</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/birthdayboy" title="birthdayboy">birthdayboy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maxcolorclique" title="maxcolorclique">maxcolorclique</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/matrica" title="matrica">matrica</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/towering" title="towering">towering</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/base2palindrome" title="base2palindrome">base2palindrome</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/latinsquare" title="latinsquare">latinsquare</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/largeparty" title="largeparty">largeparty</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/armystrengtheasy" title="armystrengtheasy">armystrengtheasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/avoidingtheapocalypse" title="avoidingtheapocalypse">avoidingtheapocalypse</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/landinheritance" title="landinheritance">landinheritance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/krtica" title="krtica">krtica</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/3dprinter" title="3dprinter">3dprinter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/favourable" title="favourable">favourable</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kralj" title="kralj">kralj</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingdoms" title="kingdoms">kingdoms</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/toilet" title="toilet">toilet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/matryoshka" title="matryoshka">matryoshka</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingdomofants" title="kingdomofants">kingdomofants</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jackdawsandcrows" title="jackdawsandcrows">jackdawsandcrows</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/threepowers" title="threepowers">threepowers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zipfsong" title="zipfsong">zipfsong</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/keepcalmandcarryoff" title="keepcalmandcarryoff">keepcalmandcarryoff</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/impossibleprices" title="impossibleprices">impossibleprices</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/splat" title="splat">splat</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/welcomehard" title="welcomehard">welcomehard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jugglingpatterns" title="jugglingpatterns">jugglingpatterns</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hottercolder" title="hottercolder">hottercolder</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/proofs" title="proofs">proofs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/touchdown" title="touchdown">touchdown</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/juggler" title="juggler">juggler</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/friends2" title="friends2">friends2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/primepath" title="primepath">primepath</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/endoftheworld" title="endoftheworld">endoftheworld</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/intervalcover" title="intervalcover">intervalcover</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/freedesserts" title="freedesserts">freedesserts</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/permcode" title="permcode">permcode</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/skyline" title="skyline">skyline</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/helpfulcurrents" title="helpfulcurrents">helpfulcurrents</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flightsafety" title="flightsafety">flightsafety</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/perket" title="perket">perket</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/palindromesubstring" title="palindromesubstring">palindromesubstring</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/globalwarming" title="globalwarming">globalwarming</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fakeit" title="fakeit">fakeit</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ornaments" title="ornaments">ornaments</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ones" title="ones">ones</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/eulerianpath" title="eulerianpath">eulerianpath</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/excitingtournament" title="excitingtournament">excitingtournament</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/odds" title="odds">odds</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/megainversions" title="megainversions">megainversions</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/engaging" title="engaging">engaging</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/driverdisagreement" title="driverdisagreement">driverdisagreement</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/natrij" title="natrij">natrij</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/linearrecurrence" title="linearrecurrence">linearrecurrence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/election" title="election">election</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cheetahs" title="cheetahs">cheetahs</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/musicyourway" title="musicyourway">musicyourway</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knapsackcollection" title="knapsackcollection">knapsackcollection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dvaput" title="dvaput">dvaput</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/catmouse" title="catmouse">catmouse</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/lostmap" title="lostmap">lostmap</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jetpack" title="jetpack">jetpack</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/debugging" title="debugging">debugging</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/busyboard" title="busyboard">busyboard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/keywords" title="keywords">keywords</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/irrationaldivision" title="irrationaldivision">irrationaldivision</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cupid" title="cupid">cupid</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aroundthetrack2" title="aroundthetrack2">aroundthetrack2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/iboard" title="iboard">iboard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greetingcard" title="greetingcard">greetingcard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/subexpression" title="subexpression">subexpression</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/antennaplacement" title="antennaplacement">antennaplacement</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hotsprings" title="hotsprings">hotsprings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flygskam" title="flygskam">flygskam</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bridge" title="bridge">bridge</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/airport" title="airport">airport</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/eulersnumber" title="eulersnumber">eulersnumber</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fenceortho" title="fenceortho">fenceortho</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/redsocks" title="redsocks">redsocks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/abinitio" title="abinitio">abinitio</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/equalsumseasy" title="equalsumseasy">equalsumseasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/faultyrobot" title="faultyrobot">faultyrobot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ballcolors" title="ballcolors">ballcolors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alternating" title="alternating">alternating</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/saxophone" title="saxophone">saxophone</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/enemyterritory" title="enemyterritory">enemyterritory</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bakice" title="bakice">bakice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bonsai" title="bonsai">bonsai</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/drinkingsong" title="drinkingsong">drinkingsong</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/equilibrium2" title="equilibrium2">equilibrium2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arrangingwine" title="arrangingwine">arrangingwine</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/treehugging" title="treehugging">treehugging</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/display" title="display">display</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dartboard" title="dartboard">dartboard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/anewadventure" title="anewadventure">anewadventure</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/symmetry" title="symmetry">symmetry</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/compositions" title="compositions">compositions</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/connectn" title="connectn">connectn</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/airports" title="airports">airports</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slika" title="slika">slika</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/character" title="character">character</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beepers" title="beepers">beepers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/uncrossedknights" title="uncrossedknights">uncrossedknights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rinse" title="rinse">rinse</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/blackfriday" title="blackfriday">blackfriday</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cartrouble" title="cartrouble">cartrouble</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/threedigits" title="threedigits">threedigits</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/planestrainsbutnotautomobiles" title="planestrainsbutnotautomobiles">planestrainsbutnotautomobiles</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/beekeeper" title="beekeeper">beekeeper</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bumped" title="bumped">bumped</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aliens" title="aliens">aliens</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spaceinvaders" title="spaceinvaders">spaceinvaders</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/armystrengthhard" title="armystrengthhard">armystrengthhard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/boomingbusiness" title="boomingbusiness">boomingbusiness</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bugs" title="bugs">bugs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/anti11hard" title="anti11hard">anti11hard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/aprizenoonecanwin" title="aprizenoonecanwin">aprizenoonecanwin</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bookclub" title="bookclub">bookclub</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/socialresistance" title="socialresistance">socialresistance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mcpartdeux" title="mcpartdeux">mcpartdeux</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ants" title="ants">ants</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/birthdayparadox" title="birthdayparadox">birthdayparadox</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shrine" title="shrine">shrine</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/manhattan" title="manhattan">manhattan</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/zyxab" title="zyxab">zyxab</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/control" title="control">control</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shesallyak" title="shesallyak">shesallyak</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lowtoner" title="lowtoner">lowtoner</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/wordcloud" title="wordcloud">wordcloud</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/askmarilyn" title="askmarilyn">askmarilyn</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/secretsantacycles" title="secretsantacycles">secretsantacycles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingdomofhamsters" title="kingdomofhamsters">kingdomofhamsters</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/whichbase" title="whichbase">whichbase</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/classy" title="classy">classy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sandart" title="sandart">sandart</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kattislittlehelpers" title="kattislittlehelpers">kattislittlehelpers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tritiling" title="tritiling">tritiling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/xorsequences" title="xorsequences">xorsequences</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roadwork" title="roadwork">roadwork</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/justiceforants" title="justiceforants">justiceforants</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/toflur" title="toflur">toflur</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wheretolive" title="wheretolive">wheretolive</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rhombinoes" title="rhombinoes">rhombinoes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/graphicmadness" title="graphicmadness">graphicmadness</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sgcoin" title="sgcoin">sgcoin</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/timezones" title="timezones">timezones</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/redbluetree" title="redbluetree">redbluetree</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fluffycat" title="fluffycat">fluffycat</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/secretchamber" title="secretchamber">secretchamber</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/agglomerator" title="agglomerator">agglomerator</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rasterized" title="rasterized">rasterized</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/floodingfields" title="floodingfields">floodingfields</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/rollcall" title="rollcall">rollcall</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/suffixarrayreconstruction" title="suffixarrayreconstruction">suffixarrayreconstruction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/railroad" title="railroad">railroad</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/equestriagames" title="equestriagames">equestriagames</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/reachableroads" title="reachableroads">reachableroads</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/silueta" title="silueta">silueta</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pollution" title="pollution">pollution</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/equality" title="equality">equality</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/vote" title="vote">vote</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/runningmom" title="runningmom">runningmom</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/planetdestruction" title="planetdestruction">planetdestruction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/domino" title="domino">domino</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/plot" title="plot">plot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rimski" title="rimski">rimski</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/primes" title="primes">primes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/checkers" title="checkers">checkers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pizzahawaii" title="pizzahawaii">pizzahawaii</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/restaurantbribes" title="restaurantbribes">restaurantbribes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paint" title="paint">paint</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/celebritysplit" title="celebritysplit">celebritysplit</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pebblesolitaire" title="pebblesolitaire">pebblesolitaire</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rectangularcity" title="rectangularcity">rectangularcity</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/orphanbackups" title="orphanbackups">orphanbackups</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/buildboat" title="buildboat">buildboat</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/averageshard" title="averageshard">averageshard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/protectingthecollection" title="protectingthecollection">protectingthecollection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mountainvillage" title="mountainvillage">mountainvillage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bracketsequence" title="bracketsequence">bracketsequence</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pairingsocks" title="pairingsocks">pairingsocks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/playingwithnumbers" title="playingwithnumbers">playingwithnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lexicography" title="lexicography">lexicography</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bonafide" title="bonafide">bonafide</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mastermind" title="mastermind">mastermind</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/numbersetseasy" title="numbersetseasy">numbersetseasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/landscaping" title="landscaping">landscaping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bitonicordering" title="bitonicordering">bitonicordering</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/juryjeopardy" title="juryjeopardy">juryjeopardy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nonnegpartsums" title="nonnegpartsums">nonnegpartsums</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jupiter" title="jupiter">jupiter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bit4bit" title="bit4bit">bit4bit</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/irepeatmyself" title="irepeatmyself">irepeatmyself</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/naturereserve" title="naturereserve">naturereserve</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/inventing" title="inventing">inventing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/basicbasis" title="basicbasis">basicbasis</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/holeynqueensbatman" title="holeynqueensbatman">holeynqueensbatman</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/namethatpermutation" title="namethatpermutation">namethatpermutation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/intersectingrectangles" title="intersectingrectangles">intersectingrectangles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/worstweather" title="worstweather">worstweather</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/happyprime" title="happyprime">happyprime</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/piano" title="piano">piano</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/golfbot" title="golfbot">golfbot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/theimp" title="theimp">theimp</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/gettowork" title="gettowork">gettowork</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/monumentmaker" title="monumentmaker">monumentmaker</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/freegoodies" title="freegoodies">freegoodies</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/telescope" title="telescope">telescope</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/flowshop" title="flowshop">flowshop</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/modulodatastructures" title="modulodatastructures">modulodatastructures</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/excellentengineers" title="excellentengineers">excellentengineers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/symmetricpolynomials" title="symmetricpolynomials">symmetricpolynomials</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/election2" title="election2">election2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingdomofcats" title="kingdomofcats">kingdomofcats</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/endor" title="endor">endor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/subway3" title="subway3">subway3</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bubbletea" title="bubbletea">bubbletea</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kayaking" title="kayaking">kayaking</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/drafttime" title="drafttime">drafttime</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stickers" title="stickers">stickers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cursethedarkness" title="cursethedarkness">cursethedarkness</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/justenoughwater" title="justenoughwater">justenoughwater</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/diversecookies" title="diversecookies">diversecookies</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/squarepie" title="squarepie">squarepie</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cookiecutter" title="cookiecutter">cookiecutter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/itsasecret" title="itsasecret">itsasecret</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/diplomacy" title="diplomacy">diplomacy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ski" title="ski">ski</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/competitivearcadebasketball" title="competitivearcadebasketball">competitivearcadebasketball</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/interestingintegers" title="interestingintegers">interestingintegers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cutitout" title="cutitout">cutitout</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shootout" title="shootout">shootout</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cokolada" title="cokolada">cokolada</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/integerlists" title="integerlists">integerlists</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bustour" title="bustour">bustour</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/radioreceiver" title="radioreceiver">radioreceiver</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/codecleanups" title="codecleanups">codecleanups</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gradecurving" title="gradecurving">gradecurving</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/brickwall" title="brickwall">brickwall</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/podnizovi" title="podnizovi">podnizovi</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/climbingworm" title="climbingworm">climbingworm</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gopher2" title="gopher2">gopher2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/blobsofdoom" title="blobsofdoom">blobsofdoom</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pizzacutting" title="pizzacutting">pizzacutting</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/circuitmath" title="circuitmath">circuitmath</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/genijalac" title="genijalac">genijalac</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/atomicenergy" title="atomicenergy">atomicenergy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/outsourcing" title="outsourcing">outsourcing</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/calculatingdartscores" title="calculatingdartscores">calculatingdartscores</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fundamentalneighbors" title="fundamentalneighbors">fundamentalneighbors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arcade" title="arcade">arcade</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/outofcontext" title="outofcontext">outofcontext</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bits" title="bits">bits</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/freighttrain" title="freighttrain">freighttrain</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aijeopardy" title="aijeopardy">aijeopardy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jogurt" title="jogurt">jogurt</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/beatspread" title="beatspread">beatspread</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/raffle" title="raffle">raffle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ads" title="ads">ads</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/inspirationmanifestation" title="inspirationmanifestation">inspirationmanifestation</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/babelfish" title="babelfish">babelfish</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ferryloading5" title="ferryloading5">ferryloading5</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tarotshamboast" title="tarotshamboast">tarotshamboast</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ifthenelse" title="ifthenelse">ifthenelse</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/knightjump" title="knightjump">knightjump</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/euclidsgame" title="euclidsgame">euclidsgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stackmachine" title="stackmachine">stackmachine</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spidersonwater" title="spidersonwater">spidersonwater</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/wizardofodds" title="wizardofodds">wizardofodds</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/eko" title="eko">eko</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sonofpipestream" title="sonofpipestream">sonofpipestream</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/holmes" title="holmes">holmes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/treasurehunt" title="treasurehunt">treasurehunt</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/divideby100" title="divideby100">divideby100</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shuffle" title="shuffle">shuffle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/holeinone" title="holeinone">holeinone</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ada" title="ada">ada</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/digitdivision" title="digitdivision">digitdivision</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/robots" title="robots">robots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gridguardian" title="gridguardian">gridguardian</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sort" title="sort">sort</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/digbuild" title="digbuild">digbuild</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/robotmaze" title="robotmaze">robotmaze</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gottacatchemall" title="gottacatchemall">gottacatchemall</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/triangle" title="triangle">triangle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/deduplicatingfiles" title="deduplicatingfiles">deduplicatingfiles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/retribution" title="retribution">retribution</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ridofcoins" title="ridofcoins">ridofcoins</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/santaklas" title="santaklas">santaklas</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dartscoring" title="dartscoring">dartscoring</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/radiotransmission" title="radiotransmission">radiotransmission</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gamesuggestions" title="gamesuggestions">gamesuggestions</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/planetaris" title="planetaris">planetaris</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/countinggis" title="countinggis">countinggis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prosjek" title="prosjek">prosjek</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gamescheduling" title="gamescheduling">gamescheduling</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/periodicstrings" title="periodicstrings">periodicstrings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/conservation" title="conservation">conservation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/puzzle2" title="puzzle2">puzzle2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/forest" title="forest">forest</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/peasoup" title="peasoup">peasoup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/concentration" title="concentration">concentration</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pickingupthedice" title="pickingupthedice">pickingupthedice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/followthebouncingball" title="followthebouncingball">followthebouncingball</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/parket" title="parket">parket</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/companypicnic" title="companypicnic">companypicnic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pharmacy" title="pharmacy">pharmacy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fairdivisions" title="fairdivisions">fairdivisions</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/averageseasy" title="averageseasy">averageseasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/communicatingstrategy" title="communicatingstrategy">communicatingstrategy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/periodicpoints" title="periodicpoints">periodicpoints</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/englishrestaurant" title="englishrestaurant">englishrestaurant</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/nothanks" title="nothanks">nothanks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/checkmateinone" title="checkmateinone">checkmateinone</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mosaic" title="mosaic">mosaic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/eksplozija" title="eksplozija">eksplozija</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/natjecanje" title="natjecanje">natjecanje</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/busplanning" title="busplanning">busplanning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/money" title="money">money</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/easymultiplication" title="easymultiplication">easymultiplication</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mravi" title="mravi">mravi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/branch" title="branch">branch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mixedbasearithmetic" title="mixedbasearithmetic">mixedbasearithmetic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dvoniz" title="dvoniz">dvoniz</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/malfunctioningrobot" title="malfunctioningrobot">malfunctioningrobot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/boggle" title="boggle">boggle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mario" title="mario">mario</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/drawingcircles" title="drawingcircles">drawingcircles</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/lindenmayorsystem" title="lindenmayorsystem">lindenmayorsystem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zapis" title="zapis">zapis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/longincsubseq" title="longincsubseq">longincsubseq</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tiling" title="tiling">tiling</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jurassicjigsaw" title="jurassicjigsaw">jurassicjigsaw</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wifi" title="wifi">wifi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/longestcommonsubsequence" title="longestcommonsubsequence">longestcommonsubsequence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/daringdont" title="daringdont">daringdont</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/htoo" title="htoo">htoo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vudu" title="vudu">vudu</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lista" title="lista">lista</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/commonground" title="commonground">commonground</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/honey" title="honey">honey</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/turbo" title="turbo">turbo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lights" title="lights">lights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/closestpair2" title="closestpair2">closestpair2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/gridmagic" title="gridmagic">gridmagic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/triangle2hexagon" title="triangle2hexagon">triangle2hexagon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/justaquiz" title="justaquiz">justaquiz</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/declaration" title="declaration">declaration</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/genius" title="genius">genius</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/traintimetables" title="traintimetables">traintimetables</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ivana" title="ivana">ivana</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/candychain" title="candychain">candychain</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/throwns" title="throwns">throwns</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tightfitsudoku" title="tightfitsudoku">tightfitsudoku</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/investigatingimposters" title="investigatingimposters">investigatingimposters</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bowserspipes" title="bowserspipes">bowserspipes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fizzbuzz2" title="fizzbuzz2">fizzbuzz2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/subway" title="subway">subway</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/idf" title="idf">idf</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/productivity" title="productivity">productivity</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dunglish" title="dunglish">dunglish</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/socialadvertising" title="socialadvertising">socialadvertising</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/icecream2" title="icecream2">icecream2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/balltricks" title="balltricks">balltricks</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/doggopher" title="doggopher">doggopher</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/skilifts" title="skilifts">skilifts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hexagoncoloring" title="hexagoncoloring">hexagoncoloring</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/artappreciation" title="artappreciation">artappreciation</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/deceptivedice" title="deceptivedice">deceptivedice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sequence2" title="sequence2">sequence2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/haybales" title="haybales">haybales</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/queryonarray" title="queryonarray">queryonarray</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dartscores" title="dartscores">dartscores</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rockscissorspaper" title="rockscissorspaper">rockscissorspaper</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/granica" title="granica">granica</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jobbdna" title="jobbdna">jobbdna</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/crne" title="crne">crne</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/riskylottery" title="riskylottery">riskylottery</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gallup" title="gallup">gallup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coincounter" title="coincounter">coincounter</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/combinationlock" title="combinationlock">combinationlock</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pullingtheirweight" title="pullingtheirweight">pullingtheirweight</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/forestconstruction" title="forestconstruction">forestconstruction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unbalancedparentheses" title="unbalancedparentheses">unbalancedparentheses</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cardboardcontainer" title="cardboardcontainer">cardboardcontainer</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ticketpricing" title="ticketpricing">ticketpricing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flyswatter" title="flyswatter">flyswatter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/straza" title="straza">straza</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/backspace" title="backspace">backspace</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pizza" title="pizza">pizza</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/conversion" title="conversion">conversion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/smoothedgardens" title="smoothedgardens">smoothedgardens</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/areyoulistening" title="areyoulistening">areyoulistening</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pianolessons" title="pianolessons">pianolessons</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jattenfinn" title="jattenfinn">jattenfinn</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sellingspatulas" title="sellingspatulas">sellingspatulas</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/anothercandies" title="anothercandies">anothercandies</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/otpor" title="otpor">otpor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/findinglines" title="findinglines">findinglines</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/saskatchewan" title="saskatchewan">saskatchewan</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/artichoke" title="artichoke">artichoke</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ntnuorienteering" title="ntnuorienteering">ntnuorienteering</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/figurinefigures" title="figurinefigures">figurinefigures</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/racetrack" title="racetrack">racetrack</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/alldifferentdirections" title="alldifferentdirections">alldifferentdirections</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mallmania" title="mallmania">mallmania</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/farmingmars" title="farmingmars">farmingmars</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/obfuscation" title="obfuscation">obfuscation</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/martiandna" title="martiandna">martiandna</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/longestcommonsubstring" title="longestcommonsubstring">longestcommonsubstring</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/expandingrods" title="expandingrods">expandingrods</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/norma" title="norma">norma</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bryr" title="bryr">bryr</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lipschitzconstant" title="lipschitzconstant">lipschitzconstant</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/exhaustiveexperiment" title="exhaustiveexperiment">exhaustiveexperiment</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/longlongstrings" title="longlongstrings">longlongstrings</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/lyklagangriti" title="lyklagangriti">lyklagangriti</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kuhar" title="kuhar">kuhar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/errands" title="errands">errands</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knox" title="knox">knox</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/universityzoning" title="universityzoning">universityzoning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/joggingtrails" title="joggingtrails">joggingtrails</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ecocover" title="ecocover">ecocover</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/keys" title="keys">keys</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/wordsfornumbers" title="wordsfornumbers">wordsfornumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gorillas" title="gorillas">gorillas</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/drzava" title="drzava">drzava</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/moretriangles" title="moretriangles">moretriangles</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/woodensigns" title="woodensigns">woodensigns</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/goofy" title="goofy">goofy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crabbles" title="crabbles">crabbles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hauntedgraveyard" title="hauntedgraveyard">hauntedgraveyard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/woodcutting" title="woodcutting">woodcutting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/goodmessages" title="goodmessages">goodmessages</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cosmocraft" title="cosmocraft">cosmocraft</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gottanudge" title="gottanudge">gottanudge</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/variablearithmetic" title="variablearithmetic">variablearithmetic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gmo" title="gmo">gmo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/classrooms" title="classrooms">classrooms</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fallingsnow" title="fallingsnow">fallingsnow</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/trollhunt" title="trollhunt">trollhunt</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gluttonousgoop" title="gluttonousgoop">gluttonousgoop</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/classpicture" title="classpicture">classpicture</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paired" title="paired">paired</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/textureanalysis" title="textureanalysis">textureanalysis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/galaksija" title="galaksija">galaksija</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chuck" title="chuck">chuck</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dominatingduos" title="dominatingduos">dominatingduos</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/stickysituation" title="stickysituation">stickysituation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/forestfires" title="forestfires">forestfires</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cdvii" title="cdvii">cdvii</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/diceandladders" title="diceandladders">diceandladders</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sretan" title="sretan">sretan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/famouspagoda" title="famouspagoda">famouspagoda</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/battleofhogwarts" title="battleofhogwarts">battleofhogwarts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dance" title="dance">dance</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/smartphone" title="smartphone">smartphone</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/facility" title="facility">facility</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bagoftiles" title="bagoftiles">bagoftiles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coupons" title="coupons">coupons</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/simon" title="simon">simon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cpu" title="cpu">cpu</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/assemblyline" title="assemblyline">assemblyline</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/classicalcounting" title="classicalcounting">classicalcounting</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/putovanje" title="putovanje">putovanje</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dontfencemein" title="dontfencemein">dontfencemein</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aspenavenue" title="aspenavenue">aspenavenue</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cellularmerging" title="cellularmerging">cellularmerging</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pripreme" title="pripreme">pripreme</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dominos" title="dominos">dominos</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/manresor" title="manresor">manresor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bribingeve" title="bribingeve">bribingeve</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/permutationencryption" title="permutationencryption">permutationencryption</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/distributingseats" title="distributingseats">distributingseats</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/witchdance" title="witchdance">witchdance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aliencodebreaking" title="aliencodebreaking">aliencodebreaking</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/anti11" title="anti11">anti11</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/decodingthehallway" title="decodingthehallway">decodingthehallway</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/winningstreak" title="winningstreak">winningstreak</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/barshelf" title="barshelf">barshelf</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/lockedtreasure" title="lockedtreasure">lockedtreasure</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/damsindistress" title="damsindistress">damsindistress</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/whostheboss" title="whostheboss">whostheboss</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/whowantstoliveforever" title="whowantstoliveforever">whowantstoliveforever</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/lineup" title="lineup">lineup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crypto" title="crypto">crypto</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/visual" title="visual">visual</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tugofwar" title="tugofwar">tugofwar</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ladice" title="ladice">ladice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/checks" title="checks">checks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trackingshares" title="trackingshares">trackingshares</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/triangles2" title="triangles2">triangles2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/grandpabernie" title="grandpabernie">grandpabernie</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/builddeps" title="builddeps">builddeps</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thepointofnoreturn" title="thepointofnoreturn">thepointofnoreturn</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/theescape" title="theescape">theescape</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/goodmorning" title="goodmorning">goodmorning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bread" title="bread">bread</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/taxededitor" title="taxededitor">taxededitor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sumsets" title="sumsets">sumsets</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/evenup" title="evenup">evenup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/blockcrusher" title="blockcrusher">blockcrusher</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tantrix" title="tantrix">tantrix</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/science" title="science">science</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/carousel" title="carousel">carousel</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bells" title="bells">bells</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sweetandsmoky" title="sweetandsmoky">sweetandsmoky</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/program" title="program">program</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/candlebox" title="candlebox">candlebox</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beehives2" title="beehives2">beehives2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roomservice" title="roomservice">roomservice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pieceofcake" title="pieceofcake">pieceofcake</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/busnumbers" title="busnumbers">busnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/battleship" title="battleship">battleship</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/quadres" title="quadres">quadres</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pasijans" title="pasijans">pasijans</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bottledup" title="bottledup">bottledup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/azulejos" title="azulejos">azulejos</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pokeball" title="pokeball">pokeball</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ograda" title="ograda">ograda</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bitbybit" title="bitbybit">bitbybit</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/simplearithmetic" title="simplearithmetic">simplearithmetic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/planete" title="planete">planete</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nvwls" title="nvwls">nvwls</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bazen" title="bazen">bazen</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shortestpath4" title="shortestpath4">shortestpath4</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/olympiadtraining" title="olympiadtraining">olympiadtraining</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nimcheater" title="nimcheater">nimcheater</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bard" title="bard">bard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/forestfruits" title="forestfruits">forestfruits</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/oddandevenzeroes" title="oddandevenzeroes">oddandevenzeroes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/necklace" title="necklace">necklace</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/anthonyanddiablo" title="anthonyanddiablo">anthonyanddiablo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zabava" title="zabava">zabava</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nullarycomputer" title="nullarycomputer">nullarycomputer</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/icecream" title="icecream">icecream</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/amsterdamdistance" title="amsterdamdistance">amsterdamdistance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unreadmessages" title="unreadmessages">unreadmessages</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/newsalaries" title="newsalaries">newsalaries</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greeneggs" title="greeneggs">greeneggs</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/listgame" title="listgame">listgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/turningtrominos" title="turningtrominos">turningtrominos</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/memory2" title="memory2">memory2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/feistelfun" title="feistelfun">feistelfun</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/different" title="different">different</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thesaurus" title="thesaurus">thesaurus</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/manhattanshopping" title="manhattanshopping">manhattanshopping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/debellatio" title="debellatio">debellatio</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/waif" title="waif">waif</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/studentsko" title="studentsko">studentsko</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/magicalgcd" title="magicalgcd">magicalgcd</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/closingtheborders" title="closingtheborders">closingtheborders</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/queenspatio" title="queenspatio">queenspatio</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stirlingsapproximation" title="stirlingsapproximation">stirlingsapproximation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/parade" title="parade">parade</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/catmasgifts" title="catmasgifts">catmasgifts</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/soundex" title="soundex">soundex</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stigavordur" title="stigavordur">stigavordur</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jednakost" title="jednakost">jednakost</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cars" title="cars">cars</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/snappereasy" title="snappereasy">snappereasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/safepassage" title="safepassage">safepassage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jackthelumberjack" title="jackthelumberjack">jackthelumberjack</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/badpacking" title="badpacking">badpacking</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/shiritori" title="shiritori">shiritori</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roberthood" title="roberthood">roberthood</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mortgage" title="mortgage">mortgage</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/attendance" title="attendance">attendance</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/seti" title="seti">seti</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/reversingroads" title="reversingroads">reversingroads</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/introtation" title="introtation">introtation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/areaofeffect" title="areaofeffect">areaofeffect</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/secretsanta" title="secretsanta">secretsanta</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/replicate" title="replicate">replicate</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/insidersidentity" title="insidersidentity">insidersidentity</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/allergy" title="allergy">allergy</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/runningsteps" title="runningsteps">runningsteps</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/railway2" title="railway2">railway2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hillnumbers" title="hillnumbers">hillnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/withinarmsreach" title="withinarmsreach">withinarmsreach</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/roundedbuttons" title="roundedbuttons">roundedbuttons</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prinova" title="prinova">prinova</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hiddencamera" title="hiddencamera">hiddencamera</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wheelgame" title="wheelgame">wheelgame</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/robotprotection" title="robotprotection">robotprotection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/primesieve" title="primesieve">primesieve</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/help2" title="help2">help2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vending" title="vending">vending</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/rhyming" title="rhyming">rhyming</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/playground" title="playground">playground</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/frozenrose" title="frozenrose">frozenrose</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/uprooted" title="uprooted">uprooted</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/reseto" title="reseto">reseto</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pie" title="pie">pie</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/easterholidays" title="easterholidays">easterholidays</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unrealestate" title="unrealestate">unrealestate</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/primaryarithmetic" title="primaryarithmetic">primaryarithmetic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pegsandlegs" title="pegsandlegs">pegsandlegs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dugovi" title="dugovi">dugovi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/triangles" title="triangles">triangles</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/powersof2easy" title="powersof2easy">powersof2easy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maximumsubarrays" title="maximumsubarrays">maximumsubarrays</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/droppingball" title="droppingball">droppingball</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/treasure" title="treasure">treasure</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/playfair" title="playfair">playfair</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ljutnja" title="ljutnja">ljutnja</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/difference" title="difference">difference</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/reseplanering" title="reseplanering">reseplanering</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/platforme" title="platforme">platforme</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kinversions" title="kinversions">kinversions</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dancehard" title="dancehard">dancehard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thebigmacquestion" title="thebigmacquestion">thebigmacquestion</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/piperotation" title="piperotation">piperotation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingofthewaves" title="kingofthewaves">kingofthewaves</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dailydivision" title="dailydivision">dailydivision</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/skakavac" title="skakavac">skakavac</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/movingday" title="movingday">movingday</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/justpassingthrough" title="justpassingthrough">justpassingthrough</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/connect" title="connect">connect</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sightseeingtour" title="sightseeingtour">sightseeingtour</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/kutevi" title="kutevi">kutevi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/janeeyre" title="janeeyre">janeeyre</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cockchafer" title="cockchafer">cockchafer</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rebeldie" title="rebeldie">rebeldie</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/kolone" title="kolone">kolone</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/inspectingillumination" title="inspectingillumination">inspectingillumination</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/carpool" title="carpool">carpool</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prospecting" title="prospecting">prospecting</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/judging" title="judging">judging</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ingredients" title="ingredients">ingredients</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/canyoncrossing" title="canyoncrossing">canyoncrossing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nanagrams" title="nanagrams">nanagrams</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jointattack" title="jointattack">jointattack</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/icpccamp" title="icpccamp">icpccamp</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/canofworms" title="canofworms">canofworms</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/moveablemaze" title="moveablemaze">moveablemaze</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/iwannabe" title="iwannabe">iwannabe</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/halloweemirrors" title="halloweemirrors">halloweemirrors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/brickpartition" title="brickpartition">brickpartition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kenken" title="kenken">kenken</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/helpme" title="helpme">helpme</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gridgame" title="gridgame">gridgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/brainfsckvm" title="brainfsckvm">brainfsckvm</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kabobs" title="kabobs">kabobs</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hardwoodspecies" title="hardwoodspecies">hardwoodspecies</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gravity" title="gravity">gravity</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/blowingcandles" title="blowingcandles">blowingcandles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/highwayhassle" title="highwayhassle">highwayhassle</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/goldbach2" title="goldbach2">goldbach2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/goingtoseed" title="goingtoseed">goingtoseed</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/basicinterpreter" title="basicinterpreter">basicinterpreter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gameofdivisibility" title="gameofdivisibility">gameofdivisibility</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/glyphrecognition" title="glyphrecognition">glyphrecognition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/clue" title="clue">clue</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tank" title="tank">tank</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/foodreview" title="foodreview">foodreview</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fibonaccicycles" title="fibonaccicycles">fibonaccicycles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fareysums" title="fareysums">fareysums</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/xormax" title="xormax">xormax</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roads" title="roads">roads</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/doubleplusgood" title="doubleplusgood">doubleplusgood</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/expeditiouscubing" title="expeditiouscubing">expeditiouscubing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/weirdflecksbutok" title="weirdflecksbutok">weirdflecksbutok</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/excludescoring" title="excludescoring">excludescoring</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/crosscountry" title="crosscountry">crosscountry</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/enviousexponents" title="enviousexponents">enviousexponents</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/uniformsubtrees" title="uniformsubtrees">uniformsubtrees</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dvdscreensaver" title="dvdscreensaver">dvdscreensaver</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/busnumbers2" title="busnumbers2">busnumbers2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/contentprotection" title="contentprotection">contentprotection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/treequivalence" title="treequivalence">treequivalence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/djgigs" title="djgigs">djgigs</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bobby" title="bobby">bobby</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/codenames" title="codenames">codenames</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/travelingmerchant" title="travelingmerchant">travelingmerchant</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/debug" title="debug">debug</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bachetsgame" title="bachetsgame">bachetsgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/joggers" title="joggers">joggers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/topovi" title="topovi">topovi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cumulative" title="cumulative">cumulative</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/acm2" title="acm2">acm2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/burglary" title="burglary">burglary</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trip" title="trip">trip</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/castingspells" title="castingspells">castingspells</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ninetynine" title="ninetynine">ninetynine</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bungeejumping" title="bungeejumping">bungeejumping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/superdoku" title="superdoku">superdoku</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/borgboogie" title="borgboogie">borgboogie</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/vaccineefficacy" title="vaccineefficacy">vaccineefficacy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arachnophobia" title="arachnophobia">arachnophobia</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sunlight" title="sunlight">sunlight</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bling" title="bling">bling</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tildes" title="tildes">tildes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/andrewant" title="andrewant">andrewant</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slimcut" title="slimcut">slimcut</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bearlymadeit" title="bearlymadeit">bearlymadeit</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/weightofwords" title="weightofwords">weightofwords</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alehouse" title="alehouse">alehouse</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/single" title="single">single</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/yikes" title="yikes">yikes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/squarepegs" title="squarepegs">squarepegs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/adventuremoving4" title="adventuremoving4">adventuremoving4</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/runningroutes" title="runningroutes">runningroutes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/virussynthesis" title="virussynthesis">virussynthesis</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/smoothiestand" title="smoothiestand">smoothiestand</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bokforing" title="bokforing">bokforing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zamboni" title="zamboni">zamboni</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stogovi" title="stogovi">stogovi</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/shuffling" title="shuffling">shuffling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/restaurant" title="restaurant">restaurant</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/politicaldevelopment" title="politicaldevelopment">politicaldevelopment</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stampstamp" title="stampstamp">stampstamp</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/parsinghex" title="parsinghex">parsinghex</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wolf" title="wolf">wolf</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pipes2" title="pipes2">pipes2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prokletnik" title="prokletnik">prokletnik</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/narrowartgallery" title="narrowartgallery">narrowartgallery</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/virtualfriends" title="virtualfriends">virtualfriends</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paleta" title="paleta">paleta</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/produktsiffra" title="produktsiffra">produktsiffra</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mountainbiking" title="mountainbiking">mountainbiking</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/worminapple" title="worminapple">worminapple</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flowers" title="flowers">flowers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/probedroids" title="probedroids">probedroids</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/keepitcool" title="keepitcool">keepitcool</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thecolonizationofelgarizm" title="thecolonizationofelgarizm">thecolonizationofelgarizm</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nuremberg" title="nuremberg">nuremberg</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/poslozi" title="poslozi">poslozi</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/islands" title="islands">islands</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tenkici" title="tenkici">tenkici</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mayhem" title="mayhem">mayhem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pinball" title="pinball">pinball</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/porpoises" title="porpoises">porpoises</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/swapspace" title="swapspace">swapspace</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/more10" title="more10">more10</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/letsmeet" title="letsmeet">letsmeet</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/icpcteamselection" title="icpcteamselection">icpcteamselection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/svm" title="svm">svm</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lostisclosetolose" title="lostisclosetolose">lostisclosetolose</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/learningtocode" title="learningtocode">learningtocode</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hopscotch50" title="hopscotch50">hopscotch50</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/consecutivesums" title="consecutivesums">consecutivesums</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/keepthemseparated" title="keepthemseparated">keepthemseparated</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kthsubtree" title="kthsubtree">kthsubtree</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fractionallotion" title="fractionallotion">fractionallotion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/subway2" title="subway2">subway2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/interview" title="interview">interview</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/keepitsorted" title="keepitsorted">keepitsorted</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/falcondive" title="falcondive">falcondive</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/setnja" title="setnja">setnja</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/double" title="double">double</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hubtown" title="hubtown">hubtown</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/escapewallmaria" title="escapewallmaria">escapewallmaria</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/savinguniverse" title="savinguniverse">savinguniverse</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/distinctivecharacter" title="distinctivecharacter">distinctivecharacter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/funwithfibonacci" title="funwithfibonacci">funwithfibonacci</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/elevatortrouble" title="elevatortrouble">elevatortrouble</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rainfall2" title="rainfall2">rainfall2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cudak" title="cudak">cudak</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/doublets" title="doublets">doublets</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dasort" title="dasort">dasort</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rainbowgraph" title="rainbowgraph">rainbowgraph</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cuckoo" title="cuckoo">cuckoo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/containment" title="containment">containment</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/conversationlog" title="conversationlog">conversationlog</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/quantumsuperposition" title="quantumsuperposition">quantumsuperposition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/convexcontour" title="convexcontour">convexcontour</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/compensation" title="compensation">compensation</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cantor" title="cantor">cantor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pandapreserve" title="pandapreserve">pandapreserve</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/closestpair1" title="closestpair1">closestpair1</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cactus" title="cactus">cactus</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/brokencalculator" title="brokencalculator">brokencalculator</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/minecraftdungeons" title="minecraftdungeons">minecraftdungeons</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cliffwalk" title="cliffwalk">cliffwalk</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/busclock" title="busclock">busclock</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/batmanacci" title="batmanacci">batmanacci</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mathemagicians" title="mathemagicians">mathemagicians</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/debt" title="debt">debt</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/battleofpokenom" title="battleofpokenom">battleofpokenom</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/awkwardparty" title="awkwardparty">awkwardparty</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/matchgame" title="matchgame">matchgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cheergame" title="cheergame">cheergame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/applemarket" title="applemarket">applemarket</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/anagramcounting" title="anagramcounting">anagramcounting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knapsack" title="knapsack">knapsack</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/catandmice" title="catandmice">catandmice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aplusb" title="aplusb">aplusb</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/almostperfect" title="almostperfect">almostperfect</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jointexcavation" title="jointexcavation">jointexcavation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/atlantis" title="atlantis">atlantis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trimmingpolygons" title="trimmingpolygons">trimmingpolygons</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/4thought" title="4thought">4thought</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/intents" title="intents">intents</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/anttyping" title="anttyping">anttyping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trickshot" title="trickshot">trickshot</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/2048" title="2048">2048</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/inflagrantedelicto" title="inflagrantedelicto">inflagrantedelicto</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/anothercoinweighingpuzzle" title="anothercoinweighingpuzzle">anothercoinweighingpuzzle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/triangularclouds" title="triangularclouds">triangularclouds</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/wffnproof" title="wffnproof">wffnproof</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/incrementalinduction" title="incrementalinduction">incrementalinduction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/race" title="race">race</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/travelingsalesman" title="travelingsalesman">travelingsalesman</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hailstone" title="hailstone">hailstone</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ghostbusters" title="ghostbusters">ghostbusters</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/administrativeproblems" title="administrativeproblems">administrativeproblems</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spider" title="spider">spider</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/queens" title="queens">queens</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/garbagetracking" title="garbagetracking">garbagetracking</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wiseguy" title="wiseguy">wiseguy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ringworld" title="ringworld">ringworld</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/trainboarding" title="trainboarding">trainboarding</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gcpc" title="gcpc">gcpc</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wire" title="wire">wire</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nnnnn" title="nnnnn">nnnnn</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/trip2007" title="trip2007">trip2007</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fakenews" title="fakenews">fakenews</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/twentyfour" title="twentyfour">twentyfour</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/languagesurvey" title="languagesurvey">languagesurvey</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/summertrip" title="summertrip">summertrip</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/erdosnumbers" title="erdosnumbers">erdosnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/triangles3" title="triangles3">triangles3</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kiwitrees" title="kiwitrees">kiwitrees</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/simplicity" title="simplicity">simplicity</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ecoins" title="ecoins">ecoins</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trianglecuts" title="trianglecuts">trianglecuts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hack" title="hack">hack</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/safehouses" title="safehouses">safehouses</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dna" title="dna">dna</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trainsorting" title="trainsorting">trainsorting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/goldbandits" title="goldbandits">goldbandits</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/polygonarea" title="polygonarea">polygonarea</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dividingkingdom" title="dividingkingdom">dividingkingdom</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/redgem" title="redgem">redgem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gathering" title="gathering">gathering</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pleasegofirst" title="pleasegofirst">pleasegofirst</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/detour" title="detour">detour</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/surveillance2" title="surveillance2">surveillance2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fractaltree" title="fractaltree">fractaltree</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/musicaltrees" title="musicaltrees">musicaltrees</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cheats" title="cheats">cheats</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/streamstats" title="streamstats">streamstats</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/floatingpoints" title="floatingpoints">floatingpoints</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/multigram" title="multigram">multigram</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cheatingbooleantree" title="cheatingbooleantree">cheatingbooleantree</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/staza" title="staza">staza</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fixingbugs" title="fixingbugs">fixingbugs</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/plowking" title="plowking">plowking</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/centsavings" title="centsavings">centsavings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/starsinacan" title="starsinacan">starsinacan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/divljak" title="divljak">divljak</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/missinggnomes" title="missinggnomes">missinggnomes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/buggyrobot2" title="buggyrobot2">buggyrobot2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stanovi" title="stanovi">stanovi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/deletethis" title="deletethis">deletethis</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/matrix" title="matrix">matrix</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/brexitnegotiations" title="brexitnegotiations">brexitnegotiations</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/snakes" title="snakes">snakes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crisscross" title="crisscross">crisscross</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mandelbrot" title="mandelbrot">mandelbrot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/iforaneye" title="iforaneye">iforaneye</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sellingland" title="sellingland">sellingland</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cantstopplaying" title="cantstopplaying">cantstopplaying</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/incognito" title="incognito">incognito</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zigzag2" title="zigzag2">zigzag2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roundtrips" title="roundtrips">roundtrips</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pikemanhard" title="pikemanhard">pikemanhard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tutorial" title="tutorial">tutorial</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/xorequation" title="xorequation">xorequation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/substrings" title="substrings">substrings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arable" title="arable">arable</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/guessthedatastructure" title="guessthedatastructure">guessthedatastructure</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vivoparc" title="vivoparc">vivoparc</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rats" title="rats">rats</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/anothersubstringqueryproblem" title="anothersubstringqueryproblem">anothersubstringqueryproblem</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fromatob" title="fromatob">fromatob</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vanishingparentheses" title="vanishingparentheses">vanishingparentheses</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/proteins" title="proteins">proteins</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wizarddance" title="wizarddance">wizarddance</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dvds" title="dvds">dvds</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unfairplay" title="unfairplay">unfairplay</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prisonrearrangement" title="prisonrearrangement">prisonrearrangement</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tree" title="tree">tree</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/deathtaxes" title="deathtaxes">deathtaxes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ultraquicksort" title="ultraquicksort">ultraquicksort</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/princeandprincess" title="princeandprincess">princeandprincess</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ultimatepipegame" title="ultimatepipegame">ultimatepipegame</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cheese" title="cheese">cheese</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/transportationplanning" title="transportationplanning">transportationplanning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/polymul2" title="polymul2">polymul2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trains" title="trains">trains</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bottles" title="bottles">bottles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tomosynthesis" title="tomosynthesis">tomosynthesis</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/poklon" title="poklon">poklon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/foxandowl" title="foxandowl">foxandowl</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cuchitunnels" title="cuchitunnels">cuchitunnels</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thedragonandtheknights" title="thedragonandtheknights">thedragonandtheknights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/numbersetshard" title="numbersetshard">numbersetshard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shovellingcost" title="shovellingcost">shovellingcost</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/countingstars" title="countingstars">countingstars</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/biggesttriangle" title="biggesttriangle">biggesttriangle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/nonboringsequences" title="nonboringsequences">nonboringsequences</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shovelling" title="shovelling">shovelling</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/closestsums" title="closestsums">closestsums</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thathanoi" title="thathanoi">thathanoi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/numbers" title="numbers">numbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/saturnbees" title="saturnbees">saturnbees</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/chess" title="chess">chess</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/taxing" title="taxing">taxing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/neverjumpdown" title="neverjumpdown">neverjumpdown</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/perfecttree" title="perfecttree">perfecttree</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cantinaofbabel" title="cantinaofbabel">cantinaofbabel</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spiderman" title="spiderman">spiderman</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/monitoringskipaths" title="monitoringskipaths">monitoringskipaths</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/peaktower" title="peaktower">peaktower</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/battlesimulation" title="battlesimulation">battlesimulation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/junk" title="junk">junk</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gradient" title="gradient">gradient</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/niceprefixes" title="niceprefixes">niceprefixes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/industrialspy" title="industrialspy">industrialspy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sixdegrees" title="sixdegrees">sixdegrees</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/message" title="message">message</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/moneytransfers" title="moneytransfers">moneytransfers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/wertyu" title="wertyu">wertyu</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shortestpath3" title="shortestpath3">shortestpath3</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maximizingyourpay" title="maximizingyourpay">maximizingyourpay</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maptiles" title="maptiles">maptiles</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tourdefrance" title="tourdefrance">tourdefrance</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/roadtrip2" title="roadtrip2">roadtrip2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/equationsolver" title="equationsolver">equationsolver</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kcolouring" title="kcolouring">kcolouring</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/loowater" title="loowater">loowater</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/reservoir" title="reservoir">reservoir</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jumpingmonkey" title="jumpingmonkey">jumpingmonkey</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/icar" title="icar">icar</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/thanos" title="thanos">thanos</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/redblacktree" title="redblacktree">redblacktree</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/juice2" title="juice2">juice2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/histogrami" title="histogrami">histogrami</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/textmessaging" title="textmessaging">textmessaging</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/powers" title="powers">powers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/journalediting" title="journalediting">journalediting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hilldriving" title="hilldriving">hilldriving</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/teacherevaluation" title="teacherevaluation">teacherevaluation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/powereggs" title="powereggs">powereggs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/joeislearningtospeak" title="joeislearningtospeak">joeislearningtospeak</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hardevidence" title="hardevidence">hardevidence</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/2naire" title="2naire">2naire</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/polyomino" title="polyomino">polyomino</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/inkblots" title="inkblots">inkblots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/guessthenumbers" title="guessthenumbers">guessthenumbers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/rot" title="rot">rot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/geometry" title="geometry">geometry</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bettor" title="bettor">bettor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/friendlyfire" title="friendlyfire">friendlyfire</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/reducedidnumbers" title="reducedidnumbers">reducedidnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pedalpower" title="pedalpower">pedalpower</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gravamen" title="gravamen">gravamen</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fishingcontest" title="fishingcontest">fishingcontest</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/recenice" title="recenice">recenice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hyperpyramids" title="hyperpyramids">hyperpyramids</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/godzilla" title="godzilla">godzilla</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dryicecream" title="dryicecream">dryicecream</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pyramidkonstruktion" title="pyramidkonstruktion">pyramidkonstruktion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/overlappingmaps" title="overlappingmaps">overlappingmaps</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/galactic" title="galactic">galactic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dangerousskiing" title="dangerousskiing">dangerousskiing</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/posterize" title="posterize">posterize</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/messages" title="messages">messages</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/freecell" title="freecell">freecell</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cycleshard" title="cycleshard">cycleshard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/playingtheslots" title="playingtheslots">playingtheslots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/manhattanmornings" title="manhattanmornings">manhattanmornings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ferryloading" title="ferryloading">ferryloading</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/countingpalindromes" title="countingpalindromes">countingpalindromes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/neutralground" title="neutralground">neutralground</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/luckynumber" title="luckynumber">luckynumber</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fencing" title="fencing">fencing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/buriedtreasure" title="buriedtreasure">buriedtreasure</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/missingnumber" title="missingnumber">missingnumber</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/litespace" title="litespace">litespace</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/familiar" title="familiar">familiar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/buenosairlines" title="buenosairlines">buenosairlines</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/millionairemadness" title="millionairemadness">millionairemadness</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lazylearner" title="lazylearner">lazylearner</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/evolution" title="evolution">evolution</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/basincity" title="basincity">basincity</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/maximumrent" title="maximumrent">maximumrent</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/joinstrings" title="joinstrings">joinstrings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/elderscrollbar" title="elderscrollbar">elderscrollbar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maintenance" title="maintenance">maintenance</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/marblestree" title="marblestree">marblestree</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jailbreak" title="jailbreak">jailbreak</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/eeriesubarrays" title="eeriesubarrays">eeriesubarrays</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/assistantranking" title="assistantranking">assistantranking</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/islandhopping" title="islandhopping">islandhopping</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ironman" title="ironman">ironman</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/directingrainfall" title="directingrainfall">directingrainfall</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zabe" title="zabe">zabe</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/illiteracy" title="illiteracy">illiteracy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/screen" title="screen">screen</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/costlycontest" title="costlycontest">costlycontest</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/structuralintegrity" title="structuralintegrity">structuralintegrity</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/horror" title="horror">horror</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gruesomecave" title="gruesomecave">gruesomecave</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coprimeintegers" title="coprimeintegers">coprimeintegers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sms" title="sms">sms</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/rectangularspiral" title="rectangularspiral">rectangularspiral</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gigcombinatorics" title="gigcombinatorics">gigcombinatorics</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/codetheft" title="codetheft">codetheft</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/polygon" title="polygon">polygon</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/geppetto" title="geppetto">geppetto</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ghostbusters2" title="ghostbusters2">ghostbusters2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cheatingluck" title="cheatingluck">cheatingluck</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maze2" title="maze2">maze2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/flowfree" title="flowfree">flowfree</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gamenight" title="gamenight">gamenight</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/catenyms" title="catenyms">catenyms</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/knightofthetarotcards" title="knightofthetarotcards">knightofthetarotcards</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fencebowling" title="fencebowling">fencebowling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fulltank" title="fulltank">fulltank</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bundles" title="bundles">bundles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thief" title="thief">thief</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dyslectionary" title="dyslectionary">dyslectionary</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/freckles" title="freckles">freckles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fence2" title="fence2">fence2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jabuke2" title="jabuke2">jabuke2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dodecaphony" title="dodecaphony">dodecaphony</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/foldedmap" title="foldedmap">foldedmap</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/biggest" title="biggest">biggest</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/intellectualproperty" title="intellectualproperty">intellectualproperty</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/safe" title="safe">safe</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/firstofhername" title="firstofhername">firstofhername</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beautifulsquare" title="beautifulsquare">beautifulsquare</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/infectionestimation" title="infectionestimation">infectionestimation</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/catcoat" title="catcoat">catcoat</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fibonacci" title="fibonacci">fibonacci</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/apostrophecatastrophe" title="apostrophecatastrophe">apostrophecatastrophe</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/firingphaser" title="firingphaser">firingphaser</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pikemaneasy" title="pikemaneasy">pikemaneasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crni" title="crni">crni</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/abstractart" title="abstractart">abstractart</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cpu2" title="cpu2">cpu2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/airconditioned" title="airconditioned">airconditioned</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coci" title="coci">coci</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/snobollskrig2" title="snobollskrig2">snobollskrig2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/enigma" title="enigma">enigma</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fluortanten" title="fluortanten">fluortanten</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/chocolates" title="chocolates">chocolates</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zoninghouses" title="zoninghouses">zoninghouses</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/darts" title="darts">darts</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/rafting" title="rafting">rafting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/busticket" title="busticket">busticket</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/v" title="v">v</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cairocorridor" title="cairocorridor">cairocorridor</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/turtlemaster" title="turtlemaster">turtlemaster</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beeproblem" title="beeproblem">beeproblem</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tourist" title="tourist">tourist</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/boardcovering" title="boardcovering">boardcovering</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tiredterry" title="tiredterry">tiredterry</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/walkforest" title="walkforest">walkforest</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingswalk" title="kingswalk">kingswalk</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/betweendarkanddawn" title="betweendarkanddawn">betweendarkanddawn</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tiles" title="tiles">tiles</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/assassins" title="assassins">assassins</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stringgame" title="stringgame">stringgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bats" title="bats">bats</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/mazemakers" title="mazemakers">mazemakers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/addemup" title="addemup">addemup</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/starwarsmovies" title="starwarsmovies">starwarsmovies</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ascendingphoto" title="ascendingphoto">ascendingphoto</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/snim" title="snim">snim</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zoning" title="zoning">zoning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/starwars" title="starwars">starwars</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/typecharts" title="typecharts">typecharts</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/sequentialmanufacturing" title="sequentialmanufacturing">sequentialmanufacturing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/uzastopni" title="uzastopni">uzastopni</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/securitybadge" title="securitybadge">securitybadge</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stretching" title="stretching">stretching</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/problemclassification" title="problemclassification">problemclassification</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/usingdigits" title="usingdigits">usingdigits</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/scenery" title="scenery">scenery</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/skysthelimit" title="skysthelimit">skysthelimit</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/peggamefortwo" title="peggamefortwo">peggamefortwo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/uniquedice" title="uniquedice">uniquedice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/returnofthejedi" title="returnofthejedi">returnofthejedi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/shotcube" title="shotcube">shotcube</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/outofsorts" title="outofsorts">outofsorts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/whiterabbit" title="whiterabbit">whiterabbit</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/redoks" title="redoks">redoks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/flightpath" title="flightpath">flightpath</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/moneymatters" title="moneymatters">moneymatters</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/politics" title="politics">politics</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/putnik" title="putnik">putnik</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/russiandolls" title="russiandolls">russiandolls</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/milestones" title="milestones">milestones</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sound" title="sound">sound</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pseudorandomnumbers" title="pseudorandomnumbers">pseudorandomnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/palindromes" title="palindromes">palindromes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/lektira" title="lektira">lektira</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/subsequencesinsubstrings" title="subsequencesinsubstrings">subsequencesinsubstrings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/princeza" title="princeza">princeza</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maxloot" title="maxloot">maxloot</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/kaleidoscopicpalindromes" title="kaleidoscopicpalindromes">kaleidoscopicpalindromes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stretchingstreamers" title="stretchingstreamers">stretchingstreamers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/poplocavanje" title="poplocavanje">poplocavanje</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lcmtree" title="lcmtree">lcmtree</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/integerdivision" title="integerdivision">integerdivision</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stopcounting" title="stopcounting">stopcounting</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pieceittogether" title="pieceittogether">pieceittogether</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kemija" title="kemija">kemija</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ignore" title="ignore">ignore</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/spaceprobe" title="spaceprobe">spaceprobe</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/permrle" title="permrle">permrle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/guessthedigits" title="guessthedigits">guessthedigits</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/hypercube" title="hypercube">hypercube</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slom" title="slom">slom</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/review" title="review">review</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/forestofcelery" title="forestofcelery">forestofcelery</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/guess" title="guess">guess</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sheldon" title="sheldon">sheldon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/parovi2" title="parovi2">parovi2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dominant" title="dominant">dominant</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/guessinggame" title="guessinggame">guessinggame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sabor" title="sabor">sabor</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pachinko" title="pachinko">pachinko</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cuttingstrings" title="cuttingstrings">cuttingstrings</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/grid" title="grid">grid</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/razbibriga" title="razbibriga">razbibriga</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/multitouch" title="multitouch">multitouch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cuttingpolygon" title="cuttingpolygon">cuttingpolygon</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/golombrulers" title="golombrulers">golombrulers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/passingsecrets" title="passingsecrets">passingsecrets</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/modelling" title="modelling">modelling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/courseplanning" title="courseplanning">courseplanning</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fridge" title="fridge">fridge</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/particlecollision" title="particlecollision">particlecollision</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/linije" title="linije">linije</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/colorwalk" title="colorwalk">colorwalk</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/fractalarea" title="fractalarea">fractalarea</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/oceancurrents" title="oceancurrents">oceancurrents</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/segmentintersection" title="segmentintersection">segmentintersection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/boom" title="boom">boom</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/floodit" title="floodit">floodit</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/multiplicationgame" title="multiplicationgame">multiplicationgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jusaccrescendi" title="jusaccrescendi">jusaccrescendi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/solarly" title="solarly">solarly</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/flipfive" title="flipfive">flipfive</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lumbercraft" title="lumbercraft">lumbercraft</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jurassicjungle" title="jurassicjungle">jurassicjungle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aladin" title="aladin">aladin</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/findpoly" title="findpoly">findpoly</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/letterwheels" title="letterwheels">letterwheels</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jumpingyoshi" title="jumpingyoshi">jumpingyoshi</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/3sideddice" title="3sideddice">3sideddice</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ferryloading4" title="ferryloading4">ferryloading4</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/keyboard" title="keyboard">keyboard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/joiningnetwork" title="joiningnetwork">joiningnetwork</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/winterroads" title="winterroads">winterroads</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/eatingout" title="eatingout">eatingout</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/juice" title="juice">juice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tower" title="tower">tower</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/amiga" title="amiga">amiga</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/downtime" title="downtime">downtime</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/joiningflows" title="joiningflows">joiningflows</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hexagon" title="hexagon">hexagon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tourdefrance2" title="tourdefrance2">tourdefrance2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/countingchocolate" title="countingchocolate">countingchocolate</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jobpostings" title="jobpostings">jobpostings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/camels" title="camels">camels</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/theendingoftheendpart1" title="theendingoftheendpart1">theendingoftheendpart1</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/capsules" title="capsules">capsules</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beanbag" title="beanbag">beanbag</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/getrichquickschemes" title="getrichquickschemes">getrichquickschemes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bookcase" title="bookcase">bookcase</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bridgesandtunnels" title="bridgesandtunnels">bridgesandtunnels</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/itcanbearranged" title="itcanbearranged">itcanbearranged</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gears" title="gears">gears</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sudokunique" title="sudokunique">sudokunique</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/arithmeticdecoding" title="arithmeticdecoding">arithmeticdecoding</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ironcoal" title="ironcoal">ironcoal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/forestevolution" title="forestevolution">forestevolution</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/subwaymap" title="subwaymap">subwaymap</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/allaboutthatbase" title="allaboutthatbase">allaboutthatbase</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/incaseofinvasion" title="incaseofinvasion">incaseofinvasion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/findingpolly" title="findingpolly">findingpolly</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/studentcounsel" title="studentcounsel">studentcounsel</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/zebrasocelots" title="zebrasocelots">zebrasocelots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/importspaghetti" title="importspaghetti">importspaghetti</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/factovisors" title="factovisors">factovisors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/snowninjas" title="snowninjas">snowninjas</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/newfiber" title="newfiber">newfiber</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/imagecompression" title="imagecompression">imagecompression</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/exitsinexcess" title="exitsinexcess">exitsinexcess</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/odometeranalysis" title="odometeranalysis">odometeranalysis</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/water" title="water">water</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hyacinth" title="hyacinth">hyacinth</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/evenland" title="evenland">evenland</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kitesurfing" title="kitesurfing">kitesurfing</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/trojke" title="trojke">trojke</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gcds" title="gcds">gcds</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/equinumerous" title="equinumerous">equinumerous</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jackjill" title="jackjill">jackjill</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/tgif" title="tgif">tgif</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/frogger" title="frogger">frogger</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/divisorgame" title="divisorgame">divisorgame</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/interception" title="interception">interception</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/textencryption" title="textencryption">textencryption</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fairwarning" title="fairwarning">fairwarning</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crackingthecode" title="crackingthecode">crackingthecode</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fancy" title="fancy">fancy</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/smallschedule" title="smallschedule">smallschedule</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/exactchange2" title="exactchange2">exactchange2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/commemorativerace" title="commemorativerace">commemorativerace</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/easyprobability" title="easyprobability">easyprobability</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/scrollingsign" title="scrollingsign">scrollingsign</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/erraticants" title="erraticants">erraticants</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/canthoexpressway" title="canthoexpressway">canthoexpressway</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/blacksmithtraining" title="blacksmithtraining">blacksmithtraining</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/rotatecut" title="rotatecut">rotatecut</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/divisors" title="divisors">divisors</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/blazingnewtrails" title="blazingnewtrails">blazingnewtrails</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bakterije" title="bakterije">bakterije</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/delivery" title="delivery">delivery</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/deadfraction" title="deadfraction">deadfraction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/biometrics" title="biometrics">biometrics</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gerrymander" title="gerrymander">gerrymander</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pathtracing" title="pathtracing">pathtracing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crane" title="crane">crane</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bicikli" title="bicikli">bicikli</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tagresan" title="tagresan">tagresan</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/speed" title="speed">speed</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cookieselection" title="cookieselection">cookieselection</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/avoidingairports" title="avoidingairports">avoidingairports</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tripletfreequeens" title="tripletfreequeens">tripletfreequeens</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/modulararithmetic" title="modulararithmetic">modulararithmetic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/conveyorbelts" title="conveyorbelts">conveyorbelts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/convex" title="convex">convex</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tangotango" title="tangotango">tangotango</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/keypad" title="keypad">keypad</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/colorland" title="colorland">colorland</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/almostunionfind" title="almostunionfind">almostunionfind</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sudoku" title="sudoku">sudoku</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/longswaps" title="longswaps">longswaps</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bestrational" title="bestrational">bestrational</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alea" title="alea">alea</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sneakattack" title="sneakattack">sneakattack</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/logo" title="logo">logo</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wordclouds" title="wordclouds">wordclouds</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/genetics2" title="genetics2">genetics2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ambush" title="ambush">ambush</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/monopoly" title="monopoly">monopoly</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wherehaveyoubin" title="wherehaveyoubin">wherehaveyoubin</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/jatten" title="jatten">jatten</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/costofliving" title="costofliving">costofliving</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jollyjumpers" title="jollyjumpers">jollyjumpers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/grass" title="grass">grass</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lampknappar" title="lampknappar">lampknappar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/condorcet" title="condorcet">condorcet</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/apples" title="apples">apples</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thekingofthenorth" title="thekingofthenorth">thekingofthenorth</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/trickandtreat" title="trickandtreat">trickandtreat</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/barktree" title="barktree">barktree</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/enlarginghashtables" title="enlarginghashtables">enlarginghashtables</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/targetpractice" title="targetpractice">targetpractice</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zuma" title="zuma">zuma</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/friends" title="friends">friends</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dobra" title="dobra">dobra</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stoichiometry" title="stoichiometry">stoichiometry</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/xyzzy" title="xyzzy">xyzzy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alchemy" title="alchemy">alchemy</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cuttingcorners" title="cuttingcorners">cuttingcorners</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sentryrobots" title="sentryrobots">sentryrobots</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/winterfestival" title="winterfestival">winterfestival</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/threedprinter" title="threedprinter">threedprinter</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cropeasy" title="cropeasy">cropeasy</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hnumbers" title="hnumbers">hnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/whatsinit" title="whatsinit">whatsinit</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mwvc" title="mwvc">mwvc</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/clockconstruction" title="clockconstruction">clockconstruction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rings" title="rings">rings</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/videopoker" title="videopoker">videopoker</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/widgettree" title="widgettree">widgettree</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/circular" title="circular">circular</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/orders" title="orders">orders</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/vacuum" title="vacuum">vacuum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tictactoe" title="tictactoe">tictactoe</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/cheeseifyouplease" title="cheeseifyouplease">cheeseifyouplease</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rainbowroads" title="rainbowroads">rainbowroads</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/unicycliccount" title="unicycliccount">unicycliccount</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/playlist" title="playlist">playlist</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/chatter" title="chatter">chatter</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/primalrepresentation" title="primalrepresentation">primalrepresentation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tickets" title="tickets">tickets</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/magicaldistances" title="magicaldistances">magicaldistances</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/caveexploration2" title="caveexploration2">caveexploration2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/presidentialelections" title="presidentialelections">presidentialelections</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/stol" title="stol">stol</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/finalexam" title="finalexam">finalexam</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/catalansquare" title="catalansquare">catalansquare</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/paintingafence" title="paintingafence">paintingafence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/carpet" title="carpet">carpet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/easyquery" title="easyquery">easyquery</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/candydivision" title="candydivision">candydivision</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/origami" title="origami">origami</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/squarerooms" title="squarerooms">squarerooms</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/downpayment" title="downpayment">downpayment</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bootstrappingnumber" title="bootstrappingnumber">bootstrappingnumber</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/muzicari" title="muzicari">muzicari</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/monkey" title="monkey">monkey</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/citytour" title="citytour">citytour</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/bigtruck" title="bigtruck">bigtruck</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mali" title="mali">mali</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/skiing" title="skiing">skiing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/skogsbrand" title="skogsbrand">skogsbrand</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/basicremains" title="basicremains">basicremains</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/low" title="low">low</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/prefixfreecode" title="prefixfreecode">prefixfreecode</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/appelspelet" title="appelspelet">appelspelet</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/alphabet" title="alphabet">alphabet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/littletoys" title="littletoys">littletoys</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pokegene" title="pokegene">pokegene</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/visitorstrain" title="visitorstrain">visitorstrain</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/zipline" title="zipline">zipline</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lcmpairsum" title="lcmpairsum">lcmpairsum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pixelated" title="pixelated">pixelated</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pipes" title="pipes">pipes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/zagrade" title="zagrade">zagrade</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kratki" title="kratki">kratki</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mushroommisery" title="mushroommisery">mushroommisery</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wine" title="wine">wine</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/wimbledon" title="wimbledon">wimbledon</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kolinje" title="kolinje">kolinje</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/medals" title="medals">medals</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maxexpression" title="maxexpression">maxexpression</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/units" title="units">units</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kitchencombinatorics" title="kitchencombinatorics">kitchencombinatorics</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/lifeguards" title="lifeguards">lifeguards</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/foodreviewhard" title="foodreviewhard">foodreviewhard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/torn2pieces" title="torn2pieces">torn2pieces</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/historicexhibition" title="historicexhibition">historicexhibition</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kletva" title="kletva">kletva</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/drivesafely" title="drivesafely">drivesafely</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/succession" title="succession">succession</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/han" title="han">han</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kallaxconstruction" title="kallaxconstruction">kallaxconstruction</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/callacab" title="callacab">callacab</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/researchproductivityindex" title="researchproductivityindex">researchproductivityindex</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/greatexpectations" title="greatexpectations">greatexpectations</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kaboom" title="kaboom">kaboom</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/busschedules" title="busschedules">busschedules</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/radir" title="radir">radir</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/game" title="game">game</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/initials" title="initials">initials</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/easyascab" title="easyascab">easyascab</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pseudoprime" title="pseudoprime">pseudoprime</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/froshweek" title="froshweek">froshweek</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hilbertsort" title="hilbertsort">hilbertsort</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/aroundthetrack" title="aroundthetrack">aroundthetrack</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/polish" title="polish">polish</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/explosion" title="explosion">explosion</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hidingchickens" title="hidingchickens">hidingchickens</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ahorseshoein" title="ahorseshoein">ahorseshoein</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/pivot" title="pivot">pivot</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/expectingrain" title="expectingrain">expectingrain</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/gasstationnumbers" title="gasstationnumbers">gasstationnumbers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/swapfrenzy" title="swapfrenzy">swapfrenzy</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/ovalwatch" title="ovalwatch">ovalwatch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/emptyingbaltic" title="emptyingbaltic">emptyingbaltic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/evenodd" title="evenodd">evenodd</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/ranklistsorting" title="ranklistsorting">ranklistsorting</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/loopytransit" title="loopytransit">loopytransit</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/elementarymath" title="elementarymath">elementarymath</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/deckrandomisation" title="deckrandomisation">deckrandomisation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/oop" title="oop">oop</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/knightsearch" title="knightsearch">knightsearch</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/efficientexchange" title="efficientexchange">efficientexchange</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/city" title="city">city</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/oldschooldays" title="oldschooldays">oldschooldays</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/jughard" title="jughard">jughard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dexsave" title="dexsave">dexsave</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/budget" title="budget">budget</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/kingdomofkittens" title="kingdomofkittens">kingdomofkittens</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/infiniteslides" title="infiniteslides">infiniteslides</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/crazedboar" title="crazedboar">crazedboar</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/bipartitebattle" title="bipartitebattle">bipartitebattle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/eggs" title="eggs">eggs</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/imagedecoding" title="imagedecoding">imagedecoding</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/countingcodes" title="countingcodes">countingcodes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/beetle" title="beetle">beetle</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/banjo" title="banjo">banjo</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/iks" title="iks">iks</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/countdown" title="countdown">countdown</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/basic" title="basic">basic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/atrivialpursuit" title="atrivialpursuit">atrivialpursuit</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/harddrive" title="harddrive">harddrive</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/coloring" title="coloring">coloring</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/barica" title="barica">barica</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/worm" title="worm">worm</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/telephones" title="telephones">telephones</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/circumsphere" title="circumsphere">circumsphere</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/alienmicrowave" title="alienmicrowave">alienmicrowave</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/fries" title="fries">fries</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/forests" title="forests">forests</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cd" title="cd">cd</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/airlinehub" title="airlinehub">airlinehub</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/magicalstring" title="magicalstring">magicalstring</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/orchard" title="orchard">orchard</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/camplunches" title="camplunches">camplunches</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/zgodan" title="zgodan">zgodan</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/funnygames" title="funnygames">funnygames</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/evilstraw" title="evilstraw">evilstraw</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/automatictrading" title="automatictrading">automatictrading</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wordequations" title="wordequations">wordequations</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/div2mul2mul3" title="div2mul2mul3">div2mul2mul3</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/europeantrip" title="europeantrip">europeantrip</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/arrayofdiscord" title="arrayofdiscord">arrayofdiscord</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/wedding" title="wedding">wedding</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/connectdots" title="connectdots">connectdots</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/draughts" title="draughts">draughts</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rationalsequence" title="rationalsequence">rationalsequence</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/variabelnamn" title="variabelnamn">variabelnamn</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/listgame2" title="listgame2">listgame2</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/dominoes2" title="dominoes2">dominoes2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/altruisticamphibians" title="altruisticamphibians">altruisticamphibians</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/toursdesalesforce" title="toursdesalesforce">toursdesalesforce</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/textprocessor" title="textprocessor">textprocessor</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/decisions" title="decisions">decisions</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/citations" title="citations">citations</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thesockpile" title="thesockpile">thesockpile</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/icefloes" title="icefloes">icefloes</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/stockbroker" title="stockbroker">stockbroker</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/driving" title="driving">driving</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/polarexpress" title="polarexpress">polarexpress</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/hiringfiring" title="hiringfiring">hiringfiring</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/crowdcontrol" title="crowdcontrol">crowdcontrol</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/twoknights" title="twoknights">twoknights</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/theendingoftheendpart2" title="theendingoftheendpart2">theendingoftheendpart2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/harvard" title="harvard">harvard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/chopwood" title="chopwood">chopwood</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tombraider" title="tombraider">tombraider</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/test2" title="test2">test2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/balancedcut" title="balancedcut">balancedcut</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/chewbacca" title="chewbacca">chewbacca</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/slikar2" title="slikar2">slikar2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/target" title="target">target</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/246greaaat" title="246greaaat">246greaaat</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/canvas" title="canvas">canvas</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rimstyrka" title="rimstyrka">rimstyrka</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/takeover" title="takeover">takeover</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mnist2class" title="mnist2class">mnist2class</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/buttonbashing" title="buttonbashing">buttonbashing</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rectilinear" title="rectilinear">rectilinear</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/swimmingballs" title="swimmingballs">swimmingballs</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/tsp" title="tsp">tsp</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/buslines" title="buslines">buslines</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/rainbowtrees" title="rainbowtrees">rainbowtrees</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/sumandproduct" title="sumandproduct">sumandproduct</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/husbygge" title="husbygge">husbygge</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/blockgame2" title="blockgame2">blockgame2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/pravokutni" title="pravokutni">pravokutni</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/scaffolding" title="scaffolding">scaffolding</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/dictionary" title="dictionary">dictionary</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/asciifigurerotation" title="asciifigurerotation">asciifigurerotation</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mosquitoes" title="mosquitoes">mosquitoes</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/savez" title="savez">savez</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/woodencrates" title="woodencrates">woodencrates</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/architecture" title="architecture">architecture</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/perfectpowers" title="perfectpowers">perfectpowers</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/restoran" title="restoran">restoran</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/towers" title="towers">towers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/paths" title="paths">paths</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/palindromicdna" title="palindromicdna">palindromicdna</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/simplification" title="simplification">simplification</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/thewireghost" title="thewireghost">thewireghost</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/raidteams" title="raidteams">raidteams</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/organising" title="organising">organising</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/patuljci2" title="patuljci2">patuljci2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/printerscheduling" title="printerscheduling">printerscheduling</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/clinic" title="clinic">clinic</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/contestscheduling" title="contestscheduling">contestscheduling</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/museum" title="museum">museum</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mravihard" title="mravihard">mravihard</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/basicprogramming2" title="basicprogramming2">basicprogramming2</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mincostmaxflow" title="mincostmaxflow">mincostmaxflow</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mravojed" title="mravojed">mravojed</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/cameramakers" title="cameramakers">cameramakers</a></td>
</tr>
<tr>
<td>🔰 <a href="https://open.kattis.com/problems/wheresmyinternet" title="wheresmyinternet">wheresmyinternet</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/maxcolinear" title="maxcolinear">maxcolinear</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/metal" title="metal">metal</a></td>
<td>🔰 <a href="https://open.kattis.com/problems/mnist10class" title="mnist10class">mnist10class</a></td>
</tr>
</tbody>
</table>
<blockquote>
<h3>AND NOW LAST BUT THE BEAST😈 problems waiting for you for a long time</h3>
<table>
<thead>
<tr>
<th style="text-align:center">&lt;/&gt;</th>
<th style="text-align:center">&lt;/&gt;</th>
<th style="text-align:center">Very Hard</th>
<th style="text-align:center">&lt;/&gt;</th>
<th style="text-align:center">&lt;/&gt;</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">&lt;........./.........&gt;</td>
<td style="text-align:center">&lt;........./.........&gt;</td>
<td style="text-align:center">🔰<a href="https://open.kattis.com/problems/satisfaction" title="satisfaction">satisfaction</a></td>
<td style="text-align:center">&lt;........./.........&gt;</td>
<td style="text-align:center">&lt;........./.........&gt;</td>
</tr>
<tr>
<td style="text-align:center">&lt;........./.........&gt;</td>
<td style="text-align:center">&lt;........./.........&gt;</td>
<td style="text-align:center">🔰<a href="https://open.kattis.com/problems/hopper" title="hopper">hopper</a></td>
<td style="text-align:center">&lt;........./.........&gt;</td>
<td style="text-align:center">&lt;........./.........&gt;</td>
</tr>
<tr>
<td style="text-align:center">&lt;........./.........&gt;</td>
<td style="text-align:center">&lt;........./.........&gt;</td>
<td style="text-align:center">🔰<a href="https://open.kattis.com/problems/magicalmysteryknigh" title="magicalmysteryknigh">magicalmysteryknigh</a></td>
<td style="text-align:center">&lt;........./.........&gt;</td>
<td style="text-align:center">&lt;........./.........&gt;</td>
</tr>
</tbody>
</table>
<br>
### CONTACT && SUPPORT && SUGGESTION
<br>
>### </>_For any support. Feel free to give any relevent suggestion to this noob
<br>
📧: Email me dummyforsunil@gmail.com
<br>
Made in IN. && Made for WORLD.
<br>
Copyright ©️ 2021 [sunil-shukla](contestarchive.github.io)
