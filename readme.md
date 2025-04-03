## Ez a MÁV utastájékoztató tanuló verziója

Ez a projekt induló és érkező vonatok megjelnítését biztosítja. Az oldal a **html** és **css** segíségével készült. A táblázatba láthatod az információkat.

### ✏️ Jellemzők
- Induló és érkező vonatok listája.
- Vonatok időpontbeli érkezése, indulása és késését mutatja a táblázat.
- Sima, egyszerű és letisztult dizájn.

### ⚒️ Használat
Nyisd meg a https://czombosnoel.github.io/2025_01_30_MAV_utastejekoztato/ linken lévő weboldalt a böngészőben, és láthatod a táblázatot és az abban lévő információkat.

### 🖥️ Élő demó

A projekt megtekinthető az alábi linken:
[MÁV utastájékoztató](https://github.com/czombosnoel/2025_01_30_MAV_utastajekoztato.git).

### 📌 Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="hu">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>MÁV utastájékoztató</title>
        <link rel="stylesheet" href="styles.css">
    </head>
```


### 📌 Alap CSS szerkezet table
```css
table   {
            border: 1px solid;
            background-color: rgb(34, 153, 34); /* betűszín */
            color: white;
            font-family: 'Courier New'; /* betűtipus */
            font-size: 30px; /* betűméret */
        }
  ```

### 🔧 Fejlesztési lehetőségek
- [ ] 🔁 Dinamikus betöltés API-n keresztül.
- [ ] 🔎 Keresési vagy szűrési lehetőség.
- [x] 📱 Megfelelő megjelnítés különbözö mobil eszközön is.
