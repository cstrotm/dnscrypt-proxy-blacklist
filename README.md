# dnscrypt-blacklist
Blacklists for <A HREF="https://github.com/jedisct1/dnscrypt-proxy">DNSCrypt-Proxy</A>, created from my <A HREF="https://github.com/cbuijs/dns-firewall">DNS-Firewall</A> repository to block ads, trackers, nasties, etc.
<BR><BR>
<STRONG>Disclaimer:</STRONG> Use at own risk! No gurantees (but should work pretty well out of the box).
<BR><BR>
Add following line to <A HREF="https://github.com/jedisct1/dnscrypt-proxy/blob/master/dnscrypt-proxy.conf">dnscrypt-proxy.confi</A>:
<BR><BR>
<code>BlackList domains:"/path/to/blacklist.txt" ips:"/path/to/blacklist-ip.txt" logfile:"/path/to/dnscrypt-blacklist.log"</code>
