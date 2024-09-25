# profile

//git push command//

git init

git add .

git commit -m "first commit"

git branch -M main

git remote add origin git@github.com:mdkawsarmahmud/Hellicupter-Blaster.git

git push -u origin main

if err//

git checkout -b my-new-branch

git add .

git branch -M "New branch"

git push -u origin my-new-branch
----short commend end---
-----all git command-----

git config --global user.name kawsar // insert user name
git config --global user.name // show user name

git config --global user.email skkawsar.bpi@gmail.com //insert email

git init //git active and add (.git) folder

ls // show file

ls -lart // show hidden file

git status //show current status


---The repository change----

1#.1/untract(u) (add) to 2/stage(A) (commit) to 3/unmodifite (edit) to 4/modifite(M) to 2/stage

2#.3/ unmodifite (remove) 1/untract

----file create----
touch index.html//index file creat

-------git add to stage---
git add file name // add git 1 file
git add -A // all file add to stage 
git add .// all file add 
git add path // 1 file add with path

git reset //all file stage to untract

---git commit--
git commit // commit
Initial commit +enter + esc // intial commite 
:wq +enter// commite done

--git commit esy way--
git commit -m "message"

---undo delete file--

git checkout file name // recover 1 file
git check out -f //recover all file


git log //show info
git log -p -1 // show last commit

git diff //show different 

git rm file name //delete file

git rm file name -f // force fully file delete

--git ignore--
add a file name git ignore 
wtite which is ignore like

app.js//js file ignore
img/ //img folder ignor
css/botstrap.css // ignore using path
*.jp //all jpg ignore 
*.png // all png ignore

----branch---
git branch // show branch
git branch name // create ne branch
git checkout -b master // create maser branch and auto into maser
git checkout main // switch main branch

--git merg--
git merge main -m "comment" // master a theke mainke merge kora

---link with SSH key---
git remote add origin SshKeyName

git remote -v // show ssh key

---push---
git push -u origin main

---ssh key creat--
eval "$(ssh-agent -s) // creat process id fpr adding ssh key

--refs pblm--
git fetch origin main:tmp
git rebase tmp

