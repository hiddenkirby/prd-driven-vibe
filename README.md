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
6. Open Cursor chat and type the following
```
@02-prd-create.mdc I want to build a full-stack webapp, beautifuly styled and responsive on mobile and tablet.

I want to keep things small and simple to start, and add the more complex features later on. 

The purpose of the app is to ...

The core functionality ...

Some key user flows are ...
```
7. Review the PRD: `Run @<newlycreatedplan.md> through @03-prd-review.mdc to validate assumptions`
It will review and also create an execute plan.
8. Make any adjustments needed. (some decision points may have been raised)
9. Start Implementation: `Use @04-prd-execute.mdc to begin Phase 1`
