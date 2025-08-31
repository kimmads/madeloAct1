Step 1: Create the Master/Main Folder
dir
clear
cd desktop
mkdir Madelo_IT120_Act1
cd madelo_IT120_Act1
git init
touch profile.txt
touch education.txt
touch background.txt
touch readme.txt
touch test.py
Check nato if naba nisila sa repository na file - (git status) if untracked means wala pa then use (git add .) pwede sab (git add nya file name kung unsa na file ang e add).

git status
git commit -m "added files" - to save

/////////////
----To register username and email in git hub----
git config --global user.name"kimmads"
git config --global user.email"kimpepitocacheromadelo@gmail.com"
\\\\\\\\\\

Step 2:Add initial Information
Adto ta sa note try nato mag type og content sa file (--all files--) then balik sa git bash to check status by (git status) then makita ddto nga changes is wala pa na commit so we need to add it by (git add 'name sa file with extension')
git status - to check if na add na then
git commit --m "update readme.txt" Mo result dri nga /1 file changed,1 insertion(+)\.

Step 3: Create and Work on Branches

git branch ra if gusto nimo makita unsa na mga branch ang na creat already.
git branch Madelo_B1 To create a branch
git checkout Madelo_B1 - Kung unsa na branch ra imo gusto makuha
echo "then additional info to be added to in a file" >> file name
git status then git add . or  git add 'filename' para ma add nasab ang file sa bdo na branch.
git status Nasab to check if naa na, ang result is na add na.
git commit -m "update 'filename' on Madelo_B1 branch
git checkout main Ma switched nasab ta sa main branch wala nata sa bdo.
git status nasab para e check kung unsay new changes sa main..

----{optional ni if ever mamali og create and changes sa content or file sa branch}----
------delete branch in main------
git branch -D 'branch name'

---deletion or removed files----
git rm --cached test.txt or rm test.py
git status To check kung na remove, so mo result diha deleted na pero naay untracked files so all we need to do next is
git add filename
git commit --m "delete si test.txt" ang result is /1 file changed,0 insertion\.
git status nasab….


>>>>>>Additional git bash command<<<<<<
ls is for checking the list for all files in a branch
cat filename is to view contents of a specific files