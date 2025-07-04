# fix-commit-email-history
use `git filter-branch`
- clone the repo you want to change
- copy this bash script into the repo
- modify `OLD_EMAIL`, `CORRECT_NAME`, `CORRECT_EMAIL`
- run the script
- run `git push --force -tags origin 'refs/heads/*'`
