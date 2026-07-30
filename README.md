# githubCommands
i write here important github command


| ***** GIT Hosting step by step ***** |

Step # 01 :- git init

Step # 02 :- git status

Step # 03 :- git add -A

Step # 04 :- git status

Step # 05 :- git commit -m "Relavant Comment"

Step # 06 :- git remote add origin (then press ctrl + v)

Step # 07 :- git push -u origin master

| ***** Hosting completed ***** |

Note : If you want to update your github repository then use these commands.

Step # 01 :- git status

Step # 02 :- git add . ( Note : git add space dot. )

Step # 03 :- git commit -m "relevant comment"

Step # 06 :- git push origin master/brance-name

Note: If you want to take pull of any repo for the very first time...!

Step # 01 :- git clone repourl
Example: git clone https://github.com/Shahzadaahmed/React-Native-Basics

Note: Agr ap kisi repo m kam kr rahy ho or apki kisi partner ne changes ki hen or apne pull lena hy then:
git pull origin master/brance-name


if i have cloned a repo of my friend in my laptop and my friend made any changes in his repo and i want that i can also take updates than first i check whether repo is remotely connected or not by using this comman <br/>
git remote -v <br/>
if not remotely active than first i connect it remotely <br/>
git remote add origin(url of my friend repo) <br/>
than check again <br/>
git remote -v <br/>
than <br/>
git pull origin or master<br/>

Adding a New repo<br/>
How to Push a Project to GitHub (Windows CMD) — Notes <br/>
One-Time Setup (per project) <br/>
Step 1: Create a repository on GitHub <br/>
Login to github.com <br/>
Click "+" (top right) → New repository <br/>
Give it a name <br/>
Choose Public or Private <br/>
Do NOT check README / .gitignore / license (your code is already ready) <br/>
Click Create repository <br/>
Copy the repo URL shown, e.g.: https://github.com/username/repo-name.git <br/>
Step 2: Open terminal and go to your project folder <br/>
cd D:\your-project-folder <br/>
Step 3: Initialize git <br/>
git init <br/>
Step 4: Set your git identity (only needed once per laptop) <br/>
git config --global user.name "Your Name" <br/>
git config --global user.email "your-email@example.com" <br/>

(Use the same email as your GitHub account) <br/>

Step 5: Add all files <br/>
git add . <br/>
Step 6: Commit <br/>
git commit -m "initial commit" <br/>

⚠️ Always use double quotes " " in Windows CMD, not single quotes ' ' <br/>

Step 7: Rename branch to main <br/>
git branch -M main <br/>
Step 8: Connect to GitHub repo <br/>
git remote add origin https://github.com/username/repo-name.git <br/>

Check it worked: <br/>

git remote -v <br/>
Step 9: Push <br/>
git push -u origin main <br/>
If it asks for login, use your GitHub username <br/>
For password, use a Personal Access Token (GitHub no longer accepts normal passwords) <br/>
Making a Personal Access Token (if needed) <br/>
GitHub → profile picture (top right) → Settings <br/>
Left sidebar (bottom) → Developer settings <br/>
Personal access tokens → Tokens (classic) <br/>
Generate new token → Generate new token (classic) <br/>
Add a note + expiration <br/>
Tick repo checkbox <br/>
Generate token <br/>
Copy it immediately (won't be shown again) <br/>
Paste it as the password when CMD asks <br/>
Every Time After (once project is already connected) <br/>

Whenever you make changes to your code: <br/>

git add . <br/>
git commit -m "describe what you changed" <br/>
git push <br/>

That's it — no need to repeat git init or git remote add again. <br/>

Common Mistakes to Avoid <br/>
❌ Using single quotes 'message' in CMD → use "message" <br/>
❌ Pasting multiple commands + old output together → paste one command at a time <br/>
❌ Running git remote add origin twice → if it says "remote origin already exists", either skip it or  <br/>run git remote remove origin first <br/>
❌ Forgetting git add . before commit → commit will say "nothing to commit" <br/>

