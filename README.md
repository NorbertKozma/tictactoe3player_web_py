# Lépésajánló algoritmusok bemutatása a Tic-Tac-Toe játék többszemélyes változatán keresztül

A projekt keretén belül megvalósult egy kiterjesztett kettőnél több játékos Tic-Tac-Toe logikai játék szabályrendszere, állapottérreprezentációja, heurisztikája, a gépi játékosok implementálása.

## Fő funkciók

Az elkészült projektben vizsgálni tudjuk a Paranoid, Maxn^n, BRS és az MP-mix lépésajánló algoritmusok működését, egymás elleni hatékonyságukat változtatható mélységkorláttal, támadó- és védőküszöbértékekkel, valamint lépéssorrenddel.

Játszhatunk két gépi ellenfél ellen, vagy akár versenyeztethetjük is egymás ellen a döntési szabályokat. Teszt játékmódban pedig egy tetszőleges csomópontot hozhatunk létre, amin célzottan vizsgálhatjuk az egyes stratégiák működését.

## Gombfunkciók

### Delete
Törli a játékállás pontszámait és üres táblát állít be.

### Start Test
A tetszőlegesen megadott csomóponthoz a három játékos a beállított paraméterek mellett végig játssza a játékot.

### Start
A beállított paramétereknek megfelelően indítja el a játékot.

## Játékmódok

### Player(X) vs AI(O) vs AI(Δ)
A funkció arra való, hogy lehessen játszani két gépi játékos ellen, így közvetlenül tapasztaljuk meg, hogy milyen nehéz a különböző többjátékos stratégiák ellen játszani. Be lehet állítani a keresési mélységkorlátot, a webalkalmazásnál ez az érték korlátozva van, elkerülve a több órát is elérhető válaszlépési időt. A játékban mindig az emberi játékos kezd az X szimbólummal. Kiválasztható külön-külön, hogy a gépi játékosok milyen döntési szabályt használjanak és szabályozhatjuk a nehézségi szintet a keresési mélységkorláttal.

### AI(X)vs AI(O) vs AI(Δ)
Funkció feladata, változtatható paraméterek mellett a különböző lépésajánlók összehasonlítása. A választható döntési szabályok a következők lehetnek: paranoid, maxn, BRS, mp-mix.

### Test
A teszt funkcióban a három játékos szimbólumait lehet elhelyezni a pályán egymás után, így beállítani egy tetszőleges játék állapotot, majd letesztelni a végeredményt előre megadott stratégiákkal. Ezáltal célzottan létrehozhatóak és vizsgálhatóak az egyes stratégiák, olyan körülmények mellett, amelyek máshogy nem, vagy csak nehezen jönnének létre.

## Játékidő

A játékidő beállítása arra szolgál, hogy meghatározzuk egy-vagy tizenhat játszmát szeretnénk.

## Technológiák

### Frontend

- HTML5
- CSS3
- JavaScript (ES6)

## Konzol alkalmazás
- Python 3 


## Szerző

Készítette: Kozma Norbert