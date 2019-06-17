<img alt="logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# HTML/CSS &ndash; elementy obok siebie


Stwórz plik style.css. Pamiętaj o dodaniu go do index.html. Style CSS pisz w pliku style.css

Ustaw elementy według poniższego wzoru.

![screen](images/elements.png)

##### 1. Nadaj elementom odpowiednie atrybuty:
  * Pierwszy div - na obrazku 'Div 1.' - ```id="first-div"``` oraz klasa - ```class="box"```
  * drugi div - na obrazku 'Div 2.' - ```id="second-div"``` oraz klasa - ```class="box"```
  * Paragrafom nie nadawaj id/klas - ostyluj je odnosząc się do selektora **p**

##### 2. W pierwszym wierszu mają być dwa elementy **div** o następujących własnościach:
  * szerokość elementu: 100px,
  * wysokość elementu: 100px,
  * szerokość obramowania: 1px,
  * styl obramowania: pojedyncza linia ciągła (**solid**), (Użyj skróconego zapisu: border: [grubość] [rodzaj linii] [kolor] )
  * kolor obramowania: czarny.

  **Ważne** - powyższe własnosci (odnoszące się do obu div-ów) ostyluj odnosząc się do selektora **.box**. Odpowiednie id (```id="first-div"``` oraz ```id="second-div"```) wykorzystaj tylko do odpowiedniego rozmieszczenia elementów.

  ```css
 .box {
    /* Tutaj deklaracja własności dla obu div-ów */
 }
 #first-div {
    /* Tutaj deklaracja własności indywidualnych dla diva o id="first-div" */
 }
 #second-div {
    /* Tutaj deklaracja własności indywidualnych dla diva o id="second-div" */
 }
  ```

**Wskazówka:** Pomiędzy elementami div a paragrafami dodaj pusty element **div** o klasie ```class="clearfix"```. W pliku style.css ustaw mu `clear: both`.

  Pierwszy div ma znajdować się po lewej stronie, a drugi &ndash; po prawej.

##### 3. W drugim wierszu mają się znaleźć dwa paragrafy o następujących własnościach:
  * szerokość elementu: 80px,
  * szerokość obramowania: 2px,
  * styl obramowania: pojedyncza linia kropkowana (**dotted**),
  * kolor obramowania: czerwony.

  Paragrafy maja ustawiać się obok siebie, po lewej stronie.

---

## Ważne
Do odpowiedniego ustawienia elementów możesz korzystać wyłącznie z następujących własności:
  * **display**
  * **float**
  * **clear**

Nie musisz jednak korzystać ze wszystkich wyżej wymienionych.

Aby ustawić elementy obok siebie skorzystaj albo z **float** albo z **display**. W tym przypadku nie może być w jednym elemencie obu tych własności na raz.



## Potrzebujesz pomocy lub inspiracji?
* [tutorial, div](http://www.html-5-tutorial.com/div-tag.htm)
* [dokumentacja, display](https://developer.mozilla.org/pl/docs/Web/CSS/display)
* [tutorial,  display](http://css.webcodehelpers.com/2014/05/css-display-block-vs-inline-block-vs.html)
* [dokumentacja, float](https://developer.mozilla.org/pl/docs/Web/CSS/float)
* [tutorial, float](http://learnlayout.com/float.html)
* [dokumentacja, clear](https://developer.mozilla.org/pl/docs/Web/CSS/clear)
* HTML i CSS &ndash; prework
