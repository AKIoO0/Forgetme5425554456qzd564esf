---
title: Add account
excerpt: 'ajoute un compte '
deprecated: false
hidden: true
link:
  new_tab: false
metadata:
  robots: index
---
[https://pztrade.xyz/add\_account](https://pztrade.xyz/add_account)

request.post(data=\{ &#x20;
"name" : username #ex Akio
"fee" : gas\_fee #ex 0.001
"buy\_method" : "fixed/flexible"
"Buy\_amount" : 1  #Si c'est fixed ça sera 1 sol si c'est flexible ça sera 1%"max\_trades" : 5 #nombre de trade max par jours