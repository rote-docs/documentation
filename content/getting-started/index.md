+++
title = "Getting Started"
description = "All you need to know to get a site up and running with Hugo and Rote"
weight = 0
+++

If you don't have Hugo yet, head on over to [Hugo's documentation](https://gohugo.io/getting-started/installing/) for information on how to get it installed on your system.

Once you have Hugo installed, you can create a new site with this theme by running the following commands.

{{< notice "warning" >}}
The commands below should work for Linux and MacOS, but _probably_ won't for Windows users.
{{< /notice >}}


```bash
hugo new site mysite
cd mysite
git init
git submodule add https://github.com/rote-docs/rote.git themes/rote
cp -r themes/rote/exampleSite/* .
hugo server
```

Once the above commands have completed, you should have a (mostly) blank Hugo site to start working with.
