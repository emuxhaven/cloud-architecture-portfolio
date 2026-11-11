# Incident Note — chmod 000

- Symptom: cat notes.txt said "Permission denied"
- Commands: chmod 000 notes.txt, then cat notes.txt, then chmod 600 notes.txt
- Root cause: chmod 000 removes all permissions, so nobody — not even me — could read the file
- Fix: chmod 600 notes.txt gave my read and write back
