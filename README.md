*** Oman projektin frontend ***

Jos haluat pyörittää fronend esimerkkiä lokaalisti ilma json tietokantaa niin voit käyttää tällöin vain komentoa 
npm run dev komentoa. Jos haluat käyttää esimerkki tietokantaa niin aja terminaalissa (projekti kansiossa) alta löytyvä
komento jolla servesi lähtee käyntiin ja anna tässä kappaleessa oleva komento vaikka visual studiossa niin saat 
frontendin ja serverin käyttöön.

*** Käytetyt komennot projektin luonnissa: ***

1. npm create vite@latest 'PROJEKTIBN NIMI TÄSSÄ' -- --template react
2. npm install
3. npm install axios
4. npm install json-server --save-dev

*** Lokaalin JSON serverin käynnistys: ***

npm run server TAI npx json-server --port=3001 --watch DB.json

Oletusarvoisesti JSON Server käynnistyy porttiin 3000. Koska Vitellä luodut projektit varaavat jo portin 3000, käytämme nyt kuitenkin porttia 3001.

*** Buildin tekeminen webistä ***

Komento: npm run build
Komento jolla Dist voidaan siirtää suoraan backend alle (kopioituna): cp -r dist ../backend