# Ban

## Description

This command allows you to quickly ban an offending user.

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
L!ban
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Banning a member

```java
L!ban <member>
```

Specifying a member will make LewdBot ban that member from the server, also deleting the past 30 days of messages from that user.

### 3 - Banning with reason

```java
L!ban <member> <reason>
```

Specifying a reason along with the member will make LewdBot ban that member from the server and register the reason on the server's **Audit Logs**.

