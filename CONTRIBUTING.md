## Vegleiðing: Soleiðis gert tú ein *fork* og *pull request* við Git

1. Tú skalt *fork’a* **main branch** av repository-num, sum tilhoyrir skeiðinum.
2. Tá tú hevur lagt títt egna tilfar afturat ella broytt nakað, skalt tú senda eitt *pull request*.
3. Eftir at *pull request* er send, skal ábyrgdarfólkið fara ígjøgnum broytingarnar og vátta, um tilfarið er nøktandi og hóskandi til skeiðið. 

## Git-nýtsla
Vit viðmæla, at tit læra at brúka Git gjøgnum **cmd**, **terminal** ella **PowerShell**, tí við at brúka Git gjøgnum IDE’s (t.d. Visual Studio Code) verða nógv ting gjørd automatiskt og verða sostatt meira ógreið.
Tað gevur eina betri fatan at læra Git á grundstøði við kommandolinju. Eitt gott youtube video, um ynski at læra nógv um git https://www.youtube.com/watch?v=tRZGeaHPoaw .

## 🔧 Stig-fyri-stig vegleiðing
Hetta kann virka torført í fyrstani, men eftir nakrar fáar ferðir kennist tað einfalt.

### 1. Fork’a repository

Far inn á GitHub repository-ið, t.d. `https://github.com/username/repository`, og trýst á **Fork** ovast til høgru.  

Hetta ger eina útgávu av repository-num á tínum egna GitHub-vanga.

### 2. Klona títt fork lokalt

"git clone https://github.com/titt-brúkaranavn/repository.git"

cd repository


### 3. Set upprunaliga repository sum "upstream remote"
"git remote add upstream https://github.com/upprunaligt-brúkaranavn/repository.git"

### 4 Ger eina nýggja grein fyri tínar broytingar
git checkout -b grein-navn

### 5. Legg títt tilfar afturat
Legg nýggja tilfarið í hóskandi mappu.

Gev gætur! Ikki leggja innlatingar ella loysnir til uppgávur, sum eru kravdar at standa í einum skeiði. (Bert stuðuls tilfarð).

### 6. Add og commit broytingarnar
git add .

git commit -m "Lagt til notur til [skeiðnavn] – vika X"

### 7. Push greinina til GitHub
git push ella git push origin grein-navn

### 8. Ger eitt Pull Request
Far á títt repository á GitHub.

GitHub vil vanliga vísa ein knapp: "Compare & pull request".

Vel main branch í upprunaliga repository-num sum base, og tína grein sum compare.

Skriva eina greiða frágreiðing um, hvat tú hevur lagt afturat.

Trýst á Create pull request.

### Tá ið pull request er sent hendur:
Verður tað kannað av ábyrgdarfólki:

🔍 Broytingarnar verða gjøgnumgingnar.

📬 Tú fært boð, um okkurt skal broytast.

✅ Um alt er í lagi, verður tilfarið lagt saman (merged) við main.

### Góð ráð / vegleiðing
Halt teg til somu uppseting og málburð sum longu er í repository-num.

Brúka greið filheiti og rættan mappustruktur.

Legg bert viðkomandi tilfar – ikki persónligar notur, innlatingar ella loysnir.

Um tú ert í iva – spyr áðrenn tú push’ar.
