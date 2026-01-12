# Troubleshooting

## Changes not on GitHub?
Did you commit AND push?
```bash
git add . && git commit -m "msg" && git push
```

## Merge conflict?
1. Open file with `<<<<<<<` markers
2. Choose which code to keep
3. Remove markers
4. Commit

## Undo last commit?
```bash
git reset --soft HEAD~1
```

## Stuck?
- Ask in team chat
- Pair with someone
- Google the error
