# Anti-Spam

## Description

This feature makes LewdBot listen for and act on possible spam. This includes mention spam, message spam and channel spam.

It's recommended that [Mod Log](modlog.md) is enabled for this feature so you can have an overview of what is happening and when.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_ANTISPAM | No |

{% hint style="info" %}
LewdBot requires the **Manage Messages** and **Kick Members** permission for this feature.
{% endhint %}

## Usages

### 1 - Help

```text
L!antispam
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Enabling or Disabling

```java
L!antispam <enable/disable>
```

This command will enable or disable the Anti-Spam feature.

## Settings

Below is the available list of settings for this feature.

| Name | Description |
| :--- | :--- |
| automod.enabled | Enables or Disables AutoMod. |
| automod.antispam.enabled | Enables or Disables Anti-Spam \(message spam\) |
| automod.antispam.mention.enabled | Enables or Disables mention spam AutoMod. |
| automod.antiraid.auto | Enables or Disables auto Anti-Raid. |
| automod.antispam.user.amount | Number of similar messages from the same user to consider spam. |
| automod.antispam.chat.amount | Number of similar messages in a channel to consider spam. \(Affects Anti-Raid\). |
| automod.antispam.chat.raid | Number of channel spam detections to trigger raid protection. |
| automod.antispam.mention.count | Number of mentions in a single message to trigger AutoMod. |

