    1  git init
    2  git config --global user.name "Alessandro.Souza"
    3  git config --global user.email "alerodriguesdesouza@gmail.com"
    4  echo 01 > arquivo.txt
    5  git add arquivo.txt
    6  git status
    7  git commit -m "git add example - arquivo.txt"
    8  echo 02 > arquivo.txt
    9  git diff
   10  git add arquivo.txt
   11  git status
   12  git diff --staged
   13  echo  03 > arquivo.txt
   14  git diff
   15  git restore --staged arquivo.txt
   16  git status
   17  git commit -m "add exemple - arquivo.txt"
   18  git log
   19  echo "*.txt" >> .gitignore 
   20  echo new > novo.txt
   21  git status
   22  history# MBA_IMPACTA
Fim
