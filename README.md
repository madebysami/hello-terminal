# hello-terminal (devstats)

A tiny Bash script that prints a quick “developer stats” dashboard in your terminal, so you can confirm your local dev environment is set up and working.

## What it does

When you run `devstats.sh`, it prints:

- Your global Git user name and email
- Your Node and npm versions
- Your Git version
- Your Homebrew version
- Your current working directory
- Your current Git branch (or “Not a git repo”)
- How many project folders are inside `~/Developer/madebysami`

## Requirements

- macOS (or any system with Bash)
- `git`
- `node` and `npm`
- `brew` (Homebrew)

## Run it

```
chmod +x devstats.sh

./devstats.sh
```


## Notes

- If you run the script outside a Git repository, the branch line will show `Not a git repo`.
- The “GitHub Repos” count is the number of folders in `~/Developer/madebysami` (your local workspace directory), not a live count from GitHub.
