Network and Server Security Essentials
==============================

## Presenter Preparation

- Put outline/instructions on website

## Audience Preparation

- Computer
- Access to a Linux machine, VM or VPS

## Schedule

### The Basics

- ssh setup and usage
    + `apt install openssh`
- Install web server
    + `apt install apache2`
- Server files
    + `/var/logs`
    + `/etc`
    + `/var/www`
- Website basics
    + Edit website and view in browser
    + Maybe basic html/css
- Config basics
    + Changing ports
    + webserver
        * web root
        * www. or not
        * indexing?

### Security

- Concepts and best practices
    + Security through obscurity
    + Encrypting or not, HTTPS everything
- Let's Encrypt?
    + Might not get to **Advanced** section, so possibly cover it here
- Open ports
    + `netstat -tulpn`
- ssh
    + ciphers
    + VisualHostkey
    + root login
- Using ssh keys
    + Asymmetric crypto basics: pub/priv key
    + `ssh-keygen`
    + `ssh-copy-id`
        * wrapper for `scp` and `echo >>`
- ssh proxy
    + `ssh -D`
    + `firefox whatismyipaddress.com` and `tcpdump`
    + Limitations
- Fail2ban
    + iptables and log examples
- openvpn?

### Advanced

- Concept of dns
    + `dig`
- Domain name and configuration
    + A, AAAA, CNAME
- Let's Encrypt
    + SSL v3.0
- https and www redirect
