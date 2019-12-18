## Sales Processes

Product Account Managers (PAMs) need to be involved on all opportunities

The Control-M PAMs must be made aware of all your activities.  The PAMs are supposed to work with the Account Managers on any and all Control-M related opportunities, including ELO’s as there is a play for maximizing the value of Platform licensing.  If your time is requested to work on a CTM opportunity by a non CTM PAM, please direct them to your manager, or ask which CTM PAM is working on this opportunity and then notify that PAM.

Tier 5 – Contact your Manager before agreeing to work on a Tier 5 account. Provide SFDC #.

## Value Selling

### PreSales Engegement Model
![](../images/presales_engag.png)

### Enablement Qualification
![](../images/enable_qual.png)

### Sales Stages
![](../images/sales_stages.png)

## Content

### Control-M Sales Plays
[ISD Sales Plays](https://bmc.seismic.com/X5/#/doccenter/b865d66b-fe9c-49b7-bcad-4149d287f62e/doc/%252Fdd599dfb25-e177-448f-ba18-1a1f5ee6491c%252FdfMTJlMDgxZjAtNjFlMC00NzFkLTg2ZWMtYjg5YjljOWQ0MTI0%252CPT0%253D%252CRVNP%252Flf4e95ec71-ad84-41bc-85a9-1fb2f69b5adc//?mode=view&searchId=fa6e3054-aaac-4b15-852d-bbb7a9e10be8)

1. IT Operations (Traditional Scheduling, IT Ops, and ERPs)

2. File Transfers

3. Data (Big Data, BI, Databases)

4. Application Development (App Dev, DevOps, Jobs-As-Code)

5. Cloud

6. CA / Broadcom Replace

### Control-M Sales Guide
Control-M Sales Guide can be found [here](https://bmcapps.my.salesforce.com/sfc/#search?searchTerm=%22sales%20guide%22)

### SFDC Content

Control-M Sales Collateral conten is in SFDC  under “Content”  Module

* If you don’t see it on the Top line of SFDC, look to the right for the + sign and click on it.  If you still don’t have it, open a service desk ticket and ask for access to the “Content” Module.

![](../images/content.png)

![](../images/content1.png)

* To set up permanently, use the "Customize My Tabs" button on that last page

![](../images/content2.png)

![](../images/content3.png)

* Click on add and move to your desired location

### Licensing

#### Task Licenses
**License Question – Official**

The below statement is official.  The below definition comes out of the MSM Pricing Handbook.  If a Rep ask you what is a task?  Please refer them to their MSM pricing handbook or send them the paragraph below.   For any price related question you can refer them to their MSM pricing handbook, which includes information about VM’s (counting sockets) and IFL (Integrated Facility for Linux).

Until a time where the EMminer can be adjusted, I would recommend having the customers use the Extreme Peak Usage report.  If on version 6.2 or below have them run the EMminer but ask if they use Group scheduling and let them know they will have to deduct them from the total count.

We will move out of the task count game in due time as the product & license packages (i.e., BAP, Simplify) are assisting in that effort.  You may or may not be aware, there is an initiative going on to do this very thing.  Moving slowly, but it has been moving in the right direction.  Until then we will continue to assist as best we can since pertains to bringing in revenue, which is part of being a Pre-Sales SC.

From Tom Geva:   Tables and smart tables are NOT counted in our workload distribution and peak usage reports. The license definition is not very explicit regarding “containers” counting, but the general agreement was (and still is) that we should not count them.


* per task

        LICENSE DEFINITION: A license is required for the maximum number of Tasks
        (as defined below) loaded into the daily CONTROL-M Active Environment in a
        24-hour period, excluding any tasks that are provided for by licenses under
        alternative Units of Measure (i.e. tier or MIPS).  A loaded task refers to
        all Control-M Tasks that are monitored by Control-M in all environments
        (including but not limited to development, staging, QA, pre-production,
        production, and test environments). This includes all Control-M environments
        on Distributed Systems and/or Mainframe installations. The number of steps or
        scripts executed within the named Task shall have no bearing upon the number
        of Tasks licensed – the sum total of the commands constitutes a single Task. 
        For CONTROL-M: licensed tasks equal the maximum number of Tasks loaded into the
        daily CONTROL-M Active Environment. For Control- M mainframe add-on products
        (Control-M/Analyzer, Control-O, Control-M Links for z/OS, Control-M/Restart,
        Control-M/Tape, or Control-M Mainframe Extension Pack), Licensed Tasks equal
        that of the Licensed Capacity of or managed by Customer’s mainframe Active Environment. 
        For all other Task based Products, the maximum number of Tasks that the Product
        is priced against, is measured as the maximum number of CONTROL-M Tasks.  “Task”
        means an executable command  containing the name of the JCL, CL, DCL, ECL, script
        or dummy processes that will execute as well as the scheduling criteria, flow
        control, resource usage.

        STATEMENT OF CAPACITY INFORMATION: List the highest aggregate number of Tasks
        loaded into the daily CONTROL-M active environment in a 24-hour period during the
        Measured Period, with the highest aggregate number of Tasks per Product referred to
        as the “Reported Capacity”.

#### CPU Licensing

Below is some general guidance around CPU licensing across all Control-M components.

General Rule:  All machines upon which any Control-M component is installed or upon which Control-M managed workload runs must be licensed. This includes Control-M Agent platforms onto which one or more CMs are installed but also includes Control-M Agent platforms where no CMs are installed.

The license rules for CMs vary according to differing types of CM as follows:-

* ERP CMs and BI/DI CMs.  The application server(s) upon which Control-M managed processes are executed should be licensed in addition to the Control-M Agent machine(s) (in some cases, this may be the same machine).

* CM for Databases – Each database server upon which Control-M managed database related processes are being executed should be counted in addition to the Control-M Agent machine(s).

* CM for AFT – Only the machine(s) upon which the AFT CM is installed should be licensed.

* CM for BPI – This offering consists of 3 CMs, these being Web services, Messaging and Java. Licensing requirements for these differ as follows:-  

* For the Web Services & Messaging CM components only the Control-M Agent machine(s) upon which the CM is installed should be licensed.

* For the Java  CM component, two types of jobs are available:-

    1. Java Beans - no Java application server is required and therefore only the relevant Control-M Agent machine(s) should be licensed.

    2. Java EJB – Java application server(s) required and therefore both the Control-M Agent machine(s) and the Java application Server machine(s) need to be licensed (it is possible that in some situations these may be the same machines).

* CM for Backup – The Control-M Agent machine(s) where the Backup CM is installed and also the hosts which are running the backup server software should be licensed (note that this excludes the client machines for which the Backup Server software is managing actual backup processes except where a backup takes place of the backup server machine itself).  

* CM for Cloud – This offering consists of 3 CMs, these being VMWare, BMC Blade Logic, Amazon) – in all 3 cases only the Control-M Agent machine(s) upon which the CMs are installed should be licensed.

* Hadoop – All machines in each managed Hadoop Cluster should be licensed.

### BMC Education

[BMC Business School Control-M](https://www.bmc.com/education/courses/control-m-training.html?intcmp=redirect_education_lpctrlm) learning path  
