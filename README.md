# This is an H1 #
## This is an H2 ##
### This is an H3 ######
***

### To-do ###
Create a page w/ links to resources I've read that I want to share or I want to create threads about.
Reverse proxy
Forward proxy
DHCP & it not having any authentication
DNS, zone transfers, poisoning, fallbacks like LLMNR, DNS also by default not having any authentication.
Email security - How the protocol by default doesn't have any authentication built-in, so you can send any email from mail.badguy.com as admin@google.com and have it get delivered successfully, despite it not coming from Google's IPs, the display name being whatever you configure, the from email address being whatever you configure, etc.
    This would include SPF, DKIM, DMARC.
Active Directory & other directory/LDAP solutions. This could branch into Azure Active Directory/Entra, but that's a HUGE topic...
    Honestly, I started learning with AD through my time in Service Desk, so maybe we start here...


#### Story about the co-worker who considered becoming a pentester ####
How the co-worker who was relatively new to the InfoSec world had been recommended to learn pentesting by their "mentor" or "company coach". In my mind, this is a perfect exmaple of someone jumping into infosec without having a strong grasp on the fundamentals. The coach was likely pushing this person into a realm where they would struggle. And honestly, becoming a pentester is going to be a struggle regardless of your background because it's hard. The depths of knowledge you're required to understand are deep and while the information exists, I imagine most pentesters spend a big chunk of their time learning.
I got off on a tangent there, but pentesting requires a deep understanding of how the system you're attempting to exploit works for you to understand why/how the exploit functions. A web server will have multiple different layers of technology processing a request and knowing their interconnectivity and the implication of that connectivity is incredibly complicated. Most people can use a pentesting tool with a GUI, point it an at IP address (or more realistically a hostname depending on their level of expertise), check the "test all exploits" button, and cross their fingers, but it takes an expert to interpret the fingerprinting, understand how, and more importantly, explain how the service can be exploited, what the implications of said exploit are, and explain the mitigations in a risk-based approach.
Running your generic web scanner tool and providing a report that the service is running SSLv3 is NOT a particularly valuable output. In that same vein, doing a scan of the organization's perimeter, identifying several endpoints running different web & OS versions, all of which are running different SSL/TLS protocol versions, different cypher suites, etc. then providing recommendations to consolidate the services behind a reverse proxy coupled with a WAF, then industry best practices for cipher suites, the market share of browsers supporting which, etc.
    Someone new to infosec, do they know what a cipher suite is? Do they know if we should be using SSLv2, v3, TLS 1.0, 1.1, 1.2, or 1.3? Would they even look for services on non-standard ports? I've seen organizations hosting administrator login portals on 8080 or 8443 and they were exposed to the internet. I will hopefully be able to tie all of these threads back to the same idea. We, as security professionals, or aspiring security professionals, should strive to understand the fundamentals of the technology we work with every day.

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
