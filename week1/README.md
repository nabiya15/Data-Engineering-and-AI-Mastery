### 12/26/2025 Update

| Step | Command                                     | What it does                    | Why it matters                                         |
| ---- | ------------------------------------------- | ------------------------------- | ------------------------------------------------------ |
| 1    | `git clone <repo>`                          | Downloads full repo + history   | Shows you treat main as sacred, never code in web UI   |
| 2    | `cd <repo>`                                 | Enters project folder           | Keeps every future command inside version control      |
| 3    | `git switch -c boiler-plate`                | Creates & checks out new branch | Modern Git (2019+), protects main, enables review flow |
| 4    | `mkdir -p week1/{src,tests,docs}`           | Builds nested dirs in one shot  | Mirrors real Python packaging; -p avoids errors        |
| 5    | `touch week1/{README.md,setup_log.txt}`     | Creates empty placeholder files | Empty dirs don’t sync; docs appear before any code     |
| 6    | `cat > file << EOF ... EOF`                 | Inline multi-line text writer   | CLI fluency: can create code on headless servers       |
| 7    | `git add .`                                 | Stages all new/modified files   | Conscious staging, no accidental build artefacts       |
| 8    | `git commit -m "chore: ..."`                | Records snapshot with tag       | Conventional commits → auto-changelogs, clean history  |
| 9    | `git push origin boiler-plate`              | Uploads branch to remote        | Enables CI & peer review, backs up work                |
| 10   | `git switch main && git merge boiler-plate` | Fast-forward merge              | Linear history, trunk-based development habit          |
