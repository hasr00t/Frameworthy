# Frameworthy
Frameworthy is a collection of Attack Surface Management (ASM) and OSINT frameworks/platforms. Some are open source and therefore "free", while others can be obtained by paying a vendor for the service. Frameworthy is the collection of options as well as explaining WHY ASM and OSINT automation should be done for your organization regardless of size.

***

### What is ASM?
ASM is the continuous discovery, analysis, monitor and remediation of vulnerabilities and potential attack vectors on an organizations infrastructure. It is an incredibly important piece of Cyber Security to monitor not only infrastructure but also the human component. As such, OSINT frameworks are listed below.

As usual, caution should always be taken and all projects should be vetted for reliability and functionality. While I do my best to vet everything on this list, not all projects are vetted and tested before being added. 


***

## Open Source OSINT Frameworks

#### Amass
URL: https://github.com/OWASP/Amass
About: The OWASP Amass Project performs network mapping of attack surfaces and external asset discovery using open source information gathering and active reconnaissance techniques.

#### eReKon
URL: https://github.com/slithery0/eReKon
About: Web reconnaissance tool, only available in dark mode. Provides subdomain scanning, port scanning, version fingerprinting and screenshots of web applications.
** While it appears there is some development being done, the overall application appears to be under development still and should be used with caution. **


#### Recon-NG
URL: https://www.kali.org/tools/recon-ng/
About: Recon-ng is a full-featured Web Reconnaissance framework written in Python. Complete with independent modules, database interaction, built in convenience functions, interactive help, and command completion, Recon-ng provides a powerful environment in which open source web-based reconnaissance can be conducted quickly and thoroughly.

Recon-ng has a look and feel similar to the Metasploit Framework, reducing the learning curve for leveraging the framework. However, it is quite different. Recon-ng is not intended to compete with existing frameworks, as it is designed exclusively for web-based open source reconnaissance. If you want to exploit, use the Metasploit Framework. If you want to Social Engineer, use the Social Engineer Toolkit.

#### reNgine
URL: https://github.com/yogeshojha/rengine
About: reNgine is a web application reconnaissance suite with focus on a highly configurable streamlined recon process via Engines, recon data correlation, continuous monitoring, recon data backed by a database, and a simple yet intuitive User Interface. With features such as sub-scan, deeper co-relation, report generation, etc. reNgine aims to fix the gap in the traditional recon tools and probably a better alternative for existing commercial tools.

reNgine makes it easy for penetration testers and security auditors to gather reconnaissance data with bare minimal configuration.

#### ReconNess
URL: https://www.reconness.com/
About: ReconNess helps you to run and keep all your recon in the same place allowing you to focus only on the potentially vulnerable targets without distraction and without required a lot of bash skill or programing skill in general.

#### ReconPi
URL: https://github.com/x1mdev/ReconPi
About: A lightweight recon tool that performs extensive reconnaissance with the latest tools using a Raspberry Pi.
** It should be noted that this project has not been updated in some time. **

#### Intelligence X
URL: https://intelx.io/
About: Intelligence X provides information about the following search terms email addresses, domains, URLs, IPs, CIDRs, Bitcoin addresses, IPFS hashes. The platform stores historical data and searches the darknet, document sharing platforms, whois data, public data leaks among other databases to provide a complete picture. It should be noted that Intelligence X is based in the Czech Republic

#### SecurityTrails
URL: https://securitytrails.com/
About: SecurityTrails API can be used to search for domain, dns and IP related data. The website search field accepts keyword, hostname and domain search terms. It offers third-party integrations and multiple SDK/wrappers. 

#### sn0int
URL: https://github.com/kpcyrd/sn0int
About: sn0int is a semi-automatic OSINT framework and package manager. It's used by IT security professionals, bug bounty hunters, law enforcement agencies and in security awareness trainings to gather intelligence about a given target or about yourself. sn0int is enumerating attack surface by semi-automatically processing public information and mapping the results in a unified format for followup investigations.

## Paid/Vendor OSINT Frameworks

#### runZero
URL: https://www.runzero.com/
About: runZero is a network discovery and asset inventory platform that uncovers every network in use and identifies every device connected–without credentials.
** Free Trial is available. **


## Open Source Attack Surface Management Frameworks

#### ArcherySec
URL: https://github.com/archerysec/archerysec
https://www.archerysec.com/
About: ArcherySec allow to interact with continuous integration/continuous delivery (CI/CD) toolchains to specify testing, and control the release of a given build based on results. Its include prioritization functions, enabling you to focus on the most critical vulnerabilities. ArcherySec uses popular opensource tools to perform comprehensive scanning for web application and network. The developers can also utilize the tool for implementation of their DevOps CI/CD environment.

