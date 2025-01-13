# Reconnaissance
## Information gathering Tool
### whois 

* The whois command is a utility used to query information about a domain name, IP address, or an autonomous system number (ASN) from a public WHOIS database.
* It retrieves details such as the domain's registration, expiration date, registrar, and contact information.
```
whois [domain-name or IP-address]
```
* [ViewDNS.info - Online](https://viewdns.info/whois/?domain) : Offers WHOIS along with other DNS and IP-related lookups.

### dig
* The dig (Domain Information Groper) command is a powerful tool for querying DNS (Domain Name System) servers. It helps retrieve information about domain names, IP addresses, and other DNS records.
```
dig [@server] name [type] [options]
```
* @server: (Optional) The DNS server to query. Defaults to the system's resolver if omitted.
* name: The domain name to query.
* type: (Optional) The type of DNS record to query (e.g., A, MX, NS, TXT). Defaults to A if omitted.
* options: (Optional) Additional flags to customize the query.

Refer : [Dig Command](https://linux.die.net/man/1/dig)
