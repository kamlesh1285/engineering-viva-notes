Git Commands Used During Development:@kamlesh1285

Clone repository:-

git clone <repo-url>

Check status:-

git status

Create branch:-

git checkout -b feature-login

Add changes:-

git add .

Commit:-

git commit -m "Added login page"

Push:-

git push origin main

Pull:-

git pull origin main
Frontend Deployment (React)
Deploy on GitHub Pages

Install package:-

npm install gh-pages --save-dev

Build:-

npm run build

Deploy:-

npm run deploy
Deploy on Vercel

Install CLI:-

npm install -g vercel

Login:-

vercel login

Deploy:-

vercel
Deploy on Netlify

Build:-

npm run build

Upload dist folder to Netlify.

Backend Deployment (Python)
Render Deployment

Requirements file:-

pip freeze > requirements.txt

Create:-

touch render.yaml

Push to GitHub:-

git push origin main

Connect GitHub repository to Render and deploy.

Railway Deployment

Install CLI:-

npm install -g @railway/cli

Login:-

railway login

Deploy:-

railway up
Backend Deployment (Node.js)

Install dependencies:

npm install

Start command:

npm start

Push code:-

git push origin main

Deploy on:-

Render
Railway
Vercel Serverless
AWS EC2





                       Git , Git Bash & Git Hub 

1. Check Git Installation:
 * git --version 
2. Check current Directory:
 * pwd           [Shows your current working directory]
3. List Files:
 * ls            [Show files]
 * ls -la.       [Shows hidden files also]
4. Change Directory:
 * cd Desktop 
 * cd ..         [Go back one folder]
 * cd ~          [Go to Home] 
5. Create Project Folder:
 * nkdir Project name [create directory]
 * cd Project name    [move inside] 
6. Create Files:
 * touch app.py 
 * touch app.py README.md xyz.txt  [create multiple]
7. Open VS code:
 * code .       [opens current folder] 
8. Initialize Git Repository:
 * git init 
9. Check Git Status:
 * git status 
10. Configure Git(One Time):
- Name
    * git config --global user.name "Kamlesh Kumar" 
- Email
    * git config --global user.email "example@gmail.com" 
- Check
    * git config --list 
11. Create .gitignore:
 * touch .gitignore    [git will ignore these files] 
12. Stage Files:
 * git add app.py      [Single file]
 * git add .           [All files] 
13. Commit:
 * git commit -m "Initial commit" 
 * git commit -m "Added login feature" 
14. View Commit History:
 * git log 
 * git log --oneline 
15. See Changes:
 * git diff          [Shows changes before commit] 

 16. Create GitHub Repository:
 - On GitHub:
    New Repository 
17. Connect Local Repository to GitHub:
 * git remote add origin http://github.com/username/ProjectName.git 
 - check
    * git remote -v 
18. Rename Branch:
 * git branch -m main 
19. Push to GitHub:
 * git push -u origin main   [Firstpush]
 * git push                  [Later] 
20. Clone Respository:
 * git clone https://github.com/username/projrct.git 
 - moveinside
            * cd project 
21. Pull Latest Changes:
 * git pull origin main 
22. Fetch Changes:
 * git fetch          [Download updates without merging] 
23. Create Branch:
 * git branch feature-login     
24. View Branches:
 * git branch 
25. Switch Branch:
 * git switch feature-login 
26. Create and Switch Together:
 * git switch -c feature-login 
27. Merge Branch:
 * git merge feature-login 
28. Delete Branch:
 * git branch -d feature-login 
29. Remove Remote:
 * git remote remove origin 
30. Change Remote URL:
 * git remote set-url origin https://github.com/username/newrepo.git 
31. Undo Last Commit (keep changes):
 * git reset --soft HEAD~1 
32. Undo Last Commit (Discard Changes):
 * git reset --hard HEAD~1         [use with caution] 
33. Restore File:
 * git restore app.py.             [Discard Local Changes to a file] 
34. Stash Changes:
 * git stash 
35. Add Git Tag:
 * git push --tags [push tags] 
36. Show Remote Repository:
 * git remote -v 
37. Show Commit Graph:
 * git log --graph --oneline --all 
38. Deploy a React App:
 * npm install               [Install dependencies] 
 * npm run dev               [Run Locally]
 * npm run build.            [Build Production version]
39. Deploy on Vercel:
 * npm install -g vercel 
 * vercel login              [Login]
 * vercel                    [Deploy]
 * vercel --prod             [Production deployment] 
40. Deploy a Python/ FastAPI App:
 * python -m venv venv.      [Create virtual environment] 
 * source venv/bin/activate  [Activate (macOS/ Linux)]
 * pip install -r requriment.txt       [Install dependencies]
 * unicorn main.app --reload           [Run Locally]

41. Deploy to AWS EC2 (Basic Flow):
 * ssh -i key.pem ubuntu@your-ec2-public-ip      [SSH into your Server] 
 * git clone https:/github.com/username/project.git    [clone your repository]
 * cd project                                          [move into the project]










