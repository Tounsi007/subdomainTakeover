# Subdomain Takeover

# Description
List of services where `Subdomain Takeover` is posible based on my experience.

# Disclaimer :warning:
**The author of this document take no responsibility for correctness. This project is merely here to help guide security researchers towards determining whether something is vulnerable or not, but does not guarantee accuracy.**

# What is a subdomain takeover?
>Subdomain takeover vulnerabilities occur when a subdomain is pointing to a service (e.g. GitHub pages, Heroku, etc.) that has been removed or deleted. This allows an attacker to set up a page on the service that was being used and point their page to that subdomain. For example, if subdomain.example.com was pointing to a GitHub page and the user decided to delete their GitHub page, an attacker can now create a GitHub page, add a CNAME file containing subdomain.example.com, and claim subdomain.example.com.
In Google you have more information.

# List

| Service | Error Page | Discussion | How to  takeover ? |
| ---------- | ---------- | ---------- | ---------- |
| Frontify   | `404 - Page not found. Oops... look like you got lost.`   |Campo B0   |Campo B0   |
               
