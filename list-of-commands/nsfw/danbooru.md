# Danbooru

## Description <a id="description"></a>

This command fetches images from [Rule34 ](https://danbooru.donmain.us/)and posts them in the channel upon request. Tags are supported.

### Permissions <a id="permissions"></a>

| Name | Default |
| :--- | :--- |
| CMD\_DANBOORU | Yes |

{% hint style="warning" %}
This command only works in channels that are marked as NSFW.
{% endhint %}

## Usages <a id="usages"></a>

### 1 - Fetching a random image <a id="1-fetching-a-random-image"></a>

```text
L!danbooru
```

This will fetch a random image from Danbooru and post it on the channel.

### 2 - Searching for an image <a id="2-searching-for-an-image"></a>

```java
L!danbooru <term>
```

Specifying a search term will make the bot search on [Rule34 ](https://danbooru.donmain.us/)for images that have a tag with that name and then post a random match on the channel.

