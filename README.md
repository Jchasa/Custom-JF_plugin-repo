# Custom Jellfin Plugin Repo
### Specifically ones that I suggest and use plugin repository for Jellyfin Media Server

# Installation
1. Open Jellyfin dashboard
2. Naviage to to catalogue settings
3. (Optional) Remove all old repositories including the default jellyfin repo, this speeds up catalogue loading
4. Add the universal repository
```
https://raw.githubusercontent.com/Jchasa/Custom-JF_plugins/refs/heads/main/manifest.json
```
# Security
Most sources are from [awesome-jellyfin](https://github.com/awesome-jellyfin/awesome-jellyfin)
The rest are from reputable developers, each source is reviewed before being added.
There is minimal risk from having even a known bad repository installed, as this project by nature acts as a proxy between your server and a malicious repository protecting your IP, however this stops being the case when you install a plugin since code is not proxied and could contain malware.

Make sure you only install plugins you recognise.


