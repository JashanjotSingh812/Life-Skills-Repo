# Content Delivery Networks (CDN)

## Introduction
A content delivery network (CDN) is a geographically distributed group of servers that caches content close to end users. A CDN allows for the quick transfer of assets needed for loading Internet content, including HTML pages, JavaScript files, stylesheets, images, and videos.

## How Content Delivery Networks Work
When a user opens a website, the request does not always go to the main server. The CDN looks at the user’s location and sends the request to the nearest edge server. If the required content is already stored there, it is sent right away. If not, the edge server fetches the data from the origin server, saves it, and then sends it to the user. This process reduces delay and saves bandwidth.

Main parts of a CDN include:
* Origin server where the original data is stored
* Edge servers that keep cached copies of content
* DNS routing to send users to the nearest server

## Advantages of Content Delivery Networks
Using a CDN offers several benefits:
* Helps web pages load faster
* Reduces delay for users in different locations
* Helps in decreasing traffic on the main server
* Improves performance during high traffic
* Offers protection from Distributed Denial of Service attacks
* Safeguards data from hackers

## Data Security - How Does a CDN Protect Data?
Information security is integral to a CDN. A CDN can keep a site secured with fresh TLS/SSL certificates, which will ensure a high standard of authentication, encryption, and integrity. Investigate the security concerns surrounding CDNs, and explore what can be done to securely deliver content.
## Use Cases of CDN
CDNs have many real-world applications:
* Video streaming and entertainment websites
* E-commerce websites with global users
* Online gaming platforms that need low latency
* Cloud-based applications and online services

## Conclusion
Content Delivery Networks are a crucial part of today’s internet. By spreading content across multiple servers in different locations, CDNs make websites faster, more reliable, and more secure. They help manage heavy traffic and ensure users receive content quickly, no matter where they are.

## References
* https://www.cloudflare.com/learning/cdn/what-is-a-cdn/
* https://developer.mozilla.org/en-US/docs/Glossary/CDN
