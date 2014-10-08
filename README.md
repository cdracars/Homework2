Homework2
=========

To see this page please visit: http://cdracars.github.io/Homework2

To setup project:
--------------------
git checkout -b gh-pages

git add .

git commit -m "Make pages visible"

git push -u --all

Change default branch on github in settings to the new gh-pages branch, then run the following on Cloud9:
--------------------
git branch -D master

git push origin :master
