| Flag | What you observed | Why it matters |
|-----:|------------------|----------------|
| 1 | Old dependency present in container | Introduces supply-chain risk |
| 2 | Files written to /tmp during processing | Indicates behavior beyond expected workflow |
| 3 | Subprocess spawned for hashing | Expands attack surface |
| 4 | Command executed with input-derived arguments | Risky if assumptions change |
| 5 | Assumes artifacts are trusted | Unsafe in evolving environments |
