---
title: "Early May"
date: 2020-05-01T10:33:29-04:00
draft: true
---

Still on the Actions learning path. From now I will be adding some useful notes here from my daily learnings (when I remember to do so).

Creating a repo using the API

```
curl -u [username]:[token] \
-H "Accept: application/vnd.github.nebula-preview+json" \
-d '{"name":"api-test-repo","description":"creating this via API","private":false}' https://api.github.com/orgs/the-robots/[repo-name]
```


Deleting a repo using the API

```
curl -v -u [username]:[token] \
-H "Accept: application/vnd.github.nebula-preview+json" \
-X DELETE https://api.github.com/repos/[username]/[repo-name]
```

Use the API to pull your public IP

- https://www.ipify.org/


Homebrew for windows ?  `scoop` - https://scoop.sh

Old but just came across it... to install MetaSploit :D

Doing some tutorials on https://tryhackme.com


