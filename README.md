# one

git init
echo "hi" > f1.txt
echo "hi hello" > f2.txt
git add f1.txt
git status
git commit -m"file f1 is commited"
git status
git add .
git status
git commit -m"all file is commited"
touch index.html .gitignore error.log
git add .
git status
git commit -m"commit all files except error.log"
git log
history -a
