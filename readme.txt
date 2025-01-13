1345  brew update
 1346  brew install gh
 1347  gh auth login
 1348  gh auth login
 1349  cd ..
 1350  cd ..
 1351  cd $(mktemp -d)
 1352  mkdir mon-nouveau-projet
 1353  cd mon-nouveau-projet
 1354  gh repo create mon-nouveau-projet --public --source=. --remote=origin
 1355  git init
 1356  gh repo create mon-nouveau-projet --public --source=. --remote=origin
 1357  echo toto > toto.txt
 1358  git add . 
 1359  git commit -m "Premier commit"
 1360  git push -u origin main

