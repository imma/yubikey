---
date: 2016-03-08T21:07:13+01:00
title: yubikey block
type: index
weight: 0
---

Downloads:

https://www.yubico.com/support/knowledge-base/categories/articles/yubikey-neo-manager/

Guides:

https://www.yubico.com/support/knowledge-base/categories/articles/use-yubikey-openpgp/

Hrm...

http://karl.kornel.us/2017/10/welp-there-go-my-git-signatures/

Save the one-time exported gpg key:

    find .gnupg/sk*

Generate the public gpg key:

    gpg2 --armor --export $email

Generate the ssh key from the gpg key:

    ssh-add -L

Change yubikey pin:

    gpg2 --card-edit
