# Projekti
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


## Rock solid project
## Aktivni tempomat
* Naredil sem aktivni tempomat, ki deluje na podlagi procesiranja slik.
* Ta aktivni tempomat je bil vzpostavljen v simulaturju AIRSIM, kjer je moj program pridobival slike kamer in hitrostnega senzorja, s pomočjo teh podatkov pa je upravljal zavoro in pogon avtomobila.
* Tempomat je vzdževal časovno razdaljo med 2 in 3 sekunde.
* Vseboval je pa tudi varnostno ustavlanje.
* Program je bil narejen v programskem jeziku python s pomočjo CV2, numpy in YOLO.
* Najprej sem zaznal avtomobile s pomočjo modela YOLO.
* Iz višine na kameri sem ugotovil razdaljo.
* S pomočjo hitrosti in razdalje sem ugotovil časovno razdaljo.
* Potem pa sem z nekaj funkcijami upravljal spremembe hitrosti avta in po potrebi varnostno zaviranje.
<img width="1202" height="731" alt="image" src="https://github.com/user-attachments/assets/85852fb4-ba4c-4cf3-8cf6-2a7c3f5b49a3" />

# 4 v vrsto in alfa-beta minmax
* alfa-beta minmax
* razne hevristične funkcije za izbolšanje nasprotnika
<img width="549" height="761" alt="image" src="https://github.com/user-attachments/assets/a21efd15-99c0-4f46-84df-03b2fefdc7fa" />

## Nevronska mreža brez knjižnic
* Program za zaznavo številk
* Implementirane (Xavier inicializacija in Sigmoid, He inicializacija in Relu, MSE Izgubna funkcija, Softmax, kategorična križna entropija)
<img width="447" height="474" alt="image" src="https://github.com/user-attachments/assets/99c09881-9a43-4b8d-a52f-39db8684aadf" />

## Q-Učenje
* Implementacija Q-učenja
* Prilagajanje Q-učenja za razne igre
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/14266c63-04a3-4c31-afe6-06ce0c47c964" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/8d6dcef7-e451-463b-9ca4-421744594d8c" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/3f4f67fb-8f3a-4e66-ab31-8cca86c654fe" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/ec190df8-667e-406b-9362-829abfdc1544" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/22eff3e5-7bfc-4558-96c6-dd68a550fb62" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/fff434ca-a0e6-449e-84a6-7ac5941ebe69" />


## Projekt v večji skupini
* Testni projekt, za vajo sodelovanja
* Skupina 15 ljudi
* Tukaj sem izvajajl postavlanje nalog, pregled sprememb, pisanje sporočil
* Postavljanje nalog, pregledi  pisanje poročil
* Implementirali smo spletno in mobilno aplikacijo za hranjenje receptov in stanja sestavin v naši shrambi.


