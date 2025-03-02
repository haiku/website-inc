---
title: Infrastructure provided by Haiku, Inc.
layout: single
---

As an open-source project, Haiku®'s visibility and presence on the internet is vital to its existence, growth, and reputation. Ensuring high quality services to the Haiku Project is the most essential item for receiving funds.

> Current as of March 1st, 2025.

## Hosting

### Kubernetes Cluster

**Cost:** $219.50 USD / Month

We maintain a Kubernetes cluster to run mission critical frontend services.  Three nodes run our
public facing services.

* discuss.haiku-os.org  ~3.7GiB Memory
* review.haiku-os.org   ~2.3GiB Memory
* Postgresql Database   ~2.5GiB Memory
* dev.haiku-os.org      ~0.7GiB - 2.0GiB Memory
* Misc services
  * hpkg.haiku-os.org
  * i18n.haiku-os.org
  * ci.haiku-os.org (Concourse)
  * build.haiku-os.org (Haikuporter Buildmaster)
  * rsync.haiku-os.org
  * download.haiku-os.org
  * Irc bots
  * Git sync services to github / codeberg

### Block Storage

**Cost:** $25.00 USD / Month

250GiB of block storage at Digital Ocean to store the Haikuports repository.

### Virtual Machines

**Cost:** $7.00 USD / Month

We maintain a dedicated mail server for all outbound and inbound email.

### Object Storage

Haiku is working on expanding our usage of object storage as it represents cheap, portable storage
which is API focused and can be migrated to alternative providers without lock-in.

**Cost:** $7.00 - 14.00 USD / Month
Wasabi s3 storage hosting package repositories as well as nightly image downloads.

**Cost:** $7.00 - 14.00 USD / Month
Backblaze B2 storage hosting haiku package repositories (experimental)

### Physical Machines

**Cost:** Occasional expenditure as-needed to maintain

* Several VM based builders for Haikuports generously donated by mmlr.
* Large physical Dell Optiplex desktop building Haiku (Concourse worker) donated by kallisti5.
* Intel Nuc building Haiku (backup / standby Concourse worker) donated by Ryan Leavengood.
* SiFive Unmatched RISC-V 64 desktop owned by kallisti5 donated by Haiku, Inc.
* SiFive Unmatched RISC-V 64 desktop owned by x512 donated by Haiku, Inc.

### Web Hosting Services
Currently, [Netlify's paid hosting services](https://www.netlify.com/) are used. We get an open-source not for profit organization via our display of the Netlify logo at the bottom of our site.

## Domain names
These are the domains, which are paid by Haiku, Inc.

- haiku-os.org
- haiku-os.com
- haiku-os.net
- haiku-project.com
- haiku-inc.org

### Retired sites
These are sites were formerly maintained by the Project, but have now been taken offline and retired:
- [svn.haiku-os.org](https://svn.haiku-os.org "svn.haiku-os.org"): Old source code repository. Previosly mirrored back to [BerliOS](https://web.archive.org/web/20161128085411/http://developer.berlios.de/projects/haiku/ "BerliOS"), to provide additional exposure.
- [hg.haiku-os.org](https://hg.haiku-os.org "hg.haiku-os.org"): Read-only mirror of Haiku's repository. Miscellaneous source repositories (modifications to Trac).
- [server-stats.haiku-os.org](https://server-stats.haiku-os.org "server-stats.haiku-os.org"): A visual look into the resource usage into the dedicated server. Nearly every aspect of the key services (www, dev, svn) can be inspected via graph.
- [web-stats.haiku-os.org](https://web-stats.haiku-os.org "web-stats.haiku-os.org"): Usage statistics, specific to website traffic
