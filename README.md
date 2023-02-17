# challenge_portfolio_Maks
# **Task 1** - Testy eksploracyjne
## Subtask 1 - Test
7 punktów
## Subtask 3 - Info
Cześć! Jestem Maks 🙂 Szukałem kursu stawiającego na zadania praktyczne i nie za miliony monet 😉 Poza względami praktycznymi zależy mi na zapoznaniu się z grubsza na specyfice zawodu testera, jak to może wyglądać na co dzień itd. 

Wiedza i doświadczenie tu nabyte pozwolą mi zweryfikować, czy nadaję się na to stanowisko 😄
#### **_Maks_**

## Subtask 4 - Testy eksploracyjne
#### **_OPIS STRONY_**
Aplikacja Scouts Panel polega na dodawaniu skautów piłki nożnej. Służy ona do monitorowania pozycji, umiejętności zawodników oraz statystyk odbytych meczów.
Dostęp do strony wymaga posiadania profilu, logowanie odbywa się za pomocą loginu i hasła. 

Na stronie głównej na samej górze jest niebieski pasek z nazwą strony. Niżej po lewej mamy pionowe pole nawigacyjne. W górnej części głównego okna są obok siebie kafelki ze statystykami (ilość graczy, meczy, raportów i akcji). Poniżej mamy kafelek panelu zarządzania graczami, meczami i do tworzenia raportów. Pod linkami pomocniczymi jest opcja "dodaj gracza". Po prawej stronie okno z ostatnimi akcjami wykonanymi na stronie.

#### **_UWAGI DO INTERFEJSU_** 🖼

