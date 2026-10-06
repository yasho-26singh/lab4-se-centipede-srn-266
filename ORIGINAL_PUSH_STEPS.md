# Push steps (run on your own computer, signed in as yasho26shreya)

Do NOT open a PR to SETAPESU26.

## A) Code with separate commits per task (your fork/copy of the assigned repo)
1. On GitHub, fork https://github.com/SETAPESU26/27_centipede to yasho26shreya (Fork button; or create an empty repo and push to it).
2. In a terminal:
   git clone centipede_with_commits.bundle 27_centipede
   cd 27_centipede
   git remote set-url origin https://github.com/yasho26shreya/27_centipede.git
   git push -u origin HEAD:main
   (If rejected, check the branch name with `git branch -a` and use master instead of main if needed.)

## B) Lab-4 folder in your Lab repo
Copy the `Lab-4` folder (before.mp4, after.mp4, game.py, README.md, chat_history.pdf) into your Lab repo, then:
   git add Lab-4
   git commit -m "Lab 4: VibeCoding deliverables"
   git push
