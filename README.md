#PO

1. a 2.
Cieľom projektu je vytvoriť aplikáciu správy ambulantnej čakárne:

Aplikáciu môžu používajú dve persóny: Pacient, a Ambulantná sestra

* Pacient
    * Ako pacient chcem, aby som po príchode do čakárne zadal svoje rodné číslo (alebo číslo pacienta) a aby ma následne systém zaradil do poradia čakajúcich. Chcem, aby mi systém oznámil moje poradie a orientačnú dobu, kedy budem vyšetrený.
    * Ako pacient s akútnym ochorením - napr. úraz, vysoká teplota, tehotenstvo - a nárokom na prednostné ošetrenie chcem, aby som po príchode do čakárne zadal svoje rodné čislo (alebo číslo pacienta) a aby ma následne systém zaradil do zoznamu čakajúcich s prednostným ošetrením.
    * Ako pacient čakajúci v ambulancii chcem mať vizuálny prehľad o aktuálnom stave môjho poradia.
* Ambulantná sestra
    * Ako setra ambulancie chcem mať prehľad o počte a identite čakajúcich pacientov a ďalšom pacientovi v poradí.
    * Ako sestra ambulancie chcem vedieť koľko a ktorí pacienti čakajú na lekárske vyšetrenie, ktorí čakajú na prednostné ošetrenie, a ktorí čakajú na vybavenie administratívneho úkonu.
    * Ako sestra ambulancie, v prípade posúdenia vážneho stavu pacienta, chcem mať možnosť zmeniť poradie čakajúcich.

3.
Technické ohraničenie:
FE: Angular alebo Vue
BE: C# s použitím knižnice ASP.NET Core (Prípadne Java Spring)
DB: lokálna databáza LiteDB. (V prípade C#)

4.
Časový plán:
1. Dodefinovanie analýzy z biznisových požiadaviek.   - 3h
2. Inštalácia všetkých potrebných technológií, Vytvorenie dummy FE A BE, ktoré spolu komunikujú    - 3h
3. Definícia REST rozhrania (Swagger, Postman)     - 3h
4. Vytvorenie LiteDB, komunikácia s .NET Core a jej inicializácia (naplnenie dát) -3h
5. FE - Navigácia Aplikácie | Komponenta pre Poradie Pacientov (otestovanie, riešenie vedľajších efektov) - 4h
6. FE - Komponenta pre Konkretneho pacienta (otestovanie, riešenie vedľajších efektov) - 3h
7. FE - Vytvorenie a Editácia pacienta (riešenie vedľajších efektov) - 3h
8. BE - Základna logika a presistencia údajov - 3h 
9. BE - Integrácia web služby s UI,otestovanie end-pointov (napr. cez Postman) - 3h
10. Kontejnarizácia aplikácie - 3h
