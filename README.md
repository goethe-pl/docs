# docs
Documentation


### Implementation

[teoria](TEORRIA.md)
[chat](CHAT.md)
[browser extension](BROWSER.md)


# Rozwiązania

Celem rozwiązania goethe, jest wykorzystanie sztucznej inteligencji do analizy zdania
Program ma być użyty w roli nauczyciela, wskazującego błedy
oraz przykłady zawierające inne formy, by pokazać uczniowi:
 + jak poprawnie zbudować zdanie
 + gdzie i dlaczego był błąd z podaniem źródeł, tabel gramatycznych, itp 
 + Jak w innej formie z tym samym słownictwem zbudować zdania
 
Program w początkowej wersji będzie tylko wspierał podstawowe słownictwo, które jest często używane.
Ograniczenie zakresu gramatyki i słownictwa pozwoli na szybki start projektu.
Wraz z dojerzewaniem projektu, zakres będzie poszerzany.
Początkowy cel, na rok 2020 to nauka gramatyki z użyciem wielu form czasów w mowie i piśmie.

## Pierwsze wdrożenie
+ Program ma wspierać naukę gramatyki języka na poziomie A2-B1.
+ Pierwsza wersja nie będzie wspierała zaawansowanego słownictwa tematycznego a jedynie podstawy
+ Nie będzie też wspierane tłumaczenie trudnych form literackich, poezji, itp.

Te ograniczenia mają przyśpieszyć wdrożenie pierwszej użyteczniej wersji do praktycznej nauki.
Dopiero gdy zostanie zebrane doswiadczenie z praktycznej nauki, zostanie wprowadzona wersja kolejna
mająca pomóc w bardziej zaawansowanej nauce na poziomie B2 - C1.
Gdzie kluczową rolę gra profesjonalizacja języka, narracja, itp.


## Moduły wchodzące wskład programu goethe.pl
    
+ translator z języka polskiego, niemieckiego, angielskiego, rosyjskiego
+ analizator gramatyki języka do logicznego rozkładu zdań
+ interfejs graficzny i tekstowy, do pisania zdań i graficznej reprezentacji poszczególnych elementów
+ interfejs audio: transkrypcje zdań wypowiadanych oraz generowanie auio do zdań pisanych
+ słownik tekstowy: z tematycznym podziałem, synonimami
+ słownik graficzny: z obrazami przedstawiającymi sens wyrażeń, zdań, jako pomoc w nauce
+ quiz: budowanie zdań w ograniczonych zdefiniowanych przez nauczyciela ramach
+ analiza profilu ucznia: na podstawie analizy zdań z języka natywnego


## Analiza gotowych zdań

+ wyszukiwanie cytatów 
+ przykładowe frazy często występujące w życiu oraz ich analiza:
    + odmiana
    + przymiotniki
    + zaimki osobowe
    + inne formy
    + odmiany 
    + czasy
    przykłady odmiany w innych osobach i przypadkach


## Analizator tworzonego zdania przez ucznia

w ograniczonym zakresie, słownictwo podstawowe
    + pokazuje rozkłada zdania
    + określa części zdania
    + czas
    + przypadek
    + zdania podrzędne i nadrzędne


## Aplikacja do budowania zdań

### Tworzenie profilu ucznia
program na początku ma za zadanie określenie profilu ucznia,
by móc dostosować zakres słownictwa, tematykę  

#### Metoda 1:
Uczeń pisze przykładowe zdania po polsku, które chciałby umieć pisać w języku obcym

+ zdania te zostają zanalizowane po polsku
+ przetłumaczone na niemiecki przy uwzględnieniu form poziomu A2-B1 
    

### 
trzeba zebrać słownictwo jakie ma być używane
Jakie czasy wykorzystywane i jakie typy zdań mają być budowane.

1. Zbuduj zdanie oznajmujące w czasie teraźniejszym

+ kombinacje tego dla zmiennych
+ 

+ Generator zadań

+ [ROZBIOR_GRAMATYCZNY.md](ROZBIOR_GRAMATYCZNY.md)
+ [ROZBIOR_LOGICZNY.md](ROZBIOR_LOGICZNY.md)


# Libraries

![lib1.png](docs/lib1.png)
https://www.jqueryscript.net/form/Tagging-System-Autocomplete-Amsify-Suggestags.html

![lib2.png](docs/lib2.png)
https://www.jqueryscript.net/demo/Simple-Animated-jQuery-Tags-Input-Plugin-Lovely-Tag/


### TOOLS


#### Spacy
https://spacy.io/models


#### pytorch
https://pytorch.org/tutorials/



#### Colaboratory
https://colab.research.google.com/notebooks/intro.ipynb#recent=true
Was ist Colaboratory?

Mit Colaboratory oder kurz "Colab" können Sie Python-Code in Ihrem Browser schreiben und ausführen. Sie können Folgendes tun:

    Keine Konfiguration erforderlich
    Kostenlosen Zugriff auf GPUs
    Einfache Freigabe


### Books

#### NLP

https://www.cl.cam.ac.uk/teaching/1314/L100/introling.pdf


