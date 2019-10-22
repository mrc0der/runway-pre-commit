# runway-pre-commit

pre-commit module for Runway

## Usage

Add the following hook to your `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/mrc0der/runway-pre-commit
    rev: master
    hooks:
    -   id: runway-test
    -   id: runway-test-pipenv
```
