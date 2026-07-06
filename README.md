# Projekti na delu
* Delo v sklopu projekta https://lhrs.feri.um.si/en/projects/projects-in-implementation/slovenian-reference-genomic-project/
* Razvoj programski orodij za pomoč pri genski analizi za UKC LJ

## Modifikacije odprto kodnega orodja scout, ki se uporablja za analizo genov
<img width="450" alt="image" src="https://github.com/user-attachments/assets/f86bd964-7516-4d52-a682-885501a612e3" />
<img width="500" alt="image" src="https://github.com/user-attachments/assets/cffe6944-40e6-4bf0-94a1-cb27700615aa" />

* Sam sem naredil okoli 70 sprememb in novih funkcionalnosti.
* Nove strani, s paginacijo in filtri po meri.
* Nekatere strani popolnoma spremenjene, da so bolj uporabne (npr. dodana strežniška paginacja, funkcionalnosti in izgled po meri)
* Prilagojene ključne funkcionalnosti, za zahteve naših uporabnikov, ki so popolnoma drugačne, kot tiste za katere je to orodoje bilo najprej razvito.
* Dodajanje sporočil za hranjenje zgodovine sprememb.
* Možnosti izvozov, novih po meri narejenjih poročil, glede stanja in zgodovine analiziranega primera.
* Projekt je narejen v Python, Flask, Jinja, MongoDB, grajenje in povezava z drugmi projekti pa preko Docker in docker-compose.
* Povezovanje Scout z drugimi aplikacijami, kot so gens s pomočjo docker-compose. Tukaj sem konfiguriral skupno avtentikacijo z Ldap strežnikom.
* Dodajanje jasnih opozoril, da uporabniki ne razumejo delovanja in sprememb napačno.
* Spreminjan projekt ima več kot 100 programskih datotek in 10000 sprememb.

## Delo na orodju, za vodenje samega postopka analize, od zajema vzorcev naprej

<img height="470" alt="image" src="https://github.com/user-attachments/assets/5b1914dc-f8e3-4959-96cf-66ab6e4936b9" />

<img height="350" alt="image" src="https://github.com/user-attachments/assets/a9be80d1-7111-471f-a93d-c4053d44b20f" />

* Tukaj smo delali na našem orodju, za vodenja postpoka analize skozi različna stanja.
* Orodje je narejeno v VueJs, PrimeVue, GraphQL, Molgenihs, PostgreSQL
* Sam sem delal na strežniški paginaciji strani, tukaj je potem bilo potrebno vse funkcionalnosti, ki so bile narejene na čelnem delu prestaviti na zaledni del (potrebno je bilo znova implementirati vso napredno filtriranje in sortiranje...)
* Python scripte za polnjeje baze in testiranje hitrost delovanja aplikacije, kot tudi primerjave raznih operacij GraphQL.
* Python skripte za odstranjevaje starih in nevalidnih podatkov.

# Privatni in šolski projekti
## Šah za več igralcev preko stražnika (TCP povezava)

<img width="600" alt="slika_igre" src="https://github.com/user-attachments/assets/2a6c1f1d-760b-4631-b7bb-b1ec9f333529" />

* Popolnoma funkcionalna igra šaha, za igralce na odaljenih napravah. (Podprte so vse možne poteze kot npr. en passant in rokada)
* Aplikacija implementirana v Python-u. Za povezavo med strežnikom in odjemalci uporabljena knjižnice Threading.
* Grafični vmesnik implemenitran s pomočjo PyGame. Vse UI gradniki (npr. gumbi, text, vnosna polja in njihove funkcionalnosti, kot so OnHover, OnClick, zajem vhoda...) sem implementiral sam.
* Sestavljena je iz strežnika in odjemalcev. Strežnik kontrolira potek iger (tudi preverja ali so uporabniške poteze legitimne). Na strani odjemalcel pa imemo grafični vmesnik, ki uporabnikom prikazuje pote igre, kdo je na potezi, omogoča izvajanje potez, povezave v igre, ...
* Strežnik podpira velik število sočasnih iger.
* Odjemalec sporoči strežniku, da želi ustvariti igro, ki jo strežnik nato ustvari, nato pa uporabnik pošlje svojemu nasprotniku unikatno kodo s katero se ta lahko poveže na strežnik.
* Poskrbeli smo tudi, da če en uporabnik izgubi povezavo se v igro še lahko nekaj časa vrne, preden se ta konča.
* Ta projekt je bil implementiran v skupini treh.