#### Attack Surface Analyzer
URL: https://github.com/microsoft/AttackSurfaceAnalyzer
About: Attack Surface Analyzer is a Microsoft developed open source security tool that analyzes the attack surface of a target system and reports on potential security vulnerabilities introduced during the installation of software or system misconfiguration.

#### Attack Surface Framework
URL: https://github.com/vmware-labs/attack-surface-framework
About: ASF aims to protect organizations acting as an attack surface watchdog, provided an “Object” which might be a: Domain, IP address or CIDR (Internal or External), ASF will discover assets/subdomains, enumerate their ports and services, track deltas and serve as a continuous and flexible attacking and alerting framework leveraging an additional layer of support against 0 day vulnerabilities with publicly available POCs.

#### AttackSurfaceMapper
URL: https://github.com/superhedgy/AttackSurfaceMapper
About: AttackSurfaceMapper (ASM) is a reconnaissance tool that uses a mixture of open source intelligence and active techniques to expand the attack surface of your target. You feed in a mixture of one or more domains, subdomains and IP addresses and it uses numerous techniques to find more targets. It enumerates subdomains with bruteforcing and passive lookups, Other IPs of the same network block owner, IPs that have multiple domain names pointing to them and so on.

Once the target list is fully expanded it performs passive reconnaissance on them, taking screenshots of websites, generating visual maps, looking up credentials in public breaches, passive port scanning with Shodan/Censys and scraping employees from LinkedIn.

#### Axium
URL: https://github.com/pry0cc/axiom
About: Axiom is a dynamic infrastructure framework to efficiently work with multi-cloud environments, build and deploy repeatable infrastructure focussed on offensive and defensive security.

Axiom works by pre-installing your tools of choice onto a 'base image', and then using that image to deploy fresh instances. From there, you can connect and instantly gain access to many tools useful for both bug hunters and pentesters. With the power of immutable infrastructure, most of which is done for you, you can just spin up 15 boxes, perform a distributed nmap/ffuf/screenshotting scan, and then shut them down.

Axiom supports several cloud providers, eventually, axiom should be completely cloud agnostic allowing unified control of a wide variety of different cloud environments with ease. Currently, DigitalOcean, IBM Cloud, Linode, Azure and AWS are officially supported providers. GCP isnt supported but is partially implemented and on the roadmap.

#### CloudFrontier
URL: https://github.com/riskprofiler/CloudFrontier
About: Monitor the internet attack surface of various public cloud environments. Currently supports AWS, GCP, Azure, DigitalOcean and Oracle Cloud.
** It should be noted that this project has not been updated in some time and there are open issues. **

#### Findomain
URL: https://github.com/Findomain/Findomain
About: The complete solution for domain recognition. Supports screenshoting, port scan, HTTP check, data import from other tools, subdomain monitoring, alerts via Discord, Slack and Telegram, multiple API Keys for sources and much more.

#### Intrigue-Core
URL: https://core.intrigue.io/
About: Intrigue Core is a framework for discovering attack surface. It discovers security-relevant assets and exposures within the context of projects and can be used with a human-in-the-loop running individual tasks, and/or automated through the use of workflows. With a flexible entity model and an incredibly deep enrichment system, it is the most full-featured attack surface discovery framework of its kind.

** A slack channel is available for support. Also, as of October 1, 2021, this component of the Intrigue project is no longer actively maintained on Github, and the code in Github has been re-licensed under the terms of the Mandiant Limited Open Source License Agreement. **

#### IVRE
URL: https://ivre.rocks/
About: IVRE is an open-source framework for network recon. It relies on open-source well-known tools (Nmap, Masscan, ZGrab2, ZDNS and Zeek (Bro)) to gather data (network intelligence), stores it in a database (MongoDB is the recommended backend), and provides tools to analyze it.

** Has a paid for model for those that do not want to deal with servers and complex configurations. **

#### Spiderfoot
URL: https://github.com/smicallef/spiderfoot
About: SpiderFoot is an open source intelligence (OSINT) automation tool. It integrates with just about every data source available and utilises a range of methods for data analysis, making that data easy to navigate.

SpiderFoot has an embedded web-server for providing a clean and intuitive web-based interface but can also be used completely via the command-line. It's written in Python 3 and MIT-licensed.

#### Sn1per
URL: https://github.com/1N3/Sn1per
https://sn1persecurity.com/wordpress/
About: Discover hidden assets and vulnerabilities in your environment with Sn1per. It integrates with commercial and open source vulnerability scanners to scan for the latest vulnerabilities. It can save time by automating the execution of tools to discover weaknesses across an organizations infrastructure. 


## Paid/Vendor Attack Surface Management Frameworks



## Misc


#### AlienVault
URL: https://otx.alienvault.com/
About: AlienVault is not necessarily an OSINT framework but rather an Open Intelligence Threat platform. Where users can submit malware for free analysis inside of AlienVault's sandboxes. AlienVault automatically extract IOCs from blogs, threat reports, emails, PCAPs, etc. It also providers users with access to millions of threat indicators.  

