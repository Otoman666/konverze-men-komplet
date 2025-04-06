# Purple Technology - Currency Converter Project

Druhá verze (kompletní) – [ExchangeRate.host API](https://www.exchangerate-api.com/)
Přešel jsem na jinou platformu, která umožňuje přímý převod mezi libovolnými dvěma měnami (např. USD → CZK)
https://api.exchangerate.host/convert?from=USD&to=CZK&amount=100

Navíc jsem celou aplikaci rozšířil o:
- Node.js backend, který zajišťuje volání na ExchangeRate API,
- ukládání historie převodů do souboru history.json,
- zobrazování statistik – počet převodů, nejčastější cílová měna a součet částek převedených do CZK,

Spuštění:
Krok 1:
Naklonuj si repozitář https://github.com/Otoman666/Purple-currency-converter-completely.git

Krok 2:
V terminálu spusť: 
npm install
node server.js

Krok 3:
Backend poběží na http://localhost:3000.

Krok 4:
Otevři index.html pomocí file:///... (nepoužívej Live Server).

Krok 5:
Zadej částku, vybírej měny a potvrď tlačítkem – částka se odešle na backend, výsledek a statistiky se zobrazí.

[Made by Otto Hyncica 2025]
