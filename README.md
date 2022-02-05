 git init 
 git pull https://github.com/szpeter992/git-vizsga-0205.git 
 touch README.md 
 git add . 
 git commit -m 'README.md'
 touch .gitignore
 git add .  
 git commit -m '.gitignore'
 git add . 
 git branch console 
 git checkout console -
 git add . 
 git commit -m 'rögzítsük a változtatást'
 git add . 
 git commit -m 'rögzítsük a változtatást css-ben'
 git add 
 git commit -m 'README.md fájl rögzítése'
 git add . 
 git checkout master 
 git commit -m 'README.md fájl rögzítése'
 git checkout console
 git remote add origin https://github.com/FerencFarkas22/vizsga.git  
 git push -u origin console 
 git checkout master 
 git remote add origin https://github.com/FerencFarkas22/vizsga.git
 git push -u origin console 
