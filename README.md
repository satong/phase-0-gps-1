# phase-0-gps-1
  324  git clone https://github.com/satong/phase-0-gps-1.git
  "Copied the repo to local"
  325  ls
  "Lists files in current directory"
  326  cd phase-0-gps-1
  "Moves into the repo"
  327  ls
  328  touch awesome_page.md
  "Creates new file"
  329  git add awesome_page.md
  "Added new file for staging"
  330  git status
  "Checks the status"
  331  git commit -m "Added awesome_page.md to directory"
  "Commits changes"
  332  git status
  333  git push origin master
  "Pushes changes to the origin master branch"
  334  git checkout -b add-command-log
  "Creates new branch and goes into new branch"
  335  git branch
  "Checks which branch we're on and what branches exist"
  336  atom readme.md
  "Opens the readme.md file in Atom"
  337  history
  "Prints log of terminal commands used"
