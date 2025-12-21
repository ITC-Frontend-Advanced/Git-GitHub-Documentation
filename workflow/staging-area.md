---
description: >-
  Learn what the staging area is and how it helps you control what goes into a
  commit. The staging area is an intermediate step between the working directory
  and a commit.
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

# Staging Area

### What is the staging area?

* It allows you to choose **which changes** will be saved in the next snapshot.

Nothing is committed automatically.\
You decide what is included.

{% hint style="warning" %}
Without a staging area, every change would be committed together.
{% endhint %}

### The staging area lets you:

* Group related changes
* Exclude unfinished work
* Create clean, meaningful commits

### How it fits in the workflow?

The usual flow is:

1. Edit files in the working directory
2. Select changes for staging
3. Create a commit from staged changes

{% hint style="info" %}
You can stage some changes and leave others for later.
{% endhint %}

{% code title="Bash" overflow="wrap" %}
```bash
# Check file status
git status

# Stage a specific file
git add index.js

# Stage all modified files
git add .

```
{% endcode %}

{% hint style="info" %}
These commands move changes from the working directory into the staging area, preparing them for a commit.
{% endhint %}

When changes are staged:

* Git takes a snapshot of the selected files
* The snapshot is prepared for committing
* Other modified files remain untouched

{% hint style="warning" %}
Common beginner mistakes

* Staging everything without reviewing
* Forgetting to stage files before committing
* Mixing unrelated changes in one commit
{% endhint %}
