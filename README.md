mkdir my-new-repo cd my-new-repo

git init

echo "# My New Repo" > README.md git add . git commit -m "Initial commit"

git remote add origin https://github.com/Geraldsalamana1/my-first-repository.git

git branch -M main git push -u origin main
