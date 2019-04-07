# PlayLists

## Description

This is the main command for the PlayLists feature on LewdBot Music.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_PLAYLIST\_LIST | Yes |
| CMD\_PLAYLIST\_USE | Yes |
| CMD\_PLAYLIST\_CREATE | Yes |
| CMD\_PLAYLIST\_DELETE | Yes |
| CMD\_PLAYLIST\_RENAME | Yes |
| CMD\_PLAYLIST\_COPY | Yes |
| CMD\_PLAYLIST\_LOCK | Yes |
| CMD\_PLAYLIST\_SHUFFLE | Yes |
| CMD\_PLAYLIST\_MODE | Yes |

{% hint style="info" %}
All guilds have a default PlayList with the name of the guild, that can be used in case you don't want to clutter your personal playlists.
{% endhint %}

## Usages

### 1 - Help

```text
L!pl
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Listing your PlayLists

```java
L!pl list
```

By using the list subcommand, you will be presented with a list of all your playlists, along with their IDs.

This list will also include the default playlist of the guild \(Guild PlayList\).

### 3 - Using/Activating or Modifying a PlayList

```java
L!pl use <name>
```

The use subcommand will make LewdBot change the currently active PlayList of the server to the specified one. This also allows you to modify your playlist \(add/remove songs\).

### 4 - Creating a new PlayList

```java
L!pl create <name>
```

By using the create subcommand, along with specifying a name, LewdBot will create a new PlayList on your account, which can later be edited and/or used.

### 5 - Deleting a PlayList

```java
L!pl delete <name>
```

By using the delete subcommand, along with specifying a name, LewdBot will delete the playlist and all it's songs from the database **permanently**.

### 6 - Renaming a PlayList

```java
L!pl rename <name> <new name>
```

By using the rename subcommand, along with specifying the name of the playlist and the new name, LewdBot will rename the PlayList.

{% hint style="info" %}
This does not change the ID of the playlist.
{% endhint %}

### 7 - Duplicating a PlayList

```java
L!pl copy <name> <name>
```

By using the copy subcommand, along with specifying the name of the playlist and the name of the new playlist, LewdBot will duplicate the playlist with it's settings and songs to your account.

### 8 - Sharing a PlayList

```java
L!pl share <name> <true/false>
```

PlayLists on LewdBot are **not shared by default**, that means that only the owner can edit \(remove/add songs\).

By setting share to **true**, any user will be able to add or remove songs from it.

### 9 - Using shuffle

```java
L!pl shuffle
```

This command will enable \(or disable\) shuffle mode on the current playlist. This change is bound per playlist, which means that if you activate another playlist, this setting will be overridden by the setting of the other playlist.

{% hint style="info" %}
This command is a subcommand of the 'modes' command below, that one allows for more configuration.
{% endhint %}

### 10 - Changing PlayList modes

```java
L!pl mode <playList> <queue/shuffle> <true/false>
```

This command will enable \(or disable\) the specified flag on the specified playlist. This change is bound per playlist, which means that if you activate another playlist, this setting will be overridden by the setting of the other playlist.

Modes:

* Queue \(Deletes songs after they are played\).
* Shuffle \(Randomly selects songs from the PlayList\).

