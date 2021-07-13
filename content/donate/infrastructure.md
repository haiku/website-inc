# Infrastructure provided by Haiku, Inc.
As an open-source project, Haiku®'s visibility and presence on the internet is vital to its existence, growth, and reputation. Ensuring high quality services to the Haiku Project is the most essential item for receiving funds.

Some weeks before the release of Haiku R1/Alpha 1, a commitment was made to overhaul the infrastructure that provides key services to the Project. Leading up to this, there had been numerous service issues with the previous shared hosting plan and free source code repository. These issues ranged from unexplainable slowdowns to even occasional downtime. In a few words, the needs of the Project were outgrowing its shoes and an upgrade was desired.

## Hosting
### Dedicated Server
Through discussions on the [haiku-development mailing list](https://www.freelists.org/list/haiku-development "haiku-development mailing list"), it was decided to acquire an [EX4 dedicated server](https://web.archive.org/web/20161128085411/http://www.hetzner.de/en/hosting/produkte_rootserver/ex4/ "EX4 dedicated server") with Hetzner. This increased the hosting costs from roughly $300/year to $900/year. Later it was decided to move the hosting to a web hosting provider, so the dedicated server is no longer in use.

For historical reference, these were the specifications of the dedicated server:
- Intel® Core™ i7-2600 Quadcore incl. Hyper-Threading Technology
- RAM 16 GB DDR3 RAM
- Hard discs 2 x 3 GB SATA 6Gb/s HDD (Software-RAID 1)
- NIC 1 GBit OnBoard (connected at 100 MBit)
- Backup Space 100 GB
- Traffic Unlimited (>10,000 GB/month will reduce bandwidth to 10 MBit/s)

### Web Hosting Services
Currently, [Netlify's paid hosting services](https://www.netlify.com/) are used. Haiku makes use of the ["Pro" plan](https://www.netlify.com/pricing/), but we have submitted an [open-source application](https://www.netlify.com/legal/open-source-policy) as we are eligible for complimentary hosting from Netlify. 

## Domain names
These are the domains, which are paid by Haiku, Inc.

- haiku-os.org
- haiku-os.com
- haiku-os.net
- haiku-project.com
- haiku-inc.org
- haiku-files.org
- haikuports.org

## Project sites
These are the websites that are actively maintained by the Project.

- [www.haiku-os.org](https://www.haiku-os.org "www.haiku-os.org"): Main Project Website, powered by Hugo
- [dev.haiku-os.org](https://dev.haiku-os.org "dev.haiku-os.org"): Development tracker, powered by Trac
- [https://i18n.haiku-os.org/](https://i18n.haiku-os.org/ "https://i18n.haiku-os.org/"): Haiku translation site, powered by Pootle and the Haiku User Guide Translator
- [https://build.haiku-os.org/](https://build.haiku-os.org/ "https://build.haiku-os.org/"): Haiku build status site, powered by Concourse (for Haiku builds) and Buildmaster (for HaikuPorts)
- [https://review.haiku-os.org/](https://review.haiku-os.org "https://review.haiku-os.org/"): Haiku code review site, powered by Gerrit
- **Source code repositories:**
	- [cgit.haiku-os.org](https://cgit.haiku-os.org "cgit.haiku-os.org"): Main source code repository. A mirror exists at [GitHub](https://github.com/haiku/ "GitHub") and there used to be one at Gitorious (the service has been shutdown), though the mirror is considered read-only and doesn't accept pull or merge requests.
	- [api.haiku-os.org](https://api.haiku-os.org "api.haiku-os.org"): (Work-in-Progress) The Haiku Book

### Retired sites
These are sites were formerly maintained by the Project, but have now been taken offline and retired:
- [svn.haiku-os.org](https://svn.haiku-os.org "svn.haiku-os.org"): Old source code repository. Previosly mirrored back to [BerliOS](https://web.archive.org/web/20161128085411/http://developer.berlios.de/projects/haiku/ "BerliOS"), to provide additional exposure.
- [hg.haiku-os.org](https://hg.haiku-os.org "hg.haiku-os.org"): Read-only mirror of Haiku's repository. Miscellaneous source repositories (modifications to Trac).
- [server-stats.haiku-os.org](https://server-stats.haiku-os.org "server-stats.haiku-os.org"): A visual look into the resource usage into the dedicated server. Nearly every aspect of the key services (www, dev, svn) can be inspected via graph.
- [web-stats.haiku-os.org](https://web-stats.haiku-os.org "web-stats.haiku-os.org"): Usage statistics, specific to website traffic
