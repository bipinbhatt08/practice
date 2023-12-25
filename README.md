# practice
# githubtrain
You changed some code
  —> now you want to switch the branch?
		Decision1: i don’t want current change.  
				git stash 
                               git reset —hard
                Decision2: I might need this change later
                              git checkout -b tempBranch
                              ACP 
		Decision3: this changes are must
				ACP


1. To copy project in vscode (already  existing):
Create a repo, add readme and gitignore
git clone link

2. If u have pre existing project:
greate a repo
git init
git remote…… 

Branch commands:
  git checkout branchName
  git checkout -b branchName

ACP Commands:
 git add .
git commit -m “message”
git push -u origin branchName

Reset commands:
git stash 
git reset —hard

Pull/fetch:
git pull origin branchName
git fetch

To check what all changes we made:
git status