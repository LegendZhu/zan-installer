# Youzan ZanPhp Installer

## Installation
The recommended way to install zan-installer is through
[Composer](http://getcomposer.org).

```bash
# Install Composer
curl -sS https://getcomposer.org/installer | php
```
See [Composer Getting Started](https://getcomposer.org/doc/00-intro.md)


```bash
composer global require youzan/zan-installer
```
The composer repository on packagist.org: [youzan/zan-installer](https://packagist.org/packages/youzan/zan-installer) 。

## Update
Use the following command to update zan-installer:

```bash
composer global update
```


## Use
Now, you can open your favorite Terminal tool, type `zan` to use!

```bash
~/Sites zan↵
   __    __
  /\ \  /\ \
  \ `\`\\/'/ ___   __  __  ____      __      ___
   `\ `\ /' / __`\/\ \/\ \/\_ ,`\  /'__`\  /' _ `\
     `\ \ \/\ \L\ \ \ \_\ \/_/  /_/\ \L\.\_/\ \/\ \
       \ \_\ \____/\ \____/ /\____\ \__/.\_\ \_\ \_\
        \/_/\/___/  \/___/  \/____/\/__/\/_/\/_/\/_/
Create a new ZanPhp application.
Which type application would you create? (use <space> to select)
❯ ● HTTP
  ○ TCP
Your application name: (ex: zanphp-demo) demo
Your application namespace: (ex: zanphp/zanhttp) youzan/demo
Please input a output directory:
~/Sites
Downloading the source code archive ...
Extracting archive ...
Congratulations, your application has been generated to the 
following directory.
~/Sites/demo/
See ~/Sites/demo/README.md for information on how to run.
```

## Also see
- [Youzan php framework &#9992;](https://github.com/youzan/zan) 
- [ZanPhp HTTP demo for zan framework &#9992;](https://github.com/youzan/zanhttp)

## License
The zan-installer is open-sourced software licensed under the Apache-2.0 license.

