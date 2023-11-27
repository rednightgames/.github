## Commits ##

**Main rules:**

1. All commits must be in English.
2. It is forbidden to use the past tense.
3. A prefix must be used.
4. There must be no extra punctuation at the end.
5. The length should not exceed 100 characters.

**Branches:**

| Branch name   | Meaning                | Source branch | Example        |
|---------------|------------------------|---------------|----------------|
| **main**      | Production             | **dev**       |                |
| **dev**       | Canary                 | **main**      |                |
| **feature-*** | Features               | **dev**       | *feature-auth* |
| **hotfix-***  | Hotfixes in production | **main**      | *hotfix-auth*  |


![Workflow](https://github.com/rednightgames/.github/blob/main/.rednight/workflow.jpeg)
-----

**Structure:**

```
[Prefix] <Message>        
```

| Prefix         | Meaning                                | Example                                                 |                                                         |
|----------------|----------------------------------------|---------------------------------------------------------|---------------------------------------------------------|
| **[FIX]**      | All about fixing bugs                  | [FIX] Bug with failed authorization                     |                                                         |
| **[DOCS]**     | All about documentation                | [DOCS] Documenting Authorization API                    | [DOCS] Documenting Authorization API                    |
| **[FEATURE]**  | All about new features                 | [FEATURE] 2FA on authorization                          | [FEATURE] 2FA on authorization                          |
| **[STYLE]**    | All about typos and formatting         | [STYLE] Typos in the authorization module               | [STYLE] Typos in the authorization module               |
| **[REFACTOR]** | All about refactoring                  | [REFACTOR] Switching to EDA in the authorization module | [REFACTOR] Switching to EDA in the authorization module |
| **[TEST]**     | All about testing                      | [TEST] Coverage of the authorization module with tests  |                                                         |
| **[ANY]**      | Anything that doesn't fit the previous | [ANY] Connecting Travis CI                              | [ANY] Connecting Travis CI                              |
