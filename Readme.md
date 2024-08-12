Criando um repositório no github:

crie um novo repositório na linha de comando

echo "# projetoGit" >> README.md 
git init 
git add README.md 
git commit -m "primeiro commit" 
git branch -M main 
git remote add origin https://github.com/izazaias/projetoGit.git
git push -u origin main

envie um repositório existente a partir da linha de comando

git remote add origin https://github.com/izazaias/projetoGit.git
git branch -M main
git push -u origin main
