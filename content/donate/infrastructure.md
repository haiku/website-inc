# Infrastructure provided by Haiku, Inc.
As an open-source project, Haiku®'s visibility and presence on the internet is vital to its existence, growth, and reputation. Ensuring high quality services to the Haiku Project is the most essential item for receiving funds.

Some weeks before the release of Haiku R1/Alpha 1, a commitment was made to overhaul the infrastructure that provides key services to the Project. Leading up to this, there had been numerous service issues with the previous shared hosting plan and free source code repository. These issues ranged from unexplainable slowdowns to even occasional downtime. In a few words, the needs of the Project were outgrowing its shoes and an upgrade was desired.

## Dedicated Server
Through discussions on the [haiku-development mailing list](https://www.freelists.org/list/haiku-development "haiku-development mailing list"), it was decided to acquire an [EX4 dedicated server](https://web.archive.org/web/20161128085411/http://www.hetzner.de/en/hosting/produkte_rootserver/ex4/ "EX4 dedicated server") with Hetzner. This increased the hosting costs from roughly $300/year to $900/year; however it has been worth every cent.

- Intel® Core™ i7-2600 Quadcore incl. Hyper-Threading Technology
- RAM 16 GB DDR3 RAM
- Hard discs 2 x 3 GB SATA 6Gb/s HDD (Software-RAID 1)
- NIC 1 GBit OnBoard (connected at 100 MBit)
- Backup Space 100 GB
- Traffic Unlimited (>10,000 GB/month will reduce bandwidth to 10 MBit/s)

To supplement the provided backup space, two project members provide off-site backup storage. These backups automatically occur on a nightly basis and ensure a greater level of redundancy to avoid worst-case data-loss scenarios

As an anecdote, Hetzner Online has a [regard for environmental protection](https://www.hetzner.com/unternehmen/umweltschutz/?country=en "regard for environmental protection") and has committed to reducing CO2 emissions.

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
- **Source code repositories:**
	- [cgit.haiku-os.org](https://cgit.haiku-os.org "cgit.haiku-os.org"): Main source code repository. A mirror exists at [GitHub](https://github.com/haiku/ "GitHub") and there used to be one at Gitorious (the service has been shutdown), though the mirror is considered read-only and doesn't accept pull or merge requests.
	- [svn.haiku-os.org](https://svn.haiku-os.org "svn.haiku-os.org"): Old source code repository. Previosly mirrored back to [BerliOS](https://web.archive.org/web/20161128085411/http://developer.berlios.de/projects/haiku/ "BerliOS"), to provide additional exposure.
	- [hg.haiku-os.org](https://hg.haiku-os.org "hg.haiku-os.org"): Read-only mirror of Haiku's repository. Miscellaneous source repositories (modifications to Trac).
	- [server-stats.haiku-os.org](https://server-stats.haiku-os.org "server-stats.haiku-os.org"): A visual look into the resource usage into the dedicated server. Nearly every aspect of the key services (www, dev, svn) can be inspected via graph.
	- [web-stats.haiku-os.org](https://web-stats.haiku-os.org "web-stats.haiku-os.org"): Usage statistics, specific to website traffic
	- [api.haiku-os.org](https://api.haiku-os.org "api.haiku-os.org"): (Work-in-Progress) The Haiku Book

## 3rd Party Sites
In some cases, hosting is provided to third-parties who provide key services to the project.

- **HaikuPorts:**
	- [ports.haiku-files.org](https://ports.haiku-files.org "ports.haiku-files.org"): Main site, Trac, SVN repository, and mailing lists.
	- [ports-space.haiku-files.org](https://ports-space.haiku-files.org "ports-space.haiku-files.org"): Storage site for binary archives. SFTP upload and HTTP anonymous access.

## Miscellaneous
- haiku-os.org email addresses available upon request to project members
- Moving away from transmitting plaintext for password authentication
- SSL Certificates