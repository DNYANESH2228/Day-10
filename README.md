# Day-10
Firewall Basics

## Objective

The objective of this task was to understand how a firewall works and learn how to check firewall status and create a basic firewall rule.

## Firewall Rule Created

I created a firewall rule to allow network traffic on port 22 using the command:

sudo ufw allow 22

This rule allows SSH connections to the system.

## Difference Before vs After Enabling Firewall

Before enabling the firewall:

* The firewall status was inactive.
* No firewall rules were applied to control network traffic.

After enabling the firewall:

* The firewall became active.
* It started controlling incoming and outgoing network connections.
* The rule allowing port 22 was added and visible in the firewall status.

## Why Firewall Alone Is Not Enough

A firewall helps control network traffic, but it cannot provide complete security.
Systems also need regular software updates, strong passwords, antivirus protection, and monitoring to stay secure.

## One New Concept Learned

I learned how to check firewall status, enable the firewall, and create a rule using UFW in Kali Linux to control network access.
