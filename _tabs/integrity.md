---
icon: fas fa-scale-balanced
order: 1
---

We live in a time where people can [come up with all sorts of excuses](../posts/on-theological-nuke/){:target="_blank"} to doubt no matter how far you go about proving that you have been telling the truth, the whole truth and nothing but the truth. Some will go as far as [solipsism and deny reality is real](../posts/on-theological-nuclear-fallout/){:target="_blank"} by not taking a leap of faith most of us [already make daily without knowing](../posts/on-faith-precedes-reason/){:target="_blank"}. To prevent potential accusations of the integrity of my posts, this tab will be used to document the paper trail using a mixture of technologies including but not limited to hash functions, git, blockchains, [OpenTimestamps](https://opentimestamps.org/){:target="_blank"} and IPFS.

This blog is statically generated using [Jekyll](https://jekyllrb.com/){:target="_blank"}. You can find [source repo](https://github.com/zyang01/zyang01.github.io){:target="_blank"} and [build repo](https://github.com/zyang01/HeSaid.Love){:target="_blank"} on [my GitHub](https://github.com/zyang01){:target="_blank"}. Feel free to keep an eye on the commit hashes, which include [OpenTimestamps](https://opentimestamps.org/){:target="_blank"}.

The Web 2.0 version of the site is accessible via the domain name HeSaid(dot)Love and hosted on Cloudflare Workers & Pages. I wrote about my concerns on Cloudflare in a post, and I'm not repeating them here. You can find the IPFS deployment details below.

Media files are currently hosted on Cloudflare R2. Will work on finding a low-cost solution as well, but with low priority since what I wrote is more important than memes and my nakedness.

As you can tell, it's not great to have too wild an imagination, and I won't be able to accurately convey what it's like to have that wild an imagination and know that God exists. You might be able to find out though if you are willing to join us.

### IPFS Deployment

A DNSLink gateway is set up on ipfs.hesaid.love using Cloudflare Web3. You can find the CID by looking up the DNS TXT record of _dnslink.ipfs.hesaid.love.

```bash
$ dig -t txt _dnslink.ipfs.hesaid.love

; <<>> DiG 9.18.30-0ubuntu0.24.04.2-Ubuntu <<>> -t txt _dnslink.ipfs.hesaid.love
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 13130
;; flags: qr rd ra; QUERY: 1, ANSWER: 1, AUTHORITY: 0, ADDITIONAL: 1

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 65494
;; QUESTION SECTION:
;_dnslink.ipfs.hesaid.love. IN TXT

;; ANSWER SECTION:
_dnslink.ipfs.hesaid.love. 300 IN TXT "dnslink=/ipfs/bafybeiewyfuixzxjwnvqpj5cbc3a3amz4rzlxu3mk26wrt365hhtdeydci"

;; Query time: 19 msec
;; SERVER: 127.0.0.53#53(127.0.0.53) (UDP)
;; WHEN: Tue Feb 25 00:45:34 GMT 2025
;; MSG SIZE  rcvd: 140
```

### Incomplete List of In-use Domain Names

- hesaid.love
- heisback.fyi
- antichrist.boo

![](/V3MuD1Z69pJm8VACHV.png)