## Aktivni tempomat
<img width="700" alt="image" src="https://github.com/user-attachments/assets/85852fb4-ba4c-4cf3-8cf6-2a7c3f5b49a3" />

* Naredil sem aktivni tempomat, ki deluje na podlagi procesiranja slik.
* Ta aktivni tempomat je bil vzpostavljen v simulaturju AIRSIM, kjer je moj program pridobival slike kamer in hitrostnega senzorja, s pomočjo teh podatkov pa je upravljal zavoro in pogon avtomobila.
* Tempomat je vzdževal časovno razdaljo med 2 in 3 sekunde.
* Vseboval je pa tudi varnostno ustavlanje.
* Program je bil narejen v programskem jeziku python s pomočjo CV2, numpy in YOLO.
* Najprej sem zaznal avtomobile s pomočjo modela YOLO.
* Iz višine na kameri sem ugotovil razdaljo.
* S pomočjo hitrosti in razdalje sem ugotovil časovno razdaljo.
* Potem pa sem z nekaj funkcijami upravljal spremembe hitrosti avta in po potrebi varnostno zaviranje.


## Projekt matura - Video igra Preobrazba
<img width="1804" height="1018" alt="image" src="https://github.com/user-attachments/assets/a338a99a-3b10-49d5-968a-f0620d387ee0" />

* Igra, ki sem jo implementiral v srednji šoli
* V igri se lahko igralac spremeni v druge objekte, kot so naprimer meč ali pa žoga, ki pleza po zidu.
* Uporablja Python in le knjižnico PyGame
* Vse fizike sem napisal sam
* Vse texture sem narisal ročno  



## Alarm za terminal (TUI)
<img width="352" height="277" alt="image" src="https://github.com/user-attachments/assets/018de01d-cf43-484a-9721-2d36788f51cb" />

* Aplikacija narejena v C++ s knjižnico Ncurses.
* Uporabnik v terminalu požene aplikacijo, po njej pa se lahko premika z puščicami ali pa vim tipkami, celotno aplikacijo lahko kontrolira s tipkovnico
* Dodajanje, odstranjevanje, urejanje alarmov
* Alarmi so lahko ponovljivi ali ne, prav tako jih je možno izklopiti in vklopiti

## Admin aplikacije za urejanje podatkov o plezališčih v sloveniji in pridobivanje podatkov o plezališčih iz drugih strani

<img width="829" height="670" alt="image" src="https://github.com/user-attachments/assets/a598c098-9f2c-408f-9216-6fdd2d0040d0" />
* Omogoča pregled in urejanje podatkov v naši bazi
* Vsebuje "web-scraper" za pridobivanje podatkov o plezališčih iz drugih straneh
* Generator testnih podatkov
* Implementirano v Kotlin in Kotlin Multiplatform, Selenium, Jsoup, Material, Mongo, OkHttp

## Spletna stran s plezališči v sloveniji

<img width="2101" height="763" alt="image" src="https://github.com/user-attachments/assets/44343795-20ab-49c4-b83d-6bac78b8c7bb" />
* Prikaz plezališč in plezalnih poti v slovenskih plezališčih
* Združevanje uporabnikov v plezalne skupine
* NodeJS, Express, ReactJS

## Zaznava plezalnih oprimkov na plezalni steni

