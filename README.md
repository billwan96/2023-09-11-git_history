# 2023-09-11-git_history

- `add <FILENAMES>`: adding the <FILENAMES> to the staging area
- `commit - <MESSAGE>`: commit with a message everything in the staging area
- `push <WHERE> <WHAT>`: push the history/commits to the remote (where: eg origin) using the commits from the specified branc (what eg. main/master)
- `pull <WHERE> <WHAT>`: pulls (updates) the local repo with contents in the remote (where) using the informaiton in the specified branch (what)

- `log`: show the log
    - `log --oneline`: shows the log in condenced format
    - this may open a termianl program called `less` that lets you scroll.
        - use `q` to quit out of less

-  `diff`: shows the "difference" between your changes and the last know git state
    - `diff --staged`: shows you the differece of the files in the staging area

-  `restore --staged <FILE>`: unstages <FILE> from the staging area

-- here are something i dont want