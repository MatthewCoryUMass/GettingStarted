# Getting Started

## Set up global variables  --> You only need to do this once!

git config --global user.name '*Your Name*'  
git config --global user.email '*Your Email Address*'  

mkdir GitLearn  
cd GitLearn  
git clone https://github.com/MatthewCoryUMass/GettingStarted  
cd GettingStarted  
git status  
git branch  
git branch *yourname*  
git branch  
git checkout *yourname*  
notepad *yourname*.txt.  Type "I would like to visit *place*".  
git status  
## EVERYTHING YOU'RE DOING RIGHT NOW IS LOCAL.  THIS IS ALL HAPPENING ON YOUR MACHINE
git add .  
git status  
git commit -m "*yourname* visits *place*"  
## COMMIT MESSAGES SHOULD ALWAYS BE USED AND BE DESCRIPTIVE
git status  
## USE GIT STATUS FREQUENTLY
git push  
git push --set-upstream origin *your branch*
## YOU JUST PUSHED TO THE CLOUD.  NOW I AM GOING TO MERGE ALL YOUR CHANGES
git log  
git checkout main  
dir  
git pull  
## WE DON'T EVER WANT ANYONE BUT THE REPO OWNER(s) PUSHING TO THE MAIN BRANCH.  ALWAYS PUSH TO A CREATED BRANCH (e.g. bugfix OR release4) AND THEN YOUR CHANGES WILL BE REVIEWED AND PUBLISHED
dir  
git log  
git log --graph --decorate --oneline   
git branch -d *yourname*  
