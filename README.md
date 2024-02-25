![screenshot-temp](https://github.com/nnmdd/homescreen_cleaner/assets/97770937/64e6bf65-1ee5-44cf-89e1-eac8c6076deb)

!ROOT REQUIRED!

this script just nullifies all found portions of adware on lg webos 6.0+ homescreen.
however, the placeholders of the deleted sections remain in place, although they are not noticeable.
idea by @bashalarmist [https://github.com/bashalarmist/war-webos-ad-remover]

for install execute line below on TV via SSH:

```curl -L https://github.com/nnmdd/homescreen_cleaner/raw/main/homescreen_cleaner | sh -```

for uninstall:

delete file ```/var/lib/webosbrew/init.d/homescreen_cleaner```  and reboot TV

