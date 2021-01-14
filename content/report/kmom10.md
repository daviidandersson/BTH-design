---
Title: Kmom01
Description: Part 10
Template: kmom
---

<div class="sidebar">
    <h2><a href="kmom01">Kmom01</a></h2>
    <h2><a href="kmom02">Kmom02</a></h2>
    <h2><a href="kmom03">Kmom03</a></h2>
    <h2><a href="kmom04">Kmom04</a></h2>
    <h2><a href="kmom05">Kmom05</a></h2>
    <h2><a href="kmom06">Kmom06</a></h2>
    <h2><a href="kmom10">Projekt</a></h2>
</div>

<div class="report">
    <h1>Rapporten för Kmom10/projektet</h1>

    <h2>Krav1 Webbplats</h2>

    <p>Jag började med att börja ifrån grunden med en helt ny installation från example/portfolio. Jag valde att göra så för att ville repetera det som har fått lära sig under kursens gång. Om jag hade valt det andra så hade jag ju bara kopierat och tagit bort det som jag inte ville ha. Det skulle inte gynnas i framtiden enligt mig. Jag tyckte att det var bättre att får repetition än att bara kopiera allt. Innehållet är rätt enkelt. Jag uppdaterar package.json för ett nytt tema och justerar twig-filen för att använda -min versionen av css-filen. Jag skapar mappar för om och highlight där deras .md mallar finns. I om mappen finns även en fil om webbplatsen. Jag kontrollerar att alla sidor laddar rätt innehåll och att länkar funkar.</p>

    <h2>Krav2 Tema</h2>

    <p>Det jag gjorde först var att leta efter bilder som skulle passa till webbplatsen. Jag placerar relevanta bilder för varje sida i meta-informationen och hämtar de i twig när det behövs. Jag jobbade mest med twigfiler. Jag gjorde en för varje sidan så en för om, en för highlight och en för om webbplasten som inte skulle synas i navbaren. Jag skrev nästan all text i twigfilerna också. Det var bara i om webbplatsen som jag skrev i meta-informationen. Det gjorde jag för det kändes lättare att skriva där då det skulle vara mycket text. Bilderna använde jag mig utav Cimage för att få till rätt storlek till respektive sida. Jag hade en scssfil för varje sida för att det skulle vara enkelt att hitta kodningen till just den sidan. Jag skapade många olika variabler i en scssfil för att hålla reda på vilka färger och typsnitt som jag använde. Det var lättare att göra så för att får det mer strukturerad. Grid används på hela sidan för att skapa layout för olika element. Det ger bra struktur som är lätt att använda och uppdatera. Jag använde till exempel två kolumner på om sidan eftersom jag ville bara har lite text och en bild på kunden. Medans på highlight så har jag tre kolumner för att jag valde tre händelser som jag ville lyfta fram. </p>

    <p>Färgen på sidan används för att ge en teater/film känsla med god kontrast till den. Jag valde en stark färgpalett eftersom det röda ser ut som en bioduk eller en röd ridå där film visas genom att de gråa är mindre än det svarta som gör att man ska fokusera på det som finns inuti den gråa färgen. Det kan också vara en teaterscen som har en rödduk och det gråa representera ljuset som finns runt om kring scener för att vissa vad som händer och vad är viktigt.</p>

    <p>Jag valde att gå på en av dem vanligaste typograffier som är Roboto och Open Sans. Jag ville att besökarna skulle tycka det var lättläst att det inte var för jobbigt att läsa. Roboto har använts för att göra texten strukturerad och lättläst. Det ger sidan en mer professionell känsla. Dock så valde jag en annan typografi för hennes namn i headern eftersom hennes namn är hennes varumärke. Jag ville att hennes namn skulle sticka ut jämfört med texterna.</p>

    <h2>Krav3 Responsivitet och tillgänglighet</h2>

    <p>Jag skapar separat scss fil för responsivitet och lägger till den på slutet
    av min style.scss och i style-second.scss eftersom jag har två teman. I
    devtools hoppar jag mellan olika mobilskärmstorlekar för att kolla att mina justeringar funkar för mobilenheter också. Till exempel hur mitt grid funkar på mobilenheter. Jag gör att alla grids bli till en kolumn för mobila enheter. På lite större skärm som på en Ipad till exempel använder jag två kolumner på highlight till exempel. Jag använder auto på background-storleken för att bakgrundsbilden ska passa bättre på mobila enheter.</p>

    <p>I lighthouse kollar jag tillgängligheten så att den ligger på 100. Jag fick ändra textfärgen på vissa ställen för den varnarde om att kontrasten var för liten. Det var i till exempel i dem gråa boxarna i huvudtemat där hade jag vit färg på texten men fick ändra till svart.</p>

    <h2>Krav4 Alternativt tema</h2>

    <p>Mitt alternativa temat är ett helt annat tema än det första. Det andra temat är mycket ljusare och färggladare. Jag valde dem här färgerna eftersom teater kopplas till kreativitet och det brukar kopplas till färger och former. Pastell får man en känsla av lekfull och det väcker nyfikenhet hos besökarna. Jag gjorde typ allt likadant som på första temat med twigfilerna och så vidare. Det jag ändrade var färgpaletten, typografin och lite av designelement. Jag valde att endast göra detta för att inte ändra för mycket. Det skall inte kännas som att man byter webbsida helt och hållet i mitt tycke. Jag ändrade typsnitten men ville fortfarande att det skulle vara enkelt att läsa så valde två sans-serf typsnitt. Jag valde det eftersom dem flesta webbsidor använder sig sans-serif och det är behagligt att titta på i mitt tycke. Det ser också professionellt ut med sans-serif. Jag använde dock samma typsnitt till hennes namn då jag ville att namnet skulle läggas på minnet för besökarna. Eftersom hennes namn är hennes varumärke.</p>

    <h2>Om projektet</h2>

    <p>Projektet i sig var kul att genomföra. Det absolut svåraste var att komma igång och komma på hur jag skulle strukturera upp det hela. Men tillslut så började det flyta på så då gick det bättre. Det tog långt tid att göra så det kändes skönt att har en lång period för det. Jag tyckte projektet var både svårt och lätt i sin helhet. Jag tycker att det var ett roligt och lärorikt projekt som jag tycker är rimligt för denna kurs.<p>

    <h2>Om kursen<h2>
    <p>Alla kursmoment har varit himla kul att göra. Jag anser att Pico är ett bra grund för att fokusera på css och design. Jag känner att min kompetens inom design och designprinciper har utökats enormt tack vare denna kursen. Jag tycker att Niklas och Emil har varit jättebra lärare och deras föreläsningar har varit himla bra. Har ingen exakt feedback bara att Niklas, Emil och dem som rättat har gjort det bra. Jag skulle nog kunna rekommendera den här kursen till någon som är nybörjare i webbdesign. Jag är nöjd med kursen och kommer ge kursen betyget 9 av 10.</p>

    <div class="next-previous">
        <a href="kmom06" aria-label="kmom06"><i class="fas fa-chevron-left"></i></a>
        <br>
        <a href="kmom01" aria-label="kmom01"><i class="fas fa-chevron-right"></i></a>
    </div>
</div>
