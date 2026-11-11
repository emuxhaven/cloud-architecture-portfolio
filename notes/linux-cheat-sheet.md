# Linux Cheat Sheet — Week 2, Block 1

1. cd ~/practice-week2 — go to a folder
2. ls -l — list with permissions, owner, size
3. pwd — show where I am
4. ls -la — list everything, including hidden files
5. mkdir archive — make a folder
6. touch report.txt data.txt — make empty files
7. cp notes.txt archive/ — copy a file
8. ls archive/ — peek inside a folder without going in
9. mv data.txt archive/ — move a file
10. echo "hello linux world" > report.txt — write text into a file
11. cat report.txt — read a file
12. grep linux report.txt — search for a word in a file
13. grep windows report.txt — no match prints nothing
14. chmod 644 notes.txt — I read/write, others read only
15. chmod 000 notes.txt — nobody can read it
16. chmod 600 notes.txt — private, only I can read/write
17. sleep 120 & — start a process in the background
18. ps aux | grep sleep — find a running process
19. kill 5032 — stop a process by its PID
20. echo "theme=dark" > app.conf — make a config file
21. nano app.conf — edit a file (Ctrl+O save, Ctrl+X exit)
22. cat app.conf — check the config change
23. cd — go home
24. tar -czf backup.tar.gz practice-week2 — archive a folder
25. ls -lh backup.tar.gz — list with human-readable sizes
