---
sidebar_label: all
---

# all(iterable)

### Input
An iterable.

### Output
True if all items are identical, False otherwise.

### Example
```yaml
actions:
-   name: trigger-slack
    if: "keep.all({{ steps.db-step.results }})"
    provider:
        type: slack
        config: " {{ providers.slack-demo }} "
        with:
            message: "Items are equal"
```