<img width="565" height="761" alt="image" src="https://github.com/user-attachments/assets/74d0b722-58ca-44e3-95b0-11bc6a176608" />
* Dodatno treniranje YOLO modela
* Del projekta rocksolid (trije člani)
* Flask za vzpostavitev strežnika

## Igra vitez

<img width="1274" height="719" alt="image" src="https://github.com/user-attachments/assets/0e49d52b-d65a-48f4-a1ce-e25e417c07e6" />

* Vitezev cilj je razbiti čim večje število kock
* Nekatere lahko razbije nekaterih ne more
* Igra vsebuje tudi razne powerup-e kot so explozije
* Vse spremembe so animirane, med animacijami se dinamično premikajo tudi točke za zaznavo kontaktov (hitboxi)
* Implementirano v Java in LibGDX

## Igra kače in lojtre 
<img width="1274" height="712" alt="image" src="https://github.com/user-attachments/assets/acd6f721-2302-4e30-ad93-120a56e89a7b" />
<img width="1281" height="715" alt="image" src="https://github.com/user-attachments/assets/3d0b4e54-e02f-44de-95c4-c4f4c20da71e" />

* Implementirano v Javi in LibGDX

### Media player
<img width="977" height="530" alt="image" src="https://github.com/user-attachments/assets/00e125bf-569e-4746-8e77-9d1e35c4b24b" />
<img width="399" height="290" alt="image" src="https://github.com/user-attachments/assets/bdb066ee-aa49-4d7a-a437-c9330a7c66e7" />

* Implementiran v C# in WPF
* Dinamična povezava podatkov, ob spreminjanja v edit oknu se aktivno spreminja vsebina v glavnem oknu.

## 4 v vrsto in alfa-beta minmax

<img width="549" height="761" alt="image" src="https://github.com/user-attachments/assets/a21efd15-99c0-4f46-84df-03b2fefdc7fa" />

* implementirana igra štiri v vrsto v kateri igramo proti računalniškem nasprotniku
* alfa-beta minmax algoritem za nasprotnika
* razne hevristične funkcije za izbolšanje nasprotnika

## Nevronska mreža brez knjižnic

<img width="447" height="474" alt="image" src="https://github.com/user-attachments/assets/99c09881-9a43-4b8d-a52f-39db8684aadf" />

* Program za zaznavo številk
* Implementirane (Xavier inicializacija in Sigmoid, He inicializacija in Relu, MSE Izgubna funkcija, Softmax, kategorična križna entropija)

## Q-Učenje

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/14266c63-04a3-4c31-afe6-06ce0c47c964" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/8d6dcef7-e451-463b-9ca4-421744594d8c" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/3f4f67fb-8f3a-4e66-ab31-8cca86c654fe" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/ec190df8-667e-406b-9362-829abfdc1544" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/22eff3e5-7bfc-4558-96c6-dd68a550fb62" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/fff434ca-a0e6-449e-84a6-7ac5941ebe69" />

* Implementacija Q-učenja
* Prilagajanje Q-učenja za razne igre

## Projekt v večji skupini
* Testni projekt, za vajo sodelovanja
* Skupina 15 ljudi
* Tukaj sem izvajajl postavlanje nalog, pregled sprememb, pisanje sporočil
* Postavljanje nalog, pregledi  pisanje poročil
* Implementirali smo spletno in mobilno aplikacijo za hranjenje receptov in stanja sestavin v naši shrambi.

## Electron media player
<img width="933" height="482" alt="image" src="https://github.com/user-attachments/assets/121be441-a449-45cf-9655-e75c01b0c1f7" />

## Prikaz števil ljudi na plezališčih na zemljevidu po katerem se premikamo v 3d prostoru
<img width="871" height="499" alt="image" src="https://github.com/user-attachments/assets/8fc92273-430b-42d5-aef0-a4cde967bf13" />

* LibGDX
* Del projekta rocksolid (trije člani)


## Adnroid aplikacije...
* V sklopu šole sem implementiral tudi razne android aplikacije v programskem jeziku Kotlin
