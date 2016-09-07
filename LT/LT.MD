#WEB SAUGUMAS

### Galutinio vertinimo formulė

Galutinis vertinimas = Savarankiška užduotis (40%) + Praktinės užduotys (30%) + Egzaminas (30%). </li>


### Savarankiška uždtuotis
Main goals:
- Create secure Web application using any programming language you are already known e.g. PHP, JAVA, ASP ect.
- Web application should have functionallity against top 10 most common web security vulnerabilities. (https://www.toptal.com/security/10-most-common-web-security-vulnerabilities). 
- Create login page all data should save to database e.g. MySQL. Also you should implement one web page with basic CRUD (Create, Read, Update, Delete) operations.   
- Create roles for users e.g. Administrator - have full control access, Basic user - have less access to web page functionalitty, Guest - only can see home page.    

### Praktinės užduotys
___
### 1 Task (10 points)
___
- Software already installed in computer classrooms if you using personal computers you can download from software section. 
- Using OWASP Zed Attack Proxy Project (ZAP tool) try to find vulnerable website in "URL to Attack" field enter URL address and press start scan. In alerts tab you see all risks which is marked as warnings, medium and high priority risks. If you find web page with high priority risks first lecture you get bonus **10 points** to your final evaluation. 
- Run A Windows Web development environment for Apache, MySQL, PHP databases and try to launch http://localhost:8888 if it working try to find www/ directory and add new webpage named myFirstPage.php, open that file and add simple code line <?php echo 'hello world!!!' ?> if everythis is fine and browser open your web page with text hello world !!! then you are ready to do next tasks.   

___
### 2 Task (10 points)
___
- Configure Damn Vulnerable Web Application - (http://www.dvwa.co.uk/) and run in localhost using WAMP server. When you run it you need to configure security levels and change it to low, then find link XSS stored and try to create script which let you pop up window with text **hello world**.
- Later create script which redirect you to your page hack.php and display fake page with same design look login form like in DVWA program and store username and password information to your data source e.g. database or textfile. Also try to implement different script where you can display ads or run audio files. 

___
### 3 Task (10 points)
___

- CAPTCHA (Completely Automated Public Turing
test to tell Computers and Humans Apart) – A CAPTCHA is a program that protects websites against bots by generating and grading tests that humans can pass but current computer programs cannot.
- Create your own unique CAPTCHA test which should have those components: picture, text, digit, quiz ect.   

___
### 4 Task (10 points)
___

- Download WGET tool (http://gnuwin32.sourceforge.net/packages/wget.htm) and first read help or documentation.
- Using Windows operating system run command prompt add your wget tool bin directory path using command e.g. **cd "C:\Program Files (x86)\GnuWin32\bin"**.  
- Run wget tool on command prompt call **wget.exe --help** read instructions and try to do some tasks. 
- Download any webpage source code using WGET tool. Finally write to text document summary what you learn to do using this tool.  

___
### 5 Task (10 points)
___

- Create **myFunction.php** then create own unique function which secure against XSS attacks (do not use default libraries functions e.g. htmlentities()). 
- You should think how to ignore special characters in input fields, also you should implement data validation function.
- When you prepeare to show your created unique function you should have some prepeared testing data for your myFunction.php input fields.

___
### Egzaminas
- Quiz from top 10 OWASP (Open Web Application Security Project) vulnerabilities.

### SOFTWARE
- A Windows Web development environment for Apache, MySQL, PHP databases (WAMP server). (https://sourceforge.net/projects/wampserver/files/latest/download).
- Damn Vulnerable Web Application - (http://www.dvwa.co.uk/).
- OWASP Zed Attack Proxy Project - (https://github.com/zaproxy/zaproxy/wiki/Downloads).
- WGET - (http://gnuwin32.sourceforge.net/packages/wget.htm).

### LECTURE NOTES
- Web application security - (https://github.com/fontpoint/Security/tree/master/EN).

### LITERATURE

- Best place for beginners learn php, xml, html, JS, SQL - (http://www.w3schools.com/php/default.asp).  
- The Web Application Hacker's Handbook: Finding and Exploiting Security Flaws 2nd Edition by Dafydd Stuttard, Marcus ISBN-13: 860-1404288999
- Official PHP manual - (http://php.net/manual/en/).
- Open Web Application Security Project - (https://www.owasp.org/index.php/Main_Page).


**1 užduotis**. Sugalvoti projektuojamos svetainės pavadinimą, bei paskirtį. a) Susikonfigūruoti lokalų serverį skirtą svetainei talpinti. Jeigu planuojate naudoti programinį paketą WAMP, LAMP, MAMP st XAMPP, jei jis nėra įdiegtas jūsų kompiuteryje tai parsisiųsti iš žemiau pateikto sąrašo. Paleisti įdiegtą programinį paketą ir patikrinti naršyklėje įvedūs "localhost" arba "http://127.0.0.1" ar programinis paketas veikia. 
b) Parsisiųsti jeigu jūsų kompiuteryje nėra įdiegta OWASP ZAP skirtą simuliuoti internetinių svetainių žinomiausių atakų rūšims. 
c) Įsidiegūs owasp zap išbandyti šią programą "Quick start" skirtuke, yra laukelis "URL to attack:" jame nurodyti planuojamos atakuoti svetainės url adresas pvz.: http://localhost, www.google.lt, www.seb.lt ar betkokios kitos svetainės. Atlikus skenavimą pažiūrėti skiltyje "Alerts" kokie pranešimai (pavojai) yra pateikti. Taip pat programa pateikia išsamią informaciją kaip reikėtų juos pašalinti. Aukšto ir vidutinio lygmens (High & medium priority) pavojai reiškia jog jūsų svetainė nėra gerai apsaugota. Taigi atsiskaitant jūsų naujai, kuriamą svetainę bus pageidautinta jog nebūtų aukšto ir vidutinio lygmens pajovų. 
d) Pavykūs rasti pažeidžiamą svetainę su aukšto lygmens pavojumi, bus skiriami bonus 0.5 balo.

**2 užduotis**. Realizuoti “Brute force” algoritmą, kuris nuskaitytų simbolių seką (abėcelę) A = (‘a’, ’b’, ’c’, ’d’, ’:’,’^’, ‘<’) ir išvestų į ekraną ar tekstinį dokumentą visų galimų variantų derinius (žodžius). Abėcėlės ilgis 4 - 5 simboliai, sudaromų žodžių ilgis minimum 4 simboliai. Pavyzdžiui: a, b, c, ab, ac, ba, bc, ca, cb, abc, acb, bac, bca, cab, cba ir t.t.

**3 užduotis**. XSS (Cross Site Scripting). Pasinaudoti praeitos užduoties pažeidžiama WEB aplikacija (Jeigu norite šią aplikaciją galite naudoti lokaliai, jos source code galite parsisiųsti iš: http://www.dvwa.co.uk/). Jeigu vis dėl to naudosite šią aplikaciją http://www.dvwa.co.uk/ lokaliai, tada pasirinkę “XSS stored” nuorodą, pažeidžiamame įvesties laukelyje (Message) galėsite aprašyti XSS scenarijų, kurio įvesties simbolių limitas yra 50, testavimo tikslams šį limitą galite šiek tiek pasididinti (www\dwa\vulnerabilities\xss_s\index.php). Be abejo kaikurios svetainės keisti įvedamų simbolių kiekio neleis, tai turėkite omenyje, kad turite sutilpti į rėmus, kokie jie yra nurodyti. Sukurti scenarijų (angl. Script), kuriuo pasinaudojus išgauti kiek įmanoma daugiau duomenų iš vartotojų besilankančių šioje svečių knygoje, arba iššaukti reklaminio pobūdžio klipą, garsą, tekstinį pranešimą, ar nukreipti į identiškai atrodančią (klonuota) WEB aplikaciją, kurioje vartotojui reikia pakartotinai įvesti duomenis, kuriuos jūs išsaugote savo serverio duomenų saugykloje (pvz. Tekstinis failas.). XSS Pavyzdys:. "iframe src="http://www.mailbase.lt/ad/sc.html">". Jūsų kuriamas scenarijus, jūsų asmeninis reikalas ką jis atliks ir kaip, svarbu, kad būtų prasmingas.

**4 užduotis**. CAPTCHA (angl. Completely Automated Public Turing test to tell Computers and Humans Apart) – testas, naudojamas kompiuteriuose ir skirtas nustatyti ar naudotojas yra žmogus, ar ne. Užduoties tikslas sugalvoti CAPTCHA algoritmą, pageidautina jog būtų, net tik skaičių ir raidžių generatorius, kurį nesunkiai nepageidauntini asmenys galėtų nuskaityti. Pavyzdžiui galėtų būti veiksmai su skaičiais, klausimai, paveikslėliai ir pnš. Užduočiai atlikti naudoti bet kokią programavimo kalbą, svarbu rezultatas.

**5 užduotis**. Įdiegti SSL (Secure Socket Layer) / TLS (Transport Layer Security) protokolą jūsų web serveryje. Sukurti SSL sertifikatą, CA (Certificate Authority) arba atsisiųsti nemokamą sertifikatą iš:http://CAcert.org. Plačiau pasiskaityti apie SSL/TLS protokolo įdiegimą APACHE web serveryje galite: http://httpd.apache.org/docs/2.4/ssl/ssl_faq.html. Sėkmingai įdiegūs SSL, ir įvedūs tam tikrą adresą pvz: https://127.0.0.1/httpsPage/index.php, adresų juostoje turi būti pavaizduota žalia užrakinta spyna nusakanti jog bus naudojamas saugus protokolas duomenų apsikeitimui su serveriu.

**6 užduotis**. Pasinaudoti programa/biblioteka WGET, kurią galimą pasileisti, bet kurioje operacinėje sistemoje: Išsiaiškinti kokias funkcijas gali atlikti ši programa, ir kokius veiksmus galėtumėte atlikti siekiant išgauti informacijos iš web aplikacijų/interneto svetainių. Nukopijuoti WEB svetainės/WEB aplikacijos turinį, pavyzdžiui savo kuriamos web aplikacijos ir jeigu yra galimybė nukopijuoti svetainės turinį paveikslėliai, puslapiai ir t.t. tada, kokį būdą galėtumėte pritaikyti siekiant užkirsti kelią svetainės turinio kopijavimui trumpai aprašyti veiksmų seką.

**7 užduotis**. Sukurti funkciją, modulį ar programą skirtą apsaugoti nuo „SQL injection“, kuri tikrintų įvesties laukelyje įvestą simbolių eilutę ir ignoruotų visus reikšminius simbolius, kurie vienaip ar kitaip gali pakenkti SQL užklausai pakeisdami logiką ar sukeldami dirbtines klaidas: SQL specifinius, bei kitus nepageidautinus simbolius. Kaip pavyzdys programai skirtai filtruoti duomenis, būtų sintaksinis analizatorius (angl. Parser).

**8 užduotis**. Sukurti naują metodą arba pritaikyti jau esamą, skirtą apsaugoti jūsų tinklalapį nuo atvaizdavimo kituose tinklalapiuose. Taip pat turėtų būti galimybė atvaizduoti jūsų tinklalapį kituose tinklalapiuose. Pavyzdžiui: www.google.lt svetainėje leidžiame atvaizduoti jūsų tinklalapį, o www.facebook.com neleidžiame atvaizduoti.

**9 užduotis**. Sukurti paprastą http serverį į kurį būtų galima kreiptis iš naršyklės arba iš klientinės programos. Serverio ir kliento „bendravimas“ gali būti realizuojamas naudojantis SOCKET ar kitomis bibliotekomis. Taip pat turi būti galima siųsti komandas ir jas apdoroti. Pavyzdžiui vietoje standartinio GET – naudoti lietuvišką žodi GAUTI arba PUBLIKUOTI.
