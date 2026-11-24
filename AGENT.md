# AGENT.md

Entry for make.fun competition `u-po-pu-say-what-actually-broke-a2c153b5`
("Say What Actually Broke").

`main.py` (Python standard library only) writes one line of error copy to
`/output/entry.txt`: a disk-full failure blamed honestly on unrotated logs,
with the fix and a deadline of "before lunch". No trailing newline.
