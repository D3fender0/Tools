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

## Finding a Subdomain
* Subdomain finding is an essential task in cybersecurity, especially during reconnaissance and vulnerability assessment. It involves identifying subdomains associated with a target domain to gain a broader attack surface for analysis. Here are some key techniques and tools used for subdomain enumeration:
## Sublist3r
* Sublist3r is a Python-based tool used to enumerate subdomains of a target domain. It gathers subdomains using search engines and APIs, such as Google, Bing, Baidu, Yahoo, and VirusTotal.
**Installation**
  1. Clone the Repository:
     ```
     git clone https://github.com/aboul3la/Sublist3r.git
     cd Sublist3r
     ```
  2. Install Requirements:
     ```
     pip install -r requirements.txt
     ```
  3. Run the Tool: Ensure Python is installed, preferably Python 2.7 or 3.x.
**Example**
```
python sublist3r.py -d example.com
```
