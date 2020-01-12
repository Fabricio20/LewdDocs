# Configuration

## Description

LewdBot has a `settings` command that allows you to configure several things in-detail.

## Usage

### 1 - List settings

```text
L!settings
```

This command will show a small help block along with a paginated list of all available settings nodes.

### 2 - Read about a setting

```text
L!settings <name>
```

This will return a description about the chosen setting as well as the default value and current value.

### 3 - Update a setting

```text
L!settings <name> <value>
```

This command will update the setting `<name>` to have the `<value>` value.

{% hint style="info" %}
Make sure you are using the proper setting type, else an error will occur. \(Ie: Don't try setting an integer when it needs a boolean\).
{% endhint %}

