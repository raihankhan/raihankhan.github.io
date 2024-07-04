---
title: Bash Utilities
weight: 215
menu:
  notes:
    name: Utilities
    identifier: notes-bash-utilities
    parent: notes-bash
    weight: 10
---

<!-- delete go caches -->
{{< note title="Delete Golang Build Caches" >}}

Useful when you have lots of golang projects under a org

```bash
rm -rf ./src/kubedb.dev/*/.go/cache/
```
{{< /note >}}

<!-- Condition -->
{{< note title="Sort top 10 directories with most storage used" >}}

```bash
du -s * | sort -nr | head -n10
```
{{< /note >}}


<!-- Condition -->
{{< note title="install gdu" >}}
Run godu to analyze disk usage for a specific directory. Use arrow keys on the keyboard to navigate through the file system.
It is implemented in the Go programming language, known for its efficiency and performance.

```bash
sudo apt install gdu
gdu
```
{{< /note >}}