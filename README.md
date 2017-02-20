# transfer-local-remote

## creation 

```
  cd Dropbox/AIND/
  git clone https://github.com/udacity/AIND-Sudoku.git
  source activate aind
  cd AIND-Sudoku/
  rm -r .git
  git init
  git add .
  git commit -m "first commit"
  git remote add origin https://github.com/JordiTorresUdacity/AIND-Sudoku.git
  git push -u origin master
  ```
  
  
## local --> remote
```
git push -u origin master
```

## remote --> local
```
git pull origin master
```
