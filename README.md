# challenge_portfolio_Maks
# **Task 1** - Testy eksploracyjne
## Subtask 1 - Test
7 punkt贸w
## Subtask 3 - Info
Cze艣膰! Jestem Maks 馃檪 Szuka艂em kursu stawiaj膮cego na zadania praktyczne i nie za miliony monet 馃槈 Poza wzgl臋dami praktycznymi zale偶y mi na zapoznaniu si臋 z grubsza na specyfice zawodu testera, jak to mo偶e wygl膮da膰 na co dzie艅 itd. 

Wiedza i do艣wiadczenie tu nabyte pozwol膮 mi zweryfikowa膰, czy nadaj臋 si臋 na to stanowisko 馃槃
#### **_Maks_**

## Subtask 4 - Testy eksploracyjne
#### **_OPIS STRONY_**
Aplikacja Scouts Panel polega na dodawaniu skaut贸w pi艂ki no偶nej. S艂u偶y ona do monitorowania pozycji, umiej臋tno艣ci zawodnik贸w oraz statystyk odbytych mecz贸w.
Dost臋p do strony wymaga posiadania profilu, logowanie odbywa si臋 za pomoc膮 loginu i has艂a. 

Na stronie g艂贸wnej na samej g贸rze jest niebieski pasek z nazw膮 strony. Ni偶ej po lewej mamy pionowe pole nawigacyjne. W g贸rnej cz臋艣ci g艂贸wnego okna s膮 obok siebie kafelki ze statystykami (ilo艣膰 graczy, meczy, raport贸w i akcji). Poni偶ej mamy kafelek panelu zarz膮dzania graczami, meczami i do tworzenia raport贸w. Pod linkami pomocniczymi jest opcja "dodaj gracza". Po prawej stronie okno z ostatnimi akcjami wykonanymi na stronie.

#### **_UWAGI DO INTERFEJSU_** 馃柤

