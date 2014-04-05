---
layout: post
tags: understand https
---
*Convert pfx*
- openssl pkcs12 -in d:\weixin.pfx -clcerts -nokeys -out d:\weixin.cer
- openssl pkcs12 -in d:\weixin.pfx -nocerts -nodes  -out d:\weixin.key
- openssl pkcs12 -in d:\weixin.pfx -out d:\weixin.crt -nodes -nokeys -cacerts