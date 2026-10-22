# DOM-skriptaus
To do-lista ennen koulua
Tekijä(t): Lisette Täks ja Anniina 
Projektisuunnitelma
Projektin idea
Sovelluksen pääidea on ”to do-lista”, mikä auttaa tekemään asiat ennen kouluun menemistä. Eli sovellus on tarkoitettu koululaisille, ketkä tarvitsevat muistinlistan tehtävilleen.

Suunnitellut toiminnot
Listaa vähintään kolme sovellukseesi suunniteltua toimintoa:
•	Toiminto 1: ”Kirjoita tehtävä…” toiminto, mikä lisää tehtävän listalle. (hakupalkki)
•	Toiminto 2: Tehtävälistan jaottelu eli toiminnot: Kaikki, kesken ja tehdyt. Näät halutessasi kolme erilaista listaa annetuista tehtävistä.
•	Toiminto 3:  ”Vain 1 tehtävä jäljellä!”, eli kertoo kuinka monta tehtävää on vielä tekemättä. Rautalankamalli on englanniksi (Only 1 task left)

 Rautalankamalli / luonnos

 KUVA
 (images/rautalankamalli.png)
 
Verkkolinkit
•	Julkaistu sovellus: https://takslisette.github.io/DOM-skriptaus/
•	GitHub-repositorio: https://github.com/takslisette/DOM-skriptaus.git 
•	Projektin videoesittely: https://youtu.be/3cdy2EX_cmM

Tietoja sovelluksesta
To do-lista ennen koulua on verkkosovellus, joka auttaa tekemään asiat ennen kouluun menemistä. Eli sovellus on tarkoitettu koululaisille, ketkä tarvitsevat muistilistan tehtävilleen. Sovelluksessa pystyt kirjaamaan niin monta haluamaasi tehtävää, ja pystyt näkemään joko ”kaikki” tehtävät tai halutessasi vain ”Kesken” olevat tehtävät tai ”Tehdyt”. Sovellus tallentaa aina (Localstorage) jättämäsi tehtävät/muutokset, joten voit käyttää listaa aina uudelleen. 

Kuvaile lyhyesti sovelluksen tarkoitus ja tärkeimmät toiminnot.
Teknologiat
Kuvaile, mitä teknologioita käytit ja mikä niiden rooli oli projektissasi.

•	HTML – sivun rakenne: Käytin HTML:ää verkkosivun rakenteen luomiseen. Sen avulla rakensin tehtävälistan, tekstikentän, lisäyspainikkeen, tehtävälistan sekä suodatus- ja poistopainikkeet.

•	CSS – ulkoasu ja asettelu: Käytin CSS:ää sivun ulkoasun ja asettelun suunnitteluun. Sen avulla toteutin sovelluksen värit, taustakuvan, painikkeiden tyylit, tehtävien ulkoasun ja responsiivisuuden eri kokoisilla näytöillä (Anniina Pitkänen)

•	JavaScript – toiminnallisuus, DOM-skriptaus ja lomakkeiden validointi: Käytin JavaScriptiä sovelluksen toiminnallisuuden toteuttamiseen. Sen avulla käyttäjä voi lisätä uusia tehtäviä, merkitä tehtäviä tehdyiksi, poistaa tehtäviä ja suodattaa tehtävälistaa. JavaScript käsittelee myös lomakkeen validoinnin, näyttää virheilmoitukset ja päivittää sivun sisältöä DOM-skriptaamisen avulla.

•	localStorage – tietojen tallentaminen selaimeen, jos käytit sitä: Käytin localStoragea tehtävien tallentamiseen selaimen paikalliseen tallennustilaan. Näin lisätyt tehtävät ja niiden valmiustila säilyvät, vaikka sivu päivitetään tai selain suljetaan ja avataan uudelleen.



Sovelluksen käyttö
Kirjoita lyhyet käyttöohjeet sovellukselle.

Sovelluksen käyttö
1.	Avaa julkaistu sovellus GitHub Pages -linkistä.
2.	Kirjoita tehtävä tekstikenttään ja paina Lisää tehtävä -painiketta.
3.	Merkitse tehtävä tehdyksi valintaruudusta tai poista se rastipainikkeella (×).
4.	Suodata tehtäviä valitsemalla Kaikki, Kesken tai Tehdyt.
5.	Voit poistaa kaikki valmiit tehtävät painamalla Poista tehdyt -painiketta.
6.	Päivitä sivu ja tarkista, että tehtävät ja niiden tila säilyvät selaimessa.

Sovelluksen käynnistäminen paikallisesti
1.	Kloonaa repositorio GitHubista tai lataa se omalle koneellesi ZIP-tiedostona.
2.	Avaa ladattu projektikansio.
3.	Varmista, että index.html, CSS-tiedosto, JavaScript-tiedosto ja images-kansio ovat oikeissa paikoissa.
4.	Avaa index.html selaimessa. Voit myös käyttää Visual Studio Coden Live Server -laajennusta.
5.	Käytä sovellusta selaimessa. Tehtävät tallennetaan selaimen paikalliseen tallennustilaan.

 Kuvakaappaukset

