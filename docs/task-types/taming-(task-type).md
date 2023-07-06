---
title: taming
parent: Built-in task types
grand_parent: Task types
---

# taming (task type)

Since v3.13
{: .label .label-green }

Tame a set amount of animals.

## Options

| Key      | Description                                     | Type                | Required | Default | Notes |
|----------|-------------------------------------------------|---------------------|----------|---------|-------|
| `amount` | The number of animals to tame.                  | Integer             | Yes      | \-      | \-    |
| `worlds` | Worlds which should count towards the progress. | List of world names | No       | \-      | \-    |

## Examples

Tame 10 animals:

``` yaml
taming:
  type: "taming"
  amount: 10                            # amount of mobs tamed
  worlds:                               # (OPTIONAL) restrict to certain worlds
   - "world"
```
