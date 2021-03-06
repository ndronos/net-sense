# net-sense

# [pfSense](https://www.pfsense.org)

https://forum.pfsense.org/ | https://doc.pfsense.org/ | https://github.com/pfsense | https://www.reddit.com/r/PFSENSE/ | https://twitter.com/pfsense

---

## [pfSense Fundamentals and Advanced Application](https://www.pfsense.org/university/) Course
```
  - Two full-days training event
  - Prerequisites: Attendees should have a basic understanding of networking and firewalls.
  - No prior knowledge with pfSense software is necessary.
```

```
Day One

Introduction      Project history and overview,
                  hardware selection, etc.

The Basics        Installation, configuration, GUI,
                  backup, restore
                  upgrades and interfaces.

The Firewall      Basic rules, aliases, best practices,
                  interface grouping, and 
                  advanced firewall options.

NAT 101           Interaction with firewall rules,
                  port forwards,
                  1:1 NAT, and 
                  outbound network address translation.

Services          DHCP and relay,
                  DNS forwarding, dynamic DNS,
                  SNMP, NTP server,
                  Wake on LAN.

VPN               Overview, selecting the appropriate VPN,
                  remote access with IPsec, OpenVPN and PPTP,
                  Site to Site with IPsec and OpenVPN.
```

```
Day Two

Multi-WAN         Overview, best practices,
                  failover and load balancing,
                  policy routing,
                  advanced options.
                  
VLANs             Switch configuration,
                  firewall configuration.
                  
High Availability       Overview, network design considerations,
                        basic CARP configuration,
                        multi-WAN,
                        multi-LAN
                  
Miscellaneous Topics    Bridging,
                        captive portal,
                        system monitoring,
                        package system overview.
```

## [pfSense 2 Cookbook](https://www.packtpub.com/networking-and-servers/pfsense-2-cookbook) (Williamson, 2011) 252p

A practical, example-driven guide to configure even the most advanced features of pfSense 2

```
    pfSense 2 Cookbook
    _______________________________________________
    
    Preface                                       1
    
1   Initial Configuration                         1
2   Essential Services                           23
3   General Configuration                        41
4   Virtual Private Networking                   67
5   Advanced Configuration                       93
6   Redundancy, Load Balancing, and Failover    125
7   Services and Maintenace                     153

A   Monitoring and Loggin                       187
B   Determining our Hardware Requirements       211

    Index                                       225
    _______________________________________________
    
    Matt Williamson
    Packt
    2011
```

```

1   Initial Configuration

    Introduction
    Applying basic settings in General Setup
    Identifying and assigning interfaces
    Configuring the WAN interface
    Configuring the LAN interface
    Configuring optional interfaces
    Enabling the Secure Shell (SSH)
    Generating authorized RSA keys
    Configuring SSH RSA key authentication
    Accessing the Secure Shell (SSH)

2   Essential Services

    Introduction
    Configuring the DHCP server
    Creating static DHCP mappings
    Configuring the DHCP relay
    Specifying alternate DNS servers
    Configuring the DNS Forwarder
    Configuring a standalone DHCP/DNS server
    Configuring dynamic DNS

3   General Configuration

    Introduction
    Creating an alias
    Creating a NAT port forward rule
    Creating a firewall rule
    Creating a schedule
    Remote desktop access, a complete example

4   Virtual Private Networking

    Introduction
    Creating an IPsec VPN tunnel
    Configuring the L2TP VPN service

5   Advanced Configuration

    Introduction
    Creating a virtual IP
    Configuring a 1:1 NAT rule
    Creating an outbound NAT rule
    Creating a gateway
    Creating a static route
    Configuring traffic-shaping (QoS, Quality of Service)
    Bridging interfaces
    Creating a virtual LAN
    Creating a captive portal

6   Redundancy, Load Balancing, and Failover

    Introduction
    Configuring multiple WAN interfaces
    Configuring multi-WAN load balancing
    Configuring multi-WAN failover
    Configuring a web server load balancer
    Configuring a web server failover
    Configuring CARP firewall failover

7   Services and Maintenance

    Introduction
    Enabling OLSR
    Enabling PPPoE
    Enabling RIP
    Enabling SNMP
    Enabling UPnP and NAT-PMP
    Enabling OpenNTPD
    Enabling Wake On LAN (WOL)
    Enabling external logging (syslog server)
    Using ping
    Using traceroute
    Backing up the configuration file
    Restoring the configuration file
    Configuring automatic configuration file backup
    Updating pfSense firmware

A   Monitoring and Logging

    Introduction
    Customizing the Status Dashboard
    Monitoring current traffic
    Configuring SMTP e-mail notifications
    Viewing system logs
    Configuring an external syslog server
    Viewing RRD graphs
    Viewing DHCP leases
    Managing services
    Monitoring the packet filter with pfInfo
    Monitoring traffic with pfTop
    Monitoring system activity

B   Determining our Hardware Requirements

    Introduction
    Determining our deployment scenario
    Determining our throughput requirements
    Determining our interface requirements
    Choosing a standard or embedded Image
    Choosing a Form Factor

C   Index
```


