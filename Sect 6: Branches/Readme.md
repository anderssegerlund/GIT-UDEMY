# Sammanfattnig kap 6

- Ett sätt att adda och comitta samtidigt är att skriva git commit -a -m "message"
- En skillnad mellan git checkout och git switch är att man kan baka in fler kommandon
- Ett sätt att skapa en ny branch och hoppa in direkt till den är git switch -c "namn på branch" eller git checkout -b "namn på branchen"
- Observera att om man skapar en fil i en branch och ändrar den i olika branches. Så kan man inte hoppa mellan branches. Tex Playlist med olika branches. Men om man skapar en helt ny fil tex "mat" så kan man hoppa via branches utan problem. Se sect 6 lect 49
- merga genom *git merge 'namn på branchen man vill merga'*