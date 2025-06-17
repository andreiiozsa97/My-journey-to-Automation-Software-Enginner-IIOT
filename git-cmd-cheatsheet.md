
# Ghid comenzi CMD și Git – IIoT Software Engineer

## 🖥️ Comenzi CMD (Command Prompt - Windows)

| Comandă                  | Descriere                                          |
|--------------------------|----------------------------------------------------|
| `cd folder`             | Intri în folderul specificat                       |
| `cd ..`                 | Mergi cu un nivel înapoi în structură             |
| `dir`                   | Listează fișierele din folderul curent            |
| `cls`                   | Curăță ecranul CMD                                 |
| `mkdir nume_folder`     | Creează un folder nou                              |
| `del nume_fisier`       | Șterge un fișier                                   |
| `rmdir /s nume_folder`  | Șterge un folder cu tot conținutul                |
| `echo %USERPROFILE%`    | Afișează calea profilului tău de utilizator       |
| `ping adresa`           | Testează conexiunea (ex: `ping github.com`)        |
| `ipconfig /all`         | Afișează detalii despre conexiunea de rețea       |
| `start .`               | Deschide folderul curent în File Explorer         |

---

## 🔁 Comenzi Git esențiale

| Comandă                         | Descriere                                                  |
|----------------------------------|------------------------------------------------------------|
| `git init`                      | Inițializează un repository Git local                     |
| `git clone <url>`              | Clonează un repository de pe GitHub                       |
| `git status`                   | Afișează fișierele modificate/nelistate                   |
| `git add nume_fisier`          | Pregătește un fișier pentru commit                        |
| `git add .`                    | Adaugă toate fișierele din folder                         |
| `git commit -m "mesaj"`        | Creează commit cu mesaj descriptiv                        |
| `git log`                      | Afișează istoricul commit-urilor                          |
| `git branch -M main`           | Schimbă numele ramurii curente în `main` (standard GH)    |
| `git remote add origin <url>` | Leagă repo-ul local de cel de pe GitHub                   |
| `git push -u origin main`      | Trimite codul local pe GitHub (prima dată)                |
| `git pull origin main`         | Actualizează repo-ul local cu modificările de pe GitHub   |
| `git reset --hard`             | Revine complet la ultima versiune salvată                |
| `git config --global user.name "Nume"`   | Setează numele utilizatorului global                    |
| `git config --global user.email "Email"` | Setează emailul utilizatorului global                   |
