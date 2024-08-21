# install-tor-on-ubuntu

## download tor file in download folder /home/user/download/
 - wget `URL`
 - Example - `wget https://dist.torproject.org/torbrowser/13.5.2/tor-browser-linux-x86_64-13.5.2.tar.xz`

> USE THESE COMMANDS
```sh
 - ls
 - You can see this file > tor-browser-linux-x86_64-13.5.2.tar.xz
 - tar -xf tor-browser-linux-x86_64-13.5.2.tar.xz
 - after extract folder check the files - ls
```

> USE THIS CMD FOR GIVE PERMISSION
```sh
 - sudo chmod +x tor-browser
 - sudo chown -R $USER:$USER ~/tor-browser
 - Example - sudo chown -R alam:alam ~/tor-browser
 - cd tor-browser
 - Give both folder permissions  `Browser` `start-tor-browser.desktop`
 - Also give permissions inside of `browser` all files - chmod +x or chmod +777 and chown - Example like - sudo chown -R alam:alam ~/tor-browser
```