STRONA GŁÓWNA
* pole nawigacyjne powinno być przeniesione na górny niebieski pasek, jako, że w tym miejscu będzie bardziej widoczne. Napisy w polu nawigacyjnym też powinny się bardziej wyróżniać.
* opcja dodaj gracza nie powinna być w kafelku z linkami pomocniczymi. To w zasadzie głowny ficzer strony i powinien być wyeksponowany
* w linkach pomocniczych powinien się znajdować Scouts Panel
* kafelki z ilością graczy, meczy itd umieściłbym na dole strony, gdyż nie są to informacje aż tak istotne, by umieszczac je na górze, gdzie zazwyczaj spoglądamy w      pierwszej kolejności.
* dodatkowo brakuje na górnym niebieskim pasku dosłownie kilku słów o czym jest ta strona.
![Strona główna uwagi](https://user-images.githubusercontent.com/39927014/212330059-9234112d-75fd-4d8d-b29c-da76200d7fc5.jpg)

DODAJ GRACZA
* na pierwszy rzut oka pola z danymi są chaotyczne - adres email powinien być trzeci w kolejce za imieniem i nazwiskiem.
* każde pole powinno być zauważalnie odseparowane od sąsiednich, teraz mam wrażenie, że jedno nachodzi na drugie.
* czcionki nad polami tekstowymi powinny być ciut większe.
* na dole strony zabrakło spolszczenia "Submit" i "clear".

MECZE
* jak w przypadku okna "dodaj gracza", każde pole powinno być zauważalnie odseparowane od sąsiednich, wrażenie, że jedno nachodzi na drugie.

RAPORTY
* logotyp "Futbol Kolektyw" i tekst pod nim - razem wyśrodkować.
* warto uporządkować poszczególne sekcje wyszczególniając co drugą pozycję delikatnym tłem dla poprawienia czytelności.

![Panel raportu](https://user-images.githubusercontent.com/39927014/212767563-f4bd996f-ce6d-4e88-883c-dce433826de9.jpg)

<<<< EDIT 25.01>>>>

MECZ "START REPORT"

![Match report](https://user-images.githubusercontent.com/39927014/214546270-d5b8d9aa-6686-4442-ac6a-3fdeab33ef8d.jpg)

<<<<END EDIT>>>>>

#### **_UWAGI EKSPLORACYJNE_**

1 STRONA GŁÓWNA

1.1 Brak uwag 👌

2 DODAJ GRACZA

2.1. Podczas wpisywania w osiągnięciach znaków specjalnych skasowało mi wcześniej wypełnione pola - jednorazowy przypadek

2.2. Po wpisaniu , gdzie to możliwe, randomowych liter cyfr i znaków specjalnych i zatwierdzeniu gracza wyświetla się na moment informacja "nie udało się dodać gracza". Nie ma żadnej informacji w których polach dane zostały źle wprowadzone.

![błąd dodawanie gracza](https://user-images.githubusercontent.com/39927014/212338306-f32a8cbf-eb38-4c97-97ee-1738c5140fef.jpg)

2.3. Po wprowadzeniu poprawnych danych udaje się zapisać gracza

![poprawne dodanie gracza](https://user-images.githubusercontent.com/39927014/212340016-3339ebf3-eb0c-44f5-9a09-9f0fcce0fb73.jpg)

2.4. Większość pól musi mieć dokładnie zdefiniowane wartości, jakie może przyjąć: 

  -  2.4.1 Na przykład pole mejlowe musi mieć zdefiniowany prefix mejla do 2 lub 3 znaków (pl, com)
  
  -  2.4.2 Pola ( imię, nazwisko, poziom rozgrywek, główna pozycja, pozycja alternatywna, osiągnięcia, Łączy nas piłka, języki) powinny mieć znaki ograniczone do liter.                 Dodatkowo wszystkie te pola, prócz imienia i nazwiska) powinny mieć zdefiniowane listy wyboru.

  -  2.4.3 Pola ( Profil facebook, link do youtube) powinny mieć zdefiniowany schemat podawania adresów, np.: www.facebook.com/xxxxx

  -  2.4.4 Pola wagi i wzrostu ograniczyć do 3 dodatnich cyfr. 
 
  -  2.4.5 Pole "telefon" zdefiniować tylko do cyfr i w określonym schemacie, np: 111 222 333

  -  2.4.6 Rok urodzenia możnaby ograniczyć od 1900 w górę.

3 MECZE

3.1 Większość pól musi mieć dokładnie zdefiniowane wartości, jakie może przyjąć:

  -  3.1.1 W polach "zdobyte gole", "stracone gole" warto zrobić rozwijaną listę z liczbą goli. Teraz można wpisywać kilkucyfrowe wartości.
    
  -  3.1.2 Pola "Web match" i "General" nie zostały przetłumaczone
    
  -  3.1.3 Datę też warto ograniczyć do kilku lat wstecz
    
  -  3.1.4 Pola "kolor koszulki" i "Liga" powinny mieć rozwijane menu wyboru. Teraz można wpisywać wszystkie możliwe znaki.
    
  -  3.1.5 Pole "numer" ograniczyć do dodatnich wartości

4 GRACZE

4.1 Nie wiem czy to kwestia przeglądarek ( Opera i Chrome), ale w opcji drukowania strony nie można ustawić widoku na wszystkie kategorie


   ![Lista graczy drukowanie](https://user-images.githubusercontent.com/39927014/212984403-02d6847d-4801-4e86-8c83-b028cc147307.jpg)

4.2 W eksportowanym pliku tableDownload.csv w unicode (UTF-8) kolumny "mecze" i "raporty zawierają dziwne dane.

![tableDownload](https://user-images.githubusercontent.com/39927014/212985667-b14e629c-97e9-4ebf-a8ea-7f5b9dc0286c.jpg)

<sub>UWAGA: Testy wykonano na systemie Windows 10 ( wersja 22H2, kompilacja 19045.2486), przeglądarka Opera w wersji 94.0.4606.38</sub>

# **Task 2** - Test cases

## Subtask 1 - Pisanie przypadków testowych na podstawie User Story.

https://docs.google.com/spreadsheets/d/1k2VSX9ljLJZ7DYsGkprwYF0FLrvy9BQv/edit?usp=sharing&ouid=109741062900965762182&rtpof=true&sd=true

## Subtask 2 - Pisanie przypadków testowych na podstawie “własnych doświadczeń

https://docs.google.com/spreadsheets/d/1iaY3haq1NTlCmZ-9KnFvkYug221VI_nI/edit?usp=sharing&ouid=109741062900965762182&rtpof=true&sd=true

## Subtask 3 - Po co piszemy test case’y?


![friends-american-sitcom](https://user-images.githubusercontent.com/39927014/216820030-26c94370-4a4f-481d-99ad-caab82a7d675.gif)

* Lepsza kontrola nad tym, co jest do przetestowania. Gwarancja, że żadna funkcjonalność nie zostanie pominięta.
* Wykrywają błędy logiczne w historyjkach użytkownika i aplikacji
* wychwycenie błędów przed wyposzczeniem produktu do eksploatacji
* Pokrycie przypadkami testowymi jak największej ilości funkcjonalności aplikacji zmniejszamy szanse wystąpienia poważniejszych błędów
* Numeracja i zwięzłe nazewnictwo każdego przypadku testowego ułatwia poruszanie się między nimi
* Dobrze napisana lista przypadków testowych może być przejmowana przez kolejne osoby
  
# **Task 3** - Raportowanie błędów
  
## Subtask 1 - Utworzenie formatki do zgłaszania błędów systemu
  
  https://docs.google.com/spreadsheets/d/1Vyvnd0yYJ1A1et3lduxvTJqAHTJ1ontK/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true
  
## Subtask 2 - Testowanie według planów testów i raportowanie błędów
  
  * Based on User story Test Cases
  https://docs.google.com/spreadsheets/d/1onzTMEpjXXKKY03y5fct-EDPGlEdXRMg/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true
  
  * Based on experience tests
  https://docs.google.com/spreadsheets/d/1eHD6XdmwG53eR9U0crZM2ilYy2-0Wa_a/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true
  

## Subtask 3 - Raport z wykonanych testów
  
 https://docs.google.com/spreadsheets/d/1TKrXUbD2A5wnBecPmASfipWVhc2RNm5O/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true

# **Task 4** - Testowanie aplikacji mobilnych - OLX 🛒

## Subtask 2 - Testowanie eksploracyjne i raportowanie błędów

https://docs.google.com/spreadsheets/d/1OkxMtNMAAsOoR7k3GUrkIO2ZBUxR2BIc/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true
  
## Subtask 3 - Do czego służy ta aplikacja?
  Aplikacja OLX służy do zamieszczania ogłoszeń dotyczących kupna/sprzedaży rzeczy lub usług.👜  Użytkownikami aplikacji są osoby planujące zakup konkretnych produktów lub usług.
  
  Aplikacja, pomimo skromnego interfejsu, jest przyjazna i czytelna dla użytkownika. Pasek menu jest na dole, co ułatwia obsługę kcuikiem.👍 Kafelki z ogłoszeniami mogły by być dla czytelności bardziej odseparowane od siebie. W kategorii "Motoryzacja" jest zdecydowanie za mało filtrów wyszukiwania lub są gdzieś ukryte.👎 Brak przebiegu auta, rodzaju paliwa, pojemności silnika itd:

https://user-images.githubusercontent.com/39927014/217283892-2bb52cc1-8274-498f-a003-eec7cf3a297e.mp4
  
  Testowanie aplikacji natywnej różni się od testowania aplikacji internetowej.📱🖥💻📲 Wynika to z tego, że obsługa telefonu/tabletu jest prostsza i mniej precyzyjna w porównaniu do obsługi komputera. Kursorem i myszką na dużym ekranie jesteśmy w stanie wykonywać bardziej skomplikowane operacje niż palcami na telefonie. Dlatego też aplikacje natywne muszą być dostosowane do tego typu prostej obsługi. Dodatkowo w aplikacjach mobilnych testowaniu podlega ich responsywność w pionowym układzie ekranu i poziomym. 


# **Task 4** - SQL part 1

## Subtask 1 - Krótki kurs podstaw SQL

- SELECT * FROM

- CREATE TABLE <table_name>
  
- SELECT * FROM <XYZ> ORDER BY <Name>
  
- SELECT * FROM <XYZ> WHERE
  
## Subtask 3 - Kilka zadań na rozgrzewkę
  
### 1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
  
  SELECT * FROM `actors` ORDER by surname
  
  ![1](https://user-images.githubusercontent.com/39927014/218466942-74e6ee19-60d6-42b9-9048-8516d03223ae.jpg)

### 2. Wyświetl film, który powstał w 2019 roku.
  
  SELECT * FROM `movies` WHERE year_of_production = '2019'
  
  ![2](https://user-images.githubusercontent.com/39927014/218469509-be1ea41b-9752-490b-b949-cba9e840d956.jpg)

### 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
  
  SELECT * FROM `movies` WHERE year_of_production BETWEEN 1900 and 1999
  
  ![3](https://user-images.githubusercontent.com/39927014/218470441-70ee600d-0b5c-469c-a79e-15a06947527b.jpg)

### 4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$
  
  SELECT title, price FROM `movies` WHERE price < 7
                                                   
                                                   
  ![4](https://user-images.githubusercontent.com/39927014/218471633-4b693b48-2079-4461-92e1-cda26e571ea4.jpg)
  
### 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
   
  SELECT actor_id, name FROM `actors` WHERE actor_id >= 4 AND actor_id <= 7
                                                                          
  ![5](https://user-images.githubusercontent.com/39927014/218473318-9fe6833d-1958-465d-8757-743449dbee4c.jpg)

### 6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.
  
  SELECT customer_id, name FROM `customers` WHERE customer_id%2 = 0                                                                        
 
  ![6](https://user-images.githubusercontent.com/39927014/218480130-e535cec1-4394-49a0-923d-0fc0daa9f25f.jpg)
                                                          
### 7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.                                                                          
                                                                          
  SELECT customer_id, name FROM `customers` WHERE customer_id IN (1, 3, 5)                                                                     
  
  ![7](https://user-images.githubusercontent.com/39927014/218480404-2078bcec-8f4a-42ad-a56b-59d067d84b38.jpg)

### 8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
                                                                          
  SELECT * FROM `actors` WHERE name LIKE 'An%'      
                                                                          
  ![8](https://user-images.githubusercontent.com/39927014/218481295-d47fc7c5-b881-418d-b132-123afc17b9c9.jpg)
                                                                
### 9. Wyświetl dane klienta, który nie ma podanego adresu email.
                                                                          
   SELECT * FROM `customers` WHERE email IS null
                                                                          
   ![9](https://user-images.githubusercontent.com/39927014/218481682-a5a45eda-2757-4eb0-bf16-44c47e68e654.jpg)
                                                                       
### 10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.                                                 
                                                                          
  SELECT * FROM `movies` WHERE price > 9 AND movie_id BETWEEN 2 AND 8
  
  ![10](https://user-images.githubusercontent.com/39927014/218482850-f26d608c-67cf-4198-9ace-d75e78464efa.jpg)

  
# **Task 6** - SQL part 2
  
  ## Subtask 1 - Krótki kurs podstaw SQL
  
  ### 11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd
  
  UPDATE customers SET surname = 'Miler' WHERE customer_id = 3;
  
  ![1](https://user-images.githubusercontent.com/39927014/219633920-4107af14-72ea-46a9-8ccb-ec27d8914fa7.jpg)

 ### 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.
  
  
  SELECT customers.name, customers.email
  
FROM customers
  
INNER JOIN sale ON customers.customer_id=sale.customer_id
  
WHERE sale.movie_id=4
   
  ![12](https://user-images.githubusercontent.com/39927014/219645559-70b9fcbc-7a99-490f-ae24-2c6213308d6e.jpg)

### 13.  Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com
  
  UPDATE customers SET email = 'pati@mail.com' WHERE customer_id = 4
    
  ![13](https://user-images.githubusercontent.com/39927014/219651943-61a30a04-c338-4ebd-b091-b270e9cac551.jpg)

### 14.   Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).
  
  SELECT customers.name, customers.surname, movies.title
  
  FROM customers
  
  INNER JOIN sale ON sale.customer_id=customers.customer_id
  
  INNER JOIN movies ON movies.movie_id=sale.customer_id
  
  ![14](https://user-images.githubusercontent.com/39927014/219687964-ca9a4f68-d52f-4220-a310-d43450f4aaa6.jpg)

  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
