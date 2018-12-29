# Voice

This command allows admins to quickly move and split users between voice channels.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_VOICE | No |

## Usages

### 1 - Help

```text
L!voice
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Moving a member to a channel

```java
L!voice move <member> <channel>
```

Specifying a member and a channel as parameters will make LewdBot move the member to that channel. 

Please note that the member already has to be in a voice channel.

### 3 - Moving all members of a channel to another channel

```java
L!voice move <channel> <channel>
```

Specifying two channels as parameters will make LewdBot move all members connected to the first channel to the second channel.

### 4 - Splitting members between channels

```java
L!voice split <channel> <channel>
```

Specifying two channels with the split command will make LewdBot split members between the two channels. This requires that all members that are to be split are in the first channel.

