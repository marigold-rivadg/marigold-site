cd "C:\Users\MediDanaj\Desktop\Personal\Marigold\marigold-site"

git checkout dev
git add .

git commit -m "feat: improve Italian/English language selector"

git push origin dev
git checkout main
git merge dev
git push origin main