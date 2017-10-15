![](http://i.imgur.com/qQsN78U.png)
____
[![Gitter](https://badges.gitter.im/tidusjar/Ombi.svg)](https://gitter.im/tidusjar/Ombi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Build status](https://ci.appveyor.com/api/projects/status/hgj8j6lcea7j0yhn?svg=true)](https://ci.appveyor.com/project/tidusjar/requestplex)
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxserver/ombi.svg)](https://hub.docker.com/r/linuxserver/ombi/)
[![Github All Releases](https://img.shields.io/github/downloads/tidusjar/Ombi/total.svg)](https://github.com/tidusjar/Ombi)
[![firsttimersonly](http://img.shields.io/badge/first--timers--only-friendly-blue.svg?style=flat-square)](http://www.firsttimersonly.com/)


[![Patreon](https://www.ombi.io/img/patreondonate.svg)](https://patreon.com/tidusjar/Ombi)
[![Paypal](https://www.ombi.io/img/paypaldonate.svg)](https://paypal.me/PlexRequestsNet)

[![Report a bug](http://i.imgur.com/xSpw482.png)](https://github.com/tidusjar/Ombi/issues/new) [![Feature request](http://i.imgur.com/mFO0OuX.png)](http://feathub.com/tidusjar/Ombi)


| Service  | Master (Version 2.0 - Recommended)                | Open Beta     (Version 3.0)          |
|----------|:---------------------------:|:----------------------------:|
| AppVeyor | [![Build status](https://ci.appveyor.com/api/projects/status/hgj8j6lcea7j0yhn/branch/master?svg=true)](https://ci.appveyor.com/project/tidusjar/requestplex/branch/master) | [![Build status](https://ci.appveyor.com/api/projects/status/hgj8j6lcea7j0yhn/branch/DotNetCore?svg=true)](https://ci.appveyor.com/project/tidusjar/requestplex/branch/DotNetCore) | 
| Download |[![Download](http://i.imgur.com/odToka3.png)](https://github.com/tidusjar/Ombi/releases)            |      [![Download](http://i.imgur.com/odToka3.png)](https://ci.appveyor.com/project/tidusjar/requestplex/branch/DotNetCore/artifacts)       | 
# Features
Here are some of the features Ombi V3 has:
* Now working without crashes on Linux.
* Lets users request Movies and TV Shows (whether it being the entire series, an entire season, or even single episodes.)
* Easily manage your requests
* User management system (supports plex.tv, Emby and local accounts)
* A landing page that will give you the availability of your Plex/Emby server and also add custom notification text to inform your users of downtime.
* Allows your users to get custom notifications!
* Secure authentication so you don't have to worry about those script kiddies
* Will show if the request is already on plex or even if it's already monitored.
* Automatically updates the status of requests when they are available on Plex/Emby
* Slick, responsive and mobile friendly UI
* Ombi will automatically update itself :)
* Very fast system.

### Integration 
We integrate with the following applications:
* Plex Media Server
* Emby
* Sonarr
* Radarr (beta)
* DogNzb
* Couch Potato


### Notifications
Supported notifications:
* SMTP Notifications (Email)
* Discord
* Slack
* Pushbullet
* Pushover
* Mattermost

### The difference between Version 3 and 2

Over the last 7 months, we focused on the main functions on Ombi, a complete rewrite while making it better, faster and more stable.
We have already done most of the work, but some features are still be missing in this first version.
We are planning to bring back these features in Version 3 but for now you can find a list below with a comparison of features between v2 and v3.


| Service  | Version 3 | Version 2 |
|----------|:----------:|:----------:|
| Supported online | Yes | No |
|Multiple Plex/Emby Servers| Yes | No |
| Emby & Plex support | Yes | Yes |
| Mono dependency | No | Yes |
| Notifications support | Yes| Yes |
| Landing page | Yes (brand new) | Yes |
| Login page | Yes (brand new) | Yes |
| Custom Logo in Ombi and notifications | Yes | No |
| Sending newsletters | Planned | Yes |
| Send a Mass Email | Planned | Yes |
| SickRage | Planned (not supported yet)| Yes |
| CouchPotato | Yes | Yes |
| Watcher | Planned | Yes |
| DogNzb | Yes | No |
| Headphones | No (support dropped) | Yes |

# Feature Requests
Feature requests are handled on FeatHub.

Search the existing requests to see if your suggestion has already been submitted.
(If a similar request exists, give it a thumbs up (+1), or add additional comments to the request)

#### [![Feature Requests](https://cloud.githubusercontent.com/assets/390379/10127973/045b3a96-6560-11e5-9b20-31a2032956b2.png)](http://feathub.com/tidusjar/Ombi)

# Preview

![Preview](http://i.imgur.com/yrz2pzl.gif)

# Installation

Windows: Download the windows zip file above and run ombi.exe

Linux: Download the linux zip file, run chmod +x Ombi to make the Ombi file an executable.

Get the following error? 
libunwind.so.8: cannot open shared object file
You may need to install libwind8.
```apt-get install libunwind8```

# FAQ
Do you have an issue or a question? if so check out our [FAQ](https://github.com/tidusjar/Ombi/wiki/FAQ)!

# Contributors

We are looking for any contributions to the project! Just pick up a task, if you have any questions ask and i'll get straight on it!

Please feel free to submit a pull request!

# Donation
If you feel like donating you can donate with the below buttons!

[![Patreon](https://www.ombi.io/img/patreondonate.svg)](https://patreon.com/tidusjar/Ombi) 
[![Paypal](https://www.ombi.io/img/paypaldonate.svg)](https://paypal.me/PlexRequestsNet)

### A massive thanks to everyone for all their helps!

## Stats
[![Throughput Graph](https://graphs.waffle.io/tidusjar/PlexRequests.Net/throughput.svg)](https://waffle.io/tidusjar/PlexRequests.Net/metrics/throughput)

### Sponsors ###
- [JetBrains](http://www.jetbrains.com/) for providing us with free licenses to their great tools
    - [ReSharper](http://www.jetbrains.com/resharper/)