## [Mastering pfSense](https://www.packtpub.com/networking-and-servers/mastering-pfsense) (Zientara, 2016) 406p

Master the art of managing, securing, and monitoring your network using the powerful pfSense 2.3

https://books.google.com.br/books?isbn=1786463369

```
    Mastering pfSense
    _______________________________________________

    Preface                                     xii

1   pfSense Essentials                            1
2   Advanced pfSense Configuration               37
3   Working with VLANs                           79
4   pfSense as a Firewall                       117
5   Traffic Shaping                             155
6   Virtual Private Networks                    193
7   Redundancy and High Availability            233
8   Routing and Bridging                        269
9   Extending pfSense with Packages             305
10  Troubleshooting pfSense                     343

    Index                                       377
    _______________________________________________
    
    David Zientara
    Packt
    2016
```

```

1   pfSense Essentials

    pfSense project overview
    Possible deployment scenarios
    Hardware requirements and sizing guidelines
    Introduction to VLANs and DNS
    The best practices for installation and configuration
    pfSense configuration
    Upgrading, backing up, and restoring pfSense
    Summary

2   Advanced pfSense Configuration

    DHCP
    DNS
    DDNS
    Captive portal
    NTP
    SNMP
    Summary

3   Working with VLANs

    Basic VLAN concepts
    VLAN configuration at the console
    VLAN configuration in the web GUI
    VLAN configuration at the switch
    Troubleshooting VLANs
    Summary

4   pfSense as a Firewall

    An example network
    Firewall fundamentals
    Firewall best practices
    Creating and editing firewall rules
    Scheduling
    NAT/port forwarding
    Aliases
    Virtual IPs
    Troubleshooting
    Summary

5   Traffic Shaping

    An example network
    Traffic shaping essentials
    Configuring traffic shaping in pfSense
    Traffic shaping examples
    Troubleshooting traffic shaping
    Summary

6   Virtual Private Networks

    VPN fundamentals
    Configuring a VPN tunnel
    Troubleshooting VPN connections
    Summary

7   Redundancy and High Availability

    An example network
    Basic concepts
    Load balancing configuration
    CARP configuration
    An example configuration – load balancing and CARP
    Troubleshooting load balancing and CARP
    Summary

8   Routing and Bridging

    Basic concepts
    Routing with pfSense
    Bridging with pfSense
    Troubleshooting routing and bridging
    Summary

9   Extending pfSense with Packages

    Basic considerations
    Installing packages
    Popular packages
    Other packages
    Summary

10  Troubleshooting pfSense

    Troubleshooting basics
    pfSense troubleshooting tools
    Troubleshooting scenarios
    Summary

A   Index
```
