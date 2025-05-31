
***

Self-referential link: https://SecurityReviewed.github.io

Security is 2 things.
1. The CIA triad
2. Risk Management
Confidentiality, Integrity, & Availability and the tradeoff of establishing different levels of each of those pillars.


#### Resources ####
I’ve worked with student workers doing student-university co-ops or job placements and will typically want to give them a set of resources where they can learn on their own. However, until this point, I hadn’t built a single space where it’s easily shareable. Normally the references would be specific to the topic of their co-op position or based on the latest news, so would be inconsistent between students & lack any form of fluidity or over-arching plan.
This is an attempt at fixing that. Ideally there’s some logic and flow, not a mismatch of random things based on the latest buzzwords & news stories.

In no particular order - I might re-order these in the future, but I don’t have any specific criteria right now.

Virtual Reading

https://tldr.tech/infosec
	This is a newsletter with security events, news, & developments. You can also review historical editions of the newsletter by changing the URI to previous issue dates. For example; this is the latest https://tldr.tech/infosec/2024-09-27 email I received, but you can view earlier entries by changing the path to https://tldr.tech/infosec/2024-09-20.

https://reddit.com/r/sysadmin
https://www.reddit.com/r/cybersecurity/
These are bundled together because they serve a lot of the same purpose. In my opinion, having System Administration skills is very valuable to cyber professionals, so understanding the issues they deal with on a regular basis allows us to make better informed recommendations. I’ve also had many instances of the Sysadmin subreddit reporting security-related issues before the security subreddit. Sysadmins are typically on call & share a lot of info, so they’re likely the first to report the outage that might have been caused by a security event.

You’ll often find posts that explain or provide background on security-related items such as email security, setting up SPF, DKIM, & DMARC, password policy & complexity, networking, automation/management of fleets via Ansible, Intune, SCCM, GPO, etc.
	For example, I saw this post about air-gapped environments & patching. Depending on your level of expertise, this might be a good chance to dig into what an air-gapped environment actually is, common misconceptions, and the difficulties that arise from extremely limited network connectivity (or entirely 0 connectivity). https://www.reddit.com/r/sysadmin/comments/1fs4n5k/solutions_for_3rd_party_patching_in_an_airgapped/

https://www.reddit.com/r/cybersecurity/wiki/faq/breaking_in/
	I haven’t read every link in here, but it’s a good place to start. A lot of questions have already been asked & answered, so let’s not reinvent the wheel.

https://krebsonsecurity.com/
	A reporter & journalist (probably selling him short here lol) on a huge amount of cyber security issues. Brian regularly gets interviews from cyber criminals and does a great job highlighting cybercrime.

https://micahflee.com/
	Tech journalist who famously covered the Trump administration's use of TeleMessage Signal and how it was hacked in 20-minutes. https://micahflee.com/how-the-knock-off-signal-app-used-by-trump-officials-got-hacked-in-20-minutes/

https://raidersofthelostarp.tech/
	Security Architect from Cisco who writes blog posts about a bunch of different topics like vulnerability exploitation, technical details on how/why certain attacks are possible, data exfil, etc.

https://www.labs.greynoise.io/grimoire/
	A collection of exploits & accompanying write-ups explaining them. These vary in their level of technical depth, so read these with a bit of trepidation that they can get nitty-gritty and into the technical details.
What is C2 & CVE-2024-4577 PHP RCE - https://www.labs.greynoise.io/grimoire/2024-07-18-c2-101/



Listening
https://darknetdiaries.com/
	I strongly recommend these podcasts as I’ve introduced non-tech people to security through these.

https://risky.biz/
	A podcast covering security topics. The Risky Biz News threads are short, rapid-fire, episodes that don’t dive into a full conversation about topics. So if you want short & sweet, check out the News episodes, otherwise check out the other episodes.

https://www.youtube.com/@Computerphile
	Computerphile cover a huge range of topics, many of which being generic IT concepts like encryption, networking, algorithms, etc. Knowing how these topics works makes for a better security professional. If you want to start learning about a topic, I’d recommend seeing if they have a video on it.
	For example, this video on Network Time Protocol https://www.youtube.com/watch?v=BAo5C2qbLq8. NTP isn’t inherently a security concept, but is heavily relied upon by security.
	https://www.youtube.com/watch?v=UgQM0rVDIQE

https://www.youtube.com/HackerSploit
	HackerSploit covers a ton of different vulnerability exploits, often going into detail on the exact commands to run and the explanations for why they work.

Windows Forensics Investigation | TryHackMe Investigating Windows Part 1 (youtube.com)
	This channel does lots of TryHackMe walkthroughs going through their thought process.

Books
Attacking Network Protocols: A Hacker’s Guide to Capture, Analysis, and Exploitation by James Forshaw.
	This book can be pretty in-the-weeds, so be careful you understand what you’re getting into & what you’re looking to learn before reading this. I still look for good resources covering the cross over between networking and security, and while this book covers some of that, it isn’t entirely what I was looking for.

