STEP 1 — Create Repository on GitHub
Go to https://github.com
Click New Repository
Repository name: Git
Do NOT check "Add a README"

STEP 2 — Create Local Project
Open Git Bash and run:
mkdir Git
cd Git

STEP 3 — Initialize Git
git init

STEP 4 — Create text.txt File
cat>> text.txt
Hi Uma!     ---> ctrlD save

STEP 5 — Add File to Staging
git add text.txt

STEP 6 — First Commit
git commit -m "First commit"

STEP 7 — Connect to GitHub Repository
git remote add origin https://github.com/your-username/Git.git

STEP 8 :Push to GitHub
git branch -M master
git push -u origin master

STEP 9:Second commit
cat >> a.txt
Hello uma
git add .
git commit -m "Added:Second Commit"
git push origin master
-----------------------------------------------------------------------------
