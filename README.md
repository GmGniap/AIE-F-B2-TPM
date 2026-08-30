# AIE-F-B2
AI Engineering (Fundamental) Class, Batch-2 by Dr.Ye Kyaw Thu

# Branching Rule for this Repo
- When creating a feature branch for an upstream contribution, start it from `upstream/main` rather than own modified `origin/main`. That way, this repo's PR will only contain actual feature code, not sync workflow.
- And never merge feature branches into this fork repo's `origin/main` branch to prevent merge divergence, keep sync clean.
- To create new branch:
```
# Fetch latest original code
git fetch upstream

# Create feature branch directly from the upstream base
git checkout -b feature/my-cool-feature upstream/main
```

- One-time setup to be able to run above command
```
git remote add upstream https://github.com/ye-kyaw-thu/AIE-F-B2.git
```
