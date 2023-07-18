![BLOG_IMAGE_1](https://github.com/kleeloy/Azure-Cloud-Web-Application-/blob/main/Diagrams/github.png)
# Creating A Web Application Using Azure 
The files for this repository were used to create a blog web application and securing with a SCL certification

## Your Web Application 
URL for the web application that was created https://kenyettassecurityblog.azurewebsites.net/

![BLOG_IMAGE_1](https://github.com/kleeloy/Project-1/blob/main/Diagrams/Project%20part%201.png)

![BLOG_IMAGE_2](https://github.com/kleeloy/Project-1/blob/main/Diagrams/Project%201%20blog%20post%202.png)

![BLOG_IMAGE_3](https://github.com/kleeloy/Project-1/blob/main/Diagrams/Project%201%20blog%20post%202.png)


## NetWorking QUestions 

#### What is the IP address of this webpage?
20.90.134.16

#### What is the location (city, state, country) of this IP address?
Londan, England

## Web Devolpment Questions

#### When creating your web app, you selected a runtime stack.  What was it? Does it work on the front end or the back end? 
PHP 7.4, Back end

## Cloud Questions

#### What is a cloud tenant?
For Saas cloud offering,the tenant is the regional location that houses the servers providing cloud services.

#### Why would an access policy be important on a key vault?
The key vault access policy determines whether a given security principal, application or user group, can perform different operations on Key Vault secrets, keys, and certificates.

#### Within the key vault, what are the differences between keys, secrets, and certificates?
Keys are cryptographic keys that can be generated using various algorithms. Certificates are keys with optional policies such as auto rotation. Think of secrets as passwords and connection strings.


## Cryptography Questions

#### What are the advantages of a self-signed certificate?
They are fast and easy to issue, Developers aren’t dependent on others for certificate issuance, They are useful in test environments.

#### What are the disadvantages of a self-signed certificate?
They are not vetted via a trusted process, Security teams lack visibility and control over certificates and trusted stores.

#### What is a wildcard certificate?
SSl/TLS certificate which includes a wildcard character to allow it to be used to protect a number of subdomains of a domain.

#### When binding a certificate to your website, Azure only provides TLS versions 1.0, 1.1, and 1.2.  Explain why SSL 3.0 isn’t provided.
In a response to a nation-wide vulnerability.

#### What is the validity of your certificate (date range)?
Monday, March 14, 2022 at 12:39:55 PM
Expires On
Thursday, March 9, 2023 at 11:39:55 AM

#### Do you have a root certificate? If so, what is it?
Yes, Microsoft Azure TLS Issuing CA 01

#### List one other root CA in your browser’s root store.
GTS CA 1C3


## Cloud Security Questions 

#### What are the similarities and differences between Azure Web Application Gateway and Azure Front Door?
Azure Front Door WAF and Azure App Gateway WAF are very similar in functionality, one main difference is where the WAF is applied. Azure front Door applies the WAF filters at the edge location, while app gateway applies the filter when it enters your VNET.

#### A feature of the Web Application Gateway and Front Door is “SSL Offloading.” What is SSL offloading? What are its benefits?
SSL offloading is the process of removing the SSL based encryption from incoming traffic that a web server receives to relieve it from decryption of data. It offloads additional tasks from your application servers so they can focus on their primary functions. It saves resources on those application servers.

#### What OSI layer does a WAF work on?
7th layer

#### Select one of the WAF managed rules (e.g., directory traversal, SQL injection, etc.), and define it.
SQL injection is a computer attack in which malicious code is embedded in a poorly-designed application and then passed to the backend database.

#### Consider the rule that you selected. Could your website (as it is currently designed) be impacted by this vulnerability if Front Door wasn’t enabled? Why or why not?
Yes because the attacker is able to influence the queries sent by a website to a database. This will enable the attacker to extract information from the database or change the contents of the database through, something like, a simple query.

# What Is Included With My Website 
## Azure Front Door enabled
![BLOG_IMAGE_3](https://github.com/kleeloy/Project-1/blob/main/Diagrams/Project%20day%203%20part%201.png)
![BLOG_IMAGE_4](https://github.com/kleeloy/Project-1/blob/main/Diagrams/Project%20day%203%20part%202.png)



