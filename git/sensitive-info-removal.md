# Accidentally committed sensitive info

## BFG
1. Download BFG tool [here](https://rtyley.github.io/bfg-repo-cleaner/)
2. Create `passwords.txt` and put all the sensitive info to be removed inside.
3. `java -jar <bfg.jar> --replace-text passwords.txt`
4. `git reflog expire --expire=now --all && git gc --prune=now --aggressive`
5. `git push --force`
