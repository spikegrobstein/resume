# Spike Grobstein

    me@spike.cx       |  Cell: 908.803.8995     |  
    San Francisco, CA |  Web: spike.grobste.in  |  GitHub: spikegrobstein

> It is **NOT OK** to contact me regarding employment opportunies for either full-time or contract work.

## Selected Skills

 * Linux (Debian/Ubuntu/Gentoo), macOS, BeOS
 * Firewalls, Bind, Chef, nginx, Docker, Apache Webserver
 * PostgreSQL, MySQL, Redis, Marklogic Server
 * Bash (expert), Rust, Swift, Javascript/Typescript, Applescript, Ruby, C, Python, PHP, XQuery, plpgsql, ObjC, Perl, Java
 * Offset printing, color separations, color correction, screenprinting, embroidery
 * Certified Expert in Adobe Photoshop and Illustrator.

## Experience
**Apple Inc** - Cupertino, CA - Hardware and Software

* 2015-01 - 2021/10 / Frontend Operations Engineer
* 2021-10 - present / Frontend Operations Architect

**Shutterstock** - New York, NY - Stock photo/video/audio platform

* 2013/08 - 2015/01 / Infrastructure Engineer

As a member of the Infrastructure team, besides typical day-to-day tasks and being part of the on-call rotation, I contributed personally in the following areas:

* Led training sessions for teaching systems engineers Ruby and other programming skills so they could be more effective at contributing to our projects
* Built interactive map frontend webapp for finding and navigating the new office, helping folks find each other and conference rooms more easily
* Maintained Puppet manifests for > 3000 node production/qa/dev infrastructure
* Architected and built prototype Configuration Management DB + Chef cookbook collection including API design, server and client libraries with distributed, multi-datacenter ElasticSearch backend
* Rewrote Deployment Ruby/Sinatra/EventMachine service to enable faster, safer deployments by improving error detection, untangling async code and rework code that blocked the event loop
* Built interactive TUI to Neon - our Dashboard/alert system in Ruby + Curses to improve the experience for engineers. We could see these alerts from a terminal instead of requiring looking up at TVs or opening a web browser

**Ticket Evolution** - Jersey City, NJ - SaaS provider for online event ticket sales  

* 2012/01 - 2013/08 / Sr DevOps Engineer

The sole systems engineer, I maintained the infrastructure and configuration that powered our platform, ensuring maxiumum uptime, consistent deployments, responsive API and easy access for developers to troubleshoot errors.

 * Profiled and optimized API through better SQL queries and better Ruby code
 * Refactored inventory importer to properly handle UTF8 and improve import performance dramatically
 * Led migration of production site from pure AWS infrastructure to local datacenter
 * Architected and implemented infrastructure in new environment with new deployment tools
   (custom Capistrano recipes for deployment and other common tasks), monitoring (scoutapp.com) and
   configuration management (Chef).
 * Built Scout plugins in Ruby for monitoring unsupported processes and services including alerts for
   customer balance tracking and internal Postgres metrics
 * Built Resque plugin (with monkey-patched Resque) for monitoring queue latency. Latency is defined as
   how long it took the last job in the queue to run from the time it was queued.

**Warner Music Group** - New York City, NY - Major Record Label  
2007/08 - 2011/12 / Digital Technology Architect

 * Architected and implemented application for collecting and reporting on data from the internet using
   Kapow, PHP (wrappers for collection agents), Rails (Frontend/CnC/Reporting), MySQL (orchestration
   datastore), Marklogic (online datastore), NEC HYDRAstor (offline/nearline storage of collected data).
   Collected and processed over 500GB of XML over a 2-year period. Application paid for itself over the
   first month of operation.
 * Investigated and reverse engineered software for applications and services designed for copyright
   infringement (eg: Limewire, etc) to determine risk, technologies and extent of violations.
 * Described and implemented procedures for configuring and managing video encoding server farm of XServes;
   built scripts to manage/audit versions of libraries and initial configuration of servers using Ruby,
   designed and documented procedures for NetRestore of servers for disaster recovery.

**National Flag & Display** - New York City, NY - Flag and Banner production company  
2004/08 - 2007/08 / Production Artist

 * Automated Art Department workflows using combination of Perl, Bash and Applescript saving each artist
   hours per day and overall improving life in the art department. Automation included procedures for
   preflighting and sending files to vendors (tagging, building PO and composing emails or burning CDs/DVDs).
 * Built FTP server for customers to upload artwork using Gentoo Linux. Included log parser (written in
   Perl) to notify of new uploads, seamless integration to their website with a web frontend for uploading
   files and including custom messages to the appropriate salesperson. Server ran for over 3 years
   unattended.
 * Redesigned and built the company's website using PHP and my own custom templating engine which
   brought in several dozen new orders per month over the first year it was up.
 * Built software for parsing, reporting and pointing out errors in EZPass statements for a subsidiary
   trucking company. Scraped EZPass website using Perl into CSV, built reports in Excel using VBA.

**Purnell School** - Pottersville, NJ - Alternative Girls Boarding High School  
2006/03 - 2012/10 / Contract Engineer

 * Designed and implemented ESX Server for hosting internal applications, consolidating 8 physical
   servers into a single unit.
 * Built a web application for tracking merits (points) of the students with dashboard so they can
   redeem them for prizes. Application was builtin Ruby on Rails with integration into ActiveDirectory
   authentication server using an LDAP gem. Supported over 250 users.
 * Implemented Moodle for student course management and homework tracking that tied into the same
   ActiveDirectory authentication server as the Merits app.
 * Built application in PHP that would seamlessly tie into Moodle and Merits to ease import of
   new student accounts via CSV file.
 * All above sites used the same look and feel as the school's intranet, leveraging modern HTML and
   CSS techniques and sharing templates and graphical assets.

*Additional Experience available on request*

## Noteworthy Side Projects

**Flatiron School** - `http://www.flatironschool.com`  
I've been invited for 4 consecutive classes to give a guest lecture on basic Linux systems administration
and application deployment. Lecture outline is available on my GitHub profile.

**mcwrapper** - `https://github.com/spikegrobstein/mcwrapper`  
A full-featured commandline tool built in Bash for managing a Minecraft Server. Wraps Minecraft Server
Java exectuable to enable offline commands using a FIFO and safe, atomic world data backups and restores.

**capistrano-mailgun** - `https://github.com/spikegrobstein/capistrano-mailgun`  
A Rubygem for sending notifications for Capistrano deployments via the Mailgun API.

**nesromtool** - `https://github.com/sadistech/nesromtool`  
A commandline tool built in C for hacking Nintendo (NES) ROMs. Cleanroom implementation from publically
available documentation. Allows one to replace programming or image content in ROMs.

**gcmtool** - `https://github.com/sadistech/gcmtool`  
A commandline tool built in C for hacking GameCube (GCM) ROMs. Mostly cleanroom implementation from
publicly available documentation. Involved some reverse engineering for unknown portions. Allows one
to read/write the filesystem of a ROM and extract/replace bootloader.

*Additional information available upon request*
