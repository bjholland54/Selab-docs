## Product Management

### Request for Enhancement

Process to improve how we manage Requests for Enhancement (RFE). It defines how we track, receive, evaluate, accept or reject requests from our customers.  **Support, Software Consultants** and **Technical Account Managers** will now complete a pre-submission form for customer requests and create an issue that Customer Support will use to open RFEs. This is important because RFEs will not be tracked or considered until an issue has been created.

1.  Open an ISSUE in Remedy OR on the BMC support web site

    * [Support website](http://www.bmc.com/available/submit-new-issue.html) requires a registered Customer Support ID

2. Ensure the following details are included in Issue Detail:

    * Primary company name and Product name

    * Enhancement Request:  

        * A Short summary

        * What specifically is being asked for in this request? Focus on the what, not the how.

        * What is the business need?  

    * Reason for Enhancement:  

        * Scenario: Give the business use case that illustrates why the request is important.  Include as much detail as possible to fully illustrate the background.

        * What is the challenge that initiated this request?

        * Why is this request needed?

        * How common would this enhancement be implemented/ utilized in your environment? (Seldom, Fairly regularly, Frequently)  

        * Would this feature improve the availability of any of your critical business applications/services? If so, please explain.

        * Would this feature improve the productivity of your IT department? If “yes” please identify which team(s) and how many team members would see productivity improvements
        from this feature.

    * Enhancement Details:

        * Details of how the Enhancement should be implemented.

        * Frequency: How frequent and pervasive is the situation that the proposed solution addresses?

    * Business Impact:  

        * Give the business impact of the current state contrasted with the future state after the enhancement in terms of hard dollar impact, if any, or other measureable improvements

        * tied back to Performance, Availability, Productivity or Risk Reduction.  

        * What is the impact if this is NOT implemented

3. After you submit your issue, Customer Support will respond to you with your RFE number for tracking purposes and then status update

### Just Do It Program

SEs can submit ideas for the Just Do It program via the [Just Do It web site UPDATE](https://bmcsoftware.sharepoint.com/Lists/SiteMigrationTracker/DispForm.aspx?ID=566)

Select Workload Automation on the left navigator (under Product Line) to see DBA ideas.

## Licensing

### Licensing - General

The below statement is official.  The below definition comes out of the MSM Pricing Handbook.  If a Rep ask you what is a task?  Please refer them to their MSM pricing handbook or send them the paragraph below.   For any price related question you can refer them to their MSM pricing handbook, which includes information about VM’s (counting sockets) and IFL (Integrated Facility for Linux).

From Tom Geva:   Tables and smart tables are NOT counted in our workload distribution and peak usage reports. The license definition is not very explicit regarding “containers” counting, but the general agreement was (and still is) that we should not count them..  

References:
* Enablement - [Control-M Licensing Overview](https://bmc.seismic.com/X5/#/doccenter/b865d66b-fe9c-49b7-bcad-4149d287f62e/doc/%252Fddc3232fcf-fce7-4cc4-87e1-6aad751f29d0%252Fdd99992505-a164-47e4-872c-f761bd6afe06%252Fdd1fc17667-aa70-4d6f-9729-87a4590fa7eb%252Fldbe4031c6-a17c-4ca4-b893-c09eccffa010%252Flde5b6a535-ac45-4028-a03d-d9a61c862b16%252Flfaefcb0d4-99cb-42d6-acff-a754dd543dfe//?mode=view&searchId=49654f73-c354-4977-abb9-9dbbc5b14cf9)

* [Introduction to License Compliance 112918](https://bmc.seismic.com/X5/#/doccenter/b865d66b-fe9c-49b7-bcad-4149d287f62e/doc/%252Fdd61b220ce-ebc8-4725-abae-3c23b4a58ed1%252Fdd533955fc-1812-429b-aa5b-4f8ef8b398e1%252Flf13002235-0cf3-49b3-8be5-5e8817420258//?mode=view&searchId=d238ee19-d792-4fc8-b996-b4dd645ff4a1)

### Task Licensing

The purpose of the below text is to aid the general use of the Control-M reporting tool.  
This below text in no way supersedes, replaces, or modifies your contract, which is the document that details
your Licensed Capacity and how it is counted.


How are tasks/jobs counted?
--------------------------------

•   The task count is based on the  total number of jobs present in  the Control –M “Active Jobs” databases  within any 24-hour period,
as further described in your contract.
This does not apply to customers who are licensed based on other units of measurement  such as MIPS, CPU, or tiers.

•   Tasks in the Control-M “Active Jobs” databases  refers to all Control-M tasks that are monitored by Control-M across all of your
Distributed Systems or Mainframe environments.
This includes development, staging, QA, pre-production, test, and production environments.

•   Tasks are counted regardless of whether they execute or not.

•   A task that runs more than once during the day (with the same Order ID) is counted as one task.  This includes tasks that are rerun
as well as cyclic tasks.

•   A single task that executes more than one script is counted as one task.

•   Tasks that have time zone settings may remain in the “Active Jobs” databases for up to three consecutive days, but are only counted
once as a single task.

•   Jobs that are ordered to run on a future date are counted every day the job resides in the “Active Jobs” database.

•   SMART folders/tables and sub-folders/tables, which contain scheduling definitions, and are listed as tasks in the “Active Jobs”
databases, are not counted as tasks.

### Server Endpoint Licensing

The purpose of the below text is to aid the general use of the Control-M reporting tool.
This below text is no way supersedes, replaces, or modifies your contract, which is the document that details your Licensed Capacity and how it is counted.

Server Endpoint Licensing

All machines upon which any Control-M component is installed or upon which Control -M managed workload runs must be licensed.
This includes Control-M Agent platforms onto which one or more application plug-ins are installed but also includes Control -M Agent
platforms where no application plug-ins are installed.

The licensing guidelines for application plug-ins are as follows:

•   ERP and BI/DI – The application server(s) upon which Control -M managed processes are executed should be licensed in
   addition to the Control -M Agent machine(s) (in some cases, this may be the same machine).

•   Databases – Each database server upon which Control -M managed database related processes are being executed should
   be counted in addition to the Control-M Agent machine(s).

•   AFT and MFT – Only the machine(s) upon which the AFT plug-in installed should be licensed.

•   Backup – The Control-M Agent machine(s) where the Backup plug-in installed and also the hosts which are running
   the backup server software should be licensed (note that this excludes the client machines for which the Backup Server software is
   managing actual backup processes except where a backup takes place of the backup server machine itself).

•   Cloud – only the Control -M Agent machine(s) upon which the plug-in is installed should be
   licensed.

•   Hadoop – All machines in each managed Hadoop Cluster should be licensed.
