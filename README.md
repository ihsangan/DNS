**Cloudflare DNS**
```
1.1.1.1::853::DoT::cloudflare-dns.com
1.0.0.1::853::DoT::cloudflare-dns.com
1.1.1.1::443::DoH::https://cloudflare-dns.com/dns-query
1.0.0.1::443::DoH::https://cloudflare-dns.com/dns-query
```
**Cloudflare Gateway**
```
172.64.36.1::853::DoT:hc4wigztnw.cloudflare-gateway.com
172.64.36.2::853::DoT::hc4wigztnw.cloudflare-gateway.com
172.64.36.1::443::DoH::https://hc4wigztnw.cloudflare-gateway.com/dns-query
172.64.36.2::443::DoH::https://hc4wigztnw.cloudflare-gateway.com/dns-query
```
**Google Public DNS**
```
8.8.8.8::853::DoT::dns.google
8.8.4.4::853::DoT::dns.google
8.8.8.8::443::DoH::https://dns.google/dns-query
8.8.4.4::443::DoH::https://dns.google/dns-query
```
**Quad9**
```
9.9.9.9::853::DoT::dns.quad9.net
149.112.112.112::853::DoT::dns.quad9.net
9.9.9.9::443::DoH::https://dns.quad9.net/dns-query
149.112.112.112::443::DoH::https://dns.quad9.net/dns-query
```
**OpenDNS**
```
208.67.222.222::443::DoH::https://doh.opendns.com/dns-query
208.67.220.220::443::DoH::https://doh.opendns.com/dns-query
```
