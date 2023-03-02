# Navigare in terminal
```bash
#WINDOWS/UNIX/GITBASH
# navigam in folderul1
cd folder1

#WINDOWS/UNIX/GITBASH
# navigam in folderul anterior
cd ..

#WINDOWS/UNIX/GITBASH
# navigeaza intr-un folder anume
cd ~/Desktop/

#UNIX/GITBASH
#afiseaza toate fisierele din folderul in care ne aflam
ls

#UNIX/GITBASH
#afiseaza folderul/calea pana la folderul in care suntem
#pwd -> print working directory
pwd

#UNIX/GITBASH
#golirea terminalului (pentru claritate)
clear

#WINDOWS
#afiseaza toate fisierele din folderul in care ne aflam
#afiseaza folderul/calea pana la folderul in care suntem
dir

#WINDOWS
#golirea terminalului (pentru claritate)
#cls -> clear screen
cls
```

# Pentru a vedea foldere invizibile
> Folderele invizibile au numele cu . in fata de exemplu .git
> Pe macos mergem in folder si apasam command + shift + .
> In folder mergem la View > Show > Hidden files
https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5



# Comenzi git
```bash
# am initializat un repo in folderul in care ma aflu
# adica s-a creat un folder ascuns numit .git
git init

# legam folderul/ repo-ul local de repo-ul de pe github
# git remote add origin url
# url reprezinta url-ul repo-ului de pe git
git remote add origin https://github.com/cezarmocanu/git-intro-1.git

# adaugam TOATE modificarile
git add .

# Ne indica ce fisiere au fost adaugate in commit
# verde adaugate in commit
# rosu ne adaugate in commit
git status

# Impachetam toate modificarile si adugam o eticheta cu un mesaj descriptiv
# Mesajul trebuie sa fie intre gilimele
git commit -m "Mesaj commit"


# Clonam/descarcam un repo de pe github in folderul in care ne aflam
# git clone url
# url reprezinta url-ul repo-ului de pe git
git clone https://github.com/cezarmocanu/git-intro-1.git
```