# PRD Driven Vibe Coding

## Steps to follow
1. . `git clone git@github.com:hiddenkirby/prd-driven-vibe.git <project_name>`
2. `cd <project_name>`
3. Read through all mdc files and alter any project specific details as required.
4. Create a new github repository.
5. Establish remote origin to the newly created github repo.
```bash
echo "# <project_name>" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:hiddenkirby/<project_name>.git
git push -u origin main
```
6. 
