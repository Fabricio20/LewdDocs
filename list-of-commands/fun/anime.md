# Anime

## Description

This command allows users to search for anime information/metadata. All the content is provided by the [Kitsu](https://kitsu.io/) API.

### Permissions

| Name | Default |
| :--- | :--- |
| CMD\_ANIME | Yes |

{% hint style="info" %}
LewdBot requires the **`Embed Links`** permission for this feature.
{% endhint %}

## Usages

### 1 - Help

```text
L!anime
```

This will make LewdBot send a help block with the description about this command along with all it's available usages.

### 2 - Finding info

```java
L!anime <name>
```

Specifying an anime name will make LewdBot search on Kitsu and return all the information available about it, including cover picture.

{% hint style="warning" %}
Animes that are marked as NSFW \(eg: Futa-bu\) will only show in NSFW channels.
{% endhint %}

