# Prefix

## Description

This command changes LewdBot's default prefix, allowing you to customize it to your liking and/or stop bot conflicts.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_PREFIX | No |

{% hint style="info" %}
LewdBot will **always** respond to `L!` and `@LewdBot` regardless of custom prefix.
{% endhint %}

## Usages

### 1 - Help

```text
L!prefix
```

This will make LewdBot send a help block with the description about this command along with all it's available usages. This will also show the current custom prefix.

### 2 - Modifying the prefix

```java
L!prefix <string>
```

Specifying a prefix will make LewdBot change the prefix to the specified one.

Eg: `L!prefix $` would change LewdBot's prefix to `$` allowing you to use `$help`.

