CSN Flödesschema Registeringssystem

1. Användaren registrerar sig på CSN:s webbplats.
2. Datan skickas via HTTP/HTTPS förfrågan till ett API (om man har ett api)
3. API tar emot datan och skickar till webbservern.
4. webbservern kontrollerar datan och sparar i databasen.
5. Databasen skickar bekräftelse/resultat tillbaka webbservern.
6. Webbserver skickar svaret vidare tillbaka till API. 
7. API Skickar svaret till frontend (CSN). 
8. Beroende på resultat så lyckas man med registerationen eller ej.
