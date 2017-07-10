# Hosts

Hosts, like `example.org` or `test.example.org`, are one of the more central types of threat data primarily because they are so prevalent. To highlight a few uses for hosts, they can be used as a callback for a malicious file, a phishing page to steal credentials, or a neutral site from which a malicious file gets information (like the current date/time, its current IP address, etc.).

So let's get practical. Assume that you have a malicious host name. Each of the points below offer some things you can do to develop more context around that host:

- Look at DNS Resolutions ([IP Addresses](ip-addresses.md) to which the host has resolved) over time
- Look at the whois information. This gives details about the information used to register the domain.
    - From some of the contact information, assuming the domain does not have some form of privacy guard anonymizing the registrant information, we can often find the name, [physical address](physical-addresses.md), [phone number](phone-numbers.md), and [email address](email-addresses.md) used to register the host.
