# DriveEasy Frontend

Interface de démonstration HTML/CSS/JavaScript, publiée séparément du backend Spring Boot.

## Démarrer en local

1. Dans un terminal, démarrer le backend depuis son dépôt avec `.\run-driveeasy.ps1`.
2. Dans un autre terminal, depuis ce dossier, lancer le serveur statique :

   ```powershell
   python -m http.server 4200
   ```

3. Ouvrir <http://localhost:4200>.

Le frontend appelle la Gateway à <http://localhost:8080>. Le backend autorise l'origine `http://localhost:4200`.