(images/Nettisivu.png)


Tunnetut virheet / puutteet
 Ei tunnettuja virheitä.
Työn jakautuminen
•	Anniina Pitkänen: Tein rautalankamallin moqups nettisivulla ja keskityin sovelluksen visuaalisuuteen, tein styles.css koodin ja valitsin kuvan nettisivulle.
•	Lisette Täks: Teki sivun index.html tiedoston, sekä script.js tiedoston.
•	Yhdessä ideoimme ja suunnittelimme sovelluksen ja kävimme koodit läpi ennen palautusta, sekä täydensimme toistemme koodeja.

Oma arvio ja oppimisen reflektointi
Pohdi työtäsi ja oppimisprosessiasi.
•	Onnistuin tekemään HTML-rakenteen ja JavaScriptin toiminnallisuudet TODO-sovellukseen. Sain toteutettua tehtävien lisäämisen, poistamisen, valmiiksi merkitsemisen ja suodattamisen. Opin myös hyödyntämään localStoragea, jotta tehtävät säilyvät selaimessa. Teimme projektin parityönä Anniinan kanssa, joka vastasi CSS-tiedostosta. Yhteistyömme avulla saimme sovelluksen rakenteen, toiminnallisuuden ja ulkoasun yhdistettyä kokonaisuudeksi.
•	Haastavinta oli JavaScriptin toiminnallisuuden toteuttaminen ja DOM-skriptauksen ymmärtäminen. Myös HTML ja JavaScriptin yhdistäminen niin, että kaikki painikkeet ja toiminnot toimivat oikein, vaati testaamista ja ongelmien ratkaisemista. Haastavaa oli myös tehdä koodia yhdessä, koska ne olivat toisistaan riippuvaisia. 
•	Jos aikaa olisi enemmän, testaisin sovellusta vielä tarkemmin eri tilanteissa ja parantaisin sen käytettävyyttä. Voisin myös lisätä uusia ominaisuuksia, kuten tehtävien määräpäivät tai tärkeysjärjestyksen.
•	Opin, että HTMLä luodaan verkkosivun rakenne, CSSä määritellään ulkoasu ja JavaScriptillä toteutetaan toiminnallisuus. Opin käyttämään DOM-skriptausta HTML-elementtien muokkaamiseen ja käyttäjän toimintoihin reagoimiseen. Lisäksi opin, miten localStoragea voidaan käyttää tietojen tallentamiseen selaimessa. Parityöskentely opetti myös tehtävien jakamista ja eri tiedostojen yhdistämistä toimivaksi sovellukseksi. Tämä oli kiinnostavaa oppia localstoragen käyttöä, kun html, css ja javascriptin on ollu osittain tuttua aiemmilta kursseilta. 
•	Haluaisin oppia lisää visuaalisen ulkoasun tekemisestä ja kokeilla erilaisia ratkaisuja(Eli myös javascriptin)
•	Oma arvio projektista: 8/10 pistettä
Lähteet ja kiitokset
Listaa kaikki projektissa käyttämäsi lähteet, tutoriaalit, kuvat ja koodiesimerkit.
Jos käytit ChatGPT:tä, GitHub Copilotia tai muuta tekoälytyökalua, mainitse se tässä ja kerro lyhyesti, miten se tuki työskentelyäsi.

•	https://www.w3schools.com/html/default.asp 
o	W3Schools: HTML Tutorial – tutustuin HTML-elementteihin ja verkkosivun rakenteen muodostamiseen.
o	W3Schools: HTML Forms – tutustuin lomakkeisiin ja tekstikenttiin.
o	W3Schools: HTML Lists – tutustuin listojen ja listan kohtien käyttöön.
o	W3Schools: HTML Form Elements – tutustuin painikkeisiin ja muihin lomake-elementteihin.
•	Otin hieman myös mallia aiemmista W01-05 workshopeista: Mm. indexin body ja head rakenteita.
•	https://www.needpix.com/photo/download/177598/green-blackboard-chalk-eraser-learn-school-free-vector-graphics-free-pictures-free-photos 
•	Käytetty tekoälytyökalu: ChatGTP
o	Miten työkalua käytettiin: Käytin ChatGPTä apuna HTML- ja JavaScript-koodin kokonaiskuvassa. Sen avulla selvitin DOM-skriptausta ja lomakkeiden validointia sekä pyysin ideoita kaikki, tehdyt ja kesken elementtien sijoitteluun sivulla.  Käytin myös koodin virheiden lukuun.

 Lisenssi
Tämä projekti on lisensoitu MIT-lisenssillä.
