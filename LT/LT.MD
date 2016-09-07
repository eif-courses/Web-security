##WEB SAUGUMAS

### Galutinio vertinimo formulė

Galutinis vertinimas = Savarankiška užduotis (40%) + Praktinės užduotys (30%) + Egzaminas (30%). </li>


### Savarankiška užduotis

___
- Semestro metu reikia sukurti saugią web aplikaciją, jos realizaciją galite rengti: PHP, JAVA, ASP ir t.t. Taip pat svetainėje turi būti numatytas duomenų validavimas, funkcionalumo plėtojimo galimybė (Nauji moduliai, pavyzdžiui: svetainės tema, kalba ir panašiai), apsaugota nuo išorinių vartotojų, dėl blogai suprogramuotos web aplikacijos galinčių peržiūrėti neleistiną turinį ar jį redaguoti. Taip pat apsaugota nuo MySQL injection, XSS ir kitų gerai žinomų isilaužimo technikų.

___

- Svetainėje turi būti prisijungimo puslapis (angl. login) ir atsijungimo nuo svetainės galimybė. Svetainės vidinius puslapius gali peržiūreti tik prisijungęs vartotojas. Taip pat turi būti bent 1 objektas su CRUD (Create, Read, Update, Delete) operacijomis. Duomenys saugomi duomenų bazėje MySQL ar kitoje jums žinomoje.

___

- Svetainėje turi būti prisijungimo puslapis (angl. login) ir atsijungimo nuo svetainės galimybė. Svetainės vidinius puslapius gali peržiūreti tik prisijungęs vartotojas. Taip pat turi būti bent 1 objektas su CRUD (Create, Read, Update, Delete) operacijomis. Duomenys saugomi duomenų bazėje MySQL ar kitoje jums žinomoje. Turi būti bent dviejų rolių (angl. role) vartotojai. Pavyzdžiui: Administratorius turintis visas teises trinti, pridėti, keisti duomenis ir Vartotojas, kuris gali sukurti, trinti, keisti tiktai savo įrašus.

____

- Praktinės užduotys bus atsiskaitomos praktinių užsiėmimų metu atsiskaitymas prasides nuo semestro pradžios iki paskutinės paskaitos, atsiskaičius WEB aplikaciją atsiųsti jos aprašą bei web aplikacijos "source code" el. paštu: m.gzegozevskis@eif.viko.lt galutinį variantą, tada teorinės paskaitos metu pristatyti savo atliktą užduotį. Atsiskaitymo metu reikės atsakyti į klausimus, bei atlikti minimalius aplikacijos pakeitimus.
- Web aplikacijos užduoties aprašas (~15 lapų). 
- Pristatymas savo sukurtosios web aplikacijos (trukmė apie 10 min.). 
___

### Praktinės užduotys

___
**1 užduotis**. Sugalvoti projektuojamos svetainės pavadinimą, bei paskirtį. 
a) Susikonfigūruoti lokalų serverį skirtą svetainei talpinti. Jeigu planuojate naudoti programinį paketą WAMP, LAMP, MAMP st XAMPP, jei jis nėra įdiegtas jūsų kompiuteryje tai parsisiųsti iš žemiau pateikto programinės įrangos sąrašo. Paleisti įdiegtą programinį paketą ir patikrinti naršyklėje įvedūs "localhost" arba "http://127.0.0.1" ar programinis paketas veikia. 
b) Parsisiųsti jeigu jūsų kompiuteryje nėra įdiegta OWASP ZAP skirtą simuliuoti internetinių svetainių žinomiausių atakų rūšims. 
c) Įsidiegūs owasp zap išbandyti šią programą "Quick start" skirtuke, yra laukelis "URL to attack:" jame nurodyti planuojamos atakuoti svetainės url adresas pvz.: http://localhost, www.google.lt, www.seb.lt ar betkokios kitos svetainės. Atlikus skenavimą pažiūrėti skiltyje "Alerts" kokie pranešimai (pavojai) yra pateikti. Taip pat programa pateikia išsamią informaciją kaip reikėtų juos pašalinti. Aukšto ir vidutinio lygmens (High & medium priority) pavojai reiškia jog jūsų svetainė nėra gerai apsaugota. Taigi atsiskaitant jūsų naujai, kuriamą svetainę bus pageidautinta jog nebūtų aukšto ir vidutinio lygmens pajovų. 
d) Pavykūs rasti pažeidžiamą svetainę su aukšto lygmens pavojumi, bus skiriami bonus 1 balas.
___

