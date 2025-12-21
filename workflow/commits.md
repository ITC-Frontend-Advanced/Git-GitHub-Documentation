---
description: >-
  Learn what a Git commit is and how commits create a clear and reliable history
  of your project.
---

# Commits

### What is a commit?

A commit is a **snapshot** of your project at a specific moment in time.

#### It records:

* The staged changes
* A message describing what changed
* A unique identifier (hash)

#### Commits allow you to:

* Track progress over time
* Understand why changes were made
* Revert to earlier versions safely

### How commits fit in the workflow

* Edit files
* Stage selected changes
* Create a commit

{% hint style="info" %}
Only staged changes are included in a commit.
{% endhint %}

### Creating a commit (example)

```bash
# Create a commit with a message
git commit -m "Add login form validation"

# This command saves the staged changes as a snapshot in the local repository.
```

#### Writing good commit messages

* Short and clear
* Describes _what_ changed, not _how_
* Written in present tense

{% hint style="danger" %}
❌ changes
{% endhint %}

{% hint style="success" %}
✅ Fix navbar alignment on mobile
{% endhint %}

[Full more information about commit message check here →](../others/commit-message.md)

{% hint style="warning" %}
Common beginner mistakes

* Committing too many unrelated changes
* Using vague messages
* Forgetting to stage files before committing
{% endhint %}

<img src="../.gitbook/assets/file.excalidraw (2).svg" alt="" class="gitbook-drawing">

