# SCOMLinkLibrary
SCOM-realted Link Collection


# Tabel of Content:

- [Core Concepts](#core-concepts)
- [Planning and Sizing](#planning-and-sizing)
- [Agent Management](#agent-management)
- [Notifications and Alerts](#notifications-and-alerts)
- [Authoring](#authoring)
- [Advanced Monitoring and Group Management](#advanced-monitoring-and-group-management)
- [Tasks](#tasks)
- [Secutity](#secutity)
- [Registry Tweaks and SQL Queries](#registry-tweaks-and-sql-queries)
- [Grooming and Retention](#grooming-and-retention)
- [Recource pools](#recource-pools)
- [APM](#apm)
- [Powershell](#powershell)
- [Miscellaneous Tools and Resources](#miscellaneous-tools-and-resources)
- [Relevant SCOM-Blogs](#relevant-scom-blogs)

---

## Core Concepts

1.  **System Center Operations Manager (SCOM) Key Concepts**

    > Overview of key concepts in SCOM, including management packs, monitoring, and tasks.
    > - [(Info) SCOM Key Concepts (learn.microsoft.com)](https://learn.microsoft.com/en-us/system-center/scom/key-concepts?view=sc-om-2022)

1.  **Sealed vs Unsealed Management Packs**

    > General Info about Sealed and Unsealed Management Pack Files
    > - [(Info) Sealed and Unsealed Management Packs(learn.microsoft.com)](https://learn.microsoft.com/en-us/previous-versions/system-center/system-center-2012-r2/hh457560(v=sc.12)#sealed-and-unsealed-management-pack-files)

    > Explanation of sealed and unsealed management packs, their uses, and best practices. - **Seal MP**
    > - [(LabGuide) Seal MP (learn.microsoft.com)](https://learn.microsoft.com/en-us/system-center/scsm/seal-mp?view=sc-sm-2022)

    > **Howto Create KeyPair**:
    > - [(LabGuide) Create public private key pair (learn.microsoft.com) ](https://learn.microsoft.com/en-us/dotnet/standard/assembly/create-public-private-key-pair)

    > **SN.exe (Strong Name Tool)**:
    > - [(Info) SN.exe (Strong Name Tool) (learn.microsoft.com)](https://learn.microsoft.com/en-us/dotnet/framework/tools/sn-exe-strong-name-tool)

1.  **Objects and Classes in SCOM**

    > Guidance on creating monitoring using target classes that fit specific needs:
    > - [(Info) Objects and Classes (learn.microsoft.com)](https://learn.microsoft.com/en-us/previous-versions/system-center/system-center-2012-r2/hh457568(v=sc.12))

1.  **Management Pack Templates**

    > Information on using templates for creating management packs:
    > - [(Info) MP Templates (learn.microsoft.com)](https://learn.microsoft.com/en-us/previous-versions/system-center/system-center-2012-r2/hh457614(v=sc.12))

1.  **Monitors and Rules**

    > Details on creating and managing monitors and rules in SCOM:
    > - [(Info) Monitors and Rules (learn.microsoft.com)](https://learn.microsoft.com/en-us/previous-versions/system-center/system-center-2012-r2/hh457603(v=sc.12))

    > Identify Windows-Server Performance Metric to create SCOM-Monitoring based on the counters identified:
    > - [(LabGuide) Get relevant Performance Counter (learn.microsoft.com)](https://learn.microsoft.com/en-us/training/modules/monitor-windows-server-performance/?source=recommendations)

1.  **Tasks Authoring**

    > Information on authoring tasks in SCOM:
    > - [(Info) Tasks Authoring (learn.microsoft.com)](https://learn.microsoft.com/en-us/previous-versions/system-center/system-center-2012-r2/hh457605(v=sc.12))


---

## Planning and Sizing

1.  **Planning for SCOM**

    > Comprehensive guide on planning for SCOM deployment:
    > - [(Info) Planning Overview (learn.microsoft.com)](https://learn.microsoft.com/en-us/system-center/scom/plan-overview?view=sc-om-2022)

1.  **SCOM Sizing Helper Tool**
    > Tool for determining the appropriate size for SCOM deployments:
    > - [(LabGuide) Sizing Helper Tool (techcommunity.microsoft.com)](https://techcommunity.microsoft.com/t5/system-center-blog/operations-manager-2012-sizing-helper-tool/ba-p/345075) 
    > - [(Download) Sizing Helper Tool Download (microsoft.com)](https://download.microsoft.com/download/C/A/6/CA60425C-950B-456E-986C-C5F2FCD5668D/System%20Center%202012%20Operations%20Manager%20Sizing%20Helper%20Tool%20v1.xls)

---

## Agent Management

1. **Enable Proxy as a default setting (SCOM 2012 - 2019)**

   > - [(LabGuide) Enable Proxy as a default setting in SCOM 2016 (kevinholman.com)](https://kevinholman.com/2017/03/10/enable-proxy-as-a-default-setting-in-scom-2016/)

1. **Get Agents back remotely manageable**

   > - [(LabGuide) how to get your agents back to remotely manageable in scom (kevinholman.com)](https://kevinholman.com/2010/02/20/how-to-get-your-agents-back-to-remotely-manageable-in-scom/)

1. **How to upgrade and update SCOM Agents using Tasks**

   > - [(LabGuide) Upgrade and Update SCOM Agents (kevinholman.com)](https://kevinholman.com/2022/04/22/how-to-upgrade-and-update-scom-agents-using-tasks/)

1. **Automating SCOM maintenance-mode for agents assigned to a gateway, when their gateway is unavailable**

   > - [(LabGuide) Automating Maintenance Mode (kevinholman.com)](https://kevinholman.com/2022/01/04/automating-scom-maintenance-mode-for-agents-assigned-to-a-gateway-when-their-gateway-is-unavailable/)

1. **Assigning gateways and agents to management servers using PowerShell**

   > - [(LabGuide) Assigning Gateways and Agents (kevinholman.com)](https://kevinholman.com/2018/08/06/assigning-gateways-and-agents-to-management-servers-using-powershell/)

1. **Reinstalling your SCOM agents with the NoAPM switch**
   > - [(LabGuide) Reinstalling SCOM Agents (kevinholman.com)](https://kevinholman.com/2017/08/05/reinstalling-your-scom-agents-with-the-noapm-switch/)

---

## Notifications and Alerts

1.  **Creating Notification Subscriptions**

    > Guide on setting up notification subscriptions in SCOM:
    > - [(LabGuide) Notification Subscriptions (learn.microsoft.com)](https://learn.microsoft.com/en-us/system-center/scom/manage-notifications-create-subscriptions?view=sc-om-2022)

1.  **Customizing Notification Messages**
    > Instructions for customizing the content of notification messages:
    > - [(Info) Customize Notification Messages (learn.microsoft.com)](https://learn.microsoft.com/en-us/system-center/scom/manage-notificiations-customize-message?view=sc-om-2022)

---

## Authoring

1.  **ManagementPack Baseline Automation**

    > This process is designed to save you a significant amount of time by fully automating the baselining procedure:
    > - [(LabGuide) ManagementPack Baseline Automation (thegermanscomguys.com)](https://thegermanscomguys.com/posts/mp-baseline-automation/)

1.  **Visual Studio Authoring Extensions**

    > Tools and extensions for authoring management packs using Visual Studio:
    > - [(Download) Visual Studio Authoring Extensions Download (microsoft.com)](https://www.microsoft.com/en-us/download/details.aspx?id=104504)

1.  **Create a new ManagementPack Project (7-Step-Guide)**

    > Detailed Guide to create new ManagementPack Projects in seven steps by Kevin Holman:
    > - [(LabGuide) Use VSAE to create a new managementpack project (kevinholman.com)](https://kevinholman.com/2016/06/04/part-1-use-vsae-to-create-a-new-management-pack-project/)

1.  **Using Combo-Fragments**
    > - [(LabGuide) MP Authoring with Fragments (kevinholman.com)](https://kevinholman.com/2019/01/17/mp-authoring-with-fragments-introducing-combo-fragments/)

---

## Advanced Monitoring and Group Management

1.  **Distributed Application Monitoring**

    > Techniques for monitoring distributed applications in SCOM:
    > - [(LabGuide) Distributed Application Monitoring (learn.microsoft.com)](https://learn.microsoft.com/en-us/previous-versions/system-center/system-center-2012-r2/hh457612(v=sc.12))

1.  **Creating and Managing SCOM Groups**
    > Detailed guide on creating and managing groups in SCOM:
    > - [(LabGuide) Authoring SCOM Groups (kevinholman.com)](https://kevinholman.com/2010/07/27/authoring-scom-groups-from-simple-to-complex/)

---

## Tasks
1. Automate Tasks
	> Guide to automate Tasks (scheduling, execute any powershell, override)
	> - [(LabGuide) PS Task (thegermanscomguys.com)](https://thegermanscomguys.com/posts/ps-task/)

---

## Secutity

1.  **Log on as a Service**

    > Detailed guide on Log on as a Service
    > - [(LabGuide) Log on as a Service 2019 (kevinholman.com)](https://kevinholman.com/2019/03/14/security-changes-in-scom-2019-log-on-as-a-service/)
    > - [(LabGuide) Log on as a Service 2022 (learn.microsoft.com)](https://learn.microsoft.com/en-us/system-center/scom/enable-service-logon?view=sc-om-2022)

1.  **Run as accounts and profiles**
    > Detailed guide on configuring run as Accounts in SCOM
    > - [(LabGuide) Configuring run as accounts and profiles in opsmgr a sql management pack example (kevinholman.com)](https://kevinholman.com/2010/09/08/configuring-run-as-accounts-and-profiles-in-opsmgr-a-sql-management-pack-example/)
    > - [(LabGuide) SQL MP run as accounts no longer required (kevinholman.com)](https://kevinholman.com/2016/08/25/sql-mp-run-as-accounts-no-longer-required/)

---

## Registry Tweaks and SQL Queries

1.  **Recommended Registry Tweaks for SCOM 2016**

    > Best practices for registry tweaks to optimize SCOM performance:
    > - [(Info) Registry Tweaks (kevinholman.com)](https://kevinholman.com/2017/03/08/recommended-registry-tweaks-for-scom-2016-management-servers/)

1.  **SCOM SQL Queries**
    > Useful SQL queries for managing and troubleshooting SCOM:
    > - [(Info) SQL Queries (kevinholman.com)](https://kevinholman.com/2016/11/11/scom-sql-queries/)

## Grooming and Retention

1.  **Grooming Tool**

    > Download System Center Operations Manager - Data Warehouse Grooming Tool
    > - [(Download) Grooming Tool (blakedrumm.com)](https://blakedrumm.com/blog/scom-dw-grooming-tool/)

1.  **Grooming Settings**
    > Configure Grooming Settings
    > - [(Info) Manage OMDWDB grooming settings (microsoft.com)](https://learn.microsoft.com/en-us/system-center/scom/manage-omdwdb-grooming-settings?view=sc-om-2022)
1.  **Grooming and Retention of Data Warehouse**

    > Nice guide from Kevin Holeman to understand Grooming an Retention of Data Warehouse
    > - [(LabGuide) Understanding Data Warehouse Retention and Grooming (kevinholman.com)](https://kevinholman.com/2010/01/05/understanding-and-modifying-data-warehouse-retention-and-grooming/)


---

## Recource pools

1.  **Understanding Recource Pools**
    > Infos about recouce Pools and their benefits
    > - [(Info) Understanding SCOM resource pools (microsoft.com)](https://kevinholman.com/2016/11/21/understanding-scom-resource-pools/)

---

## APM

1.  **Monitoring .NET Applications**
    > Monitoring .NET Applications
    > - [(Info) Monitoring .NET Applications (microsoft.com)](https://learn.microsoft.com/en-us/previous-versions/system-center/system-center-2012-R2/hh212856(v=sc.12))
		
1.  **SCOM as an APM tool**
    > Video how to use SCOM as an APM Tool
    > - [(Info) SCOM as an APM tool (youtube.com)](https://www.youtube.com/watch?v=xvYy1pYAhSU&t=2s)
		
1.  **Working with the Application Diagnostics console**
    > Article with informations about working with Application Diagnostics console
    > - [(Info) Manage working with the application diagnostics console (learn.microsoft.com)]( https://learn.microsoft.com/en-us/system-center/scom/manage-working-with-the-application-diagnostics-console?view=sc-om-2022)

---

## Powershell

1.  **OpsMgrExtended PowerShell Module**
    > PowerShell module for SCOM
    > - [(Download) OpsMgrExtended Module (github.com)](https://github.com/tyconsulting/OpsMgrExtended-PS-Module/tree/master)

1.  **Get Operationsmanager-Module without Console installed**
    > Nice Guide on installing SCOM PS Modules without console by Stefan Roth
    > - [(LabGuide) install-scom-powershell-modules-without-scom-console-installation (stefanroth.net)](https://www.stefanroth.net/2013/03/13/scom-2012-install-scom-powershell-modules-without-scom-console-installation/)

1.  **SCOM - Management Pack Creator**
    > - [(Info) Build management packs in a matter of seconds! (walshamsolutions.com)](https://www.walshamsolutions.com/scom-management-pack-creator-official-version-released)


1.  **Useful SCOM powershell scripts**
    > Guide with useful powershell script
    > - [(LabGuide)10 useful SCOM powershell scripts (cookdown.com)](https://www.cookdown.com/blog/10-useful-scom-powershell-scripts)

1.  **Some nice PS Scripts**
    > Scripts to have a look at
    > - [(Info) sepaugh PS-Library (github.com)](https://github.com/sepaugh/SCOM/tree/main)


---

## Miscellaneous Tools and Resources

1.  **SCOM Tools by Kevin Holman**
    > Collection of tools and scripts for managing SCOM:
    > - [(Info) SCOM Tools (kevinholman.com)](https://kevinholman.com/2018/12/30/scom-tools/)

1.  **MP Viewer**
    > Tool for viewing and analyzing management packs:
    > - [(Download) MP Viewer (github.com)](https://github.com/JeanCloud365/mpviewer)

1.  **SCOM Management MP**
    > Guide on how to use Management MP by Kevin Holman
    > - [ (LabGuide) SCOM management MP making a SCOM admins life a little easier (kevinholman.com)](https://kevinholman.com/2017/05/09/scom-management-mp-making-a-scom-admins-life-a-little-easier/)
    > - [(Info/Download) SCOM.Management collection (github.com)](https://github.com/thekevinholman/SCOM.Management)

1.  **SystemCenter Wiki**

    > Huge Catalogue of Management Packs used in SCOM and SCSM:
    > - [(Info) SystemCenter Wiki (systemcenter.wiki)](https://systemcenter.wiki/)

1.  **Install SCOMHelper**
    > How to install SCOMHelper from Gallery
        	[(LabGuide) SCOMHelper InstallFromGallery (monitoringguys.com)](https://monitoringguys.com/2019/11/12/scomhelper/#InstallFromGallery)

1.  **Deleting and purging Data from DB**
    > Guide to learn how to delete or purge data from Databases
        [(LabGuide) Deleting and purging data from the SCOM database (kevinholman.com)](https://kevinholman.com/2018/05/03/deleting-and-purging-data-from-the-scom-database/)

---

## Relevant SCOM-Blogs

> > [Kevin Holman (kevinholman.com)](https://kevinholman.com/)
> > 
> > [Kevin Justin (kevinjustin.com)](https://kevinjustin.com/blog/)
> > 
> > [Cookdown (cookdown.com)](https://www.cookdown.com/blog)
> > 
> > [SCOMSkills (blog.scomskills.com)](http://blog.scomskills.com/)
> > 
> > [Topqore (blog.topqore.com)](https://blog.topqore.com/)
> > 
> > [MaxCoreBlog (maxcoreblog.com)](https://maxcoreblog.com/)
> > 
> > [AzureCloudAI (azurecloudai.blog)](https://azurecloudai.blog/?s=scom)
> > 
> > [Sourav Mahato (souravmahato.com)](https://www.souravmahato.com/category/scom/)
> > 
> > [Stefan Roth (stefanroth.net)](https://www.stefanroth.net/?s=scom/)
> > 
> > [AnalyticOps (anaops.wordpress.com)](https://anaops.wordpress.com/category/scom/)

Created by [TheGermanSCOMGuys](https://thegermanscomguys.com)

---

