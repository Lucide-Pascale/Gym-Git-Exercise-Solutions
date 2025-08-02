# Bundle 1
## Exercise 1

```bash
   git --version
   git init 
   git add README.md 
   git status  
   git commit -m "Adding a Read me" 
   git branch 
   git branch -m main 
   git add . 
   git remote add origin https://github.com/Lucide-Pascale/Gym-Git-Exercise-Solutions.git
   git push
   git push -u origin main
  ```
## Exercise 2
```bash
1 try { . "c:\Users\user\AppData\Local\Programs\Microsoft VS Code\resources\app\out\vs\workben... 
   2 git add .
   3 git status
   4 git restore --staged index.html
   5 git status
   6 git add .
   7 git commit -m "Chhanges"
   8 git commit --amend
   9 git push
  10 git log
  11 git log --one-line
  12 git log --oneline
  13 git log --stat
  14 history
  15 git branch
  16 git branch dev
  17 git branch
  18 git checkout dev
  19 git branch
  20 git checkout -b test
  21 git branch
  22 git switch -c dev
  23 git switch dev
  24 git branch -d  test
  25 git branch
  26 git stash
  27 git status
  28 git stash -u
  29 git add about.html
  30 git stash
  31 git stash -u
  32 git stash list
  33 git stash pop stash@{1}
  34 git stash apply stash@{1}
  35 git stash apply "stash@{1}"
  36 git add about.html
  37 git stash
  38 git stash list
  39 git stash pop "stash@{0}"
  40 git stash pop "stash@{4}"
  41 git stash pop "stash@{3}"
  42 git stash apply "stash{3}"
  43 git stash apply "stash@{3}"
  44 git stash list
  45 git stash pop "stash@{2}"
  46 git status
  47 git add .
  48 git status
  49 git commit -m "Commiting changes"
  50 git push
  51 git push  -u origin dev
  52 git stash list
  53 git stash pop "stash@{0}"
  54 git reset
  55 git reset --hard
  56 git switch main
  57 git branch
  58 git statch main
  59 git stash -u
  60 git switch main
  61 git branch
  62 git add .
  63 git commit -m "Editing the ReadMe"
  64 git push
  65 git add .
  66 git commit -m "Editing the ReadMe"
  67 git push
```

# Bundle 2
## Exercise 1
```bash
  2 git branch
   3 git switch -c dev
   4 git switch dev
   5 git add .
   6 git commit -m "ReadMe updated from the main"
   7 git push
   8 git branch
   9 git switch dev
  10 git branch
  11 git checkout -b ft/bundle-2
  12 git branch
  13 git status
  14 git add services.html
  15 git status
  16 git commit -m "New services page in another branch"
  17 git push
  18 git push -u origin ft/bundle-2
  19 git status
  20 git checkout main --README.md
  21 git checkout main -- README.md
  22 git add .
  23 git commit -m "Updating a ReadMe to be updated with main"
  24 git push
  25 git branch

```

## Exercise 2
```bash
  27 git checkout main
  28 git branch
  29 git pull
  30 git checkout -b ft/service-redesign
  31 git branch
  32 git status
  33 git checkout main -- README.md
  34 git branch
  35 git status
  36 git switch main
  37 history
  38 git branch
  39 git status
  40  git add README.md
  41 git commit -m "Bundle 2 Exercise 1"
  42 git push
  43 git status
  44 git branch
  45 git switch ft/service-redesign
  46 git checkout main -- README.md
  47 git branch
  48 git status
  49 git add services.html
  50 git commit -m "Changes to the services.html"
  51 git push
  52 git push -u origin ft/service-redesign
  53 git push -u origin ft/service-redesign
  54 git branch
  55 git checkout main
  56 git branch
  57 git status
  58 git add .
  59 git commit -m "Changes to the Services.html"
  60 git push
  61 git branch
  62 git checkout ft/service-redesign
  63 git branch
  64 git diff main
  65 git branch
  66 git merge main
  67 git add .
  68 git commit
  69 git push
  70 git branch
  71 git checkout main
```

# Bundle 3
## Exercise 1
```bash
  git checkout -b ft/team-page
  git add team.html
  git commit -m "Adding team.html"
  git push -u origin ft/team-page
  git checkout main
  git checkout -b ft/contact-page
  git switch ft/team-page
  git log
  git checkout ft/contact-page
  git cherry-pick 96f75b77e0c3bee70cf09cd9a5d5da3a035c36d7
  git add .
  git commit -m "Adding team.html to branch ft/contact-page"
  git push
   5 git branch
   6 git status
   7 git log
   8 git branch
   9 git push
  10 git status
  11 git log --one-line
  12 git log -- one-line
  13 git log
  14 git puus
  15 git push
  16 git push --set-upstream origin ft/contact-page
  17 git branch
  18 git checkout -b ft/faq-page
  19 git branch
  20 git status
  21 git add .
  22 git commit -m "faq.html to branch ft/faq-page"
  23 git push
  24 git push --set-upstream origin ft/faq-page
  25 git branch
  26 git switch ft/team-page
  27 git log
  28 git branch
  29 git switch ft/faq-page
  30 git branch
  31 git revert 96f75b77e0c3bee70cf09cd9a5d5da3a035c36d7
  32 git log
  33 git push
  34 git status
  35 git branch
  36 git switch main
```

## Exercise 2
```bash
 git branch
  43 git switch ft/faq-page
  44 git branch
  45 git checkout -b ft/home-page-redesign
  46 git switch main
  47 git branch
  48 git status
  49 git add .
  50 git commit -m "Added some changes in home.html"
  51 git push
  52 git branch
  53 git checkout ft/home-page-redesign
  54 git rebase main
  55 git log
  56 git status
  57 git add .
  58 git commit -m "Added changes to home.html"
  59 git push
  60 git push --set-upstream origin ft/home-page-redesign
  61 git branch
  62 git checkout main
```
# Bundle 4
## Exercise 1
```bash
  67 git checkout main
  68 git branch
  69 git remote
  70 git remote -v
  71 git remote add git-copy https://github.com/Lucide-Pascale/Gym-Git-Exercise-Solutions-Repo-2.git 
  72 git remote
  73 git branch
  74 git status
  75 git status
  76 git add home.html
  77 git commit -m "feature: Adding A home emoji on home page"
  78 git push origin
  79 git push git-copy
```