# Ignore

## Description

This command allows administrators to configure channels which LewdBot will ignore.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_IGNORE | No |

{% hint style="danger" %}
LewdBot will **NOT** respond to **ANY** commands on these channels.
{% endhint %}

{% hint style="info" %}
If you accidentally ignore all channels, create a new one and remove the other ones from there.
{% endhint %}

## Usages

### 1 - Help

```text
L!ignore
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - List ignored channels

```java
L!ignore list
```

The list subcommand will send a list of all currently ignored channels.

### 3 - Ignoring a channel

```java
L!ignore add <channel>
```

By using the add subcommand, along with specifying a channel, LewdBot will add that channel to the ignored channels list and will immediately stop responding to commands on it.

### 4 - Removing an ignored channel

```java
L!ignore remove <channel>
```

By using the remove subcommand, along with specifying a channel, LewdBot will remove that channel from the ignore list and sub-sequentially start responding to commands on it.

{% hint style="info" %}
Make sure to run this command on a channel that is **NOT** being ignored.
{% endhint %}

