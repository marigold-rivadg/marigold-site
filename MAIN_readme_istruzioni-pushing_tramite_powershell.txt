cd "C:\Users\MediDanaj\Desktop\Personal\Marigold\marigold-site"

git checkout dev
git add .

git commit -m "Rimuove i pallini animati dallo sfondo dell'hero"

git push origin dev
git checkout main
git merge dev
git push origin main