# fix-commit-email-history
This bash script use `git filter-branch` to fix commit metadata.
## How to use
- clone the repo you want to change
- copy this bash script into the repo
- modify `OLD_EMAIL`, `CORRECT_NAME`, `CORRECT_EMAIL`
- run the script
- run `git push --force -tags origin 'refs/heads/*'`
