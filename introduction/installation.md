---
description: >-
  Learn how to install Git on your system using the command line or a desktop
  application, and understand which option fits your workflow.
layout:
  width: wide
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Git installation

### Install Git CLI (Recommended)

The Git command line interface is the standard way developers interact with Git and is required for most workflows.

{% tabs %}
{% tab title="Windows" %}
Download from : [Official website](https://git-scm.com/download/win)
{% endtab %}

{% tab title="macOS" %}
Using Homebrew:

```bash
brew install git
```

Or download from: [Official website](https://git-scm.com/download/mac)
{% endtab %}

{% tab title="Linux" %}
Using a package manager:

```bash
sudo apt
```
{% endtab %}
{% endtabs %}

#### Verify installation:

```bash
git --version
```

### Install Git Desktop (Optional)

A graphical interface can help visualize changes and commits, especially for beginners.

GitHub Desktop (official): [Download Here](https://desktop.github.com/)

{% hint style="info" %}
Git Desktop works alongside the Git CLI and does not replace it.
{% endhint %}

### Recommendation

{% hint style="info" %}
Use **Git CLI** as your primary tool.\
Use **Git Desktop** as a visual helper if needed.
{% endhint %}
