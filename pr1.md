# T1.PR1 Seguretat i vulnerabilitat

## Exercici 1

<h4> Escull 3 vulnerabilitats d’aquesta llista i descriu-les. Escriu l’impacte que tenen 
a la seguretat i quins danys pot arribar a fer un atac en aquesta vulnerabilitat. Enumera 
diferents mesures i tècniques per poder evitar-les.</h4>

- <u>Fallades criptogràfiques: </u> 

**Què són?** Dintre de la informàtica són un tipus de fallades que succeeixen quan la
criptografia, dissenyada per resguardar informació i dades mitjançant l'encriptació,
no compleix la seva funció correctament. Aquestes es poden donar per diversos motius:
per l'aplicació d'algorismes criptogràfics poc robusts o perillosos, pel mal l'ús
d'algorismes criptogràfics, per falles en l'estructura del sistema...

**Quin és el seu impacte?** Depenent del tipus de fallada dintre de les criptogràfiques
podria resultar en una pèrdua de dades, filtració d'informació confidencial, facilitació
d'invasió al sistema i, en el pitjor dels casos, una bretxa de dades a gran escala.

**Com es poden evitar?** Es poden evitar seguint els següents consells:
fer ús d'algorismes i protocols criptogràfics que tinguin el reconeixement de ser segur i
d'estar actualitzats, aplicar-los adequadament (seguint bones pràctiques), dissenyar
el sistema per a què gestioni els elements criptogràfics correctament, fer
proves periòdiques per identificar i corregir possibles fallades.

- <u>Injecció: </u>

**Què són?** 

**Quin és el seu impacte?**

**Com es poden evitar?**

- <u>Falles d'identificació i autenticació: </u>

-------------

## Exercici 2

<h4>Obre el següent enllaç ([sql inseckten](https://www.sql-insekten.de/)) i realitza un mínim de 7 nivells fent servir 
tècniques d’injecció SQL.</h4>
<h4> a) Copia cada una de les sentències SQL resultant que has realitzat a cada nivell i 
comenta que has aconseguit.</h4>
<h4> b) Enumera i raona diferents formes que pot evitar un atac per SQL injection en 
projectes fets amb Razor Pages i Entity Framework.</h4>

-------------

## Exercici 3

<h4>L’empresa a la qual treballes desenvoluparà una aplicació web de venda d’obres 
d’art. Els artistes registren les seves obres amb fotografies, títol, descripció i preu. 
Els clients poden comprar les obres i poden escriure ressenyes públiques dels artistes 
a qui han comprat. Tant clients com artistes han d’estar registrats. L’aplicació guarda 
nom, cognoms, adreça completa, dni i telèfon. En el cas dels artistes guarda les dades 
bancàries per fer els pagaments. Hi ha un tipus d’usuari Acount Manager que s’encarrega 
de verificar als nous artistes. Un cop aprovats poden pública i vendre les seves obres.

Ara es vol aplicar aplicant els principis de seguretat per tal de garantir el servei 
i la integritat de les dades. T’han encarregat l'elaboració de part de les polítiques 
de seguretat. Elabora els següents apartats:</h4>

<h4>a) Definició del control d’accés: enumera els rols  i quin accés a dades tenen cada 
rol.</h4>
<h4>b) Definició de la política de contrasenyes: normes de creació, d’ús i canvi de 
contrasenyes. Raona si són necessàries diferents polítiques segons el perfil d’usuari.</h4>
<h4>c) Avaluació de la informació: determina quin valor tenen les dades que treballa 
l'aplicació. Determina com tractar les dades més sensibles. Quines dades encriptaries?</h4>

-------------

## Exercici 4

<h4>En el control d’accessos, existeixen mètodes d’autenticació basats en tokens. Defineix 
l’autenticació basada en tokens. Quins tipus hi ha? Com funciona mitjançant la web? Cerca 
llibreries .Net que ens poden ajudar a implementar autenticació amb tokens.</h4>

-------------

## Exercici 5

<h4>Crea un projecte de consola amb un menú amb tres opcions: </h4>

<h4>a) Registre: l’usuari ha d’introduir username i una password. De la combinació dels dos 
camps guarda en memòria directament l'encriptació. Utilitza l’encriptació de hash HA256. 
Mostra per pantalla el resultat.</h4>

<h4>b) Verificació de dades: usuari ha de tornar a introduir les dades el programa 
mostra per pantalla si les dades són correctes.</h4>

<h4>c) Encriptació i desencriptació amb RSA. L’usuari entrarà un text per consola. A 
continuació mostra el text encriptat i en la següent línia el text desencriptat. 
L’algoritme de RSA necessita una clau pública per encriptar i una clau privada per 
desencriptar. No cal guardar-les en memòria persistent.</h4>

<h4>Per realitzar aquest exercici utilitza la llibreria System.Security.Cryptography.</h4>

-------------

## Exercici 6

#### Referències consultades:

https://lab.wallarm.com/what/a02-2021-fallas-criptograficas-owasp-conozca-mejor-este-problema-cibernetico/?lang=es