# apt

before, after.

```diff
- apt-get update
+ apt u

- apt-get upgrade
+ apt upgrade
+ apt up

- apt-get update && apt-get upgrade
+ apt uup                            (uup = u + up)

- apt-get update && apt-get upgrade -dy
+ apt uup -dy
+ apt dl                             (dl for download)

- apt-get dist-upgrade
+ apt     dist-upgrade

- apt-get remove pkg1
+ apt     remove pkg1

- apt-get install   pkg1
+ apt install       pkg1
+ apt inst          pkg1

- apt-cache search pattern1
+ apt search       pattern1
+ apt s            pattern1

- debtags   search 'deb::tag && deb::tag2'
+ apt       search 'deb::tag && deb::tag2'

- apt-cache policy pkg1
+ apt policy       pkg1
+ apt pol          pkg1
+ apt p            pkg1

- apt-cache show   pkg1
+ apt show         pkg1

- apt-get purge    pkg1
+ apt purge        pkg1

- apt-get install --reinstall pkg1
+ apt reinstall    pkg1

- apt-mark hold    pkg1
+ apt hold         pkg1

- apt-mark showhold
+ apt hold

- apt-mark unhold  pkg1
+ apt unhold       pkg1

```
