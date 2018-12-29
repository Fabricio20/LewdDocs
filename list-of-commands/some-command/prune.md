# Prune

## Description

This command allows an administrator to remove a large amount of messages from the chat in a single command.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_PRUNE | No |

{% hint style="info" %}
LewdBot requires the **`Manage Messages`** and **`Message History`** permissions for this feature.
{% endhint %}

## Usages

### 1 - Help

```text
L!prune
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Deleting old messages

```java
L!prune <number_of_messages>
```

Specifying a number of messages will make LewdBot delete the past X messages from the chat.

### 3 - Deleting messages from a user

```java
L!prune <number_of_messages> <member>
```

Specifying a member along with the number of messages will make LewdBot filter and delete only the last X messages from that user.

