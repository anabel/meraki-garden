---
tags: sources/article
---

I was once again looking for how to avoid typing ssh password once and again each time I made a commit.

I found this [stackexchange post](https://apple.stackexchange.com/questions/48502/how-can-i-permanently-add-my-ssh-private-key-to-keychain-so-it-is-automatically) where somebody explains how to do it:

> 1. Store the key in the keychain
````
ssh-add -K ~/.ssh/[your-private-key]`
````
> 3. Configure ssh to always use the keychain
````
Host *
   UseKeychain yes
   AddKeysToAgent yes
   IdentityFile ~/.ssh/id_rsa
````