How to Measure Anything in Cybersecurity Risk by Douglas Hubbard & Richard Seiersen.
	This book is very high-level and covers the “business think” side of security, heavily leaning into risk management, risk assessment, & mitigation. I suggest checking out this interview with one of the authors before looking into the book.
	https://www.youtube.com/watch?v=bYjPmptlc14

https://sebokwiki.org/wiki/SEBoK_Introduction
	This is a huge wiki on taking a unified approach to tackling problems & building systems. Lots to read in here, you could start with the System Security section, but I encourage you to read the introduction and try to understand the larger picture.
	https://sebokwiki.org/wiki/System_Security

Computer Networks: A Systems Approach
	I haven’t read the entirety of this, but it might be a good place to look into specific topics. For example, Chapter 8 dives into specific network security aspecs such as SSH, TLS/SSH, HTTPS, firewalls, wifi security, etc.


Miscellaneous
https://ransomwatch.telemetry.ltd/#/profiles?id=play
	We often hear about how widespread security incidents are, seeing them on the news & such, but we might not fully wrap our heads around how pervasive it is. This feed monitors known threat actors & captures when they post about attacking or claiming responsibility for hacks. You can take most of these findings and Google around to find news stories surrounding these attacks.

https://www.youtube.com/@pcsecuritychannel/
	I haven’t seen a significant amount of this channel’s content, so take the recommendation with a grain of salt, but what I have seen is good, informational content.

Cybersecurity Expert Answers Hacking Questions From Twitter | Tech Support | WIRED (youtube.com)
Wired interview with Malware Unicorn.

Secret Sharing Explained Visually (youtube.com)


### To-do ###
> Create a page w/ links to resources I've read that I want to share or I want to create threads about.
> Reverse proxy
> Forward proxy
> DHCP & it not having any authentication
> DNS, zone transfers, poisoning, fallbacks like LLMNR, DNS also by default not having any authentication.
> Email security - How the protocol by default doesn't have any authentication built-in, so you can send any email from mail.badguy.com as admin@google.com and have it get delivered successfully, despite it not coming from Google's IPs, the display name being whatever you configure, the from email address being whatever you configure, etc.
>> This would include SPF, DKIM, DMARC.
> Active Directory & other directory/LDAP solutions. This could branch into Azure Active Directory/Entra, but that's a HUGE topic...
>> Honestly, I started learning with AD through my time in Service Desk, so maybe we start here...


#### Story about the co-worker who considered becoming a pentester ####
> How the co-worker who was relatively new to the InfoSec world had been recommended to learn pentesting by their "mentor" or "company coach". In my mind, this is a perfect exmaple of someone jumping into infosec without having a strong grasp on the fundamentals. The coach was likely pushing this person into a realm where they would struggle. And honestly, becoming a pentester is going to be a struggle regardless of your background because it's hard. The depths of knowledge you're required to understand are deep and while the information exists, I imagine most pentesters spend a big chunk of their time learning.
> I got off on a tangent there, but pentesting requires a deep understanding of how the system you're attempting to exploit works for you to understand why/how the exploit functions. A web server will have multiple different layers of technology processing a request and knowing their interconnectivity and the implication of that connectivity is incredibly complicated. Most people can use a pentesting tool with a GUI, point it an at IP address (or more realistically a hostname depending on their level of expertise), check the "test all exploits" button, and cross their fingers, but it takes an expert to interpret the fingerprinting, understand how, and more importantly, explain how the service can be exploited, what the implications of said exploit are, and explain the mitigations in a risk-based approach.
> Running your generic web scanner tool and providing a report that the service is running SSLv3 is NOT a particularly valuable output. In that same vein, doing a scan of the organization's perimeter, identifying several endpoints running different web & OS versions, all of which are running different SSL/TLS protocol versions, different cypher suites, etc. then providing recommendations to consolidate the services behind a reverse proxy coupled with a WAF, then industry best practices for cipher suites, the market share of browsers supporting which, etc.
>>    Someone new to infosec, do they know what a cipher suite is? Do they know if we should be using SSLv2, v3, TLS 1.0, 1.1, 1.2, or 1.3? Would they even look for services on non-standard ports? I've seen organizations hosting administrator login portals on 8080 or 8443 and they were exposed to the internet. I will hopefully be able to tie all of these threads back to the same idea. We, as security professionals, or aspiring security professionals, should strive to understand the fundamentals of the technology we work with every day.


# This is an H1 #
## This is an H2 ##
### This is an H3 ######

# Title page
Sample text here w/ an H1 header above it.



### Blockquotes
HTML Tag: `<blockquote>`

Markdown uses email-style **>** characters for blockquoting. It looks best if you hard wrap the text and put a > before every line.

Code:

    > This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
    > consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
    > Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
    > 
    > Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
    > id sem consectetuer libero luctus adipiscing.
Preview:
***
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

***
Markdown allows you to be lazy and only put the > before the first line of a hard-wrapped paragraph.
