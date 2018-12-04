# Klausur 06.12.2018
## Klausurthemen
* absatz-zeilenumbruch
* css
* github-git
* grafiken
* html-grundstruktur
* listen
* semantic-html 1
* semantic-html 2
* semantic-html 3
* tabellen
## Aufschriebe von Hannah
> “Informatik HTML Aufschriebe 2018” by [HannahKup](https://github.com/HannahKup) is licensed under [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/)
### Aufschrieb 1
1. ```html <p> Absatztext </p> ```
* Absatz (paragrapgh) mit Zeilenumbruch (ist ein Blockelement)
2. ```html <br> ```
* Zeilenumbruch (Inline Element)
3. Schriftschnitte
* ```html <strong> Text </strong> ```
  * Text stark Hevorgehoben
* ```html <em> Text </em> ```
  * Text Hervorgehoben
* ```html <sup> Text </sup> ```
  * Text wird Hochgestellt
* ```html <sub> Text </sub> ```
  * Text wird Tiefgestellt
5. ```html <div class ="name"> Text </div> ```
* Verwendet Textauszeichnung aus der Klasse "name" aus der CSS-Datei (Blockelement)
6. ```html <div id = "name"> Text </div> ```
* Wie calss aber ID darf es nur einmal geben, da ID eindeutig ist kann sie in Hyperlinks verwendet werden
### Aufschrieb 2
#### CSS
* Der Sinn: Trennung von Inhalt und Design
* Hintergrundfarbe: 
``` CSS body { backround-color: blue; } ```
* Schriftfarbe:
```CSS  { @import url('https://...'); ```
```CSS   body { font-fmaily: 'open Sans', sans-serif; ```
* Textausrichtung:
```CSS body { text-align: center; } ```
* Textfarbe:
```CSS body {color: yellow;} ```
### Aufschrieb 3
1. Github 
Github ist eine Plattform, auf der man Opnesource Software veröffentlichen kann, es ermöglicht die Zusammenarbeit von Entwicklern Wletweit.
2. Git
Git ist ein Versionskontrollsystem, das Zentral und dezentral agieren kann. Es wird heutzutage von den meisten profesionellen Softwareanbietern benutzt.
3. Git Workflow
![git-workflow](https://github.com/marcelrhd/Schule/blob/master/github-git.jpg)
### Aufschrieb 4
#### Grafiken
* Elemente in eine HTML-Datei einbinden (relativer vs. absoluter Pfad)
##### Relativer Pfad
* steht in Realation zum Ausgangspunkt
* Man liest von unten nach oben
* trennt mit -> /
* ```html <img src ="projekte/images/delphine/delphin.gif"/>```
![grafiken](https://github.com/marcelrhd/Schule/blob/master/grafiken.jpg)  
##### Absoluter Pfad
* Die URL (Uniform Resource Location) zur Seite
* http://www....
* Immer eindeutig, egal von wo dieser Link gesetzt wird und setzt voraus, dass sich diese Seite bereits auf dem Server im Netz befindet
  * ```html <img src="https://onedrive.live.com/embed?cid=17FF704AFAC26C81&resid=17FF704AFAC26C81%2174170&authkey=ADDtyIc2RJjuZzU" />```
![git-workflow](https://github.com/marcelrhd/Schule/blob/master/grafiken.jpg)  
### Aufschrieb 5
```html 
<html>
  <head>
      <title>
          Mein Titel
      </title>
  </head>
  <body>
      <h1>
        Informatikstunde
      </h1>
      <ol>
          <li>Taddi</li>
          <li>Luisa</li>
      </ol>
      <img src= "https:// .....de"/>
  </body>
</html>
```
### Aufschrieb 6
#### Listen
* Geordnete Liste
ol= Ordered list
```html 
<ol>
   <li>Taddi</li> 
   <li>Luisa</li> 
</ol>
```

* Ungeordnete Liste
```html 
<ul>
   <li>Taddi</li> 
   <li>Luisa</li> 
</ul> 
```
ul= Unordered list  
li= List item  

##### Listenformation
Für ungeordnete Listen (HTML ul) und geornete Listen (HTML ol)  
Wichtige Werkzeuge des Webdesigns:
* list-style-type: 
  * ul mit disk, cycle, square  
  * ol mit Ziffer oder Buchstabe  
* list-style-position: Aufzählungssymbol in die Box für listenelemente einzieren  
* list-style-image: setzt ein Bild anstelle des Listensymbols in ul-Listen  
* none: kein Listensymbol  

### Aufschrieb 7-9
1. Body
* Das body-Element enthält den anzuzeigenden/darzustellenden Inhalt eines HTML-Dokumentes. Die folgenden tags können im Body vorkommen.
![Body](https://kenx9a.am.files.1drv.com/y4mT-PRu9TQ5-LAz3I1jdE3IqITifR4_lJfaBMMqBWDJPuzDJGGHyXn6wAmVsoKhYE9OyDGkfeaeqmUTJ8b5qAO6XrEOZ_CtNn6WfCAVayczSy9pu9KOkdS33_t6Kxbelg9t3sEJUH9QHqRHbCNSt8zHnU_GmvnokeCX1DAlXNm4JymZjM23W3SK5z-hLwJBpIIpdbaJo75OYZ5bjwXpvovaA?width=1005&height=228&cropmode=none)
2. Main
* Das main-tag enthält den Hauptsächlichen Inhalt einer Webseite.
![Main](https://kens9a.am.files.1drv.com/y4moPT1pZN-6sfQyfHn_t-SmAae8BMjap6VpG6LIN4q3ZEAmhB8Vrj0EH057Mx2YVgoWh2wYRuisU55ymz0XEh7nR2XvXoQDIz6PGiC5_hfoqJOkGn8oQsZWwfLTDY3tBfhfPMJV7NpJYKWmQvypnwgA-tdgSeChaU6EcZzy-YYzXMxDEfjaCSrOuec5Ga_8i4AgqzQTwQIInmR3HewdRc5TA?width=1004&height=405&cropmode=none)
3. Header
* Das header-tag den Kopfteil einer webseite darunter kann der Name einer Seite und /oder auch ein Logo darin vorkommen. (-> nicht der Head-tag)
![Header](https://kenr9a.am.files.1drv.com/y4mvsmutF3TXAomvPet_OdBrdPppRVRsxz1IxzbbeaIRdQX0SZQmBrKN5VRukxC6ZtUx_9k94r141k7R0DEbt6MFL3y9F8Aj39w0BY4edIFsXHIm3bSavIGBVb_KUfVG8b9mE9dw49tDH4ZV8XAUXLD8mNhhEVF9P6tEFZ3K7__xi-34clGdPs77P-mKFjSmGj6DeKHd-2mqacNBkDChFjuUg?width=1005&height=329&cropmode=none)
4. Footer
* Das footer-tag enthält die Information, die am Ende einer Webseite stehen wie z.B. Autor, Hinweise zum Urheberrecht, ein Link zum Impressum.
![Footer](https://j0n09a.am.files.1drv.com/y4mGahEVkyXF1zlxp8Yj4R3ao55nX7ukwTvUoau1EKbUmB_HkCtqM83LWF3-Qx5q4Nw9fNA95HZ2HNs5EIPTpbaoehigu_9QEHpWfzICwLzujR8yT9AJAoFK05kMyXC7e5G_dr-JmL8hzsYwZ9QazNFNPWM3RkK0cS8o4TUbUnpxl0z8BCuQowJGgZEQ52QLMTO_aPyvbrk-YkZxDk5_gsYpw?width=1003&height=721&cropmode=none)
5. Nav
* Das nav-tag beinhaltet Navigationsleisten und Menüs.
![Nav](https://j0nz9a.am.files.1drv.com/y4mH7AZZEypSKUrpK1afEXmIifkDq1PrWeHVjBFP51V_unGQohfbJpr2BzqF3nhfJ4guExjRNbI29XDDq7HoaC-yMO7PcUQBSNDFWv9DB_jjSZaUiSJpV1e1h9OhXYxiW-e4a4nBuUUg09-lSYBp_lqJdJWqjMAdmg8C_k9RZNCg2phYrhIsvE1js7e7z34Wg4xtwtFFi3kVTP6RpjgtmxRHQ?width=1005&height=419&cropmode=none)
6. Arcticle
* Das article-tag beeinhaltet die Funktion dass z.B. Zeitungsartikel auf einer Webseite dargestellt werden können.
![Arcticle](https://j0n29a.am.files.1drv.com/y4mGr1K-324h8pcSdqCCYrxibDOUsdtA_78E2k5hQuRosFRKqsF5Lb1CuzcLpBLV8PO7KE0l-1vVPYJXHlfyuD89Pzz5U3pBpNIV9FlJUgP45qzqqes_pQMJEkZ7DUdioRcNNJuje-fB5I-eqcz7NhHAs3UOYS93IlZ3dNxh1FzOT1t2k1dphW33UifzuT4MYJ9DISfVx4MVIi0FaXBi7B9dA?width=1004&height=635&cropmode=none)
7. Section
* Das section-tag enthält laut Spezifikation eine thematische Gruppierung von Inhalten typischerweise mit einer Überschrift.
![Section](https://j0n19a.am.files.1drv.com/y4mC4ePdgvyLpivcPL9HpThEiywLciXSxNox_rfcRC2zP8HhOS4f_H6xCh5YCYqcaTyxNCgB42uI_Ic6xgT1UbMa4OwL9YQTlNrgmDXpn3zUXkRoElU6D2ONG1ztJ09sqOFxBOQjQC_Kp24Hpi-mpvp884ixorUbI2eBEVzxITzHkjtn9yz00UJtgjQOvwcAa0oHIimOtDgk7H73QNfFGp1xg?width=1005&height=323&cropmode=none)
8. Aside
* Das aside-tag beinhaltet Quellenangaben oder Fußnoten (auch Randbemerkungen)
![Aside](https://j0nw9a.am.files.1drv.com/y4mHFChiWG35zG7CsZjHOFDyhHJpYhmdHVGpmXMLR6t-QSZaN5CwVzR92CTD027XQDKJ-sl2z7766tzhJL079KrCQgkue-XVL0YaOyWDOJCy9ojPHWFUh25gQBUFUb_M-8rl3CBHRjTcF6kFwpBShB6A5LUsBD2_hZO7bJ4LSIvuOTgWtxBkmlDlYJronvlUpMy41IUTrX3QJztuVXaOepfvQ?width=1006&height=551&cropmode=none)
9. Address
* Das address-tag enthält Information über den Autor/ Ersteller, kann aber auch einen Link zu einem Kontaktdatenblatt enthalten.
![Address](https://j0nv9a.am.files.1drv.com/y4m_-YVV6ikcJpJQpmY5gRIPtxl6kkiPbL4__XTDDnoh0X4bFGd16xGhYQXXNw9_5PnSm5axCGMpw3Ds8XIJeEhZaOGDD4iB4QpHanvmJUOmd-Zm_J9AN_SWnQnNqB4zYqhlP_E5j_Bwa-vGKbkISbAcTxbnF8uMG9068KXVYb1JzkI5ilTsdGoU4oPetiMXh_q3B3KpLveIUYvawtJuH-3Nw?width=1006&height=673&cropmode=none)
### Aufschrieb 10
#### Tabellen
```html
<tr> = Table row  
<td> = Table data  
<th> = Table header  
```
 
 z.B. 
```html
<table>
   <tr> <th>käse</th> <th>Fisch</th> </tr> 
   <tr> <th>Cheddar</tr> <td>Lachs</td> </tr> 
   <tr> <th>Gauda</tr> <td>Sardelle</td> </tr> 
</table>
```
