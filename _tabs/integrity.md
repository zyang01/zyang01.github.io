---
icon: fas fa-scale-balanced
order: 1
---

We live in a time where people can [come up with all sorts of excuses](../posts/on-theological-nuke/){:target="_blank"} to doubt no matter how far you go about proving that you have been telling the truth, the whole truth and nothing but the truth. Some will go as far as [solipsism and deny reality is real](../posts/on-theological-nuclear-fallout/){:target="_blank"} by not taking a leap of faith most of us [already make daily without knowing](../posts/on-faith-precedes-reason/){:target="_blank"}. To prevent potential accusations of the integrity of my posts, this tab will be used to document the paper trail using a mixture of technologies including but not limited to hash functions, git, blockchains, [OpenTimestamps](https://opentimestamps.org/){:target="_blank"} and IPFS.

This blog is statically generated using [Jekyll](https://jekyllrb.com/){:target="_blank"}. The [source](https://github.com/zyang01/zyang01.github.io){:target="_blank"} and [build](https://github.com/zyang01/HeSaid.Love){:target="_blank"} repositories are on [my GitHub](https://github.com/zyang01){:target="_blank"}. Feel free to check the commit hashes. The commit signatures include [OpenTimestamps](https://opentimestamps.org/){:target="_blank"}.

The Web2 site is accessible via the domain name HeSaid(dot)Love and hosted on Cloudflare Workers & Pages with CI/CD. I wrote about my concerns on Cloudflare in a post, and I'm not repeating them here. You can find the IPFS deployment details below. Feel free to regularly resolve and pin the DNSLinks.

As you can tell, it's not great to have too wild an imagination, and I won't be able to accurately convey what it's like to have that wild an imagination and know that God exists. You might be able to find out though if you are willing to join us.

### IPFS Deployment

DNSLink records are set up for hesaid.love and dl.hesaid.love. You can find the CIDs by looking up the DNS TXT records.

```bash
ubuntu@ipfs:~$ dig +noall +answer TXT _dnslink.hesaid.love
_dnslink.hesaid.love. 262 IN TXT "dnslink=/ipns/k51qzi5uqu5di56nvk7d2w3qmubmb3pqon5tsmxywfwt4kxhfdxtncy65w5daf"

ubuntu@ipfs:~$ ipfs name resolve /ipns/hesaid.love
/ipfs/bafybeiaauoqv37yuguduvo6xuodtnjlephglbiqvos6ouslm7nywe7smby

ubuntu@ipfs:~$ dig +noall +answer TXT _dnslink.dl.hesaid.love
_dnslink.dl.hesaid.love. 267 IN TXT "dnslink=/ipns/k51qzi5uqu5dki6xp2kc8ah1x8zu1aibeluphf4v9m4gs4lw1mruox2mv79eya"

ubuntu@ipfs:~$ ipfs name resolve /ipns/dl.hesaid.love
/ipfs/bafybeig4ukhy4m64xta5ib6vmkcfloplnpo7kas34qgtqurq7ni5vhfiom
```

### Incomplete List of In-use Domain Names

- hesaid.love
- heisback.fyi
- antichrist.boo

![](/V3MuD1Z69pJm8VACHV.png)
