cd "C:\Users\MediDanaj\OneDrive - BI Network\Desktop\Personal\Marigold\marigold-site"

git checkout dev
git add .

git commit -m "evolutiva: miglioria design"

git push origin dev
git checkout main
git merge dev
git push origin main