STRONA G艁脫WNA
* pole nawigacyjne powinno by膰 przeniesione na g贸rny niebieski pasek, jako, 偶e w tym miejscu b臋dzie bardziej widoczne. Napisy w polu nawigacyjnym te偶 powinny si臋 bardziej wyr贸偶nia膰.
* opcja dodaj gracza nie powinna by膰 w kafelku z linkami pomocniczymi. To w zasadzie g艂owny ficzer strony i powinien by膰 wyeksponowany
* w linkach pomocniczych powinien si臋 znajdowa膰 Scouts Panel
* kafelki z ilo艣ci膮 graczy, meczy itd umie艣ci艂bym na dole strony, gdy偶 nie s膮 to informacje a偶 tak istotne, by umieszczac je na g贸rze, gdzie zazwyczaj spogl膮damy w      pierwszej kolejno艣ci.
* dodatkowo brakuje na g贸rnym niebieskim pasku dos艂ownie kilku s艂贸w o czym jest ta strona.
![Strona g艂贸wna uwagi](https://user-images.githubusercontent.com/39927014/212330059-9234112d-75fd-4d8d-b29c-da76200d7fc5.jpg)

DODAJ GRACZA
* na pierwszy rzut oka pola z danymi s膮 chaotyczne - adres email powinien by膰 trzeci w kolejce za imieniem i nazwiskiem.
* ka偶de pole powinno by膰 zauwa偶alnie odseparowane od s膮siednich, teraz mam wra偶enie, 偶e jedno nachodzi na drugie.
* czcionki nad polami tekstowymi powinny by膰 ciut wi臋ksze.
* na dole strony zabrak艂o spolszczenia "Submit" i "clear".

MECZE
* jak w przypadku okna "dodaj gracza", ka偶de pole powinno by膰 zauwa偶alnie odseparowane od s膮siednich, wra偶enie, 偶e jedno nachodzi na drugie.

RAPORTY
* logotyp "Futbol Kolektyw" i tekst pod nim - razem wy艣rodkowa膰.
* warto uporz膮dkowa膰 poszczeg贸lne sekcje wyszczeg贸lniaj膮c co drug膮 pozycj臋 delikatnym t艂em dla poprawienia czytelno艣ci.

![Panel raportu](https://user-images.githubusercontent.com/39927014/212767563-f4bd996f-ce6d-4e88-883c-dce433826de9.jpg)

<<<< EDIT 25.01>>>>

MECZ "START REPORT"

![Match report](https://user-images.githubusercontent.com/39927014/214546270-d5b8d9aa-6686-4442-ac6a-3fdeab33ef8d.jpg)

<<<<END EDIT>>>>>

#### **_UWAGI EKSPLORACYJNE_**

1 STRONA G艁脫WNA

1.1 Brak uwag 馃憣

2 DODAJ GRACZA

2.1. Podczas wpisywania w osi膮gni臋ciach znak贸w specjalnych skasowa艂o mi wcze艣niej wype艂nione pola - jednorazowy przypadek

2.2. Po wpisaniu , gdzie to mo偶liwe, randomowych liter cyfr i znak贸w specjalnych i zatwierdzeniu gracza wy艣wietla si臋 na moment informacja "nie uda艂o si臋 doda膰 gracza". Nie ma 偶adnej informacji w kt贸rych polach dane zosta艂y 藕le wprowadzone.

![b艂膮d dodawanie gracza](https://user-images.githubusercontent.com/39927014/212338306-f32a8cbf-eb38-4c97-97ee-1738c5140fef.jpg)

2.3. Po wprowadzeniu poprawnych danych udaje si臋 zapisa膰 gracza

![poprawne dodanie gracza](https://user-images.githubusercontent.com/39927014/212340016-3339ebf3-eb0c-44f5-9a09-9f0fcce0fb73.jpg)

2.4. Wi臋kszo艣膰 p贸l musi mie膰 dok艂adnie zdefiniowane warto艣ci, jakie mo偶e przyj膮膰: 

  -  2.4.1 Na przyk艂ad pole mejlowe musi mie膰 zdefiniowany prefix mejla do 2 lub 3 znak贸w (pl, com)
  
  -  2.4.2 Pola ( imi臋, nazwisko, poziom rozgrywek, g艂贸wna pozycja, pozycja alternatywna, osi膮gni臋cia, 艁膮czy nas pi艂ka, j臋zyki) powinny mie膰 znaki ograniczone do liter.                 Dodatkowo wszystkie te pola, pr贸cz imienia i nazwiska) powinny mie膰 zdefiniowane listy wyboru.

  -  2.4.3 Pola ( Profil facebook, link do youtube) powinny mie膰 zdefiniowany schemat podawania adres贸w, np.: www.facebook.com/xxxxx

  -  2.4.4 Pola wagi i wzrostu ograniczy膰 do 3 dodatnich cyfr. 
 
  -  2.4.5 Pole "telefon" zdefiniowa膰 tylko do cyfr i w okre艣lonym schemacie, np: 111 222 333

  -  2.4.6 Rok urodzenia mo偶naby ograniczy膰 od 1900 w g贸r臋.

3 MECZE

3.1 Wi臋kszo艣膰 p贸l musi mie膰 dok艂adnie zdefiniowane warto艣ci, jakie mo偶e przyj膮膰:

  -  3.1.1 W polach "zdobyte gole", "stracone gole" warto zrobi膰 rozwijan膮 list臋 z liczb膮 goli. Teraz mo偶na wpisywa膰 kilkucyfrowe warto艣ci.
    
  -  3.1.2 Pola "Web match" i "General" nie zosta艂y przet艂umaczone
    
  -  3.1.3 Dat臋 te偶 warto ograniczy膰 do kilku lat wstecz
    
  -  3.1.4 Pola "kolor koszulki" i "Liga" powinny mie膰 rozwijane menu wyboru. Teraz mo偶na wpisywa膰 wszystkie mo偶liwe znaki.
    
  -  3.1.5 Pole "numer" ograniczy膰 do dodatnich warto艣ci

4 GRACZE

4.1 Nie wiem czy to kwestia przegl膮darek ( Opera i Chrome), ale w opcji drukowania strony nie mo偶na ustawi膰 widoku na wszystkie kategorie


   ![Lista graczy drukowanie](https://user-images.githubusercontent.com/39927014/212984403-02d6847d-4801-4e86-8c83-b028cc147307.jpg)

4.2 W eksportowanym pliku tableDownload.csv w unicode (UTF-8) kolumny "mecze" i "raporty zawieraj膮 dziwne dane.

![tableDownload](https://user-images.githubusercontent.com/39927014/212985667-b14e629c-97e9-4ebf-a8ea-7f5b9dc0286c.jpg)

<sub>UWAGA: Testy wykonano na systemie Windows 10 ( wersja 22H2, kompilacja 19045.2486), przegl膮darka Opera w wersji 94.0.4606.38</sub>

# **Task 2** - Test cases

## Subtask 1 - Pisanie przypadk贸w testowych na podstawie User Story.

https://docs.google.com/spreadsheets/d/1k2VSX9ljLJZ7DYsGkprwYF0FLrvy9BQv/edit?usp=sharing&ouid=109741062900965762182&rtpof=true&sd=true

## Subtask 2 - Pisanie przypadk贸w testowych na podstawie 鈥渨艂asnych do艣wiadcze艅

https://docs.google.com/spreadsheets/d/1iaY3haq1NTlCmZ-9KnFvkYug221VI_nI/edit?usp=sharing&ouid=109741062900965762182&rtpof=true&sd=true

## Subtask 3 - Po co piszemy test case鈥檡?


![friends-american-sitcom](https://user-images.githubusercontent.com/39927014/216820030-26c94370-4a4f-481d-99ad-caab82a7d675.gif)

* Lepsza kontrola nad tym, co jest do przetestowania. Gwarancja, 偶e 偶adna funkcjonalno艣膰 nie zostanie pomini臋ta.
* Wykrywaj膮 b艂臋dy logiczne w historyjkach u偶ytkownika i aplikacji
* wychwycenie b艂臋d贸w przed wyposzczeniem produktu do eksploatacji
* Pokrycie przypadkami testowymi jak najwi臋kszej ilo艣ci funkcjonalno艣ci aplikacji zmniejszamy szanse wyst膮pienia powa偶niejszych b艂臋d贸w
* Numeracja i zwi臋z艂e nazewnictwo ka偶dego przypadku testowego u艂atwia poruszanie si臋 mi臋dzy nimi
* Dobrze napisana lista przypadk贸w testowych mo偶e by膰 przejmowana przez kolejne osoby
  
# **Task 3** - Raportowanie b艂臋d贸w
  
## Subtask 1 - Utworzenie formatki do zg艂aszania b艂臋d贸w systemu
  
  https://docs.google.com/spreadsheets/d/1Vyvnd0yYJ1A1et3lduxvTJqAHTJ1ontK/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true
  
## Subtask 2 - Testowanie wed艂ug plan贸w test贸w i raportowanie b艂臋d贸w
  
  * Based on User story Test Cases
  https://docs.google.com/spreadsheets/d/1onzTMEpjXXKKY03y5fct-EDPGlEdXRMg/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true
  
  * Based on experience tests
  https://docs.google.com/spreadsheets/d/1eHD6XdmwG53eR9U0crZM2ilYy2-0Wa_a/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true
  

## Subtask 3 - Raport z wykonanych test贸w
  
 https://docs.google.com/spreadsheets/d/1TKrXUbD2A5wnBecPmASfipWVhc2RNm5O/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true

# **Task 4** - Testowanie aplikacji mobilnych - OLX 馃洅

## Subtask 2 - Testowanie eksploracyjne i raportowanie b艂臋d贸w

https://docs.google.com/spreadsheets/d/1OkxMtNMAAsOoR7k3GUrkIO2ZBUxR2BIc/edit?usp=share_link&ouid=109741062900965762182&rtpof=true&sd=true
  
## Subtask 3 - Do czego s艂u偶y ta aplikacja?
  Aplikacja OLX s艂u偶y do zamieszczania og艂osze艅 dotycz膮cych kupna/sprzeda偶y rzeczy lub us艂ug.馃憸  U偶ytkownikami aplikacji s膮 osoby planuj膮ce zakup konkretnych produkt贸w lub us艂ug.
  
  Aplikacja, pomimo skromnego interfejsu, jest przyjazna i czytelna dla u偶ytkownika. Pasek menu jest na dole, co u艂atwia obs艂ug臋 kcuikiem.馃憤 Kafelki z og艂oszeniami mog艂y by by膰 dla czytelno艣ci bardziej odseparowane od siebie. W kategorii "Motoryzacja" jest zdecydowanie za ma艂o filtr贸w wyszukiwania lub s膮 gdzie艣 ukryte.馃憥 Brak przebiegu auta, rodzaju paliwa, pojemno艣ci silnika itd:

https://user-images.githubusercontent.com/39927014/217283892-2bb52cc1-8274-498f-a003-eec7cf3a297e.mp4
  
  Testowanie aplikacji natywnej r贸偶ni si臋 od testowania aplikacji internetowej.馃摫馃枼馃捇馃摬 Wynika to z tego, 偶e obs艂uga telefonu/tabletu jest prostsza i mniej precyzyjna w por贸wnaniu do obs艂ugi komputera. Kursorem i myszk膮 na du偶ym ekranie jeste艣my w stanie wykonywa膰 bardziej skomplikowane operacje ni偶 palcami na telefonie. Dlatego te偶 aplikacje natywne musz膮 by膰 dostosowane do tego typu prostej obs艂ugi. Dodatkowo w aplikacjach mobilnych testowaniu podlega ich responsywno艣膰 w pionowym uk艂adzie ekranu i poziomym. 


# **Task 5** - SQL part 1

## Subtask 1 - Kr贸tki kurs podstaw SQL

- SELECT * FROM

- CREATE TABLE <table_name>
  
- SELECT * FROM <XYZ> ORDER BY <Name>
  
- SELECT * FROM <XYZ> WHERE
  
## Subtask 3 - Kilka zada艅 na rozgrzewk臋
  
### 1. Wy艣wietl tabel臋 actors w kolejno艣ci alfabetycznej sortuj膮c po kolumnie surname.
  
  SELECT * FROM `actors` ORDER by surname
  
  ![1](https://user-images.githubusercontent.com/39927014/218466942-74e6ee19-60d6-42b9-9048-8516d03223ae.jpg)

### 2. Wy艣wietl film, kt贸ry powsta艂 w 2019 roku.
  
  SELECT * FROM `movies` WHERE year_of_production = '2019'
  
  ![2](https://user-images.githubusercontent.com/39927014/218469509-be1ea41b-9752-490b-b949-cba9e840d956.jpg)

### 3. Wy艣wietl wszystkie filmy, kt贸re powsta艂y mi臋dzy 1900, a 1999 rokiem.
  
  SELECT * FROM `movies` WHERE year_of_production BETWEEN 1900 and 1999
  
  ![3](https://user-images.githubusercontent.com/39927014/218470441-70ee600d-0b5c-469c-a79e-15a06947527b.jpg)

### 4. Wy艣wietl JEDYNIE tytu艂 i cen臋 film贸w, kt贸re kosztuj膮 poni偶ej 7$
  
  SELECT title, price FROM `movies` WHERE price < 7
                                                   
                                                   
  ![4](https://user-images.githubusercontent.com/39927014/218471633-4b693b48-2079-4461-92e1-cda26e571ea4.jpg)
  
### 5. U偶yj operatora logicznego AND, aby wy艣wietli膰 aktor贸w o actor_id pomi臋dzy 4-7 (4 i 7 powinny si臋 wy艣wietla膰). NIE U呕YWAJ operatora BETWEEN.
   
  SELECT actor_id, name FROM `actors` WHERE actor_id >= 4 AND actor_id <= 7
                                                                          
  ![5](https://user-images.githubusercontent.com/39927014/218473318-9fe6833d-1958-465d-8757-743449dbee4c.jpg)

### 6. Wy艣wietl klient贸w o id 2,4,6 wykorzystaj do tego warunek logiczny.
  
  SELECT customer_id, name FROM `customers` WHERE customer_id%2 = 0                                                                        
 
  ![6](https://user-images.githubusercontent.com/39927014/218480130-e535cec1-4394-49a0-923d-0fc0daa9f25f.jpg)
                                                          
### 7. Wy艣wietl klient贸w o id 1,3,5 wykorzystaj do tego operator IN.                                                                          
                                                                          
  SELECT customer_id, name FROM `customers` WHERE customer_id IN (1, 3, 5)                                                                     
  
  ![7](https://user-images.githubusercontent.com/39927014/218480404-2078bcec-8f4a-42ad-a56b-59d067d84b38.jpg)

### 8. Wy艣wietl dane wszystkich os贸b z tabeli 鈥榓ctors鈥?, kt贸rych imi臋 zaczyna si臋 od ci膮gu 鈥淎n鈥?.
                                                                          
  SELECT * FROM `actors` WHERE name LIKE 'An%'      
                                                                          
  ![8](https://user-images.githubusercontent.com/39927014/218481295-d47fc7c5-b881-418d-b132-123afc17b9c9.jpg)
                                                                
### 9. Wy艣wietl dane klienta, kt贸ry nie ma podanego adresu email.
                                                                          
   SELECT * FROM `customers` WHERE email IS null
                                                                          
   ![9](https://user-images.githubusercontent.com/39927014/218481682-a5a45eda-2757-4eb0-bf16-44c47e68e654.jpg)
                                                                       
### 10. Wy艣wietl wszystkie filmy, kt贸rych cena wynosi powy偶ej 9$ oraz ich ID mie艣ci si臋 pomi臋dzy 2 i 8 movie_id.                                                 
                                                                          
  SELECT * FROM `movies` WHERE price > 9 AND movie_id BETWEEN 2 AND 8
  
  ![10](https://user-images.githubusercontent.com/39927014/218482850-f26d608c-67cf-4198-9ace-d75e78464efa.jpg)

  
# **Task 6** - SQL part 2
  
  ## Subtask 1 - Kr贸tki kurs podstaw SQL
  
  ### 11. Pope艂ni艂am b艂膮d wpisuj膮c nazwisko Ani Miler 鈥? wpisa艂am Muler. Znajd藕 i zastosuj funkcj臋, kt贸ra poprawi m贸j karko艂omny b艂膮d
  
  UPDATE customers SET surname = 'Miler' WHERE customer_id = 3;
  
  ![1](https://user-images.githubusercontent.com/39927014/219633920-4107af14-72ea-46a9-8ccb-ec27d8914fa7.jpg)

 ### 12. Pobra艂am za du偶o pieni臋dzy od klienta, kt贸ry kupi艂 w ostatnim czasie film o id 4. Korzystaj膮c z funkcji join sprawd藕, jak ma na imi臋 klient i jakiego ma maila. W celu napisania mu wiadomo艣ci o pomy艂ce fantastycznej szefowej.
  
  
  SELECT customers.name, customers.email
  
FROM customers
  
INNER JOIN sale ON customers.customer_id=sale.customer_id
  
WHERE sale.movie_id=4
   
  ![12](https://user-images.githubusercontent.com/39927014/219645559-70b9fcbc-7a99-490f-ae24-2c6213308d6e.jpg)

### 13.  Na pewno zauwa偶y艂_艣, 偶e sprzedawca zapomnia艂 wpisa膰 emaila klientce Patrycji. Uzupe艂nij ten brak wpisuj膮c: pati@mail.com
  
  UPDATE customers SET email = 'pati@mail.com' WHERE customer_id = 4
    
  ![13](https://user-images.githubusercontent.com/39927014/219651943-61a30a04-c338-4ebd-b091-b270e9cac551.jpg)

### 14.   Dla ka偶dego zakupu wy艣wietl, imi臋 i nazwisko klienta, kt贸ry dokona艂 wypo偶yczenia oraz tytu艂 wypo偶yczonego filmu. (wykorzystaj do tego funkcj臋 inner join, zastan贸w si臋 wcze艣niej, kt贸re tabele Ci si臋 przydadz膮 do wykonania 膰wiczenia).
  
  SELECT customers.name, customers.surname, movies.title
  
  FROM customers
  
  INNER JOIN sale ON sale.customer_id=customers.customer_id
  
  INNER JOIN movies ON movies.movie_id=sale.customer_id
  
  ![14](https://user-images.githubusercontent.com/39927014/219687964-ca9a4f68-d52f-4220-a310-d43450f4aaa6.jpg)

 ### 15. W celu anonimizacji danych, chcesz stworzy膰 pseudonimy swoich klient贸w. - Dodaj kolumn臋 o nazwie 鈥榩seudonym鈥? do tabeli customer,- Wype艂nij kolumn臋 w taki spos贸b, aby pseudonim stworzy艂 si臋 z dw贸ch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling 鈫? Nag
  
  - ALTER TABLE customers ADD pseudonym varchar(255);
  
  
  ![15a](https://user-images.githubusercontent.com/39927014/219698871-46dd2ddc-8178-4096-ab5c-b1f6f65d7b79.jpg)

  
  - UPDATE customers
    SET pseudonym=(SELECT concat(LEFT(name, 2), RIGHT(surname, 1)))
  
  ![15b](https://user-images.githubusercontent.com/39927014/219947004-d7acf10f-d0dc-49b8-b6ad-2ac91074f706.jpg)

  
### 16. Wy艣wietl tytu艂y film贸w, kt贸re zosta艂y zakupione, wy艣wietl tabel臋 w taki spos贸b, aby tytu艂y si臋 nie powtarza艂y.
  
  SELECT DISTINCT movies.title 
  FROM sale
  INNER JOIN movies ON movies.movie_id=sale.movie_id;
  
  ![16](https://user-images.githubusercontent.com/39927014/219948318-22c1aeee-6a90-48c8-8c16-268996f792ad.jpg)

### 17. Wy艣wietl wsp贸ln膮 list臋 imion wszystkich aktor贸w i klient贸w, a wynik uporz膮dkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)
  
  SELECT name FROM actors
  UNION
  SELECT name FROM customers
  ORDER BY name
  
  ![17](https://user-images.githubusercontent.com/39927014/219948645-b48ea9cd-eb54-411d-b49c-dc7e29faa3b9.jpg)

  
### 18. Polsk臋 opanowa艂a inflacja i nasz sklepik z filmami r贸wnie偶 dotkn膮艂 ten problem. Podnie艣 cen臋 wszystkich film贸w wyprodukowanych po 2000 roku o 2,5 $ (Pami臋taj, 偶e dolar to domy艣lna jednostka- nie u偶ywaj jej nigdzie).
  
  UPDATE movies
  SET price=price + 2.5
  
  ![18](https://user-images.githubusercontent.com/39927014/219948892-ded93e61-8f36-4fd9-bded-75f1d30afcd2.jpg)

### 19. Wy艣wietl imi臋 i nazwisko aktora o id 4 i tytu艂 filmu, w kt贸rym zagra艂
  
  SELECT actors.name, actors.surname, movies.title
  FROM actors
  INNER JOIN cast ON cast.actor_id=actors.actor_id
  INNER JOIN movies ON movies.movie_id=cast.movie_id
  WHERE actors.actor_id=4
  
  ![19](https://user-images.githubusercontent.com/39927014/219949431-74fc4176-d197-4cd5-88ee-22683c644226.jpg)

  
### 20. A gdzie nasza HONIA!? Dodaj do tabeli customers now膮 krotk臋, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa
  
  INSERT INTO customers (customer_id, name, surname, email) 
  VALUES ( 7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com');
  UPDATE customers SET pseudonym=(SELECT concat(LEFT(name, 2), RIGHT(surname, 1)))
  
  ![20](https://user-images.githubusercontent.com/39927014/219951683-fb99e489-0812-4ff4-b5d2-95e4226c78d8.jpg)

## Subtask 2 - Test
  
  wynik -7

## Subtask 3 - Tworzymy portfolio
  
  https://github.com/mygapix/PORTFOLIO-MaksymilianMyga
