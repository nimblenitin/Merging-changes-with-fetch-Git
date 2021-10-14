# Merging-changes-with-fetch-Git

When you use pull, Git tries to automatically merge. When you fetch, Git gathers any commits from the target branch that do not exist in your current branch and stores them in your local repository. However, it does not merge them with your current branch.

Steps to perform fetch and merge-

```

1. Create a repo in Github

2. Add remote origin for your local repo
$ git remote add origin <Your HTTPS_URL>
$ git remote -v

3. Pull the changes to local repo
$ git pull origin main --allow-unrelated-histories

4. Make changes to file on Github

5. Do a fetch in local repo to update local repo
$ git fetch

6. Finalize the merge by creating a new commit using the following command:
$ git commit -m "'Merge' demo.txt from"

```
