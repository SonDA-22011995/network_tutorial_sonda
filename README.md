- [Introduction Network](#introduction-network)
  - [Overview and benefit of computer network](#overview-and-benefit-of-computer-network)
    - [What is a Network?](#what-is-a-network)
    - [Some Basic Networking Rules](#some-basic-networking-rules)
    - [Type of Computer Networks (by size)](#type-of-computer-networks-by-size)
      - [Personal Area Network (PAN)](#personal-area-network-pan)
      - [Local Area Network (LAN)](#local-area-network-lan)
      - [Wireless Local Area Network (WLAN)](#wireless-local-area-network-wlan)
      - [Campus Area Network (CAN)](#campus-area-network-can)
      - [Metropolitan Area Network (MAN)](#metropolitan-area-network-man)
      - [Wide Area Network (WAN)](#wide-area-network-wan)
    - [Network Architecture](#network-architecture)
      - [Peer-to-Peer](#peer-to-peer)
      - [Client-Server](#client-server)
      - [Peer-to-Peer vs Client-Server Network](#peer-to-peer-vs-client-server-network)
  - [Introduction to Computer Networking Protocols](#introduction-to-computer-networking-protocols)
    - [What is a Protocol?](#what-is-a-protocol)
    - [Physical and Logical Protocols](#physical-and-logical-protocols)
      - [Physical Protocols](#physical-protocols)
      - [Logical Protocols](#logical-protocols)
- [How Computer Networks Work?](#how-computer-networks-work)
  - [The OSI Model](#the-osi-model)
    - [What is the OSI Model?](#what-is-the-osi-model)
    - [The 7 Layers of the OSI Model](#the-7-layers-of-the-osi-model)
    - [How Data Travels Through the OSI Model](#how-data-travels-through-the-osi-model)
    - [Encapsulation \& De-encapsulation](#encapsulation--de-encapsulation)
      - [What is Encapsulation?](#what-is-encapsulation)
        - [Encapsulation Process](#encapsulation-process)
        - [De-encapsulation process](#de-encapsulation-process)
    - [OSI Layer 7 — Application Layer](#osi-layer-7--application-layer)
      - [Overview](#overview)
      - [What happens at the Application Layer?](#what-happens-at-the-application-layer)
      - [Application vs. Application Layer Protocol](#application-vs-application-layer-protocol)
      - [Common Layer 7 Protocols](#common-layer-7-protocols)
    - [OSI Layer 6 — Presentation Layer](#osi-layer-6--presentation-layer)
      - [Overview](#overview-1)
      - [Main functions of the Presentation Layer](#main-functions-of-the-presentation-layer)
        - [Data formatting / translation](#data-formatting--translation)
        - [Encryption and decryption](#encryption-and-decryption)
        - [Compression](#compression)
    - [OSI Layer 5 — Session Layer](#osi-layer-5--session-layer)
      - [Overview](#overview-2)
      - [Main responsibilities](#main-responsibilities)
      - [Simplex, Half-Duplex and Full-Duplex](#simplex-half-duplex-and-full-duplex)
        - [Simplex](#simplex)
        - [Half-duplex](#half-duplex)
        - [Full-duplex](#full-duplex)
    - [OSI Layer 4 — Transport Layer](#osi-layer-4--transport-layer)
      - [Overview](#overview-3)
      - [Main responsibilities](#main-responsibilities-1)
      - [Data is divided into segments](#data-is-divided-into-segments)
      - [Flow control](#flow-control)
        - [Buffering](#buffering)
        - [Windowing](#windowing)
    - [OSI Layer 3 — Network Layer](#osi-layer-3--network-layer)
      - [Overview](#overview-4)
      - [Main responsibilities](#main-responsibilities-2)
      - [IP – Internet Protocol](#ip--internet-protocol)
      - [Routing](#routing)
      - [Routing Update Packets](#routing-update-packets)
    - [OSI Layer 2 — Data Link Layer](#osi-layer-2--data-link-layer)
      - [Overview](#overview-5)
      - [Two Sublayers of Layer 2](#two-sublayers-of-layer-2)
        - [LLC — Logical Link Control](#llc--logical-link-control)
        - [MAC — Media Access Control](#mac--media-access-control)
    - [OSI Layer 1 — Physical Layer](#osi-layer-1--physical-layer)
      - [What is the Physical Layer?](#what-is-the-physical-layer)
      - [What Does Layer 1 Deal With?](#what-does-layer-1-deal-with)
      - [Physical Network Equipment](#physical-network-equipment)
  - [The TCP/IP Model](#the-tcpip-model)
    - [What is the TCP/IP Model?](#what-is-the-tcpip-model)
    - [The Four Layers of TCP/IP](#the-four-layers-of-tcpip)
    - [TCP/IP vs. OSI Model](#tcpip-vs-osi-model)
    - [Important Protocol Examples](#important-protocol-examples)
  - [Network Access Methodologies](#network-access-methodologies)
    - [CSMA (Carrier Sense Multiple Access)](#csma-carrier-sense-multiple-access)
    - [Token Ring](#token-ring)
    - [CSMA vs. Token Ring](#csma-vs-token-ring)
  - [Duplex Communication](#duplex-communication)
    - [What is the Duplex Communication?](#what-is-the-duplex-communication)
    - [Half-Duplex](#half-duplex-1)
  - [Network Transmission Types](#network-transmission-types)
    - [Unicast](#unicast)
    - [Multicast](#multicast)
    - [Broadcast](#broadcast)
  - [Ethernet](#ethernet)
    - [What is Ethernet?](#what-is-ethernet)
    - [Ethernet and the OSI Model](#ethernet-and-the-osi-model)
    - [Ethernet as a Network Access Method](#ethernet-as-a-network-access-method)
    - [Ethernet Naming Convention](#ethernet-naming-convention)
      - [Baseband](#baseband)
    - [Ethernet Logical Component](#ethernet-logical-component)
- [Network Topology](#network-topology)
  - [What is Network Topology?](#what-is-network-topology)
  - [Physical Topology](#physical-topology)
  - [Logical Topology](#logical-topology)
  - [Physical vs. Logical](#physical-vs-logical)
  - [Wired Network Topologies](#wired-network-topologies)
    - [Ring Topology](#ring-topology)
    - [Star Topology](#star-topology)
    - [Mesh Topology](#mesh-topology)
      - [Full Mesh](#full-mesh)
      - [Partial Mesh](#partial-mesh)
    - [Ring vs. Star vs. Mesh](#ring-vs-star-vs-mesh)
    - [Hybrid Topology](#hybrid-topology)
  - [Wireless Network Topologies](#wireless-network-topologies)
    - [Ad Hoc Topology](#ad-hoc-topology)
    - [Infrastructure](#infrastructure)
    - [Wireless Mesh Topology](#wireless-mesh-topology)
    - [Comparison](#comparison)
- [Network devices are not assigned to a specific OSI layer](#network-devices-are-not-assigned-to-a-specific-osi-layer)
  - [SOHO Device](#soho-device)
    - [What Is a SOHO Device?](#what-is-a-soho-device)
    - [Core Functions](#core-functions)
    - [Additional Features](#additional-features)
  - [Firewall](#firewall)
    - [What Is a Firewall?](#what-is-a-firewall)
    - [Two Primary Categories](#two-primary-categories)
      - [Network-based](#network-based)
      - [Host-based](#host-based)
    - [Why Use Firewalls?](#why-use-firewalls)
    - [Defense in Depth](#defense-in-depth)
    - [Three Firewall Generations](#three-firewall-generations)
      - [First Generation — Packet Filtering](#first-generation--packet-filtering)
      - [Second Generation — Circuit-Level Firewall](#second-generation--circuit-level-firewall)
      - [Third Generation — Application Layer / NGFW](#third-generation--application-layer--ngfw)
  - [VoIP Endpoint](#voip-endpoint)
    - [What Is VoIP?](#what-is-voip)
    - [Traditional Phone vs VoIP](#traditional-phone-vs-voip)
      - [Traditional POTS](#traditional-pots)
      - [VoIP](#voip)
    - [VoIP Phone Is a Network Device](#voip-phone-is-a-network-device)
    - [VoIP Uses Specialized Protocols](#voip-uses-specialized-protocols)
    - [Hardware vs Software VoIP](#hardware-vs-software-voip)
      - [Hardware VoIP phone](#hardware-voip-phone)
      - [Software VoIP / Softphone](#software-voip--softphone)
    - [VoIP vs POTS](#voip-vs-pots)
- [Physical - OSI layer 1 - Network Access - TCP/IP Layer 1](#physical---osi-layer-1---network-access---tcpip-layer-1)
  - [Network Cabling](#network-cabling)
    - [Types of Network Cabling](#types-of-network-cabling)
    - [Coaxial Cable](#coaxial-cable)
      - [What is the Coaxial Cable?](#what-is-the-coaxial-cable)
      - [Coaxial Cable Structure](#coaxial-cable-structure)
      - [Coaxial Cable Connectors](#coaxial-cable-connectors)
        - [BNC Connector (Bayonet Neill–Concelman)](#bnc-connector-bayonet-neillconcelman)
        - [F Connector](#f-connector)
      - [RG-59 vs RG-6](#rg-59-vs-rg-6)
    - [Twisted Pair](#twisted-pair)
      - [What is the Twisted Pair?](#what-is-the-twisted-pair)
      - [Why Are the Wires Twisted?](#why-are-the-wires-twisted)
        - [Crosstalk](#crosstalk)
        - [Electromagnetic Interference (EMI)](#electromagnetic-interference-emi)
      - [UTP vs STP](#utp-vs-stp)
      - [Factors Affecting Cable Speed](#factors-affecting-cable-speed)
        - [Twist rate](#twist-rate)
        - [Conductor Quality](#conductor-quality)
        - [Insulation and separation](#insulation-and-separation)
        - [Shielding](#shielding)
        - [Supported frequency](#supported-frequency)
      - [Twisted-Pair Cable Categories](#twisted-pair-cable-categories)
      - [Cable Category vs Ethernet Standard](#cable-category-vs-ethernet-standard)
      - [Common Categories](#common-categories)
      - [RJ-45 Connectors](#rj-45-connectors)
        - [Four Color-Coded Pairs](#four-color-coded-pairs)
        - [TIA/EIA 568A and 568B](#tiaeia-568a-and-568b)
        - [568A Pinout](#568a-pinout)
        - [568B Pinout](#568b-pinout)
        - [Straight-Through vs Crossover](#straight-through-vs-crossover)
          - [Straight-through](#straight-through)
          - [Crossover](#crossover)
        - [Why Do We Need Crossover Cables?](#why-do-we-need-crossover-cables)
        - [Modern Gigabit Ethernet (GBase-T)](#modern-gigabit-ethernet-gbase-t)
      - [Other Copper Connectors](#other-copper-connectors)
    - [Fiber Optic](#fiber-optic)
      - [What Is Fiber Optic Cabling?](#what-is-fiber-optic-cabling)
      - [Advantages of Fiber Optic](#advantages-of-fiber-optic)
        - [Higher bandwidth](#higher-bandwidth)
        - [Much longer distance](#much-longer-distance)
        - [Fiber Is Not Affected by EMI](#fiber-is-not-affected-by-emi)
      - [Types of Fiber](#types-of-fiber)
        - [Multimode Fiber](#multimode-fiber)
        - [Single-Mode Fiber](#single-mode-fiber)
        - [Multimode vs Single-Mode](#multimode-vs-single-mode)
      - [Fiber Optic Connectors](#fiber-optic-connectors)
        - [LC — Lucent Connector](#lc--lucent-connector)
        - [SC — Subscriber Connector](#sc--subscriber-connector)
        - [ST — Straight Tip](#st--straight-tip)
        - [MTRJ — Mechanical Transfer Registered Jack](#mtrj--mechanical-transfer-registered-jack)
  - [Network Interface Card (NIC)](#network-interface-card-nic)
    - [What is a NIC?](#what-is-a-nic)
    - [NIC and MAC Address](#nic-and-mac-address)
    - [A Device Can Have Multiple NICs](#a-device-can-have-multiple-nics)
  - [Hub](#hub)
    - [What is a Hub?](#what-is-a-hub)
    - [Hub and Star Topology](#hub-and-star-topology)
    - [Hub = Multi-Port Repeater](#hub--multi-port-repeater)
    - [Why Are Hubs Bad?](#why-are-hubs-bad)
      - [Network Collisions](#network-collisions)
      - [Security Problem](#security-problem)
  - [Wireless Range Extender - Wi-Fi Repeater](#wireless-range-extender---wi-fi-repeater)
    - [What is a Wireless Range Extender?](#what-is-a-wireless-range-extender)
    - [How Does It Work](#how-does-it-work)
    - [When Would You Use One?](#when-would-you-use-one)
  - [Modem](#modem)
    - [What Is a Modem?](#what-is-a-modem)
    - [Cable Internet Example](#cable-internet-example)
  - [Media Converter](#media-converter)
    - [What Is a Media Converter?](#what-is-a-media-converter)
    - [Why Do We Need One?](#why-do-we-need-one)
- [Data link - OSI layer 2 - Network Access - TCP/IP Layer 1](#data-link---osi-layer-2---network-access---tcpip-layer-1)
  - [MAC Addresses - Media Access Control (MAC)](#mac-addresses---media-access-control-mac)
    - [What is a MAC Address?](#what-is-a-mac-address)
    - [MAC Address vs. MAC Address Spoofing](#mac-address-vs-mac-address-spoofing)
    - [MAC Address Format](#mac-address-format)
      - [OUI — Organizationally Unique Identifier](#oui--organizationally-unique-identifier)
      - [Individual identifier](#individual-identifier)
  - [Switch](#switch)
    - [What is a Switch?](#what-is-a-switch)
    - [MAC Address Table / CAM Table](#mac-address-table--cam-table)
    - [How a Switch Forwards Data](#how-a-switch-forwards-data)
    - [MAC Address Learning](#mac-address-learning)
    - [Collision Domains](#collision-domains)
      - [What Is a Collision Domain?](#what-is-a-collision-domain)
      - [Hub — One Collision Domain](#hub--one-collision-domain)
      - [Switch in Half-Duplex Mode — Multiple Collision Domains](#switch-in-half-duplex-mode--multiple-collision-domains)
      - [Switch in Full-Duplex Mode — No Collisions](#switch-in-full-duplex-mode--no-collisions)
      - [How Are Collisions Mitigated?](#how-are-collisions-mitigated)
    - [Broadcast Domain](#broadcast-domain)
    - [Security Advantage](#security-advantage)
    - [Why the switch can still have one large broadcast domain?](#why-the-switch-can-still-have-one-large-broadcast-domain)
    - [Switch vs. Hub](#switch-vs-hub)
    - [Unmanaged Switches](#unmanaged-switches)
    - [Managed Switches](#managed-switches)
    - [Access port](#access-port)
    - [Trunk port](#trunk-port)
    - [Virtual LANs (VLANs)](#virtual-lans-vlans)
      - [What Is a VLAN?](#what-is-a-vlan)
      - [Why Do We Use VLANs?](#why-do-we-use-vlans)
      - [How VLANs Work Across Multiple Switches](#how-vlans-work-across-multiple-switches)
    - [Layer 3 Switches](#layer-3-switches)
      - [What Is a Layer 3 Switch?](#what-is-a-layer-3-switch)
      - [Layer 2 Switch vs. Layer 3 Switch](#layer-2-switch-vs-layer-3-switch)
    - [Port Mirroring (SPAN)](#port-mirroring-span)
      - [What Is Port Mirroring?](#what-is-port-mirroring)
      - [How Does Port Mirroring Work?](#how-does-port-mirroring-work)
    - [Power over Ethernet (PoE)](#power-over-ethernet-poe)
      - [What Is Power over Ethernet?](#what-is-power-over-ethernet)
      - [Common PoE Devices](#common-poe-devices)
  - [Wireless Access Point (WAP)](#wireless-access-point-wap)
    - [What is a Wireless Access Point?](#what-is-a-wireless-access-point)
    - [WAP is NOT a Router](#wap-is-not-a-router)
    - [What Devices Connect to a WAP?](#what-devices-connect-to-a-wap)
  - [Network Protocol](#network-protocol)
    - [ARP - Address Resolution Protocol](#arp---address-resolution-protocol)
      - [What is ARP?](#what-is-arp)
      - [Where does ARP work?](#where-does-arp-work)
      - [ARP Request vs ARP Reply](#arp-request-vs-arp-reply)
      - [How ARP works](#how-arp-works)
      - [Viewing the ARP table](#viewing-the-arp-table)
- [Network - OSI layer 3 - Internet - TCP/IP Layer 2](#network---osi-layer-3---internet---tcpip-layer-2)
  - [Network device](#network-device)
    - [Router](#router)
      - [What Does a Router Do?](#what-does-a-router-do)
      - [Router Uses IP Addresses](#router-uses-ip-addresses)
      - [Router vs Switch](#router-vs-switch)
      - [Routers Determine the Best Path](#routers-determine-the-best-path)
      - [A router separates broadcast domains](#a-router-separates-broadcast-domains)
      - [Example](#example)
  - [Network Address Translation (NAT)](#network-address-translation-nat)
    - [What Is NAT?](#what-is-nat)
    - [Benefits of NAT](#benefits-of-nat)
    - [Type of NAT](#type-of-nat)
      - [Static NAT](#static-nat)
      - [Dynamic NAT](#dynamic-nat)
      - [Port Address Translation (PAT)](#port-address-translation-pat)
        - [How PAT works](#how-pat-works)
    - [Which Devices Can Perform NAT?](#which-devices-can-perform-nat)
  - [Demilitarized Zone - DMZ](#demilitarized-zone---dmz)
    - [What Is a DMZ?](#what-is-a-dmz)
    - [Common Services Hosted in a DMZ](#common-services-hosted-in-a-dmz)
    - [Typical DMZ Network Designs](#typical-dmz-network-designs)
      - [Three-Legged Design](#three-legged-design)
      - [Back-to-Back Configuration (Screened Subnet)](#back-to-back-configuration-screened-subnet)
    - [How a DMZ Works](#how-a-dmz-works)
  - [Port Forwarding - Port Redirection](#port-forwarding---port-redirection)
    - [What Is Port Forwarding?](#what-is-port-forwarding)
    - [How Port Forwarding Works](#how-port-forwarding-works)
    - [Port Forwarding vs. Static NAT](#port-forwarding-vs-static-nat)
    - [Common Uses](#common-uses)
    - [Security Considerations](#security-considerations)
  - [Access Control Lists - ACLs](#access-control-lists---acls)
    - [What is an ACL?](#what-is-an-acl)
    - [ACL Rules](#acl-rules)
  - [Network Protocol](#network-protocol-1)
    - [Internet Protocol - IP](#internet-protocol---ip)
      - [Binary math basic](#binary-math-basic)
        - [Why Binary Math Matters](#why-binary-math-matters)
        - [The IPv4 Binary Weight Table](#the-ipv4-binary-weight-table)
        - [Binary to Decimal](#binary-to-decimal)
        - [Decimal to Binary](#decimal-to-binary)
        - [Decimal Fractions to Binary](#decimal-fractions-to-binary)
        - [Binary Fractions to Decimal](#binary-fractions-to-decimal)
      - [What is IP?](#what-is-ip)
      - [Characteristics of IP](#characteristics-of-ip)
      - [Packets Can Take Different Paths](#packets-can-take-different-paths)
      - [What is an IP Addresses?](#what-is-an-ip-addresses)
      - [IP Address vs MAC Address](#ip-address-vs-mac-address)
      - [Static IP Address](#static-ip-address)
      - [Dynamic IP Address](#dynamic-ip-address)
      - [Disadvantages of IPv4](#disadvantages-of-ipv4)
        - [Why Is IPv4 Still Used?](#why-is-ipv4-still-used)
      - [Advantages of IPv6](#advantages-of-ipv6)
      - [IPv4 vs. IPv6](#ipv4-vs-ipv6)
      - [IPv4 Address Structure](#ipv4-address-structure)
        - [What is an Octet?](#what-is-an-octet)
        - [Network Portion and Host Portion](#network-portion-and-host-portion)
      - [IPv4 Address Classes](#ipv4-address-classes)
      - [Usable IPv4 Addresses](#usable-ipv4-addresses)
        - [Power of Two](#power-of-two)
        - [Total IP Addresses vs. Usable IP Addresses](#total-ip-addresses-vs-usable-ip-addresses)
      - [IPv4 Address Components](#ipv4-address-components)
        - [IP Address](#ip-address)
        - [Subnet Mask](#subnet-mask)
          - [Don't Determine the Class From IP Alone](#dont-determine-the-class-from-ip-alone)
          - [CIDR Notation](#cidr-notation)
          - [Calculate the Subnet Mask from CIDR Notation](#calculate-the-subnet-mask-from-cidr-notation)
          - [Common Subnet Mask Values](#common-subnet-mask-values)
        - [Default Gateway](#default-gateway)
        - [Network Address](#network-address)
        - [Broadcast Address](#broadcast-address)
      - [Public IPv4 Addresses](#public-ipv4-addresses)
      - [Private IPv4 Addresses](#private-ipv4-addresses)
      - [Private vs. Public IP Addresses](#private-vs-public-ip-addresses)
        - [Network Structure](#network-structure)
        - [Private IP Addresses](#private-ip-addresses)
        - [Public IP Address](#public-ip-address)
        - [NAT (Network Address Translation)](#nat-network-address-translation)
        - [Router Interfaces](#router-interfaces)
      - [Loopback Address](#loopback-address)
        - [What is the Loopback Address?](#what-is-the-loopback-address)
        - [What Does Loopback Mean?](#what-does-loopback-mean)
        - [Purpose of Loopback](#purpose-of-loopback)
      - [How to Determine Whether Two IP Addresses Are on the Same Network](#how-to-determine-whether-two-ip-addresses-are-on-the-same-network)
        - [Basic rule](#basic-rule)
        - [How to calculate network IDs](#how-to-calculate-network-ids)
        - [Example](#example-1)
      - [Subnetting](#subnetting)
        - [Why Subnetting Is Needed?](#why-subnetting-is-needed)
        - [Benefits of Subnetting](#benefits-of-subnetting)
        - [What Happens When We Subnet?](#what-happens-when-we-subnet)
        - [Calculating the Number of Subnets](#calculating-the-number-of-subnets)
        - [Calculating Hosts per Subnet](#calculating-hosts-per-subnet)
        - [Types of Subnetting](#types-of-subnetting)
        - [FLSM - Subnetting a Class C Network into Two Subnets](#flsm---subnetting-a-class-c-network-into-two-subnets)
        - [FLSM - Subnetting a Class C Network into Four Subnets](#flsm---subnetting-a-class-c-network-into-four-subnets)
      - [IPv6](#ipv6)
        - [Introduction to IPv6](#introduction-to-ipv6)
        - [IPv6 Address Format](#ipv6-address-format)
          - [Number systems used in IPv6](#number-systems-used-in-ipv6)
          - [IPv6 Address Components](#ipv6-address-components)
          - [Simplifying IPv6 Addresses](#simplifying-ipv6-addresses)
          - [IPv6 CIDR Notation](#ipv6-cidr-notation)
          - [IPv6 Data Transmission Types](#ipv6-data-transmission-types)
        - [IPv6 Unicast Address Types](#ipv6-unicast-address-types)
          - [Global Unicast Address](#global-unicast-address)
          - [Unique Local Address (ULA)](#unique-local-address-ula)
          - [Link-Local Address](#link-local-address)
          - [Loopback Address](#loopback-address-1)
          - [Compare types of IPv6 Addresses](#compare-types-of-ipv6-addresses)
    - [ICMP - Internet Control Message Protocol](#icmp---internet-control-message-protocol)
      - [What is ICMP?](#what-is-icmp)
      - [Key Characteristics](#key-characteristics)
      - [ICMP Demo](#icmp-demo)
        - [Traceroute / Tracert](#traceroute--tracert)
        - [Ping](#ping)
- [Transport - OSI layer 4 - Transport - TCP/IP Layer 3](#transport---osi-layer-4---transport---tcpip-layer-3)
  - [Network Protocol](#network-protocol-2)
    - [Understanding Protocols, Ports, and Sockets](#understanding-protocols-ports-and-sockets)
      - [Protocols](#protocols)
      - [Logical Ports](#logical-ports)
        - [Why Do We Need Ports?](#why-do-we-need-ports)
        - [Three Types of Ports](#three-types-of-ports)
      - [Socket](#socket)
      - [Common Network Services and Port Numbers](#common-network-services-and-port-numbers)
      - [`netstat` command](#netstat-command)
        - [What Does 0.0.0.0 Mean?](#what-does-0000-mean)
        - [LISTENING vs. ESTABLISHED](#listening-vs-established)
        - [Common Administration Workflow](#common-administration-workflow)
        - [For more detailed information](#for-more-detailed-information)
    - [Transmission Control Protocol - TCP](#transmission-control-protocol---tcp)
      - [TCP Three-Way Handshake - to establish a connection](#tcp-three-way-handshake---to-establish-a-connection)
      - [Four-way termination - to close a connection](#four-way-termination---to-close-a-connection)
    - [User Datagram Protocol - UDP](#user-datagram-protocol---udp)
      - [Typical UDP Applications](#typical-udp-applications)
    - [TCP vs UDP](#tcp-vs-udp)
- [Application - OSI layer 7 - Application - TCP/IP Layer 4](#application---osi-layer-7---application---tcpip-layer-4)
  - [Network Protocols](#network-protocols)
    - [Management Protocols](#management-protocols)
      - [DNS — Domain Name System](#dns--domain-name-system)
        - [What is DNS?](#what-is-dns)
        - [Fully Qualified Domain Name](#fully-qualified-domain-name)
        - [DNS Hierarchy](#dns-hierarchy)
        - [Top-Level Domain (TLD)](#top-level-domain-tld)
          - [Host Names and Subdomains](#host-names-and-subdomains)
        - [DNS Resolution Process](#dns-resolution-process)
        - [DNS Record Types](#dns-record-types)
          - [Introduction to DNS Records](#introduction-to-dns-records)
          - [Common DNS Record Types](#common-dns-record-types)
      - [DHCP - Dynamic Host Configuration Protocol](#dhcp---dynamic-host-configuration-protocol)
        - [Static IP vs DHCP](#static-ip-vs-dhcp)
        - [Basic DHCP Architecture](#basic-dhcp-architecture)
        - [DORA Process](#dora-process)
        - [DHCP Server Configuration](#dhcp-server-configuration)
          - [Address Scope / Address Pool](#address-scope--address-pool)
          - [Other DHCP Options](#other-dhcp-options)
        - [DHCP Relay Agent](#dhcp-relay-agent)
          - [Why use a relay agent?](#why-use-a-relay-agent)
        - [APIPA - Automatic Private IP Addressing](#apipa---automatic-private-ip-addressing)
      - [NTP — Network Time Protocol](#ntp--network-time-protocol)
      - [SNMP — Simple Network Management Protocol](#snmp--simple-network-management-protocol)
      - [LDAP — Lightweight Directory Access Protocol](#ldap--lightweight-directory-access-protocol)
      - [LDAPS](#ldaps)
      - [SMB — Server Message Block](#smb--server-message-block)
    - [Remote Communication Protocols](#remote-communication-protocols)
      - [Telnet — Terminal Access](#telnet--terminal-access)
      - [SSH — Secure Shell](#ssh--secure-shell)
        - [Telnet vs SSH](#telnet-vs-ssh)
      - [RDP — Remote Desktop Protocol](#rdp--remote-desktop-protocol)
    - [File Transfer Protocols](#file-transfer-protocols)
      - [FTP — File Transfer Protocol](#ftp--file-transfer-protocol)
      - [SFTP — SSH File Transfer Protocol](#sftp--ssh-file-transfer-protocol)
      - [TFTP — Trivial File Transfer Protocol](#tftp--trivial-file-transfer-protocol)
      - [FTP vs SFTP vs TFTP](#ftp-vs-sftp-vs-tftp)
    - [Email Protocols](#email-protocols)
      - [SMTP — Simple Mail Transfer Protocol](#smtp--simple-mail-transfer-protocol)
      - [POP3 — Post Office Protocol Version 3](#pop3--post-office-protocol-version-3)
      - [IMAP — Internet Message Access Protocol](#imap--internet-message-access-protocol)
      - [SMTP vs POP3 vs IMAP](#smtp-vs-pop3-vs-imap)
    - [Web Browser Application Protocols](#web-browser-application-protocols)
      - [HTTP - Hypertext Transfer Protocol](#http---hypertext-transfer-protocol)
      - [HTTPS - HTTP Secure](#https---http-secure)
        - [Why HTTPS Is Important](#why-https-is-important)
        - [Internet vs. World Wide Web](#internet-vs-world-wide-web)

# Introduction Network

## Overview and benefit of computer network

### What is a Network?

- It is composed of two main aspects:
  - Physical Connection (wires, cables, wireless media)
  - Logical Connection (data transporting across the physical media)

### Some Basic Networking Rules

- The computers in a network must use the same procedures for sending and receiving data. We call these communication protocols.
- Data must be delivered uncorrupted. If it is corrupted, it’s useless. (There are Exceptions)
- Computers in a network must be capable of determining the origin and destination of a piece of information, i.e., its IP and Mac Address.

### Type of Computer Networks (by size)

- Personal Area Network (PAN)
- Local Area Network (LAN)
- Wireless Local Area Network (WLAN)
- Campus Area Network (CAN)
- Metropolitan Area Network (MAN)
- Wide Area Network (WAN)

#### Personal Area Network (PAN)

- Ultra-small networks used for personal use to share
  data from one device to another.
- Examples: Smart Phone to Laptop, Smart Watch to Smart Phone, Heart Rate Monitor to Smart Phone

#### Local Area Network (LAN)

- A computer network within a small geographical area, such as a single room, building or group of buildings.
- Examples: Home Network, Small Business or Office Network

#### Wireless Local Area Network (WLAN)

- A LAN that’s dependent on wireless connectivity or one that extends a traditional wired LAN to a wireless LAN.
- Most home networks are WLANs.

#### Campus Area Network (CAN)

- A computer network of multiple interconnected LANs in a limited geographical area, such as a corporate business park, government agency, or university campus.
- Typically owned or used by a single entity.

#### Metropolitan Area Network (MAN)

- A computer network that interconnects users with computer resources in a city.
- Larger than a campus area network, but smaller than a wide area network.

#### Wide Area Network (WAN)

- A computer network that extends over a large geographical distance, typically multiple cities, states, or countries.
- WANs connect geographically distant LANs.
- Examples: The Internet, Corporate Offices in Different States

### Network Architecture

#### Peer-to-Peer

- All computers on the network are peers
  - No dedicated servers
  - There’s no centralized control over shared resources
- Any device can share its resources as it pleases
- All computers can act as either a client or a server
- Easy to set-up, and common in homes and small businesse

#### Client-Server

- The network is composed of client and servers
  - Servers provide resources
  - Clients receive resources
- Servers provide centralized control over network resources (files, printers, etc.)
- Centralizes user accounts, security, and access controls to simplify network administration
- More difficult to setup and requires an IT administrator

#### Peer-to-Peer vs Client-Server Network

| Criteria                 | Peer-to-Peer (P2P)                           | Client-Server                                           |
| ------------------------ | -------------------------------------------- | ------------------------------------------------------- |
| Computer roles           | All computers are peers                      | Computers are divided into clients and servers          |
| Dedicated servers        | No dedicated servers                         | Dedicated servers                                       |
| Control over resources   | No centralized control                       | Centralized control                                     |
| Resource sharing         | Each device shares resources as it chooses   | Servers provide resources                               |
| Device function          | Any computer can act as a client or a server | Clients request, servers provide                        |
| Resource management      | Decentralized                                | Centralized                                             |
| User accounts & security | No centralized management                    | Centralized user accounts, security, and access control |
| Setup complexity         | Easy to set up                               | More difficult to set up                                |
| IT administration        | Not required                                 | Requires an IT administrator                            |
| Typical usage            | Homes and small businesses                   | Medium and large organizations                          |

## Introduction to Computer Networking Protocols

### What is a Protocol?

- A protocol is essentially a set of rules that defines how systems communicate and exchange data.
- In computer networking, network protocols are rules that govern how devices on a network exchange data and enable effective communication.
- Examples:
  - Email protocols => sending and receiving emails
    - POP3, SMTP, IMAP
  - File transfer protocols => sending and receiving files
    - FTP
  - Web protocols => communicating with web servers 
    - HTTP, HTTPS

### Physical and Logical Protocols

- A computer network has two main aspects:
  - Physical aspect
  - Logical aspect
- Therefore, networking protocols can also be divided into

#### Physical Protocols

- Physical protocols deal with the physical characteristics of network communication, such as:
  - Network transmission media
  - Cables and wiring
  - Connectors
  - RJ-45 ports
  - Electrical signals
  - Voltage levels on the wire

![Physical Protocols](./static/tutorial_0012.png)

#### Logical Protocols

- Logical protocols deal with software and communication rules.
- They determine:
  - How data is sent
  - When data is sent
  - How data is received
  - How computers communicate using the underlying physical network

# How Computer Networks Work?

## The OSI Model

### What is the OSI Model?

- OSI stands for Open Systems Interconnection.
- The OSI model is a conceptual reference model that explains how data flows through a network from a source device to a destination device.
- Important:
  - OSI is not actually implemented as the networking architecture used in the real world.
  - TCP/IP is the practical networking model/protocol suite used in real networks.
  - However, OSI is widely used for learning, troubleshooting, and discussing networking concepts.

### The 7 Layers of the OSI Model

**Memorize:** _Please Do Not Throw Sausage Pizza Away_

| Layer No. | Mnemonic    | Layer Name   | Data Unit | Common Protocols                              | Typical Devices                   |
| --------- | ----------- | ------------ | --------- | --------------------------------------------- | --------------------------------- |
| 7         |  A – Away | Application  | Data      | HTTP, HTTPS, FTP, SMTP, POP3, IMAP, DNS, SNMP | PC, Server, Proxy Server          |
| 6         | P – Pizza   | Presentation | Data      | SSL/TLS, JPEG, MPEG, ASCII                    | PC, Server                        |
| 5         | S – Sausage | Session      | Data      | NetBIOS Session, RPC, PPTP                    | PC, Server                        |
| 4         | T – Throw   | Transport    | Segment   | TCP, UDP                                      | Firewall, Load Balancer (Layer 4) |
| 3         | N – Not     | Network      | Packet    | IP, ICMP, IPsec, RIP, OSPF, BGP               | Router, Layer 3 Switch            |
| 2         | D – Do      | Data Link    | Frame     | Ethernet (802.3), ARP, PPP, VLAN (802.1Q)     | Switch, Bridge, NIC               |
| 1         | P – Please    | Physical     | Bit       | Physical standards (UTP, Fiber)               | Hub, Repeater, Cable              |

### How Data Travels Through the OSI Model

- Sender: The data starts at the top

```
  Application
     ↓
  Presentation
     ↓
  Session
     ↓
  Transport
     ↓
  Network
     ↓
  Data Link
     ↓
  Physical
     ↓
   Network
```

- Receiver: Receives the transmission and processes it in the opposite direction

```
   Network
      ↓
  Physical
      ↓
  Data Link
      ↓
  Network
      ↓
  Transport
      ↓
  Session
      ↓
  Presentation
      ↓
  Application
```

![OSI Model comunication](./static/tutorial_0001.png)

### Encapsulation & De-encapsulation

#### What is Encapsulation?

- Encapsulation is the process of adding headers/trailers to data as it moves DOWN the OSI Model from Layer 7 → Layer 1.
- De-encapsulation is the reverse process: removing headers/trailers as data moves UP the OSI Model from Layer 1 → Layer 7.

##### Encapsulation Process

- Layer 7–5: The application generates the original data 
  - `[ DATA ]`
  - it is called a **Data**
- Layer 4 — Transport: The Transport Layer adds a TCP or UDP header 
  - `[ TCP/UDP Header ][ DATA ]`
  - Now we call it a **Segment**
  - The header can contain information such as
    - Source port
    - Destination port
    - Sequence number, etc. for TCP
- Layer 3 — Network: The Network Layer adds an IP header 
  - `[ IP Header ][ TCP/UDP Header ][ DATA ]`
  - Now it is called a: **Packet**
  - The IP header contains, among other things: Source IP, Destination IP
- Layer 2 — Data Link: The Data Link Layer adds Frame header, Frame trailer
  - `[ Frame Header ][ IP Header ][ TCP Header ][ DATA ][ Frame Trailer ]`
  - Now it is called a Frame
- Layer 1 — Physical: Finally, the frame is converted into bits/signals.
  - Those bits are transmitted through the physical medium.

##### De-encapsulation process

- The receiving computer performs the opposite process
- Layer 1: Receives the electrical/optical/radio signals and converts them into bits.
- Layer 2: Receives the frame and removes the Layer 2 header/trailer.
- Layer 3: Processes the IP packet and removes the IP header.
- Layer 4: Processes the TCP/UDP segment and removes the TCP/UDP header.
- Layer 5–7: The remaining data is passed to the application.



### OSI Layer 7 — Application Layer

#### Overview

- Layer 7 – Application Layer is a Host Layer.
- Host layers (Layers 5–7) operate within the end devices/computers.
- It is the layer closest to the end user.

#### What happens at the Application Layer?

- The Application Layer is where users interact with network services through applications.
- Examples:
  - Open Outlook → send/receive email.
  - Open Google Chrome → access websites.
  - Open PuTTY → remotely connect to another computer
- However, an important distinction:
  - Applications themselves do NOT reside in the Application Layer of the OSI Model.
  - Instead, applications interface with Application Layer protocols

#### Application vs. Application Layer Protocol

- Think of it this way: **User → Application → Application Layer Protocol → Network**
  - When you type: `https://google.com`
    - You interact with Chrome, but Chrome uses HTTP/HTTPS to communicate with the web server.

| Application   | Application Layer Protocols |
| ------------- | --------------------------- |
| Outlook       | IMAP, POP3, SMTP            |
| Chrome / Edge | HTTP, HTTPS                 |
| PuTTY         | SSH, Telnet                 |

#### Common Layer 7 Protocols

| Protocol   | Purpose                                   |
| ---------- | ----------------------------------------- |
| **HTTP**   | Web communication                         |
| **HTTPS**  | Secure web communication                  |
| **SMTP**   | Sending email                             |
| **POP3**   | Receiving/downloading email               |
| **IMAP**   | Accessing/managing email on a mail server |
| **SSH**    | Secure remote access                      |
| **Telnet** | Remote access, without encryption         |

### OSI Layer 6 — Presentation Layer

#### Overview

- It is a Host Layer, operating within end devices.
- Its main responsibility is to ensure that data is represented in a format that the application can understand.

#### Main functions of the Presentation Layer

- There are 3 major functions:

| Function                          | Purpose                                                 |
| --------------------------------- | ------------------------------------------------------- |
| **Data formatting / translation** | Converts data between different representations         |
| **Encryption / decryption**       | Protects data during transmission                       |
| **Compression / decompression**   | Reduces the amount of data that needs to be transmitted |

```
# Sending

Application Data
      ↓
Data Formatting
      ↓
Translation
      ↓
Compression
      ↓
Encryption
      ↓
Network
```

```
# Receiving

Network
      ↓
Decryption
      ↓
Decompression
      ↓
Translation
      ↓
Data Formatting
      ↓
Application Data
```

##### Data formatting / translation

- Computers don't necessarily transmit data in the same representation that humans see.
- The Presentation Layer can perform character-code conversion and data representation so that data can be correctly interpreted by the receiving application.

##### Encryption and decryption

- The Presentation Layer can be associated with transforming data into an encrypted representation before transmission and decrypting it when received
  - For example, **TLS** is commonly associated with secure network communication

##### Compression

- The Presentation Layer can also handle data compression
  - The purpose is to reduce the amount of data that needs to be transmitted

### OSI Layer 5 — Session Layer

#### Overview

- It is one of the Host Layers (Layers 5–7).
- Its primary responsibility is to establish, manage, and terminate communication sessions between applications/devices.

#### Main responsibilities


| Function                  | Description                                              |
| ------------------------- | -------------------------------------------------------- |
| **Session establishment** | Starts a communication session                           |
| **Session management**    | Maintains and coordinates the session                    |
| **Session termination**   | Ends the session                                         |
| **Session separation**    | Keeps different application sessions logically separate  |
| **Session recovery**      | Can help resume/restart communication after interruption |

#### Simplex, Half-Duplex and Full-Duplex

| Mode            | Communication                   | Example            |
| --------------- | ------------------------------- | ------------------ |
| **Simplex**     | One-way only                    | Radio/TV broadcast |
| **Half-duplex** | Two-way, but one side at a time | Walkie-talkie      |
| **Full-duplex** | Two-way simultaneously          | Telephone call     |

##### Simplex

- Only A sends data.

```
Device A ─────────→ Device B
```

##### Half-duplex

- Both devices can communicate, but not at the same time.

```
Device A ─────────→ Device B
Device A ←───────── Device B
```

##### Full-duplex

- Both sides can send and receive at the same time

```
Device A <─────────> Device B
```

### OSI Layer 4 — Transport Layer

#### Overview

- This is the bottom Host Layer.
- Unlike Layers 5–7, Layer 4 is where the data is divided into smaller units called segments when using TCP.
- The two major Transport Layer protocols are: TCP(Transmission Control Protocol), UDP(User Datagram Protocol)

#### Main responsibilities

- The Transport Layer is responsible for mechanisms that help ensure the data reaches the destination appropriately.
  - Breaking large data into smaller segments
  - Delivering segments to the destination
  - Ensuring proper sequence/order
  - Providing reliable delivery when required
  - Controlling the flow of data
  - Reassembling data at the destination

#### Data is divided into segments

- Large data is not normally sent as one giant block.
- For example, if you download a 1 GB file

```
1 GB File
    ↓
┌────────┬────────┬────────┬────────┬───────┐
│Segment │Segment │Segment │Segment │  ...  │
└────────┴────────┴────────┴────────┴───────┘
    ↓
Network
    ↓
Destination
    ↓
Reassembled in the correct order
```

#### Flow control

- Important distinction
  - Buffering: Temporarily stores data in memory.
  - Windowing: Controls how much data can be sent/accepted during communication.

##### Buffering

- Buffering is a form of data flow control.
- The server can produce data faster than the client can consume it.
- Instead of immediately discarding the excess data, the system can temporarily store it in a memory buffer

```
        Server
          │
          │  TCP Segments
          ↓
      Network
          │
          ↓
       Client
          │
          ↓
   ┌──────────────────┐
   │  Memory Buffer   │
   ├──────────────────┤
   │ Segment 1        │
   │ Segment 2        │
   │ Segment 3        │
   │ Segment 4        │
   └──────────────────┘
          │
          ↓
     Application
```

##### Windowing

- Windowing is another mechanism associated with flow control, particularly TCP
- The sender and receiver determine how much data can be sent before additional acknowledgment/flow-control feedback is needed

### OSI Layer 3 — Network Layer

#### Overview

- It is the highest layer of the Media Layers
- Layer 3 is also called the Routing Layer.
- Layer 3 Devices
  - Router
  - Multilayer Switch - A multilayer switch can operate at both:
    - Layer 2 – Data Link
    - Layer 3 – Network

#### Main responsibilities

- Path determination / Routing
  - Determines how packets travel from one network to another.
  - Routers operate primarily at this layer.
- Logical addressing 
  - Uses IP addresses to identify source and destination systems.
  - Main protocols: IPv4, IPv6

#### IP – Internet Protocol

- It is the primary network-layer protocol used to route data between networks, particularly across the Internet and WANs
- IP provides the logical addressing needed to determine:
  - Where did the packet come from? -> Where should it go?

| Protocol | Address             |
| -------- | ------------------- |
| IPv4     | e.g. `192.168.1.10` |
| IPv6     | e.g. `2001:db8::10` |

#### Routing

- There are two major approaches:
  - **Static routing**: Routes are manually configured by an administrator.
  - **Dynamic routing**: 
    - Routers use routing protocols to exchange routing information automatically.
    - Examples of dynamic routing protocols: RIP,OSPF,EIGRP

#### Routing Update Packets

- Used by dynamic routing protocols to exchange routing information between routers
- Routers need to exchange information about the networks they know.
  - For example: 
    - A routing protocol can communicate information such as "I know how to reach network X."
    - This allows routers to maintain and update their routing information.

### OSI Layer 2 — Data Link Layer

#### Overview

- Layer 2 is often called the Switching Layer.
- Its main responsibility is local delivery of frames within the same network (LAN).

#### Two Sublayers of Layer 2

- The Data Link Layer consists of two sublayers

```
                 OSI Layer 2
               DATA LINK LAYER
                      │
          ┌───────────┴───────────┐
          │                       │
        LLC                      MAC
          │                       │
   Error control             MAC address
   Flow control              Media access
                              Ethernet
                              CSMA/CD
                              CSMA/CA
```

##### LLC — Logical Link Control

- Main functions:
  - Error control - Helps detect/correct problems with data frames.
  - Flow control - Controls how much data is transmitted so that the receiving device isn't overwhelmed
  - Managing communication between devices at the local link level

##### MAC — Media Access Control

- Physical addressing - Uses MAC addresses `00:1A:2B:3C:4D:5E`
- Media access - Determines how devices access the shared network medium
  - Logical Topology
    - Ethernet — dominant today
    - Token Ring — obsolete/legacy technology
  - CSMA (Carrier Sense Multiple Access)
    - The basic idea is: Before transmitting, a device checks whether the medium is available.
  - CSMA/CD (Carrier Sense Multiple Access / Collision Detection)
    - Historically used with shared, half-duplex Etherne
  - CSMA/CA (Carrier Sense Multiple Access / Collision Avoidance)
    - Used with Wi-Fi.
    - Because wireless devices cannot reliably detect collisions while transmitting, Wi-Fi focuses on avoiding collisions.

### OSI Layer 1 — Physical Layer

#### What is the Physical Layer?

- The Physical Layer is Layer 1, the lowest layer of the OSI model.
- Its main purpose is to define how raw bits are physically transmitted between network devices.
- At this layer: **Frames (Data Link Layer) are converted into bits (0s and 1s) for physical transmission.**

#### What Does Layer 1 Deal With?

- The Physical Layer deals with the physical and electrical characteristics of network communication.
- It includes:
  - Network hardware
  - Physical media
  - Physical topology
  - Signals used to transmit bits

- Three main types of physical signals

| Medium           | Signal             |
| ---------------- | ------------------ |
| **Copper cable** | Electrical signals |
| **Fiber optic**  | Light photons      |
| **Wireless**     | Radio waves        |

#### Physical Network Equipment

- Layer 1 includes simple physical equipment that generally doesn't make intelligent networking decisions.
- Examples:
  - Cables
  - Network jacks
  - Patch panels
  - Hubs
  - Media converters
  - Modems

## The TCP/IP Model

### What is the TCP/IP Model?

- TCP/IP stands for Transmission Control Protocol / Internet Protocol.
- TCP/IP is the most widely used networking protocol suite today and forms the foundation of the Internet.
- Unlike the OSI model:
  - OSI model is a conceptual/teaching model with 7 layers and was never implemented as a networking protocol.
  - TCP/IP was implemented and is the most widely used networking protocol suite, used on
    - The Internet (WAN)
    - Private/local networks (LANs)

### The Four Layers of TCP/IP

| Layer No. | TCP/IP Layer Name | OSI Mapping   | Data Unit   | Common Protocols                              | Typical Devices                   |
| --------- | ----------------- | ------------- | ----------- | --------------------------------------------- | --------------------------------- |
| 4         | Application       | OSI Layer 7–5 | Data        | HTTP, HTTPS, FTP, SMTP, POP3, IMAP, DNS, SNMP | PC, Server, Proxy Server          |
| 3         | Transport         | OSI Layer 4   | Segment     | TCP, UDP                                      | Firewall, Load Balancer (Layer 4) |
| 2         | Internet          | OSI Layer 3   | Packet      | IP, ICMP, IPsec, ARP                          | Router, Layer 3 Switch            |
| 1         | Network Access    | OSI Layer 2–1 | Frame / Bit | Ethernet, Wi-Fi (802.11), PPP                 | Switch, NIC, Hub, Cable           |

### TCP/IP vs. OSI Model

- TCP/IP didn't completely change how networking functions work.
- Instead, it simplified the OSI model by combining related functions into fewer layers

| TCP/IP                | OSI                                  |
| --------------------- | ------------------------------------ |
| **Application**       | Application + Presentation + Session |
| **Transport**         | Transport                            |
| **Internet**          | Network                              |
| **Network Interface** | Data Link + Physical                 |

```
TCP/IP Model                  OSI Model

Application        ───────>   Application
                              Presentation
                              Session

Transport          ───────>   Transport

Internet           ───────>   Network

Network Interface  ───────>   Data Link
                              Physical
```

### Important Protocol Examples

| Layer                       | Protocol / Technology | Purpose                                                              |
| --------------------------- | --------------------- | -------------------------------------------------------------------- |
| **Application Layer**       | **FTP (File Transfer Protocol)**               | File transfer                                                        |
| Application Layer | **TFTP (Trivial File Transfer Protocol)** | Provides simple file transfers, commonly used for boot files and network device configuration. |
| Application Layer | **DNS (Domain Name System)** | Resolves domain names into IP addresses and vice versa. |
| Application Layer | **HTTP (Hypertext Transfer Protocol)** | Transfers web pages and other web resources between clients and servers. |
| Application Layer | **HTTPS (HTTP Secure)** | Provides secure HTTP communication using TLS encryption. |
| Application Layer | **SSH (Secure Shell)** | Provides secure remote login and command-line access to network devices and servers. |
| **Application Layer**       | **SMTP (Simple Mail Transfer Protocol)**              | Sending email                                                        |
| Application Layer | **SNMP (Simple Network Management Protocol)** | Monitors and manages network devices such as routers, switches, and servers. |
| Application Layer | **IMAP4 (Internet Message Access Protocol version 4)** | Accesses and manages emails while keeping them stored on the mail server. |
| Application Layer | **NTP (Network Time Protocol)** | Synchronizes the clocks of computers and network devices over a network. |
| Application Layer | **Telnet** | Provides remote command-line access, but sends data without encryption. |
| Application Layer | **POP3 (Post Office Protocol version 3)** | Retrieves emails from a mail server, typically downloading them to the client. |
| **Transport Layer**         | **TCP**               | Reliable transport of data, Three-way handshake                                           |
| **Transport Layer**         | **UDP**               | Fast, connectionless transport of data, No guarantee of delivery                               |
| **Transport Layer**         | **Port**               | Identify specific applications/services on a device, Common protocols use well-known port numbers|
| **Internet Layer**          | **IP (IPv4 and IPv6)**                | Logical addressing and routing                                       |
| Transport Layer | **TLS/SSL (Transport Layer Security / Secure Sockets Layer)** | Encrypts data and provides authentication and integrity for network communications. |
| **Internet Layer**          | **ARP (Address Resolution Protocol)**               | Resolving IP addresses to MAC addresses in IPv4 networks             |
| **Internet Layer**          | **ICMP (Internet Control Message Protocol)**               | Used for network diagnostics and error reporting            |
| **Network Interface Layer** | **Ethernet**          | Accessing the network and transmitting data over Ethernet networks   |
| **Network Interface Layer** | **Token Ring**        | Accessing the network and transmitting data over Token Ring networks |

## Network Access Methodologies

### CSMA (Carrier Sense Multiple Access)

- CSMA is the most common network access methodology in modern TCP/IP networks.
  - Carrier Sense: A device checks whether the network is currently being used before transmitting data.
  - Multiple Access: Multiple devices can access the same network medium.
  - Because multiple devices may transmit, collisions can occur.

- CSMA has two main variants:

| Method                            | Network           | Purpose                                                |
| --------------------------------- | ----------------- | ------------------------------------------------------ |
| **CSMA/CD** (Collision Detection) | Wired Ethernet    | Detects collisions and retransmits data when necessary |
| **CSMA/CA** (Collision Avoidance) | Wireless networks | Attempts to avoid collisions before transmitting       |

### Token Ring

- Token Ring is an older/antiquated network access methodology that is rarely used in modern networks.
  - A logical token circulates from one device to another.
  - Only the device currently holding the token can transmit data.
  - After transmitting, the device passes the token to the next device.
  - If a device has no data to send, it passes the token immediately.
  - Because only one device can transmit at a time, collisions are prevented.
- Key idea: Token Ring uses controlled access through a token, allowing only one device to transmit at a time.

### CSMA vs. Token Ring

| Feature      | CSMA                                   | Token Ring           |
| ------------ | -------------------------------------- | -------------------- |
| Access       | Multiple devices can access the medium | One device at a time |
| Collision    | Possible                               | Prevented            |
| Mechanism    | Sense the medium before transmission   | Wait for the token   |
| Wired        | CSMA/CD                                | Token Ring           |
| Wireless     | CSMA/CA                                | —                    |
| Modern usage | Very common                            | Mostly obsolete      |
| Scalability  | Generally scales better                | More limited         |


## Duplex Communication

### What is the Duplex Communication?

- Duplex describes how devices send and receive data over a communication channel.
- There are two modes:
  - Half-duplex
  - Full-duplex

### Half-Duplex

- With half-duplex, a device can send or receive data, but not both at the same time.

```
PC 1 ─────────→ PC 2
     Sending

PC 1 ←───────── PC 2
     Receiving
```

## Network Transmission Types

- Network transmission type describes the general way data is sent from one system to other systems on a network.

- There are three basic types:

| Type          | Communication   | Description                                            |
| ------------- | --------------- | ------------------------------------------------------ |
| **Unicast**   | **One-to-One**  | One sender sends data to one specific receiver         |
| **Multicast** | **One-to-Many** | One sender sends data to a specific group of receivers |
| **Broadcast** | **One-to-All**  | One sender sends data to all devices on the network    |


### Unicast

- One-to-One
- Only one specific device receives the data.

![OSI Model comunication](./static/tutorial_0003.png)

### Multicast

- One-to-Many
- The sender sends data to a specific group of devices, called a multicast group.

![OSI Model comunication](./static/tutorial_0004.png)

### Broadcast

- One-to-All
- The sender sends data to all devices on the relevant network.

![OSI Model comunication](./static/tutorial_0005.png)

## Ethernet

### What is Ethernet?

- Ethernet is a family of networking standards used primarily for communication within **Local Area Networks (LANs)**.
- It covers both:
  - Physical aspects of networking 
  - Logical/data communication aspects

| Aspect       | What it covers                                    |
| ------------ | ------------------------------------------------- |
| **Physical** | Cables, connectors, signals, transmission speed   |
| **Logical**  | How devices access/transmit data over the network |

- So Ethernet is not just about cables.

### Ethernet and the OSI Model

- Ethernet is associated with both:
  - Layer 1 — Physical: Ethernet defines physical aspects such as
    - Network cables
    - Connectors
    - Electrical signals
    - Physical transmission
  - Layer 2 — Data Link: Ethernet also defines aspects of how data moves across the local network, including:
    - Frames
    - MAC addresses
    - Access to the shared network medium
- Therefore: ethernet operates across OSI Layer 1 and Layer 2.

### Ethernet as a Network Access Method

- Ethernet provides rules for how devices access and communicate over the network medium.
- The lecture introduces CSMA: **Carrier Sense Multiple Access**
  - The idea is that devices can sense the communication medium before transmitting

### Ethernet Naming Convention

- A common Ethernet naming format is: `N + Base + X`
- Example: **10Base-T**

```
10Base-T
 │  │  │
 │  │  └── Twisted-pair copper
 │  │
 │  └────── Baseband signaling
 └───────── Signaling rate: 10 Mbps
```

#### Baseband

- Baseband means the Ethernet transmission uses the medium for a baseband digital signal rather than broadband-style multiple frequency channels
  - **Base = Baseband = digital network signaling**

### Ethernet Logical Component

- **CSMA/CD** → associated historically with shared/half-duplex wired Ethernet
- **CSMA/CA** → used by wireless LANs
  - Modern switched full-duplex Ethernet generally doesn't need CSMA/CD for collision handling, because collisions don't occur on a dedicated full-duplex switch link

```
# These are logical access methods, rather than cable specifications.

Ethernet
├── Physical
│   ├── Cable
│   ├── Connector
│   ├── Signal
│   └── Speed
│
└── Logical
    ├── CSMA/CD
    └── CSMA/CA
```

# Network Topology

## What is Network Topology?

- Network Topology can be thought of as a blueprint of a network.
- A Network has two aspects:
  - Physical
  - Logical
Therefore, we have: **Physical topology** and **Logical topology**

## Physical Topology

- Physical topology describes where devices are physically located and how they are physically connected.
- It includes:
  - Servers
  - Switches
  - Routers
  - Firewalls
  - Printers
  - Network cables
  - Physical connections

- Example

```
          Router
             │
          Switch
        ┌────┼────┐
       PC   Server Printer
```

## Logical Topology

- Logical topology describes how data flows through the network.
- It isn't primarily concerned with where the devices physically sit. Instead, it focuses on the rules and protocols that determine how data is transmitted.
- Examples include:
  - Ethernet
  - CSMA/CD
  - IEEE 802.11
  - CSMA/CA

## Physical vs. Logical

|                | **Physical Topology**                     | **Logical Topology**        |
| -------------- | ----------------------------------------- | --------------------------- |
| Focus          | Physical connections                      | Data flow                   |
| Describes      | Where/how devices are connected           | How devices communicate     |
| Examples       | Cables, switches, routers                 | Ethernet, 802.11, CSMA/CD   |
| Think of it as | **Physical blueprint**                    | **Communication blueprint** |
| Main question  | "How is everything physically connected?" | "How does data flow?"       |


## Wired Network Topologies

### Ring Topology

- In a ring topology, every device (node) is connected to two other devices, forming a closed loop.

```
       PC1
      /   \
    PC2   PC6
    |       |
    PC3   PC5
      \   /
       PC4
```

- How does data travel?
  - Data moves from node to node around the ring.
  - Each device can regenerate/repeat the signal before passing it to the next device.
- Problem with traditional ring
  - If one device or cable fails -> The ring can be broken, preventing communication.
- Modern ring topology
  - Modern implementations can use two counter-rotating rings
  - If one path fails, traffic can use the other path.
  - This provides: Redundancy- High availability- Rapid recovery from failures
  - Examples mentioned: SONET- SDH- Metro Ethernet

![OSI Model comunication](./static/tutorial_0006.png)

### Star Topology

- In a star topology, all devices connect to a central device, typically a switch.

```
           PC
            │
            │
PC ─────── Switch ───── Server
            │
            │
         Printer
```

- How does it work?
  - Devices send their data to the central switch.
  - The switch determines the destination and forwards the data to the appropriate device.
- Advantages
  - Simple to manage
  - Easy to expand
  - Easy to troubleshoot
  - Standard topology for modern LANs
- Disadvantage
  - The central switch can be a single point of failure

![OSI Model comunication](./static/tutorial_0007.png)

### Mesh Topology

- In a mesh topology, devices have multiple connections, creating redundant paths.
- There are two main types:
  - Full mesh
  - Partial mesh

![OSI Model comunication](./static/tutorial_0008.png)

#### Full Mesh

- In a full mesh, every device connects directly to every other device.
- The exact number of connections grows very quickly as more devices are added
- For n devices, the number of links is: `n(n − 1) / 2`
- For example:
  - 3 devices -> 3 links
  - 10 devices -> 45 links
  - 20 devices -> 190 links
  - 50 devices -> 1,225 links

```
      S1
     / | \
    /  |  \
  S2───┼───S3
   \   |   /
    \  |  /
      D1
```

#### Partial Mesh

- In a partial mesh, devices connect to some, but not all, other devices.
- Some devices have multiple paths, while others may have only one path.
- Main advantage
  - It provides a balance between: **Redundancy <-> Cost**
  - Therefore, partial mesh is much more practical for real-world networks.

### Ring vs. Star vs. Mesh

| Topology         | Structure                             | Main Advantage               | Main Disadvantage       | Common Use              |
| ---------------- | ------------------------------------- | ---------------------------- | ----------------------- | ----------------------- |
| **Ring**         | Devices form a loop                   | Redundancy with dual rings   | More complex            | Carrier/WAN networks    |
| **Star**         | Devices connect to central switch     | Simple & easy to manage      | Central device can fail | Modern LANs             |
| **Full Mesh**    | Every device connects to every device | Maximum redundancy           | Very expensive          | Critical infrastructure |
| **Partial Mesh** | Devices connect to selected devices   | Good redundancy/cost balance | More complex than star  | Core/WAN networks       |

### Hybrid Topology

- Real-world networks usually don't use only one topology.
- They commonly combine different topologies
- For example
  - The core might use a partial mesh for redundancy, while devices at the edge connect using a star topology.
  - This combination is called a Hybrid topology

```
              Core
          ┌─────┴─────┐
       Switch        Switch
       /   \          /   \
     PC    PC       PC    Server
```

## Wireless Network Topologies

### Ad Hoc Topology

- An **Ad Hoc network** is a **peer-to-peer (P2P)** wireless network.
- There is no central wireless **access point (AP)**.
- Devices communicate directly with one another.
- Characteristics
  - No central AP
  - Device-to-device communication
  - Simple to set up
  - Suitable for small/personal networks
  - Can be considered a type of peer-to-peer wireless communication

![OSI Model comunication](./static/tutorial_0009.png)

### Infrastructure

- This is the most common traditional wireless network design.
- Devices connect to a Wireless Access Point (WAP/AP)
- A typical infrastructure WLAN is not completely wireless
  - The wireless devices communicate with the AP wirelessly, but the AP normally has a wired connection to the rest of the network.
- Characteristics
  - Uses a central Wireless Access Point
  - Common in homes and businesses
  - Forms a WLAN (Wireless LAN)
  - Easy to manage
  - **Infrastructure = Devices → AP → Wired Network**

![OSI Model comunication](./static/tutorial_0010.png)

### Wireless Mesh Topology

- A wireless mesh network uses multiple wireless nodes/APs that communicate with one another.

```
             Node
            /    \
           /      \
Wired → Node ───── Node
           \      /
            \    /
             Node
```

- For example, if one node fails
  - Other nodes can potentially provide an alternative path
  - The network may lose some coverage or performance, but it doesn't necessarily go down completely.

```
Node A ─── ❌ Node B
   \              /
    └── Node C ──┘
```

![OSI Model comunication](./static/tutorial_0011.png)

### Comparison

|                      | **Ad Hoc**   | **Infrastructure**   | **Wireless Mesh**      |
| -------------------- | ------------ | -------------------- | ---------------------- |
| Central AP           | ❌            | ✅                    | Usually multiple nodes |
| Device communication | Direct       | Through AP           | Through mesh nodes     |
| Scale                | Small        | Small → Large        | Medium → Large         |
| Coverage             | Limited      | AP-dependent         | Large                  |
| Redundancy           | Low          | Usually low          | **High**               |
| Self-healing         | ❌            | ❌                    | **✅**                  |
| Common use           | P2P/personal | Home & business WLAN | Large homes/businesses |


# Network devices are not assigned to a specific OSI layer


## SOHO Device

### What Is a SOHO Device?

- SOHO = Small Office / Home Office
- A SOHO device is essentially an all-in-one wireless router with expanded capabilities.
- People commonly call it a wireless router, which is understandable, but technically it usually contains many other network functions

```
              SOHO DEVICE
┌─────────────────────────────────────┐
│                                     │
│  Router                             │
│  Wireless Access Point (WAP)        │
│  Switch                             │
│  Firewall                           │
│  DHCP Server                        │
│  NAT                                │
│  + Other features                   │
│                                     │
└─────────────────────────────────────┘
```

### Core Functions

- There is no strict universal list of what a SOHO device must contain.
- However, typical consumer SOHO devices provide at least

| Function        | Purpose                                  |
| --------------- | ---------------------------------------- |
| **Router**      | Connects different IP networks           |
| **WAP**         | Provides Wi-Fi connectivity              |
| **Switch**      | Connects wired devices                   |
| **Firewall**    | Controls network traffic                 |
| **DHCP Server** | Automatically assigns IP addresses       |
| **NAT**         | Translates private ↔ public IP addresses |

### Additional Features

- More expensive SOHO devices may provide additional functionality such as:
  - File server
  - Proxy server
  - Quality of Service (QoS)
  - Gaming optimization
  - Traffic management
  - Protocol-specific optimization
  - USB/network storage features
  - VPN functionality

## Firewall

### What Is a Firewall?

- A firewall is a fundamental IT security mechanism used to control and filter network traffic.
- Its primary purpose is to:
  - Allow legitimate traffic and block unwanted or potentially malicious traffic according to security rules.
- A firewall can protect:
  - An entire network
  - Individual computers/hosts
  - Specific sensitive areas of a network

### Two Primary Categories

- There are two major categories:

| Type                       | Also called                   | Protects                     |
| -------------------------- | ----------------------------- | ---------------------------- |
| **Network-based firewall** | Hardware / Appliance firewall | A network or network segment |
| **Host-based firewall**    | Software firewall             | Individual computer/server   |


#### Network-based

- The firewall sits at a strategic point and controls traffic passing between networks.

```
Internet
   │
   ▼
[Firewall]
   │
   ▼
Internal Network
 ┌──┼──┐
PC Server PC
```

#### Host-based

- The firewall runs directly on the operating system.
  - For example, modern operating systems commonly include a built-in software firewall

```
        Network
           │
           ▼
      ┌─────────┐
      │  PC     │
      │ Firewall│
      └─────────┘
```

### Why Use Firewalls?

- A basic security principle is: **Don't automatically trust traffic coming from outside your trusted network.**
- The firewall acts as a security boundary between networks with different trust levels.
- It examines traffic and applies its configured security rules.

### Defense in Depth

- Use multiple independent security controls/layers rather than relying on a single protection mechanism.

```
# A network doesn't necessarily rely on only one firewall.

Internet
   │
   ▼
[Firewall 1]
   │
   ▼
General LAN
   │
   ├───────────────┐
   │               │
   ▼               ▼
Marketing       [Firewall 2]
                    │
                    ▼
              Server Network
```

### Three Firewall Generations

| Generation | Type                                         | Main idea                                                            |
| ---------- | -------------------------------------------- | -------------------------------------------------------------------- |
| **1st**    | Packet-filtering firewall                    | Filters based on basic packet information                            |
| **2nd**    | Circuit-level firewall                       | Monitors TCP sessions/connections                                    |
| **3rd**    | Application-layer / Next-Generation Firewall | Provides more advanced inspection and application-aware capabilities |


#### First Generation — Packet Filtering

- This is the most basic type.
- It applies rules based on information such as:
  - Source IP
  - Destination IP
  - Protocol
  - Port number
- Example Rule:
  - Source IP     → 192.168.1.50
  - Protocol      → TCP
  - Destination   → Port 80
  - Action        → DENY

#### Second Generation — Circuit-Level Firewall

- A circuit-level firewall focuses on connections/sessions, particularly TCP sessions.
- The firewall monitors whether traffic belongs to a valid/established session.

```
# TCP establishes a connection using the famous:

Client                 Server

  SYN ────────────────►
      ◄──────── SYN/ACK
  ACK ────────────────►

# TCP session established
```

#### Third Generation — Application Layer / NGFW

- These firewalls can provide significantly more advanced traffic inspection and application-aware security capabilities than basic packet filtering.

```
# OSI:

Layer 7 ─ Application
          ↑
NGFW / Application-aware
```

## VoIP Endpoint

### What Is VoIP?

- VoIP = Voice over Internet Protocol
- VoIP allows voice communication to run over an IP network instead of traditional telephone networks.
- A VoIP endpoint is a device used to make/receive VoIP calls.
- Examples:
  - Physical VoIP phone
  - Software/softphone on a computer
  - Mobile/other VoIP applications

### Traditional Phone vs VoIP

#### Traditional POTS

- POTS = Plain Old Telephone Service

```
Telephone
    │
Telephone Line
    │
Telephone Network
```

#### VoIP

- The major difference is that the VoIP phone becomes an IP network device.

```
VoIP Phone
    │
 Ethernet / Wi-Fi
    │
   LAN
    │
 IP Network
```

### VoIP Phone Is a Network Device

- A physical VoIP phone connects to the network like other devices.
- It typically has:
  - MAC address
  - IP address
  - Network interface
  - Network configuration

### VoIP Uses Specialized Protocols

- VoIP systems use specialized protocols to establish and manage calls.
- One important example is: **SIP — Session Initiation Protocol**
  - **SIP** is used for things such as:
    - Establishing calls
    - Managing sessions
    - Ending calls

### Hardware vs Software VoIP

- VoIP endpoints can be either hardware or software.

#### Hardware VoIP phone

- Looks like a traditional office phone but connects to the IP network.

```
       [VoIP Phone]
             │
          Ethernet
             │
          [Switch]
             │
           Network
```

#### Software VoIP / Softphone

- A software application can turn a computer into a phone.

```
# Laptop
┌──────────────────┐
│   Softphone      │
│                  │
│  ☎ Call         │
│  Voicemail       │
└──────────────────┘
        │
      Network
```

### VoIP vs POTS

| Feature            | POTS                            | VoIP                                        |
| ------------------ | ------------------------------- | ------------------------------------------- |
| Full name          | Plain Old Telephone Service     | Voice over Internet Protocol                |
| Network            | Traditional telephone network   | IP network                                  |
| Addressing         | Traditional telephone numbering | IP/network infrastructure + phone numbering |
| Endpoint           | Traditional telephone           | IP phone / software                         |
| Network connection | Telephone line                  | Ethernet/Wi-Fi/IP network                   |
| Protocols          | Traditional telephony protocols | SIP and other VoIP protocols                |


# Physical - OSI layer 1 - Network Access - TCP/IP Layer 1

## Network Cabling

### Types of Network Cabling

- There are 3 main types of network cabling introduced in this section:

| Cable Type       | Basic Description                                        | Common Use                          |
| ---------------- | -------------------------------------------------------- | ----------------------------------- |
| **Coaxial**      | Central conductor surrounded by insulation and shielding | Cable Internet, legacy networks     |
| **Twisted Pair** | Pairs of copper wires twisted together                   | Most traditional Ethernet LANs      |
| **Fiber Optic**  | Uses light through optical fiber                         | High-speed/long-distance networking |

### Coaxial Cable

#### What is the Coaxial Cable?

- Coaxial cable is largely obsolete/antiquated technology for modern internal computer networks.
- It was commonly used in network infrastructure in the 1980s.
- Today, the main place you are likely to encounter coaxial cable is with:
  - Cable modem connections
  - Cable TV

![Coaxial Cable](./static/tutorial_0013.png)

#### Coaxial Cable Structure

- Outer PVC jacket
  - Protects the cable physically.
  - Often black, white, etc.
- Metallic shield
  - Provides shielding against electromagnetic interference.
- Insulator
  - Separates the shield from the center conductor.
- Metallic center conductor
  - Carries the electrical signal.

```
┌─────────────────────────────┐
│ Outer PVC Jacket            │
│ ┌─────────────────────────┐ │
│ │ Metallic Shield         │ │
│ │ ┌─────────────────────┐ │ │
│ │ │ Insulator           │ │ │
│ │ │   ┌─────────────┐   │ │ │
│ │ │   │ Center      │   │ │ │
│ │ │   │ Conductor   │   │ │ │
│ │ │   └─────────────┘   │ │ │
│ │ └─────────────────────┘ │ │
│ └─────────────────────────┘ │
└─────────────────────────────┘
```

#### Coaxial Cable Connectors

##### BNC Connector (Bayonet Neill–Concelman)

- Commonly used with coaxial networks in the 1980s.
- Uses a push-and-twist locking mechanism

![BNC Connector](./static/tutorial_0015.png)

##### F Connector

- The F-type connector is commonly used for:
  - Cable modems  
  - Cable TV

![F Connector](./static/tutorial_0016.png)

#### RG-59 vs RG-6

- There are different types/thicknesses of coaxial cable.

| Type      | Characteristics | Typical use              |
| --------- | --------------- | ------------------------ |
| **RG-59** | Thinner         | Older/video applications |
| **RG-6**  | Thicker         | Cable modem / cable TV   |


### Twisted Pair

#### What is the Twisted Pair?

- Twisted pair copper cabling is the most common type of network cabling.
- It normally uses an RJ-45 connector.
- Each cable contains four twisted pairs, for a total of 8 copper wires
- Each pair carries balanced signals
  - Wire 1 -> Positive signal
  - Wire 2 -> Negative signal

#### Why Are the Wires Twisted?

- The main purpose of twisting is to reduce interference

##### Crosstalk

- Crosstalk occurs when a signal from one pair interferes with another pair.
  - The twisting helps reduce this interference between pairs

```
Orange pair ──────┐
                  ├── Signal interference
Green pair  ──────┘
```

##### Electromagnetic Interference (EMI)

- Twisting makes the cable less susceptible to EMI
  - EMI is disruption to electronic equipment caused by electromagnetic fields from other electronic devices.
- Examples include environments containing:
  - Manufacturing equipment
  - Motors
  - Large electrical devices
  - Other sources of electromagnetic fields

#### UTP vs STP

- There are two major forms of twisted-pair cabling:

| Type    | Meaning                 | Shielding            | Typical environment   |
| ------- | ----------------------- | -------------------- | --------------------- |
| **UTP** | Unshielded Twisted Pair | No additional shield | Normal offices/homes  |
| **STP** | Shielded Twisted Pair   | Yes                  | High-EMI environments |

- UTP
  - cheaper
  - common in normal offices
- STP
  - better protection against EMI
  - more expensive
  - useful in manufacturing/industrial environments with significant EMI.

#### Factors Affecting Cable Speed

##### Twist rate

- Higher-category cables generally have more twists per inch.
- More twisting helps reduce crosstalk and interference

```
CAT 5e  → fewer twists
CAT 6   → more twists
CAT 7   → more twists
CAT 8   → more twists
```

##### Conductor Quality

- Better-quality copper and more consistent wire diameter can improve:
  - Signal transmission
  - Signal integrity
  - Data rates

##### Insulation and separation

- Better insulation and physical separation between pairs help reduce:
  - Interference
  - Signal degradation

##### Shielding

- Shielding helps block EMI, especially in electrically noisy environments.

##### Supported frequency

- Higher maximum frequency generally allows the cable to support higher network speeds.

#### Twisted-Pair Cable Categories

| Category   | Example Ethernet standard | Approx. maximum speed* | Typical max distance |
| ---------- | ------------------------- | ---------------------: | -------------------: |
| **Cat 3**  | 10Base-T                  |                10 Mbps |                100 m |
| **Cat 5**  | 100Base-TX                |               100 Mbps |                100 m |
| **Cat 5e** | 1000Base-T                |                 1 Gbps |                100 m |
| **Cat 6**  | 1000Base-T / 10GBASE-T    |              1–10 Gbps |         100 m / 55 m |
| **Cat 6a** | 10GBASE-T                 |                10 Gbps |                100 m |
| **Cat 7**  | 10 Gbps-class             |               10 Gbps+ |              ~100 m* |
| **Cat 8**  | 25/40GBASE-T              |             25–40 Gbps |                 30 m |

- The general progression is:
  - Higher bandwidth → higher speed → better signal performance
  - However, higher category doesn't automatically mean longer distance
    - Higher speed can require shorter cable distances.

```
Cat 3
  ↓
Cat 5
  ↓
Cat 5e
  ↓
Cat 6
  ↓
Cat 6a
  ↓
Cat 7
  ↓
Cat 8
```

![Twisted-Pair Cable Categories](./static/tutorial_0017.png)

#### Cable Category vs Ethernet Standard

- Retailers usually advertise the Cat number.
- So when shopping for a cable, you're much more likely to search for:
  - Cat 6 Ethernet cable rather than 1000Base-T cable

#### Common Categories

- Cat 5e
  - Up to 1 Gbps
  - Inexpensive
  - Very common
- Cat 6
  - Up to 1 Gbps at 100 m
  - Can support 10 Gbps over shorter distances
  - Slightly more expensive
  - Very common
- Cat 6a
  - Designed for 10 Gbps up to 100 m
  - More expensive than Cat 6
- Cat 7 / Cat 8 More specialized:
  - Higher performance
  - Often shielded
  - More expensive
  - Cat 7: useful in environments with higher EMI requirements
  - Cat 8: very short, high-speed data-center/server-room links

![Twisted Pair](./static/tutorial_0014.png)

#### RJ-45 Connectors

##### Four Color-Coded Pairs

- The four twisted pairs are color-coded:
  - Orange / Orange-White
  - Green  / Green-White
  - Blue   / Blue-White
  - Brown  / Brown-White
- So 8 wires -> 4 twisted pairs -> RJ-45 connector

##### TIA/EIA 568A and 568B

- TIA/EIA 568A and 568B are industry wiring standards that define how the 8 wires are arranged on an RJ-45 connector. There are two standards: 568A and 568B.
- 568A → original standard
- 568B → newer standard and commonly used
- Both can work for network cabling.
- The important thing is to use one standard consistently throughout a network.

##### 568A Pinout

| Pin | Wire         |
| --: | ------------ |
|   1 | White/Green  |
|   2 | Green        |
|   3 | White/Orange |
|   4 | Blue         |
|   5 | White/Blue   |
|   6 | Orange       |
|   7 | White/Brown  |
|   8 | Brown        |


##### 568B Pinout

| Pin | Wire         |
| --: | ------------ |
|   1 | White/Orange |
|   2 | Orange       |
|   3 | White/Green  |
|   4 | Blue         |
|   5 | White/Blue   |
|   6 | Green        |
|   7 | White/Brown  |
|   8 | Brown        |

##### Straight-Through vs Crossover

- There are two traditional Ethernet cable types:
  - Straight-through  
  - Crossover
  - The difference is the pinout on each end

###### Straight-through

- Both ends use the same standard:

```
568B ───────────── 568B
```

```
568A ───────────── 568A
```

- Traditionally used to connect unlike devices:

```
PC ─────── Switch
Switch ─── Router
```

###### Crossover

- The two ends use different standards:

```
568A ───────────── 568B
```

- Traditionally used to connect like devices

```
PC ───── PC
Router ─ Router
```

##### Why Do We Need Crossover Cables?

- This comes from obsolete/antiquated  Ethernet technology. For 10Base-T and 100Base-T
  - One pair was used for transmitting (TX).
  - One pair was used for receiving (RX).
  - Only pins 1, 2, 3, and 6 were used.
  - The green and orange pairs had different TX/RX roles.

- Example: If both PCs use a straight-through cable

```
PC A                         PC B

TX Pin 1 ──────────────────────► Pin 1 TX
TX Pin 2 ──────────────────────► Pin 2 TX

RX Pin 3 ◄────────────────────── Pin 3 RX
RX Pin 6 ◄────────────────────── Pin 6 RX
```

##### Modern Gigabit Ethernet (GBase-T)

- Starting with Gigabit Ethernet / Cat 5e and newer:
  - Uses all four pairs
  - Uses the blue and brown pairs in addition to green and orange.
  - Each pair can support bidirectional transmission.
  - Data can travel in both directions on each pair.
- Therefore: Crossover cables became largely unnecessary with modern Gigabit Ethernet equipment.

![RJ-45 Connectors](./static/tutorial_0021.png)

![RJ-45 Connectors](./static/tutorial_0022.png)

#### Other Copper Connectors

- RJ-11
  - Smaller than RJ-45
  - Uses two twisted pairs / four wires in the lecture's description
  - Primarily associated with telephone/landline connections
  - Not normally used for Ethernet networking.

![RJ-11](./static/tutorial_0018.png)

- DB-9
  - Used for serial connections.
  - A typical networking use is connecting directly to a managed:
    - Switch
    - Router
    - for access to its CLI/console management interface.

![DB-9](./static/tutorial_0019.png)

- DB-25
  - An older connector historically used for things such as serial printer connections. 
  - It is now largely obsolete

![DB-25](./static/tutorial_0020.png)

### Fiber Optic

#### What Is Fiber Optic Cabling?

- Fiber optic cabling is different from traditional twisted-pair copper cabling because it does not transmit electrical signals.
- Instead, fiber optic cable uses photons (light) to transmit data.
- The center of the cable contains a glass or plastic core through which light pulses travel
  - The outer jacket, buffer, and cladding protect the core.
- Fiber is commonly used in:
  - Enterprise networks
  - WANs
  - Long-distance network connections
  - ISP networks

![Fiber Optic](./static/tutorial_0023.png)

#### Advantages of Fiber Optic

- Fiber optic is more expensive than twisted-pair copper, including both the cable and related equipment. However, it provides several major advantages

##### Higher bandwidth

- Fiber can support significantly higher speeds

##### Much longer distance

- Copper twisted-pair: 100 meters
- Fiber can reach: 75 miles or more in the example given.

##### Fiber Is Not Affected by EMI

- Another major advantage is that fiber optic cabling:
  - Does not suffer from electromagnetic interference (EMI)
  - Does not emanate electrical signals

#### Types of Fiber

![Types of Fiber](./static/tutorial_0024.png)

##### Multimode Fiber

- Multimode fiber has a larger core: 50–62.5 microns
- It allows multiple light beams to travel through the fiber simultaneously.
- The light can bounce off the walls of the core, which limits its distance and speed compared with single-mode fiber.
- Typical use:
  - LANs
  - Campus networks
  - Building-to-building connections
  - Shorter distances

##### Single-Mode Fiber

- Single-mode fiber has a much smaller core: 8–10 microns
- It carries essentially one light beam at a time.
- Because the light does not bounce off the walls in the same way as multimode transmission, it can support:
  - Longer distances
  - Higher speeds
- Typical use:
  - ISP networks
  - Metropolitan Area Networks (MANs)
  - Long-distance connections

##### Multimode vs Single-Mode

| Feature     | Multimode              | Single-mode               |
| ----------- | ---------------------- | ------------------------- |
| Core size   | 50–62.5 µm             | 8–10 µm                   |
| Light       | Multiple beams         | One beam                  |
| Distance    | Shorter                | Much longer               |
| Speed       | Lower than single-mode | Higher                    |
| Typical use | LAN / campus           | ISP / MAN / long-distance |


#### Fiber Optic Connectors

![Fiber Optic Connectors](./static/tutorial_0025.png)

##### LC — Lucent Connector

- Small connector
- Uses a locking flange similar in appearance to RJ-45
- Designed for one fiber
- Used with both multimode and Single-Mode Fiber 
- Common in Gigabit and 10-Gigabit Ethernet applications

![LC — Lucent Connector](./static/tutorial_0026.png)

##### SC — Subscriber Connector

- Square-shaped connector
- Uses a push-pull mechanism
- Used with Multimode Fiber and Single-Mode Fiber Gigabit Ethernet applications.

![SC — Subscriber Connector](./static/tutorial_0027.png)

##### ST — Straight Tip

- Round connector
- Uses a bayonet-style twist-and-lock mechanism
- Similar to the locking mechanism used by older BNC-style connectors.
- Historically used with multimode fiber.
- No longer commonly used

![ST — Straight Tip](./static/tutorial_0028.png)

##### MTRJ — Mechanical Transfer Registered Jack

- Similar appearance to LC
- Designed for two fibers
- Commonly associated with multimode fiber in the lecture

![MTRJ](./static/tutorial_0029.png)

## Network Interface Card (NIC)

### What is a NIC?

- A Network Interface Card (NIC) is a hardware component that allows a device to connect and communicate with a network.
- Other terms for NIC include:
  - Network Interface Card
  - NIC
  - Network Adapter
- If a device needs to communicate on a network, it needs at least one network interface.

### NIC and MAC Address

- Each NIC has a unique MAC address associated with it.

```
NIC
 └── MAC Address
       ↓
   Unique identifier
```

- The MAC address is associated with the network interface hardware.
- Although the operating system can spoof the MAC address, that does not physically change the hardware's original address

### A Device Can Have Multiple NICs

- A computer does not have to have only one NIC.
- Example
  - Each network interface can have its own: MAC address, IP address

```
# A modern desktop might have

Desktop
 ├── Ethernet NIC
 │     └── RJ-45
 │
 └── Wi-Fi NIC
       └── Radio
```

```
# Servers commonly have multiple network interfaces

Server
 ├── NIC 1 → Network A
 └── NIC 2 → Network B
```

## Hub

### What is a Hub?

- A hub is a legacy networking device that was commonly used in older networks.
- Today, hubs have been almost completely replaced by switches.
- A hub and a switch may look physically similar, but they operate very differently internally.
  - Hub = Dumb device
  - Switch = Smart device

### Hub and Star Topology

- A hub can act as the central connecting device in a star topology.

```
# All devices connect to the hub.

          PC1
           │
PC2 ───── HUB ───── PC3
           │
          PC4

```

### Hub = Multi-Port Repeater

- A hub is essentially a multi-port repeater.
  - When data enters one port, the hub repeats it out through all other connected ports.
- For example
  - Even if PC1 only wants to communicate with PC4, the hub sends the signal to PC2, PC3, and PC4.
  - PC2 and PC3 will receive the signal and determine that the data isn't intended for them, so they discard it.

```
PC1 ──> HUB ──> PC2
             ├─> PC3
             └─> PC4
```

### Why Are Hubs Bad?

#### Network Collisions

- Because the hub sends traffic to every port, all connected devices share the same communication medium.
  - This creates a collision.
  - The larger the network, the greater the potential for collisions.

#### Security Problem

- Hubs can also create security concerns.
  - Because traffic is repeated out to every port
  - Other devices may receive traffic that wasn't intended for them.
  - A switch, on the other hand, can make forwarding decisions based on MAC addresses, so traffic can normally be sent only toward the appropriate destination port.

## Wireless Range Extender - Wi-Fi Repeater

### What is a Wireless Range Extender?

- A Wireless Range Extender is a device that extends the coverage/range of an existing Wi-Fi network.
- It works similarly to a repeater
  - The extender receives the wireless signal from the WAP and rebroadcasts it to areas where the original signal is weak.

### How Does It Work

- So the extender does not create a completely new network connection. 
- It mainly repeats/rebroadcasts the existing wireless signal.

```
Wireless Access Point
        │
        │ Wi-Fi signal
        ▼
[Range Extender]
        │
        │ Re-broadcast
        ▼
  Extended Wi-Fi Area
```

### When Would You Use One?

- A range extender is useful when
  - Your house is large.
  - Your office has areas with weak Wi-Fi.
  - Some rooms are outside the WAP's effective coverage.
  - There is radio-frequency interference.
  - You have multiple floors.

## Modem

### What Is a Modem?

- **Modem = Modulator + Demodulator**. The name comes from:
  - Mo → Modulator
  - Dem → Demodulator
- Its basic job is to convert signals between the communication medium and the form used by the computer/network equipment.

### Cable Internet Example

- A typical home cable Internet setup

```
          ISP / Internet
                │
          Coaxial Cable
        (lecture: analog)
                │
                ▼
            [Modem]
        Analog ↔ Digital
                │
            RJ-45 Ethernet
                │
                ▼
        [SOHO Device]
                │
            Router
                │
            Firewall
                │
      ┌─────────┴───────┐
      │                 │
      WAP              DHCP
      │                 │
      └────────┬────────┘
               │
            Home LAN
```

## Media Converter

### What Is a Media Converter?

- A media converter is a device that converts a network signal from one physical media type to another.
- The most common example is: **Copper Ethernet ↔ Fiber Optic**

```
[Switch]
   │
   │ RJ-45 / Copper
   ▼
[Media Converter]
   │
   │ Fiber Optic
   ▼
[Server]
```

### Why Do We Need One?

- Different network devices may use different physical media.
- For example:
  - Switch → Copper Ethernet (RJ-45)
  - Server → Fiber optic
  - They cannot directly connect using their different cable types.
  - The media converter sits between them and converts the physical signal

# Data link - OSI layer 2 - Network Access - TCP/IP Layer 1

## MAC Addresses - Media Access Control (MAC)

### What is a MAC Address?

- MAC stands for Media Access Control.
- A MAC address is the physical/hardware address associated with a device's **network adapter**.
- A network adapter is also called:
  - Network Interface Card (NIC)
  - Network Adapter
  - These terms are generally interchangeable

![network adapter](./static/tutorial_0002.png)

### MAC Address vs. MAC Address Spoofing

- Traditionally, a MAC address is assigned to the network interface hardware.
- It is associated with the hardware rather than being simply an IP address configured by the user.
- However, an operating system can perform MAC address spoofing.
  - The hardware's original MAC address isn't physically changed. Instead, the operating system is instructed to use a different MAC address.
  - MAC spoofing is also relevant in cybersecurity and network testing.

### MAC Address Format

- A MAC address is: 48 bits - 6 bytes
  - Usually represented in hexadecimal
  - Example: 00:1A:2B:3C:4D:5E

```
00 : 1A : 2B : 3C : 4D : 5E
 └───────┘   └───────────────┘
   3 bytes         3 bytes
  (24 bits)       (24 bits)
    |                 |
    ▼                 ▼
   OUI       Individual identifier
```

#### OUI — Organizationally Unique Identifier

- OUI stands for Organizationally Unique Identifier.
- The OUI identifies the organization/manufacturer associated with the network interface.
- OUIs are assigned through the IEEE
  - Institute of Electrical and Electronics Engineers

#### Individual identifier

- The remaining 24 bits can be used to identify individual network interfaces under that OUI.
- 2²⁴ ~16.7 Million Unique Addresses

## Switch

### What is a Switch?

- A switch is a network device used to connect multiple devices in a LAN (Local Area Network).
- It uses MAC addresses to forward Ethernet frames to the appropriate destination port
- Like a hub, a switch can act as the central connecting device in a star topology.
  - Although a hub and switch may look similar physically, they work very differently internally.

```
          PC1
           │
PC2 ──── Switch ──── PC3
           │
          PC4
```

### MAC Address Table / CAM Table

- A switch learns the MAC addresses of connected devices and stores them in a table.
- This table can be called:
  - MAC address table
  - CAM table (CAM = Content Addressable Memory)

### How a Switch Forwards Data

```
PC1 ──> Switch ──> MAC Address Table -> MAC Destination -> Port -> PC4
```

- How a Switch Works
  - Reads the source and destination MAC addresses.
  - Learns or updates the source MAC address and its associated port.
  - Looks up the destination MAC address in its MAC address table.
  - Forwards the frame through the appropriate port if the destination is known.

- Suppose PC1 wants to send data to PC4.
  - The switch checks its MAC/CAM table: `PC4's MAC → Port 4`
  - Therefore, it forwards the frame only through Port 4.
  - Another devices don't receive the frame

### MAC Address Learning

- A switch needs to learn which MAC addresses are reachable through which ports.
  - Known destination: Forward the frame to the associated port.
  - Unknown destination: Flood the frame to other ports in the same VLAN.
  - Broadcast destination: Flood the frame within the VLAN, excluding the incoming port.

### Collision Domains

#### What Is a Collision Domain?

- A collision domain is a network segment in which data-frame collisions can potentially occur when devices transmit simultaneously.
- Collisions can occur in traditional Ethernet networks using hubs or switches operating in half-duplex mode.
- One of the biggest advantages of a switch is that it breaks up collision domains.
  - **Hub**: A hub creates essentially one large collision domain
  - **Switch**: With a switch, each switch port represents a separate collision domain in the traditional Ethernet model

#### Hub — One Collision Domain

- A hub operates as a multiport repeater.
- Incoming signals are repeated to all other ports.
- All connected devices share one collision domain.
- Simultaneous transmissions can cause collisions throughout the shared network segment.
- As the network grows, collisions can degrade performance.

#### Switch in Half-Duplex Mode — Multiple Collision Domains

- Each switch port creates a separate collision domain.
- A switch forwards frames to the appropriate destination port rather than repeating every frame to all devices.
- Collisions are confined to the individual collision domain where they occur.
- This reduces the impact of collisions compared with a hub.

#### Switch in Full-Duplex Mode — No Collisions

- Each device can transmit and receive simultaneously.
- There is no shared transmission medium competing for access in each direction.
- Ethernet collisions do not occur during normal full-duplex operation.
- Full-duplex improves network efficiency and allows simultaneous transmission and reception.

#### How Are Collisions Mitigated?

- CSMA/CD stands for Carrier Sense Multiple Access with Collision Detection.
- It is a mechanism used by traditional shared Ethernet and half-duplex Ethernet to manage collisions.
- Its basic process is:
  - Carrier Sense: Listen to the medium before transmitting.
  - Multiple Access: Multiple devices share the same medium.
  - Collision Detection: Detect a collision while transmitting.
  - Recovery: Stop transmission, wait for a random backoff period, and retry
- **Note** that CSMA/CD is not needed for normal full-duplex Ethernet because collisions do not occur in that mode

### Broadcast Domain

- A switch does NOT normally break up a broadcast domain.
- Example

```
# For example, if PC3 sends a broadcast
# The broadcast can be forwarded to the other ports.

              ┌──→ PC1
              ├──→ PC2
PC3 → SWITCH ─┼──→ PC4
              └──→ PC5
```

- Therefore: **A basic Layer 2 switch = multiple collision domains but one broadcast domain.**


### Security Advantage

- Switches are also more secure than hubs.
- Remember
  - A switch does not automatically make a network completely secure. 
  - There are techniques such as MAC flooding, port mirroring, ARP spoofing, etc., that can affect Layer 2 security.

| **Hub**                                                                                                                    | **Switch**                                                                 |
| -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| Because the hub **repeats the signal to every port**, another device connected to the hub may potentially capture traffic. | The switch normally **forwards the frame only toward the appropriate por** |

### Why the switch can still have one large broadcast domain?

- When a new computer joins a network, it may not have an IP address yet.
  - It can send **a DHCP broadcast** asking: "Is there a DHCP server that can give me an IP address?"
  - The switch can forward this broadcast within the LAN.

```
PC
 │
 │ DHCP Broadcast
 ↓
Switch
 │
 ├──→ Other devices
 │
 └──→ DHCP Server
```

- This is why the switch can still have **one large broadcast domain**, even though it has **multiple collision domains**

### Switch vs. Hub

- The most important difference:
  - Hub -> repeats traffic everywhere
  - Switch -> intelligently forwards traffic to the destination

|                    | **Hub**         | **Switch**           |
| ------------------ | --------------- | -------------------- |
| OSI Layer          | **Layer 1**     | **Layer 2**          |
| Type               | Dumb device     | Intelligent device   |
| Main function      | Repeats signals | Forwards frames      |
| Uses MAC addresses | ❌               | ✅                    |
| Traffic            | To all ports    | To destination port  |
| Collision domains  | **1 large**     | **Multiple smaller** |
| Modern LANs        | Legacy          | **Standard**         |

### Unmanaged Switches

- An unmanaged switch is a simple network device designed to work without manual configuration or administration.
  - Typically used in homes and small offices.
  - Plug-and-play: connect the power and Ethernet cables, and it works.
  - Requires little to no network administration.
  - Offers limited monitoring and configuration capabilities.
  - Generally cheaper than managed switches.
- Example: Connecting desktop computers, printers, and other wired devices in a home LAN.

### Managed Switches

- A managed switch provides advanced configuration, monitoring, and network management features. 
  - It is commonly used in business and enterprise networks.
- Network administrators can configure and manage it through a command-line interface (CLI), web interface, or management software.
- Common management protocols include SSH, SNMP, and, on older systems, Telnet. 
  - Telnet is unencrypted and should generally be avoided in favor of SSH.

### Access port

- Typically connects to an end device, such as a PC or printer.
- Assigned to a single VLAN for ordinary access traffic.
- Frames sent by the end device are usually untagged.
- The switch associates incoming frames with the port's configured VLAN.

### Trunk port

- Commonly connects switches to carry multiple VLANs over one link.
- Carries traffic for multiple VLANs.
- Uses IEEE 802.1Q tags to identify VLAN membership for tagged frames.
- Allows the same VLAN to span multiple switches.

### Virtual LANs (VLANs)

#### What Is a VLAN?

- A VLAN (Virtual Local Area Network) is a logical network created within a physical switched network. 
- It divides one physical LAN into multiple separate logical networks.
- A managed switch can assign different physical ports to different VLANs, allowing devices to be grouped by department, function, or security requirements rather than physical location.

#### Why Do We Use VLANs?

- Broadcast domain separation: Broadcast traffic in one VLAN is not normally forwarded into another VLAN.
- Improved security: Departments can be isolated from each other, with access controlled through routing, firewall rules, and other security policies.
- Logical segmentation: Devices can belong to the same department network even when located on different floors.
- Better network organization: Administrators can group devices according to business roles rather than physical location.
- Scalability: Multiple managed switches can carry the same VLANs across a building or campus

#### How VLANs Work Across Multiple Switches

- The switches use a trunk link to carry traffic for both VLANs
- For example, when an HR computer on Floor 1 sends a frame to an HR computer on Floor 2:
  - The first switch receives the frame on an access port assigned to VLAN 10.
  - The switch forwards the frame through the trunk link, tagging it with VLAN ID 10.
  - The second switch reads the tag and identifies the frame as belonging to VLAN 10.
  - The second switch forwards the frame through the appropriate VLAN 10 access port.

### Layer 3 Switches

#### What Is a Layer 3 Switch?

- A Layer 3 switch is a managed network switch that supports both:
  - Layer 2 switching (Data Link Layer): Uses MAC addresses to forward Ethernet frames within a VLAN.
  - Layer 3 routing (Network Layer): Uses IP addresses to route packets between different networks, including different VLANs.

#### Layer 2 Switch vs. Layer 3 Switch

| Feature                       | Layer 2 Switch                      | Layer 3 Switch                           |
| ----------------------------- | ----------------------------------- | ---------------------------------------- |
| OSI layer                     | Layer 2                             | Layers 2 and 3                           |
| Forwarding information        | MAC addresses                       | MAC addresses and IP routing information |
| Connect devices within a VLAN | Yes                                 | Yes                                      |
| Route between VLANs           | No, not by itself                   | Yes                                      |
| Inter-VLAN routing            | Requires a router or Layer 3 device | Can perform routing directly             |
| Typical usage                 | LAN connectivity                    | Enterprise LANs and inter-VLAN routing   |

### Port Mirroring (SPAN)

#### What Is Port Mirroring?

- Port mirroring is a feature on managed switches that copies network traffic from one or more source ports (or VLANs) to a designated monitoring port.
- It is used for network monitoring, diagnostics, and troubleshooting without interrupting normal network communication.
- Port mirroring is also commonly called SPAN (Switched Port Analyzer), particularly on Cisco switches.

#### How Does Port Mirroring Work?

- The process works as follows:
  - The administrator selects the source ports or VLANs to monitor.
  - The switch copies traffic from those sources.
  - The switch sends the copies to the designated monitoring port.
  - A monitoring device captures and analyzes the traffic.

### Power over Ethernet (PoE)

#### What Is Power over Ethernet?

- Power over Ethernet (PoE) is a technology that allows Ethernet cables to carry both data and electrical power to network devices.
- Instead of using separate cables for network connectivity and power, a single Ethernet cable can provide both.

#### Common PoE Devices

- VoIP phones — Voice over IP communication.
- Wireless access points (APs) — Provide Wi-Fi connectivity.
- IP security cameras — Enable network video surveillance.

## Wireless Access Point (WAP)

### What is a Wireless Access Point?

- A Wireless Access Point (WAP) is a dedicated network device that bridges a wired network to a wireless network.

```
Wired Network
     │
     │ Ethernet cable
     ▼
   [ WAP ]
   /  |  \
  /   |   \
Wi-Fi Wi-Fi Wi-Fi
 PC  Phone  Tablet
```

### WAP is NOT a Router

| Device          | Main Function                                               |
| --------------- | ----------------------------------------------------------- |
| **WAP**         | Bridges wired network ↔ wireless network                    |
| **Router**      | Connects different IP networks and performs Layer 3 routing |
| **SOHO device** | Usually combines router + switch + WAP + other functions    |


### What Devices Connect to a WAP?

- A WAP allows many wireless devices to connect to the network:
  - Smartphones
  - Laptops
  - Tablets
  - IoT devices
  - Smart speakers
  - Smart lights
  - Smart plugs
  - Smart refrigerators
  - Smart garage doors
  - Other wireless devices

## Network Protocol

### ARP - Address Resolution Protocol

#### What is ARP?

- ARP (Address Resolution Protocol) is used to resolve an IP address to its corresponding MAC address. 
  - **IP address → MAC address**
- ARP is needed when a device knows the destination's IP address but does not know its MAC address.

#### Where does ARP work?

- ARP works within the local area network (LAN).
  - ARP uses broadcast messages to find the device with a specific IP address.
  - Broadcast traffic is not forwarded by routers.
  - Therefore, ARP cannot directly resolve the MAC address of a device on another network.
  - For more detail broadcast: [Broadcast](#broadcast)

```
Same LAN:
PC1 ─── Switch ─── PC2
       ARP works

Different LAN:
PC1 ─── Router ─── PC2
       ARP does NOT cross the router
```

#### ARP Request vs ARP Reply

| Message         | Destination     | Purpose                               |
| --------------- | --------------- | ------------------------------------- |
| **ARP Request** | Broadcast       | Ask which device owns an IP address   |
| **ARP Reply**   | Usually Unicast | Return the MAC address of that device |


#### How ARP works

- Suppose

```
PC1:
IP: 192.168.1.100
MAC: Unknown

PC2:
IP: 192.168.1.115
MAC: AA:BB:CC:DD:EE:FF
```

- PC1 wants to communicate with PC2 but only knows `192.168.1.115`
  - PC1 sends an **ARP Request** as a broadcast: **Who has 192.168.1.115? Tell me your MAC address**

- Every device on the LAN receives the broadcast
  - Only PC2 recognizes that the requested IP belongs to it, so PC2 sends an **ARP Reply** **192.168.1.115 is at AA:BB:CC:DD:EE:FF.**

- PC1 can then associate **192.168.1.115 → AA:BB:CC:DD:EE:FF**
  - And use the MAC address to deliver the Ethernet frame

- After learning the MAC address, the device stores the mapping in its ARP cache/table
  - Example

```
Interface: 192.168.2.48 --- 0x5
  Internet Address      Physical Address      Type
  192.168.2.1           14-49-bc-6e-82-90     dynamic
  192.168.2.10          58-cd-c9-51-e3-e3     dynamic
  192.168.2.12          a8-42-a1-c3-cf-6f     dynamic
  192.168.2.13          20-0b-74-13-a4-fe     dynamic
  192.168.2.14          e4-24-6c-a7-1a-2b     dynamic
  192.168.2.17          6e-76-54-32-9b-26     dynamic
.....................................................

Interface: 192.168.56.1 --- 0xb
  Internet Address      Physical Address      Type
  192.168.56.255        ff-ff-ff-ff-ff-ff     static
  224.0.0.2             01-00-5e-00-00-02     static
  224.0.0.22            01-00-5e-00-00-16     static
....................................................
```

#### Viewing the ARP table

- The basic command on macOS, Linux, Windows is `arp -a`

# Network - OSI layer 3 - Internet - TCP/IP Layer 2

## Network device

### Router

#### What Does a Router Do?

- A router connects different networks together.
- This is the key difference:
  - Switch → connects devices within the same network
  - Router → connects different networks

- Example: If PC1 wants to communicate with PC3, they are on different networks, so the traffic must pass through the router.

```
Network A                              Network B
192.168.1.0/24                         192.168.2.0/24

 PC1 ──┐                              ┌── PC3
       │                              │
    [Switch]                        [Switch]
       │                              │
 PC2 ──┘                              └── PC4
       │                              │
       ↓                              ↓
   [Router A] ──────────────── [Router B]
       │        Network Link        │
       └────────────────────────────┘
```

#### Router Uses IP Addresses

- A router operates primarily at: **OSI Layer 3 — Network Layer**
- It uses **IP addresses** to determine where packets should go.

| Device | OSI Layer | Main Address | Main Function                  |
| ------ | --------: | ------------ | ------------------------------ |
| Hub    |   Layer 1 | —            | Repeat signals                 |
| Switch |   Layer 2 | **MAC**      | Forward frames within LAN      |
| Router |   Layer 3 | **IP**       | Route packets between networks |

#### Router vs Switch

- **Switch**: "Which port is this MAC address connected to?"

```
# Same Network

PC1 ─── Switch ─── PC2
       MAC address
```

- **Router**: "Which network should I send this IP packet toward?"

```
# Different Networks

PC1 ─── Switch ─── Router ─── Switch ─── PC2
                  IP address
```

#### Routers Determine the Best Path

- The routers determine an appropriate/best route toward the destination based on their routing information

#### A router separates broadcast domains

- A router therefore creates a boundary between different Layer 3 networks/broadcast domains.

```
 Broadcast Domain A
 PC1 ── Switch ──┐
                 │
              [Router]
                 │
                 └── Switch ── PC3
                     Broadcast Domain B
```

#### Example

```
# When PC1 wants to communicate with PC3:

PC1
Network: 192.168.1.0/24

        ↓

[Switch]

        ↓

[Router]

        ↓

[Switch]

        ↓

PC3
Network: 192.168.2.0/24
```

- Step 1 — PC1 sends the frame
  - PC1 sends traffic toward the router through the local switch.
- Step 2 — Switch forwards using MAC
  - The switch examines the destination MAC address and uses its CAM/MAC table to determine the correct port.
- Step 3 — Router receives the packet
  - The router examines the destination IP address
- Step 4 — Router chooses the route
  - The router checks its routing information and determines where to forward the packet.
- Step 5 — Destination network
  - Eventually the packet reaches the destination network.
  - The destination switch then uses MAC addresses to deliver the frame to PC3

## Network Address Translation (NAT)

### What Is NAT?

- Network Address Translation (NAT) is a technique that translates IP addresses, typically allowing devices with private IPv4 addresses to communicate with devices on the public Internet.
- For example:
  - Devices in a home network use private IP addresses, while the router uses a public IP address to communicate with the Interne

### Benefits of NAT

- Conserves public IPv4 addresses: Multiple devices can share a public IP address when using NAT.
- Hides internal addressing: External devices normally see the translated public address rather than the private source address.
- Supports private networks: Devices can use private IPv4 addresses while accessing public Internet services.

### Type of NAT

#### Static NAT

- Static NAT = One private IP address mapped to one public IP address.
- The mapping is fixed and remains configured until it is changed.
- Example:
  - Private IP: 192.168.1.10	
  - Public IP: 203.0.113.10
- A common use case is mapping an internal server to a dedicated public IP address.
  - The server can be reachable from the Internet if the routing and firewall rules allow it.
  - The external user connects to the public IP, not the server's private IP.
  - Each statically mapped device generally requires its own public IP address.

#### Dynamic NAT

- Dynamic NAT = Private IP addresses are mapped to available public IP addresses from a pool.
- Example: A network has four computers but only three available public IP addresses.
  - When all three public addresses are in use, the fourth computer cannot obtain a mapping until an address becomes available.
  - Dynamic NAT can reuse a smaller pool of public addresses across devices that need access at different times. 
  - However, it does not let all four devices simultaneously use the three addresses through ordinary dynamic NAT alone.

| Device | Private IP   | Public IP Mapping        |
| ------ | ------------ | ------------------------ |
| PC 1   | 192.168.1.10 | 203.0.113.10             |
| PC 2   | 192.168.1.11 | 203.0.113.11             |
| PC 3   | 192.168.1.12 | 203.0.113.12             |
| PC 4   | 192.168.1.13 | No address available yet |

#### Port Address Translation (PAT)

- PAT = Many private IP addresses share one public IP address by using different port numbers
- PAT is also known as NAT Overload and is commonly used in home and small office networks
- Example

| Internal Device | Private IP and Port  | Translated Public IP and Port |
| --------------- | -------------------- | ----------------------------- |
| PC 1            | `192.168.1.10:50001` | `203.0.113.10:40001`          |
| PC 2            | `192.168.1.11:50002` | `203.0.113.10:40002`          |
| PC 3            | `192.168.1.12:50003` | `203.0.113.10:40003`          |
| PC 4            | `192.168.1.13:50004` | `203.0.113.10:40004`          |

##### How PAT works

- A computer sends a packet to an Internet server.
- The router replaces the private source IP with its public IP and assigns or selects a translated source port.
- The router records the mapping in its NAT/PAT translation table.
- When the response returns, the router checks the destination public IP and port to identify the correct internal connection.
- The router translates the destination back to the private IP and port, then forwards the packet to the correct devic


### Which Devices Can Perform NAT?

- Routers: The most common device performing NAT in home and business networks.
- Firewalls: Many firewalls also provide NAT and security policy enforcement.
- Proxy servers: Can mediate connections between clients and external services, but a proxy is not necessarily performing IP-level NAT.

## Demilitarized Zone - DMZ

### What Is a DMZ?

- A Demilitarized Zone (DMZ) is a perimeter network designed to isolate publicly accessible services from an organization's internal private network (Intranet).
- The main purpose of a DMZ is to provide access to public-facing resources while protecting the internal network from untrusted users on the Internet.
- Example: 
  - An insurance company has an internal LAN containing private files, employee information, and internal email servers. 
  - Its public website is placed in a DMZ so that Internet users can access the website without gaining direct access to the internal LAN.

### Common Services Hosted in a DMZ

- These services are isolated from the internal network to reduce the risk of unauthorized access.
  - Web servers: Host publicly accessible websites.
  - FTP servers: Provide file downloads, such as software and device drivers.
  - Email servers or gateways: Handle email services that need to communicate with external networks.

### Typical DMZ Network Designs

#### Three-Legged Design

- Uses one firewall/router with three network interfaces.
- One interface connects to the Internet, one to the internal LAN, and one to the DMZ.
- Firewall rules control traffic between all three networks.
- Requires fewer devices and is generally simpler to deploy.


![Three-Legged Design](./static/tutorial_0033.png)

#### Back-to-Back Configuration (Screened Subnet)

- Uses two firewalls, with the DMZ positioned between them.
- The external firewall controls traffic from the Internet to the DMZ.
- The internal firewall controls traffic from the DMZ to the internal LAN.
- Provides an additional security boundary but requires more equipment and configuration.

![Back-to-Back Configuration](./static/tutorial_0034.png)

### How a DMZ Works

- An external user sends a request to a public-facing server.
- The firewall permits the request if it matches the configured security rules.
- The user accesses the service hosted in the DMZ.
- The firewall prevents unauthorized access from the DMZ to the internal LAN.
- Only explicitly permitted traffic can pass between network segments.

## Port Forwarding - Port Redirection

### What Is Port Forwarding?

- Port forwarding is a networking technique that allows users on an external network, such as the Internet, to access a specific service or device inside a private LAN.
- It creates a mapping between:
  - **Public IP : External Port** → **Private IP : Internal Port**
- Port forwarding is commonly configured on SOHO (Small Office/Home Office) routers.

### How Port Forwarding Works

- Suppose a home network contains a web server:

| Component | Address |
|---|---|
| Router public IP | `203.0.113.10` |
| Web server private IP | `192.168.1.100` |
| External port | `80` |
| Internal port | `80` |

- The router can be configured with

```
203.0.113.10:80
        │
        │ Port Forwarding
        ▼
192.168.1.100:80
```

- When an Internet user sends a request to `http://203.0.113.10:80`
  - The router recognizes the port-forwarding rule and sends the traffic to `192.168.1.100:80`
  - The internal web server then processes the request

### Port Forwarding vs. Static NAT

- Port forwarding is closely related to Static NAT, but port forwarding also uses port numbers to determine where traffic should go.

| Static NAT | Port Forwarding |
|---|---|
| Maps one IP address to another IP address | Maps an IP + port to another IP + port |
| `Public IP → Private IP` | `Public IP:Port → Private IP:Port` |
| Usually exposes an address mapping | Exposes specific services |
| Example: `203.0.113.10 → 192.168.1.100` | `203.0.113.10:80 → 192.168.1.100:80` |

### Common Uses

- Port forwarding is often used to provide remote access to:
  - Web servers
  - Game servers
  - NAS devices
  - Remote-access services
  - Other self-hosted applications

### Security Considerations

- Port forwarding exposes a service inside the private network to the Internet.
- Unlike a properly segmented DMZ, the server may still reside on the same LAN as other internal devices
- If the exposed server is compromised, it may provide an attacker with opportunities to attack other devices on the same network.
- Therefore, only necessary ports should be forwarded, and exposed services should be properly secured and kept updated.

## Access Control Lists - ACLs

### What is an ACL?

- Access Control List (ACL) is a security feature used to create allow/deny rules that filter network traffic.
- ACLs can be configured on various network devices, including:
  - Routers
  - Firewalls
  - Proxy servers
  - End-user devices
- They can control traffic entering or leaving a network

### ACL Rules

- The ACL is applied to the interface connected to the Internet.

| Rule | Destination | Ports | Action | Purpose |
|---|---|---|---|---|
| 1 | `192.168.100.0/24` | `0–65535` | **Deny** | Block Internet access to internal network |
| 2 | `192.168.200.1/24` | `0–79`, `81–65535` | **Deny** | Block all ports on web server except HTTP |
| 3 | `192.168.200.1/24` | `80` | **Allow** | Allow HTTP access to web server |

## Network Protocol

### Internet Protocol - IP

#### Binary math basic

##### Why Binary Math Matters

- IPv4 addresses can be represented in two formats:
  - Dotted-decimal: `192.168.1.100`
  - Binary: `11000000.10101000.00000001.01100100`
- Understanding binary is important because:
- It helps you understand the internal structure of IPv4 addresses.
- It is essential for subnetting, an important networking skill

##### The IPv4 Binary Weight Table

```
| Bit             | 128 | 64 | 32 | 16 |  8 |  4 |  2 |  1 |
| --------------- | --: | -: | -: | -: | -: | -: | -: | -: |
| Binary position |  2⁷ | 2⁶ | 2⁵ | 2⁴ | 2³ | 2² | 2¹ | 2⁰ |
```

##### Binary to Decimal

- Rule for each bit:
  - 1 → add the corresponding value
  - 0 → ignore the value
- Example 1
  - Convert `10101010`
  - Only add the values where the bit is 1 
    - `1 × 2^7 + 0 × 2^6 + 1 × 2^5 + 0 × 2^4 + 1 × 2^3 + 0 × 2^2 + 1 × 2^1 + 0 × 2^0`
    - `128 + 32 + 8 + 2`
    - Therefore `10101010 = 170`

```
128  64  32  16   8   4   2   1
 1   0   1   0    1   0   1   0
```

##### Decimal to Binary

- Can I use this value without making the total greater than the target number?
  - Yes → write 1 and subtract/use the value
  - No → write 0
- Example: 192 → Binary
  - Target 192
  - Start with 128
    - Because 128 = 2^7 < 192 and 2^8 = 256 > 192
  - Write 1. Remaining 192 - 128 = 64
  - Then 64 = 2^6 ≤ 64
  - Write another 1 Remaining: 64 - 64 = 0
  - All remaining bits are 0
  - Therefore 192 = 11000000

![Decimal to Binary](./static/tutorial_0031.png)

##### Decimal Fractions to Binary

- Multiply the fractional part by 2.
- Record the integer part of the result (0 or 1).
- Keep only the fractional part and multiply it by 2 again.
- Repeat until the fractional part becomes 0 or until you have enough binary digits.
- Read the recorded integer parts from top to bottom.
- Example

```
0.625 × 2 = 1.25 → 1 
0.25 × 2 = 0.50 → 0 
0.50 × 2 = 1.00 → 1

# Therefore: 0.625₁₀ = 0.101₂
```

##### Binary Fractions to Decimal

- To convert the fractional part of a binary number to decimal:
  - Each position after the binary point represents a negative power of 2

```
2⁻¹ 2⁻² 2⁻³ 2⁻⁴
```

- Example
  - Convert 0.101₂ to decimal:

```
0.101₂
= 1 × 2⁻¹ + 0 × 2⁻² + 1 × 2⁻³
= 1 × 0.5 + 0 × 0.25 + 1 × 0.125
= 0.625

Therefore:

0.101₂ = 0.625₁₀
```

#### What is IP?

- IP (Internet Protocol) is a protocol of the TCP/IP Internet layer and corresponds primarily to Layer 3 (Network Layer) of the OSI model.
- IP provides end-to-end connectivity between different Layer 2 networks.
- Its two major responsibilities are:
  - Logical addressing → IP addresses
  - Routing → moving packets between different networks

#### Characteristics of IP

| Characteristic               | Description                                                     |
| ---------------------------- | --------------------------------------------------------------- |
| **Connectionless**           | IP does not establish a connection before sending packets.      |
| **Unreliable**               | IP does not guarantee packet delivery.                          |
| **Best effort**              | IP attempts to deliver packets but provides no guarantee.       |
| **Independent packets**      | Each packet is handled independently.                           |
| **No sequencing**            | IP does not ensure packets arrive in the correct order.         |
| **No error recovery**        | IP does not retransmit lost or corrupted packets.               |
| **No delivery confirmation** | IP does not check whether the destination received the packet.  |
| **Supports routing**         | Routers use IP information to forward packets between networks. |

#### Packets Can Take Different Paths

- Because IP works with routing, different packets belonging to the same communication may take different paths.

#### What is an IP Addresses?

- A logical address assigned to a device.
- Unlike a MAC address, an IP address is configured by the operating system/network configuration.
- It can be assigned:
  - Manually → Static IP (Manually configured. The administrator enters the IP address.)
  - Dynamically → DHCP
- It identifies a device on an IP-based network.
- There are two major versions:

| Version | Name                        | Example        |
| ------- | --------------------------- | -------------- |
| IPv4    | Internet Protocol version 4 | `192.168.1.10` |
| IPv6    | Internet Protocol version 6 | `2001:db8::1`  |

#### IP Address vs MAC Address

| **Category**                 | **IP Address**                                                                                         | **MAC Address**                                                                                              |
| ---------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| **Definition**               | A **logical address**                                                                                  | A **physical/hardware address** associated with a network interface card (NIC)                               |
| **OSI Layer**                | **Layer 3 — Network Layer**                                                                            | **Layer 2 — Data Link Layer**                                                                                |
| **Main Purpose**             | Used for **network-to-network communication**, especially when traffic needs to travel through routers | Used primarily for **communication within a local network (LAN)**                                            |
| **Communication**            | **Network → Network**                                                                                  | **Device/interface → Device/interface within a local network**                                               |
| **Main Network Device**      | **Router**                                                                                             | **Switch**                                                                                                   |
| **Assignment**               | **Static** or **Dynamic**                                                                              | Associated with the **NIC hardware**                                                                         |
| **Static Assignment**        | Manually configured by a network administrator                                                         | Normally associated with the network interface hardware                                                      |
| **Dynamic Assignment**       | Automatically assigned by a **DHCP server**                                                            | Not normally assigned by DHCP                                                                                |
| **Can be spoofed?**          | Yes                                                                                                    | Yes — the OS can spoof a MAC address, but this does not physically change the address stored by the hardware |
| **Example**                  | `192.168.1.10`                                                                                         | `00:1A:2B:3C:4D:5E`                                                                                          |
| **Example of communication** | Your home network → Router → Internet → Gmail network → Gmail server                                   | PC → Switch → PC / Printer                                                                                   |
| **Key concept**              | **Routing**                                                                                            | **Switching**                                                                                                |

#### Static IP Address

- A static IP address is manually configured by an administrator or user.
  - The IP address does not change automatically.
  - It only changes when someone manually reconfigures it.
  - Static IPs are commonly used for devices that need a predictable address.
- Typical examples:
  - Servers/infrastructure → usually Static
  - DNS servers
  - Web servers
  - Network printers
  - Routers / default gateways
- Advantages:
  - Predictable and easy to locate
  - Easier for administrators to manage
  - Prevents services from becoming unreachable because an IP changed

#### Dynamic IP Address

- A dynamic IP address is automatically assigned by a mechanism such as:
  - DHCP (Dynamic Host Configuration Protocol)
  - APIPA (Automatic Private IP Addressing)
  - IPv6 Stateless Address Autoconfiguration (SLAAC)
- Dynamic addresses can change over time.
- Typical examples
  - End-user devices → usually Dynamic/DHCP
  - PCs
  - Laptops 
  - Smartphones

#### Disadvantages of IPv4

- IPv4 has several limitations that IPv6 was designed to address.
- Limited address space: 
  - IPv4 uses 32-bit addresses, providing approximately 4.3 billion possible addresses. 
  - The growing number of Internet-connected devices makes this insufficient.
- Less efficient routing: IPv4 has a variable-length header, which can make packet processing and routing more complex.
- Optional security: Security mechanisms such as IPsec can be used with IPv4, but they are not mandatory.
- Increasing demand: Computers, smartphones, smart TVs, and IoT devices all require network connectivity, increasing the demand for IP addresses.

##### Why Is IPv4 Still Used?

- Despite IPv6's advantages, IPv4 remains widely used because several techniques help conserve its address space.
  - Subnetting: Divides a network into smaller networks, allowing IP addresses to be allocated more efficiently
  - Private IP addresses: Allow devices within private networks, such as office LANs and home networks, to communicate without each device requiring its own public IP address
  - Network Address Translation (NAT): Allows multiple devices using private IP addresses to share a public IPv4 address when accessing the Internet.

#### Advantages of IPv6

- IPv6 introduces several improvements over IPv4.
- Larger address space: IPv6 uses 128-bit addresses, providing 2^128 possible addresses
- Simplified routing: IPv6 has a fixed 40-byte base header, helping simplify packet processing.
- Automatic configuration: IPv6 supports Stateless Address Autoconfiguration (SLAAC), allowing devices to configure their own IP addresses without requiring a dedicated DHCP server.
- Improved security support: IPv6 includes support for IPsec, which provides authentication and encryption capabilities.
- Simplified addressing: IPv6 eliminates the traditional Class A, Class B, and Class C addressing system used in classful IPv4 networking.

#### IPv4 vs. IPv6

- IPv4 is still widely used, especially in many LANs.
- IPv4 is important for IT certifications because you need to understand:
  - IPv4 address structure
  - Network and host portions
  - Subnet masks
  - Subnetting
- IPv6 is more advanced. For basic IT knowledge, an introductory understanding is usually sufficient.
- Deeper IPv6 knowledge becomes more important for network engineers, especially when pursuing Cisco/Juniper-oriented networking paths

| Feature               | IPv4                                                | IPv6                                                             |
| --------------------- | --------------------------------------------------- | ---------------------------------------------------------------- |
| Address size          | 32 bits                                             | 128 bits                                                         |
| Address space         | Approximately 4.3 billion                           | Approximately \\(3.4 \times 10^{38}\\)                           |
| Header size           | Variable, 20–60 bytes                               | Fixed 40-byte base header                                        |
| Routing               | Less efficient in some scenarios                    | Designed to simplify routing                                     |
| Address configuration | Manual or DHCP                                      | Manual, DHCPv6, or SLAAC                                         |
| IPsec                 | Optional                                            | Support is part of the IPv6 specifications; not mandatory to use |
| Address classes       | Traditional classful addressing exists historically | No Class A, B, or C                                              |
| Deployment            | Introduced in 1981                                  | Standardized and deployed beginning in the late 1990s            |


#### IPv4 Address Structure

- An IPv4 address contains: **32 binary bits = 4 octets = 4 bytes**
- Example:
  - `192.168.1.131`
  - The computer internally represents this using binary `11000000.10101000.00000001.10000011`

##### What is an Octet?

- An IPv4 address is divided into four octets:

```
192 . 168 . 1 . 131
 ↑     ↑    ↑    ↑
Octet Octet Octet Octet
```

- Each octet contains 8 bits:

```
11000000
10101000
00000001
10000011
```

##### Network Portion and Host Portion

- An IPv4 address consists conceptually of two parts

```
+-------------------+----------------+
| Network Portion   | Host Portion   |
+-------------------+----------------+
```

- The network portion identifies the network.
- The host portion identifies a specific device within that network.
- The exact boundary between network and host cannot be determined from the **IP address** alone.
  - We need **the subnet mask**

#### IPv4 Address Classes

- IPv4 originally used a classful addressing system consisting mainly of three classes:

| Class | Network Bits | Host Bits | Number of Networks | Hosts per Network | Address Range                 | Default Subnet Mask |
| ----- | -----------: | --------: | -----------------: | ----------------: | ----------------------------- | ------------------- |
| **A** |            8 |        24 |                126 |        16,777,214 | `1.0.0.0 – 126.255.255.255`   | `255.0.0.0`         |
| **B** |           16 |        16 |             16,384 |            65,534 | `128.0.0.0 – 191.255.255.255` | `255.255.0.0`       |
| **C** |           24 |         8 |          2,097,152 |               254 | `192.0.0.0 – 223.255.255.255` | `255.255.255.0`     |


- 127 is excluded because it is reserved for a special purpose
- Class D and Class E also exist, but they are outside the main scope of this lecture.
- Each IPv4 octet contains 8 bits.
  - Therefore, each octet can contain values from `0 → 255`
  - There are 256 possible values, because zero is included `2⁸ = 256`
  - The maximum value is `128 + 64 + 32 + 16 + 8 + 4 + 2 + 1 = 255`

#### Usable IPv4 Addresses 

##### Power of Two

- In binary, the number of possible combinations is calculated using the power of two:

```
1 bit → 2¹ = 2
2 bits → 2² = 4
3 bits → 2³ = 8
...
n bits → 2ⁿ
```

- For networking, understanding powers of two is important because they are used to calculate:
  - Number of networks
  - Number of IP addresses
  - Number of hosts per network
  - Number of subnets
  - Number of hosts per subnet

| Power | Value |
| ----: | ----: |
|    2¹ |     2 |
|    2² |     4 |
|    2³ |     8 |
|    2⁴ |    16 |
|    2⁵ |    32 |
|    2⁶ |    64 |
|    2⁷ |   128 |
|    2⁸ |   256 |
|    2⁹ |   512 |
|   2¹⁰ | 1,024 |
|   2¹¹ | 2,048 |
|   2¹² | 4,096 |

##### Total IP Addresses vs. Usable IP Addresses

- The total number of IP addresses in a network is not the same as the number of usable host addresses.
- Each IPv4 network **reserves two addresses**:
  - **Network address** → identifies the network itself
  - **Broadcast address** → used to send traffic to all hosts in the network
- Therefore, **Usable Hosts = 2^n - 2**
  - `n` = number of host bits
  - `2^n` = total addresses in the block
  - `-2` = network address + broadcast address
- Example

```
# If a network has 7 host bits:

2^7 = 128 total addresses

128 - 2 = 126 usable host addresses
```

| Class       | Network Bits | Host Bits | Default Subnet Mask     | Total Addresses / Network | Usable Host Addresses |
| ----------- | -----------: | --------: | ----------------------- | ------------------------: | --------------------: |
| **Class A** |            8 |        24 | `255.0.0.0` (`/8`)      |      2²⁴ = **16,777,216** |        2²⁴-2 =**16,777,214** |
| **Class B** |           16 |        16 | `255.255.0.0` (`/16`)   |          2¹⁶ = **65,536** |            2¹⁶-2 =**65,534** |
| **Class C** |           24 |         8 | `255.255.255.0` (`/24`) |              2⁸ = **256** |                2⁸-2=**254** |


#### IPv4 Address Components

![IPv4 Address Components](./static/tutorial_0030.png)

##### IP Address

- Unique logical address assigned to each device on a network

##### Subnet Mask

- The subnet mask tells us which part of an IPv4 address represents:
  - The network
  - The host
- The subnet mask uses
  - 1 = Network portion
  - 0 = Host portion
- Example
```
# Class C:

# Subnet mask:
11111111.11111111.11111111.00000000
|                        | |      |   
|-------Network----------| |-Host-|
        24 bits             8 bits

# Class A:

# Subnet mask:
11111111.00000000.00000000.00000000
|       |                        |
|-------Network------------------|
  8 bits             24 bits
           Host


# Class B:

# Subnet mask:
11111111.11111111.00000000.00000000
|                | |              |
|------Network---| |-----Host-----|
      16 bits          16 bits
```


###### Don't Determine the Class From IP Alone

- An IP address may originally fall within a Class A, B, or C range, but subnetting can change the subnet mask and divide the original network into smaller networks.

###### CIDR Notation

- CIDR = Classless Inter-Domain Routing
- CIDR provides a shorthand way to represent the subnet mask.
- The number after `/` represents the number of network bits.
- Examples `192.168.1.0/24` means

```
# 24 network bits
# 8 host bits

255.255.255.0
```

###### Calculate the Subnet Mask from CIDR Notation

- IPv4 addresses contain **32 bits**
- If the CIDR prefix is `/n`:
- The first **n** bits are set to **1**.
- The remaining **32 - n** bits are set to **0**
- Example: `/26`
  - `11111111.11111111.11111111.11000000`
  - Convert each octet to decimal:
    - 11111111 = 255
    - 11111111 = 255
    - 11111111 = 255
    - 11000000 = 192
- Therefore: `/26` = `255.255.255.192`

###### Common Subnet Mask Values

| CIDR  | Binary                                | Subnet Mask       |
| ----- | ------------------------------------- | ----------------- |
| `/24` | `11111111.11111111.11111111.00000000` | `255.255.255.0`   |
| `/25` | `11111111.11111111.11111111.10000000` | `255.255.255.128` |
| `/26` | `11111111.11111111.11111111.11000000` | `255.255.255.192` |
| `/27` | `11111111.11111111.11111111.11100000` | `255.255.255.224` |
| `/28` | `11111111.11111111.11111111.11110000` | `255.255.255.240` |
| `/29` | `11111111.11111111.11111111.11111000` | `255.255.255.248` |
| `/30` | `11111111.11111111.11111111.11111100` | `255.255.255.252`  |


##### Default Gateway

- The default gateway is typically the IP address of a router on the local network.
- It allows a device to communicate with other networks
- If the destination is outside the local subnet, the computer sends the traffic toward the default gateway
- Is Default Gateway Mandatory? **No**
  - A device can communicate with devices on its local subnet without a default gateway.
  - For example, an isolated network could have `PC1 ─── PC2 ─── PC3` with no Internet or external network connection.

##### Network Address

- A Network Address is the first IP address in a network. 
- It identifies the network itself rather than a specific host.
- The host portion of the IP address is set to all `0`
- How to Find the Network Address
  - IP Address: `192.168.1.25/24` in binary is `11000000.10101000.00000001.00011001`
  - IP Address: `192.168.1.25/24` it is 24 network bits and 8 host bits
  - Set all host bits to `0` is `11000000.10101000.00000001.00000000`
  - Therefore, Network Address = `192.168.1.0`

```
# IP Address 192.168.1.25/24

11000000.10101000.00000001.00011001
|------- Network --------| |-Host-|                            
```

##### Broadcast Address

- A broadcast address is the last IP address in a network. 
- It is used to send a packet to all hosts within the same network.
- Formula To find the broadcast address, set all host bits to `1`
  - **Broadcast Address = Network bits + all Host bits set to 1**

- Example
  - Given the network `192.168.0.0/16` 
    - 16 network bits (For more detail [CIDR Notation](#cidr-notation))
    - 32 - 16 = 16 host bits (For more detail [IPv4 Address Structure](#ipv4-address-structure))
  - The subnet mask is `255.255.0.0`
  - To find the broadcast address, set all host bits to `1` **192.168.255.255**

```
# The subnet mask 255.255.0.0

11111111.11111111.00000000.00000000
|---Network-----| |------Host-----|
    16 bits            16 bits
```

#### Public IPv4 Addresses

- Public IP addresses are routable on the Internet.
- Must be Globally Unique
  - Web Servers
  - DNS Servers
  - Routers
- Originally, the IPv4 Class A, B, and C address spaces were designed primarily for public use.
- Organizations had to register public IP addresses.
- The original classful design eventually caused IPv4 address exhaustion because the number of Internet-connected devices grew rapidly.

#### Private IPv4 Addresses

- Private IP addresses are not routable on the public Internet.
  - Private IP addresses cannot directly communicate across the public Internet.
  - Therefore, networks commonly use NAT (Network Address Translation) or PAT (Port Address Translation)
- They are unregistered and can be freely reused by different organizations.
- They are intended for internal/private networks.
- Different homes or companies can use the same private IP ranges without conflict because their networks are separate.

| **Class** | **Private Range**               |   **Network ID** | **Number of Networks** | **Addresses per Network** |
| --------- | ------------------------------- | ---------------: | ---------------------: | ------------------------: |
| **A**     | `10.0.0.0 – 10.255.255.255`     |`10.0.0.0/8` |                      1 |                16,777,216 |
| **B**     | `172.16.0.0 – 172.31.255.255`   |`172.16.0.0-172.31.0.0/16` |                     16 |                    65,536 |
| **C**     | `192.168.0.0 – 192.168.255.255` |`192.168.0.0-192.168.255.0/16` |                    256 |                       256 |


#### Private vs. Public IP Addresses

##### Network Structure

- A typical SOHO (Small Office/Home Office) network has:
  - Internal network (LAN) → uses private IP addresses.
  - SOHO device/router → connects the internal network to the Internet.
  - External network (Internet) → uses public IP addresses.
  - The SOHO device can provide several functions:
    - Router
    - Wireless Access Point
    - Firewall
    - NAT device
    - Switch

```
                         INTERNET
                             │
                             │
                   Public IP: 140.100.100.150
                             │
                    ┌─────────────────┐
                    │   SOHO Router   │
                    │  NAT / Firewall │
                    └────────┬────────┘
                             │
                             │
                      Private Network
                      192.168.100.0/24
                             │
                    ┌────────┴────────┐
                    │      Switch     │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              │              │              │
           Tablet         Laptop         Smart TV
       192.168.100.10  192.168.100.11  192.168.100.12
              │
           Desktop
       192.168.100.13
```

##### Private IP Addresses

- Devices inside the LAN use private IP addresses.
- These addresses are used for communication inside the local network

- Example:
  - Network address: 192.168.0.0/16
  - Broadcast address: 192.168.255.255
  - Router:     192.168.100.1
  - Tablet:     192.168.100.10
  - Laptop:     192.168.100.11
  - Smart TV:   192.168.100.12
  - Desktop:    192.168.100.13

##### Public IP Address

- The router has a public IP address on its Internet-facing interface.
  - This address is visible to systems on the Internet.
  - Multiple devices inside the network can share the same public IP address
- Example:

```
  Private IP                  Public IP 
192.168.100.11 ── NAT ──> 140.100.100.150
```

##### NAT (Network Address Translation)

- NAT translates private IP addresses into a public IP address when devices communicate with the Internet.


##### Router Interfaces

- Public interface
  - Faces the Internet.
  - Uses a public IP address.
  - Receives/sends traffic to external networks.
- Private interface
  - Faces the internal LAN.
  - Uses a private IP address.
  - Communicates with devices inside the network.

```
                    Internet
                       |
                       |
             Public Interface
             140.100.100.150
                       |
                +-------------+
                |   Router    |
                |     NAT     |
                +-------------+
                       |
             Private Interface
              192.168.100.1
                       |
                       |
                Internal LAN
              192.168.100.0/24
```

#### Loopback Address

##### What is the Loopback Address?

- The loopback address is a special IP address used by a computer to communicate with itself.
- In IPv4, the loopback range is: `127.0.0.0 - 127.255.255.255`
- In the traditional IPv4 address classes system **Class A: 1 – 126**
  - You may notice that 127 is missing.
  - This is because the entire `127.0.0.0 - 127.255.255.255` range is reserved for loopback
- The most commonly used loopback address is `127.0.0.1`
- It is also commonly called `localhost`

##### What Does Loopback Mean?

- Loopback means that network traffic is sent back to the same host.
- The packet is handled internally by the operating system. It does not need to go through:
  - Network Interface Card (NIC)
  - Ethernet/Wi-Fi
  - Network cable
  - Router
  - Switch
  - Internet
- Example

```
Application
    ↓
TCP/IP Stack
    ↓
127.0.0.1
    ↓
TCP/IP Stack
    ↓
Application
```

##### Purpose of Loopback

- The main purpose is to test the TCP/IP networking stack of the operating system
- Example


```bash
ping 127.0.0.1

# If you receive replies: Reply from 127.0.0.1
# it indicates that the TCP/IP stack on the operating system is functioning.
# However, it does not prove that the physical network is working.
```

#### How to Determine Whether Two IP Addresses Are on the Same Network

##### Basic rule

- Two IP addresses are on the same network if their **Network IDs (or Network Address)** are the same.

##### How to calculate network IDs

- An IPv4 address consists of two logical parts:

```
# IP Address
┌────────────────────┬───────────────┐
│     Network Part   │   Host Part   │
└────────────────────┴───────────────┘
```

- The subnet mask tells us where the Network Part ends and the Host Part begins.
  - The `1` represent the network bits.
  - The `0` represent the host bits
- For example

```
# IP Address:
192.168.1.10

# Subnet Mask:
255.255.255.0

# IP Address in binary:
11000000.10101000.00000001.00001010

# Subnet Mask in binary:
11111111.11111111.11111111.00000000
```

- So the Network ID (Network Address) is: `192.168.1.0`

```
11000000.10101000.00000001.00001010
11111111.11111111.11111111.00000000
-----------------------------------
11000000.10101000.00000001.00000000

192.168.1.0
```

##### Example

- Given

```
IP 1:       192.168.1.10
IP 2:       192.168.2.20
Subnet:     255.255.255.0
```

- Determine host bits and network bits
  - `255.255.255.0 = /24`

```
255       . 255       . 255       . 0
11111111  . 11111111  . 11111111  . 00000000

# 24 network bits
# 8 host bits
```

- Calculate the Network Address
  - For IP1 192.168.1.10 -> Network Address = 192.168.1.0
  - For IP2 192.168.2.20 -> Network Address = 192.168.2.0
  - They are different -> Different Networks

```
# IP 1

192       . 168       . 1         . 10
11000000  . 10101000  . 00000001  . 00001010

255       . 255       . 255       . 0
11111111  . 11111111  . 11111111  . 00000000

# Network addess
11000000  . 10101000  . 00000001  . 00000000
192       . 168       . 1         . 0

```

```
# IP 2

192       . 168       . 2         . 20
11000000  . 10101000  . 00000010  . 00010100

255       . 255       . 255       . 0
11111111  . 11111111  . 11111111  . 00000000

# Network addess
11000000  . 10101000  . 00000010  . 00000000
192       . 168       . 2         . 0

```


#### Subnetting

##### Why Subnetting Is Needed?

- Subnetting divides a large IP network into multiple smaller networks called subnets.
- The original classful IPv4 system was inefficient because Class A, B, and C networks had very different sizes:
  - Class A: ~16.7 million addresses per network
  - Class B: ~65,000 addresses per network
  - Class C: ~254 usable host addresses
- Many organizations need something between these sizes. 
  - Subnetting allows a large network to be divided into smaller, more appropriate networks

##### Benefits of Subnetting

- Subnetting provides several benefits:
  - More efficient use of IP addresses
  - More efficient routing
  - Improved network security
  - Logical separation of different groups or systems


##### What Happens When We Subnet?

- An IPv4 address consists of: `Network Portion | Host Portion`
- Subnetting works by borrowing bits from the host portion and using them to create additional subnetworks
- The important trade-off is:
  - **More subnet bits → more subnets, but fewer host addresses per subnet.**

```
# Before subnetting:

Network | Host Host Host Host Host Host Host Host

# After subnetting:

Network | Subnet | Host Host Host Host Host Host
```

##### Calculating the Number of Subnets

- The number of subnets is calculated using `Number of subnets = 2^X`
  - `X` = number of borrowed host bits

##### Calculating Hosts per Subnet

- The number of addresses in each subnet is: `Block Size = 2^Y`
- The number of usable host addresses is: `Usable Hosts = 2^Y - 2`
  - `Y` =  number of remaining host bits
  - The `-2` is because:
    - One address is reserved for the network address
    - One address is reserved for the broadcast address

##### Types of Subnetting

- FLSM — Fixed-Length Subnet Mask
  - Every subnet has the same size.

- VLSM — Variable-Length Subnet Mask
  - Subnets can have different sizes.

```
# FLSM — Fixed-Length Subnet Mask

192.168.1.0/26
├── Network:   192.168.1.0
├── Hosts:     192.168.1.1 - 192.168.1.62
└── Broadcast: 192.168.1.63

192.168.1.64/26
├── Network:   192.168.1.64
├── Hosts:     192.168.1.65 - 192.168.1.126
└── Broadcast: 192.168.1.127

192.168.1.128/26
├── Network:   192.168.1.128
├── Hosts:     192.168.1.129 - 192.168.1.190
└── Broadcast: 192.168.1.191

192.168.1.192/26
├── Network:   192.168.1.192
├── Hosts:     192.168.1.193 - 192.168.1.254
└── Broadcast: 192.168.1.255
```

```
# VLSM — Variable-Length Subnet Mask

192.168.1.0/25
├── Network:   192.168.1.0
├── Hosts:     192.168.1.1 - 192.168.1.126
└── Broadcast: 192.168.1.127

192.168.1.128/26
├── Network:   192.168.1.128
├── Hosts:     192.168.1.129 - 192.168.1.190
└── Broadcast: 192.168.1.191

192.168.1.192/28
├── Network:   192.168.1.192
├── Hosts:     192.168.1.193 - 192.168.1.206
└── Broadcast: 192.168.1.207
```

##### FLSM - Subnetting a Class C Network into Two Subnets

- Starting Network

```
# Given:

# A Class C /24 network has 8 host bits in the last octet

Network:     192.168.1.0
Default Mask: 255.255.255.0
CIDR:         /24
```

- Borrowing Bits
  - To create 2 subnets, we need: `2^n = number of subnets` => `2^1 = 2`
  - Therefore, we borrow 1 host bit.
    - Original:  `/24`
    - Borrow:     1 bit
    - New mask:  `/25`
  - The last octet becomes: `10000000`
    - which equals: `128`
    - Subnet Mask: `255.255.255.128`
    - CIDR: `/25`
  
- Hosts per Subnet
  - After borrowing 1 bit, 7 host bits remain.
    - `Total addresses = 2^7 = 128 addresses`
  - Each subnet has
    - 126 usable host addresses = 128 total addresses - 1 network address - 1 broadcast address

- The Two Subnets
  - The block size is 128, so the subnet boundaries are:
    - 192.168.1.0
    - 192.168.1.128
  - Subnet 1
    - Network:   192.168.1.0/25
    - Hosts:     192.168.1.1 - 192.168.1.126
    - Broadcast: 192.168.1.127
  - Subnet 2
    - Network:   192.168.1.128/25
    - Hosts:     192.168.1.129 - 192.168.1.254
    - Broadcast: 192.168.1.255

##### FLSM - Subnetting a Class C Network into Four Subnets

- Given:

```
Network: 192.168.1.0
Default Class C mask: /24 → 255.255.255.0
Required subnets: 4
```

- Borrow host bits
  - We need 4 subnets 2^n = 4 => Therefore: n = 2
  - So we borrow 2 host bits
    - The original `/24` becomes `/26`
    - New subnet mask `255.255.255.192`

- Calculate addresses per subnet
  - A `/26` leaves `32 - 26 = 6 host bits`
  - Total addresses per subnet: `2^6 = 64`
  - Usable host addresses: `2^6 - 2 = 62`
    - We subtract 2 because each subnet has: 1 Network Address, 1 Broadcast Address

- The four subnets

```
192.168.1.0/26
├── Network:   192.168.1.0
├── Hosts:     192.168.1.1 - 192.168.1.62
└── Broadcast: 192.168.1.63

192.168.1.64/26
├── Network:   192.168.1.64
├── Hosts:     192.168.1.65 - 192.168.1.126
└── Broadcast: 192.168.1.127

192.168.1.128/26
├── Network:   192.168.1.128
├── Hosts:     192.168.1.129 - 192.168.1.190
└── Broadcast: 192.168.1.191

192.168.1.192/26
├── Network:   192.168.1.192
├── Hosts:     192.168.1.193 - 192.168.1.254
└── Broadcast: 192.168.1.255
```

#### IPv6

##### Introduction to IPv6

- IPv6 (Internet Protocol version 6) uses 128-bit addresses, compared with IPv4's 32-bit addresses. - IPv6 provides a much larger address space and uses hexadecimal notation to make addresses shorter and easier to read.
- IPv6 addresses are more complex to understand, so this lecture focuses on their basic structure

##### IPv6 Address Format

- An IPv6 address consists of eight 16-bit hexadecimal blocks, separated by colons `:`

```
2001:0DB8:0000:0000:0000:0000:0370:0001
```

- Each hexadecimal block contains four hexadecimal digits, and each digit represents 4 bits.
  - Therefore `8 * 16 = 128 bits`

###### Number systems used in IPv6

| Number system | Base | Digits used |
| ------------- | ---- | ----------- |
| Binary        | 2    | 0–1         |
| Decimal       | 10   | 0–9         |
| Hexadecimal   | 16   | 0–9 and A–F |

- Hexadecimal represents decimal values 10–15 using letters

| Decimal | Hexadecimal | Binary |
| ------- | ----------- | ------ |
| 0       | 0           | 0000   |
| 1       | 1           | 0001   |
| 2       | 2           | 0010   |
| 3       | 3           | 0011   |
| 4       | 4           | 0100   |
| 5       | 5           | 0101   |
| 6       | 6           | 0110   |
| 7       | 7           | 0111   |
| 8       | 8           | 1000   |
| 9       | 9           | 1001   |
| 10      | A           | 1010   |
| 11      | B           | 1011   |
| 12      | C           | 1100   |
| 13      | D           | 1101   |
| 14      | E           | 1110   |
| 15      | F           | 1111   |

- Why hexadecimal? 
  - Each hexadecimal digit represents exactly 4 bits, making a 128-bit address more compact and readable than its binary representation.

###### IPv6 Address Components

- An IPv6 address can be divided into network and interface portions
  - Network ID includes
    - Site prefix 
    - Subnet ID
  - Interface ID

| Component    | Purpose                                                         |
| ------------ | --------------------------------------------------------------- |
| Network ID   | Identifies the network portion of the address.                  |
| Site Prefix  | Used for routing purposes over the Internet.                    |
| Subnet ID    | Identifies subnets within an internal network.                  |
| Interface ID | Identifies a network interface within the addressing structure. |

- The Interface ID can be configured automatically using information derived from a MAC address, generated using EUI-64, or configured using DHCP or other supported methods.

![IPv6 Address Components](./static/tutorial_0032.png)

###### Simplifying IPv6 Addresses

- Rule 1: Omit leading zeros
  - Leading zeros in any 16-bit block can be removed.

```
# Original: 
2001:0DB8:0000:0000:0370:0000:0000:0001

# Shortened: 
2001:DB8:0:0:370:0:0:1
```

- Rule 2: Replace consecutive zero blocks with `::`
  - A single sequence of consecutive all-zero blocks can be replaced with a double colon.
  - Important: `::` can be used only once in an IPv6 address
  - Otherwise, the number of omitted zero blocks would be ambiguous.

```
# Original: 
2001:0DB8:0000:0000:0370:0000:0000:0001

# Shortened: 
2001:DB8::370:0:0:1
```

###### IPv6 CIDR Notation

- IPv6 supports CIDR (Classless Inter-Domain Routing) notation, just like IPv4
- Unlike traditional IPv4 subnet masks such as `255.255.255.0`, IPv6 commonly expresses the network prefix length directly using CIDR notation.

```
# The /64 indicates that the first 64 bits represent the network prefix, leaving the remaining 64 bits for the interface identifier under this addressing arrangement

2001:DB8:1234:5678:0000:0000:0000:0001/64
```

| Prefix length | Network prefix | Remaining bits     |
| ------------- | -------------- | ------------------ |
| `/64`         | 64 bits        | 128 − 64 = 64 bits |
| `/65`         | 65 bits        | 128 − 65 = 63 bits |
| `/48`         | 48 bits        | 128 − 48 = 80 bits |

###### IPv6 Data Transmission Types

- Unicast — One-to-One
  - Communication occurs between one source and one destination.
  - The packet is delivered to a specific network interface.
  - Unicast works similarly in IPv4 and IPv6.

- Multicast — One-to-Many
  - One source sends packets to a multicast group.
  - Only interfaces that are members of the group are intended to receive the multicast traffic.
  - IPv6 does not use broadcast. Multicast supports many functions that would otherwise require one-to-all delivery.

- Anycast — One-to-One-of-Many
  - The same anycast address is assigned to multiple network interfaces.
  - A packet sent to that address is routed to one of those interfaces, typically the nearest according to routing metrics.
  - It is useful for distributing traffic among multiple servers or routers.

##### IPv6 Unicast Address Types

- IPv6 unicast addresses are used for one-to-one communication between devices. 
- There are three main types of IPv6 unicast addresses, plus a special loopback address.
  - Global Unicast
  - Unique Local
  - Link-Local
  - Loopback

###### Global Unicast Address

- Similar to a public IPv4 address.
- Globally unique and routable across the Internet.
- Used for communication between devices on different networks.
- IPv6 Global Unicast addresses belong to the prefix `2000::/3`.

###### Unique Local Address (ULA)

- Similar to a private IPv4 address, such as `192.168.1.10`.
- Used for internal communication within private networks.
- Routable within an organization's internal network but not globally routable over the public Internet.
- Uses the prefix `FC00::/7`; in practice, locally assigned ULAs commonly begin with FD.

###### Link-Local Address

- Similar in purpose to an IPv4 APIPA address, although their operation and use are not identical.
- Automatically assigned to IPv6 interfaces, or it can be configured manually.
- Used for communication on the same local network link.
- Not forwarded by routers to other links.
- Uses the prefix `FE80::/10`

###### Loopback Address

- IPv6 loopback address: `::1`
- IPv4 loopback address: `127.0.0.1`
- Used to test the local device's networking stack without sending traffic to another device.
- The hostname localhost may resolve to either `127.0.0.1` or `::1`, depending on the system configuration and address selection.

###### Compare types of IPv6 Addresses

| Address Type   | Prefix / Example                                | Purpose                                             | Internet Routable? |
| -------------- | ----------------------------------------------- | --------------------------------------------------- | ------------------ |
| Global Unicast | `2000::/3` (commonly starts with `2000`–`3FFF`) | Communication across networks and over the Internet | Yes                |
| Unique Local   | `FC00::/7` (commonly starts with `FC` or `FD`)  | Private communication within internal networks      | No                 |
| Link-Local     | `FE80::/10`                                     | Communication within the local network link         | No                 |
| Loopback       | `::1`                                           | Testing the local device's IPv6 networking stack    | No                 |

### ICMP - Internet Control Message Protocol

#### What is ICMP?

- ICMP (Internet Control Message Protocol) is a companion protocol to IP and operates at the OSI Layer 3 – Network Layer.
- Its main purpose is:
  - Reporting network errors
  - Reporting delivery problems
  - Performing network diagnostics
  - Helping troubleshoot connectivity
- Important: ICMP reports problems but does not fix them.

#### Key Characteristics

- ICMP does not establish a session before sending messages

| Characteristic       | Description                            |
| -------------------- | -------------------------------------- |
| **Layer**            | OSI Layer 3 – Network                  |
| **Works with**       | IP                                     |
| **Connection**       | Connectionless                         |
| **Purpose**          | Error reporting and diagnostics        |
| **Application data** | Does not carry normal application data |
| **Common tools**     | `ping`, `traceroute` / `tracert`       |

#### ICMP Demo

##### Traceroute / Tracert

- Traceroute is used to discover the network path from a source to a destination

| OS      | Command                    |
| ------- | -------------------------- |
| Linux   | `traceroute <destination>` |
| macOS   | `traceroute <destination>` |
| Windows | `tracert <destination>`    |

##### Ping

- `ping` is used to test whether a destination responds to ICMP Echo messages

```bash
ping 192.168.0.20
```

# Transport - OSI layer 4 - Transport - TCP/IP Layer 3

## Network Protocol

### Understanding Protocols, Ports, and Sockets

#### Protocols

- A protocol is a set of rules that defines how computers communicate and exchange data.
- Examples from the lecture:  DN ,DHC ,HTTP / IIS
- For more detail: [Introduction to Computer Networking Protocols](#introduction-to-computer-networking-protocols)

#### Logical Ports

- A port in networking is a logical port, not a physical port such as USB or RJ-45.
- Ports allow a computer to distinguish between different network applications running on the same machine
- A protocol is associated with a specific port number.

| Protocol |    Port | Purpose                  |
| -------- | ------: | ------------------------ |
| FTP      |      21 | File Transfer            |
| HTTP     |      80 | Web                      |
| DNS      |      53 | Domain Name System       |
| DHCP     | 67 / 68 | Dynamic IP configuration |
| HTTPS    |     443 | Secure Web               |

- Example
  - A server has `IP: 192.168.1.100`
  - It can simultaneously run
    - FTP  → 21
    - HTTP → 80
    - DNS  → 53
  - So a client can specify
    - 192.168.1.100:21  → FTP
    - 192.168.1.100:80  → HTTP
    - 192.168.1.100:53  → DNS

##### Why Do We Need Ports?

- A server can run multiple network services simultaneously
- Without port numbers, the operating system would not know which application should receive incoming network traffic

```
                Server
            192.168.1.100
                   │
       ┌───────────┼───────────┐
       ↓           ↓           ↓
     FTP         HTTP         DNS
     :21         :80          :53
```

##### Three Types of Ports

| Port Type            |       Range | Description                                    |
| -------------------- | ----------: | ---------------------------------------------- |
| **Well-known ports** |      0–1023 | Used by well-known protocols                   |
| **Registered ports** |  1024–49151 | Registered for specific applications/protocols |
| **Dynamic ports**    | 49152–65535 | Used dynamically, typically by clients         |


#### Socket

- A socket is the combination of **IP Address + Port Number**
- This allows the operating system to identify a specific network endpoint
- For example: `192.168.1.1:80` is a socket

#### Common Network Services and Port Numbers

| Service, Protocol, or Application | Port Number(s) | TCP or UDP |
|---|---:|---|
| FTP (File Transfer Protocol) | 20, 21 | TCP |
| SFTP (Secure File Transfer Protocol) | 22 | TCP |
| SSH (Secure Shell Protocol) | 22 | TCP |
| Telnet | 23 | TCP |
| SMTP (Simple Mail Transfer Protocol) | 25 | TCP |
| DNS (Domain Name System) | 53 | UDP |
| DHCP (Dynamic Host Configuration Protocol) | 67, 68 | UDP |
| TFTP (Trivial File Transfer Protocol) | 69 | UDP |
| HTTP (Hypertext Transfer Protocol) | 80 | TCP |
| POP3 (Post Office Protocol version 3) | 110 | TCP |
| NTP (Network Time Protocol) | 123 | UDP |
| IMAP4 (Internet Message Access Protocol version 4) | 143 | TCP |
| SNMP (Simple Network Management Protocol) | 161 | UDP |
| LDAP (Lightweight Directory Access Protocol) | 389 | TCP |
| HTTPS (Hypertext Transfer Protocol Secure) | 443 | TCP |
| SMB (Server Message Block) | 445 | TCP |
| LDAPS (Lightweight Directory Access Protocol Secure) | 636 | TCP |
| RDP (Remote Desktop Protocol) | 3389 | TCP |
| ITU Telecommunication Standardization Sector A/V Recommendation | 1720 | TCP |
| SIP (Session Initiation Protocol) | 5060, 5061 | TCP |

#### `netstat` command

- `netstat -aon` is a Windows command used to display network connections, listening ports, and the Process ID (PID) associated with each connection or port

| Option | Meaning                                                                                   |
| ------ | ----------------------------------------------------------------------------------------- |
| `-a`   | Displays **all** active connections and listening ports                                   |
| `-o`   | Displays **the Process ID (PID)** associated with each connection                         |
| `-n`   | Displays IP addresses and port numbers in **numerical format** instead of resolving names |

```
Active Connections

  Proto  Local Address          Foreign Address        State           PID
  TCP    0.0.0.0:135            0.0.0.0:0              LISTENING       2044
  TCP    0.0.0.0:445            0.0.0.0:0              LISTENING       4
  TCP    0.0.0.0:5040           0.0.0.0:0              LISTENING       7044
  TCP    0.0.0.0:5357           0.0.0.0:0              LISTENING       4
............................................................................
```

- This means:
  - TCP → The connection uses TCP.
  - 0.0.0.0:135 → The computer is listening on port 135 on all IPv4 network interfaces.
  - LISTENING → The application is waiting for incoming connections.
  - 2044 → The PID of the process using port 135.

##### What Does 0.0.0.0 Mean?

- `0.0.0.0:8080` means that the application is listening on all IPv4 network interfaces.
- For example, if a server has:
  - 192.168.1.10
  - 10.0.0.10
  - 127.0.0.1
- The service may accept connections through:
  - 192.168.1.10:8080
  - 10.0.0.10:8080
  - 127.0.0.1:8080
- In contrast, if an application is bound only to `127.0.0.1:8080`
  - it can normally be accessed only from the local machine.

##### LISTENING vs. ESTABLISHED

- LISTENING
  - The server has port 443 open and is waiting for incoming TCP connections.

```
TCP    0.0.0.0:443    0.0.0.0:0    LISTENING
```


- ESTABLISHED
  - The TCP connection between the two endpoints has been successfully established.

```
TCP    192.168.2.48:55560    113.176.13.49:80    ESTABLISHED
```

##### Common Administration Workflow

- Suppose you want to find out which process is using port 443.

```
netstat -aon | findstr :443

tasklist /FI "PID eq 1234"
```

##### For more detailed information

```
netstat -abno
```

| Option | Meaning |
|---|---|
| `-a` | Display all connections and listening ports |
| `-b` | Display the executable involved in creating the connection |
| `-n` | Display addresses and ports numerically |
| `-o` | Display the Process ID (PID) |

### Transmission Control Protocol - TCP

- TCP is connection-oriented and designed to provide reliable data delivery
- Before transmitting application data, TCP establishes a connection using the three-way handshake:
  - **Three-way handshake** — establishes a connection before data transfer.
  - **Acknowledgments (ACK)** — confirms that data has been received.
  - **Checksum** — detects corrupted data.
  - **Sequence numbers** — keep track of transmitted segments.
  - **Retransmission** — lost or corrupted data can be sent again.

#### TCP Three-Way Handshake - to establish a connection

- Step 1 — SYN: The client sends a SYN request to initiate a connection.
- Step 2 — SYN-ACK: The server responds with SYN + ACK, acknowledging the client's request.
- Step 3 — ACK: The client sends an ACK back.
- After these three steps, the connection is established and data can be exchanged.

```
Client                 Server
  │                       │
  │────── SYN ───────────→│
  │                       │
  │←──── SYN + ACK ───────│
  │                       │
  │────── ACK ───────────→│
  │                       │
  │   Connection ready    │
  |   Data Transfer       |
```

#### Four-way termination - to close a connection

- When communication is finished, the client initiates the shutdown by sending a FIN (Finish) packet.
- The four steps are:
  - FIN — The client tells the server that it has finished sending data.
  - ACK — The server acknowledges the client's FIN.
  - FIN — The server sends its own FIN, indicating that it has also finished.
  - ACK — The client acknowledges the server's FIN.
- The session is then closed. The lecture describes this as a four-way ending: **FIN → ACK → FIN → ACK**

```
Client                         Server
  |                              |
  | -------- FIN, ACK ---------->|
  |                              |
  | <----------- ACK ------------|
  |                              |
  | <----------- FIN ------------|
  |                              |
  | ------------ ACK ----------> |
  |                              |
  |       Connection Closed      |
```

- Why Four Steps?
  - The important idea is that each side independently indicates that it has finished.

```
Client: "I'm finished."  → FIN
Server: "I received that." → ACK

Server: "I'm finished too." → FIN
Client: "I received that." → ACK
```

### User Datagram Protocol - UDP

- UDP is connectionless. 
  - It does not establish a connection before sending data and does not use a three-way handshake
  - Therefore, UDP is considered a best-effort protocol.
- However, this makes UDP faster and lightweight, which is useful when speed and real-time delivery are more important than reliability.

```
Client ───────────────→ Server
        UDP data
```

#### Typical UDP Applications

- UDP is commonly used when speed and real-time performance are more important than guaranteed delivery:
  - DNS
  - DHCP
  - VoIP
  - Video streaming
  - Audio streaming
  - Online gaming
  - Other real-time and network-management applications.

- For example
  - If a few VoIP audio packets are lost, retransmitting them later would not be useful because the conversation has already moved forward.

### TCP vs UDP

| Feature          | TCP                    | UDP                                    |
| ---------------- | ---------------------- | -------------------------------------- |
| Layer            | Transport Layer        | Transport Layer                        |
| Connection       | Connection-oriented    | Connectionless                         |
| Handshake        | Yes — 3-way handshake  | No                                     |
| Reliability      | Reliable               | Best effort                            |
| ACK              | Yes                    | No                                     |
| Sequence numbers | Yes                    | No                                     |
| Retransmission   | Yes                    | No                                     |
| Header size      | **20 bytes**           | **8 bytes**                            |
| Speed            | Generally slower       | Generally faster                       |
| Overhead         | Higher                 | Lower                                  |
| Typical use      | Reliable data transfer | Real-time / performance-sensitive data |



# Application - OSI layer 7 - Application - TCP/IP Layer 4

## Network Protocols

### Management Protocols

- Management protocols are network protocols used to monitor, configure, manage, and maintain network devices and services

#### DNS — Domain Name System

- Key idea: DNS translates human-readable names into network addresses.
- Port: 53
- Transport: UDP by default
- Purpose: Resolves domain names → IP addresses.
- Example: **google.com → IP address**
- DNS is important because humans remember domain names more easily than IP addresses.
- Modern websites may have multiple IP addresses, especially when using a CDN (Content Delivery Network).
- DNS can be thought of as the "Internet's phone book."

##### What is DNS?

- DNS (Domain Name System) provides TCP/IP name resolution services.
- Its fundamental purpose is to translate between:
  - Domain/host name → IP address — forward lookup
  - IP address → Domain/host name — reverse lookup
- DNS works with both:
  - IPv4
  - IPv6
- Example

```
# forward lookup
www.google.com → IP address

# reverse lookup
IP address → www.google.com
```

##### Fully Qualified Domain Name 

- A Fully Qualified Domain Name (FQDN) identifies a host within the DNS hierarchy.
- A Fully Qualified Domain Name consists of:
  - Host name
  - Domain name
  - Top-Level Domain (TLD)
- Example

```
www.instructoralton.com
│   │                │
│   │                └── Top-Level Domain (TLD)
│   └─────────────────── Domain Name
└─────────────────────── Host Name
```

##### DNS Hierarchy

- DNS uses a hierarchical system. A simplified hierarchy is:

```
Root
  │
  └── .com # Top-Level Domain
        │
        └── instructoralton.com # Second-Level Domain
              │
              ├── www # Subdomain or host name
              ├── mail
              └── hq
                    │
                    ├── printers # Further subdomain
                    └── fileserver
```

- The major levels are

```
Root
  ↓
Top-Level Domain (TLD)
  ↓
Second-Level Domain
  ↓
Subdomain / Host
  ↓
Further subdomains
```

##### Top-Level Domain (TLD)

- The TLD is the highest visible level of a domain name
- Example

```
xxxxx.com
xxxxx.net
xxxxx.org
xxxxx.edu
xxxxx.mil
```

- A domain owner can register different domain names under different TLDs if they are available

###### Host Names and Subdomains

- After registering a domain such as `instructoralton.com`
- You can create multiple DNS names underneath it
  - `www.instructoralton.com`
  - `mail.instructoralton.com`
  - `hq.instructoralton.com`
- These can point to different servers or services

```
www.instructoralton.com
        ↓
    Web Server

mail.instructoralton.com
        ↓
    Mail Server

hq.instructoralton.com
        ↓
 Headquarters
```

- You can create additional levels:

```
printers.hq.instructoralton.com
fileserver.hq.instructoralton.com
```

##### DNS Resolution Process

- Suppose a client wants to access `technet.microsoft.com`
  - But its local DNS server doesn't already know the answer
- The DNS resolution process can involve:

```
Client
  ↓
Local DNS Resolver
  ↓
Root DNS Server
  ↓
.com DNS Server
  ↓
microsoft.com DNS Server
  ↓
technet.microsoft.com
```

- Step 1: Root DNS server
  - The root server doesn't normally provide the final IP address.
  - Instead, it tells the resolver: "For `.com`, ask the `.com` TLD servers.
  - DNS Doesn't Always Start at the Root
    - If the DNS resolver already knows the answer because of:
      - Cached DNS information
      - Its own DNS records
      - Information obtained previously
    - then it doesn't need to start from the root.
- Step 2: `.com` TLD server
  - It tells the resolver where to find the authoritative DNS servers for: `microsoft.com`
  - A commonly used **public DNS resolver** is Google's: `8.8.8.8`
- Step 3: Authoritative DNS server
  - The authoritative server can provide the DNS record for `technet.microsoft.com`
  - Which may contain the corresponding IP address.

##### DNS Record Types

###### Introduction to DNS Records

- DNS (Domain Name System) records are stored on DNS servers and provide information about domain names, IP addresses, mail servers, and other network services.
- Each DNS record type serves a specific purpose. 
- The most common DNS records are A, AAAA, PTR, CNAME, MX, and NS.

###### Common DNS Record Types


| Record Type | Full Name             | Purpose                                                                   |
| ----------- | --------------------- | ------------------------------------------------------------------------- |
| A           | Address Record        | Maps a domain name to an IPv4 address.                                    |
| AAAA        | IPv6 Address Record   | Maps a domain name to an IPv6 address.                                    |
| PTR         | Pointer Record        | Maps an IP address to a domain name (reverse DNS lookup).                 |
| CNAME       | Canonical Name Record | Creates an alias that points to another domain name.                      |
| MX          | Mail Exchange Record  | Specifies the mail servers responsible for receiving emails for a domain. |
| NS          | Name Server Record    | Identifies the authoritative DNS servers for a domain.                    |

- Examples
  - A record: example.com → 192.0.2.10
  - AAAA record: example.com → 2001:db8::10
  - PTR record: 192.0.2.10 → server.example.com
  - CNAME record: www.example.com → example.com
  - MX record: example.com → mail.example.com
  - NS record: example.com → ns1.example.net

#### DHCP - Dynamic Host Configuration Protocol

- Key idea: DHCP automatically configures a device's network settings.
- Ports: 67 and 68
- Transport: UDP
- Purpose: 
  - Automatically provides network configuration to devices
- DHCP can assign:
  - IP address
  - Subnet mask
  - Default gateway
  - DNS server
- It simplifies network administration and helps prevent IP address conflicts.
- DHCP is commonly used in home, small-business, and enterprise networks.

##### Static IP vs DHCP

- For a network with hundreds of devices, manually managing every IP becomes inconvenient and increases the chance of configuration mistakes or conflicts.

| Method     | How IP is assigned                   | Suitable for                             |
| ---------- | ------------------------------------ | ---------------------------------------- |
| **Static IP** | Administrator manually configures IP | Small networks, servers, special devices |
| **DHCP**   | Server automatically assigns IP      | Medium/large networks, clients           |


##### Basic DHCP Architecture

- The new PC doesn't initially have an IP address, so it communicates on the network to find a DHCP server.
- The DHCP server can then provide an IP configuration.

```
# DORA Process
                 Network
                    │
          ┌─────────┴─────────┐
          │                   │
       [DHCP Server]        [New PC]
          │                   │
          │◄──── Request ─────┤
          │                   │
          ├──── IP Offer ────►│
          │                   │
          │◄──── Request ─────┤
          │                   │
          └──── ACK ─────────►│
```

##### DORA Process

- When a client is configured to obtain its IP address dynamically, it follows the DORA process:
  - **Discover → Offer → Request → Acknowledgement**

- The DHCP address-assignment process is commonly remembered as DORA:

| Step  | Name                 | Basic meaning                             |
| ----- | -------------------- | ----------------------------------------- |
| **D** | Discover             | Client looks for DHCP servers             |
| **O** | Offer                | DHCP server offers an IP configuration    |
| **R** | Request              | Client requests the offered configuration |
| **A** | Acknowledgment (ACK) | Server confirms the assignment            |


##### DHCP Server Configuration

A DHCP server needs to be configured with several important parameters.

###### Address Scope / Address Pool

- The scope defines the range of IP addresses that DHCP can assign to clients.
  - Example: `192.168.0.20 -> 192.168.0.254`
  - Addresses between `.20` and `.254` are available for DHCP leases.
  - Addresses outside this range can be reserved for devices that require static IP addresses, such as servers

###### Other DHCP Options

- A DHCP server can also configure:
  - **Lease time** — how long a client can use an IP address.
  - **Default gateway** — the gateway clients use to reach other networks.
  - **DNS servers** — DNS servers clients should use.
  - **MAC address assignments/reservations** — assigning a specific IP address to a particular device based on its MAC address.
  - **Exclusions** — addresses inside a broader scope that DHCP should not assign.

##### DHCP Relay Agent

- A DHCP server does not necessarily need to exist on every subnet
- A DHCP relay agent forwards DHCP requests and replies between clients and a DHCP server located on a different subnet/network.

```
Subnet A       Subnet B       Subnet C
   |              |              |
   |              |              |
   +------ DHCP Relay Agents ----+
                  |
                  |
            DHCP Server
```

###### Why use a relay agent?

- Instead of deploying

```
Subnet A → DHCP Server
Subnet B → DHCP Server
Subnet C → DHCP Server
```

- You can have

```
Subnet A ─┐
Subnet B ─┼→ DHCP Relay → One DHCP Server
Subnet C ─┘
```

- This simplifies DHCP administration.

##### APIPA - Automatic Private IP Addressing

- APIPA is used when a client is configured for DHCP but cannot reach a DHCP server
- Instead of remaining without an IP address, the system automatically assigns itself an address
  - APIPA range `169.254.0.1 -> 169.254.255.254`
  - 

#### NTP — Network Time Protocol

- Key idea: NTP keeps computers' clocks synchronized
- Port: 123
- Transport: UDP
- Purpose: Synchronizes a system's date and time with a network time server.
- Accurate time is important because many applications, protocols, and authentication systems are time-sensitive.
- Incorrect system time can cause authentication or network-service failures.

#### SNMP — Simple Network Management Protocol

- Key idea: SNMP provides centralized monitoring and management of network devices.
- Port: 161
- Transport: UDP by default
- Purpose: Allows administrators to monitor and manage network devices centrally.
- A management system can collect information such as:
  - CPU usage
  - Memory
  - Bandwidth
  - Performance
  - Device status
  - Errors
- Instead of connecting to each network device individually, administrators can monitor many devices from a centralized management system.

#### LDAP — Lightweight Directory Access Protocol

- Key idea: LDAP provides a standardized way to access and manage directory information.
- Port: 389
- Transport: TCP
- Purpose: Provides access to and querying of directory services.
- Directory information can include:
  - User accounts
  - Computer accounts
  - Printers
  - Usernames and passwords
  - Security groups and roles
- Microsoft Active Directory is described in the lecture as the most popular implementation associated with LDAP.


#### LDAPS

- LDAPS is the secure/encrypted version of LDAP.
  - Port/Transport: 636/TCP
  - LDAPS: LDAP traffic protected using encryption
  - Purpose: Protect LDAP network traffic from being transmitted unencrypted

#### SMB — Server Message Block

- Key idea: SMB enables computers to share files and printers over a network.
- Port: 445
- Transport: TCP
- Purpose: Network and file sharing, especially in Microsoft/Windows environments.
- Used for:
  - File sharing
  - Printer sharing
- For example, when Windows computers share files or printers over a network, SMB is the protocol enabling that functionality.

### Remote Communication Protocols

#### Telnet — Terminal Access

- Port: 23
- Transport: TCP
- Purpose: Connect to a remote host and access its command-line interface (CLI).
- Security: 
  - Insecure — data is transmitted in clear text.
  - Never use Telnet for remote communication across a network when SSH is available.
- Telnet has largely been replaced by SSH.
- Use case
  - Telnet may still be used with older managed network devices, such as routers and switches.
  - The lecture gives an example of connecting directly to a device using a local serial connection to configure it. In this situation, the communication is not going across the network, so the clear-text limitation is less relevant.

#### SSH — Secure Shell

- Port: 22
- Transport: TCP
- Purpose: Securely connect to a remote host through a terminal/command-line interface.
- Security: Encrypted
- Commonly used with:
  - Linux
  - Unix
  - Windows
  - macOS

##### Telnet vs SSH

| Feature      | Telnet                 | SSH                           |
| ------------ | ---------------------- | ----------------------------- |
| Port         | **23**                 | **22**                        |
| Transport    | TCP                    | TCP                           |
| Remote CLI   | ✅                      | ✅                             |
| Encryption   | ❌ Clear text           | ✅ Encrypted                   |
| Modern usage | Legacy                 | Widely used                   |
| Main purpose | Remote terminal access | Secure remote terminal access |

#### RDP — Remote Desktop Protocol

- Port: 3389
- Transport: TCP
- Purpose: Remotely connect to, view, and control a computer's graphical desktop.
- Developed/used primarily in Microsoft/Windows environments.
- RDP is commonly used for:
  - Remote administration
  - Remote support
  - Working on computers without a directly connected monitor
- Unlike SSH and Telnet, which primarily provide a command-line interface, RDP provides a graphical desktop interface.

### File Transfer Protocols

#### FTP — File Transfer Protocol

- FTP is a protocol used to transfer files between systems.
- It is considered a legacy protocol because it sends data, including credentials, in clear text.
- FTP is a full-featured file transfer protocol. It allows users to:
  - Upload files
  - Download files
  - List files and directories
  - Create and delete files
  - Rename files
  - View and modify permissions
  - Navigate directories
  - Authenticate using a username and password

- Transport: TCP
  - FTP uses TCP because it requires reliable, session-oriented communication.
- FTP ports

|   Port | Purpose          |
| -----: | ---------------- |
| **20** | Data transfer    |
| **21** | Commands/control |

#### SFTP — SSH File Transfer Protocol

- SFTP provides essentially the same general purpose as FTP: secure file transfer between systems.
- SFTP is technically not "FTP with encryption." It is a separate file-transfer protocol that operates over SSH.
- The key difference is that SFTP transfers data through SSH, so communication is encrypted.

| Feature      | SFTP                 |
| ------------ | -------------------- |
| Purpose      | Secure file transfer |
| Transport    | TCP                  |
| Default port | **22**               |
| Security     | Encrypted            |
| Technology   | SSH                  |


#### TFTP — Trivial File Transfer Protocol

- TFTP is a very simple and lightweight version of file transfer.
- Its primary purpose is simple file transfer.
- Transport: UDP
- TFTP port:	69
- Unlike FTP/SFTP, it provides very limited functionality.
- It generally does not provide:
  - User authentication
  - Directory navigation
  - File management features
  - Permission management

#### FTP vs SFTP vs TFTP

| Feature              | FTP                         | SFTP                       | TFTP                               |
| -------------------- | --------------------------- | -------------------------- | ---------------------------------- |
| Full name            | File Transfer Protocol      | SSH File Transfer Protocol | Trivial File Transfer Protocol     |
| Purpose              | Full-featured file transfer | Secure file transfer       | Simple file transfer               |
| Default port         | **20/21**                   | **22**                     | **69**                             |
| Transport            | **TCP**                     | **TCP**                    | **UDP**                            |
| Encryption           | ❌                           | ✅                          | ❌                                  |
| Authentication       | ✅                           | ✅                          | ❌                                  |
| Directory navigation | ✅                           | ✅                          | ❌                                  |
| File management      | ✅                           | ✅                          | Very limited                       |
| Typical use          | Legacy file transfer        | Secure file administration | Network devices / simple transfers |

### Email Protocols

#### SMTP — Simple Mail Transfer Protocol

- **Purpose**: Send emails.
- SMTP is used in two main situations:
  - Sending an email from an email client to a mail server.
  - Sending an email between mail servers.

| Protocol | Default Port |   Secure Port | Encryption                    | Transport |
| -------- | -----------: | ------------: | ----------------------------- | --------- |
| SMTP     |       **25** | **465 / 587** | 465: SSL/TLS, 587: STARTTLS | TCP       |

- **Important**:
  - Port 25 is traditionally unencrypted and is mainly used for server-to-server SMTP.
  - Modern email clients typically use:
    - 465 → SMTP over SSL/TLS
    - 587 → SMTP with STARTTLS
  - The email provider determines which port and encryption method should be used.

#### POP3 — Post Office Protocol Version 3

- **Purpose**: Retrieve/download emails from a mail server.

| Protocol | Default Port | Secure Port | Encryption   | Transport |
| -------- | -----------: | ----------: | ------------ | --------- |
| POP3     |      **110** |     **995** | 995: SSL/TLS | TCP       |

- The traditional POP3 behavior is:
  - After downloading, POP3 may delete the emails from the server, depending on configuration.
  - Therefore, POP3 is less convenient when you want to access the same mailbox from multiple devices.

```
Server
 ├── Email A
 ├── Email B
 └── Email C
       │
       │ POP3 download
       ▼
    Laptop

# Emails may be removed from server
```

#### IMAP — Internet Message Access Protocol

- **Purpose**: Access and synchronize emails while keeping them on the server.

| Protocol | Default Port | Secure Port | Encryption                    | Transport |
| -------- | -----------: | ----------: | ----------------------------- | --------- |
| IMAP     |      **143** |     **993** | 143: STARTTLS<br>993: SSL/TLS | TCP       |

- Unlike traditional POP3, IMAP keeps emails on the server.
  - All devices can access the same mailbox and synchronize its state
- This makes it suitable for multiple devices:

```
                 ┌── Desktop
                 │
Mail Server ─────┼── Laptop
                 │
                 └── Phone
```

#### SMTP vs POP3 vs IMAP

| Feature               | SMTP           | POP3               | IMAP                         |
| --------------------- | -------------- | ------------------ | ---------------------------- |
| Main purpose          | **Send** email | **Retrieve** email | **Access/synchronize** email |
| Default port          | 25             | 110                | 143                          |
| Secure port           | 465 / 587      | 995                | 993                          |
| Transport             | TCP            | TCP                | TCP                          |
| Keeps email on server | N/A            | Usually no*        | **Yes**                      |
| Multiple devices      | Not applicable | Limited            | **Excellent**                |
| Modern usage          | **Yes**        | Less common        | **Very common**              |

### Web Browser Application Protocols

#### HTTP - Hypertext Transfer Protocol 

- Uses TCP port 80 by default.
- Data is transmitted in plain text.
- HTTP is therefore vulnerable to network interception.
- An attacker monitoring the network may be able to read the HTTP traffic.
- Example
  - When you visit a website (HTTP request)
  - The server can return resources such as (HTTP response): HTML ,JavaScript ,CSS ,Images ,Other web resources
  - The browser then interprets these resources and renders the webpage for the user.

```
Web Browser
     │
     │ HTTP Request
     ▼
Web Server
     │
     │ HTTP Response
     ▼
Web Browser
```
  
#### HTTPS - HTTP Secure

- HTTPS protects HTTP communication by using TLS (Transport Layer Security)
- Uses TCP port 443 by default.
- Encrypts HTTP traffic.
- Protects sensitive information from being easily read by someone monitoring the network.
- Examples of sensitive information include:
  - Login credentials
  - Banking information
  - Personal information
  - Session cookies
  - Data submitted through forms

##### Why HTTPS Is Important

- HTTP

```
Browser ──── plaintext ────> Server
                 ↑
            Attacker may
            read traffic
```

- HTTPS

```
Browser ──── encrypted ────> Server
                 ↑
            Attacker sees
            encrypted data
```

- HTTPS therefore provides important protection against network eavesdropping.  

##### Internet vs. World Wide Web

- Internet
  - The overall global network infrastructure.
  - Includes many different services and protocols.

```
Internet
├── World Wide Web → HTTP/HTTPS
├── Email → SMTP/IMAP/POP3
├── DNS
├── SSH
├── FTP
└── Other services
```

- World Wide Web (WWW)
  - A service running on the Internet.
  - Primarily uses HTTP/HTTPS to access websites and web resources.