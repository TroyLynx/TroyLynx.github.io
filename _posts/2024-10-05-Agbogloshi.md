---
title: Agbogloshie
date: 2024-10-05 
categories: [CTF, BRCTF]
tags: [writeups, B2R]
math: true
mermaid: true
media_subpath:
image:
  path: ../assets/posts/BRCTF/2024-10-06-agbogloshie/agbobloshie.png
---


scaning agbogloshie we get 

```
    tcp://10.0.11.1:80
    tcp://10.0.11.1:5000
```

visiting port 80

![](../assets/posts/BRCTF/2024-10-06-agbogloshie/port80.png)

visiting 5000

![](../assets/posts/BRCTF/2024-10-06-agbogloshie/2ndport.png)

port 5000 is the target and we found an exploit

> changedetection <= 0.45.20 Remote Code Execution (RCE)

runing the exploit

![](../assets/posts/BRCTF/2024-10-06-agbogloshie/exrun.png)

and we are root

![](../assets/posts/BRCTF/2024-10-06-agbogloshie/root.png)

# Thank You..