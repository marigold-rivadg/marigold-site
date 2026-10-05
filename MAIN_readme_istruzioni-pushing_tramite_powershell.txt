cd "C:\Users\MediDanaj\Desktop\Personal\Marigold\marigold-site"

git checkout dev
git add .

git commit -m "feat(i18n): aggiunto tedesco e selettore lingua a dropdown"

git push origin dev
git checkout main
git merge dev
git push origin main