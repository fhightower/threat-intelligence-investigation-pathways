# IP Addresses

IP addresses, like `127.0.0.1` and `192.168.0.1` are critical to forming threat data into threat intelligence. IP addresses show up in many different contexts and are used in many different ways. Sometimes, IP addresses themselves are used as callbacks for malicious files or to serve a phishing page. Often an IP address will be hosting one or more hosts, some or all of which may be used maliciously.

Given an IP address, here are a couple of things you can do get some more information:

- Look at the DNS Resolutions for that address. Doing this will identify all of the [hosts](hosts.md) that have resolved/are resolving to said IP address.
- You may want to look into the [ASN](asns.md) and organization running the network that the IP address is a part of. You will find that some ASNs are more likely to have malicious content on them than others and still other ASNs are use for [bulletproof hosting](https://en.wikipedia.org/wiki/Bulletproof_hosting).
- Some IP addresses are used as URLs (like `http://192.168.0.1/test/firstbank.php`). In this case, you can investigate it as both an IP address and a [URL](urls.md).
