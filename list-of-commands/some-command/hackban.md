# Hackban

## Description

This command allows an admin to ban users that are NOT in the server \(by using their account's ID\). This feature is extremely useful for banning spambots before they even join your server.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_BAN | No |

{% hint style="info" %}
LewdBot requires the **`Ban Members`** permission for this feature.
{% endhint %}

## Usages

### 1 - Help

```text
L!hackban
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Banning an id

```java
L!hackban <id>
```

Specifying an ID will make LewdBot ban that id from the server. If a member with that ID is present, it will be kicked.

### 3 - Banning with reason

```java
L!hackban <id> <reason>
```

Specifying a reason along with the ID will make LewdBot ban that member from the server and register the reason on the server's **Audit Logs**.



