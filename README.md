echo "# story" >> README.md
git init
git add README.md
git commit -n "first commit"
git branch -H main
git remote add orgin https://github.com/gptcs/story.git
git push -u origin main
