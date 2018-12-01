# Permissions

## Description

This command allows server admins to configure permissions on a role-by-role basis. With this feature you can create roles such as DJ and Moderator that have specific LewdBot permissions.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_PERMS | No |

{% hint style="info" %}
If you want to edit permissions for default members \(no roles\) use **`everyone`** as the role name.
{% endhint %}

## Usages

### 1 - Help

```text
L!perms
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Listing all available permissions

```java
L!perms list
```

To view a list of all available permissions you can use the list subcommand or visit the List of Permissions page.

{% page-ref page="../../list-of-permissions.md" %}

### 3 - Listing permissions for a role

```java
L!perms get <role>
```

By using the get command along with specifying a role you will be presented with a list of all permissions that are defined for that role \(and their `ALLOW/DENY` status\).

{% hint style="info" %}
Please note that permissions which have default values will not be displayed.
{% endhint %}

### 4 - Resetting a role

```java
L!perms reset <role>
```

By using the reset command along with specifying a role, LewdBot will delete all permission configurations for that role \(revert to default\).

### 5 - Removing a node

```java
L!perms clear <role> <node>
```

By using the reset command and specifying a role and a [node](../../list-of-permissions.md), LewdBot will remove that specific permission configuration for that role \(revert to default\).

### 6 - Defining permissions

```java
L!perms set <role> <node> <allow/deny>
```

By using the set command, along with specifying a role, a node and a status, LewdBot will create \(or update\) the configuration of that role for that node.

In other words, if you use `L!perms set everyone CMD_CONNECT deny` you will block all members from making LewdBot joining a voice channel.

{% hint style="warning" %}
Permission calculation is hierarchical, so if a member has a role that denies a permission but a role that allows it above, the member will be able to use the command.
{% endhint %}

