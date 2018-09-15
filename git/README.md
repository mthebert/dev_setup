$ git config --global user.name "Matt Thebert"
$ git config --global user.email mthebert@hearstautos.com

git remote add origin https://github.com/user/repo.git
# Set a new remote
git remote -v
# Verify new remote
origin  https://github.com/user/repo.git (fetch)
origin  https://github.com/user/repo.git (push)

https://stackoverflow.com/questions/17659206/git-push-results-in-authentication-failed
git remote -v
git remote remove origin
git remote add origin git@github.com:user/repo.git