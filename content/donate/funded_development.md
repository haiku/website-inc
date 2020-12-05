# Development Contributions financed by Haiku, Inc.
The Haiku Project rests on the shoulders of volunteer individuals. They spend their free time developing, bug hunting and generally advancing Haiku®. Being able to financially support a contributor, to allow them to fully concentrate on development can do wonders for progressing Haiku forward.

Supporting contributors through contracts allow them to dedicate large blocks of time, which normally would not be available for Haiku development. These contracts are not for purchasing an hour here, three hours there. Nor are the contracts for working on something that would not help reach R1. These contracts are specifically for putting Haiku on the fast track to R1, whether it be the next development release or the next stable release.

The year 2010 marked the year in which Haiku, Inc. returned to financing established contributors for their development efforts on a contractual basis.

## 2013
### Package management
- Contractor: Oliver Tappe (zooey)
- Cost: €4000 EUR (approx. $5,400 USD)
- Hours: 320
- Related articles:
	- [Contract announcement](https://www.haiku-os.org/blog/zooey/2013-06-11_package_management_getting_cross/ "Contract announcement")
	- [Blog post: End of package management contract](https://www.haiku-os.org/blog/zooey/2013-11-10_end_package_management_contract/ "Blog post: End of package management contract")
	- Repository: HaikuPorts. (dead link)
	- Repository: Build recipes for bootstrapping a new Haiku architecture. (dead link)
	- Repository: Haikuporter. (dead link)
	- Documentation: HaikuPorter for Package Management (dead link)
	- Documentation: Package Management wiki (dead link)
- Summary:

> From mid June to early November 2013, I have spent 320 more hours to continue the work on package management: During the first couple of weeks, I've worked on getting the bootstrap images built (mostly on the haikuporter/haikuports side, but some bits of work on Haiku, too). When that was done, I used the feature to bootstrap the x86_64 architecture of Haiku, which involved fixing a couple of problems in haikuports/recipes. After BeGeistert (a week that I've spent working on package management, but that I didn't consider part of the paid work), the next step was to merge the package-management branches of haikuporter and haikuports into the respective master. Following that was reworking the way how packaged perl and python handle their 3rd-party modules, which involved implementing a separation of "vendor" (i.e. packaged) modules and "site" modules (which are built from source). Finally, I've worked on the infrastructure that allows to build the HaikuPorts package repositories automatically that are required by Haiku's build system.	From mid June to early November 2013, I have spent 320 more hours to continue the work on package management: During the first couple of weeks, I've worked on getting the bootstrap images built (mostly on the haikuporter/haikuports side, but some bits of work on Haiku, too). When that was done, I used the feature to bootstrap the x86_64 architecture of Haiku, which involved fixing a couple of problems in haikuports/recipes. After BeGeistert (a week that I've spent working on package management, but that I didn't consider part of the paid work), the next step was to merge the package-management branches of haikuporter and haikuports into the respective master. Following that was reworking the way how packaged perl and python handle their 3rd-party modules, which involved implementing a separation of "vendor" (i.e. packaged) modules and "site" modules (which are built from source). Finally, I've worked on the infrastructure that allows to build the HaikuPorts package repositories automatically that are required by Haiku's build system.

### Package management
- Contractor: Ingo Weinhold
- Cost: €19,200 EUR (approx. $25,600 USD)
- Hours: 480
- Related articles:
	- [Contract announcement](https://www.haiku-os.org/blog/bonefish/2013-06-03_package_management_new_contract_starts/ "Contract announcement")
	- [Blog post: Package Management: The Return of the Hybrid](https://www.haiku-os.org/blog/bonefish/2013-08-12_package_management_return_hybrid/ "Blog post: Package Management: The Return of the Hybrid")
	- [Blog post: Package Management Goes Live](https://www.haiku-os.org/blog/bonefish/2013-09-28_package_management_goes_live/ "Blog post: Package Management Goes Live")
	- Repository: Haiku Package Management (dead link)
	- Repository: Haiku Package Management Build Tools (dead link)
- Summary:
> From June through August I continued the work on package management together with Oliver Tappe. I assisted Oliver with getting the bootstrap process for HaikuPorts packages ready -- implementing the bootstrap support in haikuporter for non-Haiku systems and adjusting many of the build recipes accordingly. I added bootstrap support for Haiku itself to its build system. I also implemented secondary architecture (aka "hybrid") support to Haiku's build system, to haikuporter, and the relevant HaikuPorts recipes. I extended the build system to interact with the now-existing HaikuPorts package repository -- building it on the server side and downloading packages from it during the Haiku build process. Finally I added dependency resolution support to the package daemon. A few weeks after the end of the contract the package management branch was ready to be merged back into the Haiku mainline development.From June through August I continued the work on package management together with Oliver Tappe. I assisted Oliver with getting the bootstrap process for HaikuPorts packages ready -- implementing the bootstrap support in haikuporter for non-Haiku systems and adjusting many of the build recipes accordingly. I added bootstrap support for Haiku itself to its build system. I also implemented secondary architecture (aka "hybrid") support to Haiku's build system, to haikuporter, and the relevant HaikuPorts recipes. I extended the build system to interact with the now-existing HaikuPorts package repository -- building it on the server side and downloading packages from it during the Haiku build process. Finally I added dependency resolution support to the package daemon. A few weeks after the end of the contract the package management branch was ready to be merged back into the Haiku mainline development.

### Package management
- Contractor: Oliver Tappe
- Cost: €4000 EUR (approx. $5,300 USD)
- Hours: 320
- Related articles:
	- [Contract announcement](https://www.haiku-os.org/blog/bonefish/2013-03-25_package_management_new_season_starts/ "Contract announcement")
	- [Blog post: Package Management: Getting Cross](https://www.haiku-os.org/blog/zooey/2013-06-11_package_management_getting_cross/ "Blog post: Package Management: Getting Cross")
	- Repository: Haiku Package Management (dead link)
	- Repository: Haiku Package Management Build Tools (dead link)
	- Repository: HaikuPorts. See the "package-management" branch. (dead link)
	- Repository: Build recipes for bootstrapping a new Haiku architecture. (dead link)
	- Repository: Haikuporter. See the "package-management" branch. (dead link)
	- Documentation: HaikuPorter for Package Management (dead link)
	- Documentation: Package Management wiki (dead link)
- Summary:
> From end of March to early June 2013, I have worked with Ingo on package management. During the first couple of weeks, I've mostly worked on the second incarnation of HaikuPorter, in order to get the tool ready for building packages and hierarchical builds involving automatic dependency resolution. Just like Ingo, I have spent a considerable amount of time creating build recipes for ports required by Haiku. During the last weeks, I've concentrated on getting the cross-build repository to work, which contains ports meant to be built on one architecture for a different target architecture. Having the means to do this properly in an automated fashion facilitates porting Haiku to a new architecture. That part involved more work on build recipes as well as a bit of work on Haiku's build system.

### Package management
- Contractor: Ingo Weinhold
- Cost: €4000 EUR (approx. $5,200 USD)
- Hours: 320
- Related articles:
	- [Contract announcement](https://www.haiku-os.org/blog/bonefish/2013-03-25_package_management_new_season_starts/ "Contract announcement")
	- [Blog post: Package Management: Building Things](https://www.haiku-os.org/blog/bonefish/2013-04-13_package_management_building_things/ "Blog post: Package Management: Building Things")
	- [Blog post: Package Management: Building Things (Part 2)](https://www.haiku-os.org/blog/bonefish/2013-05-25_package_management_building_things_part_2/ "Blog post: Package Management: Building Things (Part 2)")
	- Repository: Haiku Package Management (repository has been pulled)
	- Repository: Haiku Package Management Build Tools (repository has been pulled)
- Summary:
> From end of March through early May, together with Oliver Tappe, I continued the work on package management, which had lain dormant for almost two years. During this time we mainly focused on getting the package building side of things into a good shape. I finished the port of libsolv (the dependency solving library), implemented dependency solving support in the package kit based on it, and added a dependency solving service command for package building as well as basic package installation, removal, and update commands to our command line package manager. Moreover I added a package management daemon and implemented its fundamental functionality. A significant part of the contract time was spent on creating proper build recipes for all the external software Haiku depends on or is bundled with by default. Finally I merged the Haiku master branch into the package management branch -- thus bringing the latter back in sync with the main line of Haiku development -- and improved several features of the build system related to handling optional packages.

## 2012
### WebKit, WebPositive
- Contractor: Alexandre Deckner
- Cost: €2,000 EUR (approx. $2,604 USD)
- Hours: 160
- Related articles:
	- [Contract announcement](https://www.haiku-os.org/news/2012-05-20_new_development_contractor/ "Contract announcement")
	- [Blog post: Making it Build](https://www.haiku-os.org/blog/aldeck/2012-06-06_making_it_build/ "Blog post: Making it Build")
	- [Repository: haiku-webkit](https://github.com/aldeck/haiku-webkit "Repository: haiku-webkit")
- Summary:
> In June, Haiku's WebKit port was updated to r115944. To give you a scope of this task, the previous revision used by WebPositive was over two years old and over 70,000 changesets behind! One interesting aspect is that our WebKit port is rebuilt in such a way that it is integrated with the whole history of the main WebKit tree. That makes future updates even easier, as we can just rebase off of the git-svn clone and simply make little adjustments for whatever is needed (e.g., conflict handling). Eventually, this can more or less be automated. Additionally, WebPositive (along with all of its own history) was migrated into the Haiku source tree. That allows all of Haiku's developers to make improvements to the browser.In June, Haiku's WebKit port was updated to r115944. To give you a scope of this task, the previous revision used by WebPositive was over two years old and over 70,000 changesets behind! One interesting aspect is that our WebKit port is rebuilt in such a way that it is integrated with the whole history of the main WebKit tree. That makes future updates even easier, as we can just rebase off of the git-svn clone and simply make little adjustments for whatever is needed (e.g., conflict handling). Eventually, this can more or less be automated. Additionally, WebPositive (along with all of its own history) was migrated into the Haiku source tree. That allows all of Haiku's developers to make improvements to the browser.

### Haiku R1 development
- Contractor: Michael Lotz (mmlr)
- Cost: 8,050 CHF (approx. $8774.50 USD)
- Hours: 450
- Related articles:
	- [Contract announcement](https://www.haiku-os.org/news/2011-06-29_time_now_michael_lotz_long_term_contract/ "Contract announcement")
	- [Blog post: My first Month of Contract Work](https://www.haiku-os.org/blog/mmlr/2011-10-27_my_first_month_contract_work/ "Blog post: My first Month of Contract Work")
	- [Blog post: Greetings (mostly) from the Kernel (Debugging Land)](https://www.haiku-os.org/blog/mmlr/2011-11-17_greetings_mostly_kernel_debugging_land/ "Blog post: Greetings (mostly) from the Kernel (Debugging Land)")
	- [Blog post: From Bugs back to Wireless and Friends](https://www.haiku-os.org/blog/mmlr/2011-11-28_bugs_back_wireless_and_friends/ "Blog post: From Bugs back to Wireless and Friends")
	- [Blog post: API Design is Hard, Finding Bugs (Can be Made) Easy!](https://www.haiku-os.org/blog/mmlr/2011-12-23_api_design_hard_finding_bugs_can_be_made_easy/ "Blog post: API Design is Hard, Finding Bugs (Can be Made) Easy!")
	- [Repository: KeyStore API](https://github.com/mmlr/haiku/tree/key_store "Repository: KeyStore API")
	- [Commit history to Haiku](https://git.haiku-os.org/haiku/log/?qt=author&q=mmlr&showmsg=1 "Commit history to Haiku")
- Summary:
> Through late September of 2011 to January of 2012, many areas of Haiku were worked on. First, the port of the wpa_supplicant was finished and added to Haiku. This brought WPA/WPA2 support to Haiku. Though a new mechanism to store and manage keys and passwords is needed. This eventually led to working on the KeyStore API, which is mostly implemented and is hosted at GitHub for the time being. Support for SandyBridge based integrated graphics was added into the intel_extreme driver. In between that, there was a lot of low level development, involving time intensive bug hunting. This involves, but isn't limited to adding various debug functions into the kernel and kernel debugging land, debug memory intialization for the slab heap implementation, allocation tracking for both the slab and pages. With the help of the new debugging features, numerous old tickets were revisited. For the KeyStore API, encryption still needs to be implemented and will most likely utilize OpenSSL. Aside from that it is mostly working and could be checked in afterwards.Through late September of 2011 to January of 2012, many areas of Haiku were worked on. First, the port of the wpa_supplicant was finished and added to Haiku. This brought WPA/WPA2 support to Haiku. Though a new mechanism to store and manage keys and passwords is needed. This eventually led to working on the KeyStore API, which is mostly implemented and is hosted at GitHub for the time being. Support for SandyBridge based integrated graphics was added into the intel_extreme driver. In between that, there was a lot of low level development, involving time intensive bug hunting. This involves, but isn't limited to adding various debug functions into the kernel and kernel debugging land, debug memory intialization for the slab heap implementation, allocation tracking for both the slab and pages. With the help of the new debugging features, numerous old tickets were revisited. For the KeyStore API, encryption still needs to be implemented and will most likely utilize OpenSSL. Aside from that it is mostly working and could be checked in afterwards.

## 2011
### Package Management
- Contractor: Ingo Weinhold
- Cost: $2,910 USD
- Hours: 160
- Related articles:
	- [Contract announcement](https://www.haiku-os.org/news/2011-06-12_haiku_inc_accepts_second_development_contract_2011/ "Contract announcement")
	- [Blog post: Queries, Solutions, and the Status Quo](https://www.haiku-os.org/blog/bonefish/2011-07-18_package_management_queries_solutions_and_status_quo/ "Blog post: Queries, Solutions, and the Status Quo")
- Summary:
> In mid June through mid July I continued the work on Haiku's package management functionality. I got the build system ready to produce Haiku images with a fully packaged core system and I repackaged most "/boot/common" software as Haiku packages and also let them be included in the image. I extended the boot loader and the kernel to be able to boot off of such an image. Furthermore I added query functionality to packagefs as well as support for a directory with autogenerated package and dependency links. I improved the "package" command and the build system to allow for updating individual files in a package and I also started porting libsolv to Haiku, the library the package kit's dependency solver will be based on. While my work helped to get significantly closer to a working package management solution, there's still a lot left to do to reach that goal.In mid June through mid July I continued the work on Haiku's package management functionality. I got the build system ready to produce Haiku images with a fully packaged core system and I repackaged most "/boot/common" software as Haiku packages and also let them be included in the image. I extended the boot loader and the kernel to be able to boot off of such an image. Furthermore I added query functionality to packagefs as well as support for a directory with autogenerated package and dependency links. I improved the "package" command and the build system to allow for updating individual files in a package and I also started porting libsolv to Haiku, the library the package kit's dependency solver will be based on. While my work helped to get significantly closer to a working package management solution, there's still a lot left to do to reach that goal.

## Package Management: Initial Research & Development
- Contractor: Oliver Tappe
- Cost: $2,622 USD
- Hours: 160
- Related articles: [Contract announcement](https://www.haiku-os.org/news/2010-12-27_haiku_inc_accepts_contract_relating_package_management/ "Contract announcement")
- Summary:
> In January 2011, I have worked on researching the different existing package management systems of other OSes (both their user interface and their code), in order to determine whether any of their components could be reused. As Haiku has a very special package format and mode of package-activation (package-fs), it turned out that none of the existing systems could be used, since most are closely coupled with their own package format. The only thing that we will be reusing is openSUSE's dependency solver (satsolver). That decision did require less time than anticipated, so during the rest of my contract period, I started implementing different parts of the package kit. This work is continuing and I hope to have something presentable ready in March.In January 2011, I have worked on researching the different existing package management systems of other OSes (both their user interface and their code), in order to determine whether any of their components could be reused. As Haiku has a very special package format and mode of package-activation (package-fs), it turned out that none of the existing systems could be used, since most are closely coupled with their own package format. The only thing that we will be reusing is openSUSE's dependency solver (satsolver). That decision did require less time than anticipated, so during the rest of my contract period, I started implementing different parts of the package kit. This work is continuing and I hope to have something presentable ready in March.

## 2010
### WebKit, WebPositive
- Contractor: Stephan Aßmus
- Cost: $4,000 USD
- Hours: 320
- Related articles: [Contract announcement](https://www.haiku-os.org/news/2010-02-21_haiku_inc_hiring_funds_needed/ "Contract announcement"), [renewal announcement](https://www.haiku-os.org/news/2010-03-22_haiku_inc_contractors_haiku_code_drive_and_available_funds/ "renewal announcement")
- Summary:
> In the February to April 2010 timeframe, I have completed a lot of the missing parts of the WebKit port to Haiku and also rewrote many parts of the previous porting efforts to better fit the Haiku threading model. When the port itself got more mature, I wrote the WebPositive browser offering the most important features expected from a modern web browser. Compared to the Firefox 2 port for BeOS, WebPositive is much better integrated with the Haiku system, launches very quickly and benefits from it's much more current web engine. In other aspects, it does still lack behind Firefox, though, for example in SSL certificate handling, caching, or automatic filling of forms. Still, WebPositive has been integrated in Haiku just in time for the second Alpha release and has replaced the Firefox 2 port as the default browser. Development and bug fixing had continued past the contract time.In the February to April 2010 timeframe, I have completed a lot of the missing parts of the WebKit port to Haiku and also rewrote many parts of the previous porting efforts to better fit the Haiku threading model. When the port itself got more mature, I wrote the WebPositive browser offering the most important features expected from a modern web browser. Compared to the Firefox 2 port for BeOS, WebPositive is much better integrated with the Haiku system, launches very quickly and benefits from it's much more current web engine. In other aspects, it does still lack behind Firefox, though, for example in SSL certificate handling, caching, or automatic filling of forms. Still, WebPositive has been integrated in Haiku just in time for the second Alpha release and has replaced the Firefox 2 port as the default browser. Development and bug fixing had continued past the contract time.

### POSIX improvements, managing the release of R1 Alpha 2
- Contractor: Ingo Weinhold
- Cost: $2,000 USD
- Hours: 160
- Related articles: [Contract announcement](https://www.haiku-os.org/news/2010-04-07_haiku_inc_contractors_yes_more_donation_analysis_and_google_checkout/ "Contract announcement")
- Summary:
> I continued my earlier work to get the Open POSIX Test Suite to run on Haiku. Various POSIX compliance issues and bugs in Haiku uncovered by it could be fixed, among them problems with signals, pthread mutexes and condition variables. I fixed serveral kernel bugs, most of them related to boot problems, and implemented an IOCache for read-only media to speed up booting off CD significantly. Furthermore I managed the alpha 2 release branch and reviewed most of the patches merged into it.I continued my earlier work to get the Open POSIX Test Suite to run on Haiku. Various POSIX compliance issues and bugs in Haiku uncovered by it could be fixed, among them problems with signals, pthread mutexes and condition variables. I fixed serveral kernel bugs, most of them related to boot problems, and implemented an IOCache for read-only media to speed up booting off CD significantly. Furthermore I managed the alpha 2 release branch and reviewed most of the patches merged into it.

### Locale Kit
- Contractor: Adrien Destugues
- Cost: $2,000 USD
- Hours: 320
- Related articles: [Contract announcement](https://www.haiku-os.org/news/2010-03-22_haiku_inc_contractors_haiku_code_drive_and_available_funds/ "Contract announcement")
- Summary:
> During two months in summer of 2010, I worked on various things for Haiku. The initial purpose of the contract was i18n. Following on the work I had done the previous year as part of GSoC, I extended the API most notably in the area of number and date formatting. This included some design changes in the initial API (that was created much earlier by the Open Tracker development team), and changing it to better match current use of the Locale API as a system-wide one, and the fact that ICU is used as a backend. This work included localizing dates in tracker and mostly rewriting the Time preflet to use ICU time zones instead of directly accessing the tzdata files. This latter part also led to reworking the POSIX part of the API, and moving some stuff related to it out of the kernel. Oliver Tappe took care of this. As the Locale API is now pretty stable and useable in this area, I spent the remaining time working on improving the intel_extreme video driver to bring native video resolution to my own laptop and similar models. I also wrote a driver for usb floppy drives.During two months in summer of 2010, I worked on various things for Haiku. The initial purpose of the contract was i18n. Following on the work I had done the previous year as part of GSoC, I extended the API most notably in the area of number and date formatting. This included some design changes in the initial API (that was created much earlier by the Open Tracker development team), and changing it to better match current use of the Locale API as a system-wide one, and the fact that ICU is used as a backend. This work included localizing dates in tracker and mostly rewriting the Time preflet to use ICU time zones instead of directly accessing the tzdata files. This latter part also led to reworking the POSIX part of the API, and moving some stuff related to it out of the kernel. Oliver Tappe took care of this. As the Locale API is now pretty stable and useable in this area, I spent the remaining time working on improving the intel_extreme video driver to bring native video resolution to my own laptop and similar models. I also wrote a driver for usb floppy drives.

### Networking Improvements
- Contractor: Axel Dörfler
- Cost: $1,680 USD
- Hours: 120
- Related articles: [Contract announcement](https://www.haiku-os.org/news/2010-07-14_opportunity_pay_axel_code_haiku/ "Contract announcement")
- Summary:
> Since I was actively looking for a new job, and could need the money, I took the opportunity to get contracted by Haiku, Inc. to tackle some long standing issues in the network stack. It turned out to be good timing as well, since I was able to deliver some needed functionality to the IPv6 work done by Atis Elsts during GSoC 2010. During the three weeks of my contract, I made over hundred commits, and have fixed numerous bugs.

### Media Kit, MediaPlayer, app_server
- Contractor: Stephan Aßmus
- Cost: $2,000 USD
- Hours: 160
- Related articles: [Contract announcement](https://www.haiku-os.org/news/2010-08-12_stephan_back_wheel_website_haiku_inc "Contract announcement")
- Summary:
> From September to October 2010 I worked on fixing bugs in the Haiku app_server and Media Kit. In general, the playback capabilities and media file format compatibility has been greatly improved to be mostly on par with FFmpeg, especially for such important file formats as AVI, MP4 and MKV. Support for the Xiph codecs has been improved and is offered even for encoding. The MediaPlayer interface received a complete overhaul and many new features like full-screen playback controls, media winding and limited support for video subtiles.From September to October 2010 I worked on fixing bugs in the Haiku app_server and Media Kit. In general, the playback capabilities and media file format compatibility has been greatly improved to be mostly on par with FFmpeg, especially for such important file formats as AVI, MP4 and MKV. Support for the Xiph codecs has been improved and is offered even for encoding. The MediaPlayer interface received a complete overhaul and many new features like full-screen playback controls, media winding and limited support for video subtiles.