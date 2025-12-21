---
description: Understand where files are edited and how Git detects changes.
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

# Working Directory

### What is the working directory?

The working directory is the folder on your computer where your project files live. like vs-code

{% hint style="info" %}
Before Git tracks anything, changes happen **here first**.
{% endhint %}

### How Git sees the working directory?

Git continuously compares:

* The current state of your files
* The last saved snapshot (commit)

If something changes, Git marks the file as **modified**.

#### File states in the working directory

* **Untracked** – new files Git doesn’t know yet
* **Modified** – files changed since the last commit

### Why the working directory matters

Understanding the working directory helps you:

* Avoid committing unfinished work
* Control what goes into a commit
* Debug unexpected changes

{% hint style="info" %}
Think of the working directory as your **draft area**. Nothing is permanent until you commit it.
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Diagrame_WorkingDirectory_lightmod.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Diagrame_WorkingDirectory.png" alt="Diagram explain what is working Directory in Git - ITC "></picture><figcaption></figcaption></figure>
