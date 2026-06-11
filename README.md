git init
git config --global user.name "TuNombre"
git config --global user.email "tuemail@example.com"
git clone <URL-del-repositorio>
git status
git add README.md
git commit -m "Primer commit con README"
git branch nueva-rama
git checkout nueva-rama
 o directamente:
git checkout -b nueva-rama
git merge main
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
git push origin nueva-rama
git pull origin main
git tag v1.0
git push origin v1.0
git merge otra-rama Editar archivos para resolver conflictos
git add archivo-conflictivo
git commit -m "Conflicto resuelto"
git fetch origin
git pull origin main
git log --oneline --graph --all
git log
git diff
git show <commit-id>
