======================= How to push a file in Github ======================
1. ls (get list)
2. cd
3. git init
4. git remote add origin <gitLink>
5. git remote -v / --verbose
6. git add .(.all files) / example.txt/folder(single file)
7. git commit -m "commit message" 
8. git push origin master

=======================  How to change Existing Repository =================
1. git remote set-url origin <gitLink>

=======================  How to Clone a Repository & push it =========================
1. copy the repository url
2. git clone url(repository url)
Now push it
3. git add (cloned file)
4. git commit -m "message"
5. git push origin master


=======================  How to Checkout cloning repository ================
  
1. git checkout master   (if there set main)

=======================  How to Overwrite/ merge local files ================
1. git add  *
2. git stash
3. git pull

=======================  How to delete existing files  ================

 git checkout  .
