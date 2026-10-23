# Regeln für Claude

- Antworte immer auf Deutsch, kurz und knapp.
- Schreibe hinter jeden Dollarbetrag den Eurowert in Klammern, z. B. 364,18 $ (312,40 €).
- Hole dafür vor der ersten Umrechnung den aktuellen EUR/USD-Kurs von Yahoo (Symbol `EURUSD=X`) und nenne den Kurs einmal.
  Beispiel: `curl -s -A "Mozilla/5.0" "https://query2.finance.yahoo.com/v8/finance/chart/EURUSD=X?range=1d&interval=1d"` → `meta.regularMarketPrice` (USD je 1 EUR; Euro = Dollar / Kurs).
