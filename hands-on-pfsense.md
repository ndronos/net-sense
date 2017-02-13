# pfSense Hands-On

## [iamsuperuser](http://iamsuperuser.blogspot.com)

... customized FreeBSD for use as a `firewall` and `router`



## Blacklist :: SquidGuard

System: Packages (Manager) : Available /  Installed

- Squid         | High performance web proxy cache
  SquidGuard    | High performance web proxy URL filter


Services: Proxy Server:
  Gereral
          Proxy Interface           > LAN
          Allow users on interface  > [uncheck]
          Transparent Proxy         > [enable]
          Enable logging            > [enable]

Services: Proxy Filter:
  General
          Logging Options
            Enable GUI log          > [enable]
            Enable log              > [enable]

          Blacklist options
            Blacklist               > [enable]
            Blacklist URL           > ... [squidguard.org/blacklists.html]
                                           Shalla's Blacklists [shallalist.de] Download URL, Paste
  Blacklist
          Download

  Common ACL
          Target Rules: Target Categories

          ...
          Default access [all]      access [allow]
          (Select category) eg: blk_BL_porn [deny]
                                      

          Do not allowIP-Address in URL > [enable]
          Log                           > [enable]

          [Save]

  General Settingd
          Enable [enable]
          Apply

          Service State: STARTED


Services: Proxy Server
          General
            Allow users on interface      [enable]
          [SAVE]


