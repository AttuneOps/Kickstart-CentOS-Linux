



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# Kickstart CentOS Linux






# Attune

[Attune](https://www.servertribe.com/)
automates and orchestrates processes to streamline deployments, scaling,
migrations, and management of your systems. The Attune platform is building a
community of sharable automated and orchestrated processes.

You can leverage the publicly available orchestrated blueprints to increase
your productivity, and accelerate the delivery of your projects. You can
open-source your own work and improve existing community orchestrated projects.

## Get Started with Attune, Download NOW!

The **Attune Community Edition** can be
[downloaded](https://www.servertribe.com/comunity-edition/)
for free from our
[ServerTribe website](https://www.servertribe.com/comunity-edition/).
You can learn more about Attune through
[ServerTribe's YouTube Channel](https://www.youtube.com/@servertribe).







# Clone this Project

To clone this project into your own instance of Attune, follow the
[Clone a GIT Project How To Instructions](https://servertribe-attune.readthedocs.io/en/latest/howto/design_workspace/clone_project.html).




## Blueprints

This Project contains the following Blueprints.



### Create CentOS8 BIOS Kickstart ISO

Creates a RHEL8 BIOS kickstart ISO.




## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Kickstarted Linux Node | Linux/Unix Node | `kickstartedlinuxnode` | Refers to the node being built. |
| Kickstarted Linux root User | Linux/Unix Credential | `kickstartedlinuxrootuser` | root user for "Kickstarted Linux Node". |
| Kickstarted Linux TimeZone | Text | `kickstartedlinuxtimezone` | Valid Linux timezones are listed in /usr/share/zoneinfo/posix and also at https://en.wikipedia.org/wiki/List_of_tz_database_time_zones.<br><br>Example: Australia/Brisbane |
| Kickstarted Node | Basic Node | `kickstartednode` |  |
| Kickstarted Subnet | Network IPv4 Subnet | `kickstartedsubnet` | Subnet used by the target server. |
| Kickstart Worker build Linux User | Linux/Unix Credential | `kickstartworkerbuildlinuxuser` | The user credentials for the node building the kickstart ISO.<br>Only for Kickstart Worker Linux Node. |
| Kickstart Worker Linux Node | Linux/Unix Node | `kickstartworkerlinuxnode` | Linux refers to both Linux and MacOS. |
| Kickstarted Disk First Letter | Text | `kickstarteddiskfirstletter` | The first letter of the disk in Linux, EG, sda or xda |
| Kickstart Worker Base Dir | Text | `kickstartworkerbasedir` | Base directory for deploying temporary files to build the kickstart ISO. |
| Kickstarted RPM Mirror Url | Text | `kickstartedrpmmirrorurl` |  |
| Kickstarted RPM CA Certificate | Text | `kickstartedrpmcacertificate` | RPM CA Certificate drop In directory. Place all RPM CA certificates that you want to use here.<br><br>This is an absolute path to a folder. <br><br>If it does not exist or if it is empty, then it will not be used. |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |
| CentOS8 Boot ISO | Large Archives |  |
| CentOS7 Net Install ISO | Large Archives |  |
| CentOS8 BIOS Kickstart Config | Version Controlled Files | Kickstart commands and options reference<br>https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/performing_an_advanced_rhel_8_installation/kickstart-commands-and-options-reference_installing-rhel-as-an-experienced-user<br><br>Kickstart Generator: https://access.redhat.com/labs/kickstartconfig/ |
| CentOS7 Minimal ISO | Large Archives |  |






# Contribute to this Project

**The collective power of a community of talented individuals working in
concert delivers not only more ideas, but quicker development and
troubleshooting when issues arise.**

If you’d like to contribute and help improve these projects, please fork our
repository, commit your changes in Attune, push you changes, and create a
pull request.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-pull-request-01.png" alt="pull request"/>

---

Please feel free to raise any issues or questions you have.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-02.png" alt="create an issue"/>


---

**Thank you**
