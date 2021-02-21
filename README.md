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