#### Crossfeed
URL: https://www.cisa.gov/resources-tools/services/crossfeed
About: Free CISA cybersecurity assessment services. Cyber Hygiene services are provided by CISA’s highly trained information security experts equipped with top-of-the-line tools. Their mission is to measurably reduce cybersecurity risks to the Nation by providing services to government and critical infrastructure stakeholders.

#### DefectDojo
URL: https://github.com/DefectDojo/django-DefectDojo
https://www.defectdojo.com/
About: DefectDojo is a security orchestration and vulnerability management platform. DefectDojo allows you to manage your application security program, maintain product and application information, triage vulnerabilities and push findings to systems like JIRA and Slack. DefectDojo enriches and refines vulnerability data using a number of heuristic algorithms that improve with the more you use the platform.
** Has a paid for and free version. **

#### Envizon
URL: https://github.com/evait-security/envizon
https://evait-security.github.io/envizon/
About: This tool is designed, developed and supported by evait security. In order to give something back to the security community, we publish our internally used and developed, state of the art network visualization and vulnerability reporting tool, 'envizon'. We hope your feedback will help to improve and hone it even further.

#### Faraday
URL: https://github.com/infobyte/faraday
About: Security has two difficult tasks: designing smart ways of getting new information, and keeping track of findings to improve remediation efforts. With Faraday, you may focus on discovering vulnerabilities while we help you with the rest. Just use it in your terminal and get your work organized on the run. Faraday was made to let you take advantage of the available tools in the community in a truly multiuser way.

Faraday aggregates and normalizes the data you load, allowing exploring it into different visualizations that are useful to managers and analysts alike.

#### Jok3r
URL: https://www.jok3r-framework.com/
About: Jok3r is a framework that aids penetration testers for network infrastructure and web security assessments. Its goal is to automate as much stuff as possible in order to quickly identify and exploit "low-hanging fruits" and "quick win" vulnerabilities on most common TCP/UDP services and most common web technologies (servers, CMS, languages...).

#### Natlas
URL: https://github.com/natlas/natlas
About: The goal of Natlas is not to identify a bunch of vulnerabilities, necessarily, but rather to identify exposure. Perhaps you want to make sure that no one is running ssh with password auth enabled. Or perhaps you want to look for any exposed nfs, smb, or rsync shares. Maybe you want to look for expiring or expired ssl certificates, or weak ssl ciphers being used. Since Natlas uses the popular [nmap](https://nmap.org/) port scanner, you can easily use any default nmap scripts in your scans.
** It should be noted that this project has not been updated in some time. **

#### Offensive ELK
URL: https://github.com/marco-lancini/docker_offensive_elk
About: Offensive ELK is a custom Elasticsearch setup, aiming to show how traditional “defensive” tools can be effectively used for offensive security data analysis, helping your team collaborate and triage scan results.

In particular, Elasticsearch offers the chance to aggregate a multitude of disparate data sources, query them with a unified interface, with the aim of extracting actionable knowledge from a huge amount of unclassified data.

A full walkthrough that led me to this setup can be found at: https://www.marcolancini.it/2018/blog-elk-for-nmap/.

#### Osmedeus
URL: https://github.com/j3ssie/osmedeus
About: Osmedeus is a Workflow Engine for Offensive Security. It was designed to build a foundation with the capability and flexibility that allows you to build your own reconnaissance system and run it on a large number of targets.

#### SonarSearch
URL: https://github.com/Cgboal/SonarSearch
About: This repo contains all the tools needed to create a blazing fast API for Rapid7's Project Sonar dataset. It employs a custom indexing method in order to achieve fast lookups of both subdomains for a given domain, and domains which resolve to a given IP address.

#### Sublert
URL: https://github.com/yassineaboukir/sublert
About: Sublert is a security and reconnaissance tool that was written in Python to leverage certificate transparency for the sole purpose of monitoring new subdomains deployed by specific organizations and issued TLS/SSL certificate. The tool is supposed to be scheduled to run periodically at fixed times, dates, or intervals (Ideally each day). New identified subdomains will be sent to Slack workspace with a notification push. Furthermore, the tool performs DNS resolution to determine working subdomains.

#### URLScan.io
URL: https://urlscan.io/
About: free service to scan and analyse websites. When a URL is submitted to urlscan.io, an automated process will browse to the URL like a regular user and record the activity that this page navigation creates. This includes the domains and IPs contacted, the resources (JavaScript, CSS, etc) requested from those domains, as well as additional information about the page itself. urlscan.io will take a screenshot of the page, record the DOM content, JavaScript global variables, cookies created by the page, and a myriad of other observations. If the site is targeting the users one of the more than 900 brands tracked by urlscan.io, it will be highlighted as potentially malicious in the scan results.
