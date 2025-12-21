---
description: >-
  Understand the difference between local and remote repositories and how push
  and pull connect them in the Git workflow.
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

# Local vs Remote

### Local vs Remote repositories

| Local Repository              | Remote Repository                 |
| ----------------------------- | --------------------------------- |
| Lives on your computer        | Lives on a server (e.g. GitHub)   |
| Stores commits and branches   | Stores shared project history     |
| Works offline                 | Requires internet                 |
| Used for personal development | Used for collaboration and backup |

#### How they are related

Local and remote repositories represent **two copies of the same project**.

* You work and commit changes locally.
* You synchronize those changes with the remote repository when needed.

{% hint style="warning" %}
Nothing is shared automatically.
{% endhint %}

### Push and Pull

| Push                  | Pull                       |
| --------------------- | -------------------------- |
| Local → Remote        | Remote → Local             |
| Shares your work      | Gets others’ work          |
| Requires commits      | Updates your local project |
| Used after committing | Used before starting work  |

{% hint style="info" %}
Commit locally, pull before work, push after work.
{% endhint %}

### Basic examples

```bash
# if it's a new project
git push origin main

# if it's an existing project
git pull
git push origin main
```

{% hint style="warning" %}
Only **committed changes** are pushed to the remote repository.

No commit = nothing to push.
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Diagrame_LocalVsRemote_lightmod.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Diagrame_LocalVsRemote.png" alt=""></picture><figcaption></figcaption></figure>

#### For deeper details:

[Pushing changes →](https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository)

[Pulling changes →](https://docs.github.com/en/get-started/using-git/getting-changes-from-a-remote-repository)
