# Softban

This command allows an admin to ban a member \(deleting messages\) and then automatically unbanning the member.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_SOFTBAN | No |

{% hint style="info" %}
LewdBot requires the **`Ban Members`** permission for this feature.
{% endhint %}

## Usages

### 1 - Help

```text
L!softban
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Softbanning a member

```java
L!softban <member>
```

Specifying a member will make LewdBot ban that member, delete the past 30 days of messages from that member and then unban the member.

### 3 - Softbanning with reason

```java
L!softban <member> <reason>
```

Specifying a reason along with the member will make LewdBot softban that member from the server and register the reason on the server's **Audit Logs**.

