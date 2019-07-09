## Setup

### Git

```bash
# initialize repository and set GitHub as remote
git init
touch README.md
git add README.md
git commit -m 'first commit'
git remote add origin git@github.com:coriell-research/bioinformatics_education_sessions.git
git push -u origin master

# add the gitignore
touch .gitignore
git add .gitignore
git commit -m 'added .gitignore'
git push

# copied MIT license from personal useful_code git repository to the server using Macfusion
git add LICENSE
git commit -m 'added MIT license'
git push
```