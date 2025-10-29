# Bazy danych, informatyka, studia stacjonarne, semestr 2025Z

## SQL. Tworzenie, aktualizacja oraz usuwanie tabel. Wstawianie, aktualizacja i usuwanie danych z tabeli


### Zadanie 1
Usuń dwa najstarsze projekty ale nie mogą być to projekty które nie mają daty zakońćzenia 
1. Uśmierć dwóch najstarszych wikingów, ale to nie może być Bjorn `(DELETE z WHERE)`
2. Usuń klucz główny z tabeli `postac` - może być potrzebnych kilka komend (np. odłączenie kluczy obcych)

### Zadanie 2
1. Do tabeli `postać` dodaj pole pesel składające się z 11 znaków i ustaw to pole na klucz główny
2. W tabeli `postać` zmień pole rodzaj, tak, aby możliwe było dodanie syreny
3. wstaw do tabeli `postać` syrenę o nazwie Gertruda Nieszczera

### Zadanie 3
1. Wszystkie postacie, które mają w swojej nazwie 'a', wsadź na statek Bjorna
2. Zmniejsz ładowność wszystkim statkom o 30%, których data wodowania była w XX wieku
3. Ustaw warunek sprawdzający czy wiek postaci nie jest większy od 1000

### Zadanie 4
1. Do `postaci` dodaj węża Loko, tylko nie wsadzaj go na statek
2. Stwórz nową tabelę na podstawie tabeli `Postacie` (dokładnie takie same pola), nazwij ją `Marynarz` - wrzuć do tej tabeli wszystkie postacie które mają zdefiniowany statek
3. dostosuj odpowiednio klucze główne i obce

### Zadanie 5
1. Wysadź wszystkich ze statku
2. uśmierć jednego wikinga
3. zniszcz wszystkie statki
4. usuń tabelę `statek`
5. stwórz tabelę `zwierz` z polami id - klucz główny samo zwiększający się, nazwa - ciąg znaków, wiek - liczba
6. przekopiuj z tabeli `postac` wszystkie zwierzaki
