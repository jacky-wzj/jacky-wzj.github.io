---
layout: post
tags: understand https
---
*Convert pfx*
- openssl pkcs12 -in domain.pfx -clcerts -nokeys -out domain.cer
- openssl pkcs12 -in domain.pfx -nocerts -nodes  -out domain.key
- openssl pkcs12 -in domain.pfx -out domain.crt -nodes -nokeys -cacerts



<h5>未完待续</h5>