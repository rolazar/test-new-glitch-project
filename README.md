echo "# multi-page-4znr7eualuc95gqefk2w9eh4wec2yut7vp9icjz2ggh7cekb8q" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/rolazar/multi-page-4znr7eualuc95gqefk2w9eh4wec2yut7vp9icjz2ggh7cekb8q.git
curl -sS https://webi.sh/gh | sh
gh auth login
git config user.name "rolazar"
git config user.email "rolazar.aberin@codex.academy"
git push -u origin main