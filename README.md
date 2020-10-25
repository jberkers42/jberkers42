# About Me

Hi there, my name is John - aka [jberkers42][website]

I'm a husband, father and Security Professional

My professional intersts include:

* Security (which Security Professional is not interested in security?)
* SIEM (Security Incident and Event Management)
* DevOps/SecOps/DevSecOps (basically automating stuff)

## Employment

I work at [IPSec][employer] in Melbourne, Australia, having been there since the foundation of the company in late 2009, as a Senior Security Engineer, Architect and Consultant.  I spend a lot of my time working with SIEM technologies, mostly [LogRhythm][logrhythm], as well as a number of firewall and other security technologies.

My focus for the past couple of years has been to migrate more of our environment to the cloud, as well as increasing the level of automation for deployment and maintenance tasks.

## Automation

There are two areas where I have focused on automation:

* Infrastructure build and maintenance
* Response from SIEM Alerts

For the former, most of the attention has been to implement automation and testing using [Ansible][ansible] to automate the implemtation and maintenance of our infrastructure.  This has been achieved through the use of a combination of tools:

### Infrastructure

* [GitLab][gitlab]
* [Ansible][ansible]
* [AWX][awx]

GitLab repositories are used to hold the definition of the environment(s) as well as the instructions to build them.  These are separated into functional layers:

* Inventories
* Roles
* Playbooks

Ansible and AWX are used to execute the instructions against an appropriate inventory.

### SIEM Response

One of the tents of a SOAR platform is to provide Automation and Response to an identified security incident.  [LogRhythm][logrhythm] achieves this through the use of a SmartResponse&trade;.  SmartResponses are essentially a script wrapped with an XML file that tells LogRhyhtm how to execute it.

Most of my SmartResponse work has been in [PowerShell][pwsh].

### Connect with me

[<img align="left" alt="jberkers42" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][website]
[<img align="left" alt="BerkersJohn | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="jberkers | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="john.berkers | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

<br />

## Tools

[<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />][vscode]
[<img align="left" alt="SQL" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" />][sqlserver]
[<img align="left" alt="Git" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />][git]
[<img align="left" alt="Ansible" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/ansible/ansible.png" />][ansible]
[<img align="left" alt="Azure" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/azure/azure.png" />][azure]
[<img align="left" alt="AWS" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/aws/aws.png" />][aws]
[<img align="left" alt="MarkDown" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/markdown/markdown.png" />][markdown]
[<img align="left" alt="LogRhythm" width="168px" src="https://logrhythm.com/images/lr-logos/hex/LogRhythm_Logo_Color_ForLightBackgrounds_HEX.png" />][logrhythm]
[<img algin="left" alt="GitLab" width="26px" src="https://about.gitlab.com/images/press/logo/png/gitlab-logo-gray-stacked-rgb.png" />][gitlab]
[<img algin="left" alt="PowerShell" width="26px" src="https://docs.microsoft.com/en-us/powershell/media/index/ps_black_128.svg" />][pwsh]

[website]: https://www.github.com/jberkers42
[employer]: https://www.ipsec.com/
[logrhythm]: https://www.logrhythm.com/
[gitlab]: https://www.gitlab.com/
[ansible]: https://www.ansible.com/
[vscode]: https://code.visualstudio.com/
[sqlserver]: https://www.microsoft.com/en-au/sql-server/
[git]: https://git-scm.com/
[azure]: https://azure.microsoft.com/
[aws]: https://aws.amazon.com/
[markdown]: https://www.markdownguide.org/
[awx]: https://github.com/ansible/awx
[pwsh]: https://docs.microsoft.com/en-us/powershell/
[twitter]: https://twitter.com/BerkersJohn
[instagram]: https://instagram.com/john.berkers
[linkedin]: https://www.linkedin.com/in/john-berkers-1075aa4
