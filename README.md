# git-pre-commit-check
Check files to be committed whether they contained banned words(like passwords) and stop commit

# Instructions
Either move this to your project's .git/hooks/ folder, or do a "ln -s ./pre-commit yourprojecetfolder/.git/hooks/pre-commit" to link the project to this repo's file.

On line 6, replace the words in the array with words/passwords that you don't want to allow in any git commit.  It will check all the staged contents of a commit for offending words.
