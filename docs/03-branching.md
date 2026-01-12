# Branching

Branches let you work without breaking the main code.

## Create Branch
**GitHub Desktop:** Current Branch → New Branch

**Terminal:**
```bash
git checkout -b feature/your-name/description
```

## Branch Naming
Format: `type/name/description`
- `feature/ali/add-climber`
- `fix/zeynep/motor-direction`

## Keep Updated
```bash
git checkout main
git pull
git checkout your-branch
git merge main
```

**Next:** [Pull Requests](04-pull-requests.md)
