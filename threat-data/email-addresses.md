# Email Addresses

An email address, like `badguy@example.org`, is an interesting type of threat data because an email address allows communication between multiple parties and is often used as an identifier/username for websites. This means that email addresses can be used to deliver a malicious file, register a domain, or communicate between bad guys who are working together, just to name a few possible uses.

For some practical techniques, let's assume you have a malicious email address (`badguy@example.org`) that you would like to investigate. You can:

- Search for the email address itself to see if it is listed anywhere else (on any social media accounts, webpages, etc.).
- Search for the 'username' of the email address. For example, if we are investigating `badguy@example.org`, we might try searching for "badguy" just to see if anything comes up related to that username/alias.
- If the domain name of the email address (e.g. `example.org` in `badguy@example.org`) looks suspicious, try investigating it as a [host](hosts.md).
