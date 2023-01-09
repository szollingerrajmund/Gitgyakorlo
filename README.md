# Verziókezelés alapjai
## 1. git letöltése
- [git for windows](https://gitforwindows.org/)
- [git scm](https://git-scm.com/)
## 2. Konfigurációs parancsok
- git config --global user.email szollinger.rajmund@students.jedlik.eu
- git config --global user.name szollingerrajmund
- git config --global credential.helper wincred
## 3. Repository létrehozása
- git init
## 4. Állomány hozzáadása a stage-hez '(staging area)
> A stagen lévő állonyokról tudunk állapotfelvételt (commitot) készíteni
> >üres mappa nem kerül a stage-re
- git add állomány neve
- git add . (összes állomány és mappa hozzáadása)
## 5. Állapotfelvétel (commit) készítése
- git commit "commit message"