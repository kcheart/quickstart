+++
title = 'My First Post'
date = 2023-11-14T15:46:27+08:00
draft = false

summary = 'Use Hugo to setup website'

+++

# IT Notes

Hogo 指令教學:


```shell
hugo new site quickstart
cd quickstart

git init

git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)

echo "theme = 'PaperMod'" >> hugo.toml

hugo new content posts/my-first-post.md

hugo server -D
```

Plan and Reality 1:

![Plan vs Reality](plan_and_reality.jpg)

Plan and Reality 2 (static):

![Plan vs Reality](/plan_and_reality.jpg)

Plan and Reality 3:

![Plan vs Reality](/images/plan_and_reality.jpg)

Plan and Reality 4:

![Plan vs Reality](images/plan_and_reality.jpg)

Plan and Reality 5 (quickstart):

![Plan vs Reality](/quickstart/plan_and_reality.jpg)