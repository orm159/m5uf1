##1.5 Característiques dels llenguatges més difosos

És considera un llenguatge de programació molt difós aquell que es fa servir a moltes universitats o centres educatius per 
a la docència de la iniciació a la programació. Els llenguatges de programació més difosos corresponents a diferents àmbits,
tenen una sèrie de característiques en comú que són les que marquen les similituds entre tots ells.

* **1.5.1 Característiques de la programació estructurada**
   * Es basa en el denominat teorema de l’estructura. Per això utilitza únicament tres estructures: seqüència, selecció i 
   iteració, essent innecessari l’ús de la instrucció o instruccions de transferència incondicional. Per tant les característiques
   de la programació estructurada són la claredat, el teorema de l’estructura i el disseny descendent.
   
        La claredat és que hi haurà d’haver prou informació al codi per tal que el programa pugui ser entès i verificat: comentaris, 
        noms de variables comprensibles.
   
        El teorema de l'estructura demostra que tot programa es pot escriure utilitzant únicament les tres estructures bàsiques
        de control:
        * Seqüència: instruccions executades successivament, una darrere l’altra.
        * Selecció: la instrucció condicional amb doble alternativa, de la forma “si condició, llavors SentènciaA, 
          sinó SentènciaB”.
        * Iteració: el bucle condicional “mentre condició, fes SentènciaA”, que executa les instruccions repetidament 
          mentre la condició es compleixi.
          
        El disseny descendent és una tècnica que es basa en el concepte de “divideix i venceràs” per tal de resoldre un problema 
        en l’àmbit de la programació. Es tracta de la resolució del problema al llarg de diferents nivells d’abstracció.
        
        Es parla de **programació modular**, quan ens referim a la divisió d’un programa en parts més manejables i independents.
        Una regla pràctica per aconseguir aquest propòsit és establir que cada segment del programa no excedeixi, 
        en longitud, d’un pam de codificació.
* **1.5.2 Característiques de la programació orientada a objectes**
   * L'orientació a objectes (en endavant, OO) és un paradigma de construcció de programes basat en una abstracció del món real,
   i considerem un objecte a una combinació de dades (anomenades atributs) i mètodes (funcions i procediments) que ens permeten 
   interactuar amb ell.
   
       La programació orientada a objectes es basa en la integració de 5 conceptes: abstracció, encapsulació, modularitat, 
       jerarquia i polimorfisme.  
       La **abstracció** és el procés en el qual se separen les propietats més importants d’un objecte de les que no ho són. 
       És a dir, per mitjà de l’abstracció es defineixen les característiques essencials d’un objecte del món real, 
       per després modelar-lo en un objecte de programari.  
       La **encapsulació** permet als objectes triar quina informació és publicada i quina informació és amagada a la resta
       dels objectes. Per això els objectes solen presentar els seus atributs com a dades privades o protegides, essent 
       inaccessibles des d’altres objectes.
       La **modularitat** permet poder modificar les característiques de cada una de les classes que defineixen un objecte, 
       de forma independent de la resta de classes en l’aplicació.  
       La **Jerarquia** permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un sistema complex són 
       l’herència i l’agregació.  
       L’herència també es pot veure com una forma de compartir codi, de manera que quan s’utilitza l’herència per definir 
       una nova classe només s’ha d’afegir allò que sigui diferent mentres que l’agregació és un objecte que està format de
       la combinació d’altres objectes o components.  
       El **polimorfisme** és una característica que permet donar diferents formes a un mètode, ja sigui en la definició 
       com en la implementació.
