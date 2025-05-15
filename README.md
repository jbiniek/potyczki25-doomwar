# Operacja Doom War

## _Misja specjalna_

Twoim celem jest zdobycie danych z Rosyjskich serwerów (t.j. z serwerów pozostałych drużyn). Zdobycie jest uznawane za pomyślne jeśli poznasz, w dowolny sposób, kod z któregoś z pozostałych stanowisk i zamieścisz go w rozwiązaniu. Każdy zespół ma unikalne tajne dane. Zdobycie wrogich danych jest warte __+30 punktów__ _za każdego wroga_.

Jednocześnie musisz chronić własne zasoby. Jeśli którakolwiek z wrogich służb przechwyci twoje tajne dane, będzie to katastrofą kosztującą __-50 punktów__.

Żeby nie było zbyt łatwo, musicie opublikować swój tajny kod na swoim środowisku:
- utworzyć namespace "secret-code"
- uruchomić w tym namespace dowolną usługę web (apache, wordpress, itp.), dostępną z całego klastra, wyświetlającą tajny kod
- Kod musi być wyświetlany czytelną czcionką szeryfową, np. Times New Roman (domyślna w większości przeglądarek), oraz w rozmiarze H1 (minimum 24pts)
- usługa musi przeżyć wrogi atak na naszą infrastrukturę (t.j. restart maszyny - na koniec potyczek wszystkie serwery zostaną jednocześnie wyłączone i będą sprawdzane dopiero po ponownym uruchomieniu)
Rozwiązaniem jest adres usługi, pod którym będzie wyświetlana strona zawierająca tajny kod. Brak publikacji kodu rownoznaczny jest z niepowodzeniem misji **(-50 pkt)**.

To zadanie nie jest objęte żadnymi dodatkowymi regułami - __liczy się tylko fakt uzyskania bądź utraty danych__, nieważne w jaki sposób. O przyznaniu (lub odjęciu) punktów decyduje tylko obecność odpowiedniego łańcucha znaków w repo będącym rozwiązaniem.

_Apeluję o podejmowanie legalnych działań_ - aczkolwiek sposób zdobycia danych i jego legalność nie będzie oceniana. Wśród członków drużyn, którzy nie stracą swoich danych, a pomyślnie przechwycą wrogie dane oraz podzielą się opisem metody ataku wylosowana będzie nagroda dodatkowa w postaci mojego ulubionego komiksu (kompletny cykl Doomwar #1-6 wydanie brytyjskie, stan bdb-). Wszyscy z nich otrzymają też honorowy tytuł "Doombringer", którym powinniście się chwalić jeśli chcecie, żeby dziewczyny was unikały.
