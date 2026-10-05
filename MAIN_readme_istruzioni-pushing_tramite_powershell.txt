cd "C:\Users\MediDanaj\Desktop\Personal\Marigold\marigold-site"

git checkout dev
git add .

git commit -m "bug tasto verifica disponibilità su mobile + migliorie su gestione lingua"

git push origin dev
git checkout main
git merge dev
git push origin main