# challenge_portfolio_Maks
# **Task1**
## Subtask 1
7 punktów
## Subtask 3
Cześć! Jestem Maks 🙂 Szukałem kursu stawiającego na zadania praktyczne i nie za miliony monet 😉 Poza względami praktycznymi zależy mi na zapoznaniu się z grubsza na specyfice zawodu testera, jak to może wyglądać na co dzień itd. 

Wiedza i doświadczenie tu nabyte pozwolą mi zweryfikować, czy nadaję się na to stanowisko 😄
#### **_Maks_**

## Subtask 4
#### **_OPIS STRONY_**
Aplikacja Scouts Panel polega na dodawaniu skautów piłki nożnej. Służy ona do monitorowania pozycji i umiejętności zawodników.
Dostęp do strony wymaga posiadania profilu, logowanie odbywa się za pomocą loginu i hasła. 

Na stronie głównej na samej górze jest niebieski pasek z nazwą strony. Niżej po lewej mamy pionowe pole nawigacyjne. W górnej części głównego okna są obok siebie kafelki ze statystykami (ilość graczy, meczy, raportów i akcji). Poniżej mamy kafelek panelu zarządzania graczami, meczami i do tworzenia raportów. Pod linkami pomocniczymi jest opcja "dodaj gracza". Po prawej stronie okno z ostatnimi akcjami wykonanymi na stronie.

#### **_UWAGI DO INTERFEJSU_**

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

#### **_UWAGI EKSPLORACYJNE_**

STRONA GŁÓWNA
* brak uwag

DODAJ GRACZA

1. Podczas wpisywania w osiągnięciach znaków specjalnych skasowało mi wcześniej wypełnione pola - jednorazowy przypadek
2. Po wpisaniu , gdzie to możliwe, randomowych liter cyfr i znaków specjalnych i zatwierdzeniu gracza wyświetla się na moment informacja "nie udało się dodać gracza". Nie ma żadnej informacji w których polach dane zostały źle wprowadzone.

![błąd dodawanie gracza](https://user-images.githubusercontent.com/39927014/212338306-f32a8cbf-eb38-4c97-97ee-1738c5140fef.jpg)

3. Po wprowadzeniu poprawnych danych udaje się zapisać gracza

![poprawne dodanie gracza](https://user-images.githubusercontent.com/39927014/212340016-3339ebf3-eb0c-44f5-9a09-9f0fcce0fb73.jpg)

\4. Większość pól musi mieć dokładnie zdefiniowane wartości, jakie może przyjąć: 
  4.1 Na przykład pole mejlowe musi mieć zdefiniowany prefix mejla do 2 lub 3 znaków (pl, com)
  4.2 f
    

<sub>UWAGA: Testy wykonano na systemie Windows 10 ( wersja 22H2, kompilacja 19045.2486), przeglądarka Opera w wersji 94.0.4606.38</sub>
