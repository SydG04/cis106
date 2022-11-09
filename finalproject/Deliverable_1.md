---
Sydney Gilmore
Class: CIS 106
---

# Deliverable 1

> The tutorial we will follow is this [one](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-22-04)

## Concepts I do not understand

<u>Web server</u>: Computer software and underlying hardware that accepts requests via HTTP or its secure variant HTTPS

<u>Apache</u>: Open source webs server

<u>Firewall</u> - a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a define set of security rules.
    - UFW firewall -> uncomplicated firewall

<u>TLS/SSL</u>: (Transport Layer Security/Secure Sockets Layer) encrpty communication between a client and a server to prevent 

<u>Virtual Hosts</u>: the basic unit that describes a site or a domain; allows one server to host multiple domains or sites with a single interface or ip address by using a mechanism
    - Server blocks -> allows you to run more than one website on a single machine

<u>Unmask value</u>: a four-digit octal number that UNIX uses to determine the file permission for newly created files

<u>Server Configuration</u>: defines a specific database as the repository for its data

<u>Server logs</u>: a text document that contains a record of all activity relate to a specific web server over a defined period of time

## What is a web server? Hardware and software side

<u>Web server (Hardware)</u> - a computer that stores web server software and a website's component files (e.g., HTML Documents, CSS stylesheets, and Javascript files)

<u>Web server (Software)</u> - includes several parts that control how web users access hosted files (i.e., HTTP server)
    - HTTP servers is a software that understands URLS adn HTTP (the protocol)


## What are some different web server applications?

### Apache

The reason Apache is very prominent  it because of its open license, early entry, and easy development of PHP. Other good features of this server are as followed:
    - Available on all platforms
    - The default server (CPanel) makes it easy to set up and change sites.
    - Very functional, there's likely a module that will fit your needs
    - Per-directory configuration through `.htaccess` files
    - Support for HTTP/2, compression, static files, and load balancing
    - MPM and FastCGI modes for delivering high currency
    - Easy scripting through Lua

### NGINX

Some of the features of NGINX are as followed:
    - Asynchronous architecture for handling high loads
    - Best-in-the-class static file handling, load balancing, and reverse proxy capabilities
    - FastCGI caching
    - Access control,error redirection, etc.
    - WebSockets, keepalive adn pipelined connections

### Caddy

A very prominent open-source framework. Some of the its well-know features are:
    - HTTPS enabled by default
    - HTTP/2 gets primary focus
    - Embeddable -- can be used as a library in other programs
    - Serves static files in the current directory by default

### Lighthttpd

Lighthttpd was designed to work in low-memory and low-CPU environments. This was built on the asynchronous request handling model, so it's very similar to NGINX. However, it works in a single thread. 

### MonkeyServer

MonkeyServer is known for supporting embedded platforms. Some of its other features are:
    - Supported on Linux and MacOS
    - Full-support for ARM-based processors
    - Minimal runtime (100 KB without plugins)
    - Supports IPv6 and TLS
    - Works with CGI and FastCGI
    - Basic authentication, security rules, etc.

### OpenLiteSpeed
Some of it's features include:
    - Compatible with Apache's `mod_rewrite`, which means migrating existing Apaches files will be easy
    - GUI-based admin interface
    - Higher performance
    - Caching and Google PageSpeedInsights optimizations are applied by default

### Cherokee
It provides an easy, fun and performant alternative to the mainstream web servers at the cost of not having an cutting-edge features like the other web servers. 

## What is virtualization?

<u>Virtualization</u> - the process of running a virtual instance of a computer system in a layer abstracted from the actually hardware. In simpler terms, running multiple operating systems on a computer system simultaneously.

## What is virtualbox?

<u>Virtualbox</u> - software that is provided by Oracle to instal virtual machines onto your system

## What is a virtual machine?

<u>Virtual machine</u> - the emulated equivalent of a computer system runs on top of another system.

## What is Ubuntu Server?

Ubuntu Server is apart a large set of Ubuntu tools and operating system. It gives the user the ability to assign "super user" tasks to make it easier to administer the network. 

It's compatible with many different platforms like Microsoft, Hyper-V, and VMware ESX.

## What is a firewall?

<u>Firewall</u> - a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a define set of security rules.

## What is SSH?

SSH (Secure Shell or Secure Socket Shell) a network protocol that gives users a secure way to access a computer over an unsecured network. It provides strong password authentication and public key authentication, as well as encrypted data communications between two computers connecting over an open network. 

This is used to connect to servers, make changes, perform uploads and exits, either using tools or directly through the terminal. 
