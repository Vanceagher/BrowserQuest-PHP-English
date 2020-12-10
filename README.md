# BrowserQuest-PHP-English
BrowserQuest server in PHP

![BrowserQuest width workerman](https://github.com/walkor/BrowserQuest-PHP/blob/master/Web/img/screenshot.jpg?raw=true)

## Install
1 `git clone https://github.com/Vanceagher/BrowserQuest-PHP-English`

2 `composer install `

3 Edit `Web/config/config_local.json` to change the host to your computer's IP ([How do I get my IP?](https://www.businessinsider.com/how-to-find-ip-address-on-windows))

## Start and Stop for Linux

| Start in debug mode  | `php start.php start`    |
| Start in daemon mode | `php start.php start -d` |
| Check status         | `php start.php status`   |
| Stop                 | `php start.php stop`     |

## How to play
Go to [here](http://localhost:8787/)

## Start and Stop for Windows
Double click start_for_win.bat for start.
Press ctrl + c to stop.

## Description
The game [BrowserQuest](https://github.com/mozilla/BrowserQuest) was odified, mainly to use php for the back-end nodejs part（[workerman](https://github.com/walkor/workerman)）rewrite.

## [Original Repo](https://github.com/mozilla/BrowserQuest)