**2 užduotis**. Realizuoti “Brute force” algoritmą, kuris nuskaitytų simbolių seką (abėcelę) A = (‘a’, ’b’, ’c’, ’d’, ’:’,’^’, ‘<’) ir išvestų į ekraną ar tekstinį dokumentą visų galimų variantų derinius (žodžius). Abėcėlės ilgis 4 - 5 simboliai, sudaromų žodžių ilgis minimum 4 simboliai. Pavyzdžiui: a, b, c, ab, ac, ba, bc, ca, cb, abc, acb, bac, bca, cab, cba ir t.t.
___
**3 užduotis**. XSS (Cross Site Scripting). Pasinaudoti praeitos užduoties pažeidžiama WEB aplikacija (Jeigu norite šią aplikaciją galite naudoti lokaliai, jos source code galite parsisiųsti iš: http://www.dvwa.co.uk/). Jeigu vis dėl to naudosite šią aplikaciją http://www.dvwa.co.uk/ lokaliai, tada pasirinkę “XSS stored” nuorodą, pažeidžiamame įvesties laukelyje (Message) galėsite aprašyti XSS scenarijų, kurio įvesties simbolių limitas yra 50, testavimo tikslams šį limitą galite šiek tiek pasididinti (www\dwa\vulnerabilities\xss_s\index.php). Be abejo kaikurios svetainės keisti įvedamų simbolių kiekio neleis, tai turėkite omenyje, kad turite sutilpti į rėmus, kokie jie yra nurodyti. Sukurti scenarijų (angl. Script), kuriuo pasinaudojus išgauti kiek įmanoma daugiau duomenų iš vartotojų besilankančių šioje svečių knygoje, arba iššaukti reklaminio pobūdžio klipą, garsą, tekstinį pranešimą, ar nukreipti į identiškai atrodančią (klonuota) WEB aplikaciją, kurioje vartotojui reikia pakartotinai įvesti duomenis, kuriuos jūs išsaugote savo serverio duomenų saugykloje (pvz. Tekstinis failas). Jūsų kuriamas scenarijus, jūsų asmeninis reikalas ką jis atliks ir kaip, svarbu, kad būtų prasmingas.
___
**4 užduotis**. CAPTCHA (angl. Completely Automated Public Turing test to tell Computers and Humans Apart) – testas, naudojamas kompiuteriuose ir skirtas nustatyti ar naudotojas yra žmogus, ar ne. Užduoties tikslas sugalvoti CAPTCHA algoritmą, pageidautina jog būtų, net tik skaičių ir raidžių generatorius, kurį nesunkiai nepageidauntini asmenys galėtų nuskaityti. Pavyzdžiui galėtų būti veiksmai su skaičiais, klausimai, paveikslėliai ir pnš. Užduočiai atlikti naudoti bet kokią programavimo kalbą, svarbu rezultatas.
___
**5 užduotis**. Įdiegti SSL (Secure Socket Layer) / TLS (Transport Layer Security) protokolą jūsų web serveryje. Sukurti SSL sertifikatą, CA (Certificate Authority) arba atsisiųsti nemokamą sertifikatą iš:http://CAcert.org. Plačiau pasiskaityti apie SSL/TLS protokolo įdiegimą APACHE web serveryje galite:http://httpd.apache.org/docs/2.4/ssl/ssl_faq.html. Sėkmingai įdiegūs SSL, ir įvedūs tam tikrą adresą pvz: https://127.0.0.1/httpsPage/index.php, adresų juostoje turi būti pavaizduota žalia užrakinta spyna nusakanti jog bus naudojamas saugus protokolas duomenų apsikeitimui su serveriu.
___
**6 užduotis**. Pasinaudoti programa/biblioteka WGET, kurią galimą pasileisti, bet kurioje operacinėje sistemoje: Išsiaiškinti kokias funkcijas gali atlikti ši programa, ir kokius veiksmus galėtumėte atlikti siekiant išgauti informacijos iš web aplikacijų/interneto svetainių. Nukopijuoti WEB svetainės/WEB aplikacijos turinį, pavyzdžiui savo kuriamos web aplikacijos ir jeigu yra galimybė nukopijuoti svetainės turinį paveikslėliai, puslapiai ir t.t. tada, kokį būdą galėtumėte pritaikyti siekiant užkirsti kelią svetainės turinio kopijavimui trumpai aprašyti veiksmų seką.
___
**7 užduotis**. Sukurti funkciją, modulį ar programą skirtą apsaugoti nuo „SQL injection“, kuri tikrintų įvesties laukelyje įvestą simbolių eilutę ir ignoruotų visus reikšminius simbolius, kurie vienaip ar kitaip gali pakenkti SQL užklausai pakeisdami logiką ar sukeldami dirbtines klaidas: SQL specifinius, bei kitus nepageidautinus simbolius. Kaip pavyzdys programai skirtai filtruoti duomenis, būtų sintaksinis analizatorius (angl. Parser).
___
**8 užduotis**. Sukurti naują metodą arba pritaikyti jau esamą, skirtą apsaugoti jūsų tinklalapį nuo atvaizdavimo kituose tinklalapiuose. Taip pat turėtų būti galimybė atvaizduoti jūsų tinklalapį kituose tinklalapiuose. Pavyzdžiui: www.google.lt svetainėje leidžiame atvaizduoti jūsų tinklalapį, o www.facebook.com neleidžiame atvaizduoti.
___
**9 užduotis**. Sukurti paprastą http serverį į kurį būtų galima kreiptis iš naršyklės arba iš klientinės programos. Serverio ir kliento „bendravimas“ gali būti realizuojamas naudojantis SOCKET ar kitomis bibliotekomis. Taip pat turi būti galima siųsti komandas ir jas apdoroti. Pavyzdžiui vietoje standartinio GET – naudoti lietuvišką žodi GAUTI arba PUBLIKUOTI.

___
### Egzaminas
- Testas iš top 10 OWASP (Open Web Application Security Project) web aplikacijų pažeidžiamumo technikų.

### Programinė įranga
- A Windows Web development environment for Apache, MySQL, PHP databases (WAMP server). (https://sourceforge.net/projects/wampserver/files/latest/download).
- Damn Vulnerable Web Application - (http://www.dvwa.co.uk/).
- OWASP Zed Attack Proxy Project - (https://github.com/zaproxy/zaproxy/wiki/Downloads).
- WGET - (http://gnuwin32.sourceforge.net/packages/wget.htm).

### Paskaitų medžiaga
- Web saugumas LT - (https://github.com/fontpoint/Security/tree/master/LT).
- Web application security EN - (https://github.com/fontpoint/Security/tree/master/EN).

### Literatūros sąrašas

- Best place for beginners learn php, xml, html, JS, SQL - (http://www.w3schools.com/php/default.asp).  
- The Web Application Hacker's Handbook: Finding and Exploiting Security Flaws 2nd Edition by Dafydd Stuttard, Marcus ISBN-13: 860-1404288999
- Official PHP manual - (http://php.net/manual/en/).
- Open Web Application Security Project - (https://www.owasp.org/index.php/Main_Page).
