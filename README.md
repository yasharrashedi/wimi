# What is my IP address (wimi)  

Very simple bash script (2 lines) to get your current **Public IP Address (WAN IP address).**  
Simply run  **wimi** command from command line in any path or directory.

Example:
```shell
user@pc:/any/path$ wimi
```
returns following:
```shell
My Public IP address: x.x.x.x
```
for example:
```shell
My Public IP address: 66.73.64.123
```

# Installation
```shell
sudo curl -L "https://raw.githubusercontent.com/yasharrashedi/wimi/master/wimi" -o /usr/local/bin/wimi && sudo chmod +x /usr/local/bin/wimi
```

# License
wimi is open source software licensed under the MIT License.  
Copyright © 2019-present, Yashar Rashedi.<br>

See the [LICENSE](https://github.com/yasharrashedi/wimi/blob/master/LICENSE) file for more.
