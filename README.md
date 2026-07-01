# Projekti
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

