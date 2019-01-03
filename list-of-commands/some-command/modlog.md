# ModLog

This command allows admins to create a channel where moderated actions are posted to, such as Kicks, Bans and Unbans.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_MODLOG | No |

## Usages

### 1 - Help

```text
L!modlog
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Enabling ModLog

```java
L!modlog <channel>
```

Specifying a channel will make LewdBot enable the ModLog functionality on said channel. 

All future moderated actions will be posted to this channel as well as reason updates that involve the `L!reason` command.

### 3 - Disabling ModLog

```java
L!modlog off
```

This subcommand will disable the modlog.

