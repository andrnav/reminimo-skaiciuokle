# Rėminimo skaičiuoklė

Paprasta lietuviška rėminimo skaičiuoklė, veikianti naršyklėje. Naudoja tik HTML, CSS ir JavaScript.

## Paleidimas kompiuteryje
Atidarykite `index.html` naršyklėje.

## Įkėlimas į GitHub Pages
1. GitHub sukurkite naują repository, pvz. `reminimo-skaiciuokle`.
2. Įkelkite `index.html` į repository šakninį katalogą (root).
3. Atidarykite **Settings → Pages**.
4. Prie **Build and deployment** pasirinkite **Deploy from a branch**.
5. Branch pasirinkite `main`, katalogą `/ (root)`, spauskite **Save**.
6. Palaukite, kol GitHub Pages paskelbs svetainę. Adresas bus panašus į `https://JUSU-VARDAS.github.io/reminimo-skaiciuokle/`.

## Ar reikia Cloudflare duomenų bazės?
Ne, dabartinei versijai nereikia nei duomenų bazės, nei serverio funkcijų. Visi skaičiavimai atliekami lankytojo naršyklėje. GitHub Pages pakanka.

Cloudflare Pages taip pat galima naudoti statiniam puslapiui. D1 duomenų bazė būtų reikalinga tik vėliau, jei norėtumėte saugoti užsakymus, klientų duomenis, kainoraščius ar kelis išsaugomus projektus tarp įrenginių.

## Svarbi skaičiavimo pastaba
Dabartinis prototipas skaičiuoja pasporto ir stiklo plotą pagal darbo dydį su pasportu, kai pasportas įjungtas. Bageto ilgis skaičiuojamas pagal perimetrą ir pasirinktą kampų priedą. Prieš naudojant gamybai patikrinkite šias taisykles pagal realią dirbtuvės praktiką.
