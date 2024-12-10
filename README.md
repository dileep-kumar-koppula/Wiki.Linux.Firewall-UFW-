# Setting Up UFW Firewall Rules for TCP Ports

The Uncomplicated Firewall (UFW) is a user-friendly way to manage firewall rules on Ubuntu and other Linux distributions. By default, UFW denies all incoming connections and allows all outgoing connections. You might need to allow specific ports for applications or services that you plan to run on your server.

## Allowing TCP Ports

In this guide, we'll allow two specific TCP ports: 8880 and 8443. These ports are often used for various web applications, APIs, and secure communications.

### Commands

To allow traffic through these ports, you can run the following commands in your terminal:

```bash
sudo ufw allow 8880/tcp
sudo ufw allow 8443/tcp
sudo ufw reload
```
