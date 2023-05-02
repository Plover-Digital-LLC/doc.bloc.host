---

title: bloc.host Docs

enableToc: false

---
## INTRO

To begin thank you for checking out [bloc.host](https://bloc.host). While we support, directly hosting your domain, we reccomend using a subdomain - such as www or docs - to provide the best service new and into the future. When you add your site, a custom CNAME entry will be generated and we setup a pernament redirect from your base domain. Using this allows us to "move" where your site is located for better performance and flexibility, without needed you to constantly change the IP in your DNS service provider. Even if using the prefered CNAME option, you can choose to still point your domain to us through A and AAAA records. Since we have a redirect setup, going forward, users should be pointed to the more optimized CNAME location. For those interested in just using your domain without any subdomains, that option still works. More information on setup is below.

---

### DNS RECORDS

- A - 216.66.77.162
- AAAA - 2001:470:bf:2::1
- CNAME - [generated per site].bloc.host

---

### SETUP STEPS
- [Sign up](https://bloc.host/cockpit) , You will recieve a verification email
- After verifying your email, you should check out the [cockpit](https://bloc.host/cockpit). This is where you can find all of your sites and current billing.
- Add your first site to bloc.host from the cockpit. You will need your password, the sites domain, and a public git repository url (we are working on private repositories through deploy keys). Once created you should recieve an email with some extra goodies. You will get your dashboard URL, pull webhook, and if a domain with subdomain is provided you will have a generated CNAME. If you havent already, now would be a good time to setup your DNS:
	- For those using subdomains:
		- [Namecheap](https://www.namecheap.com/support/knowledgebase/article.aspx/9646/2237/how-to-create-a-cname-record-for-your-domain/)
		- [GoDaddy](https://www.godaddy.com/help/add-a-cname-record-19236)
		- [Hover](https://help.hover.com/hc/en-us/articles/217282457-Managing-DNS-records-#h_5eab4aa7-b044-4cc6-a3c0-5869f583edc8)
		- [DigitalOcean](https://docs.digitalocean.com/glossary/cname-record/)
	- For those using a base domain:
		- [Namecheap](https://www.namecheap.com/support/knowledgebase/article.aspx/319/2237/how-can-i-set-up-an-a-address-record-for-my-domain/)
		- [GoDaddy](https://www.godaddy.com/help/add-an-a-record-19238)
		- [Hover](https://help.hover.com/hc/en-us/articles/217282457-Managing-DNS-records-#h_80fc6798-a59e-4739-bbdd-1e8bdd452df0)
		- [DigitalOcean](https://docs.digitalocean.com/products/networking/dns/how-to/manage-records/)
- Once you have a site registered, a credit card is needed on file. This can be added right on your [cockpit](https://bloc.host/cockpit) towards the bottom. You will be charged right away for $1 for your first site. Each site from there will be an additional $1/m starting on the next pay period. If you have over 10 sites with us, you will only be charged $10/m - this is the max monthly amount we charge. Anything after 10 sites is free!
- Now that you have a site setup, and started your subscriptions, your site should be live. If it is not live immediately, try reloading your site from either the site dashboard or your cockpit. If that doesn't work try using the "Pull" and then the "Reload" option on your sites dashboard. 

If you are having any issues or need further assistance with your setup, please contact us at [machines@plover.io](mailto:machines@plover.io) or join our [discord](https://discord.gg/PSYSqyBsNF)

---

## Build Containers

We currently offer a limited range of build containers for static sites. The list includes the following:
- Hugo
	- Quartz
- Jekyll
- Astro
- Docusaurus

Unlimited build time is included with your subscription. Just pick which build container you perfer right on your sites dashboard. In conjunction with our pull webhook, you can have your site updated and built in just seconds from hitting push. 