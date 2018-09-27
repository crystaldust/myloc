A simple script to calculate the author's line of code in a git repo

## How it works

The script use `git log` to fetch all the author's commits, then iterate the commits to see how many insertions and deletions in each commit, then accumulate the numbers.

The model is pretty rough, it's just an estimation of LOC.
