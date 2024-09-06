echo "# multi-page-4znr7eualuc95gqefk2w9eh4wec2yut7vp9icjz2ggh7cekb8q" >> README.md
git init
git add README.md
git config user.name "rolazar"
git config user.email "rolazar.aberin@codex.academy"
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/rolazar/multi-page-4znr7eualuc95gqefk2w9eh4wec2yut7vp9icjz2ggh7cekb8q.git
curl -sS https://webi.sh/gh | sh
gh auth login
git push -u origin main

//ADD CHANGES THAT WERE MADE TO THE README FILE
git add README.md

//ADD CHANGES THAT WERE MADE IN ALL FILES AND FOLDERS
git add .

//CREATE A SAVE POINT AND ATTACH A MEMO TO IT
git commit -m "I added user info to readme"

//SYNC CHANGES TO GITHUB
git push origin main

//VIEW THE VALUE OF ORIGIN
git remote -v

//ASSIGNS A URL TO THE ORIGIN VARIABLE
git remote add origin https://github.com/rolazar