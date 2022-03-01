# scratch_hazi

Az általam elkészített játékban egy fáról lehulló almákat kell elkapni egy tál segítségével.
A játékos feladata, hogy 25 almát összeszedjen. Ha ezt eléri, nyert.

Az alma kódja a következőképp néz ki:
Az alma a x tengelyen felvesz egy véletlenszerű pontot, onnan kezd el lefelé esni. 
Amikor az alma érintkezik a tállal, egy koppanó hangot ad ki, valamint a pontszámot megnöveli eggyel. 
Abban az esetben, ha a pontszám eléri a szükséges 25-öt, jelzi, hogy sikeresen teljesítettük a küldetést. 

![image](https://user-images.githubusercontent.com/82056989/156264922-795860a7-e8a0-41d3-afd8-127aaca2b58a.png)

A tál kódja valamivel egyszerűbb:
A játék indulásakor lenullázza a pontszámot, ezt követően pedig a játékos a jobbra és balra nyilakkal irányíthatja azt a képernyő alján.

![image](https://user-images.githubusercontent.com/82056989/156265475-46a82b91-ed10-4a9e-b1d5-3489e9576dd3.png)

A harmadik és egyben utolsó sprite egy egyszerű felirat.
Ez a játék kezdetekor még rejtve van, azonban mikor elérjük a szükséges 25 pontot és az almához tartozó kódtól megkapja a jelzést
a győzelemről, minden más sprite futását leállítja és megjelenik a "Nyertél!" felirat.

![image](https://user-images.githubusercontent.com/82056989/156265702-3c5a46ad-2ee0-4477-b5db-8eb7c09405b5.png